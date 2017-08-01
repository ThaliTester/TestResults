#### Test 113351851520d16b_iOS_Iphone6sPlus-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/113351851520d16b/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6s Plus 'Iphone6sPlus-1' (f70cda60583ea0f895d05ea355cd125983c27594) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/6ADE8D0D-43C4-4191-BEE0-B7C951229E7C/fruitstrap-lldb-prep-cmds-f70cda60583ea0f895d05ea355cd125983c27594'
,Executing commands in '/tmp/6ADE8D0D-43C4-4191-BEE0-B7C951229E7C/fruitstrap-lldb-prep-cmds-f70cda60583ea0f895d05ea355cd125983c27594'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/113351851520d16b/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/113351851520d16b/build_ios/ThaliTest.app' (arm64).
,(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/BF341FD4-5CD1-49B1-AA89-1A7C118CC8E9/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55183"
,(lldb)     command script import "/tmp/6ADE8D0D-43C4-4191-BEE0-B7C951229E7C/fruitstrap_f70cda60583ea0f895d05ea355cd125983c27594.py"
,(lldb)     command script add -f fruitstrap_f70cda60583ea0f895d05ea355cd125983c27594.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_f70cda60583ea0f895d05ea355cd125983c27594.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_f70cda60583ea0f895d05ea355cd125983c27594.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_f70cda60583ea0f895d05ea355cd125983c27594.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-08-01 11:26:09 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-01 11:26:09 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-01 11:26:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:26:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:26:09 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:26:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
2017-08-01 11:26:09 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
,AppContextTests.test_didEnterForeground finished
,AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
AppContextTests.test_esonValue finished
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "02D55E9F-CDFB-488F-A4E7-50B6E2C5A805", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:02D55E9F-CDFB-488F-A4E7-50B6E2C5A805
,Optional(true)
Optional(false)
,AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:28E39F09-BF4F-4B3B-952F-666BA702B8BA
[ThaliCore] Browser,.startListening
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:B6F40950-,D2E6-4059-B215-14DA80E6F79B
[ThaliCore] Browser.startListening
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "D866FD41-50EC-43F2-ADB1-40A3577F3C7C", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:D866FD41-50EC-43F2-ADB1-40A3577F3C7C
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D866FD41-50EC-43F2-ADB1-40A3577F3C7C:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D866FD41-50EC-43F2-ADB1-40A3577F3C7C", generation: 0)
,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
AppContextTests.test_connectReturnValueCo,rrect finished
AppContextTests finished
All tests finished
All tests finished
,2017-08-01 11:26:10 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
Number of passed tests:  13
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  1.306062996387482
,2017-08-01 11:26:10 - DEBUG UnitTest_app: 'My device name is: 'Apple-Iphone6sPlus-1''
,2017-08-01 11:26:10 - WARN testUtils: 'myNameCallback not set!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:D866FD41-50EC-43F2-ADB1-40A3577F3C7C:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "D866FD41-50EC-43F2-ADB1-40A3577F3C7C", generation: 0)
,2017-08-01 11:26:12 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-08-01 11:26:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BF341FD4-5CD1-49B1-AA89-1A7C118CC8E9/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-08-01 11:26:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BF341FD4-5CD1-49B1-AA89-1A7C118CC8E9/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-08-01 11:26:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BF341FD4-5CD1-49B1-AA89-1A7C118CC8E9/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-08-01 11:26:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BF341FD4-5CD1-49B1-AA89-1A7C118CC8E9/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-08-01 11:26:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BF341FD4-5CD1-49B1-AA89-1A7C118CC8E9/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-08-01 11:26:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BF341FD4-5CD1-49B1-AA89-1A7C118CC8E9/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-08-01 11:26:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BF341FD4-5CD1-49B1-AA89-1A7C118CC8E9/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-08-01 11:26:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BF341FD4-5CD1-49B1-AA89-1A7C118CC8E9/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-08-01 11:26:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BF341FD4-5CD1-49B1-AA89-1A7C118CC8E9/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-08-01 11:26:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BF341FD4-5CD1-49B1-AA89-1A7C118CC8E9/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-08-01 11:26:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BF341FD4-5CD1-49B1-AA89-1A7C118CC8E9/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-08-01 11:26:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BF341FD4-5CD1-49B1-AA89-1A7C118CC8E9/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-08-01 11:26:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BF341FD4-5CD1-49B1-AA89-1A7C118CC8E9/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-08-01 11:26:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BF341FD4-5CD1-49B1-AA89-1A7C118CC8E9/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-08-01 11:26:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BF341FD4-5CD1-49B1-AA89-1A7C118CC8E9/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-08-01 11:26:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BF341FD4-5CD1-49B1-AA89-1A7C118CC8E9/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-08-01 11:26:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BF341FD4-5CD1-49B1-AA89-1A7C118CC8E9/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-08-01 11:26:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BF341FD4-5CD1-49B1-AA89-1A7C118CC8E9/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-08-01 11:26:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BF341FD4-5CD1-49B1-AA89-1A7C118CC8E9/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-08-01 11:26:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BF341FD4-5CD1-49B1-AA89-1A7C118CC8E9/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-08-01 11:26:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BF341FD4-5CD1-49B1-AA89-1A7C118CC8E9/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-08-01 11:26:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BF341FD4-5CD1-49B1-AA89-1A7C118CC8E9/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-08-01 11:26:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BF341FD4-5CD1-49B1-AA89-1A7C118CC8E9/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-08-01 11:26:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BF341FD4-5CD1-49B1-AA89-1A7C118CC8E9/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-08-01 11:26:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BF341FD4-5CD1-49B1-AA89-1A7C118CC8E9/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-08-01 11:26:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BF341FD4-5CD1-49B1-AA89-1A7C118CC8E9/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-08-01 11:26:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BF341FD4-5CD1-49B1-AA89-1A7C118CC8E9/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-08-01 11:26:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BF341FD4-5CD1-49B1-AA89-1A7C118CC8E9/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-08-01 11:26:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BF341FD4-5CD1-49B1-AA89-1A7C118CC8E9/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-08-01 11:26:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BF341FD4-5CD1-49B1-AA89-1A7C118CC8E9/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-08-01 11:26:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BF341FD4-5CD1-49B1-AA89-1A7C118CC8E9/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-08-01 11:26:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BF341FD4-5CD1-49B1-AA89-1A7C118CC8E9/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-08-01 11:26:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BF341FD4-5CD1-49B1-AA89-1A7C118CC8E9/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-08-01 11:26:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BF341FD4-5CD1-49B1-AA89-1A7C118CC8E9/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-08-01 11:26:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BF341FD4-5CD1-49B1-AA89-1A7C118CC8E9/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-08-01 11:26:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BF341FD4-5CD1-49B1-AA89-1A7C118CC8E9/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-08-01 11:26:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BF341FD4-5CD1-49B1-AA89-1A7C118CC8E9/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-08-01 11:26:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BF341FD4-5CD1-49B1-AA89-1A7C118CC8E9/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-08-01 11:26:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BF341FD4-5CD1-49B1-AA89-1A7C118CC8E9/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-08-01 11:26:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BF341FD4-5CD1-49B1-AA89-1A7C118CC8E9/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-08-01 11:26:14 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-08-01 11:26:14 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
,2017-08-01 11:26:14 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
,# setup
,# closeAll can close even when connections open
,2017-08-01 11:28:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 1 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll with promise
,2017-08-01 11:28:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 2 not possible to connect to the server anymore
# teardown
,# setup
,# closeAll properly throws when closing a non open server with eatNotRunning set to false
,2017-08-01 11:28:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
# teardown
,# setup
,# closeAll works even with a server that is not listening yet witheatNotRunning set to true
,2017-08-01 11:28:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
,# setup
,# Call of onCheckpointReached handler on a single db change
,2017-08-01 11:28:30 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on a single db change''
,# teardown
,# setup
,# Call of multiple onCheckpointReached handlers on a single db change
,2017-08-01 11:28:31 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of multiple onCheckpointReached handlers on a single db change''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
,2017-08-01 11:28:33 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
,2017-08-01 11:28:34 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''
,# teardown
,# setup
,# test defaultDirectory
,ok 4 should be equal
,ok 5 should be equal
ok 6 should be equal
# teardown
,# setup
,# test defaultAdapter
,ok 7 should be equal
ok 8 should be equal
,ok 9 should be equal
ok 10 should be equal
ok 11 should be equal
ok 12 should be equal
ok 13 should be equal
ok 14 should be equal
,# teardown
,# setup
,# enqueue and run in order
,ok 15 firstPromise setTimeout
ok 16 firstPromise result
ok 17 firstPromise testValue
,ok 18 secondPromise setTimeout
ok 19 secondPromise result
ok 20 secondPromise testValue
ok 21 thirdPromise in promise
ok 22 thirdPromise result
ok 23 thirdPromise testValue
# teardown
,# setup
,# enqueueAtTop and run backwards
,ok 24 thirdPromise - first to run
,ok 25 thirdPromise - in resolve
ok 26 secondPromise - second to run
ok 27 secondPromise - in catch
ok 28 firstPromise - third to run
ok 29 firstPromise - in then
ok 30 testing promises
,# teardown
,# setup
,# mix enqueue and enqueueAtTop
,ok 31 fourth
ok 32 fourth
,ok 33 second
ok 34 secondPromise - in then
,ok 35 first
ok 36 firstPromise - in catch
ok 37 third
ok 38 thirdPromise - in then
ok 39 testingPromises
# teardown
,# setup
,# queues handled independently
,ok 40 all short operations completed before the long resolves
# teardown
,# setup
,# enqueued function are always executed asynchronously
,ok 41 executor is not called here
ok 42 executors is called
,# teardown
,# setup
,# exceptions in the executor are properly handled
,ok 43 got expected error
,# teardown
,# setup
,# basic
,ok 44 sane
,# teardown
,# setup
,# another
,ok 45 sane
,# teardown
,# setup
,# skip
,2017-08-01 11:28:58 - DEBUG CoordinatedClient: 'test was skipped, name: 'skip''
,# teardown
,# setup
,# another skip
,2017-08-01 11:28:59 - DEBUG CoordinatedClient: 'test was skipped, name: 'another skip''
,# teardown
,# setup
,# test sinon sansbox spy
,2017-08-01 11:28:59 - DEBUG testTests: 'test spy method for global sinon sansbox'
ok 46 test sandbox spy works correctly
,# teardown
,# setup
,# test sinon sansbox stub
,ok 47 test sandbox stub works correctly
,# teardown
,# setup
,# test sinon sansbox stub override
,ok 48 test sandbox stub works correctly
,# teardown
,# setup
,# test sinon sansbox mock
,# teardown
,# setup
,# test sinon sansbox restore after test end
,ok 49 test restore
,# teardown
,# setup
,# can pass data in setup
,ok 50 test participant has uuid
ok 51 participant data matches
,ok 52 test participant has uuid
ok 53 participant data matches
ok 54 test participant has uuid
ok 55 participant data matches
ok 56 own UUID is found from the participants list
,# teardown
,# setup
,# Correctly parses/stringifies USN
,ok 57 correctly parses USN string
ok 58 throws if usn has invalid prefix
ok 59 throws if usn has invalid identifier format
ok 60 throws if usn has invalid generation
ok 61 correctly stringifies peer
,# teardown
,# setup
,# onPeerLost calls jxcore
,2017-08-01 11:29:04 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
,# teardown
,2017-08-01 11:29:05 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-01 11:29:05 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-01 11:29:05 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:29:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-01 11:29:05 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-01 11:29:05 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-01 11:29:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-01 11:29:05 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# onPeerDiscovered calls jxcore
,2017-08-01 11:29:05 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
,# teardown
,2017-08-01 11:29:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-01 11:29:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-01 11:29:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:29:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-01 11:29:06 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-01 11:29:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-01 11:29:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-01 11:29:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopListeningForAdvertisements
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:3C4D3DCB-D481-4E86-B7EC-819B82D265F6
[ThaliCore] Browser.startListening
2017-08-01 11:29:06 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-01 11:29:06 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-08-01 11:29:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 62 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvert,isements()
[ThaliCore] Browser.stopListening()
2017-08-01 11:29:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:29:06 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
ok 63 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:29:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:29:07 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:29:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
,2017-08-01 11:29:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-01 11:29:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-01 11:29:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-01 11:29:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:29:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-01 11:29:07 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-01 11:29:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-01 11:29:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-01 11:29:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startListeningForAdvertisements twice is NOT an error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:825D31E9-DCB6-4BB1-8396-97EBE97275E0
[ThaliCore] Browser.startListening
,2017-08-01 11:29:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-01 11:29:07 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-01 11:29:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 64 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
2017-08-01 11:29:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"di,scoveryActive":true,"advertisingActive":false}'
2017-08-01 11:29:07 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":",B,OTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-01 11:29:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 65 Can call startListeningForAdvertisements twice without e,rror
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-01 11:29:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:29:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:29:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discovery,Active":false,"advertisingActive":false}'
2017-08-01 11:29:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:29:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-01 11:29:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-01 11:29:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:29:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:29:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:29:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:29:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:29:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling stopListeningForAdvertisements without calling start is NOT an error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:29:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:29:08 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 66 Can call stopListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:29:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:29:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 67 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:29:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:29:08 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:29:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-08-01 11:29:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:29:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-01 11:29:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-01 11:29:08 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:29:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-01 11:29:08 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-01 11:29:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-01 11:29:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-01 11:29:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopUpdateAdvertisingAndListening
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "7D503186-F928-4E26-AC33-1296959BDDA3", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:7D503186-F928-4E26-AC33-1296959BDDA3
,2017-08-01 11:29:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-01 11:29:09 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-01 11:29:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 68 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:7D503186-F928-4E26-AC33-1296959BDDA3
2017-08-01 11:29:09 ,- DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:29:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 69 Can call ,s,topAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:29:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:29:09 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:29:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-08-01 11:29:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:29:09 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-01 11:29:09 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-01 11:29:09 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:29:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-01 11:29:09 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-01 11:29:09 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-01 11:29:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-01 11:29:09 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startUpdateAdvertisingAndListening twice is NOT an error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "EBECE5F8-591D-41DE-B85C-51CE78891513", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:EBECE5F8-591D-41DE-B85C-51CE78891513
,2017-08-01 11:29:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-01 11:29:09 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-01 11:29:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 70 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "EBECE5F8-591D-41DE-B85C-51CE78891513", generation: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:EBECE5F8-591D-41DE-B85C-51CE78891513
2017-08-01 1,1:29:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-01 11:29:09 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-01 11:29:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
,ok 71 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:29:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-01 11:29:09 - INFO thaliMobile: 'Receive,d state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-01 11:2,9:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:EBECE5F8-591D-41DE-B85C-51CE78891513
[ThaliCore] Advertiser.s,topAdvertising() peerID:EBECE5F8-591D-41DE-B85C-51CE78891513
2017-08-01 11:29:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:29:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:29:09 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-01 11:29:09 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-01 11:29:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:29:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:29:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:29:09 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:29:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:29:09 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:29:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:29:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 72 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:29:10 - DEBUG th,aliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:29:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 73 Can call stopAdverti,singAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:29:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:29:11 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:29:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-08-01 11:29:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:29:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-01 11:29:11 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-01 11:29:11 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:29:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-01 11:29:11 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-01 11:29:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-01 11:29:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-01 11:29:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peerAvailabilityChange is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "FA1E2FC6-7693-41FB-8636-0E28C8C7D8EE", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:FA1E2FC6-7693-41FB-8636-0E28C8C7D8EE
2017-08-01 1,1:29:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-08-01 11:29:11 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-08-01 11:29:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 74 Can call startUpdateAdvertisingAndListeningwithout error
[ThaliCore] BrowserManager.startListeningForAdv,ertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:81CD6A77-B104-45C1-B48D-EA947B7A766D
[ThaliCore] Browser.startListening
2017-08-01 11:29:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryA,ctive":true,"advertisingActive":true}'
2017-08-01 11:29:11 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","sta,r,tArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-01 11:29:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 75 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3FF7A990-8C39-4FBC-B905-C091543C0B8F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3FF7A990-8C39-4FBC-B905-C091543C0B8F", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FA1E2FC6-7693-41FB-8636-0E28C8C7D8EE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FA1E2FC6-7693-41FB-8636-0E28C8C7D8EE", generation: 0)
,ok 76 peers must be an array
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E55A7F93-0665-4D1F-868C-2BDF896AC995:0
ok 77 peers must not be zero-length
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E55A7F93-0665-4D1F-868C-2BDF896AC995", generation: 0)
ok 78 peer must have only peerIdentifier, peerAvailable and generation properties
ok 79 peerIdentifier must be a string
ok 80 generation must be a number
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-01 11:29:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-01 ,11:29:13 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-08-01 11:29:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:FA1E2FC6-7693-41FB-8636-0,E28C8C7D8EE
2017-08-01 11:29:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:29:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
2017-08-01 11:29:13 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-01 11:29:13 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-01 11:29:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:29:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:29:13 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:29:13 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:29:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:29:13 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can connect to a remote peer
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "607A023F-B618-46EF-94E2-E6C7B7C6028C", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:607A023F-B618-46EF-94E2-E6C7B7C6028C
2017-08-01 11:29:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-01 11:29:13, - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkTy,pe":null}})'
2017-08-01 11:29:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 81 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[Thal,iCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:6D4C0CD8-C90F-48F6-A2EF-5523DDCD77D9
[ThaliCore] Browser.startListening
2017-08-01 11:29:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"adve,r,tisingActive":true}'
2017-08-01 11:29:13 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"rout,er":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-01 11:29:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 82 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3FF7A990-8C39-4FBC-B905-C091543C0B8F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3FF7A990-8C39-4FBC-B905-C091543C0B8F", generation: 0)
,2017-08-01 11:29:14 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"3FF7A990-8C39-4FBC-B905-C091543C0B8F","generation":0}'
,2017-08-01 11:29:14 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 3FF7A990-8C39-4FBC-B905-C091543C0B8F (syncValue: fsRH9tGjXLNTNb97Jo7239E0DWvWPjhD)'
,2017-08-01 11:29:14 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3FF7A990-8C39-4FBC-B905-C091543C0B8F", generation: 0) creating a new relay
[Tha,liCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3FF7A990-8C39-4FBC-B905-C091543C0B8F", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3FF7A990-8C39-4FBC-B905-C091543C0B8F:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3A455AAE-1A56-4198-ABF8-0B2F78CDA907
[ThaliCore] Advertiser: session connected Peer(uuid: "607A023F-B618-46EF-94E2-E6C7B7C6028C", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:3A455AAE-1A56-4198-ABF8-0B2F78CDA907 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:3FF7A990-8C39-4FBC-B905-C091543C0B8F:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "3FF7A990-8C39-4FBC-B905-C091543C0B8F", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:68DB7C9D-F2A9-4988-BF01-ABC00BA349A9:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "68DB7C9D-F2A9-4988-BF01-ABC00BA349A9", generation: 0)
2017-08-01 11:29:15 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAv,ailable":true,"peerIdentifier":"68DB7C9D-F2A9-4988-BF01-ABC00BA349A9","generation":0}'
2017-08-01 11:29:15 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:172A0C6B-D9CC-4AAC-89D1-604BB3D215A2:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "172A0C6B-D9CC-4AAC-89D1-604BB3D215A2", generation: 0)
2017-08-01 11:29:15 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"172A0C6B-D9CC-4AAC-89D1-604BB3D215A2","generation":0}'
2017-08-01 11:29:15 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-01 11:29:15 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:607A023F-B618-46EF-94E2-E6C7B7C6028C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "607A023F-B618-46EF-94E2-E6C7B7C6028C", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:3FF7A990-8C39-4FBC-B905-C091543C0B8F:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:3F,F7A990-8C39-4FBC-B905-C091543C0B8F:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "3FF7A990-8C39-4FBC-B905-C091543C0B8F", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,FF7A990-8C39-4FBC-B905-C091543C0B8F", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3FF7A990-8C39-4FBC-B905-C091543C0B8F", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-08-01 11:29:17 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"fsRH9tGjXLNTNb97Jo7239E0DWvWPjhD","error":"Peer is unavailable",,"portNumber":null}'
2017-08-01 11:29:17 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'fsRH9tGjXLNTNb97Jo7239E0DWvWPjhD', error: 'Peer is unavailable', listeningPort: '%s''
,2017-08-01 11:29:17 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-08-01 11:29:17 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 68DB7C9D-F2A9-4988-BF01-ABC00BA349A9 (syncValue: 20J35i9KV7k9yvjBSVwxaiB,9NXOKLVkk)'
2017-08-01 11:29:17 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "68DB7C9D-F2A9-4988-BF01-ABC00BA349A9", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "68DB7C9D-F2A9-4988-BF01-ABC00BA349A9", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:68DB7C9D-F2A9-4988-BF01-ABC00,BA349A9:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-08-01 11:29:17 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:3FF7A990-8C39-4FBC-B905-C091543C0B8F:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:3A455AAE-1A56-4198-ABF8-0B2F78CDA907
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:8EB29A2A-35C5-4297-B889-08D3D8393171
[ThaliCore] Advertiser: session connected Peer(uuid: "607A023F-B618-46EF-94E2-E6C7B7C6028C", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:8EB29A2A-35C5-4297-B889-08D3D8393171 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:3A455AAE-1A56-4198-ABF8-0B2F78CDA907 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:68DB7C9D-F2A9-4988-BF01-ABC00BA349A9:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:68DB7C9D-F2A9-4988-BF01-ABC00BA349A9:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:68DB7C9D-F2A9-4988-BF01-ABC00BA349A9:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "68DB7C9D-F2A9-4988-BF01-ABC00BA349A9", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:64459
2017-08-01 11:29:20 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"20J35i9KV7k9yvjBSVwxaiB9NXOKLVkk","error":null,"portNumber":64459}'
2017-08-01 11:29:20 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '20J35i9KV7k9yvjBSVwxaiB9NXOKLVkk', error: 'null', listeningPort: '64459''
,2017-08-01 11:29:20 - INFO testThaliMobileNative: ''
ok 83 Must have listeningPort
ok 84 listeningPort must be a number
ok 85 listening port should not be 0
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:8EB29A2A-35C5-4297-B889-08D3D8393171
,[ThaliCore] Session.session(_:peer:didChange:) peer:8EB29A2A-35C5-4297-B889-08D3D8393171 state: connecting -> connected
,2017-08-01 11:29:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-01 11:29:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-01 11:29:20 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-01 11:29:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:607A023F-B618-46EF-94E2-E6C7B7C6028C
2017-08-01 11:29:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"a,dvertisingActive":false}'
2017-08-01 11:29:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.disconnect peer:68DB7C9D-F2A9-4988-BF01-ABC00BA349A9
[ThaliCore] BrowserRelay.closeRelay(,) state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:64459
[ThaliCore] Session.disconnect() peer:68DB7C9D-F2A9-4988-BF01-ABC00BA349A9:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socke,t error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:8EB29A2A-35C5-4297-B889-08D3D8393171 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "607A023F-B618-46EF-94E2-E6C7B7C6028C", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:8EB29A2A-35C5-4297-B889-08D3D8393171
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:68DB7C9D-F2A9-4988-BF01-ABC00BA349A9:0
,[ThaliCore] BrowserRelay.deinit
,2017-08-01 11:29:20 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-01 11:29:20 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-01 11:29:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:29:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:29:20 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:29:20 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:29:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:29:20 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.deinit peer:8EB29A2A-35C5-4297-B889-08D3D8393171
,[ThaliCore] Session.session(_:peer:didChange:) peer:3A455AAE-1A56-4198-ABF8-0B2F78CDA907 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "607A023F-B618-46EF-94E2-E6C7B7C6028C", generation: 0)
,# Can shift data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "F49BF619-EFCE-49AD-936B-BA7E264E926C", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:F49BF619-EFCE-49AD-936B-BA7E264E926C
,2017-08-01 11:29:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-01 11:29:21 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-01 11:29:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 86 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:7DB0C6B8-F703-4591-92A8-677D8F65,ADE9
[ThaliCore] Browser.startListening
2017-08-01 11:29:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-08-01 11:29:21 - INFO thaliMobile: 'Received state ({"discover,y,Active":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-01 11:29:21 - INFO thaliMobi,le: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 87 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:68DB7C9D-F2A9-4988-BF01-ABC00BA349A9:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "68DB7C9D-F2A9-4988-BF01-ABC00BA349A9", generation: 0)
2017-08-01 11:29:22 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"68DB7C9D-F2A9-4988-BF01-ABC00BA349A9","generation":0}'
2017-08-01 11:29:22 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 68DB7C9D-F2A9-4988-BF01-ABC00BA349A9, (syncValue: 60BXGB8kdezsD6xTblqdY7Tz3UBKhHsG)'
2017-08-01 11:29:22 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "68DB7C9D-F2A9-4988-BF01-ABC00BA,349A9", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "68DB7C9D-F2A9-4988-BF01-ABC00BA349A9", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected,:) peer:68DB7C9D-F2A9-4988-BF01-ABC00BA349A9:0
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:172A0C6B-D9CC-4AAC-89D1-604BB3D215A2:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "172A0C6B-D9CC-4AAC-89D1-604BB3D215A2,", generation: 0)
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-08-01 11:29:22 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailabl,e":true,"peerIdentifier":"172A0C6B-D9CC-4AAC-89D1-604BB3D215A2","generation":0}'
2017-08-01 11:29:22 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-01 11:29:22 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:172A0C6B-D9CC-4AAC-89D1-604BB3D215A2:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "172A0C6B-D9CC-4AAC-89D1-604BB3D215A2", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DB57BA1F-0D18-4357-B930-5C8445B48464:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DB57BA1F-0D18-4357-B930-5C8445B48464", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:A6D469B9-3E3F-424D-B89E-3EF03B482B87:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A6D469B9-3E3F-424D-B89E-3EF03B482B87", generation: 0)
,2017-08-01 11:29:22 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"DB57BA1F-0D18-4357-B930-5C8445B48464","generation":0}'
,2017-08-01 11:29:22 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-01 11:29:22 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-01 11:29:22 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"A6D469B9-3E3F-424D-B89E-3EF03B482B87","generation":0}'
,2017-08-01 11:29:22 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-01 11:29:22 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-01 11:29:22 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F49BF619-EFCE-49AD-936B-BA7E264E926C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F49BF619-EFCE-49AD-936B-BA7E264E926C", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:68DB7C9D-F2A9-4988-BF01-ABC00BA349A9:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:68,DB7C9D-F2A9-4988-BF01-ABC00BA349A9:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "68DB7C9D-F2A9-4988-BF01-ABC00BA349A9", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,8DB7C9D-F2A9-4988-BF01-ABC00BA349A9", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "68DB7C9D-F2A9-4988-BF01-ABC00BA349A9", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:68DB7C9D-F2A9-4988-BF01-ABC00BA349A9:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:68DB7C9D-F2A9-4988-BF01-ABC00BA349A9:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:68DB7C9D-F2A9-4988-BF01-ABC00BA349A9:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:68,DB7C9D-F2A9-4988-BF01-ABC00BA349A9:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "68DB7C9D-F2A9-4988-BF01-ABC00BA349A9", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,8DB7C9D-F2A9-4988-BF01-ABC00BA349A9", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "68DB7C9D-F2A9-4988-BF01-ABC00BA349A9", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:68DB7C9D-F2A9-4988-BF01-ABC00BA349A9:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:68DB7C9D-F2A9-4988-BF01-ABC00BA349A9:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:68DB7C9D-F2A9-4988-BF01-ABC00BA349A9:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:68,DB7C9D-F2A9-4988-BF01-ABC00BA349A9:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "68DB7C9D-F2A9-4988-BF01-ABC00BA349A9", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,8DB7C9D-F2A9-4988-BF01-ABC00BA349A9", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "68DB7C9D-F2A9-4988-BF01-ABC00BA349A9", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:68DB7C9D-F2A9-4988-BF01-ABC00BA349A9:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:68DB7C9D-F2A9-4988-BF01-ABC00BA349A9:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:172A0C6B-D9CC-4AAC-89D1-604BB3D215A2:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "172A0C6B-D9CC-4AAC-89D1-604BB3D215A2", generation: 0)
2017-08-01 11:29:32 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"172A0C6B-D9CC-4AAC-89D1-604BB3D215A2","generation":0}'
2017-08-01 11:29:32 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-01 11:29:32 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-08-01 11:29:32 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-01 11:29:32 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:68DB7C9D-F2A9-4988-BF01-ABC00BA349A9:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:68,DB7C9D-F2A9-4988-BF01-ABC00BA349A9:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "68DB7C9D-F2A9-4988-BF01-ABC00BA349A9", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:68DB7C9D,-F2A9-4988-BF01-ABC00BA349A9 error: max retries exceeded
2017-08-01 11:29:33 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"60BXGB8kdezsD6xTblqdY7Tz3UBKhHsG","error":"Connection could not be established","portNumber":null}'
2017-0,8-01 11:29:33 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '60BXGB8kdezsD6xTblqdY7Tz3UBKhHsG', error: 'Connection could not be established', listeningPort: '%s''
,2017-08-01 11:29:33 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-08-01 11:29:33 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for DB57BA1F-0D18-4357-B930-5C8445B48464 (syncValue: cwv6ofZymDh10djDiUs0aQgXX9550gTv)'
2017-08-01 11:29:33 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "DB57BA1F-0D18-4357-B930-5C8445B48464", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "DB57BA1F-0D18-4357-B930-5C8445B48464", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:DB57BA1F-0D18,-4357-B930-5C8445B48464:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-08-01 11:29:33 - DEBUG thaliMobileNativeTestUtils: 'Already running tes,t,!'
2017-08-01 11:29:33 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-01 11:29:33 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:68DB7C9D-F2A9-4988-BF01-ABC00BA349A9:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:DB57BA1F-0D18-4357-B930-5C8445B48464:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:DB57BA1F-0D18-4357-B930-5C8445B48464:0
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:172A0C6B-D9CC-4AAC-89D1-604BB3D215A2:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "172A0C6B-D9CC-4AAC-89D1-604BB3D215A2", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:DB57BA1F-0D18-4357-B930-5C8445B48464:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "DB57BA1F-0D18-4357-B930-5C8445B48464", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:64466
,2017-08-01 11:29:35 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"cwv6ofZymDh10djDiUs0aQgXX9550gTv","error":null,"portNumber":64466}'
,2017-08-01 11:29:35 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'cwv6ofZymDh10djDiUs0aQgXX9550gTv', error: 'null', listeningPort: '64466''
,Connecting to the localhost:64466
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
Connected to the localhost:64466
[ThaliCore] Session.startOutputStream(with:) peer:DB57BA1F-0D18-4357-B930-5C8445B48464:0
2017-08-01 11:29:36 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-08-01 11:29:36 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:DB57BA1F-0D18-4357-B930-5C8445B48464:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1 [1]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 88 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:1
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
# teardown
[ThaliCore] VirtualSocket exited RunLoop vsID:1
[ThaliCore] VirtualSocket.deinit vsID:1 []
,2017-08-01 11:29:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-01 11:29:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-01 11:29:36 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-01 11:29:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:F49BF619-EFCE-49AD-936B-BA7E264E926C
,2017-08-01 11:29:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:29:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:DB57BA1F-0D18-4357-B930-5C8445B48464
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:64466
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:DB57BA1F-0D18-4357-B930-5C8445B48464:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:DB57BA1F-0D18-4357-B930-5C8445B48464:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "DB57BA1F-0D18-4357-B930-5C8445B48464", generation: 0)
,2017-08-01 11:29:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-01 11:29:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-01 11:29:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:29:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:29:36 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:29:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:29:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:29:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-08-01 11:29:36 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"cwv6ofZymDh10djDiUs0aQgXX9550gTv","error":"Session disconnected","portNumber":null}'
,[ThaliCore] Session.deinit peer:DB57BA1F-0D18-4357-B930-5C8445B48464:0
[ThaliCore] BrowserRelay.deinit
,# Can shift data via parallel connections
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "13783D87-45FF-4D17-B42B-A653E8B09DCB", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:13783D87-45FF-4D17-B42B-A653E8B09DCB
2017-08-01 1,1:29:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-01 11:29:37 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-01 11:29:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 89 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:15A58A4F-9263-40A8-BBEA-9BB3A3562A84
[Thal,i,Core] Browser.startListening
2017-08-01 11:29:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-08-01 11:29:37 - INFO thaliMobile: 'Received state ({"discoveryActive":true,,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-01 11:29:37 - INFO thaliMobile: 'Filtere,d out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 90 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A6D469B9-3E3F-424D-B89E-3EF03B482B87:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A6D469B9-3E3F-424D-B89E-3EF03B482B87", generation: 0)
2017-08-01 11:29:38 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"A6D469B9-3E3F-424D-B89E-3EF03B482B87","generation":0}'
2017-08-01 11:29:38 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for A6D469B9-3E3F-424D-B89E-3EF03B482B87, (syncValue: 1kItLQpI3chjhpcmRc3j1pSdYCwbttH9)'
2017-08-01 11:29:38 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A6D469B9-3E3F-424D-B89E-3EF03B4,82B87", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A6D469B9-3E3F-424D-B89E-3EF03B482B87", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected,:,) peer:A6D469B9-3E3F-424D-B89E-3EF03B482B87:0
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DB57BA1F-0D18-4357-B930-5C8445B48464:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DB57BA1F-0D18-4357-B930-5C8445B48464",, generation: 0)
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-08-01 11:29:38 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable,":true,"peerIdentifier":"DB57BA1F-0D18-4357-B930-5C8445B48464","generation":0}'
2017-08-01 11:29:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-01 11:29:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:13783D87-45FF-4D17-B42B-A653E8B09DCB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "13783D87-45FF-4D17-B42B-A653E8B09DCB", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:14E53D3B-100D-4C85-8359-22BD24E7A4CC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "14E53D3B-100D-4C85-8359-22BD24E7A4CC", generation: 0)
2017-08-01 11:29:38 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"14E53D3B-100D-4C85-8359-22BD24E7A4CC","generation":0}'
2017-08-01 11:29:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-01 11:29:38 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-08-01 11:29:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B83500FD-F735-4993-8A84-3B0EABFD7568:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B83500FD-F735-4993-8A84-3B0EABFD7568", generation: 0)
2017-08-01 11:29:39 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B83500FD-F735-4993-8A84-3B0EABFD7568","generation":0}'
2017-08-01 11:29:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-01 11:29:39 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-08-01 11:29:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-01 11:29:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:A6D469B9-3E3F-424D-B89E-3EF03B482B87:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "A6D469B9-3E3F-424D-B89E-3EF03B482B87", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:A6D469B9-3E3F-424D-B89E-3EF03B482B87:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:A6,D469B9-3E3F-424D-B89E-3EF03B482B87:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "A6D469B9-3E3F-424D-B89E-3EF03B482B87", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A,6D469B9-3E3F-424D-B89E-3EF03B482B87", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A6D469B9-3E3F-424D-B89E-3EF03B482B87", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-08-01 11:29:41 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"1kItLQpI3chjhpcmRc3j1pSdYCwbttH9","error":"Peer is unavailable",,"portNumber":null}'
2017-08-01 11:29:41 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '1kItLQpI3chjhpcmRc3j1pSdYCwbttH9', error: 'Peer is unavailable', listeningPort: '%s''
,2017-08-01 11:29:41 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-08-01 11:29:41 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for DB57BA1F-0D18-4357-B930-5C8445B48464 (syncValue: 4ubhVogOBpEec33IjLd8I4Z,KM2Cxcuvl)'
2017-08-01 11:29:41 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "DB57BA1F-0D18-4357-B930-5C8445B48464", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "DB57BA1F-0D18-4357-B930-5C8445B48464", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:DB57BA1F-0D18-4357-B930-5C844,5B48464:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-08-01 11:29:41 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-01 ,1,1:29:41 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:A6D469B9-3E3F-424D-B89E-3EF03B482B87:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:DB57BA1F-0D18-4357-B930-5C8445B48464:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "DB57BA1F-0D18-4357-B930-5C8445B48464", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:DB57BA1F-0D18-4357-B930-5C8445B48464:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:DB57BA1F-0D18-4357-B930-5C8445B48464:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "DB57BA1F-0D18-4357-B930-5C8445B48464", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D,B57BA1F-0D18-4357-B930-5C8445B48464", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "DB57BA1F-0D18-4357-B930-5C8445B48464", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-08-01 11:29:43 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"4ubhVogOBpEec33IjLd8I4ZKM2Cxcuvl","error":"Peer is unavailable","portNumber":null}'
2017-08-01 11:29:43 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '4ubhVogOBpEec33IjLd8I4ZKM2Cxcuvl', error: 'Peer is unavailable', listeningPort: '%s''
,2017-08-01 11:29:43 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-08-01 11:29:43 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 14E53D3B-100D-4C85-8359-22BD24E7A4CC (syncValue: hNVL4tw9fIIuzbukla5AnjG,sPMSHbeDG)'
2017-08-01 11:29:43 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "14E53D3B-100D-4C85-8359-22BD24E7A4CC", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "14E53D3B-100D-4C85-8359-22BD24E7A4CC", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:14E53D3B-100D-4C85-8359-22BD2,4E7A4CC:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-08-01 11:29:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:DB57BA1F-0D18-4357-B930-5C8445B48464:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:14E53D3B-100D-4C85-8359-22BD24E7A4CC:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:14E53D3B-100D-4C85-8359-22BD24E7A4CC:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:14E53D3B-100D-4C85-8359-22BD24E7A4CC:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "14E53D3B-100D-4C85-8359-22BD24E7A4CC", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:64478
2017-08-01 11:29:46 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"hNVL4tw9fIIuzbukla5AnjGsPMSHbeDG",,"error":null,"portNumber":64478}'
2017-08-01 11:29:46 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'hNVL4tw9fIIuzbukla5AnjGsPMSHbeDG', error: 'null', listeningPort: '64478''
,Connecting to the localhost:64478
Connecting to the localhost:64478
Connecting to the localhost:64478
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:14E53D3B-100D-4C85-8359-22BD24E7A4CC:0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:14E53D3B-100D-4C85-8359-22BD24E7A4CC:0
[ThaliCore], TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:14E53D3B-100D-4C85-8359-22BD24E7A4CC:0
Connected to the localhost:64478
Connected to the localhost:64478
C,onnected to the localhost:64478
,ok 91 correct string length
,2017-08-01 11:29:46 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 92 correct string length
,2017-08-01 11:29:46 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 93 correct string length
,2017-08-01 11:29:46 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,2017-08-01 11:29:46 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-08-01 11:29:46 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-08-01 11:29:46 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:14E53D3B-100D-4C85-8359-22BD24E7A4CC:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2 [2]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:14E53D3B-100D-4C85-8359-22BD24E7A4CC:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3 [2, 3]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:14E53D3B-100D-4C85-8359-22BD24E7A4CC:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4 [2, 3, 4]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
[ThaliCore] S,ession.init(session:identifier:connected:notConnected:) peer:E6BCD6D7-48EB-4EC6-951B-A45AA706E119
[ThaliCore] Advertiser: session connected Peer(uuid: "13783D87-45FF-4D17-B42B-A653E8B09DCB", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[Tha,liCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:E6BCD6D7-48EB-4EC6-951B-A45AA706E119 state: notConnected -> connecting
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:2
[ThaliCore] Browser,Relay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:2
[ThaliCore] VirtualSocket.deinit vsID:2 [3, 4]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:3
[ThaliCore] Browser,Relay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:3
[ThaliCore] VirtualSocket.deinit vsID:3 [4]
,ok 94 got the same data back
,ok 95 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vs,ID:4
,ok 96 got the same data back
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9A06BFE8-2E06-4513-8402-DF87BDDAF892
[ThaliCore] Advertiser: session connected Peer(uuid: "13783D87-45FF-4D17-B42B-A653E8B09DCB", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:9A06BFE8-2E06-4513-8402-DF87BDDAF892 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:E6BCD6D7-48EB-4EC6-951B-A45AA706E119
,[ThaliCore] Session.session(_:peer:didChange:) peer:E6BCD6D7-48EB-4EC6-951B-A45AA706E119 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E6BCD6D7-48EB-4EC6-951B-A45AA706E119
[ThaliCore] Session.startOutputStream(with:) peer:E6BCD6D7-48EB-4EC6-951B-A45AA706E119
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5 [4, 5]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E6BCD6D7-48EB-4EC6-951B-A45AA706E119
[ThaliCore] Session.startOutputStream(with:) peer:E6BCD6D7-48EB-4EC6-951B-A45AA706E119
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6, [4, 5, 6]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E6BCD6D7-48EB-4EC6-951B-A45AA706E119
[ThaliCore] Session.startOutputStream(with:) peer:E6BCD6D7-48EB-4EC6-951B-A45AA706E119
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7 [4, 5, 6, 7]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,2017-08-01 11:29:50 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-08-01 11:29:50 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-08-01 11:29:50 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-08-01 11:29:50 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-08-01 11:29:50 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-08-01 11:29:50 - DEBUG testThaliMobileNative: 'Server received (3244 bytes):'
,2017-08-01 11:29:50 - DEBUG testThaliMobileNative: 'Server received all data: Zd6EtYHhy61A8MvSZkKgIfAGRDpX7JARmtcFjhLWA56Jxq4syCPKkgPxae50qVhegA7B6H4XHHAUOqX9Y30Ih6gXUqzCSqzxWvZ9vqoff4itWKcCEVPKX3xUnYXrFfZP8nq0fzRDTsk0YpDi7t7DxbreS9GNJprv68awDZ6wmENADUgonM,3oTaBV203Pny7n81hTxEfAD8xZaYvuJvbDpgeJQTgIKE2stugF9CNNXVruFfv4M8DAGJTgCnTVBLcr3VEVbczXO7bGh2bZqedTjAl9pLCVTTCFYPvKk29VKVFz6GyozUnYxeKgrjXfPdmilyd7469OqAMB4vchDSO9EDzmlRF349zTYdAVyW5oLFgCKTuje1HAormy5EMSYouD5Lg0zv1LjU1dt6MHjCgSgyilYYp8vBO6t73OVOK2TOjOJdVNxQ,TGC9FNz4knL33LS5HMeoqg2jCT8MeXaA5d2ftKMLkUnaEmdSTTdY9W4va4ClLm6Z11ybgYk4FzWtwpWkB2q3dN6NwVRb9cq03aw1pRah5UI0iZayNCaCv9jtlaCdCBOr3PYZzfxCLYzfHRGUGqM7Sd04jjvMktcXxsXw646SXJLwQzjPbrDkP4MK9gREv7298BMijp41s2z6zh3b3M1CQrn1ExTeFEs7fQv9v7cpnmvdKypP7Mg7r3dnOe08dtk2,GbPEOIGHlSJcYdNAHXuGJYYB1hJGarKJoi4RA759VdOhCC4CFFmwyWhCTDCRDWQ56ogKq4cKfzoSffVTU9knY2wk5AurVGQPtkFWEwZjRqHUCneHgQ8LL409Dm5G40bXeHLDoR3pcqxNKpV94DN6AOTLEOeVoLyAb03EjNlKxzZFhkS8gksFpg2FxbDwLt9AIeggU4LZISgvxI1Rsml3TKxTSOtEXgsKAmU8dv6D5HsAkQqufTs5KMGpH8PWDW6Q,xX0CH2aKOF9JYTJQDBBotPLiiisKZctJ09hEKIAFTMGcyBcFbO0o9qmVLVYTchCR122L1roacU9RAuPhMjK7ZS1wf4jO9FCYvGwikFtq6mPCPKe1VQNqfp1AlesmZXMxYWRQESQaLjSftphQKJ3EgX9W6kzHTD7scWSXX2finbIcUEdID5rhtSZdUa8YUGsEWNcGJ1t3gvQnbKK6wGy3t2weH3D57wtZ4ETvL2xfVX6sHwAckvDnxQfLhDXE3q0p,e2owdgOSybpSzbq517TXG6WejglblFc2D3TuxxMtIk7qCSyNcMQjUHFTmaAk2to84YGu8zw361fN7AoHqERLlZbQcsghjv73zp9F44iJ58hyxsBSLWRM99rW4G4QPyrAJMK97omQO9JmyZGZ72dpIr7z4P2UyMH2b9ZNLmUri3HQin81h0TQcW2EsSk5kNVrMkB9ftYMhheZPddApxZQZX5mQjGMslLizzU04wNOy381A5wD9xtrMrX47WzjPJha,8vOwDToyXE0PyQD73uRMobYKZKjAfQgoTrs9VoimKKPpQjD5vubEIx0kRGtHCSMANAeKRtxtpCK97rnn22iSyzxsy18fqxy1QSb5mHYyQDNLKBatF2tm6P54EoKI3qlu9orevQ7yuE5VSux4uCfHrzQVZXyHazmtUh8nVc11ipY0KsHMNENzyJI9aerccXHWpLPr8xacBAFfqJmI9ZAwftDJOsVc7E0XmVpMmO8XbxxJxCOC1kYQALtdBHWIWfL3,8jPVBsphGzur3WCYkiG6HRZ1pbjYbZY1IP8pfD0GZwC5LS1Z1jCZqEbhzqZXNHkPBheGtoYjpHCxKC1g1DXJC6EHdwxqrp1L4PwZ2kGfx9bcVedfZxNB3LZL7tbLgPz5DfLdxuCWvfpN9gZgC8fL36AfcL1CS5kQo9Dz59oaAbwzLtozfMeh0BDEFv6Cq7451mKATJOO6a4FL0nYIAo1qvxtyzGnSal82pIboIidhW6zEPMtKcTGrVcuj5AS5xkl,i5janKUpABoLa2vdxE3gZTwroQSC8sHGCaHxguQ5U4ilAy47a1Du8JAzVAOfSb41a6jExsoddjUV5L9QXqomswzbVWj5x18EtKIVd1WnKbFfauoF6CFQm9WErQkgXkECskKci37U1SLXhK13bj0wGnEAN0k566H7ve2mZVEh1SqXvjieM2O9uMqPl2oiCBWOuMLtStA042tUzToSvTzhbJXGBpcvSHmroov0RRsuoEcPNZkZfR1BgrD8Vm3Uk475,Ly67pMHQzWDjUQ1PaMumFNhNXiCwPTEY3hTeLaUKgCdS9xK85otVKR3WBQfV4osTVeSqethkGL1hsAgMrdxrxoByTRhBUa2r0kwoP3rgiOFISq7c7F0cRfCneWQLbJNcVuc32BeK19QPA3UuSP05HCjCex8opu6P56bOMorvxLnVLcnMf5cnE3PQ1wbUdMQb47zc1RFsLHMoFMA2WltfRdlH3IW33NHnc9gXNA52pNCmCk1NlYbkBgmfLFPKBdTu,azYTVZl8bYc8tHcpY7lXypQEJdFlz0UddlSHXunYwQGKWaekCsnO7AijEowAeLlGCvcb1kiUSGL7VAlHMx1VS06kd1Uyapw7CNopOMx25VbADxn5HSiq6vh3wgtlFGPdIpjNXdBhcI40RIlWrF3dP67CFZfZbs7CZ8mG7Qjoec8rLw9dDLjVT280GR4ENuITH1gabs0zfF8FiRkNcb0xjc5Q0Lq56YrTli5rd3sQJrVDbzNp9ZHxVsxnznUs8nGe,sjEV8wLKz6ScgyLc0sUbECnOBQtvjpsigTPVVc102ByiRJbpGm20tfX1KdUWguQRIFdz4k4GiHX6uoDsofNZjlyS0gdwcXrv2lYyOK5nuQQOBv51KBOJFWZh9sI2PtIYLFPl0Y6LZSoq79ZT7kvGryAPXgc3UJk2nKuH6rYmgE6U198e2Ue9wsb5azkIkwVSgPhrCG5cqstFULEaP4jdJIG8Q95R8MyJwb2DscejUmNiCvujc8fftcIk3QIqv2l8,l1iSxPWMvrOQLvkHhSnQEgWKIYYT3WojexPkCC55HdmBpC1rLoJ11LPztyhvEictAAqYkKxbbh14pK32G9liO9bGbUvAY1CfczMgeD6NL7fB71J31JFUebpY2NLqJMnELoK3JoRLaHH5g1g72eS4kfqVVPBfJj8P5PPJiLODs7DFPFvMLlEl6eUO0YMwsKwEui9RQBCw6Os5VfrcO30TYOOSCeF1Y4y1VlFkJmxAmY10rcR2PPh9EF4GKuWS8VFO,dTVW4WLEWIj9rpT7qthRaDWAsBowlbvr7K3YlxpeLJztZc3yBdE6nLzfOW7nh4QoM2SF6ICf8n3S6qZFpLvVhSRtVe7FX0eTdDKNS1aoPtrfrzQTja4sfAWn2YGOR6BudXUbRM8OT9bvQ3Kg1UvWrMKsNJyLqnkHJ7GyzLHj9xzOzNFvDCUZPLZfP0yJpofPEY0x6M8HylBeuGyijUvCfyFQj7yiCzSYSGE6bcNPxF2WmwIZSd5fVrrSxuqRbDM2,3rBgSM0Nun3J7KywzSNVNBb2JvA53SnN93QNN89eVQlePtbJFrR6EApvHHL27SSbgaZ1BK4QhB0sXGBQHBz8EVGGU8mXbguSDsOLxXNpXVWIceQ16uKnZvy5YDhFHSt5xTvmCiGMkymp6E4LPJtUgrXMfcYe4owElqAv73bRufnZs0Hmyyo5Hb8OU6gdzIrphn7gsxQ5VHw5wwpgb7B7OIBM2uw0GNu3lIHCkhBRCkyB9ErXMMCSaV3oNG8HaWT0,9ASlBAwQNlBvm2d4jDf0ZViWNdYeFOxHgQIMcuUrYnXeMW9zQWlo2CtZaerQeTVisdfx9htJYL0WscJmaNcqOeyxJPvp7xAvm5YQbDSIxTAjwwjAEbEVtmfqx9eACmclvTVVcaeI035JCoaJ3gKYFnpHbUNP1EzZSoBoiaboZTHUD5SgxAv75FAmsbYvIa8DCs2jSrwmB74QoHHy51huN2kXMXCWSVb01D6CKBuuTB2zpMsmWpFUd6GjeKvyIufd,cxMctV6sMBgAooivHepXUEG3CF5zBKgWHeGutsJzskyFORyGwolhodiePHv515eAbiKyMiQh1zeSlbK8QPNoJEY5vUoGMIDtB9hpiexWs7fus6zxQZwf54rCjAEzZMkcjht9pnN99ZnFRfSkyDedNKx37GVO8IqvPvh2wndddZmNvkZr96gz7qsz5OQc37cPLFPHMtztoRlyUFPX8kKDTHe9DZLVP8GuJhISGGT4fVXJEY8U09rw7cVM3yVY9VcC,8Aob9QsGmakWT5UdlEjdxXvlmJGr9YPaQ3yQNlZA3gU0PZuKP367SpmUfFb3maJnLHqEcHKuDm0gvbXZF8VrvKXD90rdynKzn3Jv7wfGplzIY0bgSbW4zGLRqaaxPxTCxeuJegdmPFgrWO9Hbzy0ECZLNyvsrhXvGRmoVRSSK49i9OuwOnv0PcEhU55xCLF1dQrDsIr2rNMntP7liqmHixr6BRuYo3SYmX5krJTGMOylBJFdC9dC49JrHkdoxaO8,vBZg1hOX2AThR5MClv5cyxgNKMLypXKkdKW563eKci1IAVZDjBrGbXPJhoGpMnkYy5cDOgpkKGMvEXb5E4jRJBG8QJSQj9N4untIbuLGLlw0fszgpYW7eHFwZ4lSJ0lyJDrlUqrNkut3QHKIJ6FnGewkD8sL6lYPc1Xe2xRhyVOOCj3kXp9oY3lKbSb2XNHaLJN5PVbACudelg1avBwqq2V4sRCoEVRy930CZ5fefEL54qycRkaKYcL2F9yMR8Kd,zUm0azosTi9d0maR6apwOwgk1JaC9W3pnyw2XM4m7pKTWI7160GXtX0wu2ZtRKOeHGRgtDIggDNpEQIyiC72ZlndclWgFSvIwZXGLpJRNwmfYAg2kSu3WBb8yp9fe5mKk1g8qi5kpnbJh6df22MsEDqwa4RpnEIczLwO9jhui8ff8HCQ0K4mmLplDCX2whKkFZclRQhBxR1VTZleTQkAeot22NYLakw49DMsTa7Eny64jpEckTXYkKXQkO3AUURL,mxzVWjLogfZslJTCzKEJDfHe3rb9c8d02Ce8GMi44dyyPnFfKKww3Gf2Zf6DR5X2w3vN3LxZyFTgdhyxYcynCkNDDACGcb6fLlURtqecEPssRRHmN90bTrp4Ys6CaAO5jvyzFrE6bk50T7Y0w1lzK1TEYFjhJAQyfSNIOTt4TW6BDsUK3Hw4r8HMr0rHrdultLVF2y5UM9iIu01t6MmJTOvWWw8G7elo6KCKgo2QgBJ2EJeOxNKnnbr3DRFLSYGh,ERfULkQj05hrX5liVmJvLfbIlJzSOicvpZ1rQMNRcxmCmqVS5P9HwZEt1qjr8l0gpg4xFNioarjAQXvVXm1pdNQd12qFUyZnJHAp3v8z3UGJ0E9JRZpQBIv3dpQluA9RX2sQn4mIiqZAt6Hr35XoMvKnG3wM0YDddb1wZZZQjl0vDpPN13SzJ05ikEjc14zm5GRO4IyNxMz3Xw3nK0gOiMLQwGs6jZPladsdplVsrhcyQkyvDS8TOmhWVeTA26m4,cSeN2oPaCYfpjbuigYvsT9zuebOfO0QOyMtkwyxj1MtXgEUrmSCUSYwEcEdoTLc5K8BUzy3FjlRPkHyG19KDQZPJPyrHVJ7io6JUrqhzS7mixwj9aihaBGmk9vqdon8YQBKJpfd6Sgtc8qjbT08xm1bwu8LtOi5IZYsE1rXWf3mjG9pCE3wyEEo3FlGD4ktKaTAIGVCG4mBfGNGLn06cWVPKSXgjzqbg06KgX8dPL5bhwWaDiePAoBGziY5rY9yZ,hyBItG3U3KQeLVM6loo8Xq45DUaDPmIepuGDDrrpV14KRWtvfESu9uRy2WzrEin52hExUR6Aq4ZPSgXwcFcYgbOuHdVXxMfudSfnVDmAK44YbuvJXsJ1mikEmo6MPylTU4SaBaTIgVCLsCuo7Og8IwDowAKM7BiN3DvKNXRKUcWnurosQf8Vv97OcCv62nbqidSjFgOxccrf29Mr8MDNxRGruGa91VctJNfAIRFdHiFFANS5vZzmRApKFoXqUgRJ,MxNCL8hrK8FZyNhDJESBQaFqCYenCiAA4oMz8rVpzmH3CcjJ9rptZoGnExphxkvW2F9O1e6MMWKqP6mv3mKqGHuxOO4VD43nOvq3SPVvrX7KhNWBnWGWgOvSHxpNbelA6c9gmARamGKJZ71S2kSvJrKmKZS6pWGidK6z7aUYqzr5MmM1IO4zZjkOht3TfWYjEc6CaQ4rnWJ9a0hzi6EmL1lz95KCC71zTXKfC54liOb1dJz1G9IOh1xuas4iAFBK,igLgC71qIsI9Fox5pRjLohuv48N8rw0EgoNirPn0kmaZWLXnAQ444EjimwYICSfluzIHh9v9t7WRFGFZya1DZzNeBrSAoTOyj97m24qsqR0nPB87vIjxtLmTe7GCZEfX6dNC6qiSZihfvYs9zUeRoCFYTAxyYh1M37TiH7qLhCoXwJZAgbt2vsUhqObhLXx52WZb1DUu1fJ36tidraPyKj6QpOkIT2fZzGqk9jf7AdPU0BRPZiFlC5jDSkAaO2Sf,PV6dzJ4cbgBEC6kOzVkc08JNz5qYu6pCnosL3x3LBS3mFHdz6b7IdzFi1z3TjiBjsrEpeSP2Zg25MQKE03Uf8yRdn1JgBfM3IOG4rQFe1VsZgA5SUqEVLErMUFYiDrmk4a0tgsGHC2aWTlscuvM270yupdPd7YBu7Htac8alELPHPMmG0NELw5RRgof2BjXFOGojrDPOCXVOYY9ft6LgrRbmpWWjeF3HmJZO5Iz9etONnD0KGlqRveKHQvKLfy2C,0SvFwOcgxG2OIcX88MynvslHCfeJn1mZGJPg0apyAtSegUT7omzVFqhjFZgYL5FvY8MpTvZSx3tgjXxKNsto7ql150YZlsUnJmqRJkN2iqHKvvyljUPf1QIF5acqCmgdzLETVnEO3VskcK4uaUxf2ha3CqHPth0hte4yMuLPE8DE7IpJF5QhjqkdbxXtYNcjFgKELwAD6E9wXqJgC1SnBXaQlNsNX4roKK8Sx2fzCyxMO9SoOi1RvhaskBxZLyiw,J1qgTFgfyQb6RvK6n0e75Xtlf50jjgiCQXk4pegGA4etYd76a00nQrKSMMDzB3vgkZ4JqttRyT5TPathonhqyfi3RgYsAfVhLezkKxrMLYBDcSPeJJVzmWKmGlYqvQZ18IlxiDwyeBdHXNAkN2vysTywo1uEAEH0UnND8aZQM1miEZ5Jgvy4hNN4BbqqXFKO5O5FFRVFSbhr7UmebzgSI2oSHRU4BNPoTrKGQb2ndQzzyXJWyMWx3vojvzVnInm3,kziiRnhll7OJBpdRmdO7XwvmWZ6TD0XqRR8PNpMV9ZHmmjBZ10kwiG6T42AIZTlMDIp5310LDpQRUtoY8dyYY8Tu9iKo8uL1IqaWOtoU8f5PkmqdmrPnomvBZS8tOuBrSpvRtVRclz1ynrfz8N5wk4w74cyP0Zwe50Ho3oVkOJWnYC2swZfYjDjiINKHChmP4bvM205MH44jGPLatOHTG7Dc47XGQNj6rDySEgUWjEgQCNY7qwKEixoEgIAhGBV2,M6QAaDTneaZGlpiQUbR3r3rc2AHOlXM9UsWU45VCK27COYnZLjXQCZyLURpJ39GQjB4ShiqpDWp693kOHC7vHzMsGwV2xD8bSGX6FqKiIiwkujjuOlh0YNjw7kOWXTRp4mTsTSQ1uDBb7NdPSvD6ikh03a8CSIDQBhenXkKBglh1i06ZvfuMQAnr405zhz2BjEwCNTZ3cULCpb2JMFgGwhfPjS9CbVMWFN7MXvFydf1UeaZJmPfvJpZ0bwKyHT16,AND9489OZOpZFvIoF7S2JTnd3R2H6S5bUJNLuhJvkJPPUgiCGNJ9lHnI1ggfNt63XQCL4Kr4NtZ7KZbfmYgc79n8ilHSXHGKDkr78sZDe8uGpojZWwPX7k2g17pjmvLyhf8rcBnuzYpes9EtJj6QSNXkLgjYwl6J2PHY0qaMVs5llS8hCpRmy9n80heBUsRCtUGg6u4Tsuo7KGmCs5S9WWbJl1ke0dPgoJqE5ft0LjRcjaJoQizYXJqurMKzMf97,tTF20WfU1J0pbugtENssGpx4mlg6cphIL8KjEaWSTaG7KYrcmRwSaEc8ZinsRfcJkjZw6Kla6wVA4kVg9Si9AEU1n2BXde8n1oQosNR19bkfnbTM9ELf3YqCjdK6EhGev0fQ2iMn0gHgszgRYjGdCdX70PusmK95IipGdRtym5GaKAVrByinwYt4KTfwxhyTp8e7Ya5DPjtI5BdZ0Udh6DzJ1HwghzyxzoKfGlIW1gSXBrC4r6sYk137lyfiONDq,WYhxALIpe2pHNYGbuyse9hmVM57sPHqHft8W9zxvM0uIs7eXjL7d78SRMPG4AxH4i8rQ2eA3nD69dJRl3AKkW4hfkVXrllEOYwFgCNOGtTlHJdKU98DXPcopAyarBK6hOG5fTJS0pKqJ5OFm7MIvxJKZ9c59dHEDPfY7ywG893sqdEJeWpXzQtJwx2AP581hZ75PK1v2mj5GQTzjPQj8nqf5rewsiwbryMa3xfe8Xt5shBdtrpgmtRFbeJKPhyYY,c8ddvtF5mYql2qeXGTlJQH1lBwbhGGyiBV2bVG284m4XyS6hru5kFT6Dw1oVfrFmJJWiZkLjhnlJNKB72y7j3fX4OhV1Mg0XlpkY3bu0mld0Eg2L1gC2K6cBv6QUzTlRs89UlCYKJE7hwoRCm7ZPVebIby5hzxu8b9kXhNdVmq3n1NwpWqXBVEJ4zraewZQbDQB9mP1PzSOxlwtUm4IgZHjSZlR674Ctm5joT4Vzh8V8fEa2V190dbFOlsrziVVj,TUlwQrdS7PiqHqcKsRvDtCmE1eDLRP6yM58NZ8fM5qf8EW7wRfcelKkkZZvXW1VicubipARGvrNbjzKwQfHNpPoYFSurRR9kTwB0HXnvO8Rn9l9dTVI3YGKF2plDijCkCNwTzhSvk6oCpWadagEwMpGi4R1jWn2HUQBIfYf5l0sfNpihfIN85rXHyRqpG4GaQ1rtx3pSBzBp5AqOert1TtmXOaqA0bU4u9djidwAZJ8XdlerPE1qyihkNrc0nLdN,EaQLfAdRuzbg1BEfhl1BhsS4i76mQ1vXM5dfFGJmxAvdtw6ETHWSGaDsrnAILLPLvs8vYuwVOqCdfQJGPHuBPmuNb1ITNgZ5JIlETGmDXYrg9M8jR3wwM2qJcsqGisX2SVnDmjh8tvjM9RLVnf8Xfbapct65LGjPlBlj9sqiTwfspEO85kYm7r9a2gA9EuAA6uDkKfQ3ZYWktoht1OsG6ppqle2m3lRYEarXn8ez70yw83JA5q8Lp92mD2QxnfGO,3aTSL0YTds3pIlNL8dWempL4RQDqSGoU0RsHIQQ1aJ8ekpFKNe6uHZ60OoRLr5IDVHAFXuMuRbt5wueY06W6kWPsgYUKSVYR5pyYNPmuWWFatcf2uoshfiHRMa0SNRk3qigP5mlkZp07QZ9FBNdV33Ltz6un3jRJ16iOBvm2qqElKezXbK2ikQLpl5J52Tmpa7YUJBzJyANDu9ivvmYEaA4UqpfqdCh4XbLJq8tKWYASu3sN73Q2UTyJpDLgpRno,3BH21qbAkljS5hT9VtSR8Uq8iIHwAA4QLG9PaG4ieErFgn6gkHZDw3tkYTOwBNeO1nOpF3jbjjEtITjQnSrUUPWMFQZfpHVV3lvq6oFcgJHO0QdnyA7e0Yy4570SPERPP8fSxZWyLb8gMdJ8A3Qx2upPseJEenLPHovrAZxeOBDqtHkqMjlHkkx5CofbOdm07mSJ3Eu4arvRQ9raHDeIAWlVJ9bonzlu007oOxcrWsrj7EFOgIRtcLZ6bwUxqqoK,7i0ewg6hA87IzZkMwShEwvGFlxyLjgyUZbNrFloVFZRYf0j752jcWkR7A9ZcOV5sQV7dyViDF8PEnynho9nka3wfjs9ujQYB1mqc0xmzzXXoQA8SxI4XEuuItitXpwgMKShAZQgggfGAsCC98WRypfGQRjz1fqZePBKypqpF8o0fmjruTUdOrNk7zEMKTRAuvHU2CCh6sG6S5xDdjmYAiqsiRoylBbNLGBLk7RIfktCg2p1sH3hyiSxvY165iEuv,EdLm0HXaoUh4kXIjgsRbKhcnFIJGvJw64Duzw8FQLABGzyLc36LI9tMxjt6G79jC3A8nkqVQAhXMcXLNrndRUw58VT8sadoGARhzNKSQ5O51c1S1ABDfWe5khHlosLJdsRDwgFnIEePnR5iPzdbbXOvQS7u6kar4YHn00vgZuXtXM8XTRM81RWKzzCaWP0fZ5993P6HRdiafEcG5kkVZiUSxEbCyIi4UhvnMerpoULRXpCKBOtk3hX1DKcetWtXy,gubIus37drTrU6MCEuaZ3jLWGqbXeZPFPghGKlvXgQaaW61ZCZXxrrUO5CrG79ZsK23zzJ41MTgxjjNBeR8nh6h1m9AdfSRkQm3W2RHRb8NHskuIBhx5iqOymqw7b3YlH7gvEZpi3Vv5lzqmlwssavsGvp2zwz7OsizbBv7LH7kc1ZXLQzeba0LSVGbw4NEatIE4E6g689GduRRKF4Nz990udyOy0l5nztC9htk9owuAPYUt2orL0rBeVsFXcBuS,yqf4WiuyvlHuaP5E3GDPW9GKN6R5o4IaZqcWstyhHGxvFq1vbZx3LZp8AbC3KVgFnUp9Qn4PUtQP03uwxWWLwmpQwJZcZdfMf7YAuBFoXtgwJdu9TWMHz1dxkKsx7aGjlqxvO8DkgVGpXqBc0L8A95Cfs0OJODeeyTfx9nS8hXgeYmVk90vygzmIRRFzOW40GxXx7RKKA4obGCwSDlyn73WqCV6XK76fSJp4vfQQNbunvPT8vEzVMKuxhz23ZQYs,U0Lx3OXeULLUsMXQa1C1BeuGqLIMqe5EfEpZDhtda55SsDpSNUmChJl3HuTOwQNKtjAkhDvjfVCWDSUo1LZjOL4M7MUdvEdNn3ngrUk6zmeUaTh0CxuCuRw2bX9ay2dHnX1T8U4VdvIHfqGiicgIlW3RuY7jXYi03mGqfHvFj12s3Xxa0gxgfMcW4w2cLNoDVT6QLSy6stSkpZpWlYSxMXel5V8K5OBB9YtUBCgoxR5FCKoAq1F5HZZMZMqfsS8G,BR1DDXSGUDGFoJLgCJ6IJt9QFbE66Hor4plmXiDFCJv3zuNxj3DHVZTErEwf8Ly7CgVgIvWolGgano3O8mPUY73anzixzVg0tkmmG99sPBWKq2NPSbmRsz5hvelVbVpAJXLBBwswYPajgNUYfzhEiEyURJEHO1beOYSNSJiQbLtd1TTmFyhqSrv7iTcDzVIapeGiyaE9lfVDuRuAoqvhL9aLgDhQBN2ypurjTvaWXz0SGyQERRwfcLuYXPFqzBBX,TM7qpJFov9UbQw2c0xtME0yrprZDycxKTp5U0BffB4LJIwdVyRPmb0CrP1ar8cUEW0M14O0E1ZOFt7w7qVQEQZPvUCg3qCiHDcCfdVEFEdOXC0Iuikl2b52GUw2ckjG5ZX45cJGRZf2bLCAUZmmp5iPJ6QOnGYxtIc1iIGyUBqHEaSHnj8uzIgD4Vd6vohFKcmEh3SHOT3KZvHhQKcmhOA4jheabm542BxQpsBf6Mz8a1Ol8II7xwe8Spmrs0zJz,KZEfCjCNTwUm0ak9rokyEQTN97AaE1vgdrdhzOc8PIHhqSKjGMdog1htIdRQNH8keKaO02GmgsiGA5aNosCHhJ1F8JTrXuVl9qGbtqq3V7osiIS5MEoYjwdj3Lmzkr14AdKDI4fy9jubnfgBR0ndiOOyPQZldbDgPEz0SVhMnF5cxtoBPBtYdnZKz7TkVGjJCFwkFkfAvjVVBo3c6CMl2Me2iuNYFQemx8iAcSTtYYwDvehvLEptr6AiFPngzUMb,2WO56ovLVcSeTQM1CRTdxZsmFdsMh5nNbworjJzpgJVF70r1ueylYRJnmB6yCE3bZrxBvYTd5QisA8vJhn0bN6hc1Wt7994US9y2UrHw2aj3kB2Eev45xnERR5u0wh9m2xo5SOOhNexqev9aJwrMtnMNuedwKCKrVW3KVTy5sRICiN4NaWE3MaKLOr1NBttRUqFszjHxIJcMpP0Erz77JLFOyOBmX5Zz9W5qjqyrsr9CygMgw6HN2TwrcrVLceYT,lC3MoSlIYmzvzIzNxxmkTl0bUDtl2WPbXB72aQTt4Wc28xtxCGgyjNqUzUXcuKrMYLGYxdBmLDLd32L5HIbpc8DF7KT3bXAmjUr28F1WcmrhlBV3dHbCKHpwDINs6hH6h5h5TbnrJcMV4ddToJYXRjxMq3ou7oyh8PPqIKTarN3v7KqD5nrQb37cXEH4hETs4jlYVhy1iirTZiXUL2nV0k96EHfcyJegcUZgO2dMao7DaoZOozuh4K7F0FsvbHya,wM1SK48i2O8XLfDz7r4AOlIrcFfM0fmIxMcgZItwOM0ZsnQSjbjCSysumQmDJLzsaxP2qlPzO62Mdrl9hen2sHKT9ZnpiUdp2hUrYjwbWMg5IAIyP2UUckA15P95J23JCSbniUwEDebT8tdF9LMrrgt0OyHnDPDPfmotCQuFWuyYOysaiMkEwfwbfifjRuiTFp2azejD9qgQVUbKry01rtMl2sShkYJ1hWhDYkDFafzfWTknHQQFmumzGD1S9XTP,LXxHZbdxp2Z6CcQ8E0jc1qHdItiKy7Bx2rBJXJd8Cype3w1V0tr7yoYrmtWEZ9q8UGKM38S3gt0QCzxxmxulBR7TjZbMgk7mVdgK9yP8KNwert2rzsE5YJILGLXUp85hpfU3ggyDgslcThi7aHxUwyKskYhMslBgsDcHGIn7NbyBrMi63yoXMw85dNapyuOb4i5MzGZk5r6TiEyRkUVPxc6vgS8sEL7vyDxcnI8XBpTkcHHTvuOQawj84Zcnytzu,QaGIgRd08r82AgnOaBkJv8zHOZ9A747aCyfXTEkBzaRkcmUdbGEx5uE2o6w9bzlmYKJ89z919zE8BMlBF6JK2v8xBw3qgLeJ1FGBEDg2Gvr9gmIaUZ01khTbJeZr2WVn5DRAomSsgPzndJAzw0ZJF9lckjAfm2grf3S3ROjUk24QonSJw6BihoqfLwcDaHQOSuCJh9sgFJ3jmaJkaO8dQHACwsjArtl61prx1slwa9b4ciY1Nb9cWiaMNeA1F5FE,oGC11viq1rPsRnfNOj4g1HqrF2UsWgScxgCcpHJcoHZmH8vvIHl7AbWhmiLvZUxVqclYZqSv5jXcaaRRIwHRhr0JhrdIWT3SQHmkJ9pDsvdkuH9bGeb2QsfRTpemhI2jr4Qfe5VnRIMaNV92QfWrnXnAg5ZzF6hcYKpZn2XvCf6m86LVpnPdDwC3UZYWScpF0wOGaJPWWxj5jqRxsNVKypJDZFbYaxQBjE6YlaQIXVH8NN9Lj0SUifhvyIlwg1Vq,kvtnjZSHgqOGnBugqp3SNjSRl0D2hwBM3vrN1k0N8FojqTwtV8ZvDkdnHek9ClkjnJOxNarhkkz5CBTpiBKgxV1LWgMbozPTzpaTeANDTixG3ZjPHoSva41n1e1EGKzhmZ6wPmqkiv16P13S0u1KoId8DR4Y2eMb5p0pZv425tayFkAqBB6Grw6O0EmBZtp6xUAnihqq63TxLYncliqZplAc88iDRlRgKw2P2vHDM02XkDJGci1Ev6pRcZCkXQlS,1cFgtD20UkBnBUjsNZYanVrEueiZnof8KKgumJJpkKcbGpexniGmrnJpcifSHBUtaKinOukB3ihAANlGYjuBfQMWw8N0hBx5ZazEJJKN1trW0RNrScUvQrwjBnQ15qV5RJSvW2xWUGcrSuKDLyLW2ussb7Jz6C9XTnQqsXM6C7J52Eqtg7i8pQzm7IbvViI8VCmpbOp4t7cKSNcdnOZ3S0wdTzhWpTYpDSWvRz06SbcdJKMVHygJsbGB6KloRwYa,Oph8kq742SCagIXNvlCFGdadvSozO19o79cIq1ozyv9lQifodqmfZsjqbRkFCFIZhrwrv56u3ROZAxCLysR5GdOsKdQuCMbWlTBuq3rglqe5LuFIYCEmmkkKRXPORBdnsTzhLqUCXdxHIVCOI7rXT0gkiD87mcEya6zz53fQGL2fhyQUrbkFvTrqSMDKHUOkxz2xGUJhA3iGiXVomrkvgWRzsO5iOjDOYsYkBb8Nfl1CHdjqksJLzSsZn8OLpUaM,e85Gn9zKbTgdiyu0ijGCeRqVGbQZotB6bgSkZdIcFtvlYqZMO2LunzS5b5fHXquov177JkooULWTSIVqoJUMfRMeZvw6QO2vGVoAq00DHkYdyECkzKJk2Eu5zbfiOnUwV0bJejQxEBGds5EOLgZz43AZMVxqoUuyvmLH7qCO7DnhJkveR1362Alx209A5NlY8V6VRfHAVogzUe9gx54bCWTq72gLWuqL3F9BDtO4TNZQYh6zXy1C27pcThb4DaCy,QNT1zYydg36wMvg8MitX0C5kIXm29krOjjFOwHclpI27Ds4AvbRfz5ENrhKKphxrgib55p4FrBU2KwTJW42SSUBpYM0DmiV7zp1RUoL2YibRVcEb5mKcUXVnNUYCNRiK8CywAV7pbMCYd2vyge8EyxQxo50yl7Yzni38nAu9AfxYgBeY2Hda24PyxWPujh1dLNBtH07r5LLopILEdYHJA9okw3m4osvkpjknPZkvEIkbr5EivNtGRnuER78wHV7X,noRTfosJT5JUXls4sRWpMW0TgnbB6M4d5SekurIvgtjGGWc9ovNNgfb2VA0BOT8tT89UNQmQDBYxt4nVasaBsRIPAvzWq1JRmJU6aKVyQByvtPBtVyWttcm0e2UUB6vOHnv8GpaGsAJVnol27L7EeXGqBNONsrkSUrdIpVqg3md3AmdDvEx4MqjWPWkel2M3q3RkVVC8DL8foh1rt6TzyW9Nk7kRSXdz4Yk8AQlDiW8nyIeBU0VPoYVwrs3orOxE,m63vbHqMYLVdWPVaUjjuxNkSAUAUxWlVS27tCLTquRLCV7jjdJuw1QwbAFkSvs45iXGmFBSRLWhBLeBP6SVJOyOVasKz9jZmcNFyrr79yuxic9H6wrLhcwHZV9YkVd5BuuOtJrs0bRu73WcSBM1FfxHvR9EfMNmxR34kP2uWLL67jiccF2spCpQdR3wSC8YzWxS68Wl1e7V4oYDlKCWbDDtLesaGwGZrdkqlyL96Kd8klxCopDVtmKxGKczJ6yvo,FeUQHHEiu7xvSGhLTKzQvyY05U1NWknfnxHgoOn9JZWZgT2xNOOPgFRDmH6ezxc5J5DK2z3Xz4dqJUJfN32TC9rSgioFWSrZPCSu2V4Ps5HbHnxJgHjrW6ie2FQkZAFoWU7pRa3kJbXShepTzsdtlIo8OsUw6iK0EvWWjVNCIi5zvwFuQw0984B0sNDWitggyEhuzoewY69eOVSC4Di3O19U3Z8NbhGus1ziggzG5YbvolLSkN3D7fShpxSQyd4Q,d94866y4Ow5NjXXY64mluO2PZtDipe4RiZoV3QHlBKs2b7sRt7eLZo7BiMlXqScFbs2gSQnXRPgo7RNF21XGG6mB4Og5Lmasdw744KsCs1zKB09ikZj0HI9CSPYewQj7g3BkhbuFky205plKjmtuuNzw4pdQ1I7YQLT8PNNBGfYHICGAmjSktPRzi6nZk6jRzJVhvrk0RTV7tJYe4F5TyZuKgTyDLuGsiopi74YczPjfnr5dIbVwVLOOubKD6PVx,qgZ6yOgzQdvwCAD5W0z8nIj8BHjMrN0qehUTppkQ9HK0YTw7GmirkkJr3Bg4oItbs0at979vf88v7heGUmRI4LjKL2YRwWvJsewvpKfAeYcND01Ubr1m9gHL3FkmLhkJAuc0SNcSrAO3xgEo2z3r74dIYyoNFgCNvmu8YsQ27HWcrDppTaM4znPKpQIfuL5jkTVWtzgb3IU27D4UVdhT6bWtwVOXYT2bry1h8H99zG96cWGQ4iIehbYfdnxAawJE,cCDHcJxhAvRZKEIjJZ3aifKZ2AbwnnBpwPoDp1KlsTUhiBI1SzjZILZOZ8cmsVQLHJMuhMIVql6JEmPfVSdJJ7kUPzJltBePCXi2O2TU0ODizXjhQ5ncJH0KrQ4pyXPQab9ngLghxVI8C28StePrfobwJ9SBFYtFyopDtHgiMOKBR0WiOJ26ms6rkC7W572DjVTl43yZ4QNxjXdyjKuIIJoz7B3E73nffP78kRptBiJ2pOeSGoUNehc8OJlevXoB,OXa0ArcNr6f1pNGrdM88VzNMviWp9A41ANwHvZLDGI3i1mHIlXKikj8INzOZwJsgHL2Uzz272YBhmJ'
2017-08-01 11:29:50 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-08-01 11:29:50 - DEBUG testThaliMobileNative: 'Server data flushed',
,2017-08-01 11:29:50 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-08-01 11:29:50 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-08-01 11:29:50 - DEBUG testThaliMobileNative: 'Server received (7665 bytes):'
,2017-08-01 11:29:50 - DEBUG testThaliMobileNative: 'Server received (4339 bytes):'
,2017-08-01 11:29:50 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-08-01 11:29:50 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-08-01 11:29:50 - DEBUG testThaliMobileNative: 'Server data flushed',
,2017-08-01 11:29:50 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-08-01 11:29:50 - DEBUG testThaliMobileNative: 'Server received (6570 bytes):'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:5
[ThaliCore] VirtualSocket.closeStreams() vsID:5
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:5
,[ThaliCore] VirtualSocket.deinit vsID:5 [4, 6, 7]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-08-01 11:29:50 - DEBUG testThaliMobileNative: 'Server received (6570 bytes):'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:6
[ThaliCore] VirtualSocket.closeStreams() vsID:6
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:6
[ThaliCore] VirtualSocket.deinit vsID:6 [4, 7]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client di,sconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-08-01 11:29:50 - DEBUG testThaliMobileNative: 'Server received (1054 bytes):'
,2017-08-01 11:29:50 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-08-01 11:29:50 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-08-01 11:29:50 - DEBUG testThaliMobileNative: 'Server data flushed',
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:7
[ThaliCore] VirtualSocket.closeStreams() vsID:7
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:7
[ThaliCore] VirtualSocket.deinit vsID:7 [4]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:9A06BFE8-2E06-4513-8402-DF87BDDAF892
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DB57BA1F-0D18-4357-B930-5C8445B48464:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DB57BA1F-0D18-4357-B930-5C8445B48464", generation: 0)
2017-08-01 11:29:52 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"DB57BA1F-0D18-4357-B930-5C8445B48464","generation":0}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:9A06BFE8-2E06-4513-8402-DF87BDDAF892 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9A06BFE8-2E06-4513-8402-DF87BDDAF892
[ThaliCore] Session.startOutputStream(with:) peer:9A06BFE8-2E06-4513-8402-DF87BDDAF892
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8 [4, 8]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9A06BFE8-2E06-4513-8402-DF87BDDAF892
[ThaliCore] Session.startOutputStream(with:) peer:9A06BFE8-2E06-4513-8402-DF87BDDAF892
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9 [4, 8, 9]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9A06BFE8-2E06-4513-8402-DF87BDDAF892
[ThaliCore] Session.startOutputStream(with:) peer:9A06BFE8-2E06-4513-8402-DF87BDDAF892
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:10 [4, 8, 9, 10]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,2017-08-01 11:29:53 - DEBUG testThaliMobileNative: 'Server received (5120 bytes):'
,2017-08-01 11:29:53 - DEBUG testThaliMobileNative: 'Server received (11264 bytes):'
[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
2017-08-01 11:29:53 - DEBUG tes,tThaliMobileNative: 'Server received all data: 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'
2017-08-01 11:29:53 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-08-01 11:29:53 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-08-01 11:29:53 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-08-01 11:29:53 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-08-01 11:29:53 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-08-01 11:29:53 - DEBUG testThaliMobileNative: 'Server received (3072 bytes):'
,2017-08-01 11:29:53 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-08-01 11:29:53 - DEBUG testThaliMobileNative: 'Server received (213 bytes):'
,2017-08-01 11:29:53 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-08-01 11:29:53 - DEBUG testThaliMobileNative: 'Server received (3143 bytes):'
,2017-08-01 11:29:53 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-08-01 11:29:53 - DEBUG testThaliMobileNative: 'Server received (1237 bytes):'
,2017-08-01 11:29:53 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-08-01 11:29:53 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-08-01 11:29:53 - DEBUG testThaliMobileNative: 'Server received (4339 bytes):'
,2017-08-01 11:29:53 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-08-01 11:29:53 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-08-01 11:29:53 - DEBUG testThaliMobileNative: 'Server data flushed',
2017-08-01 11:29:53 - DEBUG testThaliMobileNative: 'Server received (4339 bytes):'
2017-08-01 11:29:53 - DEBUG testThaliMobileNative: 'Server received all data: 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[T,haliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:8
[ThaliCore] VirtualSocket.closeStreams() vsID:8
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[Th,aliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
QE4Jwj90PpzLhf58w9Dng4cNsMnlJAwskQoWAqve0nML3LuzwLhEQER9xJekHESjDOHDgMq8XwV3gSVxF2mxtQMcs5ufOUv9runS0DSxlBcTtNYP9tDeYI7yJrwwslFMWynQjkgHv4flbF3ZeLnhImMzRyNadGuva8Fh2WmMhzr5dn,1uK7hIYYMDlJaxgn6n9rT2R5s5R7nGhkZXUUVlhdJdxeBneFMOg4FxeneHr7hBduYhW2QFjUA3UmDFugWbe7W9qAGSXlIt63SRIOjwAFToAsbY5BlphZy38fAYdjAOMnX4wnw2I9bI9lsooUqQY4LUP2fdWwh04sdOtW8OXjsb8hPAsFONbzcnePufc46aX70VYsVv168sho8B7xaAwKwrlrqPsrr2NBNlPOcIz473m6WvCZaeUeFPzcnZh0Pd1h,xaskWo4WVD1QvprQGz9S4zcrRBYGYfJU8MAODBAKKMTBkSNCLA5HDxrmcfX1deErStUTyOFVFvENmFWF6H2JBEsShx4tykhWCxDnJ9oUAAnBp1rkb8J6eyMgAv7fiiBibZu9jolzamRhubJzLoBpenTHrHxvagC6MBuy8gxgddTvvbUlj819o4ovrF3G9xEZJgWWOf0NS4tiJeyDqak7btTqY68vcvNWHOScxV6IyTDL6GfdyfQs6S1HfCxqItP7,uwUnukViM51kwgOWsayg0o21ZLsrdN6ItOyUyorTf8y7VN41Tfiv8vQxSOVCnngkgeehgrY3gwajZRuNqsHrnXSKvSdVfOgTwTlKfO5D8GzDPEn0FiOjfqUc7mq4gMZ4ifS7BF4ZgDzo5dthW5HwdayUXbcEBThG0hbnX2AEpr4icz2tKt6VtstavfkQi7b3MsS3l0aj6hgvWOpmh7BSQvohPqeWnZpVT17Gg3UdWLCBe0sc79tLjf6lp5l1lrOf,jL4YM5NAKQqX5kS3uGtw1BhrU32dsfJ5wjRwekd646TmHSdNg4SnTNpBbFqzNs7hjq7ZDHjFP4t421aVETfCqbldEDc6bFqcygyTL8bFMjqd3DpnZeed8hmH48sVhJoCOOdLcXuIU6HISLjmp2odzEDeRmSWKwvn46AD38q1o8NNBYIB53RmQusUdqVFUXMFiW7Exb6jZjo5wnmau5gE8mjRumPrQxz7ngyjrNOfFqykf0x1rcMbC5clBsplBVFW,P0Th3O2Qugf7nBM14cGbaZSJAV1rDPAg4Cnt2xdRKhRPXsx3F8WALYXgah3NWelpOdEwLRiqsplObfRnMJqR8PYC7oDLnGBlPemkAGQaG1KJeMG1wcmzr3LPEka99R5W45de4gMIIGdza8TJdo9Al5qm0r34z8ToHleBwldf9RMXTgR3BHhvYgkW07wOrYYTLvfyrclxa0PZYR4aiYpgelINDDm5mDvN0Wu0DFmZBgBIhuWFPgyLzoKkomsF2XqA,8PZoG2cOdai56xquzmXXdl57Iub9dFDjt6Kxm4ImiGItO9L3IWegk3QopusnsYyQ4N6101go745DXmLINdvnjSWI8yfWninIFTfqabi6Zc8gRQDF8b3'
2017-08-01 11:29:53 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-08-01 11:29:53 - DEBUG testThal,iMobileNative: 'Server data flushed'
[ThaliCore] VirtualSocket exited RunLoop vsID:8
[ThaliCore] VirtualSocket.deinit vsID:8 [4, 9, 10]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.s,ocketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:9
[ThaliCore] VirtualSocket.closeStreams() vsID:9
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:9
[ThaliCore] VirtualSocket.deinit vsID:9 [4, 10]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:10
,[ThaliCore] VirtualSocket.closeStreams() vsID:10
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-08-01 11:29:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-08-01 11:29:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-01 11:29:53 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-01 11:29:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:13783D87-45FF-4D17-B42B-A653E8B09DCB
2017-08-01 11:29:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"a,dvertisingActive":false}'
2017-08-01 11:29:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:14E53D3B-100D-4C85-8359-22BD24E7A4CC
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:64478
[ThaliCore] Session.disconnect() p,eer:14E53D3B-100D-4C85-8359-22BD24E7A4CC:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:9A06BFE8-2E06-4513-8402-DF87BDDAF892 state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "13783D87-45FF-4D17-B42B-A653E8B09DCB", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
,[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
,[ThaliCore] Session.disconnect() peer:9A06BFE8-2E06-4513-8402-DF87BDDAF892
,[ThaliCore] Session.deinit peer:14E53D3B-100D-4C85-8359-22BD24E7A4CC:0
,2017-08-01 11:29:53 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-01 11:29:53 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-01 11:29:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:29:53 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:29:53 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:29:53 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:29:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:29:53 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:E6BCD6D7-48EB-4EC6-951B-A45AA706E119 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "13783D87-45FF-4D17-B42B-A653E8B09DCB", generation: 0)
,# Can shift data securely
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "BCACD4FC-6BC5-40D6-9610-1040266CBCE0", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:BCACD4FC-6BC5-40D6-9610-1040266CBCE0
,2017-08-01 11:29:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-01 11:29:54 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-01 11:29:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 97 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D08720CC-EAA5-4BF6-B697-407B5ADDB5F2
[ThaliCore] Browser.startListe,ning
,2017-08-01 11:29:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-08-01 11:29:54 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-01 11:29:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
,ok 98 Can call startListeningForAdvertisements without error
,[ThaliCore] Session.deinit peer:9A06BFE8-2E06-4513-8402-DF87BDDAF892
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B83500FD-F735-4993-8A84-3B0EABFD7568:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B83500FD-F735-4993-8A84-3B0EABFD7568", generation: 0)
2017-08-01 11:29:54 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B83500FD-F735-4993-8A84-3B0EABFD7568","generation":0}'
2017-08-01 11:29:54 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B83500FD-F735-4993-8A84-3B0EABFD7568, (syncValue: LBb3OysAs1uqJvfGqeHKlw6HiGI7MjFT)'
2017-08-01 11:29:54 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B83500FD-F735-4993-8A84-3B0EABF,D7568", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B83500FD-F735-4993-8A84-3B0EABFD7568", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected,:,) peer:B83500FD-F735-4993-8A84-3B0EABFD7568:0
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DB57BA1F-0D18-4357-B930-5C8445B48464:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DB57BA1F-0D18-4357-B930-5C8445B48464",, generation: 0)
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-08-01 11:29:54 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable,":true,"peerIdentifier":"DB57BA1F-0D18-4357-B930-5C8445B48464","generation":0}'
2017-08-01 11:29:54 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-01 11:29:54 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:709BCCF3-BC4B-4608-9082-D26EEC5531F5:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "709BCCF3-BC4B-4608-9082-D26EEC5531F5", generation: 0)
,2017-08-01 11:29:55 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"709BCCF3-BC4B-4608-9082-D26EEC5531F5","generation":0}'
,2017-08-01 11:29:55 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-01 11:29:55 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-01 11:29:55 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3119235A-AF7A-4ADD-9B55-A83D97083E39:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3119235A-AF7A-4ADD-9B55-A83D97083E39", generation: 0)
2017-08-01 11:29:55 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"3119235A-AF7A-4ADD-9B55-A83D97083E39","generation":0}'
2017-08-01 11:29:55 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-01 11:29:55 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-08-01 11:29:55 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-01 11:29:55 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BCACD4FC-6BC5-40D6-9610-1040266CBCE0:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BCACD4FC-6BC5-40D6-9610-1040266CBCE0", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:B83500FD-F735-4993-8A84-3B0EABFD7568:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B8,3500FD-F735-4993-8A84-3B0EABFD7568:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "B83500FD-F735-4993-8A84-3B0EABFD7568", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,83500FD-F735-4993-8A84-3B0EABFD7568", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B83500FD-F735-4993-8A84-3B0EABFD7568", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:B83500FD-F735-4993-8A84-3B0EABFD7568:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:DB57BA1F-0D18-4357-B930-5C8445B48464:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "DB57BA1F-0D18-4357-B930-5C8445B48464", generation: 0)
,[ThaliCore] Session.deinit peer:B83500FD-F735-4993-8A84-3B0EABFD7568:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:B83500FD-F735-4993-8A84-3B0EABFD7568:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B8,3500FD-F735-4993-8A84-3B0EABFD7568:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "B83500FD-F735-4993-8A84-3B0EABFD7568", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,83500FD-F735-4993-8A84-3B0EABFD7568", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B83500FD-F735-4993-8A84-3B0EABFD7568", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:B83500FD-F735-4993-8A84-3B0EABFD7568:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:B83500FD-F735-4993-8A84-3B0EABFD7568:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:B83500FD-F735-4993-8A84-3B0EABFD7568:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B8,3500FD-F735-4993-8A84-3B0EABFD7568:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "B83500FD-F735-4993-8A84-3B0EABFD7568", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,83500FD-F735-4993-8A84-3B0EABFD7568", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B83500FD-F735-4993-8A84-3B0EABFD7568", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:B83500FD-F735-4993-8A84-3B0EABFD7568:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:B83500FD-F735-4993-8A84-3B0EABFD7568:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:B83500FD-F735-4993-8A84-3B0EABFD7568:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "B83500FD-F735-4993-8A84-3B0EABFD7568", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:0674F720-4FB9-4890-AA34-55A602AF7964
[ThaliCore] Advertiser: session connected Peer(uuid: "BCACD4FC-6BC5-40D6-9610-1040266CBCE0", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:0674F720-4FB9-4890-AA34-55A602AF7964 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:B83500FD-F735-4993-8A84-3B0EABFD7568:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:B83500FD-F735-4993-8A84-3B0EABFD7568:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "B83500FD-F735-4993-8A84-3B0EABFD7568", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:B83500FD-F735-4993-8A84-3B0EABFD7568 error: max retries exceeded
,2017-08-01 11:30:05 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"LBb3OysAs1uqJvfGqeHKlw6HiGI7MjFT","error":"Connection could not be established","portNumber":null}'
,2017-08-01 11:30:05 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'LBb3OysAs1uqJvfGqeHKlw6HiGI7MjFT', error: 'Connection could not be established', listeningPort: '%s''
,2017-08-01 11:30:05 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-08-01 11:30:05 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 709BCCF3-BC4B-4608-9082-D26EEC5531F5 (syncValue: wbd7sDFZkmJWOXHTiu7NeJnTUg8xMl5y)'
,2017-08-01 11:30:05 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "709BCCF3-BC4B-4608-9082-D26EEC5531F5", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "709BCCF3-BC4B-4608-9082-D26EEC5531F5", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:709BCCF3-BC4B-4608-9082-D26EEC5531F5:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-08-01 11:30:05 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-01 11:30:05 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:B83500FD-F735-4993-8A84-3B0EABFD7568:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:709BCCF3-BC4B-4608-9082-D26EEC5531F5:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:0D6ACF47-CE18-479A-A30B-1C93F4902313
[ThaliCore] Advertiser: session connected Peer(uuid: "BCACD4FC-6BC5-40D6-9610-1040266CBCE0", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:0D6ACF47-CE18-479A-A30B-1C93F4902313 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:0674F720-4FB9-4890-AA34-55A602AF7964
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:709BCCF3-BC4B-4608-9082-D26EEC5531F5:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:0674F720-4FB9-4890-AA34-55A602AF7964 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0674F720-4FB9-4890-AA34-55A602AF7964
[ThaliCore] Session.startOutputStream(with:) peer:0674F720-4FB9-4890-AA34-55A602AF7964
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:11 [4, 10, 11]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,Server received psk id: psk-id
,2017-08-01 11:30:08 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
2017-08-01 11:30:08 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
2017-08-01 11:30:08 - DEBUG testThaliMobileNative: 'Server sends data bac,k to client (20 bytes): '
2017-08-01 11:30:08 - DEBUG testThaliMobileNative: 'Server data flushed'
2017-08-01 11:30:08 - DEBUG testThaliMobileNative: 'Server's socket stream finished'
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting,:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCo,re] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:11
[ThaliCore] VirtualSocket.closeStreams() vsID:11
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketS,t,reamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:11
[ThaliCore] VirtualSocket.deinit vsID:11 [4, 10]
,[ThaliCore] Session.session(_:peer:didChange:) peer:709BCCF3-BC4B-4608-9082-D26EEC5531F5:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "709BCCF3-BC4B-4608-9082-D26EEC5531F5", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:64503
,2017-08-01 11:30:08 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"wbd7sDFZkmJWOXHTiu7NeJnTUg8xMl5y","error":null,"portNumber":64503}'
,2017-08-01 11:30:08 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'wbd7sDFZkmJWOXHTiu7NeJnTUg8xMl5y', error: 'null', listeningPort: '64503''
,Connecting to the localhost:64503
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:709BCCF3-BC4B-4608-9082-D26EEC5531F5:0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:0D6ACF47-CE18-479A-A30B-1C93F4902313
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:709BCCF3-BC4B-4608-9082-D26EEC5531F5:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:12 [4, 10, 12]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,Connected to the localhost:64503
2017-08-01 11:30:09 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
2017-08-01 11:30:09 - DEBUG testThaliMobileNative: 'Client data flushed'
,ok 99 got the same data back
# teardown
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed b,y remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.,closeStreams() vsID:12
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:12
[ThaliCore] VirtualSocket.deinit vsID:12 [4, 10]
,[ThaliCore] Session.session(_:peer:didChange:) peer:0D6ACF47-CE18-479A-A30B-1C93F4902313 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0D6ACF47-CE18-479A-A30B-1C93F4902313
[ThaliCore] Session.startOutputStream(with:) peer:0D6ACF47-CE18-479A-A30B-1C93F4902313
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,3 [4, 10, 13]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,Server received psk id: psk-id
,2017-08-01 11:30:10 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
2017-08-01 11:30:10 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
2017-08-01 11:30:10 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes): '
,2017-08-01 11:30:10 - DEBUG testThaliMobileNative: 'Server data flushed'
2017-08-01 11:30:10 - DEBUG testThaliMobileNative: 'Server's socket stream finished'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:13
[ThaliCore] VirtualSocket.closeS,treams() vsID:13
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:13
[ThaliCore] VirtualSocket.deinit vsID:13 [4, 10]
,2017-08-01 11:30:11 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-01 11:30:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-01 11:30:11 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-01 11:30:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:BCACD4FC-6BC5-40D6-9610-1040266CBCE0
2017-08-01 11:30:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11,:,30:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:709BCCF3-BC4B-4608-9082-D26EEC5531F5
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:64503
[ThaliCore] Session.disconnect() p,eer:709BCCF3-BC4B-4608-9082-D26EEC5531F5:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:709BCCF3-BC4B-4608-9082-D26EEC5531F5:0
[ThaliCore] BrowserRelay.deinit
,2017-08-01 11:30:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-01 11:30:11 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-01 11:30:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,[ThaliCore] Session.session(_:peer:didChange:) peer:0D6ACF47-CE18-479A-A30B-1C93F4902313 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "BCACD4FC-6BC5-40D6-9610-1040266CBCE0", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:0D6ACF47-CE18-479A-A30B-1C93F4902313
,[ThaliCore] Session.session(_:peer:didChange:) peer:0674F720-4FB9-4890-AA34-55A602AF7964 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "BCACD4FC-6BC5-40D6-9610-1040266CBCE0", generation: 0)
,2017-08-01 11:30:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-01 11:30:11 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-01 11:30:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-01 11:30:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-01 11:30:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,[ThaliCore] AdvertiserRelay.deinit
,# setup
,[ThaliCore] Session.deinit peer:0D6ACF47-CE18-479A-A30B-1C93F4902313
,# Can shift large amounts of data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "8C4149E0-9EF7-47F3-AF61-7B54D5101639", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:8C4149E0-9EF7-47F3-AF61-7B54D5101639
,2017-08-01 11:30:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-08-01 11:30:11 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-01 11:30:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 100 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:E1987A65-4FE4-45E2-8BDF-0E447463D722
[ThaliCore] Browser.startListening
,2017-08-01 11:30:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-08-01 11:30:11 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-08-01 11:30:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 101 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3119235A-AF7A-4ADD-9B55-A83D97083E39:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3119235A-AF7A-4ADD-9B55-A83D97083E39", generation: 0)
2017-08-01 11:30:12 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"3119235A-AF7A-4ADD-9B55-A83D97083E39","generation":0}'
2017-08-01 11:30:12 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 3119235A-AF7A-4ADD-9B55-A83D97083E39, (syncValue: irEyx0sK3AQ7jZIecmQDZJte9O5R3hsn)'
2017-08-01 11:30:12 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3119235A-AF7A-4ADD-9B55-A83D970,83E39", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3119235A-AF7A-4ADD-9B55-A83D97083E39", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3119235A-AF7A-4ADD-9B55-A83D97083E39:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8C4149E0-9EF7-47F3-AF61-7B54D5101639:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8C4149E0-9EF7-47F3-AF61-7B54D5101639", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7D1DD656-98E9-4642-8F1D-2B7D93F24C5C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7D1DD656-98E9-4642-8F1D-2B7D93F24C5C", generation: 0)
2017-08-01 11:30:13 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"7D1DD656-98E9-4642-8F1D-2B7D93F24C5C","generation":0}'
2017-08-01 11:30:13 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-01 11:30:13 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:08A37317-9245-4816-9BBA-BFF468DCB1A3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "08A37317-9245-4816-9BBA-BFF468DCB1A3", g,eneration: 0)
2017-08-01 11:30:13 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"08A37317-9245-4816-9BBA-BFF468DCB1A3","generation":0}'
2017-08-01 11:30:13 - DEBUG thaliMobileNativeTestUtils: 'Already running ,test!'
2017-08-01 11:30:13 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-01 11:30:13 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:3119235A-AF7A-4ADD-9B55-A83D97083E39:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:31,19235A-AF7A-4ADD-9B55-A83D97083E39:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "3119235A-AF7A-4ADD-9B55-A83D97083E39", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,119235A-AF7A-4ADD-9B55-A83D97083E39", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3119235A-AF7A-4ADD-9B55-A83D97083E39", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:3119235A-AF7A-4ADD-9B55-A83D97083E39:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:3119235A-AF7A-4ADD-9B55-A83D97083E39:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:3119235A-AF7A-4ADD-9B55-A83D97083E39:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:31,19235A-AF7A-4ADD-9B55-A83D97083E39:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "3119235A-AF7A-4ADD-9B55-A83D97083E39", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,119235A-AF7A-4ADD-9B55-A83D97083E39", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3119235A-AF7A-4ADD-9B55-A83D97083E39", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:3119235A-AF7A-4ADD-9B55-A83D97083E39:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:3119235A-AF7A-4ADD-9B55-A83D97083E39:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:3119235A-AF7A-4ADD-9B55-A83D97083E39:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:31,19235A-AF7A-4ADD-9B55-A83D97083E39:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "3119235A-AF7A-4ADD-9B55-A83D97083E39", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,119235A-AF7A-4ADD-9B55-A83D97083E39", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3119235A-AF7A-4ADD-9B55-A83D97083E39", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:3119235A-AF7A-4ADD-9B55-A83D97083E39:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:3119235A-AF7A-4ADD-9B55-A83D97083E39:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:844E4EE5-1A48-45AB-86DC-C6E9AF19AB4B
[ThaliCore] Advertiser: session connected Peer(uuid: "8C4149E0-9EF7-47F3-AF61-7B54D5101639", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:844E4EE5-1A48-45AB-86DC-C6E9AF19AB4B state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:3119235A-AF7A-4ADD-9B55-A83D97083E39:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:31,19235A-AF7A-4ADD-9B55-A83D97083E39:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "3119235A-AF7A-4ADD-9B55-A83D97083E39", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:3119235A,-AF7A-4ADD-9B55-A83D97083E39 error: max retries exceeded
2017-08-01 11:30:23 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"irEyx0sK3AQ7jZIecmQDZJte9O5R3hsn","error":"Connection could not be established","portNumber":null}'
2017-0,8-01 11:30:23 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'irEyx0sK3AQ7jZIecmQDZJte9O5R3hsn', error: 'Connection could not be established', listeningPort: '%s''
,2017-08-01 11:30:23 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-08-01 11:30:23 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 7D1DD656-98E9-4642-8F1D-2B7D93F24C5C (syncValue: i1lNUfQZeE9worcidaHI9XN2ErUnJWzW)'
2017-08-01 11:30:23 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7D1DD656-98E9-4642-8F1D-2B7D93F24C5C", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7D1DD656-98E9-4642-8F1D-2B7D93F24C5C", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:7D1DD656-98E9,-4642-8F1D-2B7D93F24C5C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-08-01 11:30:23 - DEBUG thaliMobileNativeTestUtils: 'Already running tes,t,!'
2017-08-01 11:30:23 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:3119235A-AF7A-4ADD-9B55-A83D97083E39:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:7D1DD656-98E9-4642-8F1D-2B7D93F24C5C:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:844E4EE5-1A48-45AB-86DC-C6E9AF19AB4B
,[ThaliCore] Session.session(_:peer:didChange:) peer:844E4EE5-1A48-45AB-86DC-C6E9AF19AB4B state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:844E4EE5-1A48-45AB-86DC-C6E9AF19AB4B
[ThaliCore] Session.startOutputStream(with:) peer:844E4EE5-1A48-45AB-86DC-C6E9AF19AB4B
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:14 [4, 10, 14]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:726A3B35-CA0E-4B9F-BE0E-7009616DE343
[ThaliCore] Session.session(_:peer:didChange:) peer:726A3B35-CA0E-4B9F-BE0E-7009616DE343 state: notConnected -> connecting
[ThaliCore] Advertiser: session connected Peer(uuid: "8C4149E0-9EF7-47F3-AF61-7B54D5101639", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
,2017-08-01 11:30:24 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
,2017-08-01 11:30:24 - DEBUG testThaliMobileNative: 'Server received (2048 bytes):'
,2017-08-01 11:30:24 - DEBUG testThaliMobileNative: 'Server received (11264 bytes):'
,2017-08-01 11:30:24 - DEBUG testThaliMobileNative: 'Server received (13312 bytes):'
,2017-08-01 11:30:24 - DEBUG testThaliMobileNative: 'Server received (18271 bytes):'
,2017-08-01 11:30:24 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-08-01 11:30:24 - DEBUG testThaliMobileNative: 'Server received (5475 bytes):'
,2017-08-01 11:30:24 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-08-01 11:30:24 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-08-01 11:30:24 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
,2017-08-01 11:30:24 - DEBUG testThaliMobileNative: 'Server received (2026 bytes):'
,2017-08-01 11:30:24 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-08-01 11:30:24 - DEBUG testThaliMobileNative: 'Server sends data back to client (65536 bytes):'
2017-08-01 11:30:24 - DEBUG testThaliMobileNative: 'Server data flushed',
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:14
[ThaliCore] VirtualSocket.closeStreams() vsID:14
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:14
[ThaliCore] VirtualSocket.deinit vsID:14 [4, 10]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client, disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:7D1DD656-98E9-4642-8F1D-2B7D93F24C5C:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:7D1DD656-98E9-4642-8F1D-2B7D93F24C5C:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "7D1DD656-98E9-4642-8F1D-2B7D93F24C5C", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:64521
2017-08-01 11:30:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"i1lNUfQZeE9worcidaHI9XN2ErUnJWzW",,"error":null,"portNumber":64521}'
2017-08-01 11:30:26 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'i1lNUfQZeE9worcidaHI9XN2ErUnJWzW', error: 'null', listeningPort: '64521''
,Connecting to the localhost:64521
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:7D1DD656-98E9-4642-8F1D-2B7D93F24C5C:0
Connected to the localh,ost:64521
2017-08-01 11:30:26 - DEBUG testThaliMobileNative: 'Client sends data (65536 bytes):'
2017-08-01 11:30:26 - DEBUG testThaliMobileNative: 'Client data flushed'
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7D1DD656-98E9-4642-8F1D-2B7D93F24C5C:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:15 [4, 10, 15]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:15
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:15
,ok 102 got the same data back
,[ThaliCore] VirtualSocket.deinit vsID:15 [4, 10]
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:726A3B35-CA0E-4B9F-BE0E-7009616DE343
,[ThaliCore] Session.session(_:peer:didChange:) peer:726A3B35-CA0E-4B9F-BE0E-7009616DE343 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:726A3B35-CA0E-4B9F-BE0E-7009616DE343
[ThaliCore] Session.startOutputStream(with:) peer:726A3B35-CA0E-4B9F-BE0E-7009616DE343
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,6 [4, 10, 16]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-08-01 11:30:27 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-08-01 11:30:27 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-08-01 11:30:27 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-08-01 11:30:27 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
,2017-08-01 11:30:27 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-08-01 11:30:27 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-08-01 11:30:27 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-08-01 11:30:27 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
,2017-08-01 11:30:27 - DEBUG testThaliMobileNative: 'Server received (6570 bytes):'
,2017-08-01 11:30:27 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-08-01 11:30:27 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-08-01 11:30:27 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-08-01 11:30:27 - DEBUG testThaliMobileNative: 'Server received (1024 bytes):'
,2017-08-01 11:30:27 - DEBUG testThaliMobileNative: 'Server received (2261 bytes):'
,2017-08-01 11:30:27 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-08-01 11:30:27 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-08-01 11:30:27 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-08-01 11:30:27 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-08-01 11:30:27 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-08-01 11:30:27 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-08-01 11:30:27 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-08-01 11:30:27 - DEBUG testThaliMobileNative: 'Server received (3143 bytes):'
,2017-08-01 11:30:27 - DEBUG testThaliMobileNative: 'Server received (1237 bytes):'
,2017-08-01 11:30:27 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-08-01 11:30:27 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-08-01 11:30:27 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-08-01 11:30:27 - DEBUG testThaliMobileNative: 'Server received (2026 bytes):'
,2017-08-01 11:30:27 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-08-01 11:30:27 - DEBUG testThaliMobileNative: 'Server sends data back to client (65536 bytes):'
2017-08-01 11:30:27 - DEBUG testThaliMobileNative: 'Server data flushed',
,2017-08-01 11:30:27 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:16
[ThaliCore] VirtualSocket.closeStreams() vsID:16
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-08-01 11:30:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-08-01 11:30:27 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-01 11:30:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:8C4149E0-9EF7-47F3-AF61-7B54D5101639
,2017-08-01 11:30:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:30:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:7D1DD656-98E9-4642-8F1D-2B7D93F24C5C
,[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:64521
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:7D1DD656-98E9-4642-8F1D-2B7D93F24C5C:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:726A3B35-CA0E-4B9F-BE0E-7009616DE343 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "8C4149E0-9EF7-47F3-AF61-7B54D5101639", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:726A3B35-CA0E-4B9F-BE0E-7009616DE343
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:7D1DD656-98E9-4642-8F1D-2B7D93F24C5C:0
,[ThaliCore] BrowserRelay.deinit
,2017-08-01 11:30:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-01 11:30:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-01 11:30:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:30:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-01 11:30:28 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:30:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:30:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:30:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:844E4EE5-1A48-45AB-86DC-C6E9AF19AB4B state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "8C4149E0-9EF7-47F3-AF61-7B54D5101639", generation: 0)
,[ThaliCore] Session.deinit peer:726A3B35-CA0E-4B9F-BE0E-7009616DE343
,# We do not emit peerAvailabilityChanged events until one of the start methods is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "E3460A4F-36DC-4A56-B55E-DBD85034D10A", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:E3460A4F-36DC-4A56-B55E-DBD85034D10A
2017-08-01 1,1:30:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-01 11:30:30 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-01 11:30:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 103 Ready to advertise
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:21658856-BDF1-457B-ADF5-2A6D8BF886E5
[ThaliCore] Browser.startListening
2017-08,-,01 11:30:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-08-01 11:30:30 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not ma,tch with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-01 11:30:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate ,(was in stopped state).'
ok 104 Ready to listen
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:AD3FECF4-CBFE-4AFA-8379-AD80173A0C4C:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "AD3FECF4-CBFE-4AFA-8379-AD80173A0C4C", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:08A37317-9245-4816-9BBA-BFF468DCB1A3:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "08A37317-9245-4816-9BBA-BFF468DCB1A3", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B1D08031-1F9F-45B6-A50C-99D850E180F5:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B1D08031-1F9F-45B6-A50C-99D850E180F5", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:3119235A-AF7A-4ADD-9B55-A83D97083E39:0
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3119235A-AF7A-4ADD-9B55-A83D97083E39", generation: 0)
[ThaliCore] Advertiser.stopAdvertising() peerID:E3460A4F-36DC-4A56-B55E-DBD85034D10A
,2017-08-01 11:30:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-01 11:30:31 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-01 11:30:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 105 stop ads worked
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-08-01 11:30:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:30:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 106 test stop worked
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:30:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:30:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:30:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-08-01 11:30:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:30:34 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-01 11:30:34 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-01 11:30:34 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:30:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-01 11:30:34 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-01 11:30:34 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-01 11:30:34 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-01 11:30:34 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Test updating advertising and parallel data transfer
,2017-08-01 11:30:34 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test updating advertising and parallel data transfer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:30:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:30:35 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:30:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-08-01 11:30:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:30:35 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-01 11:30:35 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-01 11:30:35 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:30:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-01 11:30:35 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-01 11:30:35 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-01 11:30:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-01 11:30:35 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# discoveryAdvertisingStateUpdateNonTCP is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:337A96E6-6CFB-4F53-9A3F-EBF85F826AB0
[ThaliCore] Browser.startListening
,ok 107 discoveryActive should be false
ok 108 advertisingActive should be true
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "4F9AAE4B-5D00-4125-B694-3C2F06118E9A", generation: 0)
[ThaliCore] Advertise,r.startAdvertising with peerID:4F9AAE4B-5D00-4125-B694-3C2F06118E9A
ok 109 discoveryActive should be false
ok 110 advertisingActive should be true
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
ok 111 d,iscoveryActive should be false
ok 112 advertisingActive should be true
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:4F9AAE4B-5D00-4125-B694-3C2F06118E9A
ok 113 discoveryActive should be false
ok 114 a,dvertisingActive should be true
ok 115 Can call startListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:30:35 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-01 11:30:35 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-01 11:30:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:30:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:30:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:30:35 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:30:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:30:35 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call connect when start listening for advertisements is not active
,2017-08-01 11:30:36 - DEBUG CoordinatedClient: 'test was skipped, name: 'cannot call connect when start listening for advertisements is not active''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-01 11:30:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:30:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 116 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-01 11:30:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:30:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 117 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# Get error when trying to double connect to a peer on Android
,2017-08-01 11:30:36 - DEBUG CoordinatedClient: 'test was skipped, name: 'Get error when trying to double connect to a peer on Android''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:30:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:30:38 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 118 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:30:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:30:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 119 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection
,2017-08-01 11:30:38 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:30:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:30:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 120 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:30:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:30:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 121 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection
,2017-08-01 11:30:39 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:30:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:30:40 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 122 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-01 11:30:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:30:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 123 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer
,2017-08-01 11:30:40 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:30:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:30:40 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 124 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-01 11:30:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:30:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 125 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer
,2017-08-01 11:30:41 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:30:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:30:41 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 126 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-01 11:30:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:30:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 127 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# cannot call multiConnect when start listening for advertisements is not active
,ok 128 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:0c960f4b-59a2-42aa-9e6e-8f1169062c06 error: startListeningNotActive
,2017-08-01 11:30:41 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"GhsoYBW2YxALR4CTKGEBsHGTFt57q3FD","error":"startListeningForAdvertisements is not active","portNumber":null}'
,ok 129 Should only get called after multiConnect returned
,ok 130 SyncValue matches
,ok 131 Got right error
,ok 132 listeningPort is null
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-01 11:30:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:30:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-01 11:30:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:30:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:30:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-01 11:30:41 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-01 11:30:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:30:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:30:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:30:41 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:30:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:30:41 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with illegal peerID
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:25E9867E-B09E-49D7-8EA7-5DB7958A1378
[ThaliCore] Browser.startListening
,2017-08-01 11:30:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-01 11:30:41 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-01 11:30:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 133 No error on starting
ok 134 Got null as expected
2017-08-01 11:30:41 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"BGflFctZdkSPSHbDzrVHJqCENHvJgDqB","error":"Illegal peerID","portNumber",:null}'
ok 135 Should only get called after multiConnect returned
ok 136 SyncValue matches
ok 137 Got right error
ok 138 listeningPort is null
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-01 11:30:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01, 11:30:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:30:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discovery,Active":false,"advertisingActive":false}'
2017-08-01 11:30:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:30:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-01 11:30:41 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-01 11:30:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:30:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:30:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:30:41 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:30:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:30:41 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# multiConnect properly fails on legal but non-existent peerID
,2017-08-01 11:30:42 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiConnect properly fails on legal but non-existent peerID''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:30:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:30:42 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:30:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-08-01 11:30:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:30:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-01 11:30:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-01 11:30:42 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:30:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-01 11:30:42 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-08-01 11:30:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-01 11:30:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-01 11:30:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with invalid syncValue
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:FC9FB5C1-CC09-4F0D-9AE7-15086B4EC21D
[ThaliCore] Browser.startListening
,2017-08-01 11:30:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-01 11:30:42 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-01 11:30:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 139 No error on starting
ok 140 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-01 11:30:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01, 11:30:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:30:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discovery,Active":false,"advertisingActive":false}'
2017-08-01 11:30:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:30:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-01 11:30:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-01 11:30:42 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:30:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-01 11:30:42 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-01 11:30:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-01 11:30:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:30:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call disconnect with invalid peer id
,ok 141 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:30:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:30:43 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:30:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-08-01 11:30:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:30:43 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-01 11:30:43 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-01 11:30:43 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:30:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:30:43 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:30:43 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:30:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:30:43 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# disconnect doesn't fail on plausible but bogus peer ID
,[ThaliCore] BrowserManager.disconnect peer:80c04626-398f-4fff-83f8-f6924401fb72
ok 142 No error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:30:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:30:43 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:30:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-08-01 11:30:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:30:43 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-01 11:30:43 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-01 11:30:43 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:30:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:30:43 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:30:43 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:30:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:30:43 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Get same port when trying to connect multiple times on iOS
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "4C8FCF81-7CEA-409B-B47C-33B13E726DA2", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:4C8FCF81-7CEA-409B-B47C-33B13E726DA2
2017-08-01 1,1:30:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-08-01 11:30:43 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-01 11:30:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 143 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browse,r.init(serviceType:foundPeer:lostPeer:) peer:12ADFAEC-A5B8-44A3-B373-F08B523DE253
[ThaliCore] Browser.startListening
,2017-08-01 11:30:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-08-01 11:30:43 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-08-01 11:30:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 144 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:08A37317-9245-4816-9BBA-BFF468DCB1A3:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "08A37317-9245-4816-9BBA-BFF468DCB1A3", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4A0C3DC3-7791-4A79-AC3A-13A5BB3F1300:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4A0C3DC3-7791-4A79-AC3A-13A5BB3F1300", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0C3ABEC2-EDE9-49BF-9CEC-7F09F581009A:0
[ThaliCore] BrowserManager.fo,undPeerHandler peer:Peer(uuid: "0C3ABEC2-EDE9-49BF-9CEC-7F09F581009A", generation: 0)
2017-08-01 11:30:45 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"08A37317-9245-4816-9BBA-BFF468DCB1A3","generation":0}'
,2017-08-01 11:30:45 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 08A37317-9245-4816-9BBA-BFF468DCB1A3 (syncValue: 8WoBmhWklCApDhbitM2hC7AD6B44iBR0)'
,2017-08-01 11:30:45 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "08A37317-9245-4816-9BBA-BFF468DCB1A3", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "08A37317-9245-4816-9BBA-BFF468DCB1A3", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:08A37317-9245-4816-9BBA-BFF468DCB1A3:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-08-01 11:30:45 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"4A0C3DC3-7791-4A79-AC3A-13A5BB3F1300","generation":0}'
,2017-08-01 11:30:45 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-01 11:30:45 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-01 11:30:45 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"0C3ABEC2-EDE9-49BF-9CEC-7F09F581009A","generation":0}'
,2017-08-01 11:30:45 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-01 11:30:45 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-01 11:30:45 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4C8FCF81-7CEA-409B-B47C-33B13E726DA2:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4C8FCF81-7CEA-409B-B47C-33B13E726DA2", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:08A37317-9245-4816-9BBA-BFF468DCB1A3:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "08A37317-9245-4816-9BBA-BFF468DCB1A3", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:08A37317-9245-4816-9BBA-BFF468DCB1A3:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:08,A37317-9245-4816-9BBA-BFF468DCB1A3:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "08A37317-9245-4816-9BBA-BFF468DCB1A3", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0,8A37317-9245-4816-9BBA-BFF468DCB1A3", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "08A37317-9245-4816-9BBA-BFF468DCB1A3", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-08-01 11:30:47 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"8WoBmhWklCApDhbitM2hC7AD6B44iBR0","error":"Peer is unavailable","portNumber":null}'
2017-08-01 11:30:47 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '8WoBmhWklCApDhbitM2hC7AD6B44iBR0', error: 'Peer is unavailable', listeningPort: '%s''
,2017-08-01 11:30:47 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-08-01 11:30:48 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 4A0C3DC3-7791-4A79-AC3A-13A5BB3F1300 (syncValue: Z7nxdTsnFIsJfL1bszedO0RpXSDKNEBP)'
2017-08-01 11:30:48 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4A0C3DC3-7791-4A79-AC3A-13A5BB3F1300", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4A0C3DC3-7791-4A79-AC3A-13A5BB3F1300", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4A0C3DC3-7791-4A79-AC3A-13A5B,B3F1300:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-08-01 11:30:48 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:08A37317-9245-4816-9BBA-BFF468DCB1A3:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:4A0C3DC3-7791-4A79-AC3A-13A5BB3F1300:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:4A0C3DC3-7791-4A79-AC3A-13A5BB3F1300:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:4A0C3DC3-7791-4A79-AC3A-13A5BB3F1300:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "4A0C3DC3-7791-4A79-AC3A-13A5BB3F1300", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:64532
2017-08-01 11:30:51 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Z7nxdTsnFIsJfL1bszedO0RpXSDKNEBP","error":null,"portNumber":64532}'
,2017-08-01 11:30:51 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'Z7nxdTsnFIsJfL1bszedO0RpXSDKNEBP', error: 'null', listeningPort: '64532''
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:4A0C3DC3-7791-4A79-AC3A-13A5BB3F1300:0
,ok 145 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4A0C3DC3-7791-4A79-AC3A-13A5BB3F1300", generation: 0) found active relay
,2017-08-01 11:30:51 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"FJ7V03GenhweD5oms19B40QErsGZsSaV","error":null,"portNumber":64532}'
,ok 146 No error
,ok 147 Ports equal
,ok 148 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4A0C3DC3-7791-4A79-AC3A-13A5BB3F1300", generation: 0) found active relay
,2017-08-01 11:30:51 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"8ld4u5E7EHTbjm6y8YoRgSRTif17uapl","error":null,"portNumber":64532}'
,ok 149 No error
,ok 150 Ports equal
,# teardown
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4A0C3DC3-7791-4A79-AC3A-13A5BB3F1300:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:17 [4, 10, 16, 17]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-08-01 11:30:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-01 11:30:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-01 11:30:58 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-01 11:30:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:4C8FCF81-7CEA-409B-B47C-33B13E726DA2
2017-08-01 11:30:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11,:,30:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:4A0C3DC3-7791-4A79-AC3A-13A5BB3F1300
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:64532
[ThaliCore] VirtualSocket.closeStr,eams() vsID:17
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket remo,ved, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket exited RunLoop vsID:17
[ThaliCore] Session.disconnect() peer:4A0C3DC3-7791-4A79-AC3A-13A5BB3F1300:0
[ThaliCore] VirtualSocket.closeStreams() vsID:,17
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket.deinit vsID:17 [4, 10, 16]
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:4A0C3DC3-7791-4A79-AC3A-13A5BB3F1300:0
[ThaliCore] BrowserRelay.deinit
2017-08-01 11:30:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-01 11:30:58 - DEBUG thaliMobileNat,iveWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-01 11:30:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:30:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:30:58 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:30:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:30:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:30:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# initial peer discovery
,2017-08-01 11:30:59 - DEBUG CoordinatedClient: 'test was skipped, name: 'initial peer discovery''
,# teardown
,2017-08-01 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-01 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-01 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:30:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-01 11:30:59 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-01 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-01 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-01 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 1
,2017-08-01 11:30:59 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 1''
,# teardown
,2017-08-01 11:31:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-01 11:31:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-01 11:31:00 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:31:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-01 11:31:00 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-01 11:31:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-01 11:31:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-01 11:31:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 2
,2017-08-01 11:31:00 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 2''
,# teardown
,2017-08-01 11:31:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-01 11:31:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-01 11:31:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:31:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-01 11:31:00 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-01 11:31:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-01 11:31:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-01 11:31:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# check latest peer discovery
,2017-08-01 11:31:00 - DEBUG CoordinatedClient: 'test was skipped, name: 'check latest peer discovery''
,# teardown
,2017-08-01 11:31:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-01 11:31:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-01 11:31:00 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:31:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-01 11:31:00 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-01 11:31:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-01 11:31:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-01 11:31:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Set up for no peer discovery test
,2017-08-01 11:31:00 - DEBUG CoordinatedClient: 'test was skipped, name: 'Set up for no peer discovery test''
,# teardown
,2017-08-01 11:31:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-01 11:31:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-01 11:31:01 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:31:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-01 11:31:01 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-01 11:31:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-01 11:31:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-01 11:31:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# no peer discovery
,2017-08-01 11:31:01 - DEBUG CoordinatedClient: 'test was skipped, name: 'no peer discovery''
,# teardown
,2017-08-01 11:31:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-01 11:31:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-01 11:31:01 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:31:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-01 11:31:01 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-01 11:31:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-01 11:31:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-01 11:31:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calling createNativeListener directly rejects
,2017-08-01 11:31:01 - DEBUG createNativeListener: 'Creating Native Server'
,2017-08-01 11:31:01 - DEBUG createNativeListener: 'listening 64535'
ok 151 Should throw
,# teardown
,2017-08-01 11:31:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-01 11:31:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-01 11:31:02 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits incomingConnectionState
,2017-08-01 11:31:02 - DEBUG createNativeListener: 'Creating Native Server'
,2017-08-01 11:31:02 - DEBUG createNativeListener: 'listening 64537'
,2017-08-01 11:31:02 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-08-01 11:31:02 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 152 initial connection state should be CONNECTED
,2017-08-01 11:31:02 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 153 final connection state should be DISCONNECTED
,# teardown
,2017-08-01 11:31:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-01 11:31:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-01 11:31:02 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits routerPortConnectionFailed
,2017-08-01 11:31:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-01 11:31:02 - DEBUG createNativeListener: 'Creating Native Server'
,2017-08-01 11:31:02 - DEBUG createNativeListener: 'listening 64540'
,2017-08-01 11:31:02 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-08-01 11:31:02 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-08-01 11:31:02 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-08-01 11:31:02 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - error Error: connect ECONNREFUSED'
,ok 154 tried to connect to right port
,ok 155 failed due to refused connection
,ok 156 routerPortConnectionFailed is emitted
,# teardown
,2017-08-01 11:31:02 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-08-01 11:31:02 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-08-01 11:31:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-01 11:31:02 - DEBUG createNativeListener: 'Native Server - close'
2017-08-01 11:31:02 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-08-01 11:31:02 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server connections all up
,2017-08-01 11:31:02 - DEBUG createNativeListener: 'Creating Native Server'
2017-08-01 11:31:02 - DEBUG createNativeListener: 'listening 64544'
,2017-08-01 11:31:02 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-08-01 11:31:02 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-08-01 11:31:02 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2017-08-01 11:31:02 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,ok 157 Send/recvd #1 should be equal length
,ok 158 Send/recvd #1 should be same
,ok 159 Send/recvd #2 should be equal length
,ok 160 Send/recvd #2 should be same
,ok 161 Should be exactly 2 client sockets
,# teardown
,2017-08-01 11:31:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-01 11:31:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-01 11:31:03 - DEBUG createNativeListener: 'Native Server - close'
,2017-08-01 11:31:03 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-08-01 11:31:03 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
,2017-08-01 11:31:03 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-08-01 11:31:03 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,2017-08-01 11:31:03 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-08-01 11:31:03 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# native server - closing incoming stream cleans outgoing socket
,2017-08-01 11:31:03 - DEBUG createNativeListener: 'Creating Native Server'
,2017-08-01 11:31:03 - DEBUG createNativeListener: 'listening 64549'
,2017-08-01 11:31:03 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-08-01 11:31:03 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-08-01 11:31:03 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-08-01 11:31:03 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
2017-08-01 11:31:03 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,ok 162 socket shouldn't close until after stream
ok 163 incoming remains open
# teardown
,2017-08-01 11:31:03 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-08-01 11:31:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-01 11:31:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-01 11:31:03 - DEBUG createNativeListener: 'Native Server - close'
2017-08-01 11:31:03, - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-08-01 11:31:03 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing incoming connection cleans outgoing socket
,2017-08-01 11:31:03 - DEBUG createNativeListener: 'Creating Native Server'
,2017-08-01 11:31:03 - DEBUG createNativeListener: 'listening 64553'
,2017-08-01 11:31:03 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-08-01 11:31:03 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 164 we should not have gotten an error
,2017-08-01 11:31:04 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-08-01 11:31:04 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2017-08-01 11:31:04 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - cl,ose'
,ok 165 socket shouldn't close until after incoming
ok 166 incoming is cleaned up
# teardown
,2017-08-01 11:31:04 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-08-01 11:31:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-01 11:31:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-01 11:31:04 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - closing outgoing socket cleans associated mux stream
,2017-08-01 11:31:04 - DEBUG createNativeListener: 'Creating Native Server'
,2017-08-01 11:31:04 - DEBUG createNativeListener: 'listening 64557'
,2017-08-01 11:31:04 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-08-01 11:31:04 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-08-01 11:31:04 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-08-01 11:31:04 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
2017-08-01 11:31:04 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node -, 0 - 0 - closed'
2017-08-01 11:31:04 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,ok 167 stream was closed
ok 168 incoming should survive
ok 169 mux should have no streams
,# teardown
,2017-08-01 11:31:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-01 11:31:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-01 11:31:04 - DEBUG createNativeListener: 'Native Server - close'
,2017-08-01 11:31:04 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-08-01 11:31:04 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing the whole server cleans everything up
,2017-08-01 11:31:04 - DEBUG createNativeListener: 'Creating Native Server'
,2017-08-01 11:31:04 - DEBUG createNativeListener: 'listening 64561'
,2017-08-01 11:31:04 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-08-01 11:31:04 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 170 we should not have gotten an error
,2017-08-01 11:31:04 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 171 Buffers are identical
,2017-08-01 11:31:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-01 11:31:04 - DEBUG createNativeListener: 'Native Server - close'
,2017-08-01 11:31:04 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-08-01 11:31:04 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 172 native server is nulled out
,ok 173 native server should be closed
,ok 174 incoming has been removed
,ok 175 Incoming should be done
,ok 176 The mux object should be closed
,ok 177 The mux stream should be closed
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# teardown
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-08-01 11:31:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - we can get a ton of connections and data through and still clean up the server completely
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'Creating Native Server'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'listening 64565'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - created'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - created'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - created'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - created'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - created'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - created'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - created'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - created'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - created'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - created'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - created'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - created'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - created'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - created'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - created'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - created'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - created'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - created'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - created'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - created'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - created'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - created'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - created'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - created'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - created'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - created'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - created'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - created'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - created'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - created'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - created'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - created'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - created'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - created'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - created'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - created'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - created'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - created'
,2017-08-01 11:31:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'Native Server - close'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - closed'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - closed'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - closed'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - closed'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - closed'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - closed'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - closed'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - closed'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - closed'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - closed'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - closed'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - closed'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - closed'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - closed'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - closed'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - closed'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - closed'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - closed'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - closed'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - closed'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - closed'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - closed'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - closed'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - closed'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - closed'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - closed'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - closed'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - closed'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - closed'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - closed'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - closed'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - closed'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - closed'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - closed'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - closed'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - closed'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - closed'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - closed'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,ok 178 native server is nulled out
,ok 179 native server should be closed
,ok 180 incoming has been removed
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - close'
2017-08-01 11:31:05 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - close'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - close'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - close'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - close'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - close'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - close'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - close'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - close'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - close'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - close'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - close'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - close'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - close'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - close'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - close'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - close'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - close'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - close'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - close'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - close'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - close'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - close'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - close'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - close'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - close'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - close'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - close'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - close'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - close'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - close'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - close'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - close'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - close'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - close'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - close'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - close'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - close'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-08-01 11:31:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - simulate mux failure, make sure everything is cleaned up
,2017-08-01 11:31:06 - DEBUG createNativeListener: 'Creating Native Server'
,2017-08-01 11:31:06 - DEBUG createNativeListener: 'listening 64617'
,2017-08-01 11:31:06 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-08-01 11:31:06 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 181 we should not have gotten an error
,2017-08-01 11:31:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 182 Buffers are identical
2017-08-01 11:31:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2017-08-01 11:31:06 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client co,nnection <-> Mux - 0 - close'
,2017-08-01 11:31:06 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 183 server should be fine
ok 184 server should be open
ok 185 incoming has been removed
ok 186 The mux object should be clos,ed
ok 187 The mux stream should be closed
2017-08-01 11:31:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-08-01 11:31:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-01 11:31:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-01 11:31:07 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - timing out the incoming connection cleans everything up
,2017-08-01 11:31:07 - DEBUG createNativeListener: 'Creating Native Server'
2017-08-01 11:31:07 - DEBUG createNativeListener: 'listening 64621'
,2017-08-01 11:31:07 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-08-01 11:31:07 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 188 we should not have gotten an error
,2017-08-01 11:31:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 189 Buffers are identical
,2017-08-01 11:31:07 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - incoming socket timeout'
2017-08-01 11:31:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to ,node - 0 - 0 - closed'
2017-08-01 11:31:07 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2017-08-01 11:31:07 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux, - 0 - close'
ok 190 server should be fine
ok 191 server should be open
ok 192 incoming has been removed
ok 193 The mux object should be closed
ok 194 The mux stream should be closed
,# teardown
,2017-08-01 11:31:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-08-01 11:31:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-01 11:31:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-01 11:31:07 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# can create servers manager
,ok 195 serversManager must not be null
,ok 196 serversManager must be an object
,# teardown
,# setup
,# calling stop without start causes error
,ok 197 We need to call start first
,# teardown
,# setup
,# can start/stop servers manager
,2017-08-01 11:31:08 - DEBUG createNativeListener: 'Creating Native Server'
2017-08-01 11:31:08 - DEBUG createNativeListener: 'listening 64624'
,ok 198 port must be in range
,# teardown
,2017-08-01 11:31:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-01 11:31:08 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# starting twice resolves with listening port
,2017-08-01 11:31:08 - DEBUG createNativeListener: 'Creating Native Server'
2017-08-01 11:31:08 - DEBUG createNativeListener: 'listening 64625'
ok 199 second start should return same port
,# teardown
,2017-08-01 11:31:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-01 11:31:08 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminateIncomingConnection will terminate a connection
,2017-08-01 11:31:08 - DEBUG createNativeListener: 'Creating Native Server'
,2017-08-01 11:31:08 - DEBUG createNativeListener: 'listening 64627'
,2017-08-01 11:31:08 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-08-01 11:31:08 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 200 we should be connected
2017-08-01 11:31:08 - DEB,UG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 201 now we are disconnected
,2017-08-01 11:31:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# teardown
,2017-08-01 11:31:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-01 11:31:08 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminate an Outgoing connection
,2017-08-01 11:31:09 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 32'
ok 202 Passed bogus id
2017-08-01 11:31:09 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port, 901'
ok 203 Passed good id but bogus port
2017-08-01 11:31:09 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 900'
ok 204 Passed right context
ok 205 Right server
ok 206 No error should be set
ok 207 Ret,ry should be false
ok 208 We called close server
,# teardown
,# setup
,# Single local http request
,listening on 64629
,ok 209 should be equal
# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:31:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:31:09 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:31:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-08-01 11:31:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:31:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-01 11:31:09 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-01 11:31:09 - DEBUG thaliMobileNativeWrapper: 'Method disc,overyAdvertisingStateUpdateNonTCP registered to native'
2017-08-01 11:31:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:31:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-01 11:31:09 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-01 11:31:09 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-01 11:31:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-01 11:31:09 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Single coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "DD00B2C6-79FA-4A27-BEDA-C0FD1F4C1817", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:DD00B2C6-79FA-4A27-BEDA-C0FD1F4C1817
2017-08-01 11:31:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-01 11:31:09 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-01 11:31:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 210 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:0516D8BE-20A3-4E3D-AC6A-090E4CDC6FEF
[Tha,l,iCore] Browser.startListening
2017-08-01 11:31:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-08-01 11:31:09 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-01 11:31:09 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 211 Can call startListeningForAdvertisements without error
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D9C5C18B-152B-4BD5-858E-56BE4F5FEE23
[ThaliCore] Advertiser: session connected Peer(uuid: "DD00B2C6-79FA-4A27-BEDA-C0FD1F4C1817", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:D9C5C18B-152B-4BD5-858E-56BE4F5FEE23 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DD00B2C6-79FA-4A27-BEDA-C0FD1F4C1817:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DD00B2C6-79FA-4A27-BEDA-C0FD1F4C1817", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5AE67C3A-6330-44AA-8E2E-D189F55382F0:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5AE67C3A-6330-44AA-8E2E-D189F55382F0", generation: 0)
2017-08-01 11:31:11 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"5AE67C3A-6330-44AA-8E2E-D189F55382F0","generation":0}'
2017-08-01 11:31:11 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 5AE67C3A-6330-44AA-8E2E-D189F55382F0, (syncValue: yntzPhWX0vlbg1hqu0ozuOHSSoNoBeXq)'
2017-08-01 11:31:11 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5AE67C3A-6330-44AA-8E2E-D189F55,382F0", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5AE67C3A-6330-44AA-8E2E-D189F55382F0", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected,:,) peer:5AE67C3A-6330-44AA-8E2E-D189F55382F0:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BA0DAC81-4292-4CAE-9C1B-4EA82DA7C4B9:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BA0DAC81-4292-4CAE-9C1B-4EA82DA7C4B9", generation: 0)
2017-08-01 11:31:11 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"BA0DAC81-4292-4CAE-9C1B-4EA82DA7C4B9","generation":0}'
2017-08-01 11:31:11 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-01 11:31:11 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:5AE67C3A-6330-44AA-8E2E-D189F55382F0:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D9C5C18B-152B-4BD5-858E-56BE4F5FEE23
,[ThaliCore] Session.session(_:peer:didChange:) peer:D9C5C18B-152B-4BD5-858E-56BE4F5FEE23 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:5AE67C3A-6330-44AA-8E2E-D189F55382F0:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:5AE67C3A-6330-44AA-8E2E-D189F55382F0:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "5AE67C3A-6330-44AA-8E2E-D189F55382F0", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:64634
2017-08-01 11:31:13 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"yntzPhWX0vlbg1hqu0ozuOHSSoNoBeXq",,"error":null,"portNumber":64634}'
2017-08-01 11:31:13 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'yntzPhWX0vlbg1hqu0ozuOHSSoNoBeXq', error: 'null', listeningPort: '64634''
,ok 212 should be equal
2017-08-01 11:31:13 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for BA0DAC81-4292-4CAE-9C1B-4EA82DA7C4B9 (syncValue: qD5vO7rnpD5W2pBL7PH9H2QYfChP5njq)'
2017-08-01 11:31:13 - DEBUG thaliMobileNativeTestUtils: 'Got 'mul,tiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "BA0DAC81-4292-4CAE-9C1B-4EA82DA7C4B9", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConn,ected:) Peer(uuid: "BA0DAC81-4292-4CAE-9C1B-4EA82DA7C4B9", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:BA0DAC81-4292-4CAE-9C1B-4EA82DA7C4B9:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocke,tTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:BA0DAC81-4292-4CAE-9C1B-4EA82DA7C4B9:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:DEEE1C2E-DFA1-45B3-997B-1D11C47CA194
[ThaliCore] Advertiser: session connected Peer(uuid: "DD00B2C6-79FA-4A27-BEDA-C0FD1F4C1817", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:DEEE1C2E-DFA1-45B3-997B-1D11C47CA194 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:BA0DAC81-4292-4CAE-9C1B-4EA82DA7C4B9:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:BA0DAC81-4292-4CAE-9C1B-4EA82DA7C4B9:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "BA0DAC81-4292-4CAE-9C1B-4EA82DA7C4B9", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:64638
,2017-08-01 11:31:16 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"qD5vO7rnpD5W2pBL7PH9H2QYfChP5njq","error":null,"portNumber":64638}'
,2017-08-01 11:31:16 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'qD5vO7rnpD5W2pBL7PH9H2QYfChP5njq', error: 'null', listeningPort: '64638''
,ok 213 should be equal
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:DEEE1C2E-DFA1-45B3-997B-1D11C47CA194
,[ThaliCore] Session.session(_:peer:didChange:) peer:DEEE1C2E-DFA1-45B3-997B-1D11C47CA194 state: connecting -> connected
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-08-01 11:31:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-01 11:31:21 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-01 11:31:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:DD00B2C6-79FA-4A27-BEDA-C0FD1F4C1817
,2017-08-01 11:31:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:31:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,[ThaliCore] BrowserManager.disconnect peer:5AE67C3A-6330-44AA-8E2E-D189F55382F0
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:64634
[ThaliCore] Session.disconnect() peer:5AE67C3A-6330-44AA-8E2E-D189F55382F0:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:DEEE1C2E-DFA1-45B3-997B-1D11C47CA194 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "DD00B2C6-79FA-4A27-BEDA-C0FD1F4C1817", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:DEEE1C2E-DFA1-45B3-997B-1D11C47CA194
,[ThaliCore] Session.session(_:peer:didChange:) peer:D9C5C18B-152B-4BD5-858E-56BE4F5FEE23 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "DD00B2C6-79FA-4A27-BEDA-C0FD1F4C1817", generation: 0)
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:5AE67C3A-6330-44AA-8E2E-D189F55382F0:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] BrowserManager.disconnect peer:BA0DAC81-4292-4CAE-9C1B-4EA82DA7C4B9
,[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:64638
[ThaliCore] Session.disconnect() peer:BA0DAC81-4292-4CAE-9C1B-4EA82DA7C4B9:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:DEEE1C2E-DFA1-45B3-997B-1D11C47CA194
[ThaliCore] Session.deinit peer:BA0DAC81-4292-4CAE-9C1B-4EA82DA7C4B9:0
[ThaliCore] BrowserRelay.deinit
2017-08-01 11:31:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-01 11:31:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-01 11:31:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-01 11:31:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:31:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-01 11:31:22 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-01 11:31:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-01 11:31:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-01 11:31:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Multiple local http requests
,listening on 64640
,ok 214 should be equal
,ok 215 should be equal
,ok 216 should be equal
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:31:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:31:23 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:31:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-08-01 11:31:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:31:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-01 11:31:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-01 11:31:23 - DEBUG thaliMobileNativeWrapper: 'Method disc,overyAdvertisingStateUpdateNonTCP registered to native'
2017-08-01 11:31:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:31:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-01 11:31:23 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-01 11:31:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-01 11:31:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-01 11:31:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Multiple coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "5DB0E0CB-D9D6-4C55-8AEE-54C6FEEBC6A2", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:5DB0E0CB-D9D6-4C55-8AEE-54C6FEEBC6A2
,2017-08-01 11:31:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-08-01 11:31:23 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-01 11:31:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 217 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:DCAE8889-B1C8-4300-B33A-1CA5F88D9114
,[ThaliCore] Browser.startListening
,2017-08-01 11:31:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-08-01 11:31:23 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-01 11:31:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5AE67C3A-6330-44AA-8E2E-D189F55382F0:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5AE67C3A-6330-44AA-8E2E-D189F55382F0", generation: 0)
,ok 218 Can call startListeningForAdvertisements without error
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BA0DAC81-4292-4CAE-9C1B-4EA82DA7C4B9:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BA0DAC81-4292-4CAE-9C1B-4EA82DA7C4B9", generation: 0)
2017-08-01 11:31:23 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"5AE67C3A-6330-44AA-8E2E-D189F55382F0","generation":0}'
,2017-08-01 11:31:23 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 5AE67C3A-6330-44AA-8E2E-D189F55382F0 (syncValue: u114MDlauREQL1uX5Gjb7idWO763osIO)'
,2017-08-01 11:31:23 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5AE67C3A-6330-44AA-8E2E-D189F55382F0", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5AE67C3A-6330-44AA-8E2E-D189F55382F0", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5AE67C3A-6330-44AA-8E2E-D189F55382F0:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-08-01 11:31:23 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"BA0DAC81-4292-4CAE-9C1B-4EA82DA7C4B9","generation":0}'
,2017-08-01 11:31:23 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-01 11:31:23 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:BA0DAC81-4292-4CAE-9C1B-4EA82DA7C4B9:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "BA0DAC81-4292-4CAE-9C1B-4EA82DA7C4B9", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscov,eryInfo:) found peer:5DB0E0CB-D9D6-4C55-8AEE-54C6FEEBC6A2:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5DB0E0CB-D9D6-4C55-8AEE-54C6FEEBC6A2", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:78615FF3-BB41-476C-AB03-7264399F5297:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "78615FF3-BB41-476C-AB03-7264399F5297", generation: 0)
2017-08-01 11:31:25 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"78615FF3-BB41-476C-AB03-7264399F5297","generation":0}'
2017-08-01 11:31:25 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-01 11:31:25 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A", g,eneration: 0)
2017-08-01 11:31:25 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A","generation":0}'
2017-08-01 11:31:25 - DEBUG thaliMobileNativeTestUtils: 'Already running ,t,est!'
2017-08-01 11:31:25 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-01 11:31:25 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:5AE67C3A-6330-44AA-8E2E-D189F55382F0:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:5A,E67C3A-6330-44AA-8E2E-D189F55382F0:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "5AE67C3A-6330-44AA-8E2E-D189F55382F0", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,AE67C3A-6330-44AA-8E2E-D189F55382F0", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5AE67C3A-6330-44AA-8E2E-D189F55382F0", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:5AE67C3A-6330-44AA-8E2E-D189F55382F0:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:5AE67C3A-6330-44AA-8E2E-D189F55382F0:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:5AE67C3A-6330-44AA-8E2E-D189F55382F0:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:5A,E67C3A-6330-44AA-8E2E-D189F55382F0:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "5AE67C3A-6330-44AA-8E2E-D189F55382F0", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,AE67C3A-6330-44AA-8E2E-D189F55382F0", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5AE67C3A-6330-44AA-8E2E-D189F55382F0", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:5AE67C3A-6330-44AA-8E2E-D189F55382F0:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:5AE67C3A-6330-44AA-8E2E-D189F55382F0:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:5AE67C3A-6330-44AA-8E2E-D189F55382F0:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:5A,E67C3A-6330-44AA-8E2E-D189F55382F0:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "5AE67C3A-6330-44AA-8E2E-D189F55382F0", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,AE67C3A-6330-44AA-8E2E-D189F55382F0", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5AE67C3A-6330-44AA-8E2E-D189F55382F0", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:5AE67C3A-6330-44AA-8E2E-D189F55382F0:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:5AE67C3A-6330-44AA-8E2E-D189F55382F0:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:5AE67C3A-6330-44AA-8E2E-D189F55382F0:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:5A,E67C3A-6330-44AA-8E2E-D189F55382F0:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "5AE67C3A-6330-44AA-8E2E-D189F55382F0", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:5AE67C3A,-6330-44AA-8E2E-D189F55382F0 error: max retries exceeded
2017-08-01 11:31:34 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"u114MDlauREQL1uX5Gjb7idWO763osIO","error":"Connection could not be established","portNumber":null}'
2017-0,8-01 11:31:34 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'u114MDlauREQL1uX5Gjb7idWO763osIO', error: 'Connection could not be established', listeningPort: '%s''
,2017-08-01 11:31:34 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-08-01 11:31:34 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 78615FF3-BB41-476C-AB03-7264399F5297 (syncValue: EyAAhPd,qz6pdHuP3p8FeoCetDpWwAoZV)'
2017-08-01 11:31:34 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "78615FF3-BB41-476C-AB03-7264399F5297", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "78615FF3-BB41-476C-AB03-7264399F5297", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:78615FF3-BB41,-476C-AB03-7264399F5297:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-08-01 11:31:34 - DEBUG thaliMobileNativeTestUtils: 'Already running tes,t,!'
2017-08-01 11:31:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:5AE67C3A-6330-44AA-8E2E-D189F55382F0:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:78615FF3-BB41-476C-AB03-7264399F5297:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:78615FF3-BB41-476C-AB03-7264399F5297:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:78615FF3-BB41-476C-AB03-7264399F5297:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "78615FF3-BB41-476C-AB03-7264399F5297", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:64658
2017-08-01 11:31:37 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"EyAAhPdqz6pdHuP3p8FeoCetDpWwAoZV",,"error":null,"portNumber":64658}'
2017-08-01 11:31:37 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'EyAAhPdqz6pdHuP3p8FeoCetDpWwAoZV', error: 'null', listeningPort: '64658''
,ok 219 should be equal
ok 220 should be equal
ok 221 should be equal
2017-08-01 11:31:37 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A (syncValue: kh3pRzs1U9gXrGvgVFcpb2afxguYIJFD)'
2017-08-01 11:31:,37 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A", generation: 0) creating a new relay
[ThaliCore] Browser.i,nviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
2017-08-01 11:31:37 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:84056088-3896-48BB-8E52-4509E9BC57C6
[ThaliCore] Advertiser: session connected Peer(uuid: "5DB0E0CB-D9D6-4C55-8AEE-54C6FEEBC6A2", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:84056088-3896-48BB-8E52-4509E9BC57C6 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:5AE67C3A-6330-44AA-8E2E-D189F55382F0:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "5AE67C3A-6330-44AA-8E2E-D189F55382F0", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:84056088-3896-48BB-8E52-4509E9BC57C6
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:84056088-3896-48BB-8E52-4509E9BC57C6 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:64664
,2017-08-01 11:31:40 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"kh3pRzs1U9gXrGvgVFcpb2afxguYIJFD","error":null,"portNumber":64664}'
,2017-08-01 11:31:40 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'kh3pRzs1U9gXrGvgVFcpb2afxguYIJFD', error: 'null', listeningPort: '64664''
,ok 222 should be equal
ok 223 should be equal
,ok 224 should be equal
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:79CCE9F1-59ED-41FF-92B4-823C0E611D3D
[ThaliCore] Advertiser: session connected Peer(uuid: "5DB0E0CB-D9D6-4C55-8AEE-54C6FEEBC6A2", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:79CCE9F1-59ED-41FF-92B4-823C0E611D3D state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:79CCE9F1-59ED-41FF-92B4-823C0E611D3D
,[ThaliCore] Session.session(_:peer:didChange:) peer:79CCE9F1-59ED-41FF-92B4-823C0E611D3D state: connecting -> connected
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-01 11:31:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-01 ,11:31:49 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-08-01 11:31:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:5DB0E0CB-D9D6-4C55-8AEE-5,4C6FEEBC6A2
2017-08-01 11:31:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:31:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.disconnect peer:78615FF3-BB41-476C-AB03-7264399F5297
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCo,re] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:64658
[ThaliCore] Session.disconnect() peer:78615FF3-BB41-476C-AB03-7264399F5297:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TC,PListener.deinit
,[ThaliCore] Session.deinit peer:78615FF3-BB41-476C-AB03-7264399F5297:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] BrowserManager.disconnect peer:4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A
[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:64664
[ThaliCore] Session.disconnect() peer:4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:79CCE9F1-59ED-41FF-92B4-823C0E611D3D state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "5DB0E0CB-D9D6-4C55-8AEE-54C6FEEBC6A2", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:79CCE9F1-59ED-41FF-92B4-823C0E611D3D
[ThaliCore] Advert,iserRelay.deinit
[ThaliCore] Session.session(_:peer:didChange:) peer:84056088-3896-48BB-8E52-4509E9BC57C6 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "5DB0E0CB-D9D6-4C55-8AEE-54C6FEEBC6A2", generation: 0)
,[ThaliCore] Session.deinit peer:4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A:0
[ThaliCore] BrowserRelay.deinit
2017-08-01 11:31:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-01 11:31:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvai,labilityChanged registered to native'
,2017-08-01 11:31:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-01 11:31:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:31:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-01 11:31:49 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:31:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-01 11:31:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
2017-08-01 11:31:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# #startListeningForAdvertisements should fail if start not called
,ok 225 specific error should be returned
,# teardown
,[ThaliCore] Session.deinit peer:79CCE9F1-59ED-41FF-92B4-823C0E611D3D
,ok 226 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:31:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:31:50 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:31:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-08-01 11:31:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:31:50 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-01 11:31:50 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-01 11:31:50 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:31:50 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-01 11:31:50 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-01 11:31:50 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-01 11:31:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-01 11:31:50 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# #startUpdateAdvertisingAndListening should fail if start not called
,ok 227 specific error should be returned
,# teardown
,ok 228 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:31:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:31:51 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-01 11:31:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:31:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:31:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-01 11:31:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-01 11:31:51 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:31:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-01 11:31:51 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-01 11:31:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-01 11:31:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-01 11:31:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #stopListeningForAdvertisements many times
,2017-08-01 11:31:51 - DEBUG CoordinatedClient: 'test was skipped, name: 'should be able to call #stopListeningForAdvertisements many times''
,# teardown
,ok 229 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:31:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:31:51 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:31:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-08-01 11:31:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:31:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-01 11:31:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-01 11:31:51 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:31:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-01 11:31:51 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-01 11:31:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-01 11:31:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-01 11:31:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #startListeningForAdvertisements many times
,2017-08-01 11:31:51 - DEBUG thaliMobileNativeWrapper: 'listening 64668'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:AEC4FA88-70C3-4795-9303-A0764EBE290C
[ThaliCore] Browser.startListening
,2017-08-01 11:31:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-01 11:31:51 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-01 11:31:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 230 no errors
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-08-01 11:31:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-01 11:31:51 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-08-01 11:31:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 231 still no errors
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A", generation: 0)
2017-08-01 11:31:51 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A","generation":0}]'
2017-08-01 11:31:51 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:78615FF3-BB41-476C-AB03-7264399F5297:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "78615FF3-BB41-476C-AB03-7264399F5297", generation: 0)
2017-08-01 11:31:51 - DEBUG t,haliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A","peerAvailable":true,"generation":0,"portNumber":null}'
2017-08-01 11:31:51 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-08-01 11:31:51 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"78615FF3-BB41-476C-AB03-7264399F5297","generation":0}]'
,2017-08-01 11:31:51 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"78615FF3-BB41-476C-AB03-7264399F5297","generation":0}'
,2017-08-01 11:31:51 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"78615FF3-BB41-476C-AB03-7264399F5297","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-01 11:31:51 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"78615FF3-BB41-476C-AB03-7264399F5297","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:31:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-01 11:31:52 - INFO thaliMobile: 'Received state ({"d,iscoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-01 11:31:52 - INFO ,thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
2017-08-01 11:31:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:31:52 - INFO thaliMobile: 'Filtered out discoveryAdvertis,ingStateUpdate (was in stopped state).'
2017-08-01 11:31:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 232 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:31:52 - DEBUG thaliMobileNativeWrap,per: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:31:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising,()
2017-08-01 11:31:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:31:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped s,t,ate).'
,2017-08-01 11:31:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-01 11:31:52 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-01 11:31:52 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:31:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:31:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:31:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:31:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:31:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-08-01 11:31:52 - DEBUG thaliMobileNativeWrapper: 'listening 64669'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "75D7E045-8C01-4878-A6B7-A73B39ECCBD3", generation: 0)
[ThaliCore] Advertiser.startA,dvertising with peerID:75D7E045-8C01-4878-A6B7-A73B39ECCBD3
2017-08-01 11:31:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-01 11:31:52 - INFO thaliMobile: 'Receive,d state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-01 11:3,1:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 233 no errors
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "75D7E045-8C01-4878-A6B7-A73B39ECCBD3", ge,n,eration: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:75D7E045-8C01-4878-A6B7-A73B39ECCBD3
,2017-08-01 11:31:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-08-01 11:31:52 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-08-01 11:31:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 234 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:75D7E045-8C01-4878-A6B7-A73B39ECCBD3
[ThaliCore] Advertiser.stopAdvertising() peerID:75D7E045-8C01-4878-A6B7-A73B39ECCBD3
2017-08-01 11:31:52 - DEBUG thaliMo,bileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:31:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stop,ListeningForAdvertisements()
2017-08-01 11:31:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:31:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-01 11:31:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 235 must be stopped
[ThaliCore] BrowserManager.stopListenin,gForAdvertisements()
2017-08-01 11:31:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:31:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate ,(was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:31:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:31:52 - INFO thaliM,obile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-01 11:31:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-01 11:31:52 - DEBUG thaliMobileNativeWrapper: 'Method disco,v,eryAdvertisingStateUpdateNonTCP registered to native'
2017-08-01 11:31:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:31:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:31:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:31:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:31:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:31:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #stopAdvertisingAndListening many times
,2017-08-01 11:31:53 - DEBUG thaliMobileNativeWrapper: 'listening 64672'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:31:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingAct,ive":false}'
2017-08-01 11:31:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 236 no errors
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:31:53 - DEBUG thaliMobileNativeWrapper: 'discover,yAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:31:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 237 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:31:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:31:53 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:31:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-08-01 11:31:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:31:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 238 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:31:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonT,CP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:31:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:31:53 - DEBUG thaliMobi,leNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:31:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:31:53 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-01 11:31:53 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-01 11:31:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:31:53 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:31:53 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:31:53 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:31:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:31:53 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can get the network status before starting
,ok 239 network status should have certain non-empty properties
,# teardown
,ok 240 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:31:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:31:53 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:31:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-08-01 11:31:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:31:53 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-01 11:31:53 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-01 11:31:53 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:31:53 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:31:53 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:31:53 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:31:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:31:53 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# error returned with bad router
,2017-08-01 11:31:53 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a string'
ok 241 specific error expected
,# teardown
,ok 242 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:31:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:31:53 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:31:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-08-01 11:31:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:31:53 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-01 11:31:53 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-01 11:31:53 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:31:53 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-01 11:31:53 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-01 11:31:53 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-01 11:31:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:31:53 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# all services are started when we call start
,2017-08-01 11:31:54 - DEBUG thaliMobileNativeWrapper: 'listening 64673'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:462F68A4-2072-4DB1-A82B-DE60BD775C0F
[ThaliCore] Browser.st,artListening
2017-08-01 11:31:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-01 11:31:54 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-01 11:31:54 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "4EFF8AF6-B597-4DB3-BB5D-85AA7C3E440C", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID,:,4EFF8AF6-B597-4DB3-BB5D-85AA7C3E440C
,2017-08-01 11:31:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-08-01 11:31:54 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-01 11:31:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 243 all connection succeed
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:4EFF8AF6-B597-4DB3-BB5D-85AA7C3E440C
2017-08-01 11:31:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-01 11:31:54 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-01 11:31:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stop,Listening()
2017-08-01 11:31:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:31:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:31:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 244 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:31:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonT,CP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:31:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-01 11:31:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:31:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:31:54 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-01 11:31:54 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-01 11:31:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:31:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:31:54 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:31:54 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:31:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:31:54 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# TCP Servers Manager should be null when we call start on iOS
,2017-08-01 11:31:54 - DEBUG thaliMobileNativeWrapper: 'listening 64676'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:E54AF862-B289-431B-A13C-0EBA0D6017E7
,[ThaliCore] Browser.startListening
,2017-08-01 11:31:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-01 11:31:54 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-08-01 11:31:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "792CE43C-A595-4CDB-9516-9791B5616D89", genera,tion: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:792CE43C-A595-4CDB-9516-9791B5616D89
,2017-08-01 11:31:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-08-01 11:31:54 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-01 11:31:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 245 TCP Servers Manager doesn't exists
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:792CE43C-A595-4CDB-9516-9791B5616D89
,2017-08-01 11:31:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-01 11:31:54 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-01 11:31:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-01 11:31:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:31:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:31:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 246 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-01 11:31:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:31:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-01 11:31:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:31:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:31:54 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-01 11:31:54 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-01 11:31:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:31:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:31:54 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:31:54 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:31:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:31:54 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# all services are stopped when we call stop
,2017-08-01 11:31:55 - DEBUG thaliMobileNativeWrapper: 'listening 64678'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:303291C3-4D6E-43C4-A518-86A04E3759C5
,[ThaliCore] Browser.startListening
,2017-08-01 11:31:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-01 11:31:55 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-01 11:31:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "DBB4C430-4803-4C2C-907C-633F6F96A826", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:DBB4C430-4803-4C2C-907C-633F6F96A826
,2017-08-01 11:31:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-08-01 11:31:55 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-08-01 11:31:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:DBB4C430-4803-4C2C-907C-633F6F96A826
,2017-08-01 11:31:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-01 11:31:55 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-01 11:31:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-08-01 11:31:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:31:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:31:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 247 is stopped after calling stop
,ok 248 connection should fail after stopping
,# teardown
,ok 249 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-01 11:31:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:31:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-01 11:31:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:31:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:31:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-01 11:31:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-01 11:31:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:31:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-01 11:31:55 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:31:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:31:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:31:55 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateConnection is properly hooked up
,2017-08-01 11:31:55 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateConnection is properly hooked up''
,# teardown
,ok 250 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:31:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:31:55 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:31:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-08-01 11:31:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:31:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-01 11:31:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-01 11:31:55 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:31:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-01 11:31:55 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-01 11:31:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-01 11:31:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-01 11:31:55 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateConnection is return error if we get called on iOS
,ok 251 error description matches
,# teardown
,ok 252 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:31:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:31:56 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:31:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-08-01 11:31:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:31:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-01 11:31:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-01 11:31:56 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:31:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:31:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:31:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:31:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:31:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is properly hooked up
,2017-08-01 11:31:56 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateListener is properly hooked up''
,# teardown
,ok 253 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:31:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:31:56 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:31:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-08-01 11:31:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:31:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-01 11:31:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-01 11:31:56 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:31:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-01 11:31:56 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-01 11:31:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-01 11:31:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-01 11:31:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is return error if we get called on iOS
,ok 254 error description matches
,# teardown
,ok 255 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:31:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:31:56 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-01 11:31:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:31:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-08-01 11:31:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-01 11:31:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-01 11:31:56 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:31:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:31:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:31:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:31:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:31:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure we actually call kill connections properly
,ok 256 IMPLEMENT ME!!!!!!
,# teardown
,ok 257 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:31:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:31:57 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:31:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-08-01 11:31:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:31:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-01 11:31:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-01 11:31:57 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:31:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-01 11:31:57 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-01 11:31:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-01 11:31:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-01 11:31:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
,2017-08-01 11:31:57 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''
,# teardown
,ok 258 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:31:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:31:57 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-01 11:31:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:31:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-08-01 11:31:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-01 11:31:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-01 11:31:57 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:31:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-01 11:31:57 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-01 11:31:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-01 11:31:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-01 11:31:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager
,2017-08-01 11:31:58 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''
,# teardown
,ok 259 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:31:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:31:58 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-01 11:31:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:31:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-08-01 11:31:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-01 11:31:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-01 11:31:58 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:31:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-01 11:31:58 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-08-01 11:31:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-01 11:31:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-01 11:31:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from multiConnectConnection
,2017-08-01 11:31:58 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 260 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:31:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:31:58 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:31:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:31:58 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:31:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-01 11:31:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-01 11:31:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:31:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-01 11:31:58 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-08-01 11:31:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:31:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:31:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection
,2017-08-01 11:31:59 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 261 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:31:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:31:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-01 11:31:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:31:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-08-01 11:31:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-01 11:31:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-01 11:31:59 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:31:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-01 11:31:59 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-01 11:31:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-01 11:31:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-01 11:31:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved
,ok 262 NOT IMPLEMENTED # SKIP
,# teardown
,ok 263 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:31:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:31:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-01 11:31:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:31:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:31:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-01 11:31:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-01 11:31:59 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:31:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-01 11:31:59 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-01 11:31:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-01 11:31:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-01 11:31:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure bad PSK connections fail
,2017-08-01 11:31:59 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure bad PSK connections fail''
,# teardown
,ok 264 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:31:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:31:59 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:31:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-08-01 11:31:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:31:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-01 11:31:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-01 11:32:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:32:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:32:00 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:32:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:32:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:32:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peer changes handled from a queue
,2017-08-01 11:32:00 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer changes handled from a queue''
,# teardown
,ok 265 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:32:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:32:00 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:32:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-08-01 11:32:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:32:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-01 11:32:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-01 11:32:00 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:32:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:32:00 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:32:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:32:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:32:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# relaying discoveryAdvertisingStateUpdateNonTCP
,2017-08-01 11:32:00 - DEBUG CoordinatedClient: 'test was skipped, name: 'relaying discoveryAdvertisingStateUpdateNonTCP''
,# teardown
,ok 266 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:32:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:32:00 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:32:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-08-01 11:32:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:32:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-01 11:32:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-01 11:32:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:32:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-01 11:32:00 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-01 11:32:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-01 11:32:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-01 11:32:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received
,2017-08-01 11:32:00 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''
,# teardown
,ok 267 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-01 11:32:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:32:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-01 11:32:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:32:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:32:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-01 11:32:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-01 11:32:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:32:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:32:00 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:32:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:32:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:32:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# we successfully receive and replay discoveryAdvertisingStateUpdate
,2017-08-01 11:32:01 - DEBUG thaliMobileNativeWrapper: 'listening 64681'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:F0032001-0A05-4552-BBEC-896355F6FD9A
[ThaliCore] Browser.st,artListening
2017-08-01 11:32:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-01 11:32:01 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-01 11:32:01 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
ok 268 discoveryActive matches
ok 269 advertisingActive matches
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:32:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonT,C,P: {"discoveryActive":true,"advertisingActive":false}'
2017-08-01 11:32:01 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-01 11:32:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisemen,ts()
[ThaliCore] Browser.stopListening()
2017-08-01 11:32:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:32:01 - INFO thaliMobile: 'Filtered out discoveryAd,vertisingStateUpdate (was in stopped state).'
ok 270 discoveryActive matches
,ok 271 advertisingActive matches
,2017-08-01 11:32:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-01 11:32:01 - DEBUG thaliMobileNativeWrapper: 'listening 64682'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "51A9A700-5025-49B2-8650-B74673B1470A", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:51A9A700-5025-49B2-8650-B74673B1470A
,2017-08-01 11:32:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-01 11:32:01 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-01 11:32:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 272 discoveryActive matches
ok 273 advertisingActive matches
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:51A9A700-5025-49B2-8650-B74673B1470A
,2017-08-01 11:32:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:32:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 274 discoveryActive matches
,ok 275 advertisingActive matches
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-01 11:32:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:32:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:32:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-01 11:32:01 - DEBUG thaliMobileNativeWrapper: 'listening 64684'
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:32:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:32:01 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:32:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-08-01 11:32:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-01 11:32:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 276 must be stopped
[ThaliCore] BrowserManager.stopLi,steningForAdvertisements()
2017-08-01 11:32:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:32:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingState,U,pdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:32:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:32:01 - INFO ,thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:32:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-01 11:32:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-01 11:32:01 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:32:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:32:01 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:32:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:32:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:32:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS
,2017-08-01 11:32:01 - DEBUG thaliMobileNativeWrapper: 'listening 64685'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:701D5D8B-270B-43D4-B09F-8EE9F7935D49
[ThaliCore] Browser.startListening
2017-08-01 11:32:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-01 11:32:01 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-01 11:32:01 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "830B4368-4E9E-4860-A257-F1167467DB20", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID,:,830B4368-4E9E-4860-A257-F1167467DB20
,2017-08-01 11:32:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-08-01 11:32:01 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-01 11:32:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:78615FF3-BB41-476C-AB03-7264399F5297:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "78615FF3-BB41-476C-AB03-7264399F5297", generation: 0)
,2017-08-01 11:32:01 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A","generation":0}]'
,2017-08-01 11:32:01 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A","generation":0}'
,2017-08-01 11:32:01 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"78615FF3-BB41-476C-AB03-7264399F5297","generation":0}]'
,2017-08-01 11:32:01 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"78615FF3-BB41-476C-AB03-7264399F5297","generation":0}'
,2017-08-01 11:32:01 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A","peerAvailable":true,"generation":0,"portNumber":null}'
,ok 277 portNumber equal null
,2017-08-01 11:32:01 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"78615FF3-BB41-476C-AB03-7264399F5297","peerAvailable":true,"generation":0,"portNumber":null}'
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CB72E643-E780-49C6-BEC0-4812224ED763:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CB72E643-E780-49C6-BEC0-4812224ED763", generation: 0)
,2017-08-01 11:32:02 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"CB72E643-E780-49C6-BEC0-4812224ED763","generation":0}]'
2017-08-01 11:32:02 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"CB72E643-E780-49C6-BEC0-4812224ED763","generation":0}'
,2017-08-01 11:32:02 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"CB72E643-E780-49C6-BEC0-4812224ED763","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-01 11:32:02 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"CB72E643-E780-49C6-BEC0-4812224ED763","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:830B4368-4E9E-4860-A257-F1167467DB20:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "830B4368-4E9E-4860-A257-F1167467DB20", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B75A076C-9F54-42F5-AD10-23C35D30B52B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B75A076C-9F54-42F5-AD10-23C35D30B52B", generation: 0)
2017-08-01 11:32:03 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"B75A076C-9F54-42F5-AD10-23C35D30B52B","generation":0}]'
2017-08-01 11:32:03 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"B75A076C-9F54-42F5-AD10-23C35D30B52B","generation":0}'
,2017-08-01 11:32:03 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"B75A076C-9F54-42F5-AD10-23C35D30B52B","peerAvailable":true,"generation":0,"portNumber":null}'
2017-08-01 11:32:03 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"B75A076C-9F54-42F5-AD10-23C35D30B52B","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:830B4368-4E9E-4860-A257-F1167467DB20
2017-08-01 11:32:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-01 11:32:03 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-01 11:32:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stop,Listening()
,2017-08-01 11:32:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:32:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:32:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 278 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-01 11:32:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:32:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-01 11:32:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:32:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:32:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-01 11:32:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-01 11:32:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:32:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:32:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:32:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:32:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:32:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can do HTTP requests between peers
,2017-08-01 11:32:03 - DEBUG CoordinatedClient: 'test was skipped, name: 'can do HTTP requests between peers''
,# teardown
,ok 279 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:32:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:32:03 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:32:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-08-01 11:32:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:32:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-01 11:32:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-01 11:32:03 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:32:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-01 11:32:03 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-01 11:32:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-01 11:32:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-01 11:32:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can still do HTTP requests between peers with coordinator
,2017-08-01 11:32:03 - DEBUG CoordinatedClient: 'test was skipped, name: 'can still do HTTP requests between peers with coordinator''
,# teardown
,ok 280 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:32:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:32:04 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:32:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-08-01 11:32:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:32:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-01 11:32:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-01 11:32:04 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:32:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-01 11:32:04 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-01 11:32:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-01 11:32:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-01 11:32:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calls correct starts when network changes
,2017-08-01 11:32:04 - DEBUG CoordinatedClient: 'test was skipped, name: 'calls correct starts when network changes''
,# teardown
,ok 281 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:32:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:32:04 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:32:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-08-01 11:32:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:32:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-01 11:32:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-01 11:32:04 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:32:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:32:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:32:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:32:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:32:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# test to coordinate connection cut
,# teardown
,ok 282 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:32:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:32:04 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:32:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-08-01 11:32:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:32:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-01 11:32:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-01 11:32:04 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:32:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:32:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:32:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:32:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:32:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can do HTTP requests after connections are cut
,2017-08-01 11:32:04 - DEBUG thaliMobileNativeWrapper: 'listening 64687'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:4EB868FD-A513-4CEA-8F7F-4469883FD307
,[ThaliCore] Browser.startListening
,2017-08-01 11:32:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-01 11:32:04 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-08-01 11:32:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "A434C687-B492-4444-B453-FF485E320B98", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:A434C687-B492-4444-B453-FF485E320B98
,2017-08-01 11:32:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-08-01 11:32:04 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-08-01 11:32:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:78615FF3-BB41-476C-AB03-7264399F5297:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "78615FF3-BB41-476C-AB03-7264399F5297", generation: 0)
2017-08-01 11:32:05 - DEBUG thaliMobileNativeWrapper: 'Rec,eived peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A","generation":0}]'
,2017-08-01 11:32:05 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A","generation":0}'
,2017-08-01 11:32:05 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"78615FF3-BB41-476C-AB03-7264399F5297","generation":0}]'
,2017-08-01 11:32:05 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"78615FF3-BB41-476C-AB03-7264399F5297","generation":0}'
,2017-08-01 11:32:05 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-01 11:32:05 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-01 11:32:05 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A (syncValue: R8rDi7MaBMX8n3hkmviOZVVAN9vKqzef)'
,2017-08-01 11:32:05 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-08-01 11:32:05 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"78615FF3-BB41-476C-AB03-7264399F5297","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-01 11:32:05 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"78615FF3-BB41-476C-AB03-7264399F5297","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B1D3177E-372A-4F29-8F3A-5AC9E326B4C9:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B1D3177E-372A-4F29-8F3A-5AC9E326B4C9", generation: 0)
2017-08-01 11:32:06 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"B1D3177E-372A-4F29-8F3A-5AC9E326B4C9","generation":0}]'
2017-08-01 11:32:06 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"B1D3177E-372A-4F29-8F3A-5AC9E326B4C9","generation":0}'
,2017-08-01 11:32:06 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"B1D3177E-372A-4F29-8F3A-5AC9E326B4C9","peerAvailable":true,"generation":0,"portNumber":null}'
2017-08-01 11:32:06 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"B1D3177E-372A-4F29-8F3A-5AC9E326B4C9","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-08-01 11:32:06 - DEBUG thaliMobileNativeTestUtils: 'We got a pe,er {"peerIdentifier":"B1D3177E-372A-4F29-8F3A-5AC9E326B4C9","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A434C687-B492-4444-B453-FF485E320B98:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A434C687-B492-4444-B453-FF485E320B98", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7EDC3305-B405-453E-BBDF-6FB61274F5F5:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7EDC3305-B405-453E-BBDF-6FB61274F5F5", generation: 0)
2017-08-01 11:32:06 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"7EDC3305-B405-453E-BBDF-6FB61274F5F5","generation":0}]'
2017-08-01 11:32:06 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"7EDC3305-B405-453E-BBDF-6FB61274F5F5","generation":0}'
,2017-08-01 11:32:06 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"7EDC3305-B405-453E-BBDF-6FB61274F5F5","peerAvailable":true,"generation":0,"portNumber":null}'
2017-08-01 11:32:06 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7EDC3305-B405-453E-BBDF-6FB61274F5F5","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-08-01 11:32:06 - DEBUG thaliMobileNativeTestUtils: 'We got a pe,er {"peerIdentifier":"7EDC3305-B405-453E-BBDF-6FB61274F5F5","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A", generation: 0)
2017-08-01 11:32:07 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A","generation":0}]'
2017-08-01 11:32:07 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A","generation":0}'
,2017-08-01 11:32:07 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-08-01 11:32:07 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:41,71E906-2DAC-40F0-BF8A-D6E8BEB2B32A:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,171E906-2DAC-40F0-BF8A-D6E8BEB2B32A", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-08-01 11:32:07 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"R8rDi7MaBMX8n3hkmviOZVVAN9vKqzef","error":"Peer is unavailable",,"portNumber":null}'
2017-08-01 11:32:07 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'R8rDi7MaBMX8n3hkmviOZVVAN9vKqzef', error: 'Peer is unavailable', listeningPort: '%s''
,2017-08-01 11:32:07 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-08-01 11:32:07 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 78615FF3-BB41-476C-AB03-7264399F5297 (syncValue: IzlnN7YJjwLdxl5BzH357vc,04UfaaOVL)'
2017-08-01 11:32:07 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "78615FF3-BB41-476C-AB03-7264399F5297", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "78615FF3-BB41-476C-AB03-7264399F5297", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:78615FF3-BB41-476C-AB03-72643,99F5297:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:78615FF3-BB41-476C-AB03-7264399F5297:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:78,615FF3-BB41-476C-AB03-7264399F5297:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "78615FF3-BB41-476C-AB03-7264399F5297", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,8615FF3-BB41-476C-AB03-7264399F5297", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "78615FF3-BB41-476C-AB03-7264399F5297", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:78615FF3-BB41-476C-AB03-7264399F5297:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:78615FF3-BB41-476C-AB03-7264399F5297:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1B30CDCA-9D2B-40A0-9159-6A95AB126B85
[ThaliCore] Advertiser: session connected Peer(uuid: "A434C687-B492-4444-B453-FF485E320B98", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:1B30CDCA-9D2B-40A0-9159-6A95AB126B85 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:1B30CDCA-9D2B-40A0-9159-6A95AB126B85
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:78615FF3-BB41-476C-AB03-7264399F5297:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "78615FF3-BB41-476C-AB03-7264399F5297", generation: 0)
,2017-08-01 11:32:12 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"78615FF3-BB41-476C-AB03-7264399F5297","generation":0}]'
,2017-08-01 11:32:12 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"78615FF3-BB41-476C-AB03-7264399F5297","generation":0}'
,2017-08-01 11:32:12 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"78615FF3-BB41-476C-AB03-7264399F5297","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-08-01 11:32:12 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"78615FF3-BB41-476C-AB03-7264399F5297","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:1B30CDCA-9D2B-40A0-9159-6A95AB126B85 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:1B30CDCA-9D2B-40A0-9159-6A95AB126B85
[ThaliCore] Session.startOutputStream(with:) peer:1B30CDCA-9D2B-40A0-9159-6A95AB126B85
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:18 [4, 10, 16, 18]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:78615FF3-BB41-476C-AB03-7264399F5297:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:78,615FF3-BB41-476C-AB03-7264399F5297:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "78615FF3-BB41-476C-AB03-7264399F5297", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,8615FF3-BB41-476C-AB03-7264399F5297", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "78615FF3-BB41-476C-AB03-7264399F5297", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-08-01 11:32:13 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"IzlnN7YJjwLdxl5BzH357vc04UfaaOVL","error":"Peer is unavailable",,"portNumber":null}'
2017-08-01 11:32:13 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'IzlnN7YJjwLdxl5BzH357vc04UfaaOVL', error: 'Peer is unavailable', listeningPort: '%s''
,2017-08-01 11:32:13 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-08-01 11:32:13 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B1D3177E-372A-4F29-8F3A-5AC9E326B4C9 (syncValue: unc7hcse25gG2dmHjUTsmcC,wL22oHm3j)'
2017-08-01 11:32:13 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B1D3177E-372A-4F29-8F3A-5AC9E326B4C9", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B1D3177E-372A-4F29-8F3A-5AC9E326B4C9", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B1D3177E-372A-4F29-8F3A-5AC9E,326B4C9:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:78615FF3-BB41-476C-AB03-7264399F5297:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:B1D3177E-372A-4F29-8F3A-5AC9E326B4C9:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B1D3177E-372A-4F29-8F3A-5AC9E326B4C9:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:B1D3177E-372A-4F29-8F3A-5AC9E326B4C9:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "B1D3177E-372A-4F29-8F3A-5AC9E326B4C9", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:64698
2017-08-01 11:32:16 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"unc7hcse25gG2dmHjUTsmcCwL22oHm3j",,"error":null,"portNumber":64698}'
2017-08-01 11:32:16 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'unc7hcse25gG2dmHjUTsmcCwL22oHm3j', error: 'null', listeningPort: '64698''
,2017-08-01 11:32:16 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B1D3177E-372A-4F29-8F3A-5AC9E326B4C9:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B1D3177E-372A-4F29-8F3A-5AC9E326B4C9:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:19 [4, 10, 16, 18, 19]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-08-01 11:32:16 - DEBUG testUtils: 'Got response data'
,2017-08-01 11:32:16 - DEBUG testUtils: 'Got end'
,ok 283 response body should match testData
,ok 284 must be started
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:A434C687-B492-4444-B453-FF485E320B98
2017-08-01 11:32:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-08-01 11:32:16 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-01 11:32:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stop,Listening()
2017-08-01 11:32:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:32:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-01 11:32:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 285 must be stopped
[ThaliCore] BrowserManager.stopListenin,gForAdvertisements()
2017-08-01 11:32:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:32:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate ,(was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:32:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:32:16 - INFO thaliM,obile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:B1D3177E-372A-4F29-8F3A-5AC9E326B4C9
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:64698
[ThaliCore] VirtualSocket.closeStreams() vsID:19
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[T,haliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescripti,on=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtu,al socket vsID:18
[ThaliCore] VirtualSocket.closeStreams() vsID:18
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
,[ThaliCore] VirtualSocket exited RunLoop vsID:19
[ThaliCore] Session.disconnect() peer:B1D3177E-372A-4F29-8F3A-5AC9E326B4C9:0
[ThaliCore] VirtualSocket.closeStreams() vsID:19
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecti,ng
[ThaliCore] VirtualSocket.deinit vsID:19 [4, 10, 16, 18]
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.deinit peer:B1D3177E-372A-4F29-8F3A-5AC9E326B4C9:0
[ThaliCore] BrowserRelay.deinit
,2017-08-01 11:32:16 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-01 11:32:16 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-01 11:32:16 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:18
[ThaliCore] VirtualSocket.deinit vsID:18 [4, 10, 16]
,2017-08-01 11:32:16 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:32:16 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:32:16 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:32:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:32:16 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:1B30CDCA-9D2B-40A0-9159-6A95AB126B85 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "A434C687-B492-4444-B453-FF485E320B98", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:1B30CDCA-9D2B-40A0-9159-6A95AB126B85
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:1B30CDCA-9D2B-40A0-9159-6A95AB126B85
,# will fail bad PSK connection between peers
,ok 286 FIX ME, PLEASE!!!
,# teardown
,ok 287 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:32:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:32:17 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:32:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-08-01 11:32:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:32:17 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-01 11:32:17 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-01 11:32:17 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:32:17 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-01 11:32:17 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-08-01 11:32:17 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-01 11:32:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-01 11:32:17 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We provide notification when a listener dies and we recreate it
,2017-08-01 11:32:18 - DEBUG CoordinatedClient: 'test was skipped, name: 'We provide notification when a listener dies and we recreate it''
,# teardown
,ok 288 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:32:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:32:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-01 11:32:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:32:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-08-01 11:32:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-01 11:32:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-01 11:32:18 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:32:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-01 11:32:18 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-01 11:32:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-01 11:32:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-01 11:32:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated
,2017-08-01 11:32:18 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated''
,# teardown
,ok 289 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:32:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:32:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:32:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:32:18 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:32:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-01 11:32:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-01 11:32:18 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:32:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-01 11:32:18 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-01 11:32:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:32:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:32:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,ok 290 ThaliMobile should be stopped
,# #startListeningForAdvertisements should fail if start not called
,ok 291 specific error should be returned
,# teardown
,2017-08-01 11:32:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"CB72E643-E780-49C6-BEC0-4812224ED763","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-08-01 11:32:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"B75A076C-9F54-42F5-AD10-23C35D30B52B","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-08-01 11:32:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"B1D3177E-372A-4F29-8F3A-5AC9E326B4C9","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-08-01 11:32:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"7EDC3305-B405-453E-BBDF-6FB61274F5F5","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 292 error should be null
,ok 293 error should be null
,# setup
,ok 294 ThaliMobile should be stopped
,# #startUpdateAdvertisingAndListening should fail if start not called
,ok 295 specific error should be returned
,# teardown
,ok 296 error should be null
,ok 297 error should be null
,# setup
,ok 298 ThaliMobile should be stopped
,# should be able to call #stopListeningForAdvertisements many times
,2017-08-01 11:32:19 - DEBUG thaliMobileNativeWrapper: 'listening 64700'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:32:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"ad,vertisingActive":false}'
ok 299 error should be null
ok 300 error should be null
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:32:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive,":false,"advertisingActive":false}'
ok 301 error should be null
ok 302 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-01 11:32:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:32:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-01 11:32:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:32:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:32:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 303 error should be null
ok 304 error should be null
,# setup
,ok 305 ThaliMobile should be stopped
,# should be able to call #startListeningForAdvertisements many times
,2017-08-01 11:32:20 - DEBUG thaliMobileNativeWrapper: 'listening 64701'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:E02B9425-EFE2-433B-BBBA-653B1E6535BA
[ThaliCore] Browser.st,artListening
2017-08-01 11:32:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
ok 306 error should be null
ok 307 error should be null
[ThaliCore] BrowserManager.startListe,ningForAdvertisements
2017-08-01 11:32:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
ok 308 error should be null
ok 309 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:32:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-01 11:32:20 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
,2017-08-01 11:32:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-01 11:32:20 - DEBUG thaliMobileNativeW,rapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:32:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-01 11:32:20 - DEBUG makeIntoCloseA,llServer: 'closeAll called on server'
,ok 310 error should be null
ok 311 error should be null
,# setup
,ok 312 ThaliMobile should be stopped
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-08-01 11:32:20 - DEBUG thaliMobileNativeWrapper: 'listening 64702'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "CF42421C-AC2C-47B5-9A02-1F79F9B6D3BC", generation: 0)
[ThaliCore] Advertiser.startA,dvertising with peerID:CF42421C-AC2C-47B5-9A02-1F79F9B6D3BC
2017-08-01 11:32:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 313 error should be null
ok 314 error should, be null
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "CF42421C-AC2C-47B5-9A02-1F79F9B6D3BC", generation: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:CF42421C-AC2C-47B5-9A02-1F79F9B6D3BC
20,17-08-01 11:32:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 315 error should be null
ok 316 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:CF42421C-AC2C-47B5-9A02-1F79F9B6D3BC
[ThaliCore] Advertiser.stopAdvertising() peerID:CF42421C-AC2C-47B5-9A02-1F79F9B6D3BC
2017-08-01 11:32:20 - DEBUG thaliMo,bileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:32:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:32:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:32:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-01 11:32:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 317 error should be null
,ok 318 error should be null
,# setup
,ok 319 ThaliMobile should be stopped
,# should be able to call #stopAdvertisingAndListening many times
,2017-08-01 11:32:21 - DEBUG thaliMobileNativeWrapper: 'listening 64705'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:32:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingAct,ive":false}'
ok 320 error should be null
ok 321 error should be null
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:32:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 322 error should be null
ok 323 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:32:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:32:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-01 11:32:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:32:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:32:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 324 error should be null
,ok 325 error should be null
,# setup
,ok 326 ThaliMobile should be stopped
,# #start - Causing native or wifi to fail will cause a promise reject 
,2017-08-01 11:32:21 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a Null'
,ok 327 This should not cause wifi to fail
,ok 328 native router should be bad
,# teardown
,ok 329 error should be null
ok 330 error should be null
,# setup
,ok 331 ThaliMobile should be stopped
,# #start should fail if called twice in a row
,2017-08-01 11:32:22 - DEBUG thaliMobileNativeWrapper: 'listening 64706'
ok 332 first call should succeed
ok 333 first call should succeed
ok 334 specific error should be returned
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:32:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:32:22 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-01 11:32:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:32:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-01 11:32:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 335 error should be null
ok 336 error should be null
,# setup
,ok 337 ThaliMobile should be stopped
,# #start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)
,2017-08-01 11:32:22 - DEBUG CoordinatedClient: 'test was skipped, name: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''
,# teardown
,ok 338 error should be null
,ok 339 error should be null
,# setup
,ok 340 ThaliMobile should be stopped
,# does not emit duplicate discoveryAdvertisingStateUpdate
,2017-08-01 11:32:22 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not emit duplicate discoveryAdvertisingStateUpdate''
,# teardown
,ok 341 error should be null
,ok 342 error should be null
,# setup
,ok 343 ThaliMobile should be stopped
,# does not send duplicate availability changes
,2017-08-01 11:32:23 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"e046280c-9e91-4729-9145-c663a7efe3ad","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 344 should be calle,d once
ok 345 should not have been called more than once
,# teardown
,2017-08-01 11:32:23 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"e046280c-9e91-4729-9145-c663a7efe3ad","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 346 error should be null
ok 347 error should be null
,# setup
,ok 348 ThaliMobile should be stopped
,# can get the network status
,ok 349 network status should have certain non-empty properties
,# teardown
,ok 350 error should be null
ok 351 error should be null
,# setup
,ok 352 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer added/removed to/from cache (native)
,ok 353 we have not added peer to the cache yet
2017-08-01 11:32:23 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"332e483f-5bb1-4657-b9ae-8be51f7da8c0","connectionType":"MPCF","peerAvailable":true,"generation":0,,"newAddressPort":false}'
ok 354 peer should be available
ok 355 cache contains native peer
2017-08-01 11:32:23 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"332e483f-5bb1-4657-b9ae-8be51f7da8c0","connectionTyp,e":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
ok 356 peer should be unavailable
ok 357 peer has been removed from cache
,# teardown
,ok 358 error should be null
ok 359 error should be null
,# setup
,ok 360 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer added/removed to/from cache (wifi)
,ok 361 we have not added peer to the cache yet
2017-08-01 11:32:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"6b938c61-7d35-4fd0-9634-e90ae25eadb4","connectionType":"tcp","peerAvailable":true,"generation":0,",newAddressPort":false}'
ok 362 peer should be available
ok 363 cache contains wifi peer
2017-08-01 11:32:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"6b938c61-7d35-4fd0-9634-e90ae25eadb4","connectionType":,"tcp","peerAvailable":false,"generation":0,"newAddressPort":null}'
ok 364 peer should be unavailable
ok 365 peer has been removed from cache
,# teardown
,ok 366 error should be null
ok 367 error should be null
,# setup
,ok 368 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored
,2017-08-01 11:32:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5b85fd64-6c1c-4bd6-8017-630b0e5a6c22","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 369 first peer is a,vailable
2017-08-01 11:32:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"07989d76-3d2c-4063-8aad-26dcb844b188","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 370 second, peer is available
ok 371 first and second peers are different
,# teardown
,2017-08-01 11:32:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"5b85fd64-6c1c-4bd6-8017-630b0e5a6c22","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-08-01, 11:32:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"07989d76-3d2c-4063-8aad-26dcb844b188","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 372 error should be null
ok 373 error should be null
,# setup
,ok 374 ThaliMobile should be stopped
,# native available - new peer is cached
,ok 375 should not be in cache at start
2017-08-01 11:32:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"630cdd2b-80be-49ec-bef0-8e0af2441f40","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 376 peer is available
,# teardown
,2017-08-01 11:32:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"630cdd2b-80be-49ec-bef0-8e0af2441f40","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 377 error should be null
ok 378 error should be null
,# setup
,ok 379 ThaliMobile should be stopped
,# native available - peer with same port and different generation is cached (BLUETOOTH)
,2017-08-01 11:32:25 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with same port and different generation is cached (BLUETOOTH)''
,# teardown
,ok 380 error should be null
,ok 381 error should be null
,# setup
,ok 382 ThaliMobile should be stopped
,# native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)
,2017-08-01 11:32:25 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)''
,# teardown
,ok 383 error should be null
ok 384 error should be null
,# setup
,ok 385 ThaliMobile should be stopped
,# native available - peer with greater generation is cached (MPCF)
,2017-08-01 11:32:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"2cada3ad-4e83-4657-85e6-648a6f55e118","connectionType":"MPCF","peerAvailable":true,"generation":2,"newAddressPort":false}'
,ok 386 peer should be available
,2017-08-01 11:32:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"2cada3ad-4e83-4657-85e6-648a6f55e118","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
ok 387 peer should be ,available
ok 388 should store correct generation
,# teardown
,2017-08-01 11:32:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"2cada3ad-4e83-4657-85e6-648a6f55e118","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 389 error should be null
ok 390 error should be null
,# setup
,ok 391 ThaliMobile should be stopped
,# native available - peer with same or older generation is ignored (MPCF)
,2017-08-01 11:32:26 - DEBUG thaliMobileNativeWrapper: 'listening 64707'
,2017-08-01 11:32:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"6c723af0-46fb-4445-8657-3e3564d2d835","connectionType":"MPCF","peerAvailable":true,"generation":2,"newAddressPort":false}'
,ok 392 discovered correct peer
,ok 393 got correct generation
,2017-08-01 11:32:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"6c723af0-46fb-4445-8657-3e3564d2d835","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
,ok 394 discovered correct peer
,ok 395 got correct generation
,# teardown
,2017-08-01 11:32:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"6c723af0-46fb-4445-8657-3e3564d2d835","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore,] AdvertiserManager.stopAdvertising()
2017-08-01 11:32:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:32:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:32:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:32:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-01 11:32:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server',
,ok 396 error should be null
ok 397 error should be null
,# setup
,ok 398 ThaliMobile should be stopped
,# native unavailable - new peer is ignored
,2017-08-01 11:32:26 - DEBUG thaliMobileNativeWrapper: 'listening 64708'
,2017-08-01 11:32:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"00bbd1be-e163-4ccd-80e4-9e40956dc7ff","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 399 discovered avai,lable peer
ok 400 peer is available
,# teardown
,2017-08-01 11:32:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"00bbd1be-e163-4ccd-80e4-9e40956dc7ff","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore,] AdvertiserManager.stopAdvertising()
2017-08-01 11:32:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:32:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:32:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpd,ateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:32:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-01 11:32:27 - DEBUG makeIntoCloseAllServer: 'closeAll called on server',
,ok 401 error should be null
ok 402 error should be null
,# setup
,ok 403 ThaliMobile should be stopped
,# native unavailable - cached peer is removed
,2017-08-01 11:32:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"695a1da1-15b0-4ee7-9aed-10c41b8794a8","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 404 peer should be available
2017-08-01 11:32:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"695a1da1-15b0-4ee7-9aed-10c41b8794a8","connectionType":"MPCF","peerAvailable":false,"generation":0,"newAddressPor,t":null}'
ok 405 peer should be unavailable
ok 406 should be removed from cache
,# teardown
,ok 407 error should be null
ok 408 error should be null
,# setup
,ok 409 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for wifi peers
,2017-08-01 11:32:27 - DEBUG thaliMobileNativeWrapper: 'listening 64709'
2017-08-01 11:32:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"412063f3-ee2c-4500-a3fa-aae3fdcfa868","connectionType":"MPCF","peerAvaila,ble":true,"generation":0,"newAddressPort":false}'
ok 410 first peer is expected to be available
2017-08-01 11:32:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"ba239210-1e00-4527-a732-b8032f864417","connectio,nType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 411 second peer is expected to be available
2017-08-01 11:32:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"ba239210-1e00-,4527-a732-b8032f864417","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 412 peer became unavailable
,ok 413 it was wifi peer
2017-08-01 11:32:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"ba239210-1e00-4527-a732-b8032f864417","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}',
ok 414 we found peer again
ok 415 it was wifi peer
2017-08-01 11:32:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"ba239210-1e00-4527-a732-b8032f864417","connectionType":"tcp","peerAvailable":false,,"generation":null,"newAddressPort":null}'
ok 416 peer became unavailable
ok 417 it was wifi peer
,# teardown
,2017-08-01 11:32:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"412063f3-ee2c-4500-a3fa-aae3fdcfa868","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:32:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:32:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:32:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpd,ateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:32:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-01 11:32:27 - DEBUG makeIntoCloseAllServer: 'closeAll called on server',
,ok 418 error should be null
ok 419 error should be null
,# setup
,ok 420 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)
,2017-08-01 11:32:28 - DEBUG CoordinatedClient: 'test was skipped, name: 'networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)''
,# teardown
,ok 421 error should be null
ok 422 error should be null
,# setup
,ok 423 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)
,2017-08-01 11:32:28 - DEBUG thaliMobileNativeWrapper: 'listening 64710'
,2017-08-01 11:32:28 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"0949b36c-a36b-432d-8891-3c00ac537f56","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 424 first peer is expected to be available
,2017-08-01 11:32:28 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"fbb9279d-9233-47c2-ad81-86cc7dee6aed","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 425 second peer is expected to be available
,2017-08-01 11:32:28 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"0949b36c-a36b-432d-8891-3c00ac537f56","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 426 peer became unavailable
,2017-08-01 11:32:28 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"fbb9279d-9233-47c2-ad81-86cc7dee6aed","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 427 peer became unavailable
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-01 11:32:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:32:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-01 11:32:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:32:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:32:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 428 error should be null
,ok 429 error should be null
,# setup
,ok 430 ThaliMobile should be stopped
,# multiconnect failure - new peer is ignored (MPCF)
,2017-08-01 11:32:28 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - new peer is ignored (MPCF)''
,# teardown
,ok 431 error should be null
ok 432 error should be null
,# setup
,ok 433 ThaliMobile should be stopped
,# multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)
,2017-08-01 11:32:29 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''
,# teardown
,ok 434 error should be null
ok 435 error should be null
,# setup
,ok 436 ThaliMobile should be stopped
,# newAddressPort field (TCP_NATIVE)
,2017-08-01 11:32:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"23551d53-178c-4d45-b045-10562586fcb2","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 437 peer discovered first time does not have new address
,2017-08-01 11:32:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"23551d53-178c-4d45-b045-10562586fcb2","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddressPort":false}'
,ok 438 address has not been changed
,2017-08-01 11:32:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"23551d53-178c-4d45-b045-10562586fcb2","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddressPort":true}'
,ok 439 new port handled correctly
,2017-08-01 11:32:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"23551d53-178c-4d45-b045-10562586fcb2","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddressPort":true}'
,ok 440 new host handled correctly
,2017-08-01 11:32:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"23551d53-178c-4d45-b045-10562586fcb2","connectionType":"tcp","peerAvailable":false,"generation":20,"newAddressPort":null}'
,ok 441 newAddressPort is null for unavailable peers
,# teardown
,ok 442 error should be null
,ok 443 error should be null
,# setup
,ok 444 ThaliMobile should be stopped
,# newAddressPort field (BLUETOOTH)
,2017-08-01 11:32:29 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort field (BLUETOOTH)''
,# teardown
,ok 445 error should be null
ok 446 error should be null
,# setup
,ok 447 ThaliMobile should be stopped
,# newAddressPort field (MPCF)
,ok 448 NOT IMPLEMENTED # SKIP
,# teardown
,ok 449 error should be null
ok 450 error should be null
,# setup
,ok 451 ThaliMobile should be stopped
,# newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)
,2017-08-01 11:32:30 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)''
,# teardown
,ok 452 error should be null
ok 453 error should be null
,# setup
,ok 454 ThaliMobile should be stopped
,# #getPeerHostInfo - error when peer has not been discovered yet
,ok 455 should be equal
,# teardown
,ok 456 error should be null
ok 457 error should be null
,# setup
,ok 458 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)
,2017-08-01 11:32:31 - DEBUG CoordinatedClient: 'test was skipped, name: '#getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)''
,# teardown
,ok 459 error should be null
ok 460 error should be null
,# setup
,ok 461 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)
,2017-08-01 11:32:31 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 462 contains expected properties
,ok 463 the same hostAddress
,ok 464 the same portNumber
,# teardown
,2017-08-01 11:32:31 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 465 error should be null
,ok 466 error should be null
,# setup
,ok 467 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached wifi peer
,2017-08-01 11:32:31 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 468 contains expected properties
,ok 469 the same hostAddress
,ok 470 the same portNumber
,# teardown
,2017-08-01 11:32:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 471 error should be null
ok 472 error should be null
,# setup
,ok 473 ThaliMobile should be stopped
,# #disconnect fails on wifi peers
,2017-08-01 11:32:32 - DEBUG thaliMobileNativeWrapper: 'listening 64711'
2017-08-01 11:32:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9ce01663-7856-4146-9617-91bce0de5d06","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 474 Got specific error message
,# teardown
,2017-08-01 11:32:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"9ce01663-7856-4146-9617-91bce0de5d06","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore], AdvertiserManager.stopAdvertising()
2017-08-01 11:32:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:32:32 - INFO thaliMobile: 'Filtered out discoveryAdverti,singStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-01 11:32:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:32:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-01 11:32:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 475 error should be null
ok 476 error should be null
,# setup
,ok 477 ThaliMobile should be stopped
,# #disconnect delegates native peers to the native wrapper
,2017-08-01 11:32:32 - DEBUG thaliMobileNativeWrapper: 'listening 64712'
,2017-08-01 11:32:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"2cbd4292-6687-4f48-976d-b952114a72ef","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] BrowserManager.disconnect peer:2cbd4292-6687-4f48-976d-b952114a72ef
,ok 478 native wrapper `disconnect` called once
,ok 479 native wrapper `disconnect` called with peer data
,# teardown
,2017-08-01 11:32:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"2cbd4292-6687-4f48-976d-b952114a72ef","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-01 11:32:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:32:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-01 11:32:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:32:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:32:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 480 error should be null
,ok 481 error should be null
,# setup
,ok 482 ThaliMobile should be stopped
,# network changes emitted correctly
,2017-08-01 11:32:32 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes emitted correctly''
,# teardown
,ok 483 error should be null
,ok 484 error should be null
,# setup
,ok 485 ThaliMobile should be stopped
,# network changes not emitted in started state
,2017-08-01 11:32:32 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes not emitted in started state''
,# teardown
,ok 486 error should be null
ok 487 error should be null
,# setup
,ok 488 ThaliMobile should be stopped
,# network changes not emitted in stopped state
,2017-08-01 11:32:33 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes not emitted in stopped state''
,# teardown
,ok 489 error should be null
ok 490 error should be null
,# setup
,ok 491 ThaliMobile should be stopped
,# We properly fire peer unavailable and then available when connection fails on Android
,2017-08-01 11:32:33 - DEBUG CoordinatedClient: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on Android''
,# teardown
,ok 492 error should be null
,ok 493 error should be null
,# setup
,ok 494 ThaliMobile should be stopped
,# We properly fire peer unavailable and then available when connection fails on iOS
,2017-08-01 11:32:33 - DEBUG CoordinatedClient: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on iOS''
,# teardown
,ok 495 error should be null
ok 496 error should be null
,# setup
,ok 497 ThaliMobile should be stopped
,# If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen
,2017-08-01 11:32:34 - DEBUG CoordinatedClient: 'test was skipped, name: 'If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen''
,# teardown
,ok 498 error should be null
ok 499 error should be null
,# setup
,ok 500 ThaliMobile should be stopped
,# does not fire duplicate events after peer listener recreation
,2017-08-01 11:32:34 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not fire duplicate events after peer listener recreation''
,# teardown
,ok 501 error should be null
ok 502 error should be null
,# setup
,ok 503 ThaliMobile should be stopped
,# #stop should change peers
,2017-08-01 11:32:34 - DEBUG thaliMobileNativeWrapper: 'listening 64713'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:F79279B1-E15A-430B-8810-69E992AEE119
[ThaliCore] Browser.startListening
2017-08-01 11:32:34 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-01 11:32:34 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"57c0da78-4869-4278-950c-6440a8b656e6","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 504 Peer availabilities has one entry for our connection type
,2017-08-01 11:32:34 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"aaa35adf-d397-4764-a4c4-ba7fe4943b2a","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 505 Peer availabilities has one entry for our connection type
,2017-08-01 11:32:34 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"57c0da78-4869-4278-950c-6440a8b656e6","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-08-01 11:32:34 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"aaa35adf-d397-4764-a4c4-ba7fe4943b2a","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-01 11:32:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-01 11:32:34 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"pskIdToSecret":[102,111,1,11],"networkType":"BOTH"}})'
2017-08-01 11:32:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-08-01 11:32:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:32:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:32:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-01 11:32:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 506 No peers
,ok 507 No peers
,ok 508 No peers
,# teardown
,ok 509 error should be null
ok 510 error should be null
,# setup
,ok 511 ThaliMobile should be stopped
,# If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted
,2017-08-01 11:32:35 - DEBUG thaliMobileNativeWrapper: 'listening 64714'
2017-08-01 11:32:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"19fa5e04-ff44-47fb-b4bc-3af9d3fab865","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 512 1
ok 513 2
,2017-08-01 11:32:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"0846ba1e-ad79-40dd-8583-11a409dc7a81","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,# teardown
,2017-08-01 11:32:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"19fa5e04-ff44-47fb-b4bc-3af9d3fab865","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-08-01, 11:32:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"0846ba1e-ad79-40dd-8583-11a409dc7a81","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:32:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:32:35 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:32:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-08-01 11:32:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-01 11:32:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 514 error should be null
ok 515 error should be null
,# setup
,ok 516 ThaliMobile should be stopped
,# peer should be found once after listening and discovery started
,2017-08-01 11:32:35 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer should be found once after listening and discovery started''
,# teardown
,ok 517 error should be null
ok 518 error should be null
,# setup
,ok 519 ThaliMobile should be stopped
,# can get data from all participants
,2017-08-01 11:32:36 - DEBUG thaliMobileNativeWrapper: 'listening 64715'
ok 520 error should be null
ok 521 error should be null
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "CA88F631-A53F-4016-997C-EA,CC85DE23E5", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:CA88F631-A53F-4016-997C-EACC85DE23E5
2017-08-01 11:32:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive,":true}'
ok 522 error should be null
ok 523 error should be null
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:3CE935A7-111C-47D8-8125-279181E75889
[ThaliCore] Browser.startListening
2017-08-01 11:32:36 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
ok 524 error should be null
ok 525 error should be null
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B1D3177E-372A-4F29-8F3A-5AC9E326B4C9:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B1D3177E-372A-4F29-8F3A-5AC9E326B4C9", generation: 0)
,2017-08-01 11:32:36 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"B1D3177E-372A-4F29-8F3A-5AC9E326B4C9","generation":0}]'
2017-08-01 11:32:36 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"B1D3177E-372A-4F29-8F3A-5AC9E326B4C9","generation":0}'
,2017-08-01 11:32:36 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"B1D3177E-372A-4F29-8F3A-5AC9E326B4C9","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-01 11:32:36 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"B1D3177E-372A-4F29-8F3A-5AC9E326B4C9","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-08-01 11:32:36 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for B1D3177E-372A-4F29-8F3A-5AC9E326B4C9 (syncValue: 0)'
,2017-08-01 11:32:36 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B1D3177E-372A-4F29-8F3A-5AC9E326B4C9", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B1D3177E-372A-4F29-8F3A-5AC9E326B4C9", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B1D3177E-372A-4F29-8F3A-5AC9E326B4C9:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:ACA77010-5D8E-4A90-81AB-BDF0C37999E5:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "ACA77010-5D8E-4A90-81AB-BDF0C37999E5", generation: 0)
2017-08-01 11:32:37 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"ACA77010-5D8E-4A90-81AB-BDF0C37999E5","generation":0}]'
2017-08-01 11:32:37 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"ACA77010-5D8E-4A90-81AB-BDF0C37999E5","generation":0}'
,2017-08-01 11:32:37 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"ACA77010-5D8E-4A90-81AB-BDF0C37999E5","peerAvailable":true,"generation":0,"portNumber":null}'
2017-08-01 11:32:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"ACA77010-5D8E-4A90-81AB-BDF0C37999E5","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CA88F631-A53F-4016-997C-EACC85DE23E5:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CA88F631-A53F-4016-997C-EACC85DE23E5", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FF233C22-60DB-4B1D-B6ED-7DC1227E0497:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FF233C22-60DB-4B1D-B6ED-7DC1227E0497", generation: 0)
2017-08-01 11:32:38 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"FF233C22-60DB-4B1D-B6ED-7DC1227E0497","generation":0}]'
2017-08-01 11:32:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"FF233C22-60DB-4B1D-B6ED-7DC1227E0497","generation":0}'
,2017-08-01 11:32:38 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"FF233C22-60DB-4B1D-B6ED-7DC1227E0497","peerAvailable":true,"generation":0,"portNumber":null}'
2017-08-01 11:32:38 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"FF233C22-60DB-4B1D-B6ED-7DC1227E0497","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:B1D3177E-372A-4F29-8F3A-5AC9E326B4C9:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "B1D3177E-372A-4F29-8F3A-5AC9E326B4C9", generation: 0)
2017-08-01 11:32:38 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"B1D3177E-372A-4F29-8F3A-5AC9E326B4C9","generation":0}]'
2017-08-01 11:32:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"B1D3177E-372A-4F29-8F3A-5AC9E326B4C9","generation":0}'
,2017-08-01 11:32:38 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"B1D3177E-372A-4F29-8F3A-5AC9E326B4C9","peerAvailable":false,"generation":null,"portNumber":null}'
2017-08-01 11:32:38 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"B1D3177E-372A-4F29-8F3A-5AC9E326B4C9","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:B1D3177E-372A-4F29-8F3A-5AC9E326B4C9:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B1,D3177E-372A-4F29-8F3A-5AC9E326B4C9:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "B1D3177E-372A-4F29-8F3A-5AC9E326B4C9", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,1D3177E-372A-4F29-8F3A-5AC9E326B4C9", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B1D3177E-372A-4F29-8F3A-5AC9E326B4C9", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-08-01 11:32:39 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"0","error":"Peer is unavailable","portNumber":null}'
,2017-08-01 11:32:39 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for ACA77010-5D8E-4A90-81AB-BDF0C37999E5 (syncValue: 1)'
2017-08-01 11:32:39 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPee,r(_:syncValue:retryCount:completion:) Peer(uuid: "ACA77010-5D8E-4A90-81AB-BDF0C37999E5", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "ACA77010-5D8E-4A90-81AB-BDF0C37999E5", ge,neration: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:ACA77010-5D8E-4A90-81AB-BDF0C37999E5:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnec,ted:stoppedListening:)
,[ThaliCore] Session.deinit peer:B1D3177E-372A-4F29-8F3A-5AC9E326B4C9:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:ACA77010-5D8E-4A90-81AB-BDF0C37999E5:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:AABEB37E-ECB2-488B-8C56-59E412028A74
[ThaliCore] Advertiser: session connected Peer(uuid: "CA88F631-A53F-4016-997C-EACC85DE23E5", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:AABEB37E-ECB2-488B-8C56-59E412028A74 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:ACA77010-5D8E-4A90-81AB-BDF0C37999E5:0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:AABEB37E-ECB2-488B-8C56-59E412028A74
,[ThaliCore] Session.session(_:peer:didChange:) peer:ACA77010-5D8E-4A90-81AB-BDF0C37999E5:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "ACA77010-5D8E-4A90-81AB-BDF0C37999E5", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:64721
,2017-08-01 11:32:42 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"1","error":null,"portNumber":64721}'
,2017-08-01 11:32:42 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for FF233C22-60DB-4B1D-B6ED-7DC1227E0497 (syncValue: 2)'
,2017-08-01 11:32:42 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "FF233C22-60DB-4B1D-B6ED-7DC1227E0497", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FF233C22-60DB-4B1D-B6ED-7DC1227E0497", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FF233C22-60DB-4B1D-B6ED-7DC1227E0497:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:ACA77010-5D8E-4A90-81AB-BDF0C37999E5:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:ACA77010-5D8E-4A90-81AB-BDF0C37999E5:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:20 [4, 10, 16, 20]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-08-01 11:32:42 - DEBUG testUtils: 'Got response data'
,2017-08-01 11:32:42 - DEBUG testUtils: 'Got end'
,[ThaliCore] Session.session(_:peer:didChange:) peer:AABEB37E-ECB2-488B-8C56-59E412028A74 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:AABEB37E-ECB2-488B-8C56-59E412028A74
[ThaliCore] Session.startOutputStream(with:) peer:AABEB37E-ECB2-488B-8C56-59E412028A74
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2,1 [4, 10, 16, 20, 21]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:FF233C22-60DB-4B1D-B6ED-7DC1227E0497:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:FF233C22-60DB-4B1D-B6ED-7DC1227E0497:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:FF233C22-60DB-4B1D-B6ED-7DC1227E0497:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "FF233C22-60DB-4B1D-B6ED-7DC1227E0497", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:64726
2017-08-01 11:32:45 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"2","error":null,"portNumber":64726,}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:FF233C22-60DB-4B1D-B6ED-7DC1227E0497:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FF233C22-60DB-4B1D-B6ED-7DC1227E0497:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:22 [4, 10, 16, 20, 21, 22]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-08-01 11:32:46 - DEBUG testUtils: 'Got response data'
2017-08-01 11:32:46 - DEBUG testUtils: 'Got end'
ok 526 received all uuids
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:8B3DD96E-12C8-4FCA-BDE1-1CB5D3E46207
[ThaliCore] Advertiser: session connected Peer(uuid: "CA88F631-A53F-4016-997C-EACC85DE23E5", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:8B3DD96E-12C8-4FCA-BDE1-1CB5D3E46207 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:8B3DD96E-12C8-4FCA-BDE1-1CB5D3E46207
,[ThaliCore] Session.session(_:peer:didChange:) peer:8B3DD96E-12C8-4FCA-BDE1-1CB5D3E46207 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:8B3DD96E-12C8-4FCA-BDE1-1CB5D3E46207
[ThaliCore] Session.startOutputStream(with:) peer:8B3DD96E-12C8-4FCA-BDE1-1CB5D3E46207
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2,3 [4, 10, 16, 20, 21, 22, 23]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-08-01 11:32:55 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"ACA77010-5D8E-4A90-81AB-BDF0C37999E5","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-08-01, 11:32:55 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"FF233C22-60DB-4B1D-B6ED-7DC1227E0497","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore] Advertis,erManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:CA88F631-A53F-4016-997C-EACC85DE23E5
,2017-08-01 11:32:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-01 11:32:55 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
2017-08-01 11:32:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] Brows,erManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-01 11:32:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:32:55 - INFO ,thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-01 11:32:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:21
[ThaliCore] VirtualSocket.closeS,treams() vsID:21
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket c,losed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] Adve,rtiserRelay.didSocketDisconnectHandler removed virtual socket vsID:23
[ThaliCore] VirtualSocket exited RunLoop vsID:21
[ThaliCore] VirtualSocket.closeStreams() vsID:23
[ThaliCore] VirtualSocket.deinit vsID:21 [4, 10, 16, 20, 22, 23]
ok 527 error should be null
ok 528 error should be null
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:23
[ThaliCore] VirtualSocket.deinit vsID:23 [4, 10, 16, 20, 22]
,# setup
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:22
[ThaliCore] VirtualSocket.closeStreams() vsID:22
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:22
,[ThaliCore] VirtualSocket.deinit vsID:22 [4, 10, 16, 20]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSo,cketDisconnectHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:20
[ThaliCore] VirtualSocket.closeStreams() vsID:20
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:20
[ThaliCore] VirtualSocket.deinit vsID:20 [4, 10, 16]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket re,moved, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,ok 529 ThaliMobile should be stopped
,# test for data corruption
,2017-08-01 11:32:56 - DEBUG CoordinatedClient: 'test was skipped, name: 'test for data corruption''
,# teardown
,ok 530 error should be null
ok 531 error should be null
,# setup
,# #testThaliPeerAction - test getters
,ok 532 getPeerIdentifier
ok 533 getConnectionType
ok 534 getActionType
ok 535 getActionState
ok 536 getPskIdentity
ok 537 getPskKey
,# teardown
,# setup
,# #testThaliPeerAction - start and kill
,ok 538 initial state
ok 539 after start
2017-08-01 11:32:57 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 540 after kill
,# teardown
,# setup
,# #testThaliPeerAction - double start
,ok 541 should be equal
,# teardown
,# setup
,# #testThaliPeerAction - start after kill
,2017-08-01 11:32:58 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 542 clean kill
,ok 543 should be equal
,# teardown
,# setup
,# #testThaliPeerAction - make sure ids are unique
,ok 544 should not be equal
,# teardown
,# setup
,# #testThaliPeerAction - check that forever agent can be destroyed
,ok 545 forever agent should have it's own destroy method
ok 546 agent's destroy should be called
ok 547 agent's destroy should not be called again
ok 548 agent is destroyed
,# teardown
,# setup
,# Test PeerDictionary basic functionality
,ok 549 Entry counter must be 1
ok 550 Entry exists
ok 551 Size must be 1
ok 552 Entry counter must be 2
ok 553 Entry exists
ok 554 Size must be 2
ok 555 Entry counter must be 1
ok 556 Entry exists
,ok 557 Size must be 3
,ok 558 Entry counter must be 2
ok 559 Entry exists
,ok 560 Size must be 4
,ok 561 Entry 1_1 should not be found
,ok 562 Entry 1_1 does not exist
,ok 563 Size must be 3
,ok 564 Entry 1_2 should not be found
,ok 565 Entry 1_2 does not exist
,ok 566 Size must be 2
,ok 567 should be equal
,ok 568 Entry 2_1 should not be found
,ok 569 Entry 2_2 should not be found
,ok 570 Entry 2_1 does not exist
,ok 571 Entry 2_2 does not exist
,ok 572 Size must be 0
,# teardown
,# setup
,# Test PeerDictionary with multiple entries.
,ok 573 Size must be100
,ok 574 Entries between 20 and MAXSIZE + 20 should exist
,ok 575 WAITING state entry should not be removed
,# teardown
,# setup
,# RESOLVED entries are removed before WAITING state entry.
,ok 576 Entries between 6 and MAXSIZE + 4 should exist
ok 577 Size should be MAXSIZE
,ok 578 Size should be MAXSIZE+6
,# teardown
,# setup
,# WAITING entries are removed before CONTROLLED_BY_POOL state entry.
,ok 579 WAITING state entry should not be removed
,ok 580 Waiting entries between 6 and MAXSIZE + 4 should exist
,ok 581 Size should be MAXSIZE
,ok 582 entryCounter should be MAXSIZE+6
,# teardown
,# setup
,# When CONTROLLED_BY_POOL entry is removed and kill is called.
,ok 583 Kill should be called once
,ok 584 Size should be MAXSIZE
,# teardown
,# setup
,# #ThaliPeerPoolDefault - single action
,ok 585 is an agent
,ok 586 enqueue is fine
ok 587 Everything should be off the queue
,# teardown
,# setup
,# #ThaliPeerPoolDefault - multiple actions
,ok 588 is an agent
ok 589 first enqueue is fine
,ok 590 is an agent
ok 591 second enqueue is fine
ok 592 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
ok 593 Queue is empty
,# teardown
,# setup
,# #ThaliPeerPoolDefault - PSK Pool works
,ok 594 is an agent
ok 595 good enqueue
,ok 596 Identity should match
,2017-08-01 11:33:03 - DEBUG testUtils: 'Got response data'
,2017-08-01 11:33:03 - DEBUG testUtils: 'Got end'
,ok 597 Got expected response
,ok 598 Got psk call back
,# teardown
,2017-08-01 11:33:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #ThaliPeerPoolDefault - stop
,ok 599 is an agent
,ok 600 enqueue worked
,ok 601 is an agent
,ok 602 enqueue 2 worked
,ok 603 enqueue is not available when stopped
,ok 604 start action is killed
,ok 605 killed action is still killed
,ok 606 enqueued action when stopped is killed
,ok 607 inQueue is empty
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure that start verifies queue length
,ok 608 good start
ok 609 good enqueue
ok 610 queue is not empty
,# teardown
,# setup
,# #ThaliPeerPoolInterface - bad enqueues
,ok 611 null arg
,ok 612 wrong arg type
ok 613 wrong arg type
,# teardown
,# setup
,# #ThaliPeerPoolInterface - do not allow same object type
,ok 614 good enqueue
,ok 615 already enqueued
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure we catch kill and dequeue
,ok 616 good enqueue
,ok 617 2nd good enqueue
,ok 618 we are in the pool
,ok 619 We are out of the pool
,ok 620 Action was killed
,ok 621 The original kill was called too
,ok 622 second item is still in queue
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent
,ok 623 good enqueue
ok 624 first kill
,ok 625 second NOOP kill
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure that stop removes all actions
,ok 626 1st good enqueue
ok 627 2nd good enqueue
ok 628 1st action is in the pool
ok 629 2nd action is in the pool
ok 630 1st action is out of the pool
ok 631 2st action is out of the pool
ok 632 pool is empty
,# teardown
,# setup
,# We reject unrecognized connection type
,2017-08-01 11:33:06 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 633 Got right error
,ok 634 Start should not be called
,ok 635 Kill should have been called at least once
,# teardown
,# setup
,# We reject unrecognized action type
,2017-08-01 11:33:06 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
2017-08-01 11:33:06 - ERROR thaliPeerPoolOneAtATime: 'Got unsupported action type: blah'
ok 636 Got right error
ok 637 Start should not be called
ok 638 Kill should have been called at least once
,# teardown
,# setup
,# One action on bluetooth
,2017-08-01 11:33:08 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
ok 639 Got null
2017-08-01 11:33:08 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier,: peerID'
ok 640 is an agent
2017-08-01 11:33:08 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerID'
,ok 641 Got killed at least once
,# teardown
,# setup
,# Two notification actions
,2017-08-01 11:33:08 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
ok 642 Got Null
ok 643 Got another null
2017-08-01 11:33:08 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidB,luetooth, Peer Identifier: peerId1'
ok 644 is an agent
2017-08-01 11:33:08 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId1'
,2017-08-01 11:33:08 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
ok 645 is an agent
2017-08-01 11:33:08 - DEBUG thaliPeerPoolOneAtATime: 'acti,on returned successfully from start - Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
,ok 646 Action 1 killed at least once
,ok 647 Action 1 went first
ok 648 Action 2 killed at least once
,# teardown
,# setup
,# replicateThroughProblems
,2017-08-01 11:33:09 - DEBUG thaliPeerPoolOneAtATime: 'Action Started success'
2017-08-01 11:33:09 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - success'
,2017-08-01 11:33:09 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,ok 649 should have gotten null
,2017-08-01 11:33:09 - DEBUG thaliPeerPoolOneAtATime: 'Action Started noActivityTimeOut'
,2017-08-01 11:33:09 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: No activity time out - noActivityTimeOut'
,ok 650 Should have stopped nicely
,2017-08-01 11:33:09 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButNotAvailable'
,2017-08-01 11:33:09 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButNotAvailable'
,ok 651 Still looking for null
,2017-08-01 11:33:09 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButAvailable'
,2017-08-01 11:33:09 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButAvailable'
,2017-08-01 11:33:09 - DEBUG thaliPeerPoolOneAtATime: 'Replication action failed badly so we are going to retry'
,2017-08-01 11:33:09 - DEBUG thaliPeerPoolOneAtATime: 'Action Started clone!'
,2017-08-01 11:33:09 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - clone!'
,2017-08-01 11:33:09 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,ok 652 Yup, another null
,ok 653 We cloned!
,# teardown
,# setup
,# Replication goes first
,2017-08-01 11:33:09 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
ok 654 Null 1
ok 655 (unnamed assert)
2017-08-01 11:33:09 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBlu,etooth, Peer Identifier: notificationAction'
ok 656 is an agent
ok 657 Null 3
ok 658 Replication not yet called
ok 659 Notification 2 not yet called
2017-08-01 11:33:09 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action, ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
2017-08-01 11:33:09 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidB,luetooth, Peer Identifier: replicationAction'
ok 660 is an agent
ok 661 Notification went first
ok 662 Notification 2 not called yet
,2017-08-01 11:33:09 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
2017-08-01 11:33:09 - DEBUG thaliPeerPoo,lOneAtATime: 'Got a replication response with no error!'
2017-08-01 11:33:09 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
ok 663 is, an agent
ok 664 Notification finished
ok 665 Replication finished
,2017-08-01 11:33:09 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,# teardown
,# setup
,# wifi allows many parallel non-replication actions
,2017-08-01 11:33:10 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
2017-08-01 11:33:10 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
ok 666 is an agent
ok 667 First does, not throw
2017-08-01 11:33:10 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
ok 668 is an agent
ok 669 Second does not throw
2017-08-01 11:33:10 - DEBUG thaliPeerPoolOneAtAT,ime: 'action returned successfully from start - Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
truetruefalsetrue
,2017-08-01 11:33:10 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
truetruetruetrue
# teardown
,# setup
,# wifi allows no more than 2 simultaneous replication actions for same peerID
,2017-08-01 11:33:10 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-08-01 11:33:10 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 595, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
ok 670 is an agent
ok 671 first ok
2017-08-01 11:33:10 - DEBUG thaliPeerPoolOneAtATime: 'Actio,n Started Action ID: 596, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
ok 672 is an agent
ok 673 second ok
ok 674 third ok
,2017-08-01 11:33:10 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 595, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
2017-08-01 11:33:10 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 596, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
2017-08-01 11:33:10 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
2017-08-01 11:33:10 - DEBUG thaliPeerPoo,lOneAtATime: 'Got a replication response with no error!'
# teardown
,# setup
,# Client to server request coordinated
,2017-08-01 11:33:10 - DEBUG CoordinatedClient: 'test was skipped, name: 'Client to server request coordinated''
,# teardown
,2017-08-01 11:33:10 - INFO testThaliNotification: 'Participants:0 Peers Replied to us:0 Peers requested to:0'
,# setup
,# Test BEACONS_RETRIEVED_AND_PARSED locally
,ok 675 peerIdentifier should match
,ok 676 generation should match
,ok 677 Response should be BEACONS_RETRIEVED_AND_PARSED
,ok 678 good beacon
,ok 679 good preAmble
,ok 680 public keys match!
,ok 681 must return null after successful call
,ok 682 Once start returns the action should be in KILLED state
,# teardown
,2017-08-01 11:33:11 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test HTTP_BAD_RESPONSE locally
,2017-08-01 11:33:11 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test HTTP_BAD_RESPONSE locally''
,# teardown
,2017-08-01 11:33:11 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test NETWORK_PROBLEM locally
,ok 683 Response should be NETWORK_PROBLEM
,ok 684 reject reason should be: Could not establish TCP connection
,# teardown
,2017-08-01 11:33:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Action fails when getPeerHostInfo fails
,ok 685 Resolution should be BAD_PEER
,ok 686 correct error message
,# teardown
,2017-08-01 11:33:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the start two times
,ok 687 Call start once
,ok 688 Response should be BEACONS_RETRIEVED_AND_PARSED
,ok 689 must return null after successful call.
,# teardown
,2017-08-01 11:33:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill before calling the start
,ok 690 Should be Killed
ok 691 Start after killed
,# teardown
,2017-08-01 11:33:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill immediately after the start
,ok 692 Should be KILLED
,ok 693 must return null after successful kill
,# teardown
,2017-08-01 11:33:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill while waiting a response from the server
,ok 694 Should be KILLED
ok 695 must return null after successful kill
,# teardown
,2017-08-01 11:33:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test to exceed the max content size locally
,ok 696 HTTP_BAD_RESPONSE should be response when content size is exceeded
,ok 697 must return null after successful call
,# teardown
,2017-08-01 11:33:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Close the server socket while the client is waiting a response from the server. Local test.
,2017-08-01 11:33:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 698 Should be NETWORK_PROBLEM caused closing server socket
ok 699 Should be Could not establish TCP connection
,# teardown
,# setup
,# Close the client socket while the client is waiting a response from the server. Local test.
,ok 700 Should be NETWORK_PROBLEM caused closing client socket
ok 701 Should be Could not establish TCP connection
,# teardown
,2017-08-01 11:33:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #generatePreambleAndBeacons bad args
,ok 702 publicKeysToNotify cannot be null
ok 703 ecdh for local device cannot be null
ok 704 milliseconds cannot be less than 0
ok 705 milliseconds cannot be 0
ok 706 milliseconds cannot be greater than one_day
,# teardown
,# setup
,# #generatePreambleAndBeacons empty keys to notify
,ok 707 should be equal
,# teardown
,# setup
,# #generatePreambleAndBeacons multiple keys to notify
,ok 708 should be equal
ok 709 should be equal
,ok 710 (unnamed assert)
,ok 711 should be equal
,# teardown
,# setup
,# #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
,ok 712 should throw
,# teardown
,# setup
,# #parseBeacons invalid expiration in beaconStreamWithPreAmble
,ok 713 Preamble expiration must be a 64 bit integer
,# teardown
,# setup
,# #parseBeacons expiration out of range lower
,ok 714 Expiration out of range
,# teardown
,# setup
,# #parseBeacons expiration out of range lower
,ok 715 Expiration out of range
,# teardown
,# setup
,# #parseBeacons no beacons returns null
,ok 716 should be equal
,# teardown
,# setup
,# #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
,ok 717 Malformed encrypted beacon key ID
,# teardown
,# setup
,# #parseBeacons addressBookCallback fails decrypt
,ok 718 should be equal
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns no matches
,2017-08-01 11:33:26 - DEBUG CoordinatedClient: 'test was skipped, name: '#parseBeacons addressBookCallback returns no matches''
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns spurious match
,ok 719 should be equal
,ok 720 should be equal
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns public key
,ok 721 right number of calls to address book
ok 722 good preAmble
,ok 723 good unencryptedKeyId
,ok 724 good beacon
,# teardown
,# setup
,# validate generatePskIdentityField
,ok 725 decoded buffers match
,# teardown
,# setup
,# validate generatePskSecret
,ok 726 secrets match
,# teardown
,# setup
,# validate generatePskSecrets
,ok 727 Matching numbers
,ok 728 We have an entry!
,ok 729 keys match
ok 730 secrets match
,ok 731 We have an entry!
,ok 732 keys match
,ok 733 secrets match
,ok 734 We have an entry!
ok 735 keys match
,ok 736 secrets match
,# teardown
,# setup
,# validate generateBeaconStreamAndSecrets
,ok 737 Streams have same length
,ok 738 matching size
,ok 739 keys match
,ok 740 secrets match
,# teardown
,# setup
,# Add two Peers.
,ok 741 should be equal
ok 742 peerDictionalty contains 2 peers
ok 743 bluetooth peer's notification has correct connection type
ok 744 tcp peer's notification has correct connection type
,2017-08-01 11:33:29 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
2017-08-01 11:33:29 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-08-01 11:33:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# TCP_NATIVE peer loses DNS
,ok 745 notification peer dictionary contains exactly 1 peer
,2017-08-01 11:33:29 - WARN thaliNotificationClient: 'peer is not available'
,ok 746 notification peer dictionary does not contain any peers
,2017-08-01 11:33:29 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-08-01 11:33:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Received beacons with no values for us
,ok 747 entry exists
,ok 748 entry is resolved
,# teardown
,2017-08-01 11:33:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Notification action killed with a superseded
,ok 749 Action should be KILLED
ok 750 Peer state should be RESOLVED
,# teardown
,2017-08-01 11:33:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally
,ok 751 hostAddress must match
,ok 752 portNumber must match
,ok 753 suggestedTCPTimeout must match
,ok 754 connectionType must match
,ok 755 peerIDs must match
,# teardown
,2017-08-01 11:33:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Emits error event when peerPool.enqueue throws
,ok 756 Correct error
,# teardown
,2017-08-01 11:33:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally using ThaliPeerPoolDefault
,ok 757 hostAddress must match
,ok 758 portNumber must match
,ok 759 suggestedTCPTimeout must match
,ok 760 connectionType must match
,ok 761 peerIds must match
,# teardown
,2017-08-01 11:33:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Action fails because of a bad hostname.
,2017-08-01 11:33:33 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 762 action should be resolved with NETWORK_PROBLEM error
,2017-08-01 11:33:33 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 763 action should be resolved with NETWORK_PROBLEM error
,2017-08-01 11:33:33 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 764 action should be resolved with NETWORK_PROBLEM error
,2017-08-01 11:33:34 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 765 action should be resolved with NETWORK_PROBLEM error
ok 766 correct number of requests
ok 767 correct number of failures
ok 768 correct final peer state
,# teardown
,2017-08-01 11:33:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# hostaddress is removed when the action is running. 
,2017-08-01 11:33:37 - WARN thaliNotificationClient: 'peer is not available'
2017-08-01 11:33:37 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 769 peerDictionary should become empty
,# teardown
,2017-08-01 11:33:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notificationClient does not retry action with BAD_PEER resolution
,2017-08-01 11:33:37 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 770 failed with expected error
,ok 771 peer state should be RESOLVED
,# teardown
,2017-08-01 11:33:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notification client correctly handles peer availability changes of the same peer
,2017-08-01 11:33:38 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 772 First action failed
,ok 773 second action killed
,# teardown
,2017-08-01 11:33:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Client to server request locally
,ok 774 secrets are equal
,ok 775 Public key matches with the server key
,ok 776 hostAddress must match
,ok 777 portNumber must match
,ok 778 suggestedTCPTimeout must match
,ok 779 connectionType must match
,# teardown
,2017-08-01 11:33:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache clean and expiration
,ok 780 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE
,ok 781 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE-1
,ok 782 All entries should be expired after 1 second
# teardown
,2017-08-01 11:33:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache getSecret and getPublic
,ok 783 All keys need to be available in the cache
,ok 784 All entries should be expired after 1 second
# teardown
,2017-08-01 11:33:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache multiple entries
,ok 785 Size of the cache should be 2
ok 786 Cache doesn't contain dictionary1
,ok 787 Size of the cache should be 1
ok 788 Cache doesn't contain beaconStreamAndSecretDictionary2
# teardown
,2017-08-01 11:33:45 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Start and stop ThaliNotificationServer
,ok 789 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
,ok 790 ThaliMobile.StopAdvertisingAndListeningshould be called once
,# teardown
,2017-08-01 11:33:46 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass an empty array to ThaliNotificationServer.start
,ok 791 StartUpdateAdvertisingAndListening should not be called
,ok 792 ThaliMobile.StopAdvertisingAndListening should be called once
,ok 793 no error
,ok 794 should be 204
,# teardown
,2017-08-01 11:33:46 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass a string to ThaliNotificationServer.start
,ok 795 StartUpdateAdvertisingAndListening should not be called
,# teardown
,2017-08-01 11:33:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass an empty parameter to ThaliNotificationServer.start
,ok 796 StartUpdateAdvertisingAndListening should not be called
,# teardown
,2017-08-01 11:33:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeacons
,ok 797 no error
,ok 798 should be 200
,ok 799 should be equal
,ok 800 should be equal
,ok 801 (unnamed assert)
,ok 802 no error
,ok 803 should be 204
,# teardown
,2017-08-01 11:33:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeacons (no keys)
,ok 804 error should be null
,ok 805 should be 204
,# teardown
,2017-08-01 11:33:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeaconsbefore calling start
,ok 806 should be 404
,# teardown
,2017-08-01 11:33:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure peerDictionaryKey is reasonable
,ok 807 equal keys
ok 808 not equal connection type
ok 809 same connection type, different buffer
,# teardown
,# setup
,# Make sure start works
,2017-08-01 11:33:50 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 810 First start and on called correctly
,# teardown
,# setup
,# Make sure stop works
,ok 811 second cleared dictionary
,2017-08-01 11:33:50 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 812 First start and on called correctly
,ok 813 First stop and removeListener called correctly
,ok 814 first action kill called
,ok 815 second action kill called
,ok 816 first cleared dictionary
,ok 817 first cleared pool
,ok 818 second cleared dictionary
,ok 819 second cleared pool
,# teardown
,# setup
,# Emits error event when peerPool.enqueue throws
,ok 820 Correct error
,# teardown
,# setup
,# Simple peer event
,2017-08-01 11:33:51 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,ok 821 listener has been set
,ok 822 peer dictionary has expected number of entries
,ok 823 Dictionary and pool have same action
,ok 824 ads match
,ok 825 PouchDB matches
,ok 826 DB Names match
,ok 827 public keys match
,ok 828 peer dictionary has expected number of entries
,ok 829 Dictionary and pool have same action
,ok 830 ads match
,ok 831 PouchDB matches
,ok 832 DB Names match
,ok 833 public keys match
,2017-08-01 11:33:51 - DEBUG thaliReplicationPeerAction: 'We called _complete with  and it caused us to complete'
,ok 834 start called once
,ok 835 One entry left
,ok 836 Dictionary and pool have same action
,ok 837 Start never called
,ok 838 Kill called once
,ok 839 no entries left
,ok 840 Third action is dead
,ok 841 peer dictionary has expected number of entries
,ok 842 Dictionary and pool have same action
,ok 843 ads match
,ok 844 PouchDB matches
,ok 845 DB Names match
,ok 846 public keys match
,# teardown
,# setup
,# Coordinated pull replication from notification test
,2017-08-01 11:33:51 - DEBUG CoordinatedClient: 'test was skipped, name: 'Coordinated pull replication from notification test''
,# teardown
,# setup
,# Server is not there
,2017-08-01 11:33:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-01 11:33:52 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 connect ECONNREFUSED'
,2017-08-01 11:33:52 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: connect ECONNREFUSED  and it caused us to complete'
,ok 847 right error
,# teardown
,2017-08-01 11:33:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server accepts & closes connection
,2017-08-01 11:33:52 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 socket hang up'
,2017-08-01 11:33:52 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: socket hang up  and it caused us to complete'
,ok 848 right error
,# teardown
,2017-08-01 11:33:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 500
,2017-08-01 11:33:53 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 changes rejected'
,2017-08-01 11:33:53 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 849 Got error as expected
,# teardown
,2017-08-01 11:33:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 401
,2017-08-01 11:33:54 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  401 changes rejected'
,2017-08-01 11:33:54 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 850 Got error as expected
,# teardown
,2017-08-01 11:33:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 403
,2017-08-01 11:33:54 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  403 changes rejected'
,2017-08-01 11:33:54 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 851 Got error as expected
,# teardown
,2017-08-01 11:33:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure docs replicate with remote db with same name as local db
,2017-08-01 11:33:56 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-08-01 11:33:56 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-08-01 11:33:58 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
,ok 852 should be equal
,ok 853 All tests passed!
,# teardown
,2017-08-01 11:34:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure docs replicate with remote db with different name than local db
,2017-08-01 11:34:01 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-08-01 11:34:02 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-08-01 11:34:04 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
,ok 854 should be equal
ok 855 All tests passed!
,# teardown
,2017-08-01 11:34:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Do nothing and make sure we time out
,2017-08-01 11:34:06 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-08-01 11:34:08 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2017-08-01 11:34:08 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and s,o we ignored it'
ok 856 action should be killed
ok 857 Error should be timed out
,ok 858 No doc found
,# teardown
,2017-08-01 11:34:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Do something and make sure we time out
,2017-08-01 11:34:09 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-08-01 11:34:10 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,ok 859 should be equal
,2017-08-01 11:34:11 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2017-08-01 11:34:11 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and s,o we ignored it'
,ok 860 action should be killed
ok 861 Error should be timed out
,# teardown
,2017-08-01 11:34:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Start replicating and then catch error when server goes
,ok 862 socket hung up
,# teardown
,2017-08-01 11:34:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure clone works
,ok 863 same getPeerAdvertisesDataForUs
,ok 864 Same pouchdB
ok 865 same localDbName
ok 866 Same public key
,# teardown
,# setup
,# Coordinated replication action test - each device has the same local db name
,2017-08-01 11:34:14 - DEBUG CoordinatedClient: 'test was skipped, name: 'Coordinated replication action test - each device has the same local db name''
,# teardown
,# setup
,# Coordinated replication action test - each device has different local db name
,2017-08-01 11:34:15 - DEBUG thaliMobileNativeWrapper: 'listening 64854'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C01422D0-A999-486C-9896-7E773FFB2A7E
[ThaliCore] Browser.startListening
,2017-08-01 11:34:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "94315540-88C1-4914-B493-B105D908F8AF", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:94315540-88C1-4914-B493-B105D908F8AF
,2017-08-01 11:34:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:94315540-88C1-4914-B493-B105D908F8AF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "94315540-88C1-4914-B493-B105D908F8AF", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B271DA44-A576-46BE-9CB5-E4002F1E015B
[ThaliCore] Advertiser: session connected Peer(uuid: "94315540-88C1-4914-B493-B105D908F8AF", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:B271DA44-A576-46BE-9CB5-E4002F1E015B state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E07BFCF8-CD88-4962-AAA9-802C74BFD5C1:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E07BFCF8-CD88-4962-AAA9-802C74BFD5C1", generation: 0)
2017-08-01 11:34:16 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"E07BFCF8-CD88-4962-AAA9-802C74BFD5C1","generation":0}]'
2017-08-01 11:34:16 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"E07BFCF8-CD88-4962-AAA9-802C74BFD5C1","generation":0}'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:67DF26D7-0391-46BF-9A8E-7C486EF20B1D
[ThaliCore] Advertiser: session connected Peer(uuid: "94315540-88C1-4914-B493-B105D908F8AF", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:67DF26D7-0391-46BF-9A8E-7C486EF20B1D state: notConnected -> connecting
2017-08-01 11:34:16 - DEBUG thaliMobileNativeWrapper: 'handlePeerAv,ailabilityChanged - Emitting {"peerIdentifier":"E07BFCF8-CD88-4962-AAA9-802C74BFD5C1","peerAvailable":true,"generation":0,"portNumber":null}'
2017-08-01 11:34:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"E07,BFCF8-CD88-4962-AAA9-802C74BFD5C1","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-08-01 11:34:16 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for E07BFCF8-CD88-4962-AAA9-802C74BFD5C1 (syncValue: 3)'
2,017-08-01 11:34:16 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E07BFCF8-CD88-4962-AAA9-802C74BFD5C1", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E07BFCF8-CD88-4962-AAA9-802C74BFD5C1", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E07BFCF8-CD88-4962-AAA9-802C74BFD5C1:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3C03286D-92EB-4924-A2C4-E042DE28FC9F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3C03286D-92EB-4924-A2C4-E042DE28FC9F", generation: 0)
,2017-08-01 11:34:17 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"3C03286D-92EB-4924-A2C4-E042DE28FC9F","generation":0}]'
,2017-08-01 11:34:17 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"3C03286D-92EB-4924-A2C4-E042DE28FC9F","generation":0}'
,2017-08-01 11:34:17 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"3C03286D-92EB-4924-A2C4-E042DE28FC9F","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-01 11:34:17 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"3C03286D-92EB-4924-A2C4-E042DE28FC9F","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:E07BFCF8-CD88-4962-AAA9-802C74BFD5C1:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FF233C22-60DB-4B1D-B6ED-7DC1227E0497:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FF233C22-60DB-4B1D-B6ED-7DC1227E0497", generation: 0)
2017-08-01 11:34:17 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"FF233C22-60DB-4B1D-B6ED-7DC1227E0497","generation":0}]'
2017-08-01 11:34:17 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"FF233C22-60DB-4B1D-B6ED-7DC1227E0497","generation":0}'
,2017-08-01 11:34:17 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"FF233C22-60DB-4B1D-B6ED-7DC1227E0497","peerAvailable":true,"generation":0,"portNumber":null}'
2017-08-01 11:34:17 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"FF233C22-60DB-4B1D-B6ED-7DC1227E0497","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:E07BFCF8-CD88-4962-AAA9-802C74BFD5C1:0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B271DA44-A576-46BE-9CB5-E4002F1E015B
,[ThaliCore] Session.session(_:peer:didChange:) peer:E07BFCF8-CD88-4962-AAA9-802C74BFD5C1:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "E07BFCF8-CD88-4962-AAA9-802C74BFD5C1", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:64857
,2017-08-01 11:34:19 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"3","error":null,"portNumber":64857}'
,2017-08-01 11:34:19 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 3C03286D-92EB-4924-A2C4-E042DE28FC9F (syncValue: 4)'
2017-08-01 11:34:19 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3C03286D-92EB-4924-A2C4-E042DE28FC9F", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3C,03286D-92EB-4924-A2C4-E042DE28FC9F", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3C03286D-92EB-4924-A2C4-E042DE28FC9F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:B271DA44-A576-46BE-9CB5-E4002F1E015B state: connecting -> connected
[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:67DF26D7-0391-46BF-9A8E-7C486EF20B1D
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E07BFCF8-CD88-4962-AAA9-802C74BFD5C1:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:67DF26D7-0391-46BF-9A8E-7C486EF20B1D state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E07BFCF8-CD88-4962-AAA9-802C74BFD5C1:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:24 [4, 10, 16, 24]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B271DA44-A576-46BE-9CB5-E4002F1E015B
[ThaliCore] Session.startOutputStream(with:) peer:B271DA44-A576-46BE-9CB5-E4002F1E015B
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:25 [4, 10, 16, 24, 25]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:24
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:24
[ThaliCore] VirtualSocket.deinit vsID:24 [4, 10, 16, 25]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:67DF26D7-0391-46BF-9A8E-7C486EF20B1D
[ThaliCore] Session.startOutputStream(with:) peer:67DF26D7-0391-46BF-9A8E-7C486EF20B1D
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2,6 [4, 10, 16, 25, 26]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E07BFCF8-CD88-4962-AAA9-802C74BFD5C1:0
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E07BFCF8-CD88-4962-AAA9-802C74BFD5C1:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:27 [4, 10, 16, 25, 26, 27]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler,
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:25
[ThaliCore] VirtualSocket.closeStreams() vsID:25
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:,25
[ThaliCore] VirtualSocket.deinit vsID:25 [4, 10, 16, 26, 27]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B271DA44-A576-46BE-9CB5-E4002F1E015B
[ThaliCore] Session.startOutputStream(with:) peer:B271DA44-A576-46BE-9CB5-E4002F1E015B
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:28 [4, 10, 16, 26, 27, 28]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:26
[ThaliCore] VirtualSocket.closeStreams() vsID:26
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:67DF26D7-0391-46BF-9A8E-7C486EF20B1D
[ThaliCore] Session.startOutputStream(with:) peer:67DF26D7-0391-46BF-9A8E-7C486EF20B1D
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:29 [4, 10, 16, 26, 27, 28, 29]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-08-01 11:34:20 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B271DA44-A576-46BE-9CB5-E4002F1E015B
[ThaliCore] Session.startOutputStream(with:) peer:B271DA44-A576-46BE-9CB5-E4002F1E015B
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:30 [4, 10, 16, 26, 27, 28, 29, 30]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:peer:didChange:) peer:3C03286D-92EB-4924-A2C4-E042DE28FC9F:0 state: notConnected -> connecting
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E07BFCF8-CD88-4962-AAA9-802C74BFD5C1:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E07BFCF8-CD88-4962-AAA9-802C74BFD5C1:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:31 [4, 10, 16, 26, 27, 28, 29, 30, 31]
[ThaliCore] BrowserRelay.didOpenVirtualSocketSt,reamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B271DA44-A576-46BE-9CB5-E4002F1E015B
[ThaliCore] Session.startOutputStream(with:) peer:B271DA44-A576-46BE-9CB5-E4002F1E015B
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:32 [4, 10, 16, 26, 27, 28, 29, 30, 31, 32]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E07BFCF8-CD88-4962-AAA9-802C74BFD5C1:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:67DF26D7-0391-46BF-9A8E-7C486EF20B1D
[ThaliCore] Session.startOutputStream(with:) peer:67DF26D7-0391-46BF-9A8E-7C486EF20B1D
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:33 [4, 10, 16, 26, 27, 28, 29, 30, 31, 32, 33]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E07BFCF8-CD88-4962-AAA9-802C74BFD5C1:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:34 [4, 10, 16, 26, 27, 28, 29, 30, 31, 32, 33, 34]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B271DA44-A576-46BE-9CB5-E4002F1E015B
[ThaliCore] Session.startOutputStream(with:) peer:B271DA44-A576-46BE-9CB5-E4002F1E015B
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:35 [4, 10, 16, 26, 27, 28, 29, 30, 31, 32, 33, 34, 35]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E07BFCF8-CD88-4962-AAA9-802C74BFD5C1:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E07BFCF8-CD88-4962-AAA9-802C74BFD5C1:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:36 [4, 10, 16, 26, 27, 28, 29, 30, 31, 32, 33, 34, 35, 36]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E07BFCF8-CD88-4962-AAA9-802C74BFD5C1:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E07BFCF8-CD88-4962-AAA9-802C74BFD5C1:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:37 [4, 10, 16, 26, 27, 28, 29, 30, 31, 32, 33, 34, 35, 36, 37]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:28
[ThaliCore] VirtualSocket.closeStreams() vsID:28
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:30
[ThaliCore] VirtualSocket.closeStreams() vsID:30
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:28
,[ThaliCore] VirtualSocket.deinit vsID:28 [4, 10, 16, 26, 27, 29, 30, 31, 32, 33, 34, 35, 36, 37]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:30
[ThaliCore] VirtualSocket.deinit vsID:30 [4, 10, 16, 26, 27, 29, 31, 32, 33, 34, 35, 36, 37]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPCli,ent.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:32
,[ThaliCore] VirtualSocket.closeStreams() vsID:32
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:32
[ThaliCore] VirtualSocket.deinit vsID:32 [4, 10, 16, 26, 27, 29, 31, 33, 34, 35, 36, 37]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.,socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:35
[ThaliCore] VirtualSocket.closeStreams() vsID:35
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:35
[ThaliCore] VirtualSocket.deinit vsID:35 [4, 10, 16, 26, 27, 29, 31, 33, 34, 36, 37]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.sock,etDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:36
[ThaliCore] Browse,rRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:36
,[ThaliCore] VirtualSocket.deinit vsID:36 [4, 10, 16, 26, 27, 29, 31, 33, 34, 37]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:67DF26D7-0391-46BF-9A8E-7C486EF20B1D
[ThaliCore] Session.startOutputStream(with:) peer:67DF26D7-0391-46BF-9A8E-7C486EF20B1D
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:38 [4, 10, 16, 26, 27, 29, 31, 33, 34, 37, 38]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E07BFCF8-CD88-4962-AAA9-802C74BFD5C1:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E07BFCF8-CD88-4962-AAA9-802C74BFD5C1:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:39 [4, 10, 16, 26, 27, 29, 31, 33, 34, 37, 38, 39]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-08-01 11:34:21 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:39
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:39
,[ThaliCore] VirtualSocket.deinit vsID:39 [4, 10, 16, 26, 27, 29, 31, 33, 34, 37, 38]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:67DF26D7-0391-46BF-9A8E-7C486EF20B1D
[ThaliCore] Session.startOutputStream(with:) peer:67DF26D7-0391-46BF-9A8E-7C486EF20B1D
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:40 [4, 10, 16, 26, 27, 29, 31, 33, 34, 37, 38, 40]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:67DF26D7-0391-46BF-9A8E-7C486EF20B1D
[ThaliCore] Session.startOutputStream(with:) peer:67DF26D7-0391-46BF-9A8E-7C486EF20B1D
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:41 [4, 10, 16, 26, 27, 29, 31, 33, 34, 37, 38, 40, 41]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:40
[ThaliCore] VirtualSocket.closeStreams() vsID:40
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:40
[ThaliCore] VirtualSocket.deinit vsID:40 [4, 10, 16, 26, 27, 29, 31, 33, 34, 37, 38, 41]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.,socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:3C03286D-92EB-4924-A2C4-E042DE28FC9F:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:3C03286D-92EB-4924-A2C4-E042DE28FC9F:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "3C03286D-92EB-4924-A2C4-E042DE28FC9F", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:64878
2017-08-01 11:34:22 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"4","error":null,"portNumber":64878,}'
,2017-08-01 11:34:22 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for FF233C22-60DB-4B1D-B6ED-7DC1227E0497 (syncValue: 5)'
2017-08-01 11:34:22 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "FF233C22-60DB-4B1D-B6ED-7DC1227E0497", generation: 0) found active relay
2017-08-01 11:34:22 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"5","error":null,"portNumber":64726}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:3C03286D-92EB-4924-A2C4-E042DE28FC9F:0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[Th,aliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:FF233C22-60DB-4B1D-B6ED-7DC1227E0497:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FF233C22-60DB-4B1D-B6ED-7DC1227E0497:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:42 [4, 10, 16, 26, 27, 29, 31, 33, 34, 37, 38, 41, 42]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3C03286D-92EB-4924-A2C4-E042DE28FC9F:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:43 [4, 10, 16, 26, 27, 29, 31, 33, 34, 37, 38, 41, 42, 43]
[ThaliCore] VirtualSocket.h,andleEventOnInputStream endEncountered vsID:42
[ThaliCore] VirtualSocket.closeStreams() vsID:42
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:42
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.deinit vsID:42 [4, 10, 16, 26, 27, 29, 31, 33, 34, 37, 38, 41, 43]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-08-01 11:34:23 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,2017-08-01 11:34:23 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for FF233C22-60DB-4B1D-B6ED-7DC1227E0497 (syncValue: 6)'
2017-08-01 11:34:23 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "FF233C22-60DB-4B1D-B6ED-7DC1227E0497", generation: 0) found active relay
2017-08-01 11:34:23 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"6","error":null,"portNumber":64726}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:FF233C22-60DB-4B1D-B6ED-7DC1227E0497:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FF233C22-60DB-4B1D-B6ED-7DC1227E0497:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:44 [4, 10, 16, 26, 27, 29, 31, 33, 34, 37, 38, 41, 43, 44]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:44
[ThaliCore] VirtualSocket.closeStreams() vsID:44
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:44
[ThaliCore] VirtualSocket.deinit vsID:44 [4, 10, 16, 26, 27, 29, 31, 33, 34, 37, 38, 41, 43]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:,0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:43
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:43
[ThaliCore] VirtualSocket.deinit vsID:43 [4, 10, 16, 26, 27, 29, 31, 33, 34, 37, 38, 41]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:3C03286D-92EB-4924-A2C4-E042DE28FC9F:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3C03286D-92EB-4924-A2C4-E042DE28FC9F:0
2017-08-01 11:34:23 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:45 [4, 10, 16, 26, 27, 29, 31, 33, 34, 37, 38, 41, 45]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-08-01 11:34:23 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:3C03286D-92EB-4924-A2C4-E042DE28FC9F:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3C03286D-92EB-4924-A2C4-E042DE28FC9F:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:46 [4, 10, 16, 26, 27, 29, 31, 33, 34, 37, 38, 41, 45, 46]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-08-01 11:34:23 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for FF233C22-60DB-4B1D-B6ED-7DC1227E0497 (syncValue: 7)'
,2017-08-01 11:34:23 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "FF233C22-60DB-4B1D-B6ED-7DC1227E0497", generation: 0) found active relay
,2017-08-01 11:34:23 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"7","error":null,"portNumber":64726}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:FF233C22-60DB-4B1D-B6ED-7DC1227E0497:0
,2017-08-01 11:34:23 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
,2017-08-01 11:34:23 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FF233C22-60DB-4B1D-B6ED-7DC1227E0497:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:47 [4, 10, 16, 26, 27, 29, 31, 33, 34, 37, 38, 41, 45, 46, 47]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:27
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:27
[ThaliCore] Brows,erRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:31
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket clo,sed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketD,isconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.deinit vsID:27 [4, 10, 16, 26, 29, 31, 33, 34, 37, 38, 41, 45, 46, 47]
[ThaliCore] VirtualSocket.closeStreams() vsID:34
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted, socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] VirtualSocket exited RunLoop vsID:31
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] VirtualSocket.deinit vsID:31 [4, 10, 16, 26, 29, 33, 34, 37, 38, 41, 45, 46, 47]
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:37
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:34
,[ThaliCore] VirtualSocket.deinit vsID:34 [4, 10, 16, 26, 29, 33, 37, 38, 41, 45, 46, 47]
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:37
[ThaliCore] VirtualSocket.deinit vsID:37 [4, 10, 16, 26, 29, 33, 38, 41, 45, 46, 47]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:47
[ThaliCore] VirtualSocket.closeStreams() vsID:47
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:47
[ThaliCore] VirtualSocket.deinit vsID:47 [4, 10, 16, 26, 29, 33, 38, 41, 45, 46]
[ThaliCore] TCPListener.socketDidDisconnect(_:,withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-08-01 11:34:23 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:3C03286D-92EB-4924-A2C4-E042DE28FC9F:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3C03286D-92EB-4924-A2C4-E042DE28FC9F:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:48 [4, 10, 16, 26, 29, 33, 38, 41, 45, 46, 48]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:29
[ThaliCore] VirtualSocket.closeStreams() vsID:29
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:29
[ThaliCore] VirtualSocket.deinit vsID:29 [4, 10, 16, 26, 33, 38, 41, 45, 46, 48]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected,
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:33
[ThaliCore] VirtualSocket.closeStreams() vsID:33
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:,33
[ThaliCore] VirtualSocket.deinit vsID:33 [4, 10, 16, 26, 38, 41, 45, 46, 48]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[Th,aliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:38
[ThaliCore] VirtualSocket.closeStreams() vsID:38
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:38
[ThaliCore] VirtualSocket.deinit vsID:38 [4, 10, 16, 26, 41, 45, 46, 48]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliC,ore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:41
[ThaliCore] VirtualSocket.closeStreams() vsID:41
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:41
[ThaliCore] VirtualSocket.deinit vsID:41 [4, 10, 16, 26, 45, 46, 48]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:67DF26D7-0391-46BF-9A8E-7C486EF20B1D
[ThaliCore] Session.startOutputStream(with:) peer:67DF26D7-0391-46BF-9A8E-7C486EF20B1D
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4,9 [4, 10, 16, 26, 45, 46, 48, 49]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:3C03286D-92EB-4924-A2C4-E042DE28FC9F:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3C03286D-92EB-4924-A2C4-E042DE28FC9F:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:50 [4, 10, 16, 26, 45, 46, 48, 49, 50]
[ThaliCore] BrowserRelay.didOpenVirtualSocketSt,reamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:3C03286D-92EB-4924-A2C4-E042DE28FC9F:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3C03286D-92EB-4924-A2C4-E042DE28FC9F:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:51 [4, 10, 16, 26, 45, 46, 48, 49, 50, 51]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-08-01 11:34:24 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for FF233C22-60DB-4B1D-B6ED-7DC1227E0497 (syncValue: 8)'
2017-08-01 11:34:24 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPee,r(_:syncValue:retryCount:completion:) Peer(uuid: "FF233C22-60DB-4B1D-B6ED-7DC1227E0497", generation: 0) found active relay
2017-08-01 11:34:24 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"8","error":null,"portNumber":64726}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:FF233C22-60DB-4B1D-B6ED-7DC1227E0497:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FF233C22-60DB-4B1D-B6ED-7DC1227E0497:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:52 [4, 10, 16, 26, 45, 46, 48, 49, 50, 51, 52]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:52
[ThaliCore] VirtualSocket.closeStreams() vsID:52
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:52
[ThaliCore] VirtualSocket.deinit vsID:52 [4, 10, 16, 26, 45, 46, 48, 49, 50, 51]
[ThaliCore] TCPListener.socketDidDisconnect(_:,withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-08-01 11:34:24 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:45
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:45
,[ThaliCore] VirtualSocket.deinit vsID:45 [4, 10, 16, 26, 46, 48, 49, 50, 51]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:46
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:46
,[ThaliCore] VirtualSocket.deinit vsID:46 [4, 10, 16, 26, 48, 49, 50, 51]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:48
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:48
[,ThaliCore] VirtualSocket.deinit vsID:48 [4, 10, 16, 26, 49, 50, 51]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:50
,2017-08-01 11:34:24 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNRESET","status":500}'
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:50
,[ThaliCore] VirtualSocket.deinit vsID:50 [4, 10, 16, 26, 49, 51]
,2017-08-01 11:34:24 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 socket hang up -1'
,2017-08-01 11:34:24 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: socket hang up -1  but we are already killed and so we ignored it'
,2017-08-01 11:34:24 - DEBUG thaliReplicationPeerAction: 'Got error in update: 500 socket hang up -1, but we are already killed and so we ignored it'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:51
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:51
,[ThaliCore] VirtualSocket.deinit vsID:51 [4, 10, 16, 26, 49]
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:94315540-88C1-4914-B493-B105D908F8AF
2017-08-01 11:34:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-01 11:34:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"E07BFCF8-CD88-4962-AAA9-802C74BFD5C1","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-08-01, 11:34:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"3C03286D-92EB-4924-A2C4-E042DE28FC9F","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-08-01 11:34:24 ,- DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"FF233C22-60DB-4B1D-B6ED-7DC1227E0497","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore] AdvertiserManager.,stopAdvertising()
2017-08-01 11:34:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-01 11:34:24 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"adverti,s,ingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
2017-08-01 11:34:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).',
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-01 11:34:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-,01 11:34:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-01 11:34:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:49
[ThaliCore] VirtualSocket.closeS,treams() vsID:49
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:49
[ThaliCore] VirtualSocket.deinit vsID:49 [4, 10, 16, 26]
,ok 867 passed
,# teardown
,# setup
,# Coordinated replication action test - should throw error when wrong remote db name is provided
,2017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'listening 64890'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:E62D93A2-9949-43F9-985B-1E19C97A3BE1
[ThaliCore] Browser.startListening
,2017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E07BFCF8-CD88-4962-AAA9-802C74BFD5C1:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E07BFCF8-CD88-4962-AAA9-802C74BFD5C1", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3C03286D-92EB-4924-A2C4-E042DE28FC9F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3C03286D-92EB-4924-A2C4-E042DE28FC9F", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FF233C22-60DB-4B1D-B6ED-7DC1227E0497:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FF233C22-60DB-4B1D-B6ED-7DC1227E0497", generation: 0)
,2017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"E07BFCF8-CD88-4962-AAA9-802C74BFD5C1","generation":0}]'
2017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"E07BFCF8-CD88-4962-AAA9-802C74BFD5C1","generation":0}'
,2017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"3C03286D-92EB-4924-A2C4-E042DE28FC9F","generation":0}]'
,2017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"3C03286D-92EB-4924-A2C4-E042DE28FC9F","generation":0}'
,2017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"FF233C22-60DB-4B1D-B6ED-7DC1227E0497","generation":0}]'
,2017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"FF233C22-60DB-4B1D-B6ED-7DC1227E0497","generation":0}'
,2017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"E07BFCF8-CD88-4962-AAA9-802C74BFD5C1","peerAvailable":true,"generation":0,"portNumber":null}'
2017-08-01 11:34:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"E07BFCF8-CD88-4962-AAA9-802C74BFD5C1","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"3C03286D-92EB-4924-A2C4-E042DE28FC9F","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-01 11:34:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"3C03286D-92EB-4924-A2C4-E042DE28FC9F","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"FF233C22-60DB-4B1D-B6ED-7DC1227E0497","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-01 11:34:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"FF233C22-60DB-4B1D-B6ED-7DC1227E0497","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for E07BFCF8-CD88-4962-AAA9-802C74BFD5C1 (syncValue: 9)'
,2017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E07BFCF8-CD88-4962-AAA9-802C74BFD5C1", generation: 0) found active relay
,2017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"9","error":null,"portNumber":64857}'
,2017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 3C03286D-92EB-4924-A2C4-E042DE28FC9F (syncValue: 10)'
,2017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3C03286D-92EB-4924-A2C4-E042DE28FC9F", generation: 0) found active relay
,2017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"10","error":null,"portNumber":64878}'
,2017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for FF233C22-60DB-4B1D-B6ED-7DC1227E0497 (syncValue: 11)'
,2017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "FF233C22-60DB-4B1D-B6ED-7DC1227E0497", generation: 0) found active relay
,2017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"11","error":null,"portNumber":64726}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E07BFCF8-CD88-4962-AAA9-802C74BFD5C1:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:3C03286D-92EB-4924-A2C4-E042DE28FC9F:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:FF233C22-60DB-4B1D-B6ED-7DC1227E0497:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3C03286D-92EB-4924-A2C4-E042DE28FC9F:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:53 [4, 10, 16, 26, 53]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E07BFCF8-CD88-4962-AAA9-802C74BFD5C1:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:54 [4, 10, 16, 26, 53, 54]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "2B8EBEB4-F1B6-49B3-A042-2931850C5299", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:2B8EBEB4-F1B6-49B3-A042-2931850C5299
,2017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:53
[ThaliCore] VirtualSocket.closeStreams() vsID:53
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:53
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] VirtualSocket.deinit vsID:53 [4, 10, 16, 26, 54]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] Session.session(_:didReceive:withName:fromPeer,:) peer:FF233C22-60DB-4B1D-B6ED-7DC1227E0497:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:55 [4, 10, 16, 26, 54, 55]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-08-01 11:34:26 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:54
[ThaliCore] VirtualSocket.closeStreams() vsID:54
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:54
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] VirtualSocket.deinit vsID:54 [4, 10, 16, 26, 55]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) s,ocket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-08-01 11:34:26 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:55
[ThaliCore] VirtualSocket.closeStreams() vsID:55
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:55
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] VirtualSocket.deinit vsID:55 [4, 10, 16, 26]
,2017-08-01 11:34:26 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B271DA44-A576-46BE-9CB5-E4002F1E015B
[ThaliCore] Session.startOutputStream(with:) peer:B271DA44-A576-46BE-9CB5-E4002F1E015B
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5,6 [4, 10, 16, 26, 56]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=32 "Broken pipe" UserInfo={NSLocalizedDescription=Broken pipe, NSLocalizedFailureReason=Error in connect() function})
[T,haliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:56
[ThaliCore] VirtualSocket.closeStreams() vsID:56
[ThaliCore] AdvertiserRelay.didCloseVirtualSo,cketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:56
[ThaliCore] VirtualSocket.deinit vsID:56 [4, 10, 16, 26]
2017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for E07BFCF8-CD88-4962-AAA9-802C74BFD5C1 (syncValue: 12)'
,2017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E07BFCF8-CD88-4962-AAA9-802C74BFD5C1", generation: 0) found active relay
,2017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"12","error":null,"portNumber":64857}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E07BFCF8-CD88-4962-AAA9-802C74BFD5C1:0
,2017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 3C03286D-92EB-4924-A2C4-E042DE28FC9F (syncValue: 13)'
,2017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3C03286D-92EB-4924-A2C4-E042DE28FC9F", generation: 0) found active relay
2017-08-01, 11:34:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"13","error":null,"portNumber":64878}'
2017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for FF233C22-60DB-4B1D-B6ED-7DC1227E0497 (syncValue: 14)'
2,017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "FF233C22-60DB-4B1D-B6ED-7DC1227E0497", generation: 0) found active relay
2017-08-01 ,11:34:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"14","error":null,"portNumber":64726}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:3C03286D-92EB-4924-A2C4-E042DE28FC9F:0
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E07BFCF8-CD88-4962-AAA9-802C74BFD5C1:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:57 [4, 10, 16, 26, 57]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[Thal,iCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:FF233C22-60DB-4B1D-B6ED-7DC1227E0497:0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:57
[ThaliCore] VirtualSocket.closeStreams() vsID:57
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:57
[Th,aliCore] VirtualSocket.deinit vsID:57 [4, 10, 16, 26]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3C03286D-92EB-4924-A2C4-E042DE28FC9F:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:58 [4, 10, 16, 26, 58]
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) pe,er:FF233C22-60DB-4B1D-B6ED-7DC1227E0497:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:59 [4, 10, 16, 26, 58, 59]
2017-08-01 11:34:26 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
[ThaliCore] BrowserRelay,.didOpenVirtualSocketStreamsHandler
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:58
[ThaliCore] VirtualSocket.closeStreams() vsID:58
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:59
[ThaliCore] VirtualSocket.closeStreams() vsID:59
[Thali,Core] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:58
[ThaliCore] VirtualSocket.deinit vsID:58 [4, 10, 16, 26, 59]
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:conne,cted
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] TCPListener.socke,tDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-08-01 11:34:26 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,2017-08-01 11:34:26 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:67DF26D7-0391-46BF-9A8E-7C486EF20B1D
[ThaliCore] Session.startOutputStream(with:) peer:67DF26D7-0391-46BF-9A8E-7C486EF20B1D
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:60 [4, 10, 16, 26, 59, 60]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=32 "Broken pipe" UserInfo={NSLocalizedDescription=Broken pipe, NSLocalizedFailureReason=Error in connect() function})
[T,haliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:60
[ThaliCore] VirtualSocket.closeStreams() vsID:60
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:60
,[ThaliCore] VirtualSocket.deinit vsID:60 [4, 10, 16, 26, 59]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B271DA44-A576-46BE-9CB5-E4002F1E015B
[ThaliCore] Session.startOutputStream(with:) peer:B271DA44-A576-46BE-9CB5-E4002F1E015B
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6,1 [4, 10, 16, 26, 59, 61]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=32 "Broken pipe" UserInfo={NSLocalizedDescription=Broken pipe, NSLocalizedFailureReason=Error in connect() function})
[T,haliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:61
[ThaliCore] VirtualSocket.closeStreams() vsID:61
[ThaliCore] AdvertiserRelay.didCloseVirtualSo,cketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:61
[ThaliCore] VirtualSocket.deinit vsID:61 [4, 10, 16, 26, 59]
,2017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for E07BFCF8-CD88-4962-AAA9-802C74BFD5C1 (syncValue: 15)'
2017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPe,er(_:syncValue:retryCount:completion:) Peer(uuid: "E07BFCF8-CD88-4962-AAA9-802C74BFD5C1", generation: 0) found active relay
2017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"15","error":null,"portNumber":64857}'
[,ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E07BFCF8-CD88-4962-AAA9-802C74BFD5C1:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E07BFCF8-CD88-4962-AAA9-802C74BFD5C1:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:62 [4, 10, 16, 26, 59, 62]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler,
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:62
[ThaliCore] VirtualSocket.closeStreams() vsID:62
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:62
[Th,aliCore] VirtualSocket.deinit vsID:62 [4, 10, 16, 26, 59]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-08-01 11:34:26 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:67DF26D7-0391-46BF-9A8E-7C486EF20B1D
[ThaliCore] Session.startOutputStream(with:) peer:67DF,26D7-0391-46BF-9A8E-7C486EF20B1D
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:63 [4, 10, 16, 26, 59, 63]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,2017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 3C03286D-92EB-4924-A2C4-E042DE28FC9F (syncValue: 16)'
2017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPe,er(_:syncValue:retryCount:completion:) Peer(uuid: "3C03286D-92EB-4924-A2C4-E042DE28FC9F", generation: 0) found active relay
2017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"16","error":null,"portNumber":64878}'
,2017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for FF233C22-60DB-4B1D-B6ED-7DC1227E0497 (syncValue: 17)'
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:3C03286D-92EB-4924-A2C4-E042DE28FC9F:0
2017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "FF233C22-60DB-4B1D-B6ED-7DC1227E0497", generation: 0) found active relay
2017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"17,","error":null,"portNumber":64726}'
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=70 "Stale NFS file handle" UserInfo={NSLocalizedDescription=Stale NFS file handle, N,SLocalizedFailureReason=Error in connect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:63
[ThaliCore] VirtualSocket.closeStreams,() vsID:63
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3C03286D-92EB-4924-A2C4-E042DE28FC9F:0
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:64 [4, 10, 16, 26, 59, 63, 64]
,[ThaliCore] VirtualSocket exited RunLoop vsID:63
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] VirtualSocket.deinit vsID:63 [4, 10, 16, 26, 59, 64]
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:FF233C22-60DB-4B1D-B6ED-7DC1227E0497:0
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:64
[ThaliCore] VirtualSocket.closeStreams() vsID:64
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:64
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisc,onnectHandler
[ThaliCore] VirtualSocket.deinit vsID:64 [4, 10, 16, 26, 59]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FF233C22-60DB-4B1D-B6ED-7DC1227E0497:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:65 [4, 10, 16, 26, 59, 65]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-08-01 11:34:26 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:65
[ThaliCore] VirtualSocket.closeStreams() vsID:65
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:65
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] VirtualSocket.deinit vsID:,65 [4, 10, 16, 26, 59]
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-08-01 11:34:26 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:638674DE-1248-425B-BB3C-67ABE1127ADB
[ThaliCore] Session.session(_:peer:didChange:) peer:638674DE-1248-425B-BB3C-67ABE1127ADB state: notConnected -> connecting
[ThaliCore] Advertiser: session connected Peer(uuid: "2B8EBEB4-F1B6-49B3-A042-2931850C5299", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B271DA44-A576-46BE-9CB5-E4002F1E015B
[ThaliCore] Session.startOutputStream(with:) peer:B271DA44-A576-46BE-9CB5-E4002F1E015B
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:66 [4, 10, 16, 26, 59, 66]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=35 "Resource temporarily unavailable" UserInfo={NSLocalizedDescription=Resource temporarily unavailable, NSLocalizedFailureReason=Error in connect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:66
[ThaliCore] VirtualSocket.closeStreams() vsID:66
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:66
,[ThaliCore] VirtualSocket.deinit vsID:66 [4, 10, 16, 26, 59]
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:89459276-EC79-4CF3-8003-7EC0263C9F17:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "89459276-EC79-4CF3-8003-7EC0263C9F17", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:2B8EBEB4-F1B6-49B3-A042-2931850C5299:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2B8EBEB4-F1B6-49B3-A042-2931850C5299", generation: 0)
,2017-08-01 11:34:27 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"89459276-EC79-4CF3-8003-7EC0263C9F17","generation":0}]'
,2017-08-01 11:34:27 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"89459276-EC79-4CF3-8003-7EC0263C9F17","generation":0}'
,2017-08-01 11:34:27 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"89459276-EC79-4CF3-8003-7EC0263C9F17","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-01 11:34:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"89459276-EC79-4CF3-8003-7EC0263C9F17","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-08-01 11:34:27 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 89459276-EC79-4CF3-8003-7EC0263C9F17 (syncValue: 18)'
,2017-08-01 11:34:27 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "89459276-EC79-4CF3-8003-7EC0263C9F17", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "89,459276-EC79-4CF3-8003-7EC0263C9F17", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:89459276-EC79-4CF3-8003-7EC0263C9F17:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:68F79609-0A85-42F9-884E-51FBAC4E0541:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "68F79609-0A85-42F9-884E-51FBAC4E0541", generation: 0)
,2017-08-01 11:34:27 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"68F79609-0A85-42F9-884E-51FBAC4E0541","generation":0}]'
,2017-08-01 11:34:27 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"68F79609-0A85-42F9-884E-51FBAC4E0541","generation":0}'
,2017-08-01 11:34:27 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"68F79609-0A85-42F9-884E-51FBAC4E0541","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-01 11:34:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"68F79609-0A85-42F9-884E-51FBAC4E0541","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:89459276-EC79-4CF3-8003-7EC0263C9F17:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B271DA44-A576-46BE-9CB5-E4002F1E015B
[ThaliCore] Session.startOutputStream(with:) peer:B271DA44-A576-46BE-9CB5-E4002F1E015B
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:67 [4, 10, 16, 26, 59, 67]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=48 "Address already in use" UserInfo={NSLocalizedDescription=Address already in use, NSLocalizedFailureReason=Error in co,nnect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:67
[ThaliCore] VirtualSocket.closeStreams() vsID:67
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:67
,[ThaliCore] VirtualSocket.deinit vsID:67 [4, 10, 16, 26, 59]
,[ThaliCore] Session.session(_:peer:didChange:) peer:3C03286D-92EB-4924-A2C4-E042DE28FC9F:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() po,rt:64878
[ThaliCore] Session.disconnect() peer:3C03286D-92EB-4924-A2C4-E042DE28FC9F:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "3C03286D-92EB-4924-A2C4-E042DE28FC9F", generation: 0)
2017-08-01 11:34:27 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"4","error":"Session disconnected",,"portNumber":null}'
,[ThaliCore] Session.deinit peer:3C03286D-92EB-4924-A2C4-E042DE28FC9F:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:FF233C22-60DB-4B1D-B6ED-7DC1227E0497:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "FF233C22-60DB-4B1D-B6ED-7DC1227E0497", generation: 0)
[ThaliCore] BrowserRelay.closeRelay() state:connec,ted
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:64726
[ThaliCore] Session.disconnect() peer:FF233C22-60DB-4B1D-B6ED-7DC1227E0497:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[,ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:FF233C22-60DB-4B1D-B6ED-7DC1227E0497:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "FF233C22-60DB-4B1D-B6ED-7DC1227E0497", generation: 0) relay removed
2017-08-01 11:34:28 - DEBUG thaliMobileNativeWrapper: ',Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"FF233C22-60DB-4B1D-B6ED-7DC1227E0497","generation":0}]'
2017-08-01 11:34:28 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with, {"peerAvailable":false,"peerIdentifier":"FF233C22-60DB-4B1D-B6ED-7DC1227E0497","generation":0}'
,2017-08-01 11:34:28 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"FF233C22-60DB-4B1D-B6ED-7DC1227E0497","peerAvailable":false,"generation":null,"portNumber":null}'
2017-08-01 11:34:28 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"FF233C22-60DB-4B1D-B6ED-7DC1227E0497","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-08-01 11:34:28 - WARN thaliNotificationClient: 'peer is not avai,lable'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:89459276-EC79-4CF3-8003-7EC0263C9F17:0
[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:638674DE-1248-425B-BB3C-67ABE1127ADB
,[ThaliCore] Session.session(_:peer:didChange:) peer:89459276-EC79-4CF3-8003-7EC0263C9F17:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "89459276-EC79-4CF3-8003-7EC0263C9F17", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:64908
,2017-08-01 11:34:29 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"18","error":null,"portNumber":64908}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:638674DE-1248-425B-BB3C-67ABE1127ADB state: connecting -> connected
,2017-08-01 11:34:29 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 68F79609-0A85-42F9-884E-51FBAC4E0541 (syncValue: 19)'
,2017-08-01 11:34:29 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "68F79609-0A85-42F9-884E-51FBAC4E0541", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "68F79609-0A85-42F9-884E-51FBAC4E0541", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:68F79609-0A85-42F9-884E-51FBAC4E0541:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:89459276-EC79-4CF3-8003-7EC0263C9F17:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:89459276-EC79-4CF3-8003-7EC0263C9F17:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:68 [4, 10, 16, 26, 59, 68]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:638674DE-1248-425B-BB3C-67ABE1127ADB
[ThaliCore] Session.startOutputStream(with:) peer:638674DE-1248-425B-BB3C-67ABE1127ADB
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:69 [4, 10, 16, 26, 59, 68, 69]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:67DF26D7-0391-46BF-9A8E-7C486EF20B1D
[ThaliCore] Session.startOutputStream(with:) peer:67DF26D7-0391-46BF-9A8E-7C486EF20B1D
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:70 [4, 10, 16, 26, 59, 68, 69, 70]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=36 "Operation now in progress" UserInfo={NSLocalizedDescription=Operation now in progress, NSLocalizedFailureReason=Error, in connect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:70
[ThaliCore] VirtualSocket.closeStreams() vsID:70
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:70
,[ThaliCore] VirtualSocket.deinit vsID:70 [4, 10, 16, 26, 59, 68, 69]
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:E07BFCF8-CD88-4962-AAA9-802C74BFD5C1:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "E07BFCF8-CD88-4962-AAA9-802C74BFD5C1", generation: 0)
,[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:64857
[ThaliCore] Session.disconnect() peer:E07BFCF8-CD88-4962-AAA9-802C74BFD5C1:0
[ThaliCore] TCPListener.socketDidDisc,onnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:68
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:68
[ThaliCore] VirtualSocket.deinit vsID:68 [4, 10, 16, 26, 59, 69]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] Session.deinit peer:E07BFCF8-CD88-4962-AAA9-802C74BFD5C1:0
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "E07BFCF8-CD88-4962-AAA9-802C74BFD5C1", generation: 0) relay removed
[ThaliCore] BrowserRelay.deinit
[ThaliCore] Session.startOutputStream(with:) peer:89459276-EC79-4CF3-8003-7EC0263C9F17:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:89459276-EC79-4CF3-8003-7EC0263C9F17:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:71 [4, 10, 16, 26, 59, 69, 71]
,2017-08-01 11:34:30 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"E07BFCF8-CD88-4962-AAA9-802C74BFD5C1","generation":0}]'
,2017-08-01 11:34:30 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"E07BFCF8-CD88-4962-AAA9-802C74BFD5C1","generation":0}'
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-08-01 11:34:30 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"E07BFCF8-CD88-4962-AAA9-802C74BFD5C1","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-08-01 11:34:30 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"E07BFCF8-CD88-4962-AAA9-802C74BFD5C1","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-08-01 11:34:30 - WARN thaliNotificationClient: 'peer is not available'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:69
[ThaliCore] VirtualSocket.closeStreams() vsID:69
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:69
[ThaliCore] VirtualSocket.deinit vsID:69 [4, 10, 16, 26, 59, 71]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:wi,thError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:638674DE-1248-425B-BB3C-67ABE1127ADB
[ThaliCore] Session.startOutputStream(with:) peer:638674DE-1248-425B-BB3C-67ABE1127ADB
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:72 [4, 10, 16, 26, 59, 71, 72]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-08-01 11:34:30 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  404 no_db_file'
,2017-08-01 11:34:30 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: no_db_file  and it caused us to complete'
,ok 868 error should be 'no_db_file'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:71
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:71
,[ThaliCore] VirtualSocket.deinit vsID:71 [4, 10, 16, 26, 59, 72]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:72
[ThaliCore] VirtualSocket.closeStreams() vsID:72
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:72
[ThaliCore] VirtualSocket.deinit vsID:72 [4, 10, 16, 26, 59]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:peer:didChange:) peer:68F79609-0A85-42F9-884E-51FBAC4E0541:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:68,F79609-0A85-42F9-884E-51FBAC4E0541:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "68F79609-0A85-42F9-884E-51FBAC4E0541", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,8F79609-0A85-42F9-884E-51FBAC4E0541", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "68F79609-0A85-42F9-884E-51FBAC4E0541", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:68F79609-0A85-42F9-884E-51FBAC4E0541:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:68F79609-0A85-42F9-884E-51FBAC4E0541:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:3C03286D-92EB-4924-A2C4-E042DE28FC9F:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "3C03286D-92EB-4924-A2C4-E042DE28FC9F", generation: 0)
2017-08-01 11:34:34 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"3C03286D-92EB-4924-A2C4-E042DE28FC9F","generation":0}]'
2017-08-01 11:34:34 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"3C03286D-92EB-4924-A2C4-E042DE28FC9F","generation":0}'
,2017-08-01 11:34:34 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"3C03286D-92EB-4924-A2C4-E042DE28FC9F","peerAvailable":false,"generation":null,"portNumber":null}'
2017-08-01 11:34:34 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"3C03286D-92EB-4924-A2C4-E042DE28FC9F","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-08-01 11:34:34 - WARN thaliNotificationClient: 'peer is not avai,lable'
,[ThaliCore] Session.session(_:peer:didChange:) peer:68F79609-0A85-42F9-884E-51FBAC4E0541:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:68,F79609-0A85-42F9-884E-51FBAC4E0541:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "68F79609-0A85-42F9-884E-51FBAC4E0541", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,8F79609-0A85-42F9-884E-51FBAC4E0541", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "68F79609-0A85-42F9-884E-51FBAC4E0541", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:68F79609-0A85-42F9-884E-51FBAC4E0541:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:68F79609-0A85-42F9-884E-51FBAC4E0541:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:68F79609-0A85-42F9-884E-51FBAC4E0541:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:68,F79609-0A85-42F9-884E-51FBAC4E0541:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "68F79609-0A85-42F9-884E-51FBAC4E0541", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,8F79609-0A85-42F9-884E-51FBAC4E0541", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "68F79609-0A85-42F9-884E-51FBAC4E0541", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:68F79609-0A85-42F9-884E-51FBAC4E0541:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:68F79609-0A85-42F9-884E-51FBAC4E0541:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:68F79609-0A85-42F9-884E-51FBAC4E0541:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:68,F79609-0A85-42F9-884E-51FBAC4E0541:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "68F79609-0A85-42F9-884E-51FBAC4E0541", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:68F79609,-0A85-42F9-884E-51FBAC4E0541 error: max retries exceeded
2017-08-01 11:34:40 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"19","error":"Connection could not be established","portNumber":null}'
,2017-08-01 11:34:40 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for E07BFCF8-CD88-4962-AAA9-802C74BFD5C1 (syncValue: 20)'
2017-08-01 11:34:40 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPe,er(_:syncValue:retryCount:completion:) Peer(uuid: "E07BFCF8-CD88-4962-AAA9-802C74BFD5C1", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E07BFCF8-CD88-4962-AAA9-802C74BFD5C1", generation: 0)
,[ThaliCore] Session.deinit peer:68F79609-0A85-42F9-884E-51FBAC4E0541:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-08-01 11:34:40 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"20","error":"Peer is unavailable","portNumber":null}'
2017-08-,01 11:34:40 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 3C03286D-92EB-4924-A2C4-E042DE28FC9F (syncValue: 21)'
2017-08-01 11:34:40 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPeer(_:syn,cValue:retryCount:completion:) Peer(uuid: "3C03286D-92EB-4924-A2C4-E042DE28FC9F", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3C03286D-92EB-4924-A2C4-E042DE28FC9F", generatio,n: 0)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:67DF26D7-0391-46BF-9A8E-7C486EF20B1D
[ThaliCore] Session.startOutputStream(with:) peer:67DF26D7-0391-46BF-9A8E-7C486EF20B1D
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7,3 [4, 10, 16, 26, 59, 73]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=36 "Operation now in progress" UserInfo={NSLocalizedDescription=Operation now in progress, NSLocalizedFailureReason=Error, in connect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:73
[ThaliCore] VirtualSocket.closeStreams() vsID:73
[ThaliCore] Adver,tiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:73
[ThaliCore] VirtualSocket.deinit vsID:73 [4, 10, 16, 26, 59]
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-08-01 11:34:40 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"21","error":"Peer is unavailable","portNumber":null}'
2017-08-,01 11:34:40 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for FF233C22-60DB-4B1D-B6ED-7DC1227E0497 (syncValue: 22)'
2017-08-01 11:34:40 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPeer(_:syn,cValue:retryCount:completion:) Peer(uuid: "FF233C22-60DB-4B1D-B6ED-7DC1227E0497", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FF233C22-60DB-4B1D-B6ED-7DC1227E0497", generatio,n: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-08-01 11:34:40 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"22","error":"Peer is unavailable","portNumber":null}'
2017-08-,01 11:34:40 - DEBUG thaliPeerPoolDefault: 'Got err   Connection could not be established'
2017-08-01 11:34:40 - DEBUG thaliPeerPoolDefault: 'Got err   Peer is unavailable'
2017-08-01 11:34:40 - DEBUG thaliPeerPoolDefault: 'Got err   Peer is unavailable',
2017-08-01 11:34:40 - DEBUG thaliPeerPoolDefault: 'Got err   Peer is unavailable'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:67DF26D7-0391-46BF-9A8E-7C486EF20B1D
[ThaliCore] Session.startOutputStream(with:) peer:67DF26D7-0391-46BF-9A8E-7C486EF20B1D
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7,4 [4, 10, 16, 26, 59, 74]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedDescription=Connection refused, NSLocalizedFailureReason=Error in connect() ,function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:74
[ThaliCore] VirtualSocket.closeStreams() vsID:74
[ThaliCore] AdvertiserRelay.did,CloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:74
[ThaliCore] VirtualSocket.deinit vsID:74 [4, 10, 16, 26, 59]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:67DF26D7-0391-46BF-9A8E-7C486EF20B1D
[ThaliCore] Session.startOutputStream(with:) peer:67DF26D7-0391-46BF-9A8E-7C486EF20B1D
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7,5 [4, 10, 16, 26, 59, 75]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=36 "Operation now in progress" UserInfo={NS,LocalizedDescription=Operation now in progress, NSLocalizedFailureReason=Error in connect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socke,t vsID:75
[ThaliCore] VirtualSocket.closeStreams() vsID:75
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:75
[ThaliCore] VirtualSocket.deinit vsID:75 [4, 10, 16, 26, 59,],
,[ThaliCore] Session.session(_:peer:didChange:) peer:67DF26D7-0391-46BF-9A8E-7C486EF20B1D state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "94315540-88C1-4914-B493-B105D908F8AF", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:67DF26D7-0391-46BF-9A8E-7C486EF20B1D
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:67DF26D7-0391-46BF-9A8E-7C486EF20B1D
,not ok 869 failed with TimeoutError
  ---
    operator: fail
  ...
,# teardown
,2017-08-01 11:39:26 - ERROR CoordinatedClient: 'test failed, name: 'Coordinated replication action test - should throw error when wrong remote db name is provided''
2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll ca,n close even when connections open'
2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll with promise'
2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing, a non open server with eatNotRunning set to false'
2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll works even with a server that is not listening yet witheatNotRunning set to true'
2017-08-01 11:39:26 - INFO Coord,inatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on a single db change'
2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of multiple onCheckpointReached handlers on a single db change,',
2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval'
2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER r,esult: skipped - Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval'
2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultDirectory'
2017-08-01 11:39:26 -, INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultAdapter'
2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueue and run in order'
2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: ,passed - enqueueAtTop and run backwards'
2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - mix enqueue and enqueueAtTop'
2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - queues handled independe,n,tly'
2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueued function are always executed asynchronously'
2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - exceptions in the executor are proper,ly handled'
2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - basic'
2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - another'
2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER resul,t: skipped - skip'
2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - another skip'
2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox spy'
2017-08-01 11:39:26 - INFO Coordinate,dClient: '***TEST_LOGGER result: passed - test sinon sansbox stub'
2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub override'
2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: pas,s,ed - test sinon sansbox mock'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox restore after test end'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can pass data in setup'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Correctly parses/stringifies USN'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerLost calls jxcore'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerDiscovered calls jxcore'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopListeningForAdvertisements'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startListeningForAdvertisements twice is NOT an error'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling stopListeningForAdvertisements without calling start is NOT an error'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopUpdateAdvertisingAndListening'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startUpdateAdvertisingAndListening twice is NOT an error'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call stopUpdateAdvertisingAndListening twice without start and it is not an error'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChange is called'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can connect to a remote peer'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data via parallel connections'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data securely'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift large amounts of data'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We do not emit peerAvailabilityChanged events until one of the start methods is called'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Test updating advertising and parallel data transfer'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - discoveryAdvertisingStateUpdateNonTCP is called'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - cannot call connect when start listening for advertisements is not active'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Get error when trying to double connect to a peer on Android'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect when start listening for advertisements is not active'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with illegal peerID'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiConnect properly fails on legal but non-existent peerID'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with invalid syncValue'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call disconnect with invalid peer id'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - disconnect doesn't fail on plausible but bogus peer ID'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Get same port when trying to connect multiple times on iOS'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - initial peer discovery'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 1'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 2'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - check latest peer discovery'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Set up for no peer discovery test'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - no peer discovery'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling createNativeListener directly rejects'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits incomingConnectionState'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits routerPortConnectionFailed'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server connections all up'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming stream cleans outgoing socket'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming connection cleans outgoing socket'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing outgoing socket cleans associated mux stream'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing the whole server cleans everything up'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - we can get a ton of connections and data through and still clean up the server completely'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - simulate mux failure, make sure everything is cleaned up'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - timing out the incoming connection cleans everything up'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can create servers manager'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling stop without start causes error'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can start/stop servers manager'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - starting twice resolves with listening port'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminateIncomingConnection will terminate a connection'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminate an Outgoing connection'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single local http request'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single coordinated request ios native'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Multiple local http requests'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Multiple coordinated request ios native'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startListeningForAdvertisements should fail if start not called'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if start not called'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - should be able to call #stopListeningForAdvertisements many times'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startListeningForAdvertisements many times'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startUpdateAdvertisingAndListening many times'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopAdvertisingAndListening many times'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get the network status before starting'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - error returned with bad router'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - all services are started when we call start'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - TCP Servers Manager should be null when we call start on iOS'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - all services are stopped when we call stop'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure terminateConnection is properly hooked up'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure terminateConnection is return error if we get called on iOS'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure terminateListener is properly hooked up'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure terminateListener is return error if we get called on iOS'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure we actually call kill connections properly'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire failedNativeConnection event when we get failedConnection from multiConnectConnection'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure bad PSK connections fail'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - peer changes handled from a queue'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - relaying discoveryAdvertisingStateUpdateNonTCP'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - we successfully receive and replay discoveryAdvertisingStateUpdate'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - can do HTTP requests between peers'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - can still do HTTP requests between peers with coordinator'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - calls correct starts when network changes'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test to coordinate connection cut'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can do HTTP requests after connections are cut'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - will fail bad PSK connection between peers'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We provide notification when a listener dies and we recreate it'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startListeningForAdvertisements should fail if start not called'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if start not called'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopListeningForAdvertisements many times'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startListeningForAdvertisements many times'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startUpdateAdvertisingAndListening many times'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopAdvertisingAndListening many times'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #start - Causing native or wifi to fail will cause a promise reject '
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #start should fail if called twice in a row'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - does not emit duplicate discoveryAdvertisingStateUpdate'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - does not send duplicate availability changes'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get the network status'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer added/removed to/from cache (native)'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer added/removed to/from cache (wifi)'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - new peer is cached'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - native available - peer with same port and different generation is cached (BLUETOOTH)'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - peer with greater generation is cached (MPCF)'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - peer with same or older generation is ignored (MPCF)'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native unavailable - new peer is ignored'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native unavailable - cached peer is removed'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - networkChanged - fires peerAvailabilityChanged event for wifi peers'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiconnect failure - new peer is ignored (MPCF)'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - newAddressPort field (TCP_NATIVE)'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - newAddressPort field (BLUETOOTH)'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - newAddressPort field (MPCF)'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - error when peer has not been discovered yet'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - returns discovered cached wifi peer'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #disconnect fails on wifi peers'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #disconnect delegates native peers to the native wrapper'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes emitted correctly'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes not emitted in started state'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes not emitted in stopped state'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We properly fire peer unavailable and then available when connection fails on Android'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We properly fire peer unavailable and then available when connection fails on iOS'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - does not fire duplicate events after peer listener recreation'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #stop should change peers'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - peer should be found once after listening and discovery started'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get data from all participants'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - test for data corruption'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - test getters'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - start and kill'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - double start'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - start after kill'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - make sure ids are unique'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - check that forever agent can be destroyed'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test PeerDictionary basic functionality'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test PeerDictionary with multiple entries.'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - RESOLVED entries are removed before WAITING state entry.'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - WAITING entries are removed before CONTROLLED_BY_POOL state entry.'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - When CONTROLLED_BY_POOL entry is removed and kill is called.'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - single action'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - multiple actions'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - PSK Pool works'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - stop'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure that start verifies queue length'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - bad enqueues'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - do not allow same object type'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure we catch kill and dequeue'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure that stop removes all actions'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We reject unrecognized connection type'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We reject unrecognized action type'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - One action on bluetooth'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Two notification actions'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - replicateThroughProblems'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Replication goes first'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - wifi allows many parallel non-replication actions'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - wifi allows no more than 2 simultaneous replication actions for same peerID'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Client to server request coordinated'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test BEACONS_RETRIEVED_AND_PARSED locally'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Test HTTP_BAD_RESPONSE locally'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test NETWORK_PROBLEM locally'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Action fails when getPeerHostInfo fails'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the start two times'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill before calling the start'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill immediately after the start'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill while waiting a response from the server'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test to exceed the max content size locally'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Close the server socket while the client is waiting a response from the server. Local test.'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Close the client socket while the client is waiting a response from the server. Local test.'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons bad args'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons empty keys to notify'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons multiple keys to notify'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid expiration in beaconStreamWithPreAmble'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons expiration out of range lower'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons expiration out of range lower'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons no beacons returns null'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback fails decrypt'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #parseBeacons addressBookCallback returns no matches'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns spurious match'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns public key'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskIdentityField'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskSecret'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskSecrets'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generateBeaconStreamAndSecrets'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Add two Peers.'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - TCP_NATIVE peer loses DNS'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Received beacons with no values for us'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Notification action killed with a superseded'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Resolves an action locally'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Emits error event when peerPool.enqueue throws'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Resolves an action locally using ThaliPeerPoolDefault'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Action fails because of a bad hostname.'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - hostaddress is removed when the action is running. '
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - notificationClient does not retry action with BAD_PEER resolution'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - notification client correctly handles peer availability changes of the same peer'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Client to server request locally'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache clean and expiration'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache getSecret and getPublic'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache multiple entries'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Start and stop ThaliNotificationServer'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass an empty array to ThaliNotificationServer.start'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass a string to ThaliNotificationServer.start'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass an empty parameter to ThaliNotificationServer.start'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeacons'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeacons (no keys)'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeaconsbefore calling start'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure peerDictionaryKey is reasonable'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure start works'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure stop works'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Emits error event when peerPool.enqueue throws'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Simple peer event'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Coordinated pull replication from notification test'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server is not there'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server accepts & closes connection'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server always returns 500'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server always returns 401'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server always returns 403'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure docs replicate with remote db with same name as local db'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure docs replicate with remote db with different name than local db'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Do nothing and make sure we time out'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Do something and make sure we time out'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Start replicating and then catch error when server goes'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure clone works'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Coordinated replication action test - each device has the same local db name'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Coordinated replication action test - each device has different local db name'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: failed - Coordinated replication action test - should throw error when wrong remote db name is provided, error: 'Error: test failed, name: 'Coordinated replication action test - should t,hrow error when wrong remote db name is provided'', stack: 'CoordinatedClient.prototype._processEvent/</</endHandler/<@/private/var/containers/Bundle/Application/BF341FD4-5CD1-49B1-AA89-1A7C118CC8E9/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:463:22,
tryCatcher@/private/var/containers/Bundle/Application/BF341FD4-5CD1-49B1-AA89-1A7C118CC8E9/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/util.js:16:16
module.exports/Promise.prototype._settlePromiseFromHandler@/private/var/containers/Bundle/A,pplication/BF341FD4-5CD1-49B1-AA89-1A7C118CC8E9/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:510:13
module.exports/Promise.prototype._settlePromise@/private/var/containers/Bundle/Application/BF341FD4-5CD1-49B1-AA89-1A7C118CC8E9/Th,aliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:567:13
module.exports/Promise.prototype._settlePromise0@/private/var/containers/Bundle/Application/BF341FD4-5CD1-49B1-AA89-1A7C118CC8E9/ThaliTest.app/www/jxcore/node_modules/bluebird/js/re,lease/promise.js:612:5
module.exports/Promise.prototype._settlePromises@/private/var/containers/Bundle/Application/BF341FD4-5CD1-49B1-AA89-1A7C118CC8E9/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:691:13''
2017-08-01 11:39:26 - ER,ROR CoordinatedClient: 'failed to run unit tests, platformName: 'ios''
,2017-08-01 11:39:26 - DEBUG CoordinatedClient: 'all tests completed'
,2017-08-01 11:41:26 - DEBUG CoordinatedClient: 'test client disconnected'
2017-08-01 11:41:26 - DEBUG CoordinatedClient: 'test client failed'
2017-08-01 11:41:26 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: TimeoutError: timeout exceeded, ,event: 'run_Coordinated replication action test - should throw error when wrong remote db name is provided_finished', test: 'Coordinated replication action test - should throw error when wrong remote db name is provided'', stack: 'CoordinatedClient.prototy,pe._customError@/private/var/containers/Bundle/Application/BF341FD4-5CD1-49B1-AA89-1A7C118CC8E9/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:292:27
Emitter.prototype.emit@/private/var/containers/Bundle/Application/BF341FD4-5CD1-49B1-AA89-1A7C118CC8E9,/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7
Socket.prototype.onevent@/private/var/containers/Bundle/Application/BF341FD4-5CD1-49B1-AA89-1A7C118CC8E9/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:263:5
S,o,cket.prototype.onpacket@/private/var/containers/Bundle/Application/BF341FD4-5CD1-49B1-AA89-1A7C118CC8E9/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:221:7
module.exports/<@/private/var/containers/Bundle/Application/BF341FD4-5CD1-49,B1-AA89-1A7C118CC8E9/ThaliTest.app/www/jxcore/node_modules/component-bind/index.js:21:12
Emitter.prototype.emit@/private/var/containers/Bundle/Application/BF341FD4-5CD1-49B1-AA89-1A7C118CC8E9/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.j,s:131:7''
2017-08-01 11:41:26 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'

```
