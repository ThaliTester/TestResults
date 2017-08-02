#### Test 113351851520d16b_iOS_Iphone6sPlus-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/113351851520d16b/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6s Plus 'Iphone6sPlus-1' (f70cda60583ea0f895d05ea355cd125983c27594) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/E108E38C-356B-4143-9F42-55405A7ABC8C/fruitstrap-lldb-prep-cmds-f70cda60583ea0f895d05ea355cd125983c27594'
,Executing commands in '/tmp/E108E38C-356B-4143-9F42-55405A7ABC8C/fruitstrap-lldb-prep-cmds-f70cda60583ea0f895d05ea355cd125983c27594'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/113351851520d16b/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/113351851520d16b/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/40D065A8-D634-4A4D-BFB3-1330C4840FF5/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56962"
,(lldb)     command script import "/tmp/E108E38C-356B-4143-9F42-55405A7ABC8C/fruitstrap_f70cda60583ea0f895d05ea355cd125983c27594.py"
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
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-08-02 13:32:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-02 13:32:11 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-02 13:32:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:32:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:32:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:32:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:32:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
,AppContextTests.test_didEnterForeground finished
,AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
AppContextTests.test_esonValue finished
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "6C003A74-D278-468D-9272-893AEE9170EC", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:6C003A74-D278-468D-9272-893AEE9170EC
Optional(true)
Optional(false)
App,ContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:6CB4DD4E-E0BB-4511-A19A-086CD4AF1F2E
[ThaliCore] Browser.st,artListening
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:7F8142F2-F5C,7-4778-95F2-67B47D597F6A
[ThaliCore] Browser.startListening
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "D63ABDD0-22AE-4195-AA91-8FE9A90DCBF7", generation: 0)
[ThaliCore] Advertiser.startAdvertising ,with peerID:D63ABDD0-22AE-4195-AA91-8FE9A90DCBF7
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D63ABDD0-22AE-4195-AA91-8FE9A90DCBF7:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D63ABDD0-22AE-4195-AA91-8FE9A90DCBF7", generation: 0)
,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
AppContextTests.test_connectReturnValueCo,rrect finished
AppContextTests finished
All tests finished
All tests finished
,2017-08-02 13:32:13 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
Number of passed tests:  13
Number of failed tests:  0
,Number of ignored tests:  0
Total duration:  1.604707062244415
,2017-08-02 13:32:13 - DEBUG UnitTest_app: 'My device name is: 'Apple-Iphone6sPlus-1''
2017-08-02 13:32:13 - WARN testUtils: 'myNameCallback not set!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:D63ABDD0-22AE-4195-AA91-8FE9A90DCBF7:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "D63ABDD0-22AE-4195-AA91-8FE9A90DCBF7", generation: 0)
,2017-08-02 13:32:14 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-08-02 13:32:14 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/40D065A8-D634-4A4D-BFB3-1330C4840FF5/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-08-02 13:32:14 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/40D065A8-D634-4A4D-BFB3-1330C4840FF5/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-08-02 13:32:15 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/40D065A8-D634-4A4D-BFB3-1330C4840FF5/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-08-02 13:32:15 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/40D065A8-D634-4A4D-BFB3-1330C4840FF5/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-08-02 13:32:15 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/40D065A8-D634-4A4D-BFB3-1330C4840FF5/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-08-02 13:32:15 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/40D065A8-D634-4A4D-BFB3-1330C4840FF5/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-08-02 13:32:15 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/40D065A8-D634-4A4D-BFB3-1330C4840FF5/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-08-02 13:32:15 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/40D065A8-D634-4A4D-BFB3-1330C4840FF5/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-08-02 13:32:15 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/40D065A8-D634-4A4D-BFB3-1330C4840FF5/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-08-02 13:32:15 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/40D065A8-D634-4A4D-BFB3-1330C4840FF5/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-08-02 13:32:15 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/40D065A8-D634-4A4D-BFB3-1330C4840FF5/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-08-02 13:32:15 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/40D065A8-D634-4A4D-BFB3-1330C4840FF5/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-08-02 13:32:15 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/40D065A8-D634-4A4D-BFB3-1330C4840FF5/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-08-02 13:32:15 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/40D065A8-D634-4A4D-BFB3-1330C4840FF5/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-08-02 13:32:15 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/40D065A8-D634-4A4D-BFB3-1330C4840FF5/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-08-02 13:32:15 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/40D065A8-D634-4A4D-BFB3-1330C4840FF5/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-08-02 13:32:15 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/40D065A8-D634-4A4D-BFB3-1330C4840FF5/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-08-02 13:32:15 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/40D065A8-D634-4A4D-BFB3-1330C4840FF5/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-08-02 13:32:15 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/40D065A8-D634-4A4D-BFB3-1330C4840FF5/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-08-02 13:32:15 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/40D065A8-D634-4A4D-BFB3-1330C4840FF5/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-08-02 13:32:15 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/40D065A8-D634-4A4D-BFB3-1330C4840FF5/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-08-02 13:32:15 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/40D065A8-D634-4A4D-BFB3-1330C4840FF5/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-08-02 13:32:15 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/40D065A8-D634-4A4D-BFB3-1330C4840FF5/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-08-02 13:32:15 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/40D065A8-D634-4A4D-BFB3-1330C4840FF5/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-08-02 13:32:15 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/40D065A8-D634-4A4D-BFB3-1330C4840FF5/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-08-02 13:32:16 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/40D065A8-D634-4A4D-BFB3-1330C4840FF5/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-08-02 13:32:16 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/40D065A8-D634-4A4D-BFB3-1330C4840FF5/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-08-02 13:32:16 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/40D065A8-D634-4A4D-BFB3-1330C4840FF5/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-08-02 13:32:16 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/40D065A8-D634-4A4D-BFB3-1330C4840FF5/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-08-02 13:32:16 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/40D065A8-D634-4A4D-BFB3-1330C4840FF5/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-08-02 13:32:16 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/40D065A8-D634-4A4D-BFB3-1330C4840FF5/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-08-02 13:32:16 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/40D065A8-D634-4A4D-BFB3-1330C4840FF5/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-08-02 13:32:16 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/40D065A8-D634-4A4D-BFB3-1330C4840FF5/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-08-02 13:32:16 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/40D065A8-D634-4A4D-BFB3-1330C4840FF5/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-08-02 13:32:16 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/40D065A8-D634-4A4D-BFB3-1330C4840FF5/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-08-02 13:32:16 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/40D065A8-D634-4A4D-BFB3-1330C4840FF5/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-08-02 13:32:16 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/40D065A8-D634-4A4D-BFB3-1330C4840FF5/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-08-02 13:32:16 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/40D065A8-D634-4A4D-BFB3-1330C4840FF5/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-08-02 13:32:16 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/40D065A8-D634-4A4D-BFB3-1330C4840FF5/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-08-02 13:32:16 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/40D065A8-D634-4A4D-BFB3-1330C4840FF5/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-08-02 13:32:16 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-08-02 13:32:16 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
,2017-08-02 13:32:16 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
,# setup
,# closeAll can close even when connections open
,2017-08-02 13:34:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 1 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll with promise
,2017-08-02 13:34:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 2 not possible to connect to the server anymore
# teardown
,# setup
,# closeAll properly throws when closing a non open server with eatNotRunning set to false
,2017-08-02 13:34:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
# teardown
,# setup
,# closeAll works even with a server that is not listening yet witheatNotRunning set to true
,2017-08-02 13:34:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
,# setup
,# Call of onCheckpointReached handler on a single db change
,2017-08-02 13:34:31 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on a single db change''
,# teardown
,# setup
,# Call of multiple onCheckpointReached handlers on a single db change
,2017-08-02 13:34:32 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of multiple onCheckpointReached handlers on a single db change''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
,2017-08-02 13:34:33 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
,2017-08-02 13:34:34 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''
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
,ok 16 firstPromise result
,ok 17 firstPromise testValue
,ok 18 secondPromise setTimeout
,ok 19 secondPromise result
,ok 20 secondPromise testValue
,ok 21 thirdPromise in promise
,ok 22 thirdPromise result
,ok 23 thirdPromise testValue
,# teardown
,# setup
,# enqueueAtTop and run backwards
,ok 24 thirdPromise - first to run
ok 25 thirdPromise - in resolve
,ok 26 secondPromise - second to run
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
,2017-08-02 13:34:51 - DEBUG CoordinatedClient: 'test was skipped, name: 'skip''
,# teardown
,# setup
,# another skip
,2017-08-02 13:34:53 - DEBUG CoordinatedClient: 'test was skipped, name: 'another skip''
,# teardown
,# setup
,# test sinon sansbox spy
,2017-08-02 13:34:53 - DEBUG testTests: 'test spy method for global sinon sansbox'
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
,ok 58 throws if usn has invalid prefix
ok 59 throws if usn has invalid identifier format
ok 60 throws if usn has invalid generation
ok 61 correctly stringifies peer
,# teardown
,# setup
,# onPeerLost calls jxcore
,2017-08-02 13:34:57 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
,# teardown
,2017-08-02 13:34:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-02 13:34:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-02 13:34:57 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:34:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-02 13:34:57 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-02 13:34:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-02 13:34:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-02 13:34:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# onPeerDiscovered calls jxcore
,2017-08-02 13:34:58 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
,# teardown
,2017-08-02 13:34:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-02 13:34:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-02 13:34:58 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:34:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-02 13:34:58 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-02 13:34:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-02 13:34:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-02 13:34:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopListeningForAdvertisements
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:11E5B1E1-DE70-4086-B8B1-948EF2DE9FA2
[ThaliCore] Browser.startListening
2017-08-02 13:34:58 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-02 13:34:58 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-08-02 13:34:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 62 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvert,isements()
[ThaliCore] Browser.stopListening()
2017-08-02 13:34:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:34:58 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
ok 63 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:34:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:34:58 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:34:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-08-02 13:34:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:34:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-02 13:34:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-02 13:34:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:34:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:34:58 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:34:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:34:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:34:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startListeningForAdvertisements twice is NOT an error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:716DB509-B1EF-477D-9738-BF63CD834202
,[ThaliCore] Browser.startListening
,2017-08-02 13:34:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-02 13:34:58 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-02 13:34:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 64 Can call startListeningForAdvertisements without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-08-02 13:34:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-02 13:34:58 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-08-02 13:34:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 65 Can call startListeningForAdvertisements twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-02 13:34:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02, 13:34:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:34:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discovery,Active":false,"advertisingActive":false}'
2017-08-02 13:34:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:34:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-02 13:34:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-02 13:34:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:34:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:34:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:34:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:34:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:34:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling stopListeningForAdvertisements without calling start is NOT an error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:35:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:35:00 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 66 Can call stopListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:35:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:35:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 67 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:35:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:35:00 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:35:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-08-02 13:35:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:35:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-02 13:35:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-02 13:35:00 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:35:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-02 13:35:00 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-02 13:35:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-02 13:35:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-02 13:35:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopUpdateAdvertisingAndListening
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "863DC54F-0B4E-4C13-BF56-E4B67443C335", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:863DC54F-0B4E-4C13-BF56-E4B67443C335
,2017-08-02 13:35:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-02 13:35:03 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:35:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 68 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:863DC54F-0B4E-4C13-BF56-E4B67443C335
2017-08-02 13:35:03 ,- DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:35:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 69 Can call ,s,topAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-02 13:35:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:35:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:35:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:35:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:35:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-02 13:35:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-02 13:35:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:35:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:35:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:35:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:35:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:35:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startUpdateAdvertisingAndListening twice is NOT an error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "B2075C3A-DDD6-45AA-8FF7-872904D17A95", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:B2075C3A-DDD6-45AA-8FF7-872904D17A95
,2017-08-02 13:35:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-02 13:35:04 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:35:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 70 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "B2075C3A-DDD6-45AA-8FF7-872904D17A95", generation: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:B2075C3A-DDD6-45AA-8FF7-872904D17A95
2017-08-02 1,3:35:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-02 13:35:04 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:35:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 71 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-02 13:35:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-08-02 13:35:05 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-08-02 13:35:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:B2075C3A-DDD6-45AA-8FF7-872904D17A95
,[ThaliCore] Advertiser.stopAdvertising() peerID:B2075C3A-DDD6-45AA-8FF7-872904D17A95
2017-08-02 13:35:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:35:05 - ,INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:35:05 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-02 13:35:05 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-02 13:35:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:35:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:35:05 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-08-02 13:35:05 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:35:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:35:05 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:35:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:35:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 72 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:35:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive",:false}'
2017-08-02 13:35:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 73 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:35:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:35:06 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:35:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-08-02 13:35:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:35:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-02 13:35:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-02 13:35:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:35:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-02 13:35:06 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-02 13:35:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-02 13:35:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-02 13:35:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peerAvailabilityChange is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "15D5145B-E249-4A5F-B306-CF7DADB80079", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:15D5145B-E249-4A5F-B306-CF7DADB80079
2017-08-02 1,3:35:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-08-02 13:35:12 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-08-02 13:35:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 74 Can call startUpdateAdvertisingAndListeningwithout error
[ThaliCore] BrowserManager.startListeningForAdv,ertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:61A63DF9-CE6F-4C73-9A2D-B429827CD799
[ThaliCore] Browser.startListening
2017-08-02 13:35:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryA,ctive":true,"advertisingActive":true}'
2017-08-02 13:35:12 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","sta,r,tArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-02 13:35:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 75 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1EECE896-6DA2-4ED3-9377-AA8EDCC67D79:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1EECE896-6DA2-4ED3-9377-AA8EDCC67D79", generation: 0)
,ok 76 peers must be an array
,ok 77 peers must not be zero-length
,ok 78 peer must have only peerIdentifier, peerAvailable and generation properties
,ok 79 peerIdentifier must be a string
,ok 80 generation must be a number
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:ED60016B-7091-44FC-9A9B-74EEA528D285:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "ED60016B-7091-44FC-9A9B-74EEA528D285", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:15D5145B-E249-4A5F-B306-CF7DADB80079:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "15D5145B-E249-4A5F-B306-CF7DADB80079", generation: 0)
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-02 13:35:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-02 13:35:14 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-08-02 13:35:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:15D5145B-E249-4A5F-B306-C,F7DADB80079
2017-08-02 13:35:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:35:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
,2017-08-02 13:35:14 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-02 13:35:14 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-02 13:35:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:35:14 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:35:14 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:35:14 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:35:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:35:14 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can connect to a remote peer
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "544E1963-72AB-4976-83C3-D98BB4166601", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:544E1963-72AB-4976-83C3-D98BB4166601
2017-08-02 13:35:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-02 13:35:19, - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkTy,pe":null}})'
2017-08-02 13:35:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 81 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[Thal,iCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:02CD7B60-D529-4BD1-84C7-064615D6C7E6
[ThaliCore] Browser.startListening
2017-08-02 13:35:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"adve,r,tisingActive":true}'
2017-08-02 13:35:19 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"rout,er":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:35:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 82 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:544E1963-72AB-4976-83C3-D98BB4166601:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "544E1963-72AB-4976-83C3-D98BB4166601", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7C550145-A750-4414-8AE2-913CC31E1F62:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7C550145-A750-4414-8AE2-913CC31E1F62", generation: 0)
2017-08-02 13:35:21 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"7C550145-A750-4414-8AE2-913CC31E1F62","generation":0}'
2017-08-02 13:35:21 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 7C550145-A750-4414-8AE2-913CC31E1F62, (syncValue: rFtOi8agqAmysbbzJuiXCeDADaVnWBVI)'
2017-08-02 13:35:21 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7C550145-A750-4414-8AE2-913CC31,E1F62", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7C550145-A750-4414-8AE2-913CC31E1F62", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected,:,) peer:7C550145-A750-4414-8AE2-913CC31E1F62:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:18EAED4C-36F9-42F4-85C3-9F97B529CE7D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "18EAED4C-36F9-42F4-85C3-9F97B529CE7D", generation: 0)
,2017-08-02 13:35:21 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"18EAED4C-36F9-42F4-85C3-9F97B529CE7D","generation":0}'
,2017-08-02 13:35:21 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-02 13:35:21 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B5E2CB85-18AA-4585-90E3-3FE0CFDA5F86
[ThaliCore] Advertiser: session connected Peer(uuid: "544E1963-72AB-4976-83C3-D98BB4166601", generation: 0)
[ThaliCore] Session.session(_:peer:didChange:) peer:B5E2CB85-18AA-4585-90E3-3FE0CFDA5F86 state: notConnected -> connecting
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B16DCEE6-EA4A-4C87-9E88-632FDE6C243A
[ThaliCore] Advertiser: session connected Peer(uuid: "544E1963-72AB-4976-83C3-D98BB4166601", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:B16DCEE6-EA4A-4C87-9E88-632FDE6C243A state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:7C550145-A750-4414-8AE2-913CC31E1F62:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:7C550145-A750-4414-8AE2-913CC31E1F62:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:7C550145-A750-4414-8AE2-913CC31E1F62:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "7C550145-A750-4414-8AE2-913CC31E1F62", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:65241
2017-08-02 13:35:23 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"rFtOi8agqAmysbbzJuiXCeDADaVnWBVI","error":null,"portN,umber":65241}'
2017-08-02 13:35:23 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'rFtOi8agqAmysbbzJuiXCeDADaVnWBVI', error: 'null', listeningPort: '65241''
,2017-08-02 13:35:23 - INFO testThaliMobileNative: ''
,ok 83 Must have listeningPort
,ok 84 listeningPort must be a number
,ok 85 listening port should not be 0
[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B5E2CB85-18AA-4585-90E3-3FE0CFDA5F86
,# teardown
,[ThaliCore] Session.session(_:peer:didChange:) peer:B5E2CB85-18AA-4585-90E3-3FE0CFDA5F86 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B16DCEE6-EA4A-4C87-9E88-632FDE6C243A
,[ThaliCore] Session.session(_:peer:didChange:) peer:B16DCEE6-EA4A-4C87-9E88-632FDE6C243A state: connecting -> connected
,2017-08-02 13:35:25 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-02 13:35:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-02 13:35:25 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:35:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:544E1963-72AB-4976-83C3-D98BB4166601
2017-08-02 13:35:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13,:,35:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:7C550145-A750-4414-8AE2-913CC31E1F62
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:65241
[ThaliCore] Session.disconnect() p,eer:7C550145-A750-4414-8AE2-913CC31E1F62:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:B5E2CB85-18AA-4585-90E3-3FE0CFDA5F86 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "544E1963-72AB-4976-83C3-D98BB4166601", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:B16DCEE6-EA4A-4C87-9E88-632FDE6C243A
[ThaliCore] Sessio,n.deinit peer:B16DCEE6-EA4A-4C87-9E88-632FDE6C243A
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:7C550145-A750-4414-8AE2-913CC31E1F62:0
,[ThaliCore] BrowserRelay.deinit
,2017-08-02 13:35:25 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-02 13:35:25 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-02 13:35:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:35:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:35:25 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:35:25 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:35:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
2017-08-02 13:35:25 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "03768CE9-40C2-463B-93B4-8F5364C40B1B", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:03768CE9-40C2-463B-93B4-8F5364C40B1B
,2017-08-02 13:35:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-02 13:35:26 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:35:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 86 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:AB616CAE-D6E1-4DAB-8830-7D71E9DE,20E9
[ThaliCore] Browser.startListening
2017-08-02 13:35:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-08-02 13:35:26 - INFO thaliMobile: 'Received state ({"discover,y,Active":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:35:26 - INFO thaliMobi,le: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 87 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7C550145-A750-4414-8AE2-913CC31E1F62:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7C550145-A750-4414-8AE2-913CC31E1F62", generation: 0)
2017-08-02 13:35:27 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"7C550145-A750-4414-8AE2-913CC31E1F62","generation":0}'
2017-08-02 13:35:27 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 7C550145-A750-4414-8AE2-913CC31E1F62, (syncValue: wXdUEwFKNYaEXdEc0UlJROzQ1lKkhqXb)'
2017-08-02 13:35:27 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7C550145-A750-4414-8AE2-913CC31,E1F62", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7C550145-A750-4414-8AE2-913CC31E1F62", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected,:,) peer:7C550145-A750-4414-8AE2-913CC31E1F62:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1E06C374-CB3C-4D19-9DBC-249F54A9464A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1E06C374-CB3C-4D19-9DBC-249F54A9464A", generation: 0)
,2017-08-02 13:35:27 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"1E06C374-CB3C-4D19-9DBC-249F54A9464A","generation":0}'
,2017-08-02 13:35:27 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-02 13:35:27 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F810FD1D-5AEA-463E-8C18-4DA0A132C00B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F810FD1D-5AEA-463E-8C18-4DA0A132C00B", generation: 0)
,2017-08-02 13:35:27 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"F810FD1D-5AEA-463E-8C18-4DA0A132C00B","generation":0}'
2017-08-02 13:35:27 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-02 13:35:27 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-02 13:35:27 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:03768CE9-40C2-463B-93B4-8F5364C40B1B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "03768CE9-40C2-463B-93B4-8F5364C40B1B", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:7C550145-A750-4414-8AE2-913CC31E1F62:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:7C,550145-A750-4414-8AE2-913CC31E1F62:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "7C550145-A750-4414-8AE2-913CC31E1F62", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,C550145-A750-4414-8AE2-913CC31E1F62", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7C550145-A750-4414-8AE2-913CC31E1F62", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:7C550145-A750-4414-8AE2-913CC31E1F62:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:7C550145-A750-4414-8AE2-913CC31E1F62:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:7C550145-A750-4414-8AE2-913CC31E1F62:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:7C,550145-A750-4414-8AE2-913CC31E1F62:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "7C550145-A750-4414-8AE2-913CC31E1F62", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,C550145-A750-4414-8AE2-913CC31E1F62", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7C550145-A750-4414-8AE2-913CC31E1F62", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:7C550145-A750-4414-8AE2-913CC31E1F62:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:7C550145-A750-4414-8AE2-913CC31E1F62:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:7C550145-A750-4414-8AE2-913CC31E1F62:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:7C,550145-A750-4414-8AE2-913CC31E1F62:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "7C550145-A750-4414-8AE2-913CC31E1F62", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,C550145-A750-4414-8AE2-913CC31E1F62", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7C550145-A750-4414-8AE2-913CC31E1F62", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:7C550145-A750-4414-8AE2-913CC31E1F62:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:7C550145-A750-4414-8AE2-913CC31E1F62:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:7C550145-A750-4414-8AE2-913CC31E1F62:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:7C550145-A750-4414-8AE2-913CC31E1F62:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "7C550145-A750-4414-8AE2-913CC31E1F62", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:7C550145,-A750-4414-8AE2-913CC31E1F62 error: max retries exceeded
2017-08-02 13:35:38 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"wXdUEwFKNYaEXdEc0UlJROzQ1lKkhqXb","error":"Connection could not be established","portNumber":null}'
2017-0,8-02 13:35:38 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'wXdUEwFKNYaEXdEc0UlJROzQ1lKkhqXb', error: 'Connection could not be established', listeningPort: '%s''
,2017-08-02 13:35:38 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-08-02 13:35:38 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 1E06C374-CB3C-4D19-9DBC-249F54A9464A (syncValue: fx2KqmV,kxN9XE4Zc0ylnP0DQ9Uol0GRv)'
2017-08-02 13:35:38 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1E06C374-CB3C-4D19-9DBC-249F54A9464A", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1E06C374-CB3C-4D19-9DBC-249F54A9464A", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1E06C374-CB3C,-4D19-9DBC-249F54A9464A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-08-02 13:35:38 - DEBUG thaliMobileNativeTestUtils: 'Already running tes,t,!'
,2017-08-02 13:35:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:7C550145-A750-4414-8AE2-913CC31E1F62:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:1E06C374-CB3C-4D19-9DBC-249F54A9464A:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:1E06C374-CB3C-4D19-9DBC-249F54A9464A:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:1E06C374-CB3C-4D19-9DBC-249F54A9464A:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "1E06C374-CB3C-4D19-9DBC-249F54A9464A", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:65255
2017-08-02 13:35:41 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"fx2KqmVkxN9XE4Zc0ylnP0DQ9Uol0GRv",,"error":null,"portNumber":65255}'
2017-08-02 13:35:41 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'fx2KqmVkxN9XE4Zc0ylnP0DQ9Uol0GRv', error: 'null', listeningPort: '65255''
,Connecting to the localhost:65255
,Connected to the localhost:65255
2017-08-02 13:35:41 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
2017-08-02 13:35:41 - DEBUG testThaliMobileNative: 'Client data flushed'
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCor,e] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:1E06C374-CB3C-4D19-9DBC-249F54A9464A:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:1E06C374-CB3C-4D19-9DBC-249F54A9464A:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1 [1]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 88 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pee,r})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams,() vsID:1
# teardown
,[ThaliCore] VirtualSocket exited RunLoop vsID:1
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket.deinit vsID:1 []
,2017-08-02 13:35:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-02 13:35:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-02 13:35:41 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:35:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:03768CE9-40C2-463B-93B4-8F5364C40B1B
2017-08-02 13:35:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13,:,35:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:1E06C374-CB3C-4D19-9DBC-249F54A9464A
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:65255
[ThaliCore] Session.disconnect() p,eer:1E06C374-CB3C-4D19-9DBC-249F54A9464A:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:1E06C374-CB3C-4D19-9DBC-249F54A9464A:0
[ThaliCore] BrowserRelay.deinit
,2017-08-02 13:35:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-02 13:35:41 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-02 13:35:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:35:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:35:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:35:41 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:35:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:35:41 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data via parallel connections
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "3AAC3A35-ACDB-4760-AEA7-5C08AC335BC3", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:3AAC3A35-ACDB-4760-AEA7-5C08AC335BC3
,2017-08-02 13:35:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-02 13:35:42 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:35:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 89 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:558E3B4F-2DA6-43D0-A21E-0A0FE136,66B3
[ThaliCore] Browser.startListening
2017-08-02 13:35:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-08-02 13:35:42 - INFO thaliMobile: 'Received state ({"discover,y,Active":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:35:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 90 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1E06C374-CB3C-4D19-9DBC-249F54A9464A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1E06C374-CB3C-4D19-9DBC-249F54A9464A", generation: 0)
2017-08-02 13:35:42 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"1E06C374-CB3C-4D19-9DBC-249F54A9464A","generation":0}'
2017-08-02 13:35:42 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 1E06C374-CB3C-4D19-9DBC-249F54A9464A, (syncValue: IrT87PG7b37y0kdGPqfZ48WRXEVgTVKP)'
2017-08-02 13:35:42 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1E06C374-CB3C-4D19-9DBC-249F54A,9464A", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1E06C374-CB3C-4D19-9DBC-249F54A9464A", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected,:) peer:1E06C374-CB3C-4D19-9DBC-249F54A9464A:0
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7C550145-A750-4414-8AE2-913CC31E1F62:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7C550145-A750-4414-8AE2-913CC31E1F62,", generation: 0)
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-08-02 13:35:42 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailabl,e":true,"peerIdentifier":"7C550145-A750-4414-8AE2-913CC31E1F62","generation":0}'
2017-08-02 13:35:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-02 13:35:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
[ThaliCore] ,Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F810FD1D-5AEA-463E-8C18-4DA0A132C00B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F810FD1D-5AEA-463E-8C18-4DA0A132C00B", generation: 0)
2017-08-02 13:35:42 - DEBUG thaliMobileN,a,tiveTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"F810FD1D-5AEA-463E-8C18-4DA0A132C00B","generation":0}'
,2017-08-02 13:35:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-02 13:35:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-02 13:35:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:F810FD1D-5AEA-463E-8C18-4DA0A132C00B:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "F810FD1D-5AEA-463E-8C18-4DA0A132C00B", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscov,eryInfo:) found peer:3437029A-5592-425D-88F9-94BA127A2E7C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3437029A-5592-425D-88F9-94BA127A2E7C", generation: 0)
2017-08-02 13:35:43 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAv,ailable":true,"peerIdentifier":"3437029A-5592-425D-88F9-94BA127A2E7C","generation":0}'
2017-08-02 13:35:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-02 13:35:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-0,8-02 13:35:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:AD28B5DB-E788-401E-9F57-0536CE0FD977:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "AD28B5DB-E788-401E-9F57-0536CE0FD977", generation: 0)
2017-08-02 13:35:43 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"AD28B5DB-E788-401E-9F57-0536CE0FD977","generation":0}'
2017-08-02 13:35:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-02 13:35:43 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-08-02 13:35:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-02 13:35:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3AAC3A35-ACDB-4760-AEA7-5C08AC335BC3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3AAC3A35-ACDB-4760-AEA7-5C08AC335BC3", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:7C550145-A750-4414-8AE2-913CC31E1F62:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "7C550145-A750-4414-8AE2-913CC31E1F62", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:1E06C374-CB3C-4D19-9DBC-249F54A9464A:0 state: notConnected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:1E06C374-CB3C-4D19-9DBC-249F54A9464A:0
,[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "1E06C374-CB3C-4D19-9DBC-249F54A9464A", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1E06C374-CB3C-4D19-9DBC-249F54A9464A", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1E06C374-CB3C-4D19-9DBC-249F54A9464A", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1E06C374-CB3C-4D19-9DBC-249F54A9464A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Session.deinit peer:1E06C374-CB3C-4D19-9DBC-249F54A9464A:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:1E06C374-CB3C-4D19-9DBC-249F54A9464A:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:1E,06C374-CB3C-4D19-9DBC-249F54A9464A:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "1E06C374-CB3C-4D19-9DBC-249F54A9464A", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1,E06C374-CB3C-4D19-9DBC-249F54A9464A", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1E06C374-CB3C-4D19-9DBC-249F54A9464A", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:1E06C374-CB3C-4D19-9DBC-249F54A9464A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:1E06C374-CB3C-4D19-9DBC-249F54A9464A:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:1E06C374-CB3C-4D19-9DBC-249F54A9464A:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:1E,06C374-CB3C-4D19-9DBC-249F54A9464A:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "1E06C374-CB3C-4D19-9DBC-249F54A9464A", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1,E06C374-CB3C-4D19-9DBC-249F54A9464A", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1E06C374-CB3C-4D19-9DBC-249F54A9464A", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:1E06C374-CB3C-4D19-9DBC-249F54A9464A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:1E06C374-CB3C-4D19-9DBC-249F54A9464A:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:1E06C374-CB3C-4D19-9DBC-249F54A9464A:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:1E,06C374-CB3C-4D19-9DBC-249F54A9464A:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "1E06C374-CB3C-4D19-9DBC-249F54A9464A", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:1E06C374,-CB3C-4D19-9DBC-249F54A9464A error: max retries exceeded
2017-08-02 13:35:53 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"IrT87PG7b37y0kdGPqfZ48WRXEVgTVKP","error":"Connection could not be established","portNumber":null}'
2017-0,8-02 13:35:53 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'IrT87PG7b37y0kdGPqfZ48WRXEVgTVKP', error: 'Connection could not be established', listeningPort: '%s''
,2017-08-02 13:35:53 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-08-02 13:35:53 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 3437029A-5592-425D-88F9-94BA127A2E7C (syncValue: LCqYUcF,SgzmlX9ZeLcUitZ4coqrVubnd)'
2017-08-02 13:35:53 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3437029A-5592-425D-88F9-94BA127A2E7C", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3437029A-5592-425D-88F9-94BA127A2E7C", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3437029A-5592-425D-88F9-94BA127A2E7C:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-08-02 13:35:53 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-02 13:35:53 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:1E06C374-CB3C-4D19-9DBC-249F54A9464A:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:1E06C374-CB3C-4D19-9DBC-249F54A9464A:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "1E06C374-CB3C-4D19-9DBC-249F54A9464A", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:3437029A-5592-425D-88F9-94BA127A2E7C:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:3437029A-5592-425D-88F9-94BA127A2E7C:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:3437029A-5592-425D-88F9-94BA127A2E7C:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "3437029A-5592-425D-88F9-94BA127A2E7C", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:65263
,2017-08-02 13:35:57 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"LCqYUcFSgzmlX9ZeLcUitZ4coqrVubnd","error":null,"portNumber":65263}'
,2017-08-02 13:35:57 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'LCqYUcFSgzmlX9ZeLcUitZ4coqrVubnd', error: 'null', listeningPort: '65263''
,Connecting to the localhost:65263
,Connecting to the localhost:65263
Connecting to the localhost:65263
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:3437029A-5592-425D-88F9-94BA127A2E7C:0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[Th,aliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:3437029A-5592-425D-88F9-94BA127A2E7C:0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCo,re] Session.startOutputStream(with:) peer:3437029A-5592-425D-88F9-94BA127A2E7C:0
,Connected to the localhost:65263
,Connected to the localhost:65263
,Connected to the localhost:65263
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3437029A-5592-425D-88F9-94BA127A2E7C:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2 [2]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3437029A-5592-425D-88F9-94BA127A2E7C:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3 [2, 3]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3437029A-5592-425D-88F9-94BA127A2E7C:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4 [2, 3, 4]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 91 correct string length
,2017-08-02 13:35:57 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 92 correct string length
,2017-08-02 13:35:57 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 93 correct string length
,2017-08-02 13:35:57 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,2017-08-02 13:35:57 - DEBUG testThaliMobileNative: 'Client data flushed'
2017-08-02 13:35:57 - DEBUG testThaliMobileNative: 'Client data flushed'
2017-08-02 13:35:57 - DEBUG testThaliMobileNative: 'Client data flushed'
,ok 94 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pee,r})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:2
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:2
,[ThaliCore] VirtualSocket.deinit vsID:2 [3, 4]
,ok 95 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pee,r})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams,() vsID:3
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,ok 96 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pee,r})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:4
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:4
[ThaliCore] VirtualSocket.deinit vsID:4 [3]
,# teardown
,2017-08-02 13:35:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-02 13:35:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-02 13:35:58 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:35:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:3AAC3A35-ACDB-4760-AEA7-5C08AC335BC3
,2017-08-02 13:35:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:35:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:3437029A-5592-425D-88F9-94BA127A2E7C
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:65263
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:3437029A-5592-425D-88F9-94BA127A2E7C:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:3437029A-5592-425D-88F9-94BA127A2E7C:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uui,d: "3437029A-5592-425D-88F9-94BA127A2E7C", generation: 0)
,2017-08-02 13:35:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-02 13:35:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-02 13:35:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:35:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:35:58 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:35:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:35:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:35:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-08-02 13:35:58 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"LCqYUcFSgzmlX9ZeLcUitZ4coqrVubnd","error":"Session disconnected","portNumber":null}'
,[ThaliCore] Session.deinit peer:3437029A-5592-425D-88F9-94BA127A2E7C:0
,# Can shift data securely
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "35268274-9198-49CF-822E-A7FA7B1EE03C", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:35268274-9198-49CF-822E-A7FA7B1EE03C
,2017-08-02 13:35:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-02 13:35:58 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:35:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 97 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:2DEA6E48-F596-4C5D-9716-66E488CE4075
[ThaliCore] Browser.startListening
2017-08-02 13:35:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,",advertisingActive":true}'
2017-08-02 13:35:58 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:35:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 98 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3437029A-5592-425D-88F9-94BA127A2E7C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3437029A-5592-425D-88F9-94BA127A2E7C", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:AD28B5DB-E788-401E-9F57-0536CE0FD977:0
2017-08-02 13:35:59 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"3437029A-5592-425D-88F9-94BA127A2E,7C","generation":0}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "AD28B5DB-E788-401E-9F57-0536CE0FD977", generation: 0)
2017-08-02 13:35:59 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 3437029A-5592-425D-88F9-94BA127A2E7C (syncValue: BeiexaEq9kT35ixqoscZAUCjdsyeFpRU)'
,2017-08-02 13:35:59 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3437029A-5592-425D-88F9-94BA127A2E7C", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3437029A-5592-425D-88F9-94BA127A2E7C", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3437029A-5592-425D-88F9-94BA127A2E7C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
2017-08-02 13:35:59 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"AD28B5DB-E788-401E-9F57-0536CE0FD977","generation":0}'
2017-08-02 13:35:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-02 13:35:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:35268274-9198-49CF-822E-A7FA7B1EE03C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "35268274-9198-49CF-822E-A7FA7B1EE03C", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6133E365-15A1-4D8C-9D13-580E318DED29:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6133E365-15A1-4D8C-9D13-580E318DED29", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2A2FAD16-B69B-48BB-8217-693632C78C14:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2A2FAD16-B69B-48BB-8217-693632C78C14", generation: 0)
,2017-08-02 13:35:59 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"6133E365-15A1-4D8C-9D13-580E318DED29","generation":0}'
,2017-08-02 13:35:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-02 13:35:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-02 13:35:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-02 13:35:59 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"2A2FAD16-B69B-48BB-8217-693632C78C14","generation":0}'
,2017-08-02 13:35:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-02 13:35:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-02 13:35:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-02 13:35:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:3437029A-5592-425D-88F9-94BA127A2E7C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:34,37029A-5592-425D-88F9-94BA127A2E7C:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "3437029A-5592-425D-88F9-94BA127A2E7C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,437029A-5592-425D-88F9-94BA127A2E7C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3437029A-5592-425D-88F9-94BA127A2E7C", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:3437029A-5592-425D-88F9-94BA127A2E7C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:3437029A-5592-425D-88F9-94BA127A2E7C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:AD28B5DB-E788-401E-9F57-0536CE0FD977:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "AD28B5DB-E788-401E-9F57-0536CE0FD977", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:3437029A-5592-425D-88F9-94BA127A2E7C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:34,37029A-5592-425D-88F9-94BA127A2E7C:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "3437029A-5592-425D-88F9-94BA127A2E7C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,437029A-5592-425D-88F9-94BA127A2E7C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3437029A-5592-425D-88F9-94BA127A2E7C", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:3437029A-5592-425D-88F9-94BA127A2E7C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:3437029A-5592-425D-88F9-94BA127A2E7C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:3437029A-5592-425D-88F9-94BA127A2E7C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:34,37029A-5592-425D-88F9-94BA127A2E7C:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "3437029A-5592-425D-88F9-94BA127A2E7C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,437029A-5592-425D-88F9-94BA127A2E7C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3437029A-5592-425D-88F9-94BA127A2E7C", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:3437029A-5592-425D-88F9-94BA127A2E7C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:3437029A-5592-425D-88F9-94BA127A2E7C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:3437029A-5592-425D-88F9-94BA127A2E7C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:34,37029A-5592-425D-88F9-94BA127A2E7C:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "3437029A-5592-425D-88F9-94BA127A2E7C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:3437029A,-5592-425D-88F9-94BA127A2E7C error: max retries exceeded
2017-08-02 13:36:10 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"BeiexaEq9kT35ixqoscZAUCjdsyeFpRU","error":"Connection could not be established","portNumber":null}'
2017-0,8-02 13:36:10 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'BeiexaEq9kT35ixqoscZAUCjdsyeFpRU', error: 'Connection could not be established', listeningPort: '%s''
,2017-08-02 13:36:10 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-08-02 13:36:10 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 6133E365-15A1-4D8C-9D13-580E318DED29 (syncValue: I9XGPTu,I4whlamaUUAnLUi6kOokQ4vFm)'
2017-08-02 13:36:10 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6133E365-15A1-4D8C-9D13-580E318DED29", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "6133E365-15A1-4D8C-9D13-580E318DED29", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:6133E365-15A1,-4D8C-9D13-580E318DED29:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-08-02 13:36:10 - DEBUG thaliMobileNativeTestUtils: 'Already running tes,t,!'
2017-08-02 13:36:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:3437029A-5592-425D-88F9-94BA127A2E7C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:3437029A-5592-425D-88F9-94BA127A2E7C:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "3437029A-5592-425D-88F9-94BA127A2E7C", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:6133E365-15A1-4D8C-9D13-580E318DED29:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:6133E365-15A1-4D8C-9D13-580E318DED29:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:6133E365-15A1-4D8C-9D13-580E318DED29:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "6133E365-15A1-4D8C-9D13-580E318DED29", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:65282
2017-08-02 13:36:13 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"I9XGPTuI4whlamaUUAnLUi6kOokQ4vFm",,"error":null,"portNumber":65282}'
2017-08-02 13:36:13 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'I9XGPTuI4whlamaUUAnLUi6kOokQ4vFm', error: 'null', listeningPort: '65282''
,Connecting to the localhost:65282
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:6133E365-15A1-4D8C-9D13-580E318DED29:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:6133E365-15A1-4D8C-9D13-580E318DED29:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5 [3, 5]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,Connected to the localhost:65282
2017-08-02 13:36:13 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
2017-08-02 13:36:13 - DEBUG testThaliMobileNative: 'Client data flushed'
,ok 99 got the same data back
# teardown
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed b,y remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:5
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,2017-08-02 13:36:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-02 13:36:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-02 13:36:13 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:36:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:35268274-9198-49CF-822E-A7FA7B1EE03C
2017-08-02 13:36:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13,:,36:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:6133E365-15A1-4D8C-9D13-580E318DED29
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:65282
[ThaliCore] Session.disconnect() p,eer:6133E365-15A1-4D8C-9D13-580E318DED29:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:6133E365-15A1-4D8C-9D13-580E318DED29:0
,2017-08-02 13:36:14 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-02 13:36:14 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-02 13:36:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:36:14 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:36:14 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:36:14 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:36:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:36:14 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift large amounts of data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "57015E63-23BD-4EB8-8492-2EBC0DAADB25", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:57015E63-23BD-4EB8-8492-2EBC0DAADB25
,2017-08-02 13:36:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-02 13:36:14 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:36:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 100 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:15328036-B9D1-4DEB-ADFA-F3CBEFC39B6B
[ThaliCore] Browser.startListening
2017-08-02 13:36:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,",advertisingActive":true}'
,2017-08-02 13:36:14 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-02 13:36:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 101 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2A2FAD16-B69B-48BB-8217-693632C78C14:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2A2FAD16-B69B-48BB-8217-693632C78C14", generation: 0)
2017-08-02 13:36:15 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"2A2FAD16-B69B-48BB-8217-693632C78C14","generation":0}'
2017-08-02 13:36:15 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 2A2FAD16-B69B-48BB-8217-693632C78C14, (syncValue: x3zc5bWOVW2sFWTuSCWJPwD3GwbP12qf)'
2017-08-02 13:36:15 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2A2FAD16-B69B-48BB-8217-693632C,78C14", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2A2FAD16-B69B-48BB-8217-693632C78C14", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected,:,) peer:2A2FAD16-B69B-48BB-8217-693632C78C14:0
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6133E365-15A1-4D8C-9D13-580E318DED29:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6133E365-15A1-4D8C-9D13-580E318DED29",, generation: 0)
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-08-02 13:36:15 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable,":true,"peerIdentifier":"6133E365-15A1-4D8C-9D13-580E318DED29","generation":0}'
2017-08-02 13:36:15 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-02 13:36:15 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3354EF96-D625-4161-8D00-E338DDA254DF:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3354EF96-D625-4161-8D00-E338DDA254DF", generation: 0)
,2017-08-02 13:36:15 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"3354EF96-D625-4161-8D00-E338DDA254DF","generation":0}'
,2017-08-02 13:36:15 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-02 13:36:15 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-02 13:36:15 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:57015E63-23BD-4EB8-8492-2EBC0DAADB25:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "57015E63-23BD-4EB8-8492-2EBC0DAADB25", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A6416A01-7433-4745-962F-A44CFEAB83C5:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A6416A01-7433-4745-962F-A44CFEAB83C5", generation: 0)
2017-08-02 13:36:16 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"A6416A01-7433-4745-962F-A44CFEAB83C5","generation":0}'
2017-08-02 13:36:16 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-02 13:36:16 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-08-02 13:36:16 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-02 13:36:16 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:2A2FAD16-B69B-48BB-8217-693632C78C14:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:2A,2FAD16-B69B-48BB-8217-693632C78C14:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "2A2FAD16-B69B-48BB-8217-693632C78C14", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2,A2FAD16-B69B-48BB-8217-693632C78C14", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2A2FAD16-B69B-48BB-8217-693632C78C14", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:2A2FAD16-B69B-48BB-8217-693632C78C14:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:2A2FAD16-B69B-48BB-8217-693632C78C14:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:6133E365-15A1-4D8C-9D13-580E318DED29:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "6133E365-15A1-4D8C-9D13-580E318DED29", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:2A2FAD16-B69B-48BB-8217-693632C78C14:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:2A2FAD16-B69B-48BB-8217-693632C78C14:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "2A2FAD16-B69B-48BB-8217-693632C78C14", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2,A2FAD16-B69B-48BB-8217-693632C78C14", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2A2FAD16-B69B-48BB-8217-693632C78C14", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:2A2FAD16-B69B-48BB-8217-693632C78C14:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:2A2FAD16-B69B-48BB-8217-693632C78C14:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:2A2FAD16-B69B-48BB-8217-693632C78C14:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:2A,2FAD16-B69B-48BB-8217-693632C78C14:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "2A2FAD16-B69B-48BB-8217-693632C78C14", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2,A2FAD16-B69B-48BB-8217-693632C78C14", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2A2FAD16-B69B-48BB-8217-693632C78C14", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:2A2FAD16-B69B-48BB-8217-693632C78C14:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:2A2FAD16-B69B-48BB-8217-693632C78C14:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C48CFE58-829C-494C-B1A6-009DC5C2F39F
[ThaliCore] Advertiser: session connected Peer(uuid: "57015E63-23BD-4EB8-8492-2EBC0DAADB25", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:C48CFE58-829C-494C-B1A6-009DC5C2F39F state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:2A2FAD16-B69B-48BB-8217-693632C78C14:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:2A,2FAD16-B69B-48BB-8217-693632C78C14:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "2A2FAD16-B69B-48BB-8217-693632C78C14", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:2A2FAD16,-B69B-48BB-8217-693632C78C14 error: max retries exceeded
2017-08-02 13:36:25 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"x3zc5bWOVW2sFWTuSCWJPwD3GwbP12qf","error":"Connection could not be established","portNumber":null}'
2017-0,8-02 13:36:25 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'x3zc5bWOVW2sFWTuSCWJPwD3GwbP12qf', error: 'Connection could not be established', listeningPort: '%s''
,2017-08-02 13:36:25 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-08-02 13:36:25 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 3354EF96-D625-4161-8D00-E338DDA254DF (syncValue: 5LAtxzq,BY6uevch7HO15KXFoq4iW5FSw)'
2017-08-02 13:36:25 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3354EF96-D625-4161-8D00-E338DDA254DF", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3354EF96-D625-4161-8D00-E338DDA254DF", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3354EF96-D625,-4161-8D00-E338DDA254DF:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-08-02 13:36:25 - DEBUG thaliMobileNativeTestUtils: 'Already running tes,t,!'
2017-08-02 13:36:25 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:2A2FAD16-B69B-48BB-8217-693632C78C14:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:3354EF96-D625-4161-8D00-E338DDA254DF:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:C48CFE58-829C-494C-B1A6-009DC5C2F39F
,[ThaliCore] Session.session(_:peer:didChange:) peer:C48CFE58-829C-494C-B1A6-009DC5C2F39F state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C48CFE58-829C-494C-B1A6-009DC5C2F39F
[ThaliCore] Session.startOutputStream(with:) peer:C48CFE58-829C-494C-B1A6-009DC5C2F39F
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6 [3, 5, 6]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-08-02 13:36:26 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-08-02 13:36:26 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
,2017-08-02 13:36:26 - DEBUG testThaliMobileNative: 'Server received (2119 bytes):'
,2017-08-02 13:36:26 - DEBUG testThaliMobileNative: 'Server received (2261 bytes):'
,2017-08-02 13:36:26 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-08-02 13:36:26 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-08-02 13:36:26 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-08-02 13:36:26 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-08-02 13:36:26 - DEBUG testThaliMobileNative: 'Server received (2119 bytes):'
,2017-08-02 13:36:26 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-08-02 13:36:26 - DEBUG testThaliMobileNative: 'Server received (3214 bytes):'
,2017-08-02 13:36:26 - DEBUG testThaliMobileNative: 'Server received (2332 bytes):'
,2017-08-02 13:36:26 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-08-02 13:36:26 - DEBUG testThaliMobileNative: 'Server received (1024 bytes):'
,2017-08-02 13:36:26 - DEBUG testThaliMobileNative: 'Server received (3356 bytes):'
,2017-08-02 13:36:26 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-08-02 13:36:26 - DEBUG testThaliMobileNative: 'Server received (5404 bytes):'
,2017-08-02 13:36:26 - DEBUG testThaliMobileNative: 'Server received (3214 bytes):'
,2017-08-02 13:36:26 - DEBUG testThaliMobileNative: 'Server received (2332 bytes):'
,2017-08-02 13:36:26 - DEBUG testThaliMobileNative: 'Server received (17356 bytes):'
,2017-08-02 13:36:26 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-08-02 13:36:26 - DEBUG testThaliMobileNative: 'Server sends data back to client (65536 bytes):'
2017-08-02 13:36:26 - DEBUG testThaliMobileNative: 'Server data flushed',
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:6
[ThaliCore] VirtualSocket.closeStreams() vsID:6
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:6
[ThaliCore] VirtualSocket.deinit vsID:6 [3, 5]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:3354EF96-D625-4161-8D00-E338DDA254DF:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:3354EF96-D625-4161-8D00-E338DDA254DF:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "3354EF96-D625-4161-8D00-E338DDA254DF", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:65299
,2017-08-02 13:36:28 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"5LAtxzqBY6uevch7HO15KXFoq4iW5FSw","error":null,"portNumber":65299}'
2017-08-02 13:36:28 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '5LAtxzqBY6uevch7HO15KXFoq4iW5FSw', error: 'null', listeningPort: '65299''
,Connecting to the localhost:65299
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:3354EF96-D625-4161-8D00-E338DDA254DF:0
,Connected to the localhost:65299
2017-08-02 13:36:28 - DEBUG testThaliMobileNative: 'Client sends data (65536 bytes):'
2017-08-02 13:36:28 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3354EF96-D625-4161-8D00-E338DDA254DF:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7 [3, 5, 7]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:7
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:7
[ThaliCore] VirtualSocket.deinit vsID:7 [3, 5]
,ok 102 got the same data back
,# teardown
,2017-08-02 13:36:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-08-02 13:36:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-08-02 13:36:29 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-02 13:36:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:57015E63-23BD-4EB8-8492-2EBC0DAADB25
,2017-08-02 13:36:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:36:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:3354EF96-D625-4161-8D00-E338DDA254DF
,[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:65299
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:3354EF96-D625-4161-8D00-E338DDA254DF:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:3354EF96-D625-4161-8D00-E338DDA254DF:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "3354EF96-D625-4161-8D00-E338DDA254DF", generation: 0)
,2017-08-02 13:36:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-02 13:36:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-02 13:36:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:36:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:36:29 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:36:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:36:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:36:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-08-02 13:36:29 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"5LAtxzqBY6uevch7HO15KXFoq4iW5FSw","error":"Session disconnected","portNumber":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:C48CFE58-829C-494C-B1A6-009DC5C2F39F state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "57015E63-23BD-4EB8-8492-2EBC0DAADB25", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:C48CFE58-829C-494C-B1A6-009DC5C2F39F
[ThaliCore] Advert,iserRelay.deinit
,[ThaliCore] Session.deinit peer:3354EF96-D625-4161-8D00-E338DDA254DF:0
[ThaliCore] BrowserRelay.deinit
,# We do not emit peerAvailabilityChanged events until one of the start methods is called
,[ThaliCore] Session.deinit peer:C48CFE58-829C-494C-B1A6-009DC5C2F39F
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "41D3B57A-35E7-466F-9DBF-DA142AC44F5C", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:41D3B57A-35E7-466F-9DBF-DA142AC44F5C
2017-08-02 1,3:36:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-02 13:36:32 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:36:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 103 Ready to advertise
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:E177066F-9889-4FA6-BC17-B9A70DDCBCFF
[ThaliCore] Browser.startListening
2017-08,-02 13:36:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-08-02 13:36:32 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not m,atch with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:36:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate, (was in stopped state).'
ok 104 Ready to listen
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:AAC7114D-9198-4417-ABCB-FAF457EC1EA7:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "AAC7114D-9198-4417-ABCB-FAF457EC1EA7", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3354EF96-D625-4161-8D00-E338DDA254DF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3354EF96-D625-4161-8D00-E338DDA254DF", generation: 0)
[ThaliCore] AdvertiserManager,.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:41D3B57A-35E7-466F-9DBF-DA142AC44F5C
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2DF1643D-E6BB-4CD0-AF7F-003E6A7880B8:0
[ThaliCore] BrowserManager.foundPeerHan,dler peer:Peer(uuid: "2DF1643D-E6BB-4CD0-AF7F-003E6A7880B8", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2A2FAD16-B69B-48BB-8217-693632C78C14:0
2017-08-02 13:36:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2A2FAD16-B69B-48BB-8217-693632C78C14", generation: 0)
2017-08-02 13:36:32 - INFO thaliMobile: 'Received state ({"di,scoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-02 13:36:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 105 stop ads worked
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-08-02 13:36:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:36:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,ok 106 test stop worked
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:36:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:36:36 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:36:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:36:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-02 13:36:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-02 13:36:36 - DEBUG thaliMo,bileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-02 13:36:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:36:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-02 13:36:36 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-02 13:36:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-02 13:36:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:36:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Test updating advertising and parallel data transfer
,2017-08-02 13:36:36 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test updating advertising and parallel data transfer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-02 13:36:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:36:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:36:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:36:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:36:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-02 13:36:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-02 13:36:36 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:36:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-02 13:36:36 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-02 13:36:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-02 13:36:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-02 13:36:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# discoveryAdvertisingStateUpdateNonTCP is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:F39E37BE-B0B0-4914-9A90-86A6D85F6B0E
[ThaliCore] Browser.startListening
,ok 107 discoveryActive should be false
ok 108 advertisingActive should be true
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "75FCEEE6-6B84-4C34-AB0C-F4D6B4CCA356", generation: 0)
[ThaliCore] Advertise,r.startAdvertising with peerID:75FCEEE6-6B84-4C34-AB0C-F4D6B4CCA356
ok 109 discoveryActive should be false
ok 110 advertisingActive should be true
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
ok 111 d,iscoveryActive should be false
ok 112 advertisingActive should be true
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:75FCEEE6-6B84-4C34-AB0C-F4D6B4CCA356
ok 113 discoveryActive should be false
ok 114 a,dvertisingActive should be true
ok 115 Can call startListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:36:37 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-02 13:36:37 - DEBUG thaliMobi,leNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-02 13:36:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:36:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-02 13:36:37 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-02 13:36:37 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-02 13:36:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-02 13:36:37 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call connect when start listening for advertisements is not active
,2017-08-02 13:36:37 - DEBUG CoordinatedClient: 'test was skipped, name: 'cannot call connect when start listening for advertisements is not active''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:36:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:36:37 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 116 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:36:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:36:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 117 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# Get error when trying to double connect to a peer on Android
,2017-08-02 13:36:37 - DEBUG CoordinatedClient: 'test was skipped, name: 'Get error when trying to double connect to a peer on Android''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:36:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:36:37 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 118 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:36:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:36:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 119 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection
,2017-08-02 13:36:38 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-02 13:36:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:36:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 120 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:36:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:36:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 121 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection
,2017-08-02 13:36:38 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:36:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:36:39 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 122 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:36:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:36:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 123 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer
,2017-08-02 13:36:39 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:36:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:36:39 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 124 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:36:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:36:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 125 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer
,2017-08-02 13:36:39 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:36:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:36:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 126 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:36:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:36:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 127 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# cannot call multiConnect when start listening for advertisements is not active
,ok 128 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:67ba7a0b-70fb-44d1-a8c3-1320e57342c5 error: startListeningNotActive
2017-08-02 13:36:40 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"jBiN0EDW0cjvnG,rsafLsVdGEzxqMfRqw","error":"startListeningForAdvertisements is not active","portNumber":null}'
ok 129 Should only get called after multiConnect returned
ok 130 SyncValue matches
ok 131 Got right error
ok 132 listeningPort is null
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:36:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:36:40 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:36:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-08-02 13:36:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-02 13:36:40 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-02 13:36:40 - DEBUG t,haliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-02 13:36:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:36:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-02 13:36:40 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-02 13:36:40 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-02 13:36:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-02 13:36:40 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with illegal peerID
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:8C523DEA-6754-4383-8E63-B7A1C52236C9
[ThaliCore] Browser.startListening
,2017-08-02 13:36:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-02 13:36:41 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:36:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 133 No error on starting
ok 134 Got null as expected
2017-08-02 13:36:41 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"jM09UKjyaprwmIlBXodxuzBVd9bsofDQ","error":"Illegal peerID","portNumber",:null}'
ok 135 Should only get called after multiConnect returned
ok 136 SyncValue matches
ok 137 Got right error
ok 138 listeningPort is null
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2A2FAD16-B69B-48BB-8217-693632C78C14:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2A2FAD16-B69B-48BB-8217-693632C78C14", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:3354EF96-D625-4161-8D00-E338DDA254DF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3354EF96-D625-4161-8D00-E338DDA254DF", generation: 0)
2017-08-02 13:36:41 - DEBUG thaliMobileNativeWrapper: 'Rec,eived peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"2A2FAD16-B69B-48BB-8217-693632C78C14","generation":0}]'
2017-08-02 13:36:41 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"p,eerAvailable":true,"peerIdentifier":"2A2FAD16-B69B-48BB-8217-693632C78C14","generation":0}'
2017-08-02 13:36:41 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-08-02 13:36:41 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"3354EF96-D625-4161-8D00-E338DDA254DF","generation":0}]'
2017-08-02 13:36:41 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"3354EF96-D625-4161-8D00-E338DDA254DF","generation":0}'
,2017-08-02 13:36:41 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-08-02 13:36:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:36:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:36:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:36:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:36:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-02 13:36:41 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-02 13:36:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:36:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:36:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:36:41 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:36:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:36:41 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# multiConnect properly fails on legal but non-existent peerID
,2017-08-02 13:36:41 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiConnect properly fails on legal but non-existent peerID''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:36:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:36:42 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:36:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-08-02 13:36:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:36:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-02 13:36:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-02 13:36:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:36:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-02 13:36:42 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-02 13:36:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-02 13:36:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
2017-08-02 13:36:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with invalid syncValue
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:BCC5F512-99C6-4887-AF49-8BB968CEDBD9
[ThaliCore] Browser.startListening
2017-08-02 13:36:42 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-02 13:36:42 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-02 13:36:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 139 No error on starting
,ok 140 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-02 13:36:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02, 13:36:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:36:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discovery,Active":false,"advertisingActive":false}'
2017-08-02 13:36:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:36:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-02 13:36:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-02 13:36:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:36:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:36:42 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:36:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:36:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:36:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call disconnect with invalid peer id
,ok 141 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:36:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:36:42 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:36:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-08-02 13:36:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:36:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-02 13:36:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-02 13:36:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:36:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:36:42 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:36:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:36:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:36:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# disconnect doesn't fail on plausible but bogus peer ID
,[ThaliCore] BrowserManager.disconnect peer:47f259fd-3b2f-41ac-8c5e-a6ad0be1aa3b
ok 142 No error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:36:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:36:43 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:36:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-08-02 13:36:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:36:43 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-02 13:36:43 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-02 13:36:43 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:36:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-02 13:36:43 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-02 13:36:43 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-02 13:36:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-02 13:36:43 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Get same port when trying to connect multiple times on iOS
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "2D5EA3C1-2612-4C80-833C-86BA8D46ADA6", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:2D5EA3C1-2612-4C80-833C-86BA8D46ADA6
2017-08-02 13:36:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-02 13:36:44, - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkTy,pe":null}})'
2017-08-02 13:36:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 143 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[Tha,liCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:19DE0C72-4053-401B-9A8A-EE6CE66C33B1
[ThaliCore] Browser.startListening
2017-08-02 13:36:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"adv,e,rtisingActive":true}'
2017-08-02 13:36:44 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"rou,ter":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:36:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 144 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2A2FAD16-B69B-48BB-8217-693632C78C14:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2A2FAD16-B69B-48BB-8217-693632C78C14", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3354EF96-D625-4161-8D00-E338DDA254DF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3354EF96-D625-4161-8D00-E338DDA254DF", generation: 0)
2017-08-02 13:36:44 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"2A2FAD16-B69B-48BB-8217-693632C78C14","generation":0}'
,2017-08-02 13:36:44 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 2A2FAD16-B69B-48BB-8217-693632C78C14 (syncValue: zz4QfUTD87kCdkwAp84RY3ZwXq1rYlMl)'
,2017-08-02 13:36:44 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2A2FAD16-B69B-48BB-8217-693632C78C14", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2A2FAD16-B69B-48BB-8217-693632C78C14", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2A2FAD16-B69B-48BB-8217-693632C78C14:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
2017-08-02 13:36:44 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"3354EF96-D625-4161-8D00-E338DDA254DF","generation":0}'
,2017-08-02 13:36:44 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-02 13:36:44 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:69DFFFC2-5186-4945-983D-DB6839F2BF34:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "69DFFFC2-5186-4945-983D-DB6839F2BF34", generation: 0)
,2017-08-02 13:36:45 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"69DFFFC2-5186-4945-983D-DB6839F2BF34","generation":0}'
,2017-08-02 13:36:45 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-02 13:36:45 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-02 13:36:45 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2D5EA3C1-2612-4C80-833C-86BA8D46ADA6:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2D5EA3C1-2612-4C80-833C-86BA8D46ADA6", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4C0E8F9D-7F20-4990-B0D6-35B5449DA4C3
[ThaliCore] Advertiser: session connected Peer(uuid: "2D5EA3C1-2612-4C80-833C-86BA8D46ADA6", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:4C0E8F9D-7F20-4990-B0D6-35B5449DA4C3 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B1240C8D-B477-419D-98C6-0B92452098A6:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B1240C8D-B477-419D-98C6-0B92452098A6", generation: 0)
2017-08-02 13:36:46 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B1240C8D-B477-419D-98C6-0B92452098A6","generation":0}'
2017-08-02 13:36:46 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-02 13:36:46 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-08-02 13:36:46 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-02 13:36:46 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:2A2FAD16-B69B-48BB-8217-693632C78C14:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:2A,2FAD16-B69B-48BB-8217-693632C78C14:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "2A2FAD16-B69B-48BB-8217-693632C78C14", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2,A2FAD16-B69B-48BB-8217-693632C78C14", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2A2FAD16-B69B-48BB-8217-693632C78C14", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:2A2FAD16-B69B-48BB-8217-693632C78C14:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:2A2FAD16-B69B-48BB-8217-693632C78C14:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:4C0E8F9D-7F20-4990-B0D6-35B5449DA4C3
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:3354EF96-D625-4161-8D00-E338DDA254DF:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "3354EF96-D625-4161-8D00-E338DDA254DF", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:4C0E8F9D-7F20-4990-B0D6-35B5449DA4C3 state: connecting -> connected
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:2A2FAD16-B69B-48BB-8217-693632C78C14:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "2A2FAD16-B69B-48BB-8217-693632C78C14", generation: 0)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4C0E8F9D-7F20-4990-B0D6-35B5449DA4C3
[ThaliCore] Session.startOutputStream(with:) peer:4C0E8F9D-7F20-4990-B0D6-35B5449DA4C3
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8, [3, 5, 8]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:6081F6C6-C3D1-4B64-B214-7F8CF14FB19F
[ThaliCore] Advertiser: session connected Peer(uuid: "2D5EA3C1-2612-4C80-833C-86BA8D46ADA6", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:6081F6C6-C3D1-4B64-B214-7F8CF14FB19F state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:2A2FAD16-B69B-48BB-8217-693632C78C14:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:2A,2FAD16-B69B-48BB-8217-693632C78C14:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "2A2FAD16-B69B-48BB-8217-693632C78C14", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2,A2FAD16-B69B-48BB-8217-693632C78C14", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2A2FAD16-B69B-48BB-8217-693632C78C14", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-08-02 13:36:49 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"zz4QfUTD87kCdkwAp84RY3ZwXq1rYlMl","error":"Peer is unavailable",,"portNumber":null}'
2017-08-02 13:36:49 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'zz4QfUTD87kCdkwAp84RY3ZwXq1rYlMl', error: 'Peer is unavailable', listeningPort: '%s''
,2017-08-02 13:36:49 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-08-02 13:36:49 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 69DFFFC2-5186-4945-983D-DB6839F2BF34 (syncValue: mmwNsOyBAKft7k1zDJA7hUe,JejZpmyuc)'
2017-08-02 13:36:49 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "69DFFFC2-5186-4945-983D-DB6839F2BF34", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "69DFFFC2-5186-4945-983D-DB6839F2BF34", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:69DFFFC2-5186-4945-983D-DB683,9F2BF34:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-08-02 13:36:49 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:2A2FAD16-B69B-48BB-8217-693632C78C14:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:69DFFFC2-5186-4945-983D-DB6839F2BF34:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:6081F6C6-C3D1-4B64-B214-7F8CF14FB19F
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:69DFFFC2-5186-4945-983D-DB6839F2BF34:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:6081F6C6-C3D1-4B64-B214-7F8CF14FB19F state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:6081F6C6-C3D1-4B64-B214-7F8CF14FB19F
[ThaliCore] Session.startOutputStream(with:) peer:6081F6C6-C3D1-4B64-B214-7F8CF14FB19F
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9 [3, 5, 8, 9]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:69DFFFC2-5186-4945-983D-DB6839F2BF34:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "69DFFFC2-5186-4945-983D-DB6839F2BF34", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:65313
,2017-08-02 13:36:52 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"mmwNsOyBAKft7k1zDJA7hUeJejZpmyuc","error":null,"portNumber":65313}'
,2017-08-02 13:36:52 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'mmwNsOyBAKft7k1zDJA7hUeJejZpmyuc', error: 'null', listeningPort: '65313''
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:69DFFFC2-5186-4945-983D-DB6839F2BF34:0
,ok 145 Got null as expected
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "69DFFFC2-5186-4945-983D-DB6839F2BF34", generation: 0) found active relay
,2017-08-02 13:36:52 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"8f8g4CwpSr85CZsLftz5k4xH57YffxbA","error":null,"portNumber":65313}'
,ok 146 No error
,ok 147 Ports equal
,ok 148 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "69DFFFC2-5186-4945-983D-DB6839F2BF34", generation: 0) found active relay
,2017-08-02 13:36:52 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"cE7Br18g4jFkKRkHErmbEzfpcPw2fXCK","error":null,"portNumber":65313}'
ok 149 No error
,ok 150 Ports equal
,# teardown
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:69DFFFC2-5186-4945-983D-DB6839F2BF34:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:10 [3, 5, 8, 9, 10]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-08-02 13:36:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-02 13:36:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-02 13:36:52 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:36:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:2D5EA3C1-2612-4C80-833C-86BA8D46ADA6
2017-08-02 13:36:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13,:36:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer," UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:8
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandl,er removed virtual socket vsID:9
[ThaliCore] VirtualSocket.closeStreams() vsID:8
[ThaliCore] VirtualSocket.closeStreams() vsID:9
[ThaliCore] BrowserManager.disconnect peer:69DFFFC2-5186-4945-983D-DB6839F2BF34
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:65313
[ThaliCore] VirtualSocket.closeStreams() vsID:10
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListene,r.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsH,andler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:8
[ThaliCore] VirtualSocket.deinit vsID:8 [3, 5, 9, 10]
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLo,op vsID:9
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
,[ThaliCore] VirtualSocket exited RunLoop vsID:10
[ThaliCore] VirtualSocket.deinit vsID:9 [3, 5, 10]
[ThaliCore] Session.disconnect() peer:69DFFFC2-5186-4945-983D-DB6839F2BF34:0
[ThaliCore] VirtualSocket.closeStreams() vsID:10
[ThaliCore] BrowserRelay.d,idCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket.deinit vsID:10 [3, 5]
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:69DFFFC2-5186-4945-983D-DB6839F2BF34:0
[ThaliCore] BrowserRelay.deinit
2017-08-02 13:36:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-02 13:36:52 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-02 13:36:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:36:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:36:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:36:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:36:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:36:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:4C0E8F9D-7F20-4990-B0D6-35B5449DA4C3 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "2D5EA3C1-2612-4C80-833C-86BA8D46ADA6", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:6081F6C6-C3D1-4B64-B214-7F8CF14FB19F
,[ThaliCore] Session.deinit peer:6081F6C6-C3D1-4B64-B214-7F8CF14FB19F
[ThaliCore] AdvertiserRelay.deinit
,# initial peer discovery
,2017-08-02 13:36:53 - DEBUG CoordinatedClient: 'test was skipped, name: 'initial peer discovery''
,# teardown
,2017-08-02 13:36:53 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-02 13:36:53 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-02 13:36:53 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:36:53 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-02 13:36:53 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-02 13:36:53 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-02 13:36:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-02 13:36:53 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 1
,2017-08-02 13:36:53 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 1''
,# teardown
,2017-08-02 13:36:54 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-02 13:36:54 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-02 13:36:54 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:36:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-02 13:36:54 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-02 13:36:54 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-02 13:36:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-02 13:36:54 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 2
,2017-08-02 13:36:54 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 2''
,# teardown
,2017-08-02 13:36:54 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-02 13:36:54 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-02 13:36:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:36:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-02 13:36:54 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-02 13:36:54 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-02 13:36:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-02 13:36:54 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# check latest peer discovery
,2017-08-02 13:36:54 - DEBUG CoordinatedClient: 'test was skipped, name: 'check latest peer discovery''
,# teardown
,2017-08-02 13:36:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-02 13:36:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-02 13:36:55 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:36:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-02 13:36:55 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-02 13:36:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-02 13:36:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-02 13:36:55 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Set up for no peer discovery test
,2017-08-02 13:36:55 - DEBUG CoordinatedClient: 'test was skipped, name: 'Set up for no peer discovery test''
,# teardown
,2017-08-02 13:36:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-02 13:36:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-02 13:36:55 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:36:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-02 13:36:55 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-02 13:36:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-02 13:36:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-02 13:36:55 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# no peer discovery
,2017-08-02 13:36:55 - DEBUG CoordinatedClient: 'test was skipped, name: 'no peer discovery''
,# teardown
,2017-08-02 13:36:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-02 13:36:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-02 13:36:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:36:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:36:55 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:36:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:36:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:36:55 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calling createNativeListener directly rejects
,2017-08-02 13:36:56 - DEBUG createNativeListener: 'Creating Native Server'
,2017-08-02 13:36:56 - DEBUG createNativeListener: 'listening 65316'
ok 151 Should throw
,# teardown
,2017-08-02 13:36:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-02 13:36:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-02 13:36:56 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits incomingConnectionState
,2017-08-02 13:36:56 - DEBUG createNativeListener: 'Creating Native Server'
,2017-08-02 13:36:56 - DEBUG createNativeListener: 'listening 65318'
,2017-08-02 13:36:56 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-08-02 13:36:56 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 152 initial connection state should be CONNECTED
,2017-08-02 13:36:56 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 153 final connection state should be DISCONNECTED
,# teardown
,2017-08-02 13:36:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-02 13:36:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-02 13:36:56 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits routerPortConnectionFailed
,2017-08-02 13:36:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-02 13:36:57 - DEBUG createNativeListener: 'Creating Native Server'
2017-08-02 13:36:57 - DEBUG createNativeListener: 'listening 65321'
,2017-08-02 13:36:57 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-08-02 13:36:57 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-08-02 13:36:57 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-08-02 13:36:57 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - error Error: connect ECONNREFUSED'
,ok 154 tried to connect to right port
,ok 155 failed due to refused connection
,ok 156 routerPortConnectionFailed is emitted
,# teardown
,2017-08-02 13:36:57 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-08-02 13:36:57 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-08-02 13:36:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-02 13:36:57 - DEBUG createNativeListener: 'Native Server - close'
2017-08-02 13:36:57 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <,-> Mux - 0 - close'
,2017-08-02 13:36:57 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server connections all up
,2017-08-02 13:36:57 - DEBUG createNativeListener: 'Creating Native Server'
,2017-08-02 13:36:57 - DEBUG createNativeListener: 'listening 65325'
,2017-08-02 13:36:57 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-08-02 13:36:57 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-08-02 13:36:57 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2017-08-02 13:36:57 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,ok 157 Send/recvd #1 should be equal length
,ok 158 Send/recvd #1 should be same
,ok 159 Send/recvd #2 should be equal length
,ok 160 Send/recvd #2 should be same
,ok 161 Should be exactly 2 client sockets
,# teardown
,2017-08-02 13:36:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-02 13:36:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-02 13:36:57 - DEBUG createNativeListener: 'Native Server - close'
,2017-08-02 13:36:57 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-08-02 13:36:57 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
,2017-08-02 13:36:57 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-08-02 13:36:57 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,2017-08-02 13:36:57 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-08-02 13:36:57 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# native server - closing incoming stream cleans outgoing socket
,2017-08-02 13:36:58 - DEBUG createNativeListener: 'Creating Native Server'
2017-08-02 13:36:58 - DEBUG createNativeListener: 'listening 65330'
,2017-08-02 13:36:58 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-08-02 13:36:58 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-08-02 13:36:58 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-08-02 13:36:58 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
2017-08-02 13:36:58 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,ok 162 socket shouldn't close until after stream
ok 163 incoming remains open
# teardown
,2017-08-02 13:36:58 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-08-02 13:36:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-02 13:36:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-02 13:36:58 - DEBUG createNativeListener: 'Native Server - close'
2017-08-02 13:36:58, - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-08-02 13:36:58 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing incoming connection cleans outgoing socket
,2017-08-02 13:36:58 - DEBUG createNativeListener: 'Creating Native Server'
,2017-08-02 13:36:58 - DEBUG createNativeListener: 'listening 65334'
,2017-08-02 13:36:58 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-08-02 13:36:58 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 164 we should not have gotten an error
,2017-08-02 13:36:58 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-08-02 13:36:58 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2017-08-02 13:36:58 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - cl,ose'
,ok 165 socket shouldn't close until after incoming
,ok 166 incoming is cleaned up
,# teardown
,2017-08-02 13:36:58 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-08-02 13:36:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-02 13:36:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-02 13:36:58 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - closing outgoing socket cleans associated mux stream
,2017-08-02 13:36:59 - DEBUG createNativeListener: 'Creating Native Server'
,2017-08-02 13:36:59 - DEBUG createNativeListener: 'listening 65338'
,2017-08-02 13:36:59 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-08-02 13:36:59 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-08-02 13:36:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-08-02 13:36:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-08-02 13:36:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-08-02 13:36:59 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,ok 167 stream was closed
,ok 168 incoming should survive
,ok 169 mux should have no streams
,# teardown
,2017-08-02 13:36:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-02 13:36:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-02 13:36:59 - DEBUG createNativeListener: 'Native Server - close'
,2017-08-02 13:36:59 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2017-08-02 13:36:59 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing the whole server cleans everything up
,2017-08-02 13:36:59 - DEBUG createNativeListener: 'Creating Native Server'
,2017-08-02 13:36:59 - DEBUG createNativeListener: 'listening 65342'
,2017-08-02 13:36:59 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-08-02 13:36:59 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 170 we should not have gotten an error
,2017-08-02 13:36:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 171 Buffers are identical
2017-08-02 13:36:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-02 13:36:59 - DEBUG createNativeListener: 'Native Server - close'
2017-08-02 13:36:59 - DEBUG createNativeListener: 'stream - mux stream, <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2017-08-02 13:36:59 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 172 native server is nulled out
ok 173 native server should be cl,osed
ok 174 incoming has been removed
ok 175 Incoming should be done
ok 176 The mux object should be closed
ok 177 The mux stream should be closed
,2017-08-02 13:36:59 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# teardown
2017-08-02 13:36:59 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-08-02 13:36:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - we can get a ton of connections and data through and still clean up the server completely
,2017-08-02 13:36:59 - DEBUG createNativeListener: 'Creating Native Server'
2017-08-02 13:36:59 - DEBUG createNativeListener: 'listening 65346'
,2017-08-02 13:36:59 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-08-02 13:36:59 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2017-08-02 13:36:59 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1'
2017-08-02 13:36:59 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - created'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - created'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - created'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - created'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - created'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - created'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - created'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - created'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - created'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - created'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - created'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - created'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - created'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - created'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - created'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - created'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - created'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - created'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - created'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - created'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - created'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - created'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - created'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - created'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - created'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - created'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - created'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - created'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - created'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - created'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - created'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - created'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - created'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - created'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - created'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - created'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - created'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - created'
,2017-08-02 13:37:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'Native Server - close'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - closed'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - closed'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - closed'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - closed'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - closed'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - closed'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - closed'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - closed'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - closed'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - closed'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - closed'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - closed'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - closed'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - closed'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - closed'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - closed'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - closed'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - closed'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - closed'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - closed'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - closed'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - closed'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - closed'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - closed'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - closed'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - closed'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - closed'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - closed'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - closed'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - closed'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - closed'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - closed'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - closed'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - closed'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - closed'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - closed'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - closed'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - closed'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,ok 178 native server is nulled out
ok 179 native server should be closed
,ok 180 incoming has been removed
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - close'
2017-08-02 13:37:00 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - close'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - close'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - close'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - close'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - close'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - close'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - close'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - close'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - close'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - close'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - close'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - close'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - close'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - close'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - close'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - close'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - close'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - close'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - close'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - close'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - close'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - close'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - close'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - close'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - close'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - close'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - close'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - close'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - close'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - close'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - close'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - close'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - close'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - close'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - close'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - close'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - close'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-08-02 13:37:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - simulate mux failure, make sure everything is cleaned up
,2017-08-02 13:37:01 - DEBUG createNativeListener: 'Creating Native Server'
,2017-08-02 13:37:01 - DEBUG createNativeListener: 'listening 65398'
,2017-08-02 13:37:01 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-08-02 13:37:01 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 181 we should not have gotten an error
,2017-08-02 13:37:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 182 Buffers are identical
2017-08-02 13:37:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2017-08-02 13:37:01 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-08-02 13:37:01 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 183 server should be fine
ok 184 server should be open
ok 185 incoming has been removed
ok 186 The mux object should be clos,ed
ok 187 The mux stream should be closed
2017-08-02 13:37:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-08-02 13:37:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-02 13:37:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-02 13:37:01 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - timing out the incoming connection cleans everything up
,2017-08-02 13:37:02 - DEBUG createNativeListener: 'Creating Native Server'
,2017-08-02 13:37:02 - DEBUG createNativeListener: 'listening 65402'
,2017-08-02 13:37:02 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-08-02 13:37:02 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 188 we should not have gotten an error
,2017-08-02 13:37:02 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 189 Buffers are identical
,2017-08-02 13:37:02 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - incoming socket timeout'
,2017-08-02 13:37:02 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-08-02 13:37:02 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-08-02 13:37:02 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 190 server should be fine
,ok 191 server should be open
,ok 192 incoming has been removed
,ok 193 The mux object should be closed
,ok 194 The mux stream should be closed
,# teardown
,2017-08-02 13:37:02 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-08-02 13:37:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-02 13:37:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-02 13:37:02 - DEBUG createNativeListener: 'Native Server - close'
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
,2017-08-02 13:37:03 - DEBUG createNativeListener: 'Creating Native Server'
2017-08-02 13:37:03 - DEBUG createNativeListener: 'listening 65405'
ok 198 port must be in range
,# teardown
,2017-08-02 13:37:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-02 13:37:03 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# starting twice resolves with listening port
,2017-08-02 13:37:03 - DEBUG createNativeListener: 'Creating Native Server'
,2017-08-02 13:37:03 - DEBUG createNativeListener: 'listening 65406'
ok 199 second start should return same port
,# teardown
,2017-08-02 13:37:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-02 13:37:03 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminateIncomingConnection will terminate a connection
,2017-08-02 13:37:03 - DEBUG createNativeListener: 'Creating Native Server'
2017-08-02 13:37:03 - DEBUG createNativeListener: 'listening 65408'
,2017-08-02 13:37:03 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-08-02 13:37:03 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 200 we should be connected
2017-08-02 13:37:03 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 201 now we are disconnected
,2017-08-02 13:37:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# teardown
,2017-08-02 13:37:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-02 13:37:04 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminate an Outgoing connection
,2017-08-02 13:37:04 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 32'
ok 202 Passed bogus id
2017-08-02 13:37:04 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port, 901'
ok 203 Passed good id but bogus port
2017-08-02 13:37:04 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 900'
ok 204 Passed right context
,ok 205 Right server
,ok 206 No error should be set
,ok 207 Retry should be false
,ok 208 We called close server
,# teardown
,# setup
,# Single local http request
,listening on 65410
,ok 209 should be equal
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-02 13:37:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:37:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:37:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:37:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:37:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-02 13:37:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-02 13:37:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-02 13:37:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:37:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:37:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:37:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:37:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:37:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Single coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C712BB72-1ECB-455C-8BB1-65EBA45DEC6A", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:C712BB72-1ECB-455C-8BB1-65EBA45DEC6A
2017-08-02 1,3:37:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-02 13:37:04 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:37:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 210 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C07E8E38-F7B6-45B9-A070-2A2492D7E5B4
[Tha,l,iCore] Browser.startListening
2017-08-02 13:37:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-08-02 13:37:04 - INFO thaliMobile: 'Received state ({"discoveryActive":tru,e,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:37:04 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 211 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:69DFFFC2-5186-4945-983D-DB6839F2BF34:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "69DFFFC2-5186-4945-983D-DB6839F2BF34", generation: 0)
,2017-08-02 13:37:04 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"69DFFFC2-5186-4945-983D-DB6839F2BF34","generation":0}'
,2017-08-02 13:37:04 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 69DFFFC2-5186-4945-983D-DB6839F2BF34 (syncValue: E5MHG1tZ5uBlQgOPoz6aU9STm0l4TD9s)'
,2017-08-02 13:37:04 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "69DFFFC2-5186-4945-983D-DB6839F2BF34", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "69,DFFFC2-5186-4945-983D-DB6839F2BF34", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:69DFFFC2-5186-4945-983D-DB6839F2BF34:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CCE5AE9E-6A2F-4382-99A8-BB35E900BC6E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CCE5AE9E-6A2F-4382-99A8-BB35E900BC6E", generation: 0)
2017-08-02 13:37:05 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"CCE5AE9E-6A2F-4382-99A8-BB35E900BC6E","generation":0}'
2017-08-02 13:37:05 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-02 13:37:05 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4A952A36-869C-4BA1-B6B2-B18200FBF636:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4A952A36-869C-4BA1-B6B2-B18200FBF636", generation: 0)
,2017-08-02 13:37:06 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"4A952A36-869C-4BA1-B6B2-B18200FBF636","generation":0}'
,2017-08-02 13:37:06 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-02 13:37:06 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-02 13:37:06 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C712BB72-1ECB-455C-8BB1-65EBA45DEC6A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C712BB72-1ECB-455C-8BB1-65EBA45DEC6A", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:69DFFFC2-5186-4945-983D-DB6839F2BF34:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:69,DFFFC2-5186-4945-983D-DB6839F2BF34:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "69DFFFC2-5186-4945-983D-DB6839F2BF34", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,9DFFFC2-5186-4945-983D-DB6839F2BF34", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "69DFFFC2-5186-4945-983D-DB6839F2BF34", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:69DFFFC2-5186-4945-983D-DB6839F2BF34:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:69DFFFC2-5186-4945-983D-DB6839F2BF34:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:69DFFFC2-5186-4945-983D-DB6839F2BF34:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "69DFFFC2-5186-4945-983D-DB6839F2BF34", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:69DFFFC2-5186-4945-983D-DB6839F2BF34:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:69,DFFFC2-5186-4945-983D-DB6839F2BF34:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "69DFFFC2-5186-4945-983D-DB6839F2BF34", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,9DFFFC2-5186-4945-983D-DB6839F2BF34", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "69DFFFC2-5186-4945-983D-DB6839F2BF34", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-08-02 13:37:10 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"E5MHG1tZ5uBlQgOPoz6aU9STm0l4TD9s","error":"Peer is unavailable",,"portNumber":null}'
2017-08-02 13:37:10 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'E5MHG1tZ5uBlQgOPoz6aU9STm0l4TD9s', error: 'Peer is unavailable', listeningPort: '%s''
,2017-08-02 13:37:10 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-08-02 13:37:10 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for CCE5AE9E-6A2F-4382-99A8-BB35E900BC6E (syncValue: uU9t3mHw5h8bLb0Q2csb5Nh,9byXVNwab)'
2017-08-02 13:37:10 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "CCE5AE9E-6A2F-4382-99A8-BB35E900BC6E", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CCE5AE9E-6A2F-4382-99A8-BB35E900BC6E", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:CCE5AE9E-6A2F-4382-99A8-BB35E,900BC6E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-08-02 13:37:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:69DFFFC2-5186-4945-983D-DB6839F2BF34:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:CCE5AE9E-6A2F-4382-99A8-BB35E900BC6E:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:CCE5AE9E-6A2F-4382-99A8-BB35E900BC6E:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:CCE5AE9E-6A2F-4382-99A8-BB35E900BC6E:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "CCE5AE9E-6A2F-4382-99A8-BB35E900BC6E", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:65420
2017-08-02 13:37:14 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"uU9t3mHw5h8bLb0Q2csb5Nh9byXVNwab",,"error":null,"portNumber":65420}'
2017-08-02 13:37:14 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'uU9t3mHw5h8bLb0Q2csb5Nh9byXVNwab', error: 'null', listeningPort: '65420''
,ok 212 should be equal
2017-08-02 13:37:14 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 4A952A36-869C-4BA1-B6B2-B18200FBF636 (syncValue: YTRflW3SgBzeXqX7g1VYWHJvSColDhyI)'
2017-08-02 13:37:14 - DEBUG thaliMobileNativeTestUtils: 'Got 'mul,tiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4A952A36-869C-4BA1-B6B2-B18200FBF636", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConn,ected:) Peer(uuid: "4A952A36-869C-4BA1-B6B2-B18200FBF636", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4A952A36-869C-4BA1-B6B2-B18200FBF636:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocke,tTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:4A952A36-869C-4BA1-B6B2-B18200FBF636:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9326440E-49A8-4DC5-9049-885DBB40813A
[ThaliCore] Advertiser: session connected Peer(uuid: "C712BB72-1ECB-455C-8BB1-65EBA45DEC6A", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:9326440E-49A8-4DC5-9049-885DBB40813A state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:DC95A3D5-4F19-4144-80B3-3BCBE1B0E02E
[ThaliCore] Advertiser: session connected Peer(uuid: "C712BB72-1ECB-455C-8BB1-65EBA45DEC6A", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:DC95A3D5-4F19-4144-80B3-3BCBE1B0E02E state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:4A952A36-869C-4BA1-B6B2-B18200FBF636:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:4A952A36-869C-4BA1-B6B2-B18200FBF636:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "4A952A36-869C-4BA1-B6B2-B18200FBF636", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:65424
,2017-08-02 13:37:17 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"YTRflW3SgBzeXqX7g1VYWHJvSColDhyI","error":null,"portNumber":65424}'
,2017-08-02 13:37:17 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'YTRflW3SgBzeXqX7g1VYWHJvSColDhyI', error: 'null', listeningPort: '65424''
,ok 213 should be equal
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:9326440E-49A8-4DC5-9049-885DBB40813A
,[ThaliCore] Session.session(_:peer:didChange:) peer:9326440E-49A8-4DC5-9049-885DBB40813A state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:DC95A3D5-4F19-4144-80B3-3BCBE1B0E02E
,[ThaliCore] Session.session(_:peer:didChange:) peer:DC95A3D5-4F19-4144-80B3-3BCBE1B0E02E state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:9326440E-49A8-4DC5-9049-885DBB40813A state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "C712BB72-1ECB-455C-8BB1-65EBA45DEC6A", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:DC95A3D5-4F19-4144-80B3-3BCBE1B0E02E
,[ThaliCore] Session.deinit peer:DC95A3D5-4F19-4144-80B3-3BCBE1B0E02E
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-02 13:37:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-02 ,13:37:23 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-08-02 13:37:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:C712BB72-1ECB-455C-8BB1-6,5EBA45DEC6A
2017-08-02 13:37:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:37:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
[ThaliCore] BrowserManager.disconnect peer:CCE5AE9E-6A2F-4382-99A8-BB35E900BC6E
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:65420
[ThaliCore] Sessi,on.disconnect() peer:CCE5AE9E-6A2F-4382-99A8-BB35E900BC6E:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:CCE5AE9E-6A2F-4382-99A8-BB35E900BC6E:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] BrowserManager.disconnect peer:4A952A36-869C-4BA1-B6B2-B18200FBF636
,[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:65424
,[ThaliCore] Session.disconnect() peer:4A952A36-869C-4BA1-B6B2-B18200FBF636:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:4A952A36-869C-4BA1-B6B2-B18200FBF636:0
,[ThaliCore] BrowserRelay.deinit
,2017-08-02 13:37:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-02 13:37:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-02 13:37:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-02 13:37:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:37:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:37:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:37:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:37:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:37:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Multiple local http requests
,listening on 65426
,ok 214 should be equal
ok 215 should be equal
ok 216 should be equal
# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:37:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:37:24 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:37:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-08-02 13:37:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:37:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-02 13:37:24 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-02 13:37:24 - DEBUG thaliMobileNativeWrapper: 'Method disc,overyAdvertisingStateUpdateNonTCP registered to native'
2017-08-02 13:37:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:37:24 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-02 13:37:24 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-02 13:37:24 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-02 13:37:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-02 13:37:24 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Multiple coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "D0A7596E-3DFD-4990-A0F0-BB946745D9EF", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:D0A7596E-3DFD-4990-A0F0-BB946745D9EF
2017-08-02 13:37:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-02 13:37:25, - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkTy,pe":null}})'
2017-08-02 13:37:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 217 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[Tha,liCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:94B9F7F2-9417-48C7-A5B2-E572F8D3A1CE
[ThaliCore] Browser.startListening
2017-08-02 13:37:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"adv,e,rtisingActive":true}'
2017-08-02 13:37:25 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"rou,ter":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:37:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 218 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CCE5AE9E-6A2F-4382-99A8-BB35E900BC6E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CCE5AE9E-6A2F-4382-99A8-BB35E900BC6E", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:4A952A36-869C-4BA1-B6B2-B18200FBF636:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4A952A36-869C-4BA1-B6B2-B18200FBF636", generation: 0)
2017-08-02 13:37:25 - DEBUG thaliMobileNativeTestUtils: 'W,e got a peer {"peerAvailable":true,"peerIdentifier":"CCE5AE9E-6A2F-4382-99A8-BB35E900BC6E","generation":0}'
,2017-08-02 13:37:25 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for CCE5AE9E-6A2F-4382-99A8-BB35E900BC6E (syncValue: uD90YV5d9rIioxToJFPX0m1pXWxDwCmy)'
2017-08-02 13:37:25 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "CCE5AE9E-6A2F-4382-99A8-BB35E900BC6E", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CCE5AE9E-6A2F-4382-99A8-BB35E900BC6E", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:CCE5AE9E-6A2F-4382-99A8-BB35E900BC6E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
2017-08-02 13:37:25 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"4A952A36-869C-4BA1-B6B2-B18200FBF636","generation":0}'
,2017-08-02 13:37:25 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-02 13:37:25 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:38EB4510-C4BB-4339-8267-E8BFF2A630EC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "38EB4510-C4BB-4339-8267-E8BFF2A630EC", generation: 0)
,2017-08-02 13:37:25 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"38EB4510-C4BB-4339-8267-E8BFF2A630EC","generation":0}'
,2017-08-02 13:37:25 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-02 13:37:25 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-02 13:37:25 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D0A7596E-3DFD-4990-A0F0-BB946745D9EF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D0A7596E-3DFD-4990-A0F0-BB946745D9EF", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:00DC2AB4-228C-4A26-A795-434E1581F9F6:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "00DC2AB4-228C-4A26-A795-434E1581F9F6", generation: 0)
,2017-08-02 13:37:25 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"00DC2AB4-228C-4A26-A795-434E1581F9F6","generation":0}'
2017-08-02 13:37:25 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-02 13:37:25 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-02 13:37:25 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-02 13:37:25 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:CCE5AE9E-6A2F-4382-99A8-BB35E900BC6E:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:CC,E5AE9E-6A2F-4382-99A8-BB35E900BC6E:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "CCE5AE9E-6A2F-4382-99A8-BB35E900BC6E", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C,CE5AE9E-6A2F-4382-99A8-BB35E900BC6E", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CCE5AE9E-6A2F-4382-99A8-BB35E900BC6E", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:CCE5AE9E-6A2F-4382-99A8-BB35E900BC6E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:CCE5AE9E-6A2F-4382-99A8-BB35E900BC6E:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:CCE5AE9E-6A2F-4382-99A8-BB35E900BC6E:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "CCE5AE9E-6A2F-4382-99A8-BB35E900BC6E", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:CCE5AE9E-6A2F-4382-99A8-BB35E900BC6E:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:CC,E5AE9E-6A2F-4382-99A8-BB35E900BC6E:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "CCE5AE9E-6A2F-4382-99A8-BB35E900BC6E", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C,CE5AE9E-6A2F-4382-99A8-BB35E900BC6E", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CCE5AE9E-6A2F-4382-99A8-BB35E900BC6E", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-08-02 13:37:30 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"uD90YV5d9rIioxToJFPX0m1pXWxDwCmy","error":"Peer is unavailable",,"portNumber":null}'
2017-08-02 13:37:30 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'uD90YV5d9rIioxToJFPX0m1pXWxDwCmy', error: 'Peer is unavailable', listeningPort: '%s''
,2017-08-02 13:37:30 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-08-02 13:37:30 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 4A952A36-869C-4BA1-B6B2-B18200FBF636 (syncValue: lwC6rpWYyTB4Fgh3MUKBEU1,fe9RDYQIx)'
2017-08-02 13:37:30 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4A952A36-869C-4BA1-B6B2-B18200FBF636", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4A952A36-869C-4BA1-B6B2-B18200FBF636", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4A952A36-869C-4BA1-B6B2-B1820,0FBF636:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-08-02 13:37:30 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-02 ,1,3:37:30 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:CCE5AE9E-6A2F-4382-99A8-BB35E900BC6E:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:4A952A36-869C-4BA1-B6B2-B18200FBF636:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:4A,952A36-869C-4BA1-B6B2-B18200FBF636:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "4A952A36-869C-4BA1-B6B2-B18200FBF636", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,A952A36-869C-4BA1-B6B2-B18200FBF636", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4A952A36-869C-4BA1-B6B2-B18200FBF636", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:4A952A36-869C-4BA1-B6B2-B18200FBF636:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:4A952A36-869C-4BA1-B6B2-B18200FBF636:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:4A952A36-869C-4BA1-B6B2-B18200FBF636:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:4A,952A36-869C-4BA1-B6B2-B18200FBF636:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "4A952A36-869C-4BA1-B6B2-B18200FBF636", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,A952A36-869C-4BA1-B6B2-B18200FBF636", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4A952A36-869C-4BA1-B6B2-B18200FBF636", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:4A952A36-869C-4BA1-B6B2-B18200FBF636:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:4A952A36-869C-4BA1-B6B2-B18200FBF636:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:114D954D-133E-477A-A2FB-8DF94A6BD274
[ThaliCore] Advertiser: session connected Peer(uuid: "D0A7596E-3DFD-4990-A0F0-BB946745D9EF", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:114D954D-133E-477A-A2FB-8DF94A6BD274 state: notConnected -> connecting
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4818CFC3-52BB-48B5-8FD1-E7E06BE326B0
[ThaliCore] Advertiser: session connected Peer(uuid: "D0A7596E-3DFD-4990-A0F0-BB946745D9EF", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[T,haliCore] Session.session(_:peer:didChange:) peer:4818CFC3-52BB-48B5-8FD1-E7E06BE326B0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:4A952A36-869C-4BA1-B6B2-B18200FBF636:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:4A,952A36-869C-4BA1-B6B2-B18200FBF636:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "4A952A36-869C-4BA1-B6B2-B18200FBF636", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,A952A36-869C-4BA1-B6B2-B18200FBF636", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4A952A36-869C-4BA1-B6B2-B18200FBF636", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:4A952A36-869C-4BA1-B6B2-B18200FBF636:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:4A952A36-869C-4BA1-B6B2-B18200FBF636:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:4A952A36-869C-4BA1-B6B2-B18200FBF636:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "4A952A36-869C-4BA1-B6B2-B18200FBF636", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:4818CFC3-52BB-48B5-8FD1-E7E06BE326B0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:114D954D-133E-477A-A2FB-8DF94A6BD274
,[ThaliCore] Session.session(_:peer:didChange:) peer:4818CFC3-52BB-48B5-8FD1-E7E06BE326B0 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:114D954D-133E-477A-A2FB-8DF94A6BD274 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:4A952A36-869C-4BA1-B6B2-B18200FBF636:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:4A,952A36-869C-4BA1-B6B2-B18200FBF636:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "4A952A36-869C-4BA1-B6B2-B18200FBF636", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:4A952A36,-869C-4BA1-B6B2-B18200FBF636 error: max retries exceeded
2017-08-02 13:37:41 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"lwC6rpWYyTB4Fgh3MUKBEU1fe9RDYQIx","error":"Connection could not be established","portNumber":null}'
2017-0,8-02 13:37:41 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'lwC6rpWYyTB4Fgh3MUKBEU1fe9RDYQIx', error: 'Connection could not be established', listeningPort: '%s''
,2017-08-02 13:37:41 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-08-02 13:37:41 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 38EB4510-C4BB-4339-8267-E8BFF2A630EC (syncValue: NPQqVIs9LrbfOKHJA6tAUdo31MiJkVBz)'
,2017-08-02 13:37:41 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "38EB4510-C4BB-4339-8267-E8BFF2A630EC", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "38EB4510-C4BB-4339-8267-E8BFF2A630EC", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:38EB4510-C4BB-4339-8267-E8BFF2A630EC:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-08-02 13:37:41 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-02 13:37:41 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:4A952A36-869C-4BA1-B6B2-B18200FBF636:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:38EB4510-C4BB-4339-8267-E8BFF2A630EC:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:38EB4510-C4BB-4339-8267-E8BFF2A630EC:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:38EB4510-C4BB-4339-8267-E8BFF2A630EC:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "38EB4510-C4BB-4339-8267-E8BFF2A630EC", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:65449
2017-08-02 13:37:44 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"NPQqVIs9LrbfOKHJA6tAUdo31MiJkVBz",,"error":null,"portNumber":65449}'
2017-08-02 13:37:44 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'NPQqVIs9LrbfOKHJA6tAUdo31MiJkVBz', error: 'null', listeningPort: '65449''
,ok 219 should be equal
ok 220 should be equal
ok 221 should be equal
2017-08-02 13:37:44 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 00DC2AB4-228C-4A26-A795-434E1581F9F6 (syncValue: G0oBn3p6zJUahCj1QqD9se3KsguTaj12)'
2017-08-02 13:37:,44 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "00DC2AB4-228C-4A26-A795-434E1581F9F6", generation: 0) creating a new relay
[ThaliCore] Browser.i,nviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "00DC2AB4-228C-4A26-A795-434E1581F9F6", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:00DC2AB4-228C-4A26-A795-434E1581F9F6:0
[ThaliCore] Browser,Relay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-08-02 13:37:44 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:00DC2AB4-228C-4A26-A795-434E1581F9F6:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:00DC2AB4-228C-4A26-A795-434E1581F9F6:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:00DC2AB4-228C-4A26-A795-434E1581F9F6:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "00DC2AB4-228C-4A26-A795-434E1581F9F6", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:65455
2017-08-02 13:37:47 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"G0oBn3p6zJUahCj1QqD9se3KsguTaj12",,"error":null,"portNumber":65455}'
2017-08-02 13:37:47 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'G0oBn3p6zJUahCj1QqD9se3KsguTaj12', error: 'null', listeningPort: '65455''
,ok 222 should be equal
ok 223 should be equal
ok 224 should be equal
# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-02 13:37:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-02 13:37:48 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-08-02 13:37:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:D0A7596E-3DFD-4990-A0F0-B,B946745D9EF
2017-08-02 13:37:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:37:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:38EB4510-C4BB-4339-8267-E8BFF2A630EC
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:65449
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:38EB4510-C4BB-4339-8267-E8BFF2A630EC:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:38EB4510-C4BB-4339-8267-E8BFF2A630EC:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "38EB4510-C4BB-4339-8267-E8BFF2A630EC", generation: 0)
,[ThaliCore] BrowserManager.disconnect peer:00DC2AB4-228C-4A26-A795-434E1581F9F6
[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:65455
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:00DC2AB4-228C-4A26-A795-434E1581F9F6:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:114D954D-133E-477A-A2FB-8DF94A6BD274 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "D0A7596E-3DFD-4990-A0F0-BB946745D9EF", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:4818CFC3-52BB-48B5-8FD1-E7E06BE326B0
,[ThaliCore] Session.deinit peer:4818CFC3-52BB-48B5-8FD1-E7E06BE326B0
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:00DC2AB4-228C-4A26-A795-434E1581F9F6:0
[ThaliCore] BrowserRelay.deinit
,2017-08-02 13:37:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-02 13:37:48 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-02 13:37:48 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-02 13:37:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:37:48 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:37:48 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:37:48 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:37:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:37:48 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-08-02 13:37:48 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"NPQqVIs9LrbfOKHJA6tAUdo31MiJkVBz","error":"Session disconnected","portNumber":null}'
,[ThaliCore] Session.deinit peer:38EB4510-C4BB-4339-8267-E8BFF2A630EC:0
[ThaliCore] BrowserRelay.deinit
,# #startListeningForAdvertisements should fail if start not called
,ok 225 specific error should be returned
,# teardown
,ok 226 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:37:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:37:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:37:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:37:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:37:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-02 13:37:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-02 13:37:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:37:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-02 13:37:51 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-02 13:37:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-02 13:37:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-02 13:37:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# #startUpdateAdvertisingAndListening should fail if start not called
,ok 227 specific error should be returned
,# teardown
,ok 228 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:37:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:37:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:37:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-08-02 13:37:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:37:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-02 13:37:52 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-02 13:37:52 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:37:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-02 13:37:52 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-02 13:37:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-02 13:37:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-02 13:37:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #stopListeningForAdvertisements many times
,2017-08-02 13:37:52 - DEBUG CoordinatedClient: 'test was skipped, name: 'should be able to call #stopListeningForAdvertisements many times''
,# teardown
,ok 229 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:37:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:37:52 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:37:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:37:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-08-02 13:37:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-02 13:37:52 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-02 13:37:52 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:37:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:37:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:37:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:37:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:37:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #startListeningForAdvertisements many times
,2017-08-02 13:37:52 - DEBUG thaliMobileNativeWrapper: 'listening 65459'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:05189449-5FFB-442F-8BEF-5E431171072C
[ThaliCore] Browser.startListening
,2017-08-02 13:37:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-02 13:37:52 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-02 13:37:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 230 no errors
,[ThaliCore] BrowserManager.startListeningForAdvertisements
2017-08-02 13:37:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-02 13:37:52 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-02 13:37:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 231 still no errors
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:38EB4510-C4BB-4339-8267-E8BFF2A630EC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "38EB4510-C4BB-4339-8267-E8BFF2A630EC", generation: 0)
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:00DC2AB4-228C-4A26-A795-434E1581F9F6:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "00DC2AB4-228C-4A26-A795-434E1581F9F6", generation: 0)
,2017-08-02 13:37:52 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"38EB4510-C4BB-4339-8267-E8BFF2A630EC","generation":0}]'
,2017-08-02 13:37:52 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"38EB4510-C4BB-4339-8267-E8BFF2A630EC","generation":0}'
,2017-08-02 13:37:52 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"00DC2AB4-228C-4A26-A795-434E1581F9F6","generation":0}]'
,2017-08-02 13:37:52 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"00DC2AB4-228C-4A26-A795-434E1581F9F6","generation":0}'
,2017-08-02 13:37:52 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"38EB4510-C4BB-4339-8267-E8BFF2A630EC","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-02 13:37:52 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"38EB4510-C4BB-4339-8267-E8BFF2A630EC","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-08-02 13:37:52 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"00DC2AB4-228C-4A26-A795-434E1581F9F6","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-02 13:37:52 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"00DC2AB4-228C-4A26-A795-434E1581F9F6","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:37:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-02 13:37:53 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-08-02 13:37:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-08-02 13:37:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:37:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:37:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 232 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-02 13:37:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:37:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:37:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:37:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:37:53 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-02 13:37:53 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-02 13:37:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:37:53 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:37:53 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:37:53 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:37:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:37:53 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-08-02 13:37:53 - DEBUG thaliMobileNativeWrapper: 'listening 65460'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "7556DA77-08E7-4AC8-961D-C8999A750908", generation: 0)
[ThaliCore] Advertiser.startA,dvertising with peerID:7556DA77-08E7-4AC8-961D-C8999A750908
2017-08-02 13:37:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-02 13:37:53 - INFO thaliMobile: 'Receive,d state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:3,7:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 233 no errors
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "7556DA77-08E7-4AC8-961D-C8999A750908", ge,n,eration: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:7556DA77-08E7-4AC8-961D-C8999A750908
2017-08-02 13:37:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-0,8-02 13:37:53 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":nu,ll,"networkType":null}})'
2017-08-02 13:37:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 234 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:7556DA77-08E7-4AC8-961D-C8999A750908
[ThaliCore] Advertiser.stopAdvertising() peerID:7556DA77-08E7-4AC8-961D-C8999A750908
2017-08-02 13:37:53 - DEBUG thaliMo,bileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:37:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stop,ListeningForAdvertisements()
2017-08-02 13:37:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:37:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-02 13:37:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 235 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:37:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:37:53 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:37:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:37:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:37:53 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-02 13:37:53 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-02 13:37:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:37:53 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:37:53 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:37:53 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:37:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:37:53 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #stopAdvertisingAndListening many times
,2017-08-02 13:37:53 - DEBUG thaliMobileNativeWrapper: 'listening 65463'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:37:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:37:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 236 no errors
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:37:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:37:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 237 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:37:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:37:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-02 13:37:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:37:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:37:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 238 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-02 13:37:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:37:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:37:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:37:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:37:53 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-02 13:37:53 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-02 13:37:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:37:53 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:37:53 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:37:53 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:37:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:37:53 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can get the network status before starting
,ok 239 network status should have certain non-empty properties
,# teardown
,ok 240 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-02 13:37:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:37:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:37:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:37:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:37:54 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-02 13:37:54 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-02 13:37:54 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:37:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-02 13:37:54 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-02 13:37:54 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-02 13:37:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-02 13:37:54 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# error returned with bad router
,2017-08-02 13:37:54 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a string'
ok 241 specific error expected
,# teardown
,ok 242 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:37:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:37:54 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:37:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-08-02 13:37:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:37:54 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-02 13:37:54 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-02 13:37:54 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:37:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-02 13:37:54 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-02 13:37:54 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-02 13:37:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-02 13:37:54 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# all services are started when we call start
,2017-08-02 13:37:54 - DEBUG thaliMobileNativeWrapper: 'listening 65464'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:469A04B7-02E0-4EE8-903A-8C1729AB1402
[ThaliCore] Browser.startListening
2017-08-02 13:37:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-02 13:37:54 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:37:54 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "6AF682A6-3BAD-46A6-AE61-C0F0A4CD82EF", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID,:,6AF682A6-3BAD-46A6-AE61-C0F0A4CD82EF
2017-08-02 13:37:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-08-02 13:37:54 - INFO thaliMobile: 'Received state ({"discoveryActi,ve":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:37:54 - INFO thaliMobile: ,'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 243 all connection succeed
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:00DC2AB4-228C-4A26-A795-434E1581F9F6:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "00DC2AB4-228C-4A26-A795-434E1581F9F6", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:38EB4510-C4BB-4339-8267-E8BFF2A630EC:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "38EB4510-C4BB-4339-8267-E8BFF2A630EC", generation: 0)
,2017-08-02 13:37:55 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"00DC2AB4-228C-4A26-A795-434E1581F9F6","generation":0}]'
2017-08-02 13:37:55 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"00DC2AB4-228C-4A26-A795-434E1581F9F6","generation":0}'
2017-08-02 13:37:55 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native, layer [{"peerAvailable":true,"peerIdentifier":"38EB4510-C4BB-4339-8267-E8BFF2A630EC","generation":0}]'
,2017-08-02 13:37:55 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"38EB4510-C4BB-4339-8267-E8BFF2A630EC","generation":0}'
,2017-08-02 13:37:55 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"00DC2AB4-228C-4A26-A795-434E1581F9F6","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-02 13:37:55 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"38EB4510-C4BB-4339-8267-E8BFF2A630EC","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:6AF682A6-3BAD-46A6-AE61-C0F0A4CD82EF
,2017-08-02 13:37:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-02 13:37:55 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-08-02 13:37:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-08-02 13:37:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:37:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:37:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 244 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-02 13:37:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:37:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:37:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:37:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:37:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-02 13:37:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-02 13:37:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:37:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:37:55 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:37:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:37:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:37:55 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# TCP Servers Manager should be null when we call start on iOS
,2017-08-02 13:37:55 - DEBUG thaliMobileNativeWrapper: 'listening 65467'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:8950B0E2-ABAC-4CC1-BCB0-85501FFCAAA6
[ThaliCore] Browser.st,artListening
2017-08-02 13:37:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-02 13:37:55 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:37:55 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "5F845E9D-0776-46D4-B2C1-1A6AFE00F8F1", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID,:,5F845E9D-0776-46D4-B2C1-1A6AFE00F8F1
2017-08-02 13:37:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-08-02 13:37:55 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:37:55 - INFO thaliMobile: ,'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 245 TCP Servers Manager doesn't exists
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:38EB4510-C4BB-4339-8267-E8BFF2A630EC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "38EB4510-C4BB-4339-8267-E8BFF2A630EC", generation: 0)
# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:00DC2AB4-228C-4A26-A795-434E1581F9F6:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "00DC2AB4-228C-4A26-A795-434E1581F9F6", generation: 0)
,2017-08-02 13:37:55 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"38EB4510-C4BB-4339-8267-E8BFF2A630EC","generation":0}]'
,2017-08-02 13:37:55 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"38EB4510-C4BB-4339-8267-E8BFF2A630EC","generation":0}'
,2017-08-02 13:37:55 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"00DC2AB4-228C-4A26-A795-434E1581F9F6","generation":0}]'
,2017-08-02 13:37:55 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"00DC2AB4-228C-4A26-A795-434E1581F9F6","generation":0}'
,2017-08-02 13:37:55 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"38EB4510-C4BB-4339-8267-E8BFF2A630EC","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-02 13:37:55 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"00DC2AB4-228C-4A26-A795-434E1581F9F6","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:5F845E9D-0776-46D4-B2C1-1A6AFE00F8F1
2017-08-02 13:37:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-02 13:37:55 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:37:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stop,Listening()
2017-08-02 13:37:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:37:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
2017-08-02 13:37:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 246 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:37:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:37:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:37:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:37:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:37:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-02 13:37:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-02 13:37:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:37:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:37:55 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:37:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:37:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:37:55 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# all services are stopped when we call stop
,2017-08-02 13:37:56 - DEBUG thaliMobileNativeWrapper: 'listening 65469'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:009AF876-08BB-4EB1-8C53-74155D40293A
[ThaliCore] Browser.st,artListening
2017-08-02 13:37:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-02 13:37:56 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:37:56 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "B44FDAD6-034A-45E4-8BE6-E4285868EC1E", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID,:,B44FDAD6-034A-45E4-8BE6-E4285868EC1E
2017-08-02 13:37:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-08-02 13:37:56 - INFO thaliMobile: 'Received state ({"discoveryActi,ve":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:37:56 - INFO thaliMobile: ,'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:B44FDAD6-034A-45E4-8BE6-E4285868EC1E
2017-08-02 13:37:56 - DEBUG thaliMobileNativeWrap,per: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-02 13:37:56 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"lis,t,ening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-02 13:37:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-08-02 13:37:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:37:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-02 13:37:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 247 is stopped after calling stop
,ok 248 connection should fail after stopping
,# teardown
,ok 249 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:37:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:37:56 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:37:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-08-02 13:37:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:37:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-02 13:37:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-02 13:37:56 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:37:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-02 13:37:56 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-02 13:37:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-02 13:37:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-02 13:37:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateConnection is properly hooked up
,2017-08-02 13:37:56 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateConnection is properly hooked up''
,# teardown
,ok 250 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:37:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:37:56 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:37:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-08-02 13:37:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:37:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-02 13:37:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-02 13:37:56 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:37:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-02 13:37:56 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-02 13:37:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-02 13:37:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-02 13:37:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateConnection is return error if we get called on iOS
,ok 251 error description matches
,# teardown
,ok 252 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:37:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:37:57 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:37:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-08-02 13:37:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:37:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-02 13:37:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-02 13:37:57 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:37:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-02 13:37:57 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-02 13:37:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-02 13:37:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:37:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is properly hooked up
,2017-08-02 13:37:57 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateListener is properly hooked up''
,# teardown
,ok 253 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:37:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:37:57 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:37:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-08-02 13:37:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:37:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-02 13:37:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-02 13:37:57 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:37:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-02 13:37:57 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-02 13:37:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-02 13:37:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-02 13:37:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is return error if we get called on iOS
,ok 254 error description matches
,# teardown
,ok 255 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:37:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:37:58 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:37:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:37:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-08-02 13:37:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-02 13:37:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-02 13:37:58 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:37:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-02 13:37:58 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-02 13:37:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-02 13:37:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
2017-08-02 13:37:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure we actually call kill connections properly
,ok 256 IMPLEMENT ME!!!!!!
,# teardown
,ok 257 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:37:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:37:58 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:37:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-08-02 13:37:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:37:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-02 13:37:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-02 13:37:58 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:37:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:37:58 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:37:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:37:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:37:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
,2017-08-02 13:37:58 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''
,# teardown
,ok 258 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:37:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:37:58 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:37:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-08-02 13:37:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:37:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-02 13:37:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-02 13:37:58 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:37:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-02 13:37:58 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-02 13:37:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-02 13:37:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
2017-08-02 13:37:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager
,2017-08-02 13:37:58 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''
,# teardown
,ok 259 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:37:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:37:58 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:37:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:37:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:37:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-02 13:37:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-02 13:37:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:37:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:37:58 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:37:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:37:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:37:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from multiConnectConnection
,2017-08-02 13:37:59 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 260 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:37:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:37:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:37:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:37:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:37:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-02 13:37:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-02 13:37:59 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:37:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-02 13:37:59 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-02 13:37:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-02 13:37:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-02 13:37:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection
,2017-08-02 13:37:59 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 261 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:37:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:37:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:37:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:37:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-08-02 13:37:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-02 13:37:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-02 13:37:59 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:37:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-02 13:37:59 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-02 13:37:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-02 13:37:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-02 13:37:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved
,ok 262 NOT IMPLEMENTED # SKIP
,# teardown
,ok 263 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:37:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:37:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:37:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:37:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-08-02 13:37:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-02 13:37:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-02 13:37:59 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:37:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-02 13:37:59 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-02 13:37:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-02 13:37:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-02 13:37:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure bad PSK connections fail
,2017-08-02 13:38:00 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure bad PSK connections fail''
,# teardown
,ok 264 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:38:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:38:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:38:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-08-02 13:38:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:38:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-02 13:38:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-02 13:38:00 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:38:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-02 13:38:00 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:38:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:38:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:38:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peer changes handled from a queue
,2017-08-02 13:38:00 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer changes handled from a queue''
,# teardown
,ok 265 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:38:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:38:00 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:38:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-08-02 13:38:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:38:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-02 13:38:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-02 13:38:00 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:38:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-02 13:38:00 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-08-02 13:38:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-02 13:38:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-02 13:38:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# relaying discoveryAdvertisingStateUpdateNonTCP
,2017-08-02 13:38:00 - DEBUG CoordinatedClient: 'test was skipped, name: 'relaying discoveryAdvertisingStateUpdateNonTCP''
,# teardown
,ok 266 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:38:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:38:00 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:38:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-08-02 13:38:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:38:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-02 13:38:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-02 13:38:00 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:38:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-02 13:38:00 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-02 13:38:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-02 13:38:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-02 13:38:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received
,2017-08-02 13:38:01 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''
,# teardown
,ok 267 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:38:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:38:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:38:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:38:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-08-02 13:38:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-02 13:38:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-02 13:38:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:38:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-02 13:38:01 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-02 13:38:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-02 13:38:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-02 13:38:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# we successfully receive and replay discoveryAdvertisingStateUpdate
,2017-08-02 13:38:01 - DEBUG thaliMobileNativeWrapper: 'listening 65472'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:B20E77E4-A4CF-47BA-9A0D-4FAAA3687A56
[ThaliCore] Browser.st,artListening
2017-08-02 13:38:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-02 13:38:01 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:38:01 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
ok 268 discoveryActive matches
ok 269 advertisingActive matches
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:38:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonT,C,P: {"discoveryActive":true,"advertisingActive":false}'
2017-08-02 13:38:01 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkT,ype":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:38:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisemen,ts()
[ThaliCore] Browser.stopListening()
2017-08-02 13:38:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:38:01 - INFO thaliMobile: 'Filtered out discoveryAd,vertisingStateUpdate (was in stopped state).'
ok 270 discoveryActive matches
ok 271 advertisingActive matches
,2017-08-02 13:38:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-02 13:38:01 - DEBUG thaliMobileNativeWrapper: 'listening 65473'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "99FC0D5D-E370-4973-B24E-16E7CF454103", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:99FC0D5D-E370-4973-B24E-16E7CF454103
,2017-08-02 13:38:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-02 13:38:01 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:38:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 272 discoveryActive matches
,ok 273 advertisingActive matches
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:99FC0D5D-E370-4973-B24E-16E7CF454103
,2017-08-02 13:38:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:38:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 274 discoveryActive matches
ok 275 advertisingActive matches
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-02 13:38:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:38:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:38:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-02 13:38:01 - DEBUG thaliMobileNativeWrapper: 'listening 65475'
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:38:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:38:01 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:38:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:38:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:38:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 276 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-02 13:38:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:38:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:38:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:38:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:38:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-02 13:38:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-02 13:38:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:38:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:38:01 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:38:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:38:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:38:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS
,2017-08-02 13:38:02 - DEBUG thaliMobileNativeWrapper: 'listening 65476'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:5B8B97C0-F7EB-41B4-9BA9-226E56D91A39
[ThaliCore] Browser.st,artListening
2017-08-02 13:38:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-02 13:38:02 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:38:02 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "B4214F04-2954-44F1-BCC5-45677AFEBDAC", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID,:,B4214F04-2954-44F1-BCC5-45677AFEBDAC
,2017-08-02 13:38:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-08-02 13:38:02 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-02 13:38:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:38EB4510-C4BB-4339-8267-E8BFF2A630EC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "38EB4510-C4BB-4339-8267-E8BFF2A630EC", generation: 0)
,2017-08-02 13:38:03 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"38EB4510-C4BB-4339-8267-E8BFF2A630EC","generation":0}]'
,2017-08-02 13:38:03 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"38EB4510-C4BB-4339-8267-E8BFF2A630EC","generation":0}'
,2017-08-02 13:38:03 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"38EB4510-C4BB-4339-8267-E8BFF2A630EC","peerAvailable":true,"generation":0,"portNumber":null}'
,ok 277 portNumber equal null
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CFE11449-403B-465C-8474-A0A7BD88124B:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CFE11449-403B-465C-8474-A0A7BD88124B", generation: 0)
,2017-08-02 13:38:03 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"CFE11449-403B-465C-8474-A0A7BD88124B","generation":0}]'
,2017-08-02 13:38:03 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"CFE11449-403B-465C-8474-A0A7BD88124B","generation":0}'
,2017-08-02 13:38:03 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"CFE11449-403B-465C-8474-A0A7BD88124B","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-02 13:38:03 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"CFE11449-403B-465C-8474-A0A7BD88124B","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5054820D-90EB-4D0B-9C85-F5A7951960E1:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5054820D-90EB-4D0B-9C85-F5A7951960E1", generation: 0)
,2017-08-02 13:38:03 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"5054820D-90EB-4D0B-9C85-F5A7951960E1","generation":0}]'
2017-08-02 13:38:03 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"5054820D-90EB-4D0B-9C85-F5A7951960E1","generation":0}'
,2017-08-02 13:38:03 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"5054820D-90EB-4D0B-9C85-F5A7951960E1","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-02 13:38:03 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5054820D-90EB-4D0B-9C85-F5A7951960E1","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:B4214F04-2954-44F1-BCC5-45677AFEBDAC
2017-08-02 13:38:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-08-02 13:38:03 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:38:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stop,Listening()
,2017-08-02 13:38:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:38:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
2017-08-02 13:38:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 278 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:38:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdate,NonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:38:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:38:03 - DEBUG thali,MobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:38:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-02 13:38:03 - DEBUG ,t,haliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-02 13:38:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-02 13:38:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:38:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:38:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:38:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:38:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:38:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can do HTTP requests between peers
,2017-08-02 13:38:04 - DEBUG CoordinatedClient: 'test was skipped, name: 'can do HTTP requests between peers''
,# teardown
,ok 279 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:38:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:38:04 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:38:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-08-02 13:38:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:38:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-02 13:38:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-02 13:38:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:38:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-02 13:38:04 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-02 13:38:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-02 13:38:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-02 13:38:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can still do HTTP requests between peers with coordinator
,2017-08-02 13:38:04 - DEBUG CoordinatedClient: 'test was skipped, name: 'can still do HTTP requests between peers with coordinator''
,# teardown
,ok 280 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:38:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:38:04 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:38:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-08-02 13:38:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:38:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-02 13:38:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-02 13:38:04 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:38:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:38:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:38:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:38:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:38:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calls correct starts when network changes
,2017-08-02 13:38:04 - DEBUG CoordinatedClient: 'test was skipped, name: 'calls correct starts when network changes''
,# teardown
,ok 281 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:38:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:38:04 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:38:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-08-02 13:38:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:38:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-02 13:38:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-02 13:38:04 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:38:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-02 13:38:04 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-02 13:38:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-02 13:38:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-02 13:38:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# test to coordinate connection cut
,# teardown
,ok 282 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:38:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:38:05 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:38:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-08-02 13:38:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:38:05 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-02 13:38:05 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-02 13:38:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:38:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-02 13:38:05 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-02 13:38:05 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-02 13:38:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-02 13:38:05 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can do HTTP requests after connections are cut
,2017-08-02 13:38:05 - DEBUG thaliMobileNativeWrapper: 'listening 65478'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:8FBFA9F4-57BE-4E10-B4BA-3AE4CF01E950
,[ThaliCore] Browser.startListening
,2017-08-02 13:38:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-02 13:38:05 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-08-02 13:38:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "B8B1B7E3-CFBF-4090-9ADB-F4833B9D6679", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:B8B1B7E3-CFBF-4090-9ADB-F4833B9D6679
,2017-08-02 13:38:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-08-02 13:38:05 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-02 13:38:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B8B1B7E3-CFBF-4090-9ADB-F4833B9D6679:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B8B1B7E3-CFBF-4090-9ADB-F4833B9D6679", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:75362F1E-B9D2-4EFB-AF5E-0D4E56228E2E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "75362F1E-B9D2-4EFB-AF5E-0D4E56228E2E", generation: 0)
2017-08-02 13:38:06 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"75362F1E-B9D2-4EFB-AF5E-0D4E56228E2E","generation":0}]'
2017-08-02 13:38:06 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"75362F1E-B9D2-4EFB-AF5E-0D4E56228E2E","generation":0}'
,2017-08-02 13:38:06 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"75362F1E-B9D2-4EFB-AF5E-0D4E56228E2E","peerAvailable":true,"generation":0,"portNumber":null}'
2017-08-02 13:38:06 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"75362F1E-B9D2-4EFB-AF5E-0D4E56228E2E","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-08-02 13:38:06 - DEBUG thaliMobileNativeTestUtils: 'We got a pe,er {"peerIdentifier":"75362F1E-B9D2-4EFB-AF5E-0D4E56228E2E","peerAvailable":true,"generation":0,"portNumber":null}'
2017-08-02 13:38:06 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 75362F1E-B9D2-4EFB-AF5E-0D4E56228E2E (syncValue: 0xRzKhya,Dd6uX1VIexcss89IJiwI6rKO)'
2017-08-02 13:38:06 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "75362F1E-B9D2-4EFB-AF5E-0D4E56228E2E", generation: ,0,) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "75362F1E-B9D2-4EFB-AF5E-0D4E56228E2E", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:75362F1E-B9D2-,4EFB-AF5E-0D4E56228E2E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5F9B6F57-AB39-4527-81DB-C997CCB7CD5C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5F9B6F57-AB39-4527-81DB-C997CCB7CD5C", generation: 0)
2017-08-02 13:38:06 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"5F9B6F57-AB39-4527-81DB-C997CCB7CD5C","generation":0}]'
2017-08-02 13:38:06 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"5F9B6F57-AB39-4527-81DB-C997CCB7CD5C","generation":0}'
,2017-08-02 13:38:06 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"5F9B6F57-AB39-4527-81DB-C997CCB7CD5C","peerAvailable":true,"generation":0,"portNumber":null}'
2017-08-02 13:38:06 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5F9B6F57-AB39-4527-81DB-C997CCB7CD5C","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-08-02 13:38:06 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"5F9B6F57-AB39-4527-81DB-C997CCB7CD5C","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:75362F1E-B9D2-4EFB-AF5E-0D4E56228E2E:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:75362F1E-B9D2-4EFB-AF5E-0D4E56228E2E:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:75362F1E-B9D2-4EFB-AF5E-0D4E56228E2E:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "75362F1E-B9D2-4EFB-AF5E-0D4E56228E2E", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:65481
2017-08-02 13:38:09 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"0xRzKhyaDd6uX1VIexcss89IJiwI6rKO",,"error":null,"portNumber":65481}'
2017-08-02 13:38:09 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '0xRzKhyaDd6uX1VIexcss89IJiwI6rKO', error: 'null', listeningPort: '65481''
2017-08-02 13:38:09 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:75362F1E-B9D2-4EFB-AF5E-0D4E56228E2E:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:75362F1E-B9D2-4EFB-AF5E-0D4E56228E2E:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:11 [3, 5, 11]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-08-02 13:38:10 - DEBUG testUtils: 'Got response data'
,2017-08-02 13:38:10 - DEBUG testUtils: 'Got end'
,ok 283 response body should match testData
,ok 284 must be started
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:11F2F362-6C64-4861-9AB3-DD113F00BD29
[ThaliCore] Advertiser: session connected Peer(uuid: "B8B1B7E3-CFBF-4090-9ADB-F4833B9D6679", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:11F2F362-6C64-4861-9AB3-DD113F00BD29 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:11F2F362-6C64-4861-9AB3-DD113F00BD29
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B2A3826C-A35E-4C46-B429-74AFA0F4C0FD
[ThaliCore] Advertiser: session connected Peer(uuid: "B8B1B7E3-CFBF-4090-9ADB-F4833B9D6679", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:B2A3826C-A35E-4C46-B429-74AFA0F4C0FD state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:11F2F362-6C64-4861-9AB3-DD113F00BD29 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:11F2F362-6C64-4861-9AB3-DD113F00BD29
[ThaliCore] Session.startOutputStream(with:) peer:11F2F362-6C64-4861-9AB3-DD113F00BD29
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:12 [3, 5, 11, 12]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B2A3826C-A35E-4C46-B429-74AFA0F4C0FD
,[ThaliCore] Session.session(_:peer:didChange:) peer:B2A3826C-A35E-4C46-B429-74AFA0F4C0FD state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B2A3826C-A35E-4C46-B429-74AFA0F4C0FD
[ThaliCore] Session.startOutputStream(with:) peer:B2A3826C-A35E-4C46-B429-74AFA0F4C0FD
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:13 [3, 5, 11, 12, 13]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:13
[ThaliCore] VirtualSocket.closeStreams() vsID:13
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:,13
[ThaliCore] VirtualSocket.deinit vsID:13 [3, 5, 11, 12]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:peer:didChange:) peer:B2A3826C-A35E-4C46-B429-74AFA0F4C0FD state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "B8B1B7E3-CFBF-4090-9ADB-F4833B9D6679", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:B2A3826C-A35E-4C46-B429-74AFA0F4C0FD
[ThaliCore] Advert,iserRelay.deinit
,[ThaliCore] Session.deinit peer:B2A3826C-A35E-4C46-B429-74AFA0F4C0FD
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:11
[ThaliCore] VirtualSocket.closeStreams() vsID:11
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] VirtualSocket exited RunLoop vsID:11
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] VirtualSocket.deinit vsID:11 [3, 5, 12]
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:B8B1B7E3-CFBF-4090-9ADB-F4833B9D6679
2017-08-02 13:38:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-08-02 13:38:17 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:38:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-02 13:38:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:38:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in s,topped state).'
2017-08-02 13:38:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 285 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:38:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:38:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:38:17 ,- DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:38:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidD,isconnect(_:withError:) client disconnected
[ThaliCore] BrowserManager.disconnect peer:75362F1E-B9D2-4EFB-AF5E-0D4E56228E2E
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:12
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:65481
[ThaliCore] VirtualSocket.closeStreams() vsID:12
[ThaliCore] Session.disconnect() peer:75362F1E-B9D2-4EFB-AF5E-0D4E56228E2E:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:12
[ThaliCore] VirtualSocket.deinit vsID:12 [3, 5]
,[ThaliCore] Session.deinit peer:75362F1E-B9D2-4EFB-AF5E-0D4E56228E2E:0
,[ThaliCore] BrowserRelay.deinit
,2017-08-02 13:38:17 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-02 13:38:17 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-02 13:38:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:38:17 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:38:17 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-08-02 13:38:17 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:38:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:38:17 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:11F2F362-6C64-4861-9AB3-DD113F00BD29 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "B8B1B7E3-CFBF-4090-9ADB-F4833B9D6679", generation: 0)
,# will fail bad PSK connection between peers
,ok 286 FIX ME, PLEASE!!!
,# teardown
,ok 287 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-02 13:38:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:38:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:38:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:38:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:38:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-02 13:38:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-02 13:38:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:38:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:38:18 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:38:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:38:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:38:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We provide notification when a listener dies and we recreate it
,2017-08-02 13:38:19 - DEBUG CoordinatedClient: 'test was skipped, name: 'We provide notification when a listener dies and we recreate it''
,# teardown
,ok 288 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:38:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:38:19 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:38:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-08-02 13:38:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:38:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-02 13:38:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-02 13:38:19 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:38:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-02 13:38:19 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-02 13:38:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-02 13:38:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-02 13:38:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated
,2017-08-02 13:38:19 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated''
,# teardown
,ok 289 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:38:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:38:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:38:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:38:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-08-02 13:38:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-02 13:38:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-02 13:38:19 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:38:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-02 13:38:19 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-02 13:38:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-02 13:38:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-02 13:38:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,ok 290 ThaliMobile should be stopped
,# #startListeningForAdvertisements should fail if start not called
,ok 291 specific error should be returned
,# teardown
,2017-08-02 13:38:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"38EB4510-C4BB-4339-8267-E8BFF2A630EC","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-08-02, 13:38:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"00DC2AB4-228C-4A26-A795-434E1581F9F6","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-08-02 13:38:20 ,- DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"CFE11449-403B-465C-8474-A0A7BD88124B","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-08-02 13:38:20 - DEBUG th,aliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"5054820D-90EB-4D0B-9C85-F5A7951960E1","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-08-02 13:38:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"75362F1E-B9D2-4EFB-AF5E-0D4E56228E2E","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-08-02, 13:38:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"5F9B6F57-AB39-4527-81DB-C997CCB7CD5C","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 292 error should be null
ok 293 error should be null
,# setup
,ok 294 ThaliMobile should be stopped
,# #startUpdateAdvertisingAndListening should fail if start not called
,ok 295 specific error should be returned
,# teardown
,ok 296 error should be null
ok 297 error should be null
,# setup
,ok 298 ThaliMobile should be stopped
,# should be able to call #stopListeningForAdvertisements many times
,2017-08-02 13:38:20 - DEBUG thaliMobileNativeWrapper: 'listening 65485'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:38:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"ad,vertisingActive":false}'
ok 299 error should be null
ok 300 error should be null
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:38:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive,":false,"advertisingActive":false}'
ok 301 error should be null
ok 302 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:38:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:38:20 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-02 13:38:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:38:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
2017-08-02 13:38:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 303 error should be null
ok 304 error should be null
,# setup
,ok 305 ThaliMobile should be stopped
,# should be able to call #startListeningForAdvertisements many times
,2017-08-02 13:38:20 - DEBUG thaliMobileNativeWrapper: 'listening 65486'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:80F88E50-963E-4D27-AE97-8172CB36CEF5
,[ThaliCore] Browser.startListening
,2017-08-02 13:38:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,ok 306 error should be null
,ok 307 error should be null
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-08-02 13:38:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,ok 308 error should be null
,ok 309 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:38:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-02 13:38:21 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
,2017-08-02 13:38:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-08-02 13:38:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:38:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:38:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 310 error should be null
,ok 311 error should be null
,# setup
,ok 312 ThaliMobile should be stopped
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-08-02 13:38:21 - DEBUG thaliMobileNativeWrapper: 'listening 65487'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "26806305-D217-441C-B1F7-7BC878CE9AD6", generation: 0)
[ThaliCore] Advertiser.startA,dvertising with peerID:26806305-D217-441C-B1F7-7BC878CE9AD6
2017-08-02 13:38:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 313 error should be null
ok 314 error should, be null
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "26806305-D217-441C-B1F7-7BC878CE9AD6", generation: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:26806305-D217-441C-B1F7-7BC878CE9AD6
20,17-08-02 13:38:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 315 error should be null
ok 316 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:26806305-D217-441C-B1F7-7BC878CE9AD6
[ThaliCore] Advertiser.stopAdvertising() peerID:26806305-D217-441C-B1F7-7BC878CE9AD6
2017-08-02 13:38:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:38:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:38:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:38:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-02 13:38:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 317 error should be null
ok 318 error should be null
,# setup
,ok 319 ThaliMobile should be stopped
,# should be able to call #stopAdvertisingAndListening many times
,2017-08-02 13:38:21 - DEBUG thaliMobileNativeWrapper: 'listening 65490'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:38:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingAct,ive":false}'
ok 320 error should be null
ok 321 error should be null
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:38:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActi,ve":false}'
,ok 322 error should be null
ok 323 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:38:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:38:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:38:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:38:22 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-02 13:38:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 324 error should be null
ok 325 error should be null
,# setup
,ok 326 ThaliMobile should be stopped
,# #start - Causing native or wifi to fail will cause a promise reject 
,2017-08-02 13:38:22 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a Null'
,ok 327 This should not cause wifi to fail
ok 328 native router should be bad
,# teardown
,ok 329 error should be null
ok 330 error should be null
,# setup
,ok 331 ThaliMobile should be stopped
,# #start should fail if called twice in a row
,2017-08-02 13:38:22 - DEBUG thaliMobileNativeWrapper: 'listening 65491'
ok 332 first call should succeed
ok 333 first call should succeed
ok 334 specific error should be returned
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:38:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:38:22 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:38:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-08-02 13:38:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-02 13:38:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 335 error should be null
ok 336 error should be null
,# setup
,ok 337 ThaliMobile should be stopped
,# #start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)
,2017-08-02 13:38:23 - DEBUG CoordinatedClient: 'test was skipped, name: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''
,# teardown
,ok 338 error should be null
ok 339 error should be null
,# setup
,ok 340 ThaliMobile should be stopped
,# does not emit duplicate discoveryAdvertisingStateUpdate
,2017-08-02 13:38:23 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not emit duplicate discoveryAdvertisingStateUpdate''
,# teardown
,ok 341 error should be null
,ok 342 error should be null
,# setup
,ok 343 ThaliMobile should be stopped
,# does not send duplicate availability changes
,2017-08-02 13:38:23 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"22d835b5-f24d-443e-896a-2b6af5a1bb51","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 344 should be called once
,ok 345 should not have been called more than once
,# teardown
,2017-08-02 13:38:23 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"22d835b5-f24d-443e-896a-2b6af5a1bb51","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 346 error should be null
,ok 347 error should be null
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
2017-08-02 13:38:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"200bf63e-4550-4ebb-b851-eea28264f23a","connectionType":"MPCF","peerAvailable":true,"generation":0,,"newAddressPort":false}'
ok 354 peer should be available
ok 355 cache contains native peer
2017-08-02 13:38:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"200bf63e-4550-4ebb-b851-eea28264f23a","connectionTyp,e":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
ok 356 peer should be unavailable
ok 357 peer has been removed from cache
,# teardown
,ok 358 error should be null
ok 359 error should be null
,# setup
,ok 360 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer added/removed to/from cache (wifi)
,ok 361 we have not added peer to the cache yet
,2017-08-02 13:38:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"c995dc13-6072-495a-a1cf-bd1c73d08a20","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 362 peer should be a,vailable
ok 363 cache contains wifi peer
2017-08-02 13:38:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"c995dc13-6072-495a-a1cf-bd1c73d08a20","connectionType":"tcp","peerAvailable":false,"generation":0,"newA,ddressPort":null}'
ok 364 peer should be unavailable
ok 365 peer has been removed from cache
,# teardown
,ok 366 error should be null
ok 367 error should be null
,# setup
,ok 368 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored
,2017-08-02 13:38:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"4239ac59-79d6-40f9-b314-559a52a67f97","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 369 first peer is a,vailable
2017-08-02 13:38:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"2934d21f-9ba7-4b85-aa90-0b0f247730eb","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 370 second, peer is available
ok 371 first and second peers are different
,# teardown
,2017-08-02 13:38:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"4239ac59-79d6-40f9-b314-559a52a67f97","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-08-02, 13:38:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"2934d21f-9ba7-4b85-aa90-0b0f247730eb","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 372 error should be null
ok 373 error should be null
,# setup
,ok 374 ThaliMobile should be stopped
,# native available - new peer is cached
,ok 375 should not be in cache at start
2017-08-02 13:38:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5ee36e83-36dd-47a8-8147-95c921b846da","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddr,essPort":false}'
,ok 376 peer is available
,# teardown
,2017-08-02 13:38:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"5ee36e83-36dd-47a8-8147-95c921b846da","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 377 error should be null
,ok 378 error should be null
,# setup
,ok 379 ThaliMobile should be stopped
,# native available - peer with same port and different generation is cached (BLUETOOTH)
,2017-08-02 13:38:25 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with same port and different generation is cached (BLUETOOTH)''
,# teardown
,ok 380 error should be null
ok 381 error should be null
,# setup
,ok 382 ThaliMobile should be stopped
,# native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)
,2017-08-02 13:38:25 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)''
,# teardown
,ok 383 error should be null
,ok 384 error should be null
,# setup
,ok 385 ThaliMobile should be stopped
,# native available - peer with greater generation is cached (MPCF)
,2017-08-02 13:38:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1bd37e19-53ad-478a-adb6-c28cbb41442e","connectionType":"MPCF","peerAvailable":true,"generation":2,"newAddressPort":false}'
ok 386 peer should be ,available
,2017-08-02 13:38:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1bd37e19-53ad-478a-adb6-c28cbb41442e","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
ok 387 peer should be available
ok 388 should store correct generation
,# teardown
,2017-08-02 13:38:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"1bd37e19-53ad-478a-adb6-c28cbb41442e","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 389 error should be null
ok 390 error should be null
,# setup
,ok 391 ThaliMobile should be stopped
,# native available - peer with same or older generation is ignored (MPCF)
,2017-08-02 13:38:26 - DEBUG thaliMobileNativeWrapper: 'listening 65492'
2017-08-02 13:38:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"2b4a8212-69d0-441e-bffd-3f46ea8ffb0a","connectionType":"MPCF","peerAvaila,ble":true,"generation":2,"newAddressPort":false}'
ok 392 discovered correct peer
ok 393 got correct generation
,2017-08-02 13:38:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"2b4a8212-69d0-441e-bffd-3f46ea8ffb0a","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
ok 394 discovered corr,ect peer
ok 395 got correct generation
,# teardown
,2017-08-02 13:38:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"2b4a8212-69d0-441e-bffd-3f46ea8ffb0a","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:38:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:38:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:38:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpd,ateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:38:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-02 13:38:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server',
,ok 396 error should be null
ok 397 error should be null
,# setup
,ok 398 ThaliMobile should be stopped
,# native unavailable - new peer is ignored
,2017-08-02 13:38:27 - DEBUG thaliMobileNativeWrapper: 'listening 65493'
,2017-08-02 13:38:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"077fc67f-679d-48d1-99db-db51f50a38a0","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 399 discovered avai,lable peer
ok 400 peer is available
,# teardown
,2017-08-02 13:38:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"077fc67f-679d-48d1-99db-db51f50a38a0","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore,] AdvertiserManager.stopAdvertising()
2017-08-02 13:38:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:38:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:38:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpd,ateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:38:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-02 13:38:27 - DEBUG makeIntoCloseAllServer: 'closeAll called on server',
,ok 401 error should be null
ok 402 error should be null
,# setup
,ok 403 ThaliMobile should be stopped
,# native unavailable - cached peer is removed
,2017-08-02 13:38:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"003c070f-ba28-43b5-b9ad-7c3d981cb71c","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 404 peer should be ,available
,2017-08-02 13:38:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"003c070f-ba28-43b5-b9ad-7c3d981cb71c","connectionType":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
ok 405 peer should be unavailable
ok 406 should be removed from cache
,# teardown
,ok 407 error should be null
ok 408 error should be null
,# setup
,ok 409 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for wifi peers
,2017-08-02 13:38:27 - DEBUG thaliMobileNativeWrapper: 'listening 65494'
2017-08-02 13:38:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"39d26b26-b23e-4d4b-b979-c3ab455b3dbf","connectionType":"MPCF","peerAvaila,ble":true,"generation":0,"newAddressPort":false}'
ok 410 first peer is expected to be available
2017-08-02 13:38:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"8d4768e1-c08e-41bc-a548-ac069e5d3bee","connectio,nType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 411 second peer is expected to be available
2017-08-02 13:38:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"8d4768e1-c08e-,41bc-a548-ac069e5d3bee","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 412 peer became unavailable
,ok 413 it was wifi peer
,2017-08-02 13:38:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"8d4768e1-c08e-41bc-a548-ac069e5d3bee","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 414 we found peer again
,ok 415 it was wifi peer
,2017-08-02 13:38:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"8d4768e1-c08e-41bc-a548-ac069e5d3bee","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 416 peer became unavailable
,ok 417 it was wifi peer
,# teardown
,2017-08-02 13:38:28 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"39d26b26-b23e-4d4b-b979-c3ab455b3dbf","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:38:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:38:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-02 13:38:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:38:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:38:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 418 error should be null
,ok 419 error should be null
,# setup
,ok 420 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)
,2017-08-02 13:38:28 - DEBUG CoordinatedClient: 'test was skipped, name: 'networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)''
,# teardown
,ok 421 error should be null
,ok 422 error should be null
,# setup
,ok 423 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)
,2017-08-02 13:38:28 - DEBUG thaliMobileNativeWrapper: 'listening 65495'
2017-08-02 13:38:28 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"0aeb0c68-e264-4176-9014-b0a0e1fef088","connectionType":"MPCF","peerAvaila,ble":true,"generation":0,"newAddressPort":false}'
ok 424 first peer is expected to be available
2017-08-02 13:38:28 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"abd4b9ff-cccb-46c4-9150-b0442c840ef3","connectio,nType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 425 second peer is expected to be available
,2017-08-02 13:38:28 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"0aeb0c68-e264-4176-9014-b0a0e1fef088","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 426 pee,r became unavailable
2017-08-02 13:38:28 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"abd4b9ff-cccb-46c4-9150-b0442c840ef3","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPor,t":null}'
ok 427 peer became unavailable
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:38:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:38:28 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-02 13:38:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:38:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:38:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 428 error should be null
,ok 429 error should be null
,# setup
,ok 430 ThaliMobile should be stopped
,# multiconnect failure - new peer is ignored (MPCF)
,2017-08-02 13:38:28 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - new peer is ignored (MPCF)''
,# teardown
,ok 431 error should be null
ok 432 error should be null
,# setup
,ok 433 ThaliMobile should be stopped
,# multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)
,2017-08-02 13:38:28 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''
,# teardown
,ok 434 error should be null
ok 435 error should be null
,# setup
,ok 436 ThaliMobile should be stopped
,# newAddressPort field (TCP_NATIVE)
,2017-08-02 13:38:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"4e2c05cf-f953-4939-9281-3f229e19d3f0","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 437 peer discovered first time does not have new address
2017-08-02 13:38:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"4e2c05cf-f953-4939-9281-3f229e19d3f0","connectionType":"tcp","peerAvailable":true,"ge,neration":20,"newAddressPort":false}'
ok 438 address has not been changed
2017-08-02 13:38:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"4e2c05cf-f953-4939-9281-3f229e19d3f0","connectionType":"tcp","peerAvai,lable":true,"generation":20,"newAddressPort":true}'
ok 439 new port handled correctly
2017-08-02 13:38:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"4e2c05cf-f953-4939-9281-3f229e19d3f0","connectionType":"tc,p","peerAvailable":true,"generation":20,"newAddressPort":true}'
ok 440 new host handled correctly
2017-08-02 13:38:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"4e2c05cf-f953-4939-9281-3f229e19d3f0","connec,t,ionType":"tcp","peerAvailable":false,"generation":20,"newAddressPort":null}'
ok 441 newAddressPort is null for unavailable peers
,# teardown
,ok 442 error should be null
ok 443 error should be null
,# setup
,ok 444 ThaliMobile should be stopped
,# newAddressPort field (BLUETOOTH)
,2017-08-02 13:38:29 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort field (BLUETOOTH)''
,# teardown
,ok 445 error should be null
ok 446 error should be null
,# setup
,ok 447 ThaliMobile should be stopped
,# newAddressPort field (MPCF)
,ok 448 NOT IMPLEMENTED # SKIP
,# teardown
,ok 449 error should be null
,ok 450 error should be null
,# setup
,ok 451 ThaliMobile should be stopped
,# newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)
,2017-08-02 13:38:30 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)''
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
,2017-08-02 13:38:31 - DEBUG CoordinatedClient: 'test was skipped, name: '#getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)''
,# teardown
,ok 459 error should be null
,ok 460 error should be null
,# setup
,ok 461 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)
,2017-08-02 13:38:31 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 462 contains expected properties
ok 463 the same hostAddress
ok 464 the same portNumber
,# teardown
,2017-08-02 13:38:31 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 465 error should be null
ok 466 error should be null
,# setup
,ok 467 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached wifi peer
,2017-08-02 13:38:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 468 contains expected properties
ok 469 the same hostAddress
ok 470 the same portNumber
,# teardown
,2017-08-02 13:38:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 471 error should be null
ok 472 error should be null
,# setup
,ok 473 ThaliMobile should be stopped
,# #disconnect fails on wifi peers
,2017-08-02 13:38:32 - DEBUG thaliMobileNativeWrapper: 'listening 65496'
2017-08-02 13:38:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"b4438b35-a0a0-4c4e-bec8-37b96579d131","connectionType":"tcp","peerAvailab,le":true,"generation":0,"newAddressPort":false}'
ok 474 Got specific error message
,# teardown
,2017-08-02 13:38:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"b4438b35-a0a0-4c4e-bec8-37b96579d131","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore], AdvertiserManager.stopAdvertising()
2017-08-02 13:38:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:38:32 - INFO thaliMobile: 'Filtered out discoveryAdverti,singStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:38:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-,08-02 13:38:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-02 13:38:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 475 error should be null
ok 476 error should be null
,# setup
,ok 477 ThaliMobile should be stopped
,# #disconnect delegates native peers to the native wrapper
,2017-08-02 13:38:32 - DEBUG thaliMobileNativeWrapper: 'listening 65497'
2017-08-02 13:38:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"a96e59fd-d97e-48cf-8e4c-81de012a1fbe","connectionType":"MPCF","peerAvaila,ble":true,"generation":0,"newAddressPort":false}'
[ThaliCore] BrowserManager.disconnect peer:a96e59fd-d97e-48cf-8e4c-81de012a1fbe
ok 478 native wrapper `disconnect` called once
ok 479 native wrapper `disconnect` called with peer data
,# teardown
,2017-08-02 13:38:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"a96e59fd-d97e-48cf-8e4c-81de012a1fbe","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore,] AdvertiserManager.stopAdvertising()
2017-08-02 13:38:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:38:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:38:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpd,ateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:38:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-02 13:38:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server',
,ok 480 error should be null
,ok 481 error should be null
,# setup
,ok 482 ThaliMobile should be stopped
,# network changes emitted correctly
,2017-08-02 13:38:32 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes emitted correctly''
,# teardown
,ok 483 error should be null
ok 484 error should be null
,# setup
,ok 485 ThaliMobile should be stopped
,# network changes not emitted in started state
,2017-08-02 13:38:33 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes not emitted in started state''
,# teardown
,ok 486 error should be null
ok 487 error should be null
,# setup
,ok 488 ThaliMobile should be stopped
,# network changes not emitted in stopped state
,2017-08-02 13:38:33 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes not emitted in stopped state''
,# teardown
,ok 489 error should be null
ok 490 error should be null
,# setup
,ok 491 ThaliMobile should be stopped
,# We properly fire peer unavailable and then available when connection fails on Android
,2017-08-02 13:38:33 - DEBUG CoordinatedClient: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on Android''
,# teardown
,ok 492 error should be null
ok 493 error should be null
,# setup
,ok 494 ThaliMobile should be stopped
,# We properly fire peer unavailable and then available when connection fails on iOS
,2017-08-02 13:38:33 - DEBUG CoordinatedClient: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on iOS''
,# teardown
,ok 495 error should be null
ok 496 error should be null
,# setup
,ok 497 ThaliMobile should be stopped
,# If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen
,2017-08-02 13:38:34 - DEBUG CoordinatedClient: 'test was skipped, name: 'If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen''
,# teardown
,ok 498 error should be null
ok 499 error should be null
,# setup
,ok 500 ThaliMobile should be stopped
,# does not fire duplicate events after peer listener recreation
,2017-08-02 13:38:34 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not fire duplicate events after peer listener recreation''
,# teardown
,ok 501 error should be null
ok 502 error should be null
,# setup
,ok 503 ThaliMobile should be stopped
,# #stop should change peers
,2017-08-02 13:38:34 - DEBUG thaliMobileNativeWrapper: 'listening 65498'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:7FFBEA04-0DCA-4977-B897-A5177AD5331E
,[ThaliCore] Browser.startListening
,2017-08-02 13:38:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-02 13:38:34 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"6cf24cce-47a8-4b5c-b05b-8879866bfb42","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 504 Peer availabilities has one entry for our connection type
,2017-08-02 13:38:34 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"63b87001-25e6-4a30-aaaf-687acc26e495","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 505 Peer availabilities has one entry for our connection type
,2017-08-02 13:38:34 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"6cf24cce-47a8-4b5c-b05b-8879866bfb42","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-08-02 13:38:34 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"63b87001-25e6-4a30-aaaf-687acc26e495","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:38:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-02 13:38:34 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"pskIdToSecret":[102,111,111],"networkType":"BOTH"}})'
,2017-08-02 13:38:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-08-02 13:38:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:38:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:38:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-02 13:38:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 506 No peers
,ok 507 No peers
,ok 508 No peers
,# teardown
,ok 509 error should be null
ok 510 error should be null
,# setup
,ok 511 ThaliMobile should be stopped
,# If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted
,2017-08-02 13:38:35 - DEBUG thaliMobileNativeWrapper: 'listening 65499'
,2017-08-02 13:38:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"d808fcbd-e65b-4bd6-baff-c964d0baa973","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 512 1
,ok 513 2
,2017-08-02 13:38:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"c088aaab-a8a9-4fc6-b824-c8e1601a3cb6","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,# teardown
,2017-08-02 13:38:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"d808fcbd-e65b-4bd6-baff-c964d0baa973","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-08-02 13:38:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"c088aaab-a8a9-4fc6-b824-c8e1601a3cb6","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:38:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:38:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-02 13:38:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:38:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:38:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 514 error should be null
,ok 515 error should be null
,# setup
,ok 516 ThaliMobile should be stopped
,# peer should be found once after listening and discovery started
,2017-08-02 13:38:36 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer should be found once after listening and discovery started''
,# teardown
,ok 517 error should be null
ok 518 error should be null
,# setup
,ok 519 ThaliMobile should be stopped
,# can get data from all participants
,2017-08-02 13:38:36 - DEBUG thaliMobileNativeWrapper: 'listening 65500'
ok 520 error should be null
ok 521 error should be null
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "8B2DDBB7-B3DF-467C-B63F-625FA51822DC", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:8B2DDBB7-B3DF-467C-B63F-625FA51822DC
2017-08-02 13:38:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive,":true}'
ok 522 error should be null
ok 523 error should be null
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C421471F-9A7D-45A4-AB76-3A9780512700
[ThaliCore] Browser.startLi,stening
2017-08-02 13:38:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
ok 524 error should be null
,ok 525 error should be null
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5F9B6F57-AB39-4527-81DB-C997CCB7CD5C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5F9B6F57-AB39-4527-81DB-C997CCB7CD5C", generation: 0)
,2017-08-02 13:38:36 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"5F9B6F57-AB39-4527-81DB-C997CCB7CD5C","generation":0}]'
,2017-08-02 13:38:36 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"5F9B6F57-AB39-4527-81DB-C997CCB7CD5C","generation":0}'
,2017-08-02 13:38:36 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"5F9B6F57-AB39-4527-81DB-C997CCB7CD5C","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-02 13:38:36 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5F9B6F57-AB39-4527-81DB-C997CCB7CD5C","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-08-02 13:38:36 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 5F9B6F57-AB39-4527-81DB-C997CCB7CD5C (syncValue: 0)'
,2017-08-02 13:38:36 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5F9B6F57-AB39-4527-81DB-C997CCB7CD5C", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5F9B6F57-AB39-4527-81DB-C997CCB7CD5C", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5F9B6F57-AB39-4527-81DB-C997CCB7CD5C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:22C031AA-D4EE-4D0C-A5BD-075CA882B9C4
[ThaliCore] Advertiser: session connected Peer(uuid: "8B2DDBB7-B3DF-467C-B63F-625FA51822DC", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:22C031AA-D4EE-4D0C-A5BD-075CA882B9C4 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8B2DDBB7-B3DF-467C-B63F-625FA51822DC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8B2DDBB7-B3DF-467C-B63F-625FA51822DC", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8222BD6A-6049-42EA-8E3E-EADA99C64585:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8222BD6A-6049-42EA-8E3E-EADA99C64585", generation: 0)
,2017-08-02 13:38:37 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"8222BD6A-6049-42EA-8E3E-EADA99C64585","generation":0}]'
,2017-08-02 13:38:37 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"8222BD6A-6049-42EA-8E3E-EADA99C64585","generation":0}'
,2017-08-02 13:38:37 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"8222BD6A-6049-42EA-8E3E-EADA99C64585","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-02 13:38:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"8222BD6A-6049-42EA-8E3E-EADA99C64585","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1FFD57F3-189F-4C51-9BD0-1F96D486CC8B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1FFD57F3-189F-4C51-9BD0-1F96D486CC8B", generation: 0)
2017-08-02 13:38:38 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"1FFD57F3-189F-4C51-9BD0-1F96D486CC8B","generation":0}]'
2017-08-02 13:38:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"1FFD57F3-189F-4C51-9BD0-1F96D486CC8B","generation":0}'
,2017-08-02 13:38:38 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"1FFD57F3-189F-4C51-9BD0-1F96D486CC8B","peerAvailable":true,"generation":0,"portNumber":null}'
2017-08-02 13:38:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1FFD57F3-189F-4C51-9BD0-1F96D486CC8B","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:5F9B6F57-AB39-4527-81DB-C997CCB7CD5C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:5F,9B6F57-AB39-4527-81DB-C997CCB7CD5C:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "5F9B6F57-AB39-4527-81DB-C997CCB7CD5C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,F9B6F57-AB39-4527-81DB-C997CCB7CD5C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5F9B6F57-AB39-4527-81DB-C997CCB7CD5C", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:5F9B6F57-AB39-4527-81DB-C997CCB7CD5C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:5F9B6F57-AB39-4527-81DB-C997CCB7CD5C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:22C031AA-D4EE-4D0C-A5BD-075CA882B9C4
,[ThaliCore] Session.session(_:peer:didChange:) peer:22C031AA-D4EE-4D0C-A5BD-075CA882B9C4 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:22C031AA-D4EE-4D0C-A5BD-075CA882B9C4
[ThaliCore] Session.startOutputStream(with:) peer:22C031AA-D4EE-4D0C-A5BD-075CA882B9C4
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,4 [3, 5, 14]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:5F9B6F57-AB39-4527-81DB-C997CCB7CD5C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:5F,9B6F57-AB39-4527-81DB-C997CCB7CD5C:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "5F9B6F57-AB39-4527-81DB-C997CCB7CD5C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,F9B6F57-AB39-4527-81DB-C997CCB7CD5C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5F9B6F57-AB39-4527-81DB-C997CCB7CD5C", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:5F9B6F57-AB39-4527-81DB-C997CCB7CD5C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:5F9B6F57-AB39-4527-81DB-C997CCB7CD5C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:5F9B6F57-AB39-4527-81DB-C997CCB7CD5C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:5F,9B6F57-AB39-4527-81DB-C997CCB7CD5C:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "5F9B6F57-AB39-4527-81DB-C997CCB7CD5C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,F9B6F57-AB39-4527-81DB-C997CCB7CD5C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5F9B6F57-AB39-4527-81DB-C997CCB7CD5C", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:5F9B6F57-AB39-4527-81DB-C997CCB7CD5C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:5F9B6F57-AB39-4527-81DB-C997CCB7CD5C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:5F9B6F57-AB39-4527-81DB-C997CCB7CD5C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:5F,9B6F57-AB39-4527-81DB-C997CCB7CD5C:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "5F9B6F57-AB39-4527-81DB-C997CCB7CD5C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:5F9B6F57,-AB39-4527-81DB-C997CCB7CD5C error: max retries exceeded
2017-08-02 13:38:47 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"0","error":"Connection could not be established","portNumber":null}'
,2017-08-02 13:38:47 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 8222BD6A-6049-42EA-8E3E-EADA99C64585 (syncValue: 1)'
2017-08-02 13:38:47 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPee,r(_:syncValue:retryCount:completion:) Peer(uuid: "8222BD6A-6049-42EA-8E3E-EADA99C64585", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8222BD6A-6049-42EA-8E3E-EADA99C64585", ge,neration: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:8222BD6A-6049-42EA-8E3E-EADA99C64585:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnec,ted:stoppedListening:)
,[ThaliCore] Session.deinit peer:5F9B6F57-AB39-4527-81DB-C997CCB7CD5C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:54561342-FCEC-42D3-B0DF-2D9BEA207A87
[ThaliCore] Advertiser: session connected Peer(uuid: "8B2DDBB7-B3DF-467C-B63F-625FA51822DC", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:54561342-FCEC-42D3-B0DF-2D9BEA207A87 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:8222BD6A-6049-42EA-8E3E-EADA99C64585:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:8222BD6A-6049-42EA-8E3E-EADA99C64585:0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:54561342-FCEC-42D3-B0DF-2D9BEA207A87
,[ThaliCore] Session.session(_:peer:didChange:) peer:54561342-FCEC-42D3-B0DF-2D9BEA207A87 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:54561342-FCEC-42D3-B0DF-2D9BEA207A87
[ThaliCore] Session.startOutputStream(with:) peer:54561342-FCEC-42D3-B0DF-2D9BEA207A87
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:15 [3, 5, 14, 15]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:8222BD6A-6049-42EA-8E3E-EADA99C64585:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "8222BD6A-6049-42EA-8E3E-EADA99C64585", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:65514
,2017-08-02 13:38:50 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"1","error":null,"portNumber":65514}'
,2017-08-02 13:38:50 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 1FFD57F3-189F-4C51-9BD0-1F96D486CC8B (syncValue: 2)'
,2017-08-02 13:38:50 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1FFD57F3-189F-4C51-9BD0-1F96D486CC8B", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1FFD57F3-189F-4C51-9BD0-1F96D486CC8B", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1FFD57F3-189F-4C51-9BD0-1F96D486CC8B:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:8222BD6A-6049-42EA-8E3E-EADA99C64585:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:8222BD6A-6049-42EA-8E3E-EADA99C64585:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:16 [3, 5, 14, 15, 16]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-08-02 13:38:50 - DEBUG testUtils: 'Got response data'
2017-08-02 13:38:50 - DEBUG testUtils: 'Got end'
,[ThaliCore] Session.session(_:peer:didChange:) peer:1FFD57F3-189F-4C51-9BD0-1F96D486CC8B:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:1FFD57F3-189F-4C51-9BD0-1F96D486CC8B:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:1FFD57F3-189F-4C51-9BD0-1F96D486CC8B:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "1FFD57F3-189F-4C51-9BD0-1F96D486CC8B", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:65517
2017-08-02 13:38:53 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"2","error":null,"portNumber":65517,}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:1FFD57F3-189F-4C51-9BD0-1F96D486CC8B:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:1FFD57F3-189F-4C51-9BD0-1F96D486CC8B:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:17 [3, 5, 14, 15, 16, 17]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler,
,2017-08-02 13:38:53 - DEBUG testUtils: 'Got response data'
2017-08-02 13:38:53 - DEBUG testUtils: 'Got end'
ok 526 received all uuids
,# teardown
,2017-08-02 13:38:53 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"5F9B6F57-AB39-4527-81DB-C997CCB7CD5C","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-08-02, 13:38:53 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"8222BD6A-6049-42EA-8E3E-EADA99C64585","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-08-02 13:38:53 ,- DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"1FFD57F3-189F-4C51-9BD0-1F96D486CC8B","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:8B2DDBB7-B3DF-467C-B63F-625FA51822DC
2017-08-02 13:38:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-08-02 13:38:53 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,}})'
2017-08-02 13:38:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-02 13:38:53 - DEBUG thaliMobileN,ativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:38:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-02 13:38:53 - DEBUG makeInt,o,CloseAllServer: 'closeAll called on server'
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual soc,ket vsID:14
[ThaliCore] VirtualSocket.closeStreams() vsID:14
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocali,zedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler ,r,emoved virtual socket vsID:15
ok 527 error should be null
ok 528 error should be null
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:14
[ThaliCore] VirtualSocket.closeStreams() vsID:15
[ThaliCore] VirtualSocket.deinit vsID:14 [3, 5, 15, 16, 17]
[ThaliCore,] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:15
[ThaliCore] VirtualSocket.deinit vsID:15 [3, 5, 16, 17]
,# setup
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:17
[ThaliCore] VirtualSocket.closeStreams() vsID:17
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:17
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] VirtualSocket.deinit vsID:17 [3, 5, 16]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:16
[ThaliCore] VirtualSocket.closeStreams() vsID:16
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:16
[Th,aliCore] VirtualSocket.deinit vsID:16 [3, 5]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,ok 529 ThaliMobile should be stopped
,# test for data corruption
,2017-08-02 13:38:55 - DEBUG CoordinatedClient: 'test was skipped, name: 'test for data corruption''
,# teardown
,ok 530 error should be null
ok 531 error should be null
,# setup
,# #testThaliPeerAction - test getters
,ok 532 getPeerIdentifier
ok 533 getConnectionType
ok 534 getActionType
,ok 535 getActionState
ok 536 getPskIdentity
ok 537 getPskKey
,# teardown
,# setup
,# #testThaliPeerAction - start and kill
,ok 538 initial state
,ok 539 after start
,2017-08-02 13:38:57 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 540 after kill
,# teardown
,# setup
,# #testThaliPeerAction - double start
,ok 541 should be equal
,# teardown
,# setup
,# #testThaliPeerAction - start after kill
,2017-08-02 13:38:58 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 542 clean kill
,ok 543 should be equal
,# teardown
,# setup
,# #testThaliPeerAction - make sure ids are unique
,ok 544 should not be equal
,# teardown
,# setup
,# #testThaliPeerAction - check that forever agent can be destroyed
,ok 545 forever agent should have it's own destroy method
,ok 546 agent's destroy should be called
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
ok 557 Size must be 3
,ok 558 Entry counter must be 2
,ok 559 Entry exists
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
,ok 577 Size should be MAXSIZE
ok 578 Size should be MAXSIZE+6
,# teardown
,# setup
,# WAITING entries are removed before CONTROLLED_BY_POOL state entry.
,ok 579 WAITING state entry should not be removed
,ok 580 Waiting entries between 6 and MAXSIZE + 4 should exist
ok 581 Size should be MAXSIZE
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
ok 586 enqueue is fine
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
,2017-08-02 13:39:07 - DEBUG testUtils: 'Got response data'
,2017-08-02 13:39:07 - DEBUG testUtils: 'Got end'
,ok 597 Got expected response
,ok 598 Got psk call back
,# teardown
,2017-08-02 13:39:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #ThaliPeerPoolDefault - stop
,ok 599 is an agent
ok 600 enqueue worked
,ok 601 is an agent
ok 602 enqueue 2 worked
ok 603 enqueue is not available when stopped
ok 604 start action is killed
ok 605 killed action is still killed
ok 606 enqueued action when stopped is killed
ok 607 inQueue is empty
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
ok 615 already enqueued
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure we catch kill and dequeue
,ok 616 good enqueue
,ok 617 2nd good enqueue
ok 618 we are in the pool
ok 619 We are out of the pool
ok 620 Action was killed
ok 621 The original kill was called too
ok 622 second item is still in queue
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent
,ok 623 good enqueue
,ok 624 first kill
ok 625 second NOOP kill
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure that stop removes all actions
,ok 626 1st good enqueue
ok 627 2nd good enqueue
,ok 628 1st action is in the pool
ok 629 2nd action is in the pool
ok 630 1st action is out of the pool
ok 631 2st action is out of the pool
ok 632 pool is empty
,# teardown
,# setup
,# We reject unrecognized connection type
,2017-08-02 13:39:11 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
ok 633 Got right error
ok 634 Start should not be called
ok 635 Kill should have been called at least once
,# teardown
,# setup
,# We reject unrecognized action type
,2017-08-02 13:39:12 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
2017-08-02 13:39:12 - ERROR thaliPeerPoolOneAtATime: 'Got unsupported action type: blah'
ok 636 Got right error
ok 637 Start should not be called
ok 638 Kill should have been calle,d at least once
,# teardown
,# setup
,# One action on bluetooth
,2017-08-02 13:39:12 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
ok 639 Got null
2017-08-02 13:39:12 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier,: peerID'
ok 640 is an agent
2017-08-02 13:39:12 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerID'
,ok 641 Got killed at least once
,# teardown
,# setup
,# Two notification actions
,2017-08-02 13:39:13 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
ok 642 Got Null
ok 643 Got another null
2017-08-02 13:39:13 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidB,luetooth, Peer Identifier: peerId1'
ok 644 is an agent
2017-08-02 13:39:13 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peer,Id1'
2017-08-02 13:39:13 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
ok 645 is an agent
2017-08-02 13:39:13 - DEBUG thaliPeerPoolOneAtATime:, 'action returned successfully from start - Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
,ok 646 Action 1 killed at least once
,ok 647 Action 1 went first
ok 648 Action 2 killed at least once
,# teardown
,# setup
,# replicateThroughProblems
,2017-08-02 13:39:14 - DEBUG thaliPeerPoolOneAtATime: 'Action Started success'
,2017-08-02 13:39:14 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - success'
2017-08-02 13:39:14 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
ok 649 should have gotten null
2017-08-02 13:39:14 ,- DEBUG thaliPeerPoolOneAtATime: 'Action Started noActivityTimeOut'
2017-08-02 13:39:14 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: No activity time out - noActivityTimeOut'
ok 650 Should have stopped nicely
2017-08-02 ,13:39:14 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButNotAvailable'
2017-08-02 13:39:14 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButNotAvailable'
ok 651 Still looking for null
2017-08-02, 13:39:14 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButAvailable'
2017-08-02 13:39:14 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButAvailable'
2017-08-02 13:39:14 - DEBUG thaliPeerPoolOneA,t,ATime: 'Replication action failed badly so we are going to retry'
2017-08-02 13:39:14 - DEBUG thaliPeerPoolOneAtATime: 'Action Started clone!'
2017-08-02 13:39:14 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - clone!'
2017-0,8-02 13:39:14 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
ok 652 Yup, another null
ok 653 We cloned!
,# teardown
,# setup
,# Replication goes first
,2017-08-02 13:39:14 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 654 Null 1
,ok 655 (unnamed assert)
,2017-08-02 13:39:14 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,ok 656 is an agent
,ok 657 Null 3
,ok 658 Replication not yet called
,ok 659 Notification 2 not yet called
,2017-08-02 13:39:14 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,2017-08-02 13:39:14 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
,ok 660 is an agent
,ok 661 Notification went first
,ok 662 Notification 2 not called yet
,2017-08-02 13:39:14 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
,2017-08-02 13:39:14 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,2017-08-02 13:39:14 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,ok 663 is an agent
,ok 664 Notification finished
,ok 665 Replication finished
,2017-08-02 13:39:14 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,# teardown
,# setup
,# wifi allows many parallel non-replication actions
,2017-08-02 13:39:14 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-08-02 13:39:14 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
,ok 666 is an agent
,ok 667 First does not throw
,2017-08-02 13:39:14 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
,ok 668 is an agent
,ok 669 Second does not throw
,2017-08-02 13:39:14 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
,truetruefalsetrue
,2017-08-02 13:39:14 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
,truetruetruetrue
,# teardown
,# setup
,# wifi allows no more than 2 simultaneous replication actions for same peerID
,2017-08-02 13:39:15 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-08-02 13:39:15 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 595, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,ok 670 is an agent
,ok 671 first ok
,2017-08-02 13:39:15 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 596, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,ok 672 is an agent
,ok 673 second ok
,ok 674 third ok
,2017-08-02 13:39:15 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 595, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,2017-08-02 13:39:15 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 596, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,2017-08-02 13:39:15 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,2017-08-02 13:39:15 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,# teardown
,# setup
,# Client to server request coordinated
,2017-08-02 13:39:16 - DEBUG CoordinatedClient: 'test was skipped, name: 'Client to server request coordinated''
,# teardown
,2017-08-02 13:39:16 - INFO testThaliNotification: 'Participants:0 Peers Replied to us:0 Peers requested to:0'
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
,2017-08-02 13:39:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test HTTP_BAD_RESPONSE locally
,2017-08-02 13:39:17 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test HTTP_BAD_RESPONSE locally''
,# teardown
,2017-08-02 13:39:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test NETWORK_PROBLEM locally
,ok 683 Response should be NETWORK_PROBLEM
ok 684 reject reason should be: Could not establish TCP connection
,# teardown
,2017-08-02 13:39:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Action fails when getPeerHostInfo fails
,ok 685 Resolution should be BAD_PEER
ok 686 correct error message
,# teardown
,2017-08-02 13:39:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the start two times
,ok 687 Call start once
,ok 688 Response should be BEACONS_RETRIEVED_AND_PARSED
,ok 689 must return null after successful call.
,# teardown
,2017-08-02 13:39:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill before calling the start
,ok 690 Should be Killed
ok 691 Start after killed
,# teardown
,2017-08-02 13:39:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill immediately after the start
,ok 692 Should be KILLED
,ok 693 must return null after successful kill
,# teardown
,2017-08-02 13:39:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill while waiting a response from the server
,ok 694 Should be KILLED
ok 695 must return null after successful kill
,# teardown
,2017-08-02 13:39:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test to exceed the max content size locally
,ok 696 HTTP_BAD_RESPONSE should be response when content size is exceeded
,ok 697 must return null after successful call
,# teardown
,2017-08-02 13:39:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Close the server socket while the client is waiting a response from the server. Local test.
,2017-08-02 13:39:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 698 Should be NETWORK_PROBLEM caused closing server socket
ok 699 Should be Could not establish TCP connection
,# teardown
,# setup
,# Close the client socket while the client is waiting a response from the server. Local test.
,ok 700 Should be NETWORK_PROBLEM caused closing client socket
ok 701 Should be Could not establish TCP connection
,# teardown
,2017-08-02 13:39:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
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
,ok 709 should be equal
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
,2017-08-02 13:39:32 - DEBUG CoordinatedClient: 'test was skipped, name: '#parseBeacons addressBookCallback returns no matches''
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns spurious match
,ok 719 should be equal
,ok 720 should be equal
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns public key
,ok 721 right number of calls to address book
,ok 722 good preAmble
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
,ok 730 secrets match
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
,ok 742 peerDictionalty contains 2 peers
,ok 743 bluetooth peer's notification has correct connection type
,ok 744 tcp peer's notification has correct connection type
,2017-08-02 13:39:36 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,2017-08-02 13:39:36 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-08-02 13:39:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# TCP_NATIVE peer loses DNS
,ok 745 notification peer dictionary contains exactly 1 peer
,2017-08-02 13:39:36 - WARN thaliNotificationClient: 'peer is not available'
ok 746 notification peer dictionary does not contain any peers
,2017-08-02 13:39:36 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-08-02 13:39:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Received beacons with no values for us
,ok 747 entry exists
,ok 748 entry is resolved
,# teardown
,2017-08-02 13:39:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Notification action killed with a superseded
,ok 749 Action should be KILLED
,ok 750 Peer state should be RESOLVED
,# teardown
,2017-08-02 13:39:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally
,ok 751 hostAddress must match
,ok 752 portNumber must match
,ok 753 suggestedTCPTimeout must match
,ok 754 connectionType must match
,ok 755 peerIDs must match
,# teardown
,2017-08-02 13:39:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Emits error event when peerPool.enqueue throws
,ok 756 Correct error
,# teardown
,2017-08-02 13:39:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally using ThaliPeerPoolDefault
,ok 757 hostAddress must match
,ok 758 portNumber must match
,ok 759 suggestedTCPTimeout must match
,ok 760 connectionType must match
,ok 761 peerIds must match
,# teardown
,2017-08-02 13:39:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Action fails because of a bad hostname.
,2017-08-02 13:39:41 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 762 action should be resolved with NETWORK_PROBLEM error
,2017-08-02 13:39:42 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 763 action should be resolved with NETWORK_PROBLEM error
,2017-08-02 13:39:42 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 764 action should be resolved with NETWORK_PROBLEM error
,2017-08-02 13:39:43 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 765 action should be resolved with NETWORK_PROBLEM error
ok 766 correct number of requests
ok 767 correct number of failures
ok 768 correct final peer state
,# teardown
,2017-08-02 13:39:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# hostaddress is removed when the action is running. 
,2017-08-02 13:39:45 - WARN thaliNotificationClient: 'peer is not available'
2017-08-02 13:39:45 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 769 peerDictionary should become empty
,# teardown
,2017-08-02 13:39:46 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notificationClient does not retry action with BAD_PEER resolution
,2017-08-02 13:39:46 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 770 failed with expected error
ok 771 peer state should be RESOLVED
,# teardown
,2017-08-02 13:39:46 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notification client correctly handles peer availability changes of the same peer
,2017-08-02 13:39:47 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 772 First action failed
,ok 773 second action killed
,# teardown
,2017-08-02 13:39:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Client to server request locally
,ok 774 secrets are equal
,ok 775 Public key matches with the server key
,ok 776 hostAddress must match
,ok 777 portNumber must match
,ok 778 suggestedTCPTimeout must match
,ok 779 connectionType must match
,# teardown
,2017-08-02 13:39:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache clean and expiration
,ok 780 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE
ok 781 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE-1
,ok 782 All entries should be expired after 1 second
# teardown
,2017-08-02 13:39:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache getSecret and getPublic
,ok 783 All keys need to be available in the cache
,ok 784 All entries should be expired after 1 second
# teardown
,2017-08-02 13:39:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache multiple entries
,ok 785 Size of the cache should be 2
ok 786 Cache doesn't contain dictionary1
,ok 787 Size of the cache should be 1
ok 788 Cache doesn't contain beaconStreamAndSecretDictionary2
# teardown
,2017-08-02 13:39:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Start and stop ThaliNotificationServer
,ok 789 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
,ok 790 ThaliMobile.StopAdvertisingAndListeningshould be called once
,# teardown
,2017-08-02 13:39:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass an empty array to ThaliNotificationServer.start
,ok 791 StartUpdateAdvertisingAndListening should not be called
,ok 792 ThaliMobile.StopAdvertisingAndListening should be called once
,ok 793 no error
,ok 794 should be 204
,# teardown
,2017-08-02 13:39:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass a string to ThaliNotificationServer.start
,ok 795 StartUpdateAdvertisingAndListening should not be called
,# teardown
,2017-08-02 13:39:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass an empty parameter to ThaliNotificationServer.start
,ok 796 StartUpdateAdvertisingAndListening should not be called
,# teardown
,2017-08-02 13:39:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeacons
,ok 797 no error
,ok 798 should be 200
ok 799 should be equal
,ok 800 should be equal
,ok 801 (unnamed assert)
,ok 802 no error
,ok 803 should be 204
,# teardown
,2017-08-02 13:39:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeacons (no keys)
,ok 804 error should be null
,ok 805 should be 204
,# teardown
,2017-08-02 13:39:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeaconsbefore calling start
,ok 806 should be 404
# teardown
,2017-08-02 13:39:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure peerDictionaryKey is reasonable
,ok 807 equal keys
ok 808 not equal connection type
ok 809 same connection type, different buffer
,# teardown
,# setup
,# Make sure start works
,2017-08-02 13:39:56 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 810 First start and on called correctly
,# teardown
,# setup
,# Make sure stop works
,ok 811 second cleared dictionary
2017-08-02 13:39:57 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 812 First start and on called correctly
,ok 813 First stop and removeListener called correctly
ok 814 first action kill called
ok 815 second action kill called
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
,2017-08-02 13:39:58 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 821 listener has been set
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
,2017-08-02 13:39:58 - DEBUG thaliReplicationPeerAction: 'We called _complete with  and it caused us to complete'
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
,2017-08-02 13:39:58 - DEBUG CoordinatedClient: 'test was skipped, name: 'Coordinated pull replication from notification test''
,# teardown
,# setup
,# Server is not there
,2017-08-02 13:39:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-02 13:39:59 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 connect ECONNREFUSED'
,2017-08-02 13:39:59 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: connect ECONNREFUSED  and it caused us to complete'
,ok 847 right error
,# teardown
,2017-08-02 13:39:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server accepts & closes connection
,2017-08-02 13:39:59 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 socket hang up'
,2017-08-02 13:39:59 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: socket hang up  and it caused us to complete'
,ok 848 right error
,# teardown
,2017-08-02 13:40:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 500
,2017-08-02 13:40:00 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 changes rejected'
,2017-08-02 13:40:00 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 849 Got error as expected
,# teardown
,2017-08-02 13:40:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 401
,2017-08-02 13:40:00 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  401 changes rejected'
,2017-08-02 13:40:00 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 850 Got error as expected
,# teardown
,2017-08-02 13:40:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 403
,2017-08-02 13:40:01 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  403 changes rejected'
,2017-08-02 13:40:01 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 851 Got error as expected
,# teardown
,2017-08-02 13:40:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure docs replicate with remote db with same name as local db
,2017-08-02 13:40:03 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-08-02 13:40:03 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-08-02 13:40:05 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
,ok 852 should be equal
ok 853 All tests passed!
,# teardown
,2017-08-02 13:40:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure docs replicate with remote db with different name than local db
,2017-08-02 13:40:09 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-08-02 13:40:09 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-08-02 13:40:12 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
,ok 854 should be equal
ok 855 All tests passed!
,# teardown
,2017-08-02 13:40:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Do nothing and make sure we time out
,2017-08-02 13:40:13 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-08-02 13:40:15 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2017-08-02 13:40:15 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and s,o we ignored it'
ok 856 action should be killed
ok 857 Error should be timed out
,ok 858 No doc found
,# teardown
,2017-08-02 13:40:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Do something and make sure we time out
,2017-08-02 13:40:17 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-08-02 13:40:17 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,ok 859 should be equal
,2017-08-02 13:40:19 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
,2017-08-02 13:40:19 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
,ok 860 action should be killed
ok 861 Error should be timed out
,# teardown
,2017-08-02 13:40:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Start replicating and then catch error when server goes
,ok 862 socket hung up
,# teardown
,2017-08-02 13:40:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure clone works
,ok 863 same getPeerAdvertisesDataForUs
,ok 864 Same pouchdB
,ok 865 same localDbName
,ok 866 Same public key
,# teardown
,# setup
,# Coordinated replication action test - each device has the same local db name
,2017-08-02 13:40:22 - DEBUG CoordinatedClient: 'test was skipped, name: 'Coordinated replication action test - each device has the same local db name''
,# teardown
,# setup
,# Coordinated replication action test - each device has different local db name
,2017-08-02 13:40:23 - DEBUG thaliMobileNativeWrapper: 'listening 49260'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:20A96530-E2DC-45AC-948D-7A1ABD41B9E9
[ThaliCore] Browser.startListening
,2017-08-02 13:40:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "DBD8E41B-2745-45AA-9AFC-91E8212BCF42", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:DBD8E41B-2745-45AA-9AFC-91E8212BCF42
,2017-08-02 13:40:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DBD8E41B-2745-45AA-9AFC-91E8212BCF42:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DBD8E41B-2745-45AA-9AFC-91E8212BCF42", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:57A9FCF1-AB81-4433-BBB3-0B6005506F6D
[ThaliCore] Advertiser: session connected Peer(uuid: "DBD8E41B-2745-45AA-9AFC-91E8212BCF42", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:84EBA22C-7CFD-4B2E-A071-1E6274AF0B70
[ThaliCore] Advertiser: session connected Peer(uuid: "DBD8E41B-2745-45AA-9AFC-9,1E8212BCF42", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:57A9FCF1-AB81-4433-BBB3-0B6005506F6D state: notConnected -> connecting
[T,haliCore] Session.session(_:peer:didChange:) peer:84EBA22C-7CFD-4B2E-A071-1E6274AF0B70 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B62FD9DD-B264-4CBF-8735-F2F333E048E2:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B62FD9DD-B264-4CBF-8735-F2F333E048E2", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2D5A4CED-5489-48C5-AAA0-5C484A196223:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2D5A4CED-5489-48C5-AAA0-5C484A196223", generation: 0)
,2017-08-02 13:40:24 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"B62FD9DD-B264-4CBF-8735-F2F333E048E2","generation":0}]'
,2017-08-02 13:40:24 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"B62FD9DD-B264-4CBF-8735-F2F333E048E2","generation":0}'
,2017-08-02 13:40:24 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"2D5A4CED-5489-48C5-AAA0-5C484A196223","generation":0}]'
,2017-08-02 13:40:24 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"2D5A4CED-5489-48C5-AAA0-5C484A196223","generation":0}'
,2017-08-02 13:40:24 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"B62FD9DD-B264-4CBF-8735-F2F333E048E2","peerAvailable":true,"generation":0,"portNumber":null}'
2017-08-02 13:40:24 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"B62FD9DD-B264-4CBF-8735-F2F333E048E2","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-08-02 13:40:24 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"2D5A4CED-5489-48C5-AAA0-5C484A196223","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-02 13:40:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"2D5A4CED-5489-48C5-AAA0-5C484A196223","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-08-02 13:40:24 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for B62FD9DD-B264-4CBF-8735-F2F333E048E2 (syncValue: 3)'
,2017-08-02 13:40:24 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B62FD9DD-B264-4CBF-8735-F2F333E048E2", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B6,2FD9DD-B264-4CBF-8735-F2F333E048E2", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B62FD9DD-B264-4CBF-8735-F2F333E048E2:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:B62FD9DD-B264-4CBF-8735-F2F333E048E2:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:84EBA22C-7CFD-4B2E-A071-1E6274AF0B70
,[ThaliCore] Session.session(_:peer:didChange:) peer:84EBA22C-7CFD-4B2E-A071-1E6274AF0B70 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:84EBA22C-7CFD-4B2E-A071-1E6274AF0B70
[ThaliCore] Session.startOutputStream(with:) peer:84EBA22C-7CFD-4B2E-A071-1E6274AF0B70
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:18 [3, 5, 18]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:18
[ThaliCore] VirtualSocket.closeStreams() vsID:18
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:18
[ThaliCore] VirtualSocket.deinit vsID:18 [3, 5]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client ,disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:84EBA22C-7CFD-4B2E-A071-1E6274AF0B70
[ThaliCore] Session.startOutputStream(with:) peer:84EBA22C-7CFD-4B2E-A071-1E6274AF0B70
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:19 [3, 5, 19]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:57A9FCF1-AB81-4433-BBB3-0B6005506F6D
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:84EBA22C-7CFD-4B2E-A071-1E6274AF0B70
[ThaliCore] Session.session(_:peer:didChange:) peer:57A9FCF1-AB81-4433-BBB3-0B6005506F6D state: connecting -> connected
[ThaliCore] Session.startOutputStream(with:) peer:84EBA22C-7CFD-4B2E-A071-1E6274AF0B70
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:20 [3, 5, 19, 20]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B62FD9DD-B264-4CBF-8735-F2F333E048E2:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:57A9FCF1-AB81-4433-BBB3-0B6005506F6D
[ThaliCore] Session.startOutputStream(with:) peer:57A9FCF1-AB81-4433-BBB3-0B6005506F6D
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:21 [3, 5, 19, 20, 21]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:B62FD9DD-B264-4CBF-8735-F2F333E048E2:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "B62FD9DD-B264-4CBF-8735-F2F333E048E2", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:49267
,2017-08-02 13:40:27 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"3","error":null,"portNumber":49267}'
,2017-08-02 13:40:27 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 2D5A4CED-5489-48C5-AAA0-5C484A196223 (syncValue: 4)'
,2017-08-02 13:40:27 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2D5A4CED-5489-48C5-AAA0-5C484A196223", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2D5A4CED-5489-48C5-AAA0-5C484A196223", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2D5A4CED-5489-48C5-AAA0-5C484A196223:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B62FD9DD-B264-4CBF-8735-F2F333E048E2:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B62FD9DD-B264-4CBF-8735-F2F333E048E2:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:22 [3, 5, 19, 20, 21, 22]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:21
[ThaliCore] VirtualSocket.closeStreams() vsID:21
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:21
[ThaliCore] VirtualSocket.deinit vsID:21 [3, 5, 19, 20, 22]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:57A9FCF1-AB81-4433-BBB3-0B6005506F6D
,[ThaliCore] Session.startOutputStream(with:) peer:57A9FCF1-AB81-4433-BBB3-0B6005506F6D
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:23 [3, 5, 19, 20, 22, 23]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:84EBA22C-7CFD-4B2E-A071-1E6274AF0B70
[ThaliCore] Session.startOutputStream(with:) peer:84EBA22C-7CFD-4B2E-A071-1E6274AF0B70
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:24 [3, 5, 19, 20, 22, 23, 24]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vs,ID:22
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:22
,[ThaliCore] VirtualSocket.deinit vsID:22 [3, 5, 19, 20, 23, 24]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B62FD9DD-B264-4CBF-8735-F2F333E048E2:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B62FD9DD-B264-4CBF-8735-F2F333E048E2:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:25 [3, 5, 19, 20, 23, 24, 25]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-08-02 13:40:28 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B62FD9DD-B264-4CBF-8735-F2F333E048E2:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:57A9FCF1-AB81-4433-BBB3-0B6005506F6D
[ThaliCore] Session.startOutputStream(with:) peer:57A9FCF1-AB81-4433-BBB3-0B6005506F6D
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:26 [3, 5, 19, 20, 23, 24, 25, 26]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B62FD9DD-B264-4CBF-8735-F2F333E048E2:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:27 [3, 5, 19, 20, 23, 24, 25, 26, 27]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:peer:didChange:) peer:2D5A4CED-5489-48C5-AAA0-5C484A196223:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:84EBA22C-7CFD-4B2E-A071-1E6274AF0B70
[ThaliCore] Session.startOutputStream(with:) peer:84EBA22C-7CFD-4B2E-A071-1E6274AF0B70
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:28 [3, 5, 19, 20, 23, 24, 25, 26, 27, 28]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B62FD9DD-B264-4CBF-8735-F2F333E048E2:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B62FD9DD-B264-4CBF-8735-F2F333E048E2:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:29 [3, 5, 19, 20, 23, 24, 25, 26, 27, 28, 29]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:84EBA22C-7CFD-4B2E-A071-1E6274AF0B70
[ThaliCore] Session.startOutputStream(with:) peer:84EBA22C-7CFD-4B2E-A071-1E6274AF0B70
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:30 [3, 5, 19, 20, 23, 24, 25, 26, 27, 28, 29, 30]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:28
,[ThaliCore] VirtualSocket.closeStreams() vsID:28
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:28
[ThaliCore] VirtualSocket.deinit vsID:28 [3, 5, 19, 20, 23, 24, 25, 26, 27, 29, 30]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socke,tDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:57A9FCF1-AB81-4433-BBB3-0B6005506F6D
[ThaliCore] Session.startOutputStream(with:) peer:57A9FCF1-AB81-4433-BBB3-0B6005506F6D
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:31 [3, 5, 19, 20, 23, 24, 25, 26, 27, 29, 30, 31]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B62FD9DD-B264-4CBF-8735-F2F333E048E2:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B62FD9DD-B264-4CBF-8735-F2F333E048E2:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:32 [3, 5, 19, 20, 23, 24, 25, 26, 27, 29, 30, 31, 32]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B62FD9DD-B264-4CBF-8735-F2F333E048E2:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B62FD9DD-B264-4CBF-8735-F2F333E048E2:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:33 [3, 5, 19, 20, 23, 24, 25, 26, 27, 29, 30, 31, 32, 33]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vs,ID:32
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:32
,[ThaliCore] VirtualSocket.deinit vsID:32 [3, 5, 19, 20, 23, 24, 25, 26, 27, 29, 30, 31, 33]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:57A9FCF1-AB81-4433-BBB3-0B6005506F6D
,[ThaliCore] Session.startOutputStream(with:) peer:57A9FCF1-AB81-4433-BBB3-0B6005506F6D
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:34 [3, 5, 19, 20, 23, 24, 25, 26, 27, 29, 30, 31, 33, 34]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:84EBA22C-7CFD-4B2E-A071-1E6274AF0B70
[ThaliCore] Session.startOutputStream(with:) peer:84EBA22C-7CFD-4B2E-A071-1E6274AF0B70
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:35 [3, 5, 19, 20, 23, 24, 25, 26, 27, 29, 30, 31, 33, 34, 35]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:57A9FCF1-AB81-4433-BBB3-0B6005506F6D
[ThaliCore] Session.startOutputStream(with:) peer:57A9FCF1-AB81-4433-BBB3-0B6005506F6D
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:36 [3, 5, 19, 20, 23, 24, 25, 26, 27, 29, 30, 31, 33, 34, 35, 36]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B62FD9DD-B264-4CBF-8735-F2F333E048E2:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B62FD9DD-B264-4CBF-8735-F2F333E048E2:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:37 [3, 5, 19, 20, 23, 24, 25, 26, 27, 29, 30, 31, 33, 34, 35, 36, 37]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:34
[ThaliCore] VirtualSocket.closeStreams() vsID:34
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:34
[ThaliCore] VirtualSocket.deinit vsID:34 [3, 5, 19, 20, 23, 24, 25, 26, 27, 29, 30, 31, 33, 35, 36, 37]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-08-02 13:40:29 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:37
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:37
[ThaliCore] VirtualSocket.deinit vsID:37 [3, 5, 19, 20, 23, 24, 25, 26, 27, 29, 30, 31, 33, 35, 36]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:35
[ThaliCore] VirtualSocket.closeStreams() vsID:35
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:84EBA22C-7CFD-4B2E-A071-1E6274AF0B70
[ThaliCore] Session.startOutputStream(with:) peer:84EBA22C-7CFD-4B2E-A071-1E6274AF0B70
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:38 [3, 5, 19, 20, 23, 24, 25, 26, 27, 29, 30, 31, 33, 35, 36, 38]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:35
,[ThaliCore] VirtualSocket.deinit vsID:35 [3, 5, 19, 20, 23, 24, 25, 26, 27, 29, 30, 31, 33, 36, 38]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:30
[ThaliCore] VirtualSocket.closeStreams() vsID:30
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:30
[ThaliCore] VirtualSocket.deinit vsID:30 [3, 5, 19, 20, 23, 24, 25, 26, 27, 29, 31, 33, 36, 38]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:84EBA22C-7CFD-4B2E-A071-1E6274AF0B70
[ThaliCore] Session.startOutputStream(with:) peer:84EBA22C-7CFD-4B2E-A071-1E6274AF0B70
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3,9 [3, 5, 19, 20, 23, 24, 25, 26, 27, 29, 31, 33, 36, 38, 39]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:38
[ThaliCore] VirtualSocket.closeStreams() vsID:38
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:,38
[ThaliCore] VirtualSocket.deinit vsID:38 [3, 5, 19, 20, 23, 24, 25, 26, 27, 29, 31, 33, 36, 39]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:57A9FCF1-AB81-4433-BBB3-0B6005506F6D
[ThaliCore] Session.startOutputStream(with:) peer:57A9FCF1-AB81-4433-BBB3-0B6005506F6D
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:40 [3, 5, 19, 20, 23, 24, 25, 26, 27, 29, 31, 33, 36, 39, 40]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:40
[ThaliCore] VirtualSocket.closeStreams() vsID:40
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:40
[ThaliCore] VirtualSocket.deinit vsID:40 [3, 5, 19, 20, 23, 24, 25, 26, 27, 29, 31, 33, 36, 39]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:2D5A4CED-5489-48C5-AAA0-5C484A196223:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:2D5A4CED-5489-48C5-AAA0-5C484A196223:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "2D5A4CED-5489-48C5-AAA0-5C484A196223", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:49288
2017-08-02 13:40:30 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"4","error":null,"portNumber":49288,}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:2D5A4CED-5489-48C5-AAA0-5C484A196223:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2D5A4CED-5489-48C5-AAA0-5C484A196223:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:41 [3, 5, 19, 20, 23, 24, 25, 26, 27, 29, 31, 33, 36, 39, 41]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:41
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:41
,[ThaliCore] VirtualSocket.deinit vsID:41 [3, 5, 19, 20, 23, 24, 25, 26, 27, 29, 31, 33, 36, 39]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:2D5A4CED-5489-48C5-AAA0-5C484A196223:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2D5A4CED-5489-48C5-AAA0-5C484A196223:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:42 [3, 5, 19, 20, 23, 24, 25, 26, 27, 29, 31, 33, 36, 39, 42]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-08-02 13:40:31 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:2D5A4CED-5489-48C5-AAA0-5C484A196223:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2D5A4CED-5489-48C5-AAA0-5C484A196223:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:43 [3, 5, 19, 20, 23, 24, 25, 26, 27, 29, 31, 33, 36, 39, 42, 43]
[ThaliCore] BrowserR,elay.didOpenVirtualSocketStreamsHandler
,2017-08-02 13:40:31 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
,2017-08-02 13:40:31 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:25
[ThaliCore] TCPLis,tener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect,(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:27
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:29
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:33
,[ThaliCore] VirtualSocket exited RunLoop vsID:25
,[ThaliCore] VirtualSocket.deinit vsID:25 [3, 5, 19, 20, 23, 24, 26, 27, 29, 31, 33, 36, 39, 42, 43]
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:27
[ThaliCore] VirtualSocket.deinit vsID:27 [3, 5, 19, 20, 23, 24, 26, 29, 31, 33, 36, 39, 42, 43]
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:29
[ThaliCore] VirtualSocket.deinit vsID:29 [3, 5, 19, 20, 23, 24, 26, 31, 33, 36, 39, 42, 43]
[ThaliCore] BrowserRelay.didCloseVi,rtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:33
[ThaliCore] VirtualSocket.deinit vsID:33 [3, 5, 19, 20, 23, 24, 26, 31, 36, 39, 42, 43]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:23
[ThaliCore] VirtualSocket.closeStreams() vsID:23
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:26
[ThaliCore] VirtualSocket.closeStreams() vsID:26
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:31
[ThaliCore] VirtualSocket.closeStreams() vsID:31
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:36
[ThaliCore] VirtualSocket.closeStreams() vsID:36
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:23
[ThaliCore] VirtualSocket.deinit vsID:23 [3, 5, 19, 20, 24, 26, 31, 36, 39, 42, 43]
[ThaliCore] TCPClient.socketDidDisco,nnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] TCPClient.socketDidDisconnect(_:w,ithError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:26
[Tha,liCore] VirtualSocket.deinit vsID:26 [3, 5, 19, 20, 24, 31, 36, 39, 42, 43]
[ThaliCore] VirtualSocket exited RunLoop vsID:31
[ThaliCore] VirtualSocket.deinit vsID:31 [3, 5, 19, 20, 24, 36, 39, 42, 43]
[ThaliCore] TCPClient.socketDidDisconnect(_:withErro,r:) disconnecting:false socket error:nil
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:36
[ThaliCore] VirtualSocket.deinit vsID:36 [3, 5, 19, 20, 24, 39, 42, 43]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconne,ct(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:2D5A4CED-5489-48C5-AAA0-5C484A196223:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2D5A4CED-5489-48C5-AAA0-5C484A196223:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:44 [3, 5, 19, 20, 24, 39, 42, 43, 44]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStr,eamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:84EBA22C-7CFD-4B2E-A071-1E6274AF0B70
[ThaliCore] Session.startOutputStream(with:) peer:84EBA22C-7CFD-4B2E-A071-1E6274AF0B70
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4,5 [3, 5, 19, 20, 24, 39, 42, 43, 44, 45]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:2D5A4CED-5489-48C5-AAA0-5C484A196223:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2D5A4CED-5489-48C5-AAA0-5C484A196223:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:46 [3, 5, 19, 20, 24, 39, 42, 43, 44, 45, 46]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:2D5A4CED-5489-48C5-AAA0-5C484A196223:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2D5A4CED-5489-48C5-AAA0-5C484A196223:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:47 [3, 5, 19, 20, 24, 39, 42, 43, 44, 45, 46, 47]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:45
[ThaliCore] VirtualSocket.closeStreams() vsID:45
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:45
[ThaliCore] VirtualSocket.deinit vsID:45 [3, 5, 19, 20, 24, 39, 42, 43, 44, 46, 47]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:19
[ThaliCore] VirtualSocket.closeStreams() vsID:19
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:19
[ThaliCore] VirtualSocket.deinit vsID:19 [3, 5, 20, 24, 39, 42, 43, 44, 46, 47]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDid,Disconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:20
[ThaliCore] VirtualSocket.closeStreams() vsID:20
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:24
[ThaliCore] VirtualSocket.closeStreams() vsID:24
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket.handleEventOnInputSt,ream endEncountered vsID:39
[ThaliCore] VirtualSocket.closeStreams() vsID:39
[ThaliCore] VirtualSocket exited RunLoop vsID:24
[ThaliCore] VirtualSocket.deinit vsID:24 [3, 5, 20, 39, 42, 43, 44, 46, 47]
[ThaliCore] TCPClient.socketDidDisconnect(_:withEr,ror:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHan,dler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:39
[ThaliCore] VirtualSocket.deinit vsID:39 [3, 5, 20, 42, 43, 44, 46, 47]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] ,TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:46
[ThaliCore] Browse,rRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:46
[ThaliCore] VirtualSocket.deinit vsID:46 [3, 5, 20, 42, 43, 44, 47]
,2017-08-02 13:40:32 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-08-02 13:40:32 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDom,ain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] B,rowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:42
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:42
[ThaliCore] Vi,rtualSocket.deinit vsID:42 [3, 5, 20, 43, 44, 47]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:43
[ThaliCore] Browse,rRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:43
[ThaliCore] VirtualSocket.deinit vsID:43 [3, 5, 20, 44, 47]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:44
[ThaliCore] Browse,rRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:44
[ThaliCore] VirtualSocket.deinit vsID:44 [3, 5, 20, 47]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:47
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:47
[ThaliCore] VirtualSocket.deinit vsID:47 [3, 5, 20]
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:DBD8E41B-2745-45AA-9AFC-91E8212BCF42
2017-08-02 13:40:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-02 13:40:33 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"B62FD9DD-B264-4CBF-8735-F2F333E048E2","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-08-02, 13:40:33 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"2D5A4CED-5489-48C5-AAA0-5C484A196223","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore] Advertis,erManager.stopAdvertising()
2017-08-02 13:40:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-02 13:40:33 - INFO thaliMobile: 'Received state ({"discoveryActive":true,,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
2017-08-02 13:40:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopp,e,d state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-02 13:40:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}',
2017-08-02 13:40:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-02 13:40:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] VirtualSocket exited RunLoop vsID:20
[ThaliCore] VirtualSocket.deinit vsID:20 [3, 5]
,ok 867 passed
,# teardown
,# setup
,# Coordinated replication action test - should throw error when wrong remote db name is provided
,2017-08-02 13:40:34 - DEBUG thaliMobileNativeWrapper: 'listening 49296'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:9FB72528-4FE6-478B-9FE5-2FCD0CA27E11
[ThaliCore] Browser.startListening
,2017-08-02 13:40:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "E7FE4C83-AA88-4B5F-8AFC-024A3E3E0A29", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:E7FE4C83-AA88-4B5F-8AFC-024A3E3E0A29
,2017-08-02 13:40:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B62FD9DD-B264-4CBF-8735-F2F333E048E2:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B62FD9DD-B264-4CBF-8735-F2F333E048E2", generation: 0)
,2017-08-02 13:40:35 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"B62FD9DD-B264-4CBF-8735-F2F333E048E2","generation":0}]'
,2017-08-02 13:40:35 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"B62FD9DD-B264-4CBF-8735-F2F333E048E2","generation":0}'
,2017-08-02 13:40:35 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"B62FD9DD-B264-4CBF-8735-F2F333E048E2","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-02 13:40:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"B62FD9DD-B264-4CBF-8735-F2F333E048E2","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-08-02 13:40:35 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for B62FD9DD-B264-4CBF-8735-F2F333E048E2 (syncValue: 5)'
,2017-08-02 13:40:35 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B62FD9DD-B264-4CBF-8735-F2F333E048E2", generation: 0) found active relay
,2017-08-02 13:40:35 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"5","error":null,"portNumber":49267}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B62FD9DD-B264-4CBF-8735-F2F333E048E2:0
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E7FE4C83-AA88-4B5F-8AFC-024A3E3E0A29:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E7FE4C83-AA88-4B5F-8AFC-024A3E3E0A29", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D5A64512-996D-4760-894C-603F43EE5BA7
[ThaliCore] Advertiser: session connected Peer(uuid: "E7FE4C83-AA88-4B5F-8AFC-024A3E3E0A29", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:D5A64512-996D-4760-894C-603F43EE5BA7 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B62FD9DD-B264-4CBF-8735-F2F333E048E2:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:48 [3, 5, 48]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:48
[ThaliCore] VirtualSocket.closeStreams() vsID:48
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
2017-08-02 13:40:35 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5891A3EE-D937-4353-ACE3-CA5B2BF22CDE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5891A3EE-D937-4353-ACE3-CA5B2BF22CDE", generation: 0)
2017-08-02 13:40:35 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"5891A3EE-D937-4353-ACE3-CA5B2BF22CDE","generation":0}]'
2017-08-02 13:40:35 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"5891A3EE-D937-4353-ACE3-CA5B2BF22CDE","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:26AD2EE6-305B-44CC-A33E-0510D7802E5F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "26AD2EE6-305B-44CC-A33E-0510D7802E5F", generation: 0)
2017-08-02 13:40:35 - DEBUG t,haliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"5891A3EE-D937-4353-ACE3-CA5B2BF22CDE","peerAvailable":true,"generation":0,"portNumber":null}'
2017-08-02 13:40:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5891A3EE-D937-4353-ACE3-CA5B2BF22CDE","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-08-02 13:40:35 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 5891A3EE-D937-4353-ACE3-CA5B2BF22CDE (syncValue: 6)'
,2017-08-02 13:40:35 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5891A3EE-D937-4353-ACE3-CA5B2BF22CDE", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5891A3EE-D937-4353-ACE3-CA5B2BF22CDE", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5891A3EE-D937-4353-ACE3-CA5B2BF22CDE:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
2017-08-02 13:40:35 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"26AD2EE6-305B-44CC-A33E-0510D7802E5F","generation":0}]'
2017-08-02 13:40:35 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"26AD2EE6-305B-44CC-A33E-0510D7802E5F","generation":0}'
,2017-08-02 13:40:35 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"26AD2EE6-305B-44CC-A33E-0510D7802E5F","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-02 13:40:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"26AD2EE6-305B-44CC-A33E-0510D7802E5F","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:14CDD1DD-E264-45D9-847A-348E1B79446A
[ThaliCore] Advertiser: session connected Peer(uuid: "E7FE4C83-AA88-4B5F-8AFC-024A3E3E0A29", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:14CDD1DD-E264-45D9-847A-348E1B79446A state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:5891A3EE-D937-4353-ACE3-CA5B2BF22CDE:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:2D5A4CED-5489-48C5-AAA0-5C484A196223:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() po,rt:49288
[ThaliCore] Session.disconnect() peer:2D5A4CED-5489-48C5-AAA0-5C484A196223:0
[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "2D5A4CED-5489-48C5-AAA0-5C484A196223", generation: 0)
2017-08-02 13:40:37 - DEBUG thaliMobi,leNativeWrapper: 'multiConnectResolved: {"syncValue":"4","error":"Session disconnected","portNumber":null}'
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:2D5A4CED-5489-48C5-AAA0-5C484A196223:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D5A64512-996D-4760-894C-603F43EE5BA7
,[ThaliCore] Session.session(_:peer:didChange:) peer:D5A64512-996D-4760-894C-603F43EE5BA7 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:14CDD1DD-E264-45D9-847A-348E1B79446A
,[ThaliCore] Session.session(_:peer:didChange:) peer:14CDD1DD-E264-45D9-847A-348E1B79446A state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D5A64512-996D-4760-894C-603F43EE5BA7
[ThaliCore] Session.startOutputStream(with:) peer:D5A64512-996D-4760-894C-603F43EE5BA7
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:49 [3, 5, 48, 49]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:5891A3EE-D937-4353-ACE3-CA5B2BF22CDE:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:5891A3EE-D937-4353-ACE3-CA5B2BF22CDE:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "5891A3EE-D937-4353-ACE3-CA5B2BF22CDE", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:49301
,2017-08-02 13:40:38 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"6","error":null,"portNumber":49301}'
,2017-08-02 13:40:38 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 26AD2EE6-305B-44CC-A33E-0510D7802E5F (syncValue: 7)'
,2017-08-02 13:40:38 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "26AD2EE6-305B-44CC-A33E-0510D7802E5F", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "26AD2EE6-305B-44CC-A33E-0510D7802E5F", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:26AD2EE6-305B-44CC-A33E-0510D7802E5F:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:14CDD1DD-E264-45D9-847A-348E1B79446A
[ThaliCore] Session.startOutputStream(with:) peer:14CDD1DD-E264-45D9-847A-348E1B79446A
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:50 [3, 5, 48, 49, 50]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:49
[ThaliCore] VirtualSocket.closeStreams() vsID:49
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:49
[ThaliCore] VirtualSocket.deinit vsID:49 [3, 5, 48, 50]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:), client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D5A64512-996D-4760-894C-603F43EE5BA7
[ThaliCore] Session.startOutputStream(with:) peer:D5A64512-996D-4760-894C-603F43EE5BA7
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5,1 [3, 5, 48, 50, 51]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:5891A3EE-D937-4353-ACE3-CA5B2BF22CDE:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5891A3EE-D937-4353-ACE3-CA5B2BF22CDE:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:52 [3, 5, 48, 50, 51, 52]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:52
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:52
[ThaliCore] VirtualSocket.deinit vsID:52 [3, 5, 48, 50, 51]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:5891A3EE-D937-4353-ACE3-CA5B2BF22CDE:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5891A3EE-D937-4353-ACE3-CA5B2BF22CDE:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:53 [3, 5, 48, 50, 51, 53]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:51
[ThaliCore] VirtualSocket.closeStreams() vsID:51
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:51
,[ThaliCore] VirtualSocket.deinit vsID:51 [3, 5, 48, 50, 53]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-08-02 13:40:38 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  404 no_db_file'
,2017-08-02 13:40:38 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: no_db_file  and it caused us to complete'
,ok 868 error should be 'no_db_file'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:53
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:53
[ThaliCore] VirtualSocket.deinit vsID:53 [3, 5, 48, 50]
,[ThaliCore] Session.session(_:peer:didChange:) peer:26AD2EE6-305B-44CC-A33E-0510D7802E5F:0 state: notConnected -> connecting
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:50
[ThaliCore] VirtualSocket.closeStreams() vsID:50
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:50
[ThaliCore] VirtualSocket.deinit vsID:50 [3, 5, 48]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.,didSocketDisconnectHandler disconnecting:false
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:14CDD1DD-E264-45D9-847A-348E1B79446A
[ThaliCore] Session.startOutputStream(with:) peer:14CDD1DD-E264-45D9-847A-348E1B79446A
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:54 [3, 5, 48, 54]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:54
[ThaliCore] VirtualSocket.closeStreams() vsID:54
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:54
[ThaliCore] VirtualSocket.deinit vsID:54 [3, 5, 48]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:26AD2EE6-305B-44CC-A33E-0510D7802E5F:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:26AD2EE6-305B-44CC-A33E-0510D7802E5F:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "26AD2EE6-305B-44CC-A33E-0510D7802E5F", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:49308
2017-08-02 13:40:41 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"7","error":null,"portNumber":49308,}'
,2017-08-02 13:40:41 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for B62FD9DD-B264-4CBF-8735-F2F333E048E2 (syncValue: 8)'
2017-08-02 13:40:41 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPee,r(_:syncValue:retryCount:completion:) Peer(uuid: "B62FD9DD-B264-4CBF-8735-F2F333E048E2", generation: 0) found active relay
2017-08-02 13:40:41 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"8","error":null,"portNumber":49267}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:26AD2EE6-305B-44CC-A33E-0510D7802E5F:0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[Th,aliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B62FD9DD-B264-4CBF-8735-F2F333E048E2:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:26AD2EE6-305B-44CC-A33E-0510D7802E5F:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:55 [3, 5, 48, 55]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B62FD9DD-B264-4CBF-8735-F2F333E048E2:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:56 [3, 5, 48, 55, 56]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:56
[ThaliCore] VirtualSocket.closeStreams() vsID:56
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:56
[ThaliCore] VirtualSocket.deinit vsID:56 [3, 5, 48, 55]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocket,DisconnectHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:55
[ThaliCore] Browse,rRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:55
[ThaliCore] VirtualSocket.deinit vsID:55 [3, 5, 48]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:26AD2EE6-305B-44CC-A33E-0510D7802E5F:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:26AD2EE6-305B-44CC-A33E-0510D7802E5F:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:57 [3, 5, 48, 57]
2017-08-02 13:40:41 - DEBUG thaliPeerPoolDefault: 'Got err   Could n,ot establish TCP connection'
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-08-02 13:40:41 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  404 no_db_file'
,2017-08-02 13:40:41 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: no_db_file  and it caused us to complete'
,ok 869 error should be 'no_db_file'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vs,ID:57
,[ThaliCore] VirtualSocket exited RunLoop vsID:57
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket.deinit vsID:57 [3, 5, 48]
,2017-08-02 13:40:41 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for B62FD9DD-B264-4CBF-8735-F2F333E048E2 (syncValue: 9)'
2017-08-02 13:40:41 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPee,r(_:syncValue:retryCount:completion:) Peer(uuid: "B62FD9DD-B264-4CBF-8735-F2F333E048E2", generation: 0) found active relay
2017-08-02 13:40:41 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"9","error":null,"portNumber":49267}'
[Th,aliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B62FD9DD-B264-4CBF-8735-F2F333E048E2:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B62FD9DD-B264-4CBF-8735-F2F333E048E2:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:58 [3, 5, 48, 58]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:58
[ThaliCore] VirtualSocket.closeStreams() vsID:58
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:58
[ThaliCore] VirtualSocket.deinit vsID:58 [3, 5, 48]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket e,rror:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-08-02 13:40:42 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:E7FE4C83-AA88-4B5F-8AFC-024A3E3E0A29
,2017-08-02 13:40:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-02 13:40:42 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"B62FD9DD-B264-4CBF-8735-F2F333E048E2","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-08-02, 13:40:42 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"5891A3EE-D937-4353-ACE3-CA5B2BF22CDE","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-08-02 13:40:42 ,- DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"26AD2EE6-305B-44CC-A33E-0510D7802E5F","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:40:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-02 13:40:42 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
2017-08-02 13:40:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] Brows,erManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-02 13:40:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:40:42 - INFO ,thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-02 13:40:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 870 passed
,# teardown
,# setup
,# compareBufferArrays
,ok 871 should throw
,ok 872 should throw
,ok 873 (unnamed assert)
,ok 874 (unnamed assert)
,ok 875 (unnamed assert)
ok 876 (unnamed assert)
,ok 877 (unnamed assert)
,# teardown
,# setup
,# Call start twice and get error
,ok 878 should throw
,# teardown
,# setup
,# Start and make sure it runs
,# teardown
,# setup
,# Make sure getTimeWhenRun is right after start
,ok 879 (unnamed assert)
# teardown
,# setup
,# Make sure getTimeWhenRun is -1 after function is called
,ok 880 should be equal
,# teardown
,# setup
,# Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running
,ok 881 should be equal
ok 882 should be equal
,ok 883 should throw
,# teardown
,# setup
,# Test TransientState
,ok 884 should throw
,ok 885 should throw
ok 886 should be equal
ok 887 should be equal
ok 888 should be equal
ok 889 should be equal
ok 890 (unnamed assert)
ok 891 (unnamed assert)
,# teardown
,# setup
,# No peers and empty database
,ok 892 verify failed
,ok 893 constructor called once
,ok 894 constructor called with right args
,ok 895 match start arg
,ok 896 start called once
,ok 897 stop called once
,ok 898 stop after start
,# teardown
,# setup
,# One peer and empty DB
,2017-08-02 13:40:47 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 899 verify failed
,ok 900 constructor called once
,ok 901 constructor called with right args
,ok 902 match start arg
,ok 903 start called once
,ok 904 stop called once
,ok 905 stop after start
,# teardown
,# setup
,# One peer with _Local set behind current seq
,2017-08-02 13:40:47 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
ok 906 verify failed
,ok 907 constructor called once
ok 908 constructor called with right args
,ok 909 match start arg
,ok 910 start called once
,ok 911 stop called once
,ok 912 stop after start
,# teardown
,# setup
,# One peer with _Local set equal to current seq
,2017-08-02 13:40:48 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 913 verify failed
,ok 914 constructor called once
,ok 915 constructor called with right args
,ok 916 match start arg
,ok 917 start called once
,ok 918 stop called once
,ok 919 stop after start
,# teardown
,# setup
,# One peer with _Local set ahead of current seq (and no this should not happen)
,2017-08-02 13:40:49 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 920 verify failed
,ok 921 constructor called once
,ok 922 constructor called with right args
,ok 923 match start arg
,ok 924 start called once
,ok 925 stop called once
,ok 926 stop after start
,# teardown
,# setup
,# Three peers, one not in DB, one behind and one ahead
,2017-08-02 13:40:49 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 927 verify failed
,ok 928 constructor called once
,ok 929 constructor called with right args
,ok 930 match start arg
,ok 931 start called once
,ok 932 stop called once
,ok 933 stop after start
,# teardown
,# setup
,# More than maximum peers, make sure we only send maximum allowed
,2017-08-02 13:40:50 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
ok 934 verify failed
,ok 935 constructor called once
,ok 936 constructor called with right args
,ok 937 match start arg
ok 938 start called once
,ok 939 stop called once
,ok 940 stop after start
,# teardown
,# setup
,# two peers with empty DB, update the doc
,2017-08-02 13:40:50 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,2017-08-02 13:40:50 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 941 verify failed
,ok 942 constructor called once
,ok 943 constructor called with right args
,ok 944 last start before stop
,ok 945 empty first start
,ok 946 full second start
,ok 947 only 2 timers
,# teardown
,# setup
,# add doc and make sure tokens refresh when they expire
,2017-08-02 13:40:51 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,2017-08-02 13:40:51 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,2017-08-02 13:40:51 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 948 verify failed
,ok 949 constructor called once
,ok 950 constructor called with right args
,ok 951 start before stop
,ok 952 We got at least 3 calls to start
,ok 953 at least 3
,ok 954 default 1
,ok 955 1 run
,ok 956 default 2
,ok 957 2 run
,ok 958 default 3
,# teardown
,# setup
,# start and stop and start and stop
,ok 959 start out null
,2017-08-02 13:40:52 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 960 back to null
,2017-08-02 13:40:52 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 961 still null
,ok 962 verify failed
,ok 963 constructor called once
,ok 964 constructor called with right args
,ok 965 first start before first stop
,ok 966 first stop before second start
,ok 967 second start before second stop
,# teardown
,# setup
,# two identical starts in a row
,2017-08-02 13:40:52 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 968 verify failed
,ok 969 constructor called once
,ok 970 constructor called with right args
,ok 971 (unnamed assert)
,# teardown
,# setup
,# two different starts in a row
,2017-08-02 13:40:53 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 972 verify failed
,ok 973 constructor called once
,ok 974 constructor called with right args
,ok 975 (unnamed assert)
,ok 976 (unnamed assert)
,# teardown
,# setup
,# two stops and a start and two stops
,2017-08-02 13:40:54 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 977 verify failed
,ok 978 constructor called once
,ok 979 constructor called with right args
,ok 980 start before stop
,# teardown
,# setup
,# we properly enqueue requests so no then needed
,2017-08-02 13:40:54 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 981 verify failed
,ok 982 constructor called once
,ok 983 constructor called with right args
,ok 984 start before stop
,# teardown
,# setup
,# test calculateSeqPointKeyId
,ok 985 should be equal
,ok 986 should be equal
,# teardown
,# setup
,# #_doImmediateSeqUpdate - server is not there
,2017-08-02 13:40:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-02 13:40:55 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}'
,ok 987 Got right error
,# teardown
,2017-08-02 13:40:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - server accepts & closes connection
,2017-08-02 13:40:55 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNRESET","status":500}'
ok 988 Got socket hang up
# teardown
,2017-08-02 13:40:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - server always returns 500
,2017-08-02 13:40:56 - DEBUG localSeqManager: 'Got an error trying to update seq []'
ok 989 Got 500 as expected
# teardown
,2017-08-02 13:40:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - create new seq doc
,ok 990 should be equal
,ok 991 revs are equal
,# teardown
,2017-08-02 13:40:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - doc exists, need to get rev and update
,ok 992 should be equal
,ok 993 revs are equal
,# teardown
,2017-08-02 13:40:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - update seq three times
,ok 994 should be equal
,ok 995 revs are equal
,ok 996 should be equal
,ok 997 revs are equal
,ok 998 should be equal
,ok 999 revs are equal
,# teardown
,2017-08-02 13:41:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - rev got changed under us
,(node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
,Trace: 
    at $3.prototype.trace@console.js:139:8
    at addListener@events.js:140:1
    at module.exports@/private/var/containers/Bundle/Application/40D065A8-D634-4A4D-BFB3-1330C4840FF5/ThaliTest.app/www/jxcore/node_modules/pouchdb-all-dbs/lib/index.js:82:3
    at module.exports/<.start/<@/private/var/containers/Bundle/Application/40D065A8-D634-4A4D-BFB3-1330C4840FF5/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/lib/index.js:143:9
    at tryCatcher@/private/var/containers/Bundle/Application/4,0D065A8-D634-4A4D-BFB3-1330C4840FF5/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/util.js:16:16
    at module.exports/Promise.prototype._settlePromiseFromHandler@/private/var/containers/Bundle/Application/40D065A8-,D634-4A4D-BFB3-1330C4840FF5/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:504:13
,2017-08-02 13:41:02 - DEBUG localSeqManager: 'Got an error trying to update seq {"error":"conflict","reason":"Document update conflict","name":"conflict","status":409,"message":"Document update conflict"}'
ok 1000 Our rev is old so we should fail
,# teardown
,2017-08-02 13:41:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - fail if stop is called
,ok 1001 confirm stop caused failure
,(node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
,Trace: 
    at $3.prototype.trace@console.js:139:8
    at addListener@events.js:140:1
    at module.exports@/private/var/containers/Bundle/Application/40D065A8-D634-4A4D-BFB3-1330C4840FF5/ThaliTest.app/www/jxcore/node_modules/pouchdb-all-dbs/lib/index.j,s:57:3
    at module.exports/<.start/<@/private/var/containers/Bundle/Application/40D065A8-D634-4A4D-BFB3-1330C4840FF5/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/lib/index.js:143:9
    at tryCatcher@/private/var/containers/Bundle/Application/4,0D065A8-D634-4A4D-BFB3-1330C4840FF5/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/util.js:16:16
    at module.exports/Promise.prototype._settlePromiseFromHandler@/private/var/containers/Bundle/Application/40D065A8-,D634-4A4D-BFB3-1330C4840FF5/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:504:13
,# teardown
,2017-08-02 13:41:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - stop after get but before put fails right
,2017-08-02 13:41:04 - DEBUG localSeqManager: 'Got an error trying to update seq {"onPut":true}'
,ok 1002 stop caused us to fail
,ok 1003 We specifically failed on a stop before put
,# teardown
,2017-08-02 13:41:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - fail if stop is called
,ok 1004 failed due to stop
,ok 1005 failed due to stop
,# teardown
,2017-08-02 13:41:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - set seq for first time
,ok 1006 should be equal
,# teardown
,2017-08-02 13:41:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - Fail on bad seq value
,2017-08-02 13:41:08 - DEBUG localSeqManager: 'Got a bad seq, submitted seq 9, _nextSeqValueToSend: 10'
,ok 1007 Expected bad seq error
,# teardown
,2017-08-02 13:41:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - do we cancel timer properly on an immediate?
,ok 1008 Different promises
,ok 1009 Timer was cancelled
,ok 1010 should be equal
,# teardown
,2017-08-02 13:41:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - do we wait for blocked update
,ok 1011 One go and one blocked
,ok 1012 All blocked
,ok 1013 Still blocked
,ok 1014 should be equal
,# teardown
,2017-08-02 13:41:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - test that we wait long enough
,ok 1015 We waited long enough
,ok 1016 should be equal
,# teardown
,2017-08-02 13:41:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - test that we pick up new sequences while we wait
,ok 1017 Should have gotten same timer promise
,ok 1018 Still same timer promise
,ok 1019 We waited long enough
,ok 1020 should be equal
,# teardown
,2017-08-02 13:41:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Coordinated seq test
,2017-08-02 13:41:19 - DEBUG CoordinatedClient: 'test was skipped, name: 'Coordinated seq test''
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:41:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:41:20 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
,# setup
,# test thali manager spies
,2017-08-02 13:41:20 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
,2017-08-02 13:41:20 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
,2017-08-02 13:41:20 - DEBUG thaliManager: 'creating express pouchdb instance'
,ok 1021 expressPouchDB was called once
ok 1022 expressPouchDB was called with 2 arguments
,ok 1023 expressPouchDB was called with 'PouchDB' as 1-st argument
,ok 1024 expressPouchDB was called with 'expressPouchDB options' as 2-st argument
,ok 1025 PouchDB was called once
,ok 1026 PouchDB was called with 1 arguments
,ok 1027 PouchDB was called with 'dbName' as 1-st argument
,ok 1028 ThaliSendNotificationBasedOnReplication was called once
,ok 1029 ThaliSendNotificationBasedOnReplication was called with 4 arguments
,ok 1030 ThaliSendNotificationBasedOnReplication was called with 'express.Router instance' as 1-st argument
,ok 1031 ThaliSendNotificationBasedOnReplication was called with 'ecdhForLocalDevice' as 2-st argument
,ok 1032 ThaliSendNotificationBasedOnReplication was called with 'thaliConfig.BEACON_MILLISECONDS_TO_EXPIRE' as 3-st argument
,ok 1033 ThaliSendNotificationBasedOnReplication was called with 'PouchDB instance' as 4-st argument
,ok 1034 ThaliPullReplicationFromNotification was called once
,ok 1035 ThaliPullReplicationFromNotification was called with 4 arguments
,ok 1036 ThaliPullReplicationFromNotification was called with 'PouchDB' as 1-st argument
,ok 1037 ThaliPullReplicationFromNotification was called with 'dbName' as 2-st argument
,ok 1038 ThaliPullReplicationFromNotification was called with 'ThaliPeerPoolInterface instance' as 3-st argument
,ok 1039 ThaliPullReplicationFromNotification was called with 'ecdhForLocalDevice' as 4-st argument
,ok 1040 Salti was called once
,ok 1041 Salti was called with 4 arguments
,ok 1042 Salti was called with 'dbName' as 1-st argument
,ok 1043 Salti was called with 'acl' as 2-st argument
,ok 1044 Salti was called with 'thaliIdCallback' as 3-st argument
,ok 1045 Salti was called with 'options' as 4-st argument
,2017-08-02 13:41:20 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
,2017-08-02 13:41:20 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-08-02 13:41:20 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-08-02 13:41:20 - DEBUG thaliMobileNativeWrapper: 'listening 49382'
,2017-08-02 13:41:20 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:B2BFED77-08FC-4551-9F15-AB9508AA1D3C
,[ThaliCore] Browser.startListening
,2017-08-02 13:41:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-02 13:41:20 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "024DCAC4-2CC6-4C28-ACA9-B06F3F28B64F", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:024DCAC4-2CC6-4C28-ACA9-B06F3F28B64F
,2017-08-02 13:41:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-08-02 13:41:20 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
,ok 1046 ThaliMobile.start was called once
,ok 1047 ThaliMobile.start was called with 3 arguments
ok 1048 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
,ok 1049 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
,ok 1050 ThaliMobile.start was called with 'networkType' as 3-st argument
,ok 1051 ThaliMobile.startListeningForAdvertisements was called once
,ok 1052 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
,ok 1053 ThaliMobile.startUpdateAdvertisingAndListening was called once
,ok 1054 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
,ok 1055 ThaliSendNotificationBasedOnReplication.prototype.start was called once
,ok 1056 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
,ok 1057 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
,ok 1058 ThaliPullReplicationFromNotification.prototype.start was called once
,ok 1059 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
,ok 1060 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
,2017-08-02 13:41:20 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:024DCAC4-2CC6-4C28-ACA9-B06F3F28B64F
,2017-08-02 13:41:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-02 13:41:20 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})'
2017-08-02 13:41:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-02 13:41:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:41:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:41:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 1061 ThaliMobile.stop was called once
ok 1062 ThaliMobile.stop was called with 0 arguments
ok 1063 ThaliSendNotificationBasedOnReplication.prototype.stop was called once
,ok 1064 ThaliSendNotificationBasedOnReplication.prototype.stop was called with 0 arguments
,ok 1065 ThaliPullReplicationFromNotification.prototype.stop was called once
,ok 1066 ThaliPullReplicationFromNotification.prototype.stop was called with 0 arguments
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:41:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:41:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,# teardown
,# setup
,# test thali manager multiple starts and stops
,2017-08-02 13:41:21 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
,2017-08-02 13:41:21 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
,2017-08-02 13:41:21 - DEBUG thaliManager: 'creating express pouchdb instance'
,ok 1067 expressPouchDB was called once
ok 1068 expressPouchDB was called with 2 arguments
ok 1069 expressPouchDB was called with 'PouchDB' as 1-st argument
ok 1070 expressPouchDB was called with 'expressPouchDB options' as 2-st argument
ok 1071 PouchDB was called once
,ok 1072 PouchDB was called with 1 arguments
,ok 1073 PouchDB was called with 'dbName' as 1-st argument
,ok 1074 ThaliSendNotificationBasedOnReplication was called once
ok 1075 ThaliSendNotificationBasedOnReplication was called with 4 arguments
,ok 1076 ThaliSendNotificationBasedOnReplication was called with 'express.Router instance' as 1-st argument
,ok 1077 ThaliSendNotificationBasedOnReplication was called with 'ecdhForLocalDevice' as 2-st argument
,ok 1078 ThaliSendNotificationBasedOnReplication was called with 'thaliConfig.BEACON_MILLISECONDS_TO_EXPIRE' as 3-st argument
,ok 1079 ThaliSendNotificationBasedOnReplication was called with 'PouchDB instance' as 4-st argument
,ok 1080 ThaliPullReplicationFromNotification was called once
,ok 1081 ThaliPullReplicationFromNotification was called with 4 arguments
,ok 1082 ThaliPullReplicationFromNotification was called with 'PouchDB' as 1-st argument
,ok 1083 ThaliPullReplicationFromNotification was called with 'dbName' as 2-st argument
,ok 1084 ThaliPullReplicationFromNotification was called with 'ThaliPeerPoolInterface instance' as 3-st argument
,ok 1085 ThaliPullReplicationFromNotification was called with 'ecdhForLocalDevice' as 4-st argument
,ok 1086 Salti was called once
,ok 1087 Salti was called with 4 arguments
,ok 1088 Salti was called with 'dbName' as 1-st argument
,ok 1089 Salti was called with 'acl' as 2-st argument
,ok 1090 Salti was called with 'thaliIdCallback' as 3-st argument
,ok 1091 Salti was called with 'options' as 4-st argument
,2017-08-02 13:41:21 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
,2017-08-02 13:41:21 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-08-02 13:41:21 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-08-02 13:41:21 - DEBUG thaliMobileNativeWrapper: 'listening 49384'
2017-08-02 13:41:21 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:DCF517A3-7A9F-4EF0-8F46-A21859B38B21
,[ThaliCore] Browser.startListening
,2017-08-02 13:41:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-02 13:41:21 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "D5551387-99F5-446B-AF8D-D62C67C5A32B", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:D5551387-99F5-446B-AF8D-D62C67C5A32B
2017-08-02 13:41:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-08-02 13:41:21 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
,ok 1092 ThaliMobile.start was called once
ok 1093 ThaliMobile.start was called with 3 arguments
,ok 1094 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
,ok 1095 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
ok 1096 ThaliMobile.start was called with 'networkType' as 3-st argument
,ok 1097 ThaliMobile.startListeningForAdvertisements was called once
,ok 1098 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
,ok 1099 ThaliMobile.startUpdateAdvertisingAndListening was called once
,ok 1100 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
,ok 1101 ThaliSendNotificationBasedOnReplication.prototype.start was called once
,ok 1102 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
,ok 1103 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
,ok 1104 ThaliPullReplicationFromNotification.prototype.start was called once
,ok 1105 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
,ok 1106 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
,2017-08-02 13:41:21 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:D5551387-99F5-446B-AF8D-D62C67C5A32B
,2017-08-02 13:41:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-02 13:41:21 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})'
,2017-08-02 13:41:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-08-02 13:41:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:41:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:41:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:41:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:41:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 1107 ThaliMobile.stop was called once
,ok 1108 ThaliMobile.stop was called with 0 arguments
,ok 1109 ThaliSendNotificationBasedOnReplication.prototype.stop was called once
,ok 1110 ThaliSendNotificationBasedOnReplication.prototype.stop was called with 0 arguments
,ok 1111 ThaliPullReplicationFromNotification.prototype.stop was called once
,ok 1112 ThaliPullReplicationFromNotification.prototype.stop was called with 0 arguments
,2017-08-02 13:41:21 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
,2017-08-02 13:41:21 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-08-02 13:41:21 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-08-02 13:41:21 - DEBUG thaliMobileNativeWrapper: 'listening 49386'
2017-08-02 13:41:21 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:24CC51B8-5EC0-44E7-99D4-3704118D86A8
,[ThaliCore] Browser.startListening
,2017-08-02 13:41:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-02 13:41:21 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "42A6F39F-8990-4217-BB8C-5FA3BE14D3B7", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:42A6F39F-8990-4217-BB8C-5FA3BE14D3B7
,2017-08-02 13:41:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-08-02 13:41:21 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
,2017-08-02 13:41:21 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:42A6F39F-8990-4217-BB8C-5FA3BE14D3B7
,2017-08-02 13:41:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-02 13:41:21 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})'
2017-08-02 13:41:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-02 13:41:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02, 13:41:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-02 13:41:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:41:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:41:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:41:21 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2017-08-02 13:41:21 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-08-02 13:41:21 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-08-02 13:41:21 - DEBUG thaliMobileNativeWrapper: 'listening 49388'
,2017-08-02 13:41:21 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:373EB675-0694-4602-8C68-6764554924F5
[ThaliCore] Browser.startListening
,2017-08-02 13:41:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-02 13:41:21 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "E3FF2631-9E54-4785-82EC-C82D46FBE9B2", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:E3FF2631-9E54-4785-82EC-C82D46FBE9B2
,2017-08-02 13:41:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-08-02 13:41:21 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
,2017-08-02 13:41:21 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:E3FF2631-9E54-4785-82EC-C82D46FBE9B2
,2017-08-02 13:41:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-02 13:41:21 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})'
2017-08-02 13:41:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-08-02 13:41:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:41:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-02 13:41:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:41:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:41:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:41:21 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2017-08-02 13:41:21 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-08-02 13:41:21 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-08-02 13:41:21 - DEBUG thaliMobileNativeWrapper: 'listening 49390'
,2017-08-02 13:41:21 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:312BF840-0077-4607-96A1-36CE89418509
,[ThaliCore] Browser.startListening
,2017-08-02 13:41:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-02 13:41:21 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "9E0FCD45-99A7-4A86-8D72-52899878B135", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:9E0FCD45-99A7-4A86-8D72-52899878B135
,2017-08-02 13:41:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-08-02 13:41:21 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
,ok 1113 ThaliMobile.start was called once
,ok 1114 ThaliMobile.start was called with 3 arguments
,ok 1115 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
,ok 1116 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
,ok 1117 ThaliMobile.start was called with 'networkType' as 3-st argument
,ok 1118 ThaliMobile.startListeningForAdvertisements was called once
,ok 1119 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
,ok 1120 ThaliMobile.startUpdateAdvertisingAndListening was called once
,ok 1121 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
,ok 1122 ThaliSendNotificationBasedOnReplication.prototype.start was called once
,ok 1123 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
,ok 1124 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
,ok 1125 ThaliPullReplicationFromNotification.prototype.start was called once
,ok 1126 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
,ok 1127 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
,2017-08-02 13:41:21 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:9E0FCD45-99A7-4A86-8D72-52899878B135
,2017-08-02 13:41:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-02 13:41:21 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})'
2017-08-02 13:41:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state,).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-08-02 13:41:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:41:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-02 13:41:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:41:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:41:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,# teardown
,# setup
,# ssdp server and client should be restarted when wifi toggled
,2017-08-02 13:41:22 - DEBUG CoordinatedClient: 'test was skipped, name: 'ssdp server and client should be restarted when wifi toggled''
,# teardown
,# setup
,# ssdp server and client should be restarted when bssid changed
,2017-08-02 13:41:23 - DEBUG CoordinatedClient: 'test was skipped, name: 'ssdp server and client should be restarted when bssid changed''
,# teardown
,# setup
,# ssdp server and client should be restarted only when advertising/listening is active
,2017-08-02 13:41:23 - DEBUG CoordinatedClient: 'test was skipped, name: 'ssdp server and client should be restarted only when advertising/listening is active''
,# teardown
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll can close even when connections open'
2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll with promise'
2017-08-02 13:41:23 - INFO, CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning set to false'
2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll works even with a server ,that is not listening yet witheatNotRunning set to true'
2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on a single db change'
2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOG,GER result: skipped - Call of multiple onCheckpointReached handlers on a single db change'
2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are in the checkpoi,n,ts plugin delay interval'
2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval'
2017-08-02 13:41:23 - INFO Coordin,atedClient: '***TEST_LOGGER result: passed - test defaultDirectory'
2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultAdapter'
2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueue, and run in order'
2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueueAtTop and run backwards'
2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - mix enqueue and enqueueAtTop'
2017-08-02 13:,41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - queues handled independently'
2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueued function are always executed asynchronously'
2017-08-02 13:41:23 - INF,O, CoordinatedClient: '***TEST_LOGGER result: passed - exceptions in the executor are properly handled'
2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - basic'
2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER resu,lt: passed - another'
2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - skip'
2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - another skip'
2017-08-02 13:41:23 - INFO CoordinatedClient: '***T,EST_LOGGER result: passed - test sinon sansbox spy'
2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub'
2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox ,stub override'
2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox mock'
2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox restore after test end'
2017-08-02 ,1,3:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can pass data in setup'
2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Correctly parses/stringifies USN'
2017-08-02 13:41:23 - INFO CoordinatedClient: '***,TEST_LOGGER result: skipped - onPeerLost calls jxcore'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerDiscovered calls jxcore'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopListeningForAdvertisements'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startListeningForAdvertisements twice is NOT an error'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling stopListeningForAdvertisements without calling start is NOT an error'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopUpdateAdvertisingAndListening'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startUpdateAdvertisingAndListening twice is NOT an error'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call stopUpdateAdvertisingAndListening twice without start and it is not an error'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChange is called'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can connect to a remote peer'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data via parallel connections'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data securely'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift large amounts of data'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We do not emit peerAvailabilityChanged events until one of the start methods is called'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Test updating advertising and parallel data transfer'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - discoveryAdvertisingStateUpdateNonTCP is called'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - cannot call connect when start listening for advertisements is not active'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Get error when trying to double connect to a peer on Android'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect when start listening for advertisements is not active'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with illegal peerID'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiConnect properly fails on legal but non-existent peerID'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with invalid syncValue'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call disconnect with invalid peer id'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - disconnect doesn't fail on plausible but bogus peer ID'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Get same port when trying to connect multiple times on iOS'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - initial peer discovery'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 1'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 2'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - check latest peer discovery'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Set up for no peer discovery test'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - no peer discovery'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling createNativeListener directly rejects'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits incomingConnectionState'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits routerPortConnectionFailed'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server connections all up'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming stream cleans outgoing socket'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming connection cleans outgoing socket'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing outgoing socket cleans associated mux stream'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing the whole server cleans everything up'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - we can get a ton of connections and data through and still clean up the server completely'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - simulate mux failure, make sure everything is cleaned up'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - timing out the incoming connection cleans everything up'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can create servers manager'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling stop without start causes error'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can start/stop servers manager'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - starting twice resolves with listening port'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminateIncomingConnection will terminate a connection'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminate an Outgoing connection'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single local http request'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single coordinated request ios native'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Multiple local http requests'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Multiple coordinated request ios native'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startListeningForAdvertisements should fail if start not called'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if start not called'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - should be able to call #stopListeningForAdvertisements many times'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startListeningForAdvertisements many times'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startUpdateAdvertisingAndListening many times'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopAdvertisingAndListening many times'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get the network status before starting'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - error returned with bad router'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - all services are started when we call start'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - TCP Servers Manager should be null when we call start on iOS'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - all services are stopped when we call stop'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure terminateConnection is properly hooked up'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure terminateConnection is return error if we get called on iOS'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure terminateListener is properly hooked up'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure terminateListener is return error if we get called on iOS'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure we actually call kill connections properly'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire failedNativeConnection event when we get failedConnection from multiConnectConnection'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure bad PSK connections fail'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - peer changes handled from a queue'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - relaying discoveryAdvertisingStateUpdateNonTCP'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - we successfully receive and replay discoveryAdvertisingStateUpdate'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - can do HTTP requests between peers'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - can still do HTTP requests between peers with coordinator'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - calls correct starts when network changes'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test to coordinate connection cut'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can do HTTP requests after connections are cut'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - will fail bad PSK connection between peers'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We provide notification when a listener dies and we recreate it'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startListeningForAdvertisements should fail if start not called'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if start not called'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopListeningForAdvertisements many times'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startListeningForAdvertisements many times'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startUpdateAdvertisingAndListening many times'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopAdvertisingAndListening many times'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #start - Causing native or wifi to fail will cause a promise reject '
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #start should fail if called twice in a row'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - does not emit duplicate discoveryAdvertisingStateUpdate'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - does not send duplicate availability changes'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get the network status'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer added/removed to/from cache (native)'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer added/removed to/from cache (wifi)'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - new peer is cached'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - native available - peer with same port and different generation is cached (BLUETOOTH)'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - peer with greater generation is cached (MPCF)'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - peer with same or older generation is ignored (MPCF)'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native unavailable - new peer is ignored'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native unavailable - cached peer is removed'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - networkChanged - fires peerAvailabilityChanged event for wifi peers'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiconnect failure - new peer is ignored (MPCF)'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - newAddressPort field (TCP_NATIVE)'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - newAddressPort field (BLUETOOTH)'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - newAddressPort field (MPCF)'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - error when peer has not been discovered yet'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - returns discovered cached wifi peer'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #disconnect fails on wifi peers'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #disconnect delegates native peers to the native wrapper'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes emitted correctly'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes not emitted in started state'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes not emitted in stopped state'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We properly fire peer unavailable and then available when connection fails on Android'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We properly fire peer unavailable and then available when connection fails on iOS'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - does not fire duplicate events after peer listener recreation'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #stop should change peers'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - peer should be found once after listening and discovery started'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get data from all participants'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - test for data corruption'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - test getters'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - start and kill'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - double start'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - start after kill'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - make sure ids are unique'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - check that forever agent can be destroyed'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test PeerDictionary basic functionality'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test PeerDictionary with multiple entries.'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - RESOLVED entries are removed before WAITING state entry.'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - WAITING entries are removed before CONTROLLED_BY_POOL state entry.'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - When CONTROLLED_BY_POOL entry is removed and kill is called.'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - single action'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - multiple actions'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - PSK Pool works'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - stop'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure that start verifies queue length'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - bad enqueues'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - do not allow same object type'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure we catch kill and dequeue'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure that stop removes all actions'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We reject unrecognized connection type'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We reject unrecognized action type'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - One action on bluetooth'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Two notification actions'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - replicateThroughProblems'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Replication goes first'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - wifi allows many parallel non-replication actions'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - wifi allows no more than 2 simultaneous replication actions for same peerID'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Client to server request coordinated'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test BEACONS_RETRIEVED_AND_PARSED locally'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Test HTTP_BAD_RESPONSE locally'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test NETWORK_PROBLEM locally'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Action fails when getPeerHostInfo fails'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the start two times'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill before calling the start'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill immediately after the start'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill while waiting a response from the server'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test to exceed the max content size locally'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Close the server socket while the client is waiting a response from the server. Local test.'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Close the client socket while the client is waiting a response from the server. Local test.'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons bad args'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons empty keys to notify'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons multiple keys to notify'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid expiration in beaconStreamWithPreAmble'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons expiration out of range lower'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons expiration out of range lower'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons no beacons returns null'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback fails decrypt'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #parseBeacons addressBookCallback returns no matches'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns spurious match'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns public key'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskIdentityField'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskSecret'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskSecrets'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generateBeaconStreamAndSecrets'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Add two Peers.'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - TCP_NATIVE peer loses DNS'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Received beacons with no values for us'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Notification action killed with a superseded'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Resolves an action locally'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Emits error event when peerPool.enqueue throws'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Resolves an action locally using ThaliPeerPoolDefault'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Action fails because of a bad hostname.'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - hostaddress is removed when the action is running. '
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - notificationClient does not retry action with BAD_PEER resolution'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - notification client correctly handles peer availability changes of the same peer'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Client to server request locally'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache clean and expiration'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache getSecret and getPublic'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache multiple entries'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Start and stop ThaliNotificationServer'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass an empty array to ThaliNotificationServer.start'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass a string to ThaliNotificationServer.start'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass an empty parameter to ThaliNotificationServer.start'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeacons'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeacons (no keys)'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeaconsbefore calling start'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure peerDictionaryKey is reasonable'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure start works'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure stop works'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Emits error event when peerPool.enqueue throws'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Simple peer event'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Coordinated pull replication from notification test'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server is not there'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server accepts & closes connection'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server always returns 500'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server always returns 401'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server always returns 403'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure docs replicate with remote db with same name as local db'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure docs replicate with remote db with different name than local db'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Do nothing and make sure we time out'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Do something and make sure we time out'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Start replicating and then catch error when server goes'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure clone works'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Coordinated replication action test - each device has the same local db name'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Coordinated replication action test - each device has different local db name'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Coordinated replication action test - should throw error when wrong remote db name is provided'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - compareBufferArrays'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call start twice and get error'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Start and make sure it runs'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure getTimeWhenRun is right after start'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure getTimeWhenRun is -1 after function is called'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test TransientState'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - No peers and empty database'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - One peer and empty DB'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - One peer with _Local set behind current seq'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - One peer with _Local set equal to current seq'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - One peer with _Local set ahead of current seq (and no this should not happen)'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Three peers, one not in DB, one behind and one ahead'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - More than maximum peers, make sure we only send maximum allowed'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - two peers with empty DB, update the doc'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - add doc and make sure tokens refresh when they expire'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - start and stop and start and stop'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - two identical starts in a row'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - two different starts in a row'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - two stops and a start and two stops'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - we properly enqueue requests so no then needed'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test calculateSeqPointKeyId'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - server is not there'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - server accepts & closes connection'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - server always returns 500'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - create new seq doc'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - doc exists, need to get rev and update'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - update seq three times'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - rev got changed under us'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - fail if stop is called'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - stop after get but before put fails right'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #update - fail if stop is called'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #update - set seq for first time'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #update - Fail on bad seq value'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #update - do we cancel timer properly on an immediate?'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #update - do we wait for blocked update'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #update - test that we wait long enough'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #update - test that we pick up new sequences while we wait'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Coordinated seq test'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test thali manager spies'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test thali manager multiple starts and stops'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - ssdp server and client should be restarted when wifi toggled'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - ssdp server and client should be restarted when bssid changed'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - ssdp server and client should be restarted only when advertising/listening is active'
,2017-08-02 13:41:23 - DEBUG CoordinatedClient: 'all unit tests succeeded, platformName: 'ios''
,2017-08-02 13:41:24 - DEBUG CoordinatedClient: 'all tests completed'
,2017-08-02 13:41:24 - DEBUG CoordinatedClient: 'test client disconnected'
,2017-08-02 13:41:24 - DEBUG CoordinatedClient: 'test client succeed'
,2017-08-02 13:41:24 - DEBUG CoordinatedThaliTape: 'all tests succeed'
,2017-08-02 13:41:24 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****'

```
