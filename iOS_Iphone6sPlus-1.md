#### Test 113351851ac4367c_iOS_Iphone6sPlus-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/113351851ac4367c/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6s Plus 'Iphone6sPlus-1' (f70cda60583ea0f895d05ea355cd125983c27594) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/325C0627-699C-4C6B-86D8-86507207AF5F/fruitstrap-lldb-prep-cmds-f70cda60583ea0f895d05ea355cd125983c27594'
,Executing commands in '/tmp/325C0627-699C-4C6B-86D8-86507207AF5F/fruitstrap-lldb-prep-cmds-f70cda60583ea0f895d05ea355cd125983c27594'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/113351851ac4367c/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/113351851ac4367c/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/83F91E1F-B78B-4AAD-A7C2-E59ED0838EAA/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61158"
,(lldb)     command script import "/tmp/325C0627-699C-4C6B-86D8-86507207AF5F/fruitstrap_f70cda60583ea0f895d05ea355cd125983c27594.py"
,(lldb)     command script add -f fruitstrap_f70cda60583ea0f895d05ea355cd125983c27594.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_f70cda60583ea0f895d05ea355cd125983c27594.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_f70cda60583ea0f895d05ea355cd125983c27594.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_f70cda60583ea0f895d05ea355cd125983c27594.safequit_command safequit
,(lldb)     connect
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
,2017-07-14 12:37:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 12:37:11 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 12:37:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:37:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 12:37:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:37:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:37:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
AppContextTests.test_didEnterForeground finished
,AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
AppContextTests.test_esonValue finished
[ThaliCore] AdvertiserMa,nager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "EE25A1E8-78BD-4A55-8962-6F52B917C29E", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:EE25A1E8-78BD-4A55-8962-6F52B917C29E
,Optional(true)
Optional(false)
AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:7C25905A-1714-4B8D-8BA9-3D495DBE4CFB
[ThaliCore] Browser.startListening
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:fo,undPeer:lostPeer:) peer:A47F09E3-6FAC-4AA8-8F6A-EB4545DC7B52
[ThaliCore] Browser.startListening
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "5DA600C9-CBE9-4ED4-9AB2-FD2D0822CC1C", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:5DA600C9-CBE9-4ED4-9AB2-FD2D0822CC1C
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5DA600C9-CBE9-4ED4-9AB2-FD2D0822CC1C:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5DA600C9-CBE9-4ED4-9AB2-FD2D0822CC1C", generation: 0)
AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvaila,bilityConversion finished
AppContextTests.test_disconnectErrors finished
AppContextTests.test_connectReturnValueCorrect finished
AppContextTests finished
All tests finished
All tests finished
2017-07-14 12:37:13 - DEBUG UnitTest_app: 'Running unit te,sts'
*Native tests were executed*
Total number of executed tests:  13
Number of passed tests:  13
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  1.590132117271423
2017-07-14 12:37:13 - DEBUG UnitTest_app: 'My device name is: 'Apple-Iphone6sPlus-1''
,2017-07-14 12:37:13 - WARN testUtils: 'myNameCallback not set!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:5DA600C9-CBE9-4ED4-9AB2-FD2D0822CC1C:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "5DA600C9-CBE9-4ED4-9AB2-FD2D0822CC1C", generation: 0)
,2017-07-14 12:37:15 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-07-14 12:37:15 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/83F91E1F-B78B-4AAD-A7C2-E59ED0838EAA/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-07-14 12:37:15 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/83F91E1F-B78B-4AAD-A7C2-E59ED0838EAA/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-07-14 12:37:15 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/83F91E1F-B78B-4AAD-A7C2-E59ED0838EAA/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-07-14 12:37:15 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/83F91E1F-B78B-4AAD-A7C2-E59ED0838EAA/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-07-14 12:37:15 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/83F91E1F-B78B-4AAD-A7C2-E59ED0838EAA/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-07-14 12:37:15 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/83F91E1F-B78B-4AAD-A7C2-E59ED0838EAA/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-07-14 12:37:15 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/83F91E1F-B78B-4AAD-A7C2-E59ED0838EAA/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-07-14 12:37:15 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/83F91E1F-B78B-4AAD-A7C2-E59ED0838EAA/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-07-14 12:37:15 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/83F91E1F-B78B-4AAD-A7C2-E59ED0838EAA/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-07-14 12:37:15 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/83F91E1F-B78B-4AAD-A7C2-E59ED0838EAA/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-07-14 12:37:15 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/83F91E1F-B78B-4AAD-A7C2-E59ED0838EAA/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-07-14 12:37:15 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/83F91E1F-B78B-4AAD-A7C2-E59ED0838EAA/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-07-14 12:37:15 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/83F91E1F-B78B-4AAD-A7C2-E59ED0838EAA/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-07-14 12:37:15 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/83F91E1F-B78B-4AAD-A7C2-E59ED0838EAA/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-07-14 12:37:15 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/83F91E1F-B78B-4AAD-A7C2-E59ED0838EAA/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-07-14 12:37:15 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/83F91E1F-B78B-4AAD-A7C2-E59ED0838EAA/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-07-14 12:37:15 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/83F91E1F-B78B-4AAD-A7C2-E59ED0838EAA/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-07-14 12:37:15 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/83F91E1F-B78B-4AAD-A7C2-E59ED0838EAA/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-07-14 12:37:15 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/83F91E1F-B78B-4AAD-A7C2-E59ED0838EAA/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-07-14 12:37:15 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/83F91E1F-B78B-4AAD-A7C2-E59ED0838EAA/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-07-14 12:37:15 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/83F91E1F-B78B-4AAD-A7C2-E59ED0838EAA/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-07-14 12:37:15 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/83F91E1F-B78B-4AAD-A7C2-E59ED0838EAA/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-07-14 12:37:15 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/83F91E1F-B78B-4AAD-A7C2-E59ED0838EAA/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-07-14 12:37:15 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/83F91E1F-B78B-4AAD-A7C2-E59ED0838EAA/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-07-14 12:37:15 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/83F91E1F-B78B-4AAD-A7C2-E59ED0838EAA/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-07-14 12:37:16 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/83F91E1F-B78B-4AAD-A7C2-E59ED0838EAA/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-07-14 12:37:16 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/83F91E1F-B78B-4AAD-A7C2-E59ED0838EAA/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-07-14 12:37:16 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/83F91E1F-B78B-4AAD-A7C2-E59ED0838EAA/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-07-14 12:37:16 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/83F91E1F-B78B-4AAD-A7C2-E59ED0838EAA/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-07-14 12:37:16 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/83F91E1F-B78B-4AAD-A7C2-E59ED0838EAA/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-07-14 12:37:16 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/83F91E1F-B78B-4AAD-A7C2-E59ED0838EAA/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-07-14 12:37:16 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/83F91E1F-B78B-4AAD-A7C2-E59ED0838EAA/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-07-14 12:37:16 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/83F91E1F-B78B-4AAD-A7C2-E59ED0838EAA/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-07-14 12:37:16 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/83F91E1F-B78B-4AAD-A7C2-E59ED0838EAA/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-07-14 12:37:16 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/83F91E1F-B78B-4AAD-A7C2-E59ED0838EAA/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-07-14 12:37:16 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/83F91E1F-B78B-4AAD-A7C2-E59ED0838EAA/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-07-14 12:37:16 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/83F91E1F-B78B-4AAD-A7C2-E59ED0838EAA/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-07-14 12:37:16 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/83F91E1F-B78B-4AAD-A7C2-E59ED0838EAA/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-07-14 12:37:16 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/83F91E1F-B78B-4AAD-A7C2-E59ED0838EAA/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-07-14 12:37:16 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/83F91E1F-B78B-4AAD-A7C2-E59ED0838EAA/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-07-14 12:37:16 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-07-14 12:37:16 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
,2017-07-14 12:37:17 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
,# setup
,# closeAll can close even when connections open
,2017-07-14 12:39:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 1 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll with promise
,2017-07-14 12:39:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 2 not possible to connect to the server anymore
# teardown
,# setup
,# closeAll properly throws when closing a non open server with eatNotRunning set to false
,2017-07-14 12:39:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
# teardown
,# setup
,# closeAll works even with a server that is not listening yet witheatNotRunning set to true
,2017-07-14 12:39:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
,# setup
,# Call of onCheckpointReached handler on a single db change
,2017-07-14 12:39:24 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on a single db change''
,# teardown
,# setup
,# Call of multiple onCheckpointReached handlers on a single db change
,2017-07-14 12:39:26 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of multiple onCheckpointReached handlers on a single db change''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
,2017-07-14 12:39:30 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
,2017-07-14 12:39:32 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''
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
,2017-07-14 12:39:40 - DEBUG CoordinatedClient: 'test was skipped, name: 'skip''
,# teardown
,# setup
,# another skip
,2017-07-14 12:39:40 - DEBUG CoordinatedClient: 'test was skipped, name: 'another skip''
,# teardown
,# setup
,# test sinon sansbox spy
,2017-07-14 12:39:41 - DEBUG testTests: 'test spy method for global sinon sansbox'
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
,2017-07-14 12:39:45 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
,# teardown
,2017-07-14 12:39:45 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 12:39:45 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:39:45 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:39:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 12:39:45 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 12:39:45 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 12:39:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-14 12:39:45 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# onPeerDiscovered calls jxcore
,2017-07-14 12:39:45 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
,# teardown
,2017-07-14 12:39:46 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 12:39:46 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:39:46 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:39:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 12:39:46 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 12:39:46 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 12:39:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-14 12:39:46 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-14 12:39:46 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 12:39:46 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:39:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:39:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 12:39:46 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 12:39:46 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 12:39:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-14 12:39:46 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can call start/stopListeningForAdvertisements
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:BE74522A-DC2D-456F-A6CB-996BB17FF9F7
[ThaliCore] Browser.startListening
,2017-07-14 12:39:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-14 12:39:46 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 12:39:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 62 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-14 12:39:46 - DEBUG thaliMobileNativeWrapper: 'disco,veryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:39:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 63 Can call stopListeningForAdvertisements without e,r,ror
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-14 12:39:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:39:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 64 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 12:39:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:39:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 65 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-14 12:39:47 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 12:39:47 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:39:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:39:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 12:39:47 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 12:39:47 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 12:39:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-14 12:39:47 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Calling startListeningForAdvertisements twice is NOT an error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:3F58A0FD-C55F-422F-B95D-5B6FDC315839
[ThaliCore] Browser.startListening
,2017-07-14 12:39:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-14 12:39:48 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 12:39:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 66 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
2017-07-14 12:39:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"di,scoveryActive":true,"advertisingActive":false}'
2017-07-14 12:39:48 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":",B,OTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 12:39:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 67 Can call startListeningForAdvertisements twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-14 12:39:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14, 12:39:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 68 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-14 12:39:49 - DEBUG thal,iMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:39:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 69 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-14 12:39:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 12:39:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:39:49 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:39:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 12:39:49 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 12:39:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 12:39:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-14 12:39:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Calling stopListeningForAdvertisements without calling start is NOT an error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-14 12:39:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:39:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 70 Can call stopListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-14 12:39:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:39:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 71 Can call sto,pListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-14 12:39:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:39:53 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 72 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 12:39:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:39:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 73 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-14 12:39:53 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 12:39:53 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:39:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:39:53 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 12:39:53 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 12:39:53 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 12:39:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-14 12:39:53 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can call start/stopUpdateAdvertisingAndListening
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "4399775C-27C2-4F31-A2D7-E0BDA0C26C33", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:4399775C-27C2-4F31-A2D7-E0BDA0C26C33
,2017-07-14 12:39:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 12:39:54 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 12:39:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 74 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
2017-07-14 12:39:54 - DEBUG thaliMobileNativeWrapper: 'discovery,AdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:39:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 75 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-14 12:39:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:39:55 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 76 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-14 12:39:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdver,tisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:39:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 77 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-14 12:39:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 12:39:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:39:56 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:39:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 12:39:56 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 12:39:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:39:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
2017-07-14 12:39:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Calling startUpdateAdvertisingAndListening twice is NOT an error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "2C5B5713-6645-4963-BC2D-4BBAE87CABAB", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:2C5B5713-6645-4963-BC2D-4BBAE87CABAB
,2017-07-14 12:39:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 12:39:56 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 12:39:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 78 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "2C5B5713-6645-4963-BC2D-4BBAE87CABAB", generation: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:2C5B5713-6645-4963-BC2D-4BBAE87CABAB
2017-07-14 1,2:39:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 12:39:56 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 12:39:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 79 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-14 12:39:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 12:39:59 - INFO thaliMobile: 'Receive,d state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 12:3,9:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 80 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertisin,g()
[ThaliCore] Advertiser.stopAdvertising()
,2017-07-14 12:39:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:39:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 81 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-14 12:40:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 12:40:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:40:06 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:40:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 12:40:06 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 12:40:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 12:40:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-14 12:40:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-14 12:40:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:40:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 82 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-14 12:40:22 - DEBUG th,aliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:40:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 83 Can call stopAdverti,singAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-14 12:40:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:40:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 84 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 12:40:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:40:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 85 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-14 12:40:27 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 12:40:27 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:40:27 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:40:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 12:40:27 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 12:40:27 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 12:40:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-14 12:40:27 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# peerAvailabilityChange is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "3C925756-E54C-43A8-85BF-9E1651BC74ED", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:3C925756-E54C-43A8-85BF-9E1651BC74ED
2017-07-14 1,2:40:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-14 12:40:28 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-14 12:40:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 86 Can call startUpdateAdvertisingAndListeningwithout error
[ThaliCore] BrowserManager.startListeningForAdv,ertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:7A914E08-E042-44F8-B815-57F9B027813A
[ThaliCore] Browser.startListening
2017-07-14 12:40:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryA,ctive":true,"advertisingActive":true}'
2017-07-14 12:40:28 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","sta,r,tArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 12:40:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 87 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D768C9AD-0186-4DCA-B627-720F1CFF507B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D768C9AD-0186-4DCA-B627-720F1CFF507B", generation: 0)
ok 88 peers must be an array,
ok 89 peers must not be zero-length
ok 90 peer must have only peerIdentifier, peerAvailable and generation properties
ok 91 peerIdentifier must be a string
ok 92 generation must be a number
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:EBFCCF03-A21B-4FC3-AD11-14753B232823:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "EBFCCF03-A21B-4FC3-AD11-14753B232823", generation: 0)
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-14 12:40:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 ,12:40:29 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-14 12:40:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 93 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
,2017-07-14 12:40:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:40:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 94 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-14 12:40:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 12:40:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:40:30 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:40:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 12:40:30 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 12:40:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 12:40:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-14 12:40:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can connect to a remote peer
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "CAC774EE-985F-4EB8-98CB-836275DBB8DB", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:CAC774EE-985F-4EB8-98CB-836275DBB8DB
2017-07-14 1,2:40:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 12:40:32 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 12:40:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 95 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:DBB085BB-4E90-4045-A376-4108412178F3
[Thal,i,Core] Browser.startListening
2017-07-14 12:40:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-14 12:40:32 - INFO thaliMobile: 'Received state ({"discoveryActive":true,,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 12:40:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 96 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CAC774EE-985F-4EB8-98CB-836275DBB8DB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CAC774EE-985F-4EB8-98CB-836275DBB8DB", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:8AAD9A3E-939A-4A26-B19E-1F26CF192571
[ThaliCore] Advertiser: session connected Peer(uuid: "CAC774EE-985F-4EB8-98CB-836275DBB8DB", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:8AAD9A3E-939A-4A26-B19E-1F26CF192571 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:DC378D7C-FBBE-465D-A82A-96AFD7A5FDD0
[ThaliCore] Advertiser: session connected Peer(uuid: "CAC774EE-985F-4EB8-98CB-836275DBB8DB", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:DC378D7C-FBBE-465D-A82A-96AFD7A5FDD0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0D72AE22-FA55-4054-B2AE-210720329C10:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0D72AE22-FA55-4054-B2AE-210720329C10", generation: 0)
2017-07-14 12:40:34 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"0D72AE22-FA55-4054-B2AE-210720329C10","generation":0}'
2017-07-14 12:40:34 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 0D72AE22-FA55-4054-B2AE-210720329C10, (syncValue: o7nVuknSgAMMQruoItnUfUxkEtnsulgn)'
2017-07-14 12:40:34 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "0D72AE22-FA55-4054-B2AE-210720329C10", gen,eration: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "0D72AE22-FA55-4054-B2AE-210720329C10", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:0D72AE22-FA55-,4054-B2AE-210720329C10:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:381534BF-0A7C-4DD9-BB76-E7FC86950E7A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "381534BF-0A7C-4DD9-BB76-E7FC86950E7A", generation: 0)
,2017-07-14 12:40:34 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"381534BF-0A7C-4DD9-BB76-E7FC86950E7A","generation":0}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:0D72AE22-FA55-4054-B2AE-210720329C10:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:8AAD9A3E-939A-4A26-B19E-1F26CF192571
,[ThaliCore] Session.session(_:peer:didChange:) peer:8AAD9A3E-939A-4A26-B19E-1F26CF192571 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:DC378D7C-FBBE-465D-A82A-96AFD7A5FDD0
,[ThaliCore] Session.session(_:peer:didChange:) peer:DC378D7C-FBBE-465D-A82A-96AFD7A5FDD0 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:0D72AE22-FA55-4054-B2AE-210720329C10:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:0D72AE22-FA55-4054-B2AE-210720329C10:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "0D72AE22-FA55-4054-B2AE-210720329C10", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50421
2017-07-14 12:40:37 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"o7nVuknSgAMMQruoItnUfUxkEtnsulgn","error":null,"portNumber":50421}'
,2017-07-14 12:40:37 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'o7nVuknSgAMMQruoItnUfUxkEtnsulgn', error: 'null', listeningPort: '50421''
,2017-07-14 12:40:37 - INFO testThaliMobileNative: ''
,ok 97 Must have listeningPort
,ok 98 listeningPort must be a number
,ok 99 listening port should not be 0
,# teardown
,2017-07-14 12:40:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-14 12:40:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 12:40:37 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 12:40:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 100 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
2017-07-14 12:40:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTC,P: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:40:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 101 Should be able to call stopAdvertisingAndListening in teardown
[ThaliCore] Brow,serManager.disconnect peer:0D72AE22-FA55-4054-B2AE-210720329C10
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50421
[ThaliCore] Session.disconnect() peer:0D72AE22,-FA55-4054-B2AE-210720329C10:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] Session.session(_:peer:didChange:) peer:0D72AE22-FA55-4054-B2AE-210720329C10:0 state: connected -> notConnected
[ThaliCore] ,B,rowser: session notConnected Peer(uuid: "0D72AE22-FA55-4054-B2AE-210720329C10", generation: 0)
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "0D72AE22-FA55-4054-B2AE-210720329C10", generation: 0)
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:8AAD9A3E-939A-4A26-B19E-1F26CF192571 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "CAC774EE-985F-4EB8-98CB-836275DBB8DB", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
,[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
,[ThaliCore] Session.disconnect() peer:DC378D7C-FBBE-465D-A82A-96AFD7A5FDD0
[ThaliCore] Session.deinit peer:DC378D7C-FBBE-465D-A82A-96AFD7A5FDD0
[ThaliCore] AdvertiserRelay.deinit
,2017-07-14 12:40:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 12:40:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:40:38 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:40:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 12:40:38 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 12:40:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 12:40:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-14 12:40:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can shift data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "4AAB776C-211D-47ED-BBDD-F924EF51954D", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:4AAB776C-211D-47ED-BBDD-F924EF51954D
2017-07-14 1,2:40:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 12:40:38 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 12:40:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 102 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browse,r.init(serviceType:foundPeer:lostPeer:) peer:BCED68A6-B186-489D-8C70-DAA9CAE7C8CA
[ThaliCore] Browser.startListening
2017-07-14 12:40:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive",:true}'
2017-07-14 12:40:38 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"psk,IdToSecret":null,"networkType":null}})'
2017-07-14 12:40:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 103 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DBC05482-D5B6-4F51-A692-E8C2855F7F2F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DBC05482-D5B6-4F51-A692-E8C2855F7F2F", generation: 0)
2017-07-14 12:40:39 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"DBC05482-D5B6-4F51-A692-E8C2855F7F2F","generation":0}'
2017-07-14 12:40:39 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for DBC05482-D5B6-4F51-A692-E8C2855F7F2F, (syncValue: WibIt4w1NHGn3tSba1QypsIT8lqQBVUu)'
2017-07-14 12:40:39 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "DBC05482-D5B6-4F51-A692-E8C2855F7F2F", gen,eration: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "DBC05482-D5B6-4F51-A692-E8C2855F7F2F", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:DBC05482-D5B6-4,F51-A692-E8C2855F7F2F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4AAB776C-211D-47ED-BBDD-F924EF51954D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4AAB776C-211D-47ED-BBDD-F924EF51954D", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B5A79CA8-4B6D-42E9-A632-564AB2A52DDA:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B5A79CA8-4B6D-42E9-A632-564AB2A52DDA", generation: 0)
2017-07-14 12:40:40 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B5A79CA8-4B6D-42E9-A632-564AB2A52DDA","generation":0}'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:18F8B334-CA3B-4F8D-9B49-5E164A8197FE
[ThaliCore] Advertiser: session connected Peer(uuid: "4AAB776C-211D-47ED-BBDD-F924EF51954D", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:18F8B334-CA3B-4F8D-9B49-5E164A8197FE state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:DBC05482-D5B6-4F51-A692-E8C2855F7F2F:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:DBC05482-D5B6-4F51-A692-E8C2855F7F2F:0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:18F8B334-CA3B-4F8D-9B49-5E164A8197FE
,[ThaliCore] Session.session(_:peer:didChange:) peer:DBC05482-D5B6-4F51-A692-E8C2855F7F2F:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "DBC05482-D5B6-4F51-A692-E8C2855F7F2F", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50425
2017-07-14 12:40:42 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"WibIt4w1NHGn3tSba1QypsIT8lqQBVUu",,"error":null,"portNumber":50425}'
2017-07-14 12:40:42 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'WibIt4w1NHGn3tSba1QypsIT8lqQBVUu', error: 'null', listeningPort: '50425''
,Connecting to the localhost:50425
[ThaliCore] Session.session(_:peer:didChange:) peer:18F8B334-CA3B-4F8D-9B49-5E164A8197FE state: connecting -> connected
,Connected to the localhost:50425
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:DBC05482-D5B6-4F51-A692-E8C2855F7F2F:0
2017-07-14 12:40:42 - DE,BUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-14 12:40:42 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:DBC05482-D5B6-4F51-A692-E8C2855F7F2F:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1 [1]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:18F8B334-CA3B-4F8D-9B49-5E164A8197FE
[ThaliCore] Session.startOutputStream(with:) peer:18F8B334-CA3B-4F8D-9B49-5E164A8197FE
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2, [1, 2]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-14 12:40:42 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
2017-07-14 12:40:42 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
2017-07-14 12:40:42 - DEBUG testThaliMobileNative: 'Server sends data bac,k to client (20 bytes):'
2017-07-14 12:40:42 - DEBUG testThaliMobileNative: 'Server data flushed'
,ok 104 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pe,er})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStream,s() vsID:1
# teardown
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:2
[ThaliCore] VirtualSocket.closeStreams() vsID:2
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:2
[ThaliCore] VirtualSocket.deinit vsID:2 [1]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disco,nnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-14 12:40:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-14 12:40:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 12:40:48 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 12:40:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 105 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
2017-07-14 12:40:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTC,P: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:40:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 106 Should be able to call stopAdvertisingAndListening in teardown
[ThaliCore] Brow,serManager.disconnect peer:DBC05482-D5B6-4F51-A692-E8C2855F7F2F
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50425
[ThaliCore] Session.disconnect() peer:DBC05482,-D5B6-4F51-A692-E8C2855F7F2F:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] Session.session(_:peer:didChange:) peer:DBC05482-D5B6-4F51-A692-E8C2855F7F2F:0 state: connected -> notConnected
[ThaliCore] ,B,rowser: session notConnected Peer(uuid: "DBC05482-D5B6-4F51-A692-E8C2855F7F2F", generation: 0)
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "DBC05482-D5B6-4F51-A692-E8C2855F7F2F", generation: 0)
# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:18F8B334-CA3B-4F8D-9B49-5E164A8197FE state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "4AAB776C-211D-47ED-BBDD-F924EF51954D", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:18F8B334-CA3B-4F8D-9B49-5E164A8197FE
[ThaliCore] Advert,iserRelay.deinit
[ThaliCore] Session.deinit peer:18F8B334-CA3B-4F8D-9B49-5E164A8197FE
,2017-07-14 12:40:48 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 12:40:48 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:40:48 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:40:48 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 12:40:48 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 12:40:48 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 12:40:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-14 12:40:48 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can shift data via parallel connections
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "99ECCC86-6352-4B09-8204-FA460094AD9F", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:99ECCC86-6352-4B09-8204-FA460094AD9F
,2017-07-14 12:40:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 12:40:49 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 12:40:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 107 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:7B5CC7F3-8D3F-4850-93C3-9132A7C,933D9
[ThaliCore] Browser.startListening
2017-07-14 12:40:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-14 12:40:49 - INFO thaliMobile: 'Received state ({"discover,yActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 12:40:49 - INFO thaliMob,ile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 108 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B5A79CA8-4B6D-42E9-A632-564AB2A52DDA:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B5A79CA8-4B6D-42E9-A632-564AB2A52DDA", generation: 0)
2017-07-14 12:40:49 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B5A79CA8-4B6D-42E9-A632-564AB2A52DDA","generation":0}'
2017-07-14 12:40:49 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B5A79CA8-4B6D-42E9-A632-564AB2A52DDA, (syncValue: P0HOu62mDyCEFPQuRT7eDKVLUxvnREd0)'
2017-07-14 12:40:49 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "B5A79CA8-4B6D-42E9-A632-564AB2A52DDA", gen,eration: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B5A79CA8-4B6D-42E9-A632-564AB2A52DDA", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B5A79CA8-4B6D-,4,2E9-A632-564AB2A52DDA:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9A4807DE-B800-467B-855C-24982A72E20C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9A4807DE-B800-467B-855C-24982A72E20C", generation: 0)
,2017-07-14 12:40:50 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"9A4807DE-B800-467B-855C-24982A72E20C","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D131BF9A-C3B7-4266-80FA-0A8E3B2B40CE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D131BF9A-C3B7-4266-80FA-0A8E3B2B40CE", generation: 0)
,2017-07-14 12:40:50 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"D131BF9A-C3B7-4266-80FA-0A8E3B2B40CE","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:99ECCC86-6352-4B09-8204-FA460094AD9F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "99ECCC86-6352-4B09-8204-FA460094AD9F", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:B5A79CA8-4B6D-42E9-A632-564AB2A52DDA:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "B5A79CA8-4B6D-42E9-A632-564AB2A52DDA", generation: 0)
[ThaliCore] Session.disconnect() peer:B5A79CA8-4B6D-42E9-A632-564AB2A52DDA:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:B5A79CA8-4B6D-42E9-A632-564AB2A52DDA:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "B5A79CA8-4B6D-42E9-A632-564AB2A52DDA", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:B5A79CA8-4B6D-42E9-A632-564AB2A52DDA:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "B5A79CA8-4B6D-42E9-A632-564AB2A52DDA", genera,tion: 0)
2017-07-14 12:40:55 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"P0HOu62mDyCEFPQuRT7eDKVLUxvnREd0","error":"Connection could not be established","portNumber":null}'
2017-07-14 12:40:55 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'P0HOu62mDyCEFPQuRT7eDKVLUxvnREd0', error: 'Connection could not be established', listeningPort: '%s''
2017-07-14 12:40:55 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,t,ifier":"B5A79CA8-4B6D-42E9-A632-564AB2A52DDA","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-14 12:40:55 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-14 ,12:40:55 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"B5A79CA8-4B6D-42E9-A632-564AB2A52DDA","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-14 12:40:55 - DEBUG thaliMobileNativeWrapp,er: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-14 12:40:55 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-14 12:40:55 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 9A4807DE-B800-467B-855C-24982A72E20C (syncValue: IOmyyIZ,mQfI5BJIM6bi916KK6MRPc0lE)'
2017-07-14 12:40:55 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "9A4807DE-B800-467B-855C-24982A72E20C", generation: 0) new rela,y
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9A4807DE-B800-467B-855C-24982A72E20C", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9A4807DE-B800-467B-855C-24982A72E20,C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:9A4807DE-B800-467B-855C-24982A72E20C:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:9A4807DE-B800-467B-855C-24982A72E20C:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:9A4807DE-B800-467B-855C-24982A72E20C:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "9A4807DE-B800-467B-855C-24982A72E20C", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50435
2017-07-14 12:40:59 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"IOmyyIZmQfI5BJIM6bi916KK6MRPc0lE",,"error":null,"portNumber":50435}'
2017-07-14 12:40:59 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'IOmyyIZmQfI5BJIM6bi916KK6MRPc0lE', error: 'null', listeningPort: '50435''
,Connecting to the localhost:50435
Connecting to the localhost:50435
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:9A4807DE-B800-467B-855C-2498,2A72E20C:0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:9A4807DE-B800-467B-855C-24982A72E20C:0
,Connecting to the localhost:50435
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:9A4807DE-B800-467B-855C-24982A72E20C:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9A4807DE-B800-467B-855C-24982A72E20C:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3 [1, 3]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,Connected to the localhost:50435
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9A4807DE-B800-467B-855C-24982A72E20C:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4 [1, 3, 4]
,Connected to the localhost:50435
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,Connected to the localhost:50435
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9A4807DE-B800-467B-855C-24982A72E20C:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5 [1, 3, 4, 5]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 109 correct string length
,2017-07-14 12:40:59 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 110 correct string length
,2017-07-14 12:40:59 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 111 correct string length
,2017-07-14 12:40:59 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,2017-07-14 12:40:59 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-14 12:40:59 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-14 12:40:59 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:3
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,ok 112 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:4
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,ok 113 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:5
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:5
[ThaliCore] VirtualSocket.deinit vsID:5 [1, 3, 4]
,ok 114 got the same data back
,# teardown
,2017-07-14 12:41:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-14 12:41:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-14 12:41:00 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-14 12:41:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 115 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
,2017-07-14 12:41:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:41:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 116 Should be able to call stopAdvertisingAndListening in teardown
,[ThaliCore] BrowserManager.disconnect peer:9A4807DE-B800-467B-855C-24982A72E20C
,[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50435
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] Session.disconnect() peer:9A4807DE-B800-467B-855C-24982A72E20C:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:9A4807DE-B800-467B-855C-24982A72E20C:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "9A4807DE-B800-467B-855C-24982A72E20C", generation: 0)
[ThaliCore] Browser: s,ession notConnected removed relay for Peer(uuid: "9A4807DE-B800-467B-855C-24982A72E20C", generation: 0)
,# setup
,2017-07-14 12:41:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 12:41:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:41:01 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:41:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 12:41:01 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 12:41:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 12:41:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-14 12:41:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can shift data securely
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "27B2CA8B-3D18-4D1B-BBCA-23DEE60C715D", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:27B2CA8B-3D18-4D1B-BBCA-23DEE60C715D
,2017-07-14 12:41:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 12:41:01 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 12:41:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 117 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:93D8A46B-C1D0-4FFD-A0B5-358048326D9F
[ThaliCore] Browser.startListening
,2017-07-14 12:41:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-14 12:41:01 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-14 12:41:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 118 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D131BF9A-C3B7-4266-80FA-0A8E3B2B40CE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D131BF9A-C3B7-4266-80FA-0A8E3B2B40CE", generation: 0)
2017-07-14 12:41:01 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"D131BF9A-C3B7-4266-80FA-0A8E3B2B40CE","generation":0}'
2017-07-14 12:41:01 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for D131BF9A-C3B7-4266-80FA-0A8E3B2B40CE, (syncValue: GzY6s1wZXIrJZWe6mUC17xATk0tPTXtM)'
2017-07-14 12:41:01 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "D131BF9A-C3B7-4266-80FA-0A8E3B2B40CE", gen,eration: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D131BF9A-C3B7-4266-80FA-0A8E3B2B40CE", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D131BF9A-C3B7-,4266-80FA-0A8E3B2B40CE:0
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9A4807DE-B800-467B-855C-24982A72E20C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9A4807DE-B800-467B-855C-24982A72E20C", generation: 0)
[Th,aliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-14 12:41:01 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifie,r":"9A4807DE-B800-467B-855C-24982A72E20C","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:794CF4E2-DF66-4642-B5B9-3D4ACD297C95:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "794CF4E2-DF66-4642-B5B9-3D4ACD297C95", generation: 0)
,2017-07-14 12:41:01 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"794CF4E2-DF66-4642-B5B9-3D4ACD297C95","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FD9E51BC-9FE1-45FD-9E88-E6A08077A58D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FD9E51BC-9FE1-45FD-9E88-E6A08077A58D", generation: 0)
2017-07-14 12:41:02 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"FD9E51BC-9FE1-45FD-9E88-E6A08077A58D","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:27B2CA8B-3D18-4D1B-BBCA-23DEE60C715D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "27B2CA8B-3D18-4D1B-BBCA-23DEE60C715D", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:D131BF9A-C3B7-4266-80FA-0A8E3B2B40CE:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "D131BF9A-C3B7-4266-80FA-0A8E3B2B40CE", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:D131BF9A-C3B7-4266-80FA-0A8E3B2B40CE:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "D131BF9A-C3B7-4266-80FA-0A8E3B2B40CE", genera,tion: 0)
2017-07-14 12:41:07 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"GzY6s1wZXIrJZWe6mUC17xATk0tPTXtM","error":"Connection could not be established","portNumber":null}'
2017-07-14 12:41:07 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'GzY6s1wZXIrJZWe6mUC17xATk0tPTXtM', error: 'Connection could not be established', listeningPort: '%s''
2017-07-14 12:41:07 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,t,ifier":"D131BF9A-C3B7-4266-80FA-0A8E3B2B40CE","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-14 12:41:07 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-14 ,12:41:07 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"D131BF9A-C3B7-4266-80FA-0A8E3B2B40CE","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-14 12:41:07 - DEBUG thaliMobileNativeWrapp,er: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-14 12:41:07 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-14 12:41:07 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 9A4807DE-B800-467B-855C-24982A72E20C (syncValue: my6q7zF,LeMYMVK1jgGI42gigs8cPgcmZ)'
2017-07-14 12:41:07 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "9A4807DE-B800-467B-855C-24982A72E20C", generation: 0) new rela,y
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9A4807DE-B800-467B-855C-24982A72E20C", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9A4807DE-B800-467B-855C-24982A72E20,C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:A71FE476-0307-4F55-9AA0-968301ACCEBC
[ThaliCore] Advertiser: session connected Peer(uuid: "27B2CA8B-3D18-4D1B-BBCA-23DEE60C715D", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:A71FE476-0307-4F55-9AA0-968301ACCEBC state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:6AF9FEE5-E74E-4700-A046-E538896949E1
[ThaliCore] Advertiser: session connected Peer(uuid: "27B2CA8B-3D18-4D1B-BBCA-23DEE60C715D", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:6AF9FEE5-E74E-4700-A046-E538896949E1 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:A71FE476-0307-4F55-9AA0-968301ACCEBC
,[ThaliCore] Session.session(_:peer:didChange:) peer:A71FE476-0307-4F55-9AA0-968301ACCEBC state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A71FE476-0307-4F55-9AA0-968301ACCEBC
[ThaliCore] Session.startOutputStream(with:) peer:A71FE476-0307-4F55-9AA0-968301ACCEBC
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6 [1, 3, 4, 6]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,Server received psk id: psk-id
,2017-07-14 12:41:10 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
2017-07-14 12:41:10 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
2017-07-14 12:41:10 - DEBUG testThaliMobileNative: 'Server sends data bac,k to client (20 bytes): '
2017-07-14 12:41:10 - DEBUG testThaliMobileNative: 'Server data flushed'
2017-07-14 12:41:10 - DEBUG testThaliMobileNative: 'Server's socket stream finished'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:6
[ThaliCore] VirtualSocket.closeSt,reams() vsID:6
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:6
[ThaliCore] VirtualSocket.deinit vsID:6 [1, 3, 4]
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:6AF9FEE5-E74E-4700-A046-E538896949E1
,[ThaliCore] Session.session(_:peer:didChange:) peer:6AF9FEE5-E74E-4700-A046-E538896949E1 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:6AF9FEE5-E74E-4700-A046-E538896949E1
[ThaliCore] Session.startOutputStream(with:) peer:6AF9FEE5-E74E-4700-A046-E538896949E1
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7 [1, 3, 4, 7]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,Server received psk id: psk-id
,2017-07-14 12:41:11 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
2017-07-14 12:41:11 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-14 12:41:11 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes): '
,2017-07-14 12:41:11 - DEBUG testThaliMobileNative: 'Server data flushed'
2017-07-14 12:41:11 - DEBUG testThaliMobileNative: 'Server's socket stream finished'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:7
[ThaliCore] VirtualSocket.closeStreams() vsID:7
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:7
[ThaliCore] VirtualSocket.deinit vsID:7 [1, 3, 4]
,[ThaliCore] Session.session(_:peer:didChange:) peer:9A4807DE-B800-467B-855C-24982A72E20C:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "9A4807DE-B800-467B-855C-24982A72E20C", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:9A4807DE-B800-467B-855C-24982A72E20C:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "9A4807DE-B800-467B-855C-24982A72E20C", genera,tion: 0)
2017-07-14 12:41:12 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"my6q7zFLeMYMVK1jgGI42gigs8cPgcmZ","error":"Connection could not be established","portNumber":null}'
2017-07-14 12:41:12 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'my6q7zFLeMYMVK1jgGI42gigs8cPgcmZ', error: 'Connection could not be established', listeningPort: '%s''
2017-07-14 12:41:12 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,t,ifier":"9A4807DE-B800-467B-855C-24982A72E20C","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-14 12:41:12 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-14 ,12:41:12 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"9A4807DE-B800-467B-855C-24982A72E20C","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-14 12:41:12 - DEBUG thaliMobileNativeWrapp,er: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-14 12:41:12 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-14 12:41:12 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 794CF4E2-DF66-4642-B5B9-3D4ACD297C95 (syncValue: 6DImKyQ2CKBNd4hpPWvVzzaGQU49fGoR)'
,2017-07-14 12:41:12 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "794CF4E2-DF66-4642-B5B9-3D4ACD297C95", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "794CF4E2-DF66-4642-B5B9-3D4ACD297C95", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:794CF4E2-DF66-4642-B5B9-3D4ACD297C95:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:794CF4E2-DF66-4642-B5B9-3D4ACD297C95:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:794CF4E2-DF66-4642-B5B9-3D4ACD297C95:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:794CF4E2-DF66-4642-B5B9-3D4ACD297C95:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "794CF4E2-DF66-4642-B5B9-3D4ACD297C95", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50448
2017-07-14 12:41:15 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"6DImKyQ2CKBNd4hpPWvVzzaGQU49fGoR",,"error":null,"portNumber":50448}'
2017-07-14 12:41:15 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '6DImKyQ2CKBNd4hpPWvVzzaGQU49fGoR', error: 'null', listeningPort: '50448''
,Connecting to the localhost:50448
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:794CF4E2-DF66-4642-B5B9-3D4ACD297C95:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:794CF4E2-DF66-4642-B5B9-3D4ACD297C95:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8 [1, 3, 4, 8]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,Connected to the localhost:50448
,2017-07-14 12:41:15 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-14 12:41:15 - DEBUG testThaliMobileNative: 'Client data flushed'
,ok 119 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:8
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:8
[ThaliCore] VirtualSocket.deinit vsID:8 [1, 3, 4]
# teardown
,2017-07-14 12:41:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-14 12:41:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 12:41:15 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 12:41:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 120 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,2017-07-14 12:41:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:41:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 121 Should be able to call stopAdvertisingAndListening in teardown
[ThaliCore] BrowserManager.disconnect peer:794CF4E2-DF66-4642-B5B9-3D4ACD297C95
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] TCPListener.stopListeningForConne,ctionsAndDisconnectClients() port:50448
[ThaliCore] Session.disconnect() peer:794CF4E2-DF66-4642-B5B9-3D4ACD297C95:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] Session.session(_:peer:didChange:) peer:794CF4E2-DF66-4642-B5B9-3D4ACD297C95:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "794CF4E2-DF66-4642-B5B9-3D4ACD297C95", generation: 0)
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "794CF4E2-DF66-4642-B5B9-3D4ACD297C95", generation: 0)
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:6AF9FEE5-E74E-4700-A046-E538896949E1 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "27B2CA8B-3D18-4D1B-BBCA-23DEE60C715D", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:6AF9FEE5-E74E-4700-A046-E538896949E1
,2017-07-14 12:41:15 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 12:41:15 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:41:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,[ThaliCore] Session.session(_:peer:didChange:) peer:A71FE476-0307-4F55-9AA0-968301ACCEBC state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "27B2CA8B-3D18-4D1B-BBCA-23DEE60C715D", generation: 0)
,2017-07-14 12:41:15 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 12:41:15 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 12:41:15 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 12:41:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,[ThaliCore] AdvertiserRelay.deinit
[ThaliCore] Session.deinit peer:6AF9FEE5-E74E-4700-A046-E538896949E1
2017-07-14 12:41:15 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can shift large amounts of data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "8ABBC275-0A33-4834-8930-987F8EE3835A", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:8ABBC275-0A33-4834-8930-987F8EE3835A
,2017-07-14 12:41:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-14 12:41:16 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 12:41:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 122 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:A2D2B89B-DD8B-4639-A692-D9E61EEF0BA2
,[ThaliCore] Browser.startListening
,2017-07-14 12:41:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-14 12:41:16 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 12:41:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 123 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:794CF4E2-DF66-4642-B5B9-3D4ACD297C95:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "794CF4E2-DF66-4642-B5B9-3D4ACD297C95", generation: 0)
2017-07-14 12:41:17 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"794CF4E2-DF66-4642-B5B9-3D4ACD297C95","generation":0}'
2017-07-14 12:41:17 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 794CF4E2-DF66-4642-B5B9-3D4ACD297C95, (syncValue: yzeF0IaRzhnKrq0KB3vSHqOPP7xwpaFh)'
2017-07-14 12:41:17 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "794CF4E2-DF66-4642-B5B9-3D4ACD297C95", gen,eration: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "794CF4E2-DF66-4642-B5B9-3D4ACD297C95", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:794CF4E2-DF66-,4,642-B5B9-3D4ACD297C95:0
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9A4807DE-B800-467B-855C-24982A72E20C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9A4807DE-B800-467B-855C-24982A72E20C", generation: 0)
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-14 12:41:17 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"9A4807DE-B800-467B-855C-24982A72E20C","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8ABBC275-0A33-4834-8930-987F8EE3835A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8ABBC275-0A33-4834-8930-987F8EE3835A", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:05F6B8F2-51F6-437E-B02A-47E24E1B1558:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "05F6B8F2-51F6-437E-B02A-47E24E1B1558", generation: 0)
2017-07-14 12:41:18 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"05F6B8F2-51F6-437E-B02A-47E24E1B1558","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CB1D2901-E973-4AA9-BB6A-4759081EBB4A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CB1D2901-E973-4AA9-BB6A-4759081EBB4A", generation: 0)
2017-07-14 12:41:18 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"CB1D2901-E973-4AA9-BB6A-4759081EBB4A","generation":0}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:9A4807DE-B800-467B-855C-24982A72E20C:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "9A4807DE-B800-467B-855C-24982A72E20C", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:34F8A776-667A-422C-9196-2202DC36D9E4
[ThaliCore] Advertiser: session connected Peer(uuid: "8ABBC275-0A33-4834-8930-987F8EE3835A", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:34F8A776-667A-422C-9196-2202DC36D9E4 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:794CF4E2-DF66-4642-B5B9-3D4ACD297C95:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "794CF4E2-DF66-4642-B5B9-3D4ACD297C95", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:794CF4E2-DF66-4642-B5B9-3D4ACD297C95:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "794CF4E2-DF66-4642-B5B9-3D4ACD297C95", genera,tion: 0)
2017-07-14 12:41:22 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"yzeF0IaRzhnKrq0KB3vSHqOPP7xwpaFh","error":"Connection could not be established","portNumber":null}'
2017-07-14 12:41:22 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'yzeF0IaRzhnKrq0KB3vSHqOPP7xwpaFh', error: 'Connection could not be established', listeningPort: '%s''
2017-07-14 12:41:22 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,t,ifier":"794CF4E2-DF66-4642-B5B9-3D4ACD297C95","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-14 12:41:22 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-14 12:41:22 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"794CF4E2-DF66-4642-B5B9-3D4ACD297C95","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-14 12:41:22 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-14 12:41:22 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-14 12:41:22 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 05F6B8F2-51F6-437E-B02A-47E24E1B1558 (syncValue: 5UKEYZp,Th57eIuoQkbcoZZjgj2vKe6eL)'
2017-07-14 12:41:22 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "05F6B8F2-51F6-437E-B02A-47E24E1B1558", generation: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "05F6B8F2-51F6-437E-B02A-47E24E1B1558", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:05F6B8F2-51F6-437E-B02A-47E24E1B1558:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:05F6B8F2-51F6-437E-B02A-47E24E1B1558:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:34F8A776-667A-422C-9196-2202DC36D9E4
,[ThaliCore] Session.session(_:peer:didChange:) peer:34F8A776-667A-422C-9196-2202DC36D9E4 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:34F8A776-667A-422C-9196-2202DC36D9E4
[ThaliCore] Session.startOutputStream(with:) peer:34F8A776-667A-422C-9196-2202DC36D9E4
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9 [1, 3, 4, 9]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-14 12:41:25 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-14 12:41:25 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-14 12:41:25 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-14 12:41:25 - DEBUG testThaliMobileNative: 'Server received (5262 bytes):'
,2017-07-14 12:41:25 - DEBUG testThaliMobileNative: 'Server received (213 bytes):'
2017-07-14 12:41:25 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
,2017-07-14 12:41:25 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-14 12:41:25 - DEBUG testThaliMobileNative: 'Server received (4096 bytes):'
,2017-07-14 12:41:25 - DEBUG testThaliMobileNative: 'Server received (4451 bytes):'
,2017-07-14 12:41:26 - DEBUG testThaliMobileNative: 'Server received (2048 bytes):'
,2017-07-14 12:41:26 - DEBUG testThaliMobileNative: 'Server received (9216 bytes):'
,2017-07-14 12:41:26 - DEBUG testThaliMobileNative: 'Server received (12288 bytes):'
,2017-07-14 12:41:26 - DEBUG testThaliMobileNative: 'Server received (10240 bytes):'
,2017-07-14 12:41:26 - DEBUG testThaliMobileNative: 'Server received (4582 bytes):'
,2017-07-14 12:41:26 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-14 12:41:26 - DEBUG testThaliMobileNative: 'Server sends data back to client (65536 bytes):'
2017-07-14 12:41:26 - DEBUG testThaliMobileNative: 'Server data flushed',
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:9
[ThaliCore] VirtualSocket.closeStreams() vsID:9
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:9
,[ThaliCore] VirtualSocket.deinit vsID:9 [1, 3, 4]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:05F6B8F2-51F6-437E-B02A-47E24E1B1558:0
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D9426A85-721E-4F30-B627-0E906DB0F182
[ThaliCore] Advertiser: session connected Peer(uuid: "8ABBC275-0A33-4834-8930-987F8EE3835A", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] Session.session(_:peer:didChange:) peer:D9426A85-721E-4F30-B627-0E906DB0F182 state: notConnected -> connecting
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:05F6B8F2-51F6-437E-B02A-47E24E1B1558:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "05F6B8F2-51F6-437E-B02A-47E24E1B1558", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50458
,2017-07-14 12:41:28 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"5UKEYZpTh57eIuoQkbcoZZjgj2vKe6eL","error":null,"portNumber":50458}'
,2017-07-14 12:41:28 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '5UKEYZpTh57eIuoQkbcoZZjgj2vKe6eL', error: 'null', listeningPort: '50458''
,Connecting to the localhost:50458
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:05F6B8F2-51F6-437E-B02A-47E24E1B1558:0
,Connected to the localhost:50458
,2017-07-14 12:41:28 - DEBUG testThaliMobileNative: 'Client sends data (65536 bytes):'
,2017-07-14 12:41:28 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:05F6B8F2-51F6-437E-B02A-47E24E1B1558:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:10 [1, 3, 4, 10]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 124 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pe,er})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:10
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,# teardown
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:794CF4E2-DF66-4642-B5B9-3D4ACD297C95:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "794CF4E2-DF66-4642-B5B9-3D4ACD297C95", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D9426A85-721E-4F30-B627-0E906DB0F182
,[ThaliCore] Session.session(_:peer:didChange:) peer:D9426A85-721E-4F30-B627-0E906DB0F182 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D9426A85-721E-4F30-B627-0E906DB0F182
[ThaliCore] Session.startOutputStream(with:) peer:D9426A85-721E-4F30-B627-0E906DB0F182
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:11 [1, 3, 4, 10, 11]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-14 12:41:30 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-14 12:41:30 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
2017-07-14 12:41:30 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
2017-07-14 12:41:30 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
2017,-07-14 12:41:30 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
2017-07-14 12:41:30 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-14 12:41:30 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-14 12:41:30 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
,2017-07-14 12:41:30 - DEBUG testThaliMobileNative: 'Server received (5475 bytes):'
,2017-07-14 12:41:30 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-14 12:41:30 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
,2017-07-14 12:41:30 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-14 12:41:30 - DEBUG testThaliMobileNative: 'Server received (3214 bytes):'
,2017-07-14 12:41:30 - DEBUG testThaliMobileNative: 'Server received (3356 bytes):'
,2017-07-14 12:41:30 - DEBUG testThaliMobileNative: 'Server received (3214 bytes):'
,2017-07-14 12:41:30 - DEBUG testThaliMobileNative: 'Server received (4451 bytes):'
,2017-07-14 12:41:30 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-14 12:41:30 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
,2017-07-14 12:41:30 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
,2017-07-14 12:41:30 - DEBUG testThaliMobileNative: 'Server received (4238 bytes):'
,2017-07-14 12:41:30 - DEBUG testThaliMobileNative: 'Server received (1073 bytes):'
,2017-07-14 12:41:30 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-14 12:41:30 - DEBUG testThaliMobileNative: 'Server sends data back to client (65536 bytes):'
2017-07-14 12:41:30 - DEBUG testThaliMobileNative: 'Server data flushed',
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:11
,[ThaliCore] VirtualSocket.closeStreams() vsID:11
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:11
[ThaliCore] VirtualSocket.deinit vsID:11 [1, 3, 4, 10]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-14 12:41:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-14 12:41:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 12:41:31 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 12:41:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 125 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,2017-07-14 12:41:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:41:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 126 Should be able to call stopAdvertisingAndListening in teardown
[ThaliCore] BrowserManager.disconnect peer:05F6B8F2-51F6-437E-B02A-47E24E1B1558
,[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50458
,[ThaliCore] Session.disconnect() peer:05F6B8F2-51F6-437E-B02A-47E24E1B1558:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] Session.session(_:peer:didChange:) peer:05F6B8F2-51F6-437E-B02A-47E24E1B1558:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "05F6B8F2-51F6-437E-B02A-47E24E1B1558", generation: 0)
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "05F6B8F2-51F6-437E-B02A-47E24E1B1558", generation: 0)
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:D9426A85-721E-4F30-B627-0E906DB0F182 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "8ABBC275-0A33-4834-8930-987F8EE3835A", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:D9426A85-721E-4F30-B627-0E906DB0F182
,[ThaliCore] AdvertiserRelay.deinit
[ThaliCore] Session.deinit peer:D9426A85-721E-4F30-B627-0E906DB0F182
,2017-07-14 12:41:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 12:41:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 12:41:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,[ThaliCore] Session.session(_:peer:didChange:) peer:34F8A776-667A-422C-9196-2202DC36D9E4 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "8ABBC275-0A33-4834-8930-987F8EE3835A", generation: 0)
,2017-07-14 12:41:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 12:41:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 12:41:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:41:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:41:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# We do not emit peerAvailabilityChanged events until one of the start methods is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "B18F8EE3-9874-42AE-B250-3AAB1F55A867", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:B18F8EE3-9874-42AE-B250-3AAB1F55A867
2017-07-14 12:41:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 12:41:34 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 12:41:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 127 Ready to advertise
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:1D07FF3D-466F-463B-A7BD-C47B90A675E3
[ThaliCore] Browser.startListening
2017-07,-,14 12:41:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-14 12:41:34 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not ma,tch with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 12:41:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate ,(was in stopped state).'
ok 128 Ready to listen
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C9B187BB-C74A-4332-BEEC-8E80FFCFA986:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C9B187BB-C74A-4332-BEEC-8E80FFCFA986", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1383F40C-96B4-4A21-A631-CDF40A05698D:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1383F40C-96B4-4A21-A631-CDF40A05698D", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:05F6B8F2-51F6-437E-B02A-47E24E1B1558:0
[ThaliCore] BrowserManager.fo,undPeerHandler peer:Peer(uuid: "05F6B8F2-51F6-437E-B02A-47E24E1B1558", generation: 0)
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CB1D290,1-E973-4AA9-BB6A-4759081EBB4A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CB1D2901-E973-4AA9-BB6A-4759081EBB4A", generation: 0)
,2017-07-14 12:41:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 12:41:34 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-14 12:41:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 129 stop ads worked
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-14 12:41:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:41:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 130 test stop worked
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-14 12:41:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:41:38 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 131 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-14 12:41:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:41:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 132 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-14 12:41:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 12:41:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:41:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:41:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 12:41:38 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 12:41:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 12:41:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-14 12:41:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Test updating advertising and parallel data transfer
,2017-07-14 12:41:38 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test updating advertising and parallel data transfer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-14 12:41:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:41:38 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 133 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-14 12:41:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:41:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 134 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-14 12:41:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 12:41:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:41:38 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:41:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 12:41:38 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 12:41:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 12:41:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-14 12:41:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# discoveryAdvertisingStateUpdateNonTCP is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C1FD582F-A364-42BE-ABCC-5A6F828B4B5C
[ThaliCore] Browser.startListening
ok 135 discoveryActive should be false
ok 136 advertisingA,ctive should be true
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "0A51BA97-33A1-4523-A51C-5F74110D8DD4", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:0A51BA97-33A1-4523-A51C-5F74,110D8DD4
ok 137 discoveryActive should be false
ok 138 advertisingActive should be true
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
ok 139 discoveryActive should be false
ok 140 advertisingActive sh,ould be true
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
ok 141 discoveryActive should be false
ok 142 advertisingActive should be true
ok 143 Can call startListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,ok 144 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,ok 145 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# cannot call connect when start listening for advertisements is not active
,2017-07-14 12:41:38 - DEBUG CoordinatedClient: 'test was skipped, name: 'cannot call connect when start listening for advertisements is not active''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,ok 146 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
ok 147 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# Get error when trying to double connect to a peer on Android
,2017-07-14 12:41:39 - DEBUG CoordinatedClient: 'test was skipped, name: 'Get error when trying to double connect to a peer on Android''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
ok 148 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
ok 149 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection
,2017-07-14 12:41:39 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
ok 150 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
ok 151 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection
,2017-07-14 12:41:40 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
ok 152 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
ok 153 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer
,2017-07-14 12:41:40 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
ok 154 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
ok 155 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer
,2017-07-14 12:41:41 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
ok 156 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
ok 157 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-14 12:41:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 12:41:41 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:41:41 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:41:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 12:41:41 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 12:41:41 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 12:41:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-14 12:41:41 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# cannot call multiConnect when start listening for advertisements is not active
,ok 158 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) peer:801a92e3-c89f-43ce-a7ea-fdeff8b2c34c error: startListeningNotActive
2017-07-14 12:41:41 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"93nN6VWGonuHKmT4AFSM64xiD,NahfzGe","error":"startListeningForAdvertisements is not active","portNumber":null}'
ok 159 Should only get called after multiConnect returned
ok 160 SyncValue matches
ok 161 Got right error
ok 162 listeningPort is null
2017-07-14 12:41:41 - DEBUG tha,liMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"801a92e3-c89f-43ce-a7ea-fdeff8b2c34c","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-14 12:41:41 - DEBUG thaliMobileNativeWrapper: 'Filtered out n,onTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-14 12:41:41 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"801a92e3-c89f-43ce-a7ea-fdeff8b2c34c","peerAvailable":true,"portN,umber":null,"recreated":true}'
,2017-07-14 12:41:41 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-14 12:41:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:41:41 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 163 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 12:41:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:41:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 164 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-14 12:41:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 12:41:41 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:41:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:41:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 12:41:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 12:41:41 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:41:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:41:41 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# cannot call multiConnect with illegal peerID
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:714F700E-E3EA-4106-A917-8B736D41E898
,[ThaliCore] Browser.startListening
,2017-07-14 12:41:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 12:41:41 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CB1D2901-E973-4AA9-BB6A-4759081EBB4A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CB1D2901-E973-4AA9-BB6A-4759081EBB4A", generation: 0)
,2017-07-14 12:41:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 165 No error on starting
ok 166 Got null as expected
2017-07-14 12:41:41 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"XF9Nm6EiUJcr2cGkhcTO0AHyWx40XPAH","error":"Illegal peerID","portNumber":null}'
,ok 167 Should only get called after multiConnect returned
,ok 168 SyncValue matches
,ok 169 Got right error
,ok 170 listeningPort is null
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:05F6B8F2-51F6-437E-B02A-47E24E1B1558:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "05F6B8F2-51F6-437E-B02A-47E24E1B1558", generation: 0)
,# teardown
,2017-07-14 12:41:41 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"CB1D2901-E973-4AA9-BB6A-4759081EBB4A","generation":0}]'
,2017-07-14 12:41:41 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"CB1D2901-E973-4AA9-BB6A-4759081EBB4A","generation":0}'
,2017-07-14 12:41:41 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-14 12:41:41 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"05F6B8F2-51F6-437E-B02A-47E24E1B1558","generation":0}]'
,2017-07-14 12:41:41 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"05F6B8F2-51F6-437E-B02A-47E24E1B1558","generation":0}'
,2017-07-14 12:41:41 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-14 12:41:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:41:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 171 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 12:41:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:41:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 172 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-14 12:41:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 12:41:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 12:41:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:41:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 12:41:42 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 12:41:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:41:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:41:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# multiConnect properly fails on legal but non-existent peerID
,2017-07-14 12:41:42 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiConnect properly fails on legal but non-existent peerID''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 12:41:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:41:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 173 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 12:41:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:41:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 174 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-14 12:41:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 12:41:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 12:41:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:41:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 12:41:42 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 12:41:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:41:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:41:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# cannot call multiConnect with invalid syncValue
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:610DC75E-5FFA-438F-A4EF-54C752D14293
[ThaliCore] Browser.startListening
2017-07-14 12:41:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-14 12:41:42 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 12:41:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 175 No error on star,ting
ok 176 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-14 12:41:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14, 12:41:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 177 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-14 12:41:42 - DEBUG tha,liMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:41:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 178 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-14 12:41:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 12:41:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:41:42 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:41:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 12:41:42 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 12:41:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:41:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:41:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# cannot call disconnect with invalid peer id
,ok 179 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-14 12:41:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:41:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 180 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-14 12:41:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:41:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 181 Should be able to call stopAdvertisingAndListening in tea,rdown
,# setup
,2017-07-14 12:41:43 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 12:41:43 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:41:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:41:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 12:41:43 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 12:41:43 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 12:41:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-14 12:41:43 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# disconnect doesn't fail on plausible but bogus peer ID
,[ThaliCore] BrowserManager.disconnect peer:f833ea87-b5b4-4aa1-b658-4b2980efd432
ok 182 No error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-14 12:41:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:41:43 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 183 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-14 12:41:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:41:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 184 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-14 12:41:43 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 12:41:43 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:41:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:41:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 12:41:43 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 12:41:43 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 12:41:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-14 12:41:43 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Get same port when trying to connect multiple times on iOS
,2017-07-14 12:41:43 - DEBUG CoordinatedClient: 'test was skipped, name: 'Get same port when trying to connect multiple times on iOS''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-14 12:41:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:41:44 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 185 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-14 12:41:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:41:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 186 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# initial peer discovery
,2017-07-14 12:41:44 - DEBUG CoordinatedClient: 'test was skipped, name: 'initial peer discovery''
,# teardown
,2017-07-14 12:41:44 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 12:41:44 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:41:44 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:41:44 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 12:41:44 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 12:41:44 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 12:41:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-14 12:41:44 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 1
,2017-07-14 12:41:45 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 1''
,# teardown
,2017-07-14 12:41:45 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 12:41:45 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:41:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:41:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 12:41:45 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 12:41:45 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 12:41:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-14 12:41:45 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 2
,2017-07-14 12:41:45 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 2''
,# teardown
,2017-07-14 12:41:45 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 12:41:45 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:41:45 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:41:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 12:41:45 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 12:41:45 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 12:41:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-14 12:41:45 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# check latest peer discovery
,2017-07-14 12:41:45 - DEBUG CoordinatedClient: 'test was skipped, name: 'check latest peer discovery''
,# teardown
,2017-07-14 12:41:46 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 12:41:46 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:41:46 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:41:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 12:41:46 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 12:41:46 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 12:41:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-14 12:41:46 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Set up for no peer discovery test
,2017-07-14 12:41:46 - DEBUG CoordinatedClient: 'test was skipped, name: 'Set up for no peer discovery test''
,# teardown
,2017-07-14 12:41:46 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 12:41:46 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:41:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:41:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 12:41:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 12:41:46 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:41:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:41:46 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# no peer discovery
,2017-07-14 12:41:46 - DEBUG CoordinatedClient: 'test was skipped, name: 'no peer discovery''
,# teardown
,2017-07-14 12:41:46 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 12:41:46 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:41:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:41:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 12:41:46 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 12:41:46 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 12:41:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-14 12:41:46 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calling createNativeListener directly rejects
,2017-07-14 12:41:46 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-14 12:41:46 - DEBUG createNativeListener: 'listening 50464'
,ok 187 Should throw
,# teardown
,2017-07-14 12:41:46 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 12:41:46 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 12:41:46 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits incomingConnectionState
,2017-07-14 12:41:46 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-14 12:41:46 - DEBUG createNativeListener: 'listening 50466'
,2017-07-14 12:41:46 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-14 12:41:46 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 188 initial connection state should be CONNECTED
,2017-07-14 12:41:47 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 189 final connection state should be DISCONNECTED
,# teardown
,2017-07-14 12:41:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 12:41:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 12:41:47 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits routerPortConnectionFailed
,2017-07-14 12:41:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-14 12:41:47 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-14 12:41:47 - DEBUG createNativeListener: 'listening 50469'
,2017-07-14 12:41:47 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-14 12:41:47 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-14 12:41:47 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-14 12:41:47 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - error Error: connect ECONNREFUSED'
,ok 190 tried to connect to right port
,ok 191 failed due to refused connection
,ok 192 routerPortConnectionFailed is emitted
,# teardown
,2017-07-14 12:41:47 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-14 12:41:47 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-14 12:41:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-14 12:41:47 - DEBUG createNativeListener: 'Native Server - close'
2017-07-14 12:41:47 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-14 12:41:47 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server connections all up
,2017-07-14 12:41:47 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-14 12:41:47 - DEBUG createNativeListener: 'listening 50473'
,2017-07-14 12:41:47 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-14 12:41:47 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-14 12:41:47 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2017-07-14 12:41:47 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - ,0 - 1 - created'
,ok 193 Send/recvd #1 should be equal length
ok 194 Send/recvd #1 should be same
ok 195 Send/recvd #2 should be equal length
ok 196 Send/recvd #2 should be same
ok 197 Should be exactly 2 client sockets
,# teardown
,2017-07-14 12:41:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-14 12:41:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-14 12:41:48 - DEBUG createNativeListener: 'Native Server - close'
2017-07-14 12:41:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-14 12:41:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
2017-07-14 12:41:48 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close',
2017-07-14 12:41:48 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
2017-07-14 12:41:48 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
2017-07-14 12:41:48 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection, to node - 0 - 0 - close'
,# native server - closing incoming stream cleans outgoing socket
,2017-07-14 12:41:48 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-14 12:41:48 - DEBUG createNativeListener: 'listening 50478'
,2017-07-14 12:41:48 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-14 12:41:48 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-14 12:41:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-14 12:41:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-07-14 12:41:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,ok 198 socket shouldn't close until after stream
,ok 199 incoming remains open
,# teardown
,2017-07-14 12:41:48 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-14 12:41:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 12:41:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 12:41:48 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-14 12:41:48 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-14 12:41:48 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing incoming connection cleans outgoing socket
,2017-07-14 12:41:48 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-14 12:41:48 - DEBUG createNativeListener: 'listening 50482'
,2017-07-14 12:41:48 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-14 12:41:48 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 200 we should not have gotten an error
,2017-07-14 12:41:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-14 12:41:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-14 12:41:48 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 201 socket shouldn't close until after incoming
,ok 202 incoming is cleaned up
,# teardown
,2017-07-14 12:41:48 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-14 12:41:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 12:41:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 12:41:48 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - closing outgoing socket cleans associated mux stream
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'listening 50486'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-14 12:41:49 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node -, 0 - 0 - closed'
2017-07-14 12:41:49 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,ok 203 stream was closed
ok 204 incoming should survive
ok 205 mux should have no streams
,# teardown
,2017-07-14 12:41:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 12:41:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing the whole server cleans everything up
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'listening 50490'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 206 we should not have gotten an error
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 207 Buffers are identical
,2017-07-14 12:41:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 208 native server is nulled out
,ok 209 native server should be closed
,ok 210 incoming has been removed
,ok 211 Incoming should be done
,ok 212 The mux object should be closed
,ok 213 The mux stream should be closed
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# teardown
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-14 12:41:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - we can get a ton of connections and data through and still clean up the server completely
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'listening 50494'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - created'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - created'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - created'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - created'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - created'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - created'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - created'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - created'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - created'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - created'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - created'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - created'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - created'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - created'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - created'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - created'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - created'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - created'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - created'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - created'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - created'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - created'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - created'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - created'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - created'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - created'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - created'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - created'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - created'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - created'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - created'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - created'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - created'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - created'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - created'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - created'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - created'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - created'
,2017-07-14 12:41:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - closed'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - closed'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - closed'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - closed'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - closed'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - closed'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - closed'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - closed'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - closed'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - closed'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - closed'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - closed'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - closed'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - closed'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - closed'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - closed'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - closed'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - closed'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - closed'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - closed'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - closed'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - closed'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - closed'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - closed'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - closed'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - closed'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - closed'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - closed'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - closed'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - closed'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - closed'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - closed'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - closed'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - closed'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - closed'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - closed'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - closed'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - closed'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,ok 214 native server is nulled out
,ok 215 native server should be closed
,ok 216 incoming has been removed
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - close'
2017-07-14 12:41:50 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - close'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - close'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - close'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - close'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - close'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - close'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - close'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - close'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - close'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - close'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - close'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - close'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - close'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - close'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - close'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - close'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - close'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - close'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - close'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - close'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - close'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - close'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - close'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - close'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - close'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - close'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - close'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - close'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - close'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - close'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - close'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - close'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - close'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - close'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - close'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - close'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - close'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-14 12:41:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - simulate mux failure, make sure everything is cleaned up
,2017-07-14 12:41:55 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-14 12:41:55 - DEBUG createNativeListener: 'listening 50546'
,2017-07-14 12:41:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-14 12:41:55 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 217 we should not have gotten an error
,2017-07-14 12:41:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 218 Buffers are identical
2017-07-14 12:41:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2017-07-14 12:41:55 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-14 12:41:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 219 server should be fine
ok 220 server should be open
ok 221 incoming has been removed
ok 222 The mux object should be clos,ed
ok 223 The mux stream should be closed
2017-07-14 12:41:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-14 12:41:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-14 12:41:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-14 12:41:55 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - timing out the incoming connection cleans everything up
,2017-07-14 12:41:55 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-14 12:41:55 - DEBUG createNativeListener: 'listening 50550'
,2017-07-14 12:41:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-14 12:41:55 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 224 we should not have gotten an error
,2017-07-14 12:41:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 225 Buffers are identical
,2017-07-14 12:41:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - incoming socket timeout'
,2017-07-14 12:41:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-14 12:41:55 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-14 12:41:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 226 server should be fine
,ok 227 server should be open
,ok 228 incoming has been removed
,ok 229 The mux object should be closed
,ok 230 The mux stream should be closed
,# teardown
,2017-07-14 12:41:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-14 12:41:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 12:41:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 12:41:55 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# can create servers manager
,ok 231 serversManager must not be null
,ok 232 serversManager must be an object
,# teardown
,# setup
,# calling stop without start causes error
,ok 233 We need to call start first
,# teardown
,# setup
,# can start/stop servers manager
,2017-07-14 12:41:56 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-14 12:41:56 - DEBUG createNativeListener: 'listening 50553'
ok 234 port must be in range
,# teardown
,2017-07-14 12:41:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-14 12:41:56 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# starting twice resolves with listening port
,2017-07-14 12:41:57 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-14 12:41:57 - DEBUG createNativeListener: 'listening 50554'
ok 235 second start should return same port
,# teardown
,2017-07-14 12:41:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-14 12:41:57 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminateIncomingConnection will terminate a connection
,2017-07-14 12:41:57 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-14 12:41:57 - DEBUG createNativeListener: 'listening 50556'
,2017-07-14 12:41:57 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-14 12:41:57 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 236 we should be connected
2017-07-14 12:41:57 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 237 now we are disconnected
,2017-07-14 12:41:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# teardown
,2017-07-14 12:41:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-14 12:41:57 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminate an Outgoing connection
,2017-07-14 12:41:58 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 32'
ok 238 Passed bogus id
2017-07-14 12:41:58 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 901'
ok 239 Passed good id but bogus port
2017-07-14 12:41:58 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 900'
ok 240 Passed right context
ok 241 Right server
ok 242 No error should be set
ok 243 Ret,ry should be false
ok 244 We called close server
,# teardown
,# setup
,# Single local http request
,listening on 50558
,ok 245 should be equal
# teardown
,2017-07-14 12:41:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Single coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2
2017-07-14 1,2:41:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 12:41:59 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 12:41:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 246 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:72BF5322-2BE1-4356-B635-4EBC6052DD67
[Tha,l,iCore] Browser.startListening
2017-07-14 12:41:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-14 12:41:59 - INFO thaliMobile: 'Received state ({"discoveryActive":tru,e,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 12:41:59 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 247 Can call startListeningForAdvertisements without error
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:176B5A53-E1B9-4695-BE7A-233BFCE90948
[ThaliCore] Advertiser: session connected Peer(uuid: "83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:176B5A53-E1B9-4695-BE7A-233BFCE90948 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FC300130-5B0C-4E41-A003-41F0F159FE44
[ThaliCore] Advertiser: session connected Peer(uuid: "83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:FC300130-5B0C-4E41-A003-41F0F159FE44 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:66FCBB9A-2036-4526-9064-41C06DEDA815:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "66FCBB9A-2036-4526-9064-41C06DEDA815", generation: 0)
,2017-07-14 12:42:00 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"66FCBB9A-2036-4526-9064-41C06DEDA815","generation":0}'
,2017-07-14 12:42:00 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 66FCBB9A-2036-4526-9064-41C06DEDA815 (syncValue: l5oFzKOg9K7kTObAYv3FZP9sXAulycsG)'
,2017-07-14 12:42:00 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "66FCBB9A-2036-4526-9064-41C06DEDA815", generation: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "66FCBB9A-2036-4526-9064-41C06DEDA815", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:66FCBB9A-2036-4526-9064-41C06DEDA815:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49", generation: 0)
,2017-07-14 12:42:00 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49","generation":0}'
,2017-07-14 12:42:00 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49 (syncValue: WKxS6iyLMLjetn1QVh61GqwqtJrpgGec)'
,2017-07-14 12:42:00 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49", generation: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4F09C7E7-1F18-4ABA-9ED2-,53A8539D5B49", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49:0 state: notConnected -> connecting
[ThaliCore] Session.session(_:peer:didChange:) peer:66FCBB9A-2036-4526-9064-41C06DEDA815:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:FC300130-5B0C-4E41-A003-41F0F159FE44
,[ThaliCore] Session.session(_:peer:didChange:) peer:FC300130-5B0C-4E41-A003-41F0F159FE44 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:176B5A53-E1B9-4695-BE7A-233BFCE90948
,[ThaliCore] Session.session(_:peer:didChange:) peer:176B5A53-E1B9-4695-BE7A-233BFCE90948 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:66FCBB9A-2036-4526-9064-41C06DEDA815:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:66FCBB9A-2036-4526-9064-41C06DEDA815:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "66FCBB9A-2036-4526-9064-41C06DEDA815", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50564
,2017-07-14 12:42:03 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"l5oFzKOg9K7kTObAYv3FZP9sXAulycsG","error":null,"portNumber":50564}'
,2017-07-14 12:42:03 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'l5oFzKOg9K7kTObAYv3FZP9sXAulycsG', error: 'null', listeningPort: '50564''
,2017-07-14 12:42:03 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'l5oFzKOg9K7kTObAYv3FZP9sXAulycsG', error: 'null', listeningPort: '50564''
,2017-07-14 12:42:03 - WARN thaliMobileNativeTestUtils: 'multiConnectResolved received invalid syncValue: 'l5oFzKOg9K7kTObAYv3FZP9sXAulycsG', originalSyncValue: 'WKxS6iyLMLjetn1QVh61GqwqtJrpgGec''
,ok 248 should be equal
,ok 249 (unnamed assert)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50566
2017-07-14 12:42:03 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"WKxS6iyLMLjetn1QVh61GqwqtJrpgGec",,"error":null,"portNumber":50566}'
2017-07-14 12:42:03 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'WKxS6iyLMLjetn1QVh61GqwqtJrpgGec', error: 'null', listeningPort: '50566''
,ok 250 should be equal
,# teardown
,[ThaliCore] BrowserManager.disconnect peer:66FCBB9A-2036-4526-9064-41C06DEDA815
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50564
[ThaliCore] Session.disconnect,() peer:66FCBB9A-2036-4526-9064-41C06DEDA815:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] BrowserManager.disconnect peer:4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49
[ThaliCore] BrowserRelay.closeRelay() dis,connecting:false
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50566
[ThaliCore] Session.disconnect() peer:4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket, error:nil
[ThaliCore] Session.session(_:peer:didChange:) peer:66FCBB9A-2036-4526-9064-41C06DEDA815:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "66FCBB9A-2036-4526-9064-41C06DEDA815", generation: 0)
[ThaliCor,e,] Browser: session notConnected removed relay for Peer(uuid: "66FCBB9A-2036-4526-9064-41C06DEDA815", generation: 0)
[ThaliCore] Session.session(_:peer:didChange:) peer:4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49:0 state: connected -> notConnected
[ThaliCore] Br,owser: session notConnected Peer(uuid: "4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49", generation: 0)
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49", generation: 0)
,2017-07-14 12:42:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
[ThaliCore] Session.session(_:peer:didChange:) peer:FC300130-5B0C-4E41-A003-41F0F159FE44 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnecte,d Peer(uuid: "83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[Tha,liCore] Session.disconnect() peer:FC300130-5B0C-4E41-A003-41F0F159FE44
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:FC300130-5B0C-4E41-A003-41F0F159FE44
,[ThaliCore] Session.session(_:peer:didChange:) peer:176B5A53-E1B9-4695-BE7A-233BFCE90948 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2", generation: 0)
,# Multiple local http requests
,listening on 50568
,ok 251 should be equal
ok 252 should be equal
ok 253 should be equal
# teardown
,2017-07-14 12:42:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Multiple coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2", generation: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2
2017-07-14 12:42:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-14 12:42:05 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match ,with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 12:42:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was, in stopped state).'
ok 254 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
2017-07-14 12:42:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryAc,t,ive":true,"advertisingActive":true}'
2017-07-14 12:42:05 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startA,rguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 12:42:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 255 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2:1
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2", generation: 1)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49:1
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49", generation: 1)
2017-07-14 12:42:06 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49","generation":1}'
2017-07-14 12:42:06 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49, (syncValue: XmahnC5m2iLumLAgzrKvXXpOCzvQxkWJ)'
2017-07-14 12:42:06 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49", gen,eration: 1) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49", generation: 1)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4F09C7E7-1F18-,4,ABA-9ED2-53A8539D5B49:1
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:66FCBB9A-2036-4526-9064-41C06DEDA815:1
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "66FCBB9A-2036-4526-9064-41C06DEDA815", generation: 1)
,2017-07-14 12:42:06 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"66FCBB9A-2036-4526-9064-41C06DEDA815","generation":1}'
,2017-07-14 12:42:06 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 66FCBB9A-2036-4526-9064-41C06DEDA815 (syncValue: PdAmyqJMhLig3aSBZhMHw9eknYeHbL7y)'
,2017-07-14 12:42:06 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "66FCBB9A-2036-4526-9064-41C06DEDA815", generation: 1) new relay
[ThaliCore] Browser.invite,ToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "66FCBB9A-2036-4526-9064-41C06DEDA815", generation: 1)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:66FCBB9A-2036-4526-9064-41C06DEDA815:1
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FC300130-5B0C-4E41-A003-41F0F159FE44
[ThaliCore] Advertiser: session connected Peer(uuid: "83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2", generation: 1)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:FC300130-5B0C-4E41-A003-41F0F159FE44 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:176B5A53-E1B9-4695-BE7A-233BFCE90948
[ThaliCore] Advertiser: session connected Peer(uuid: "83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2", generation: 1)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:176B5A53-E1B9-4695-BE7A-233BFCE90948 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49:1 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:66FCBB9A-2036-4526-9064-41C06DEDA815:1 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:FC300130-5B0C-4E41-A003-41F0F159FE44
,[ThaliCore] Session.session(_:peer:didChange:) peer:FC300130-5B0C-4E41-A003-41F0F159FE44 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49:1
,[ThaliCore] Session.session(_:peer:didChange:) peer:4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49:1 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49", generation: 1)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50576
,2017-07-14 12:42:09 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"XmahnC5m2iLumLAgzrKvXXpOCzvQxkWJ","error":null,"portNumber":50576}'
,2017-07-14 12:42:09 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'XmahnC5m2iLumLAgzrKvXXpOCzvQxkWJ', error: 'null', listeningPort: '50576''
,2017-07-14 12:42:09 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'XmahnC5m2iLumLAgzrKvXXpOCzvQxkWJ', error: 'null', listeningPort: '50576''
,2017-07-14 12:42:09 - WARN thaliMobileNativeTestUtils: 'multiConnectResolved received invalid syncValue: 'XmahnC5m2iLumLAgzrKvXXpOCzvQxkWJ', originalSyncValue: 'PdAmyqJMhLig3aSBZhMHw9eknYeHbL7y''
,ok 256 should be equal
,ok 257 (unnamed assert)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:176B5A53-E1B9-4695-BE7A-233BFCE90948
,[ThaliCore] Session.session(_:peer:didChange:) peer:176B5A53-E1B9-4695-BE7A-233BFCE90948 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:66FCBB9A-2036-4526-9064-41C06DEDA815:1
,[ThaliCore] Session.session(_:peer:didChange:) peer:66FCBB9A-2036-4526-9064-41C06DEDA815:1 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "66FCBB9A-2036-4526-9064-41C06DEDA815", generation: 1)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50578
2017-07-14 12:42:10 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"PdAmyqJMhLig3aSBZhMHw9eknYeHbL7y",,"error":null,"portNumber":50578}'
2017-07-14 12:42:10 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'PdAmyqJMhLig3aSBZhMHw9eknYeHbL7y', error: 'null', listeningPort: '50578''
,ok 258 should be equal
# teardown
,[ThaliCore] BrowserManager.disconnect peer:4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50576
[ThaliCore] Session.disconnect,() peer:4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49:1
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] BrowserManager.disconnect peer:66FCBB9A-2036-4526-9064-41C06DEDA815
[ThaliCore] BrowserRelay.closeRelay() dis,connecting:false
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50578
[ThaliCore] Session.disconnect() peer:66FCBB9A-2036-4526-9064-41C06DEDA815:1
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket, error:nil
[ThaliCore] Session.session(_:peer:didChange:) peer:4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49:1 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49", generation: 1)
[ThaliCor,e,] Browser: session notConnected removed relay for Peer(uuid: "4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49", generation: 1)
[ThaliCore] Session.session(_:peer:didChange:) peer:66FCBB9A-2036-4526-9064-41C06DEDA815:1 state: connected -> notConnected
[ThaliCore] Br,owser: session notConnected Peer(uuid: "66FCBB9A-2036-4526-9064-41C06DEDA815", generation: 1)
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "66FCBB9A-2036-4526-9064-41C06DEDA815", generation: 1)
,2017-07-14 12:42:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:176B5A53-E1B9-4695-BE7A-233BFCE90948 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2", generation: 1)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:176B5A53-E1B9-4695-BE7A-233BFCE90948
[ThaliCore] Advert,iserRelay.deinit
[ThaliCore] Session.deinit peer:176B5A53-E1B9-4695-BE7A-233BFCE90948
,2017-07-14 12:42:10 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 12:42:10 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 12:42:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:42:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 12:42:10 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 12:42:10 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:42:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:42:10 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# #startListeningForAdvertisements should fail if start not called
,[ThaliCore] Session.session(_:peer:didChange:) peer:FC300130-5B0C-4E41-A003-41F0F159FE44 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2", generation: 1)
,ok 259 specific error should be returned
,# teardown
,ok 260 must be stopped
,# setup
,2017-07-14 12:42:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 12:42:11 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:42:11 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:42:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 12:42:11 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 12:42:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 12:42:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-14 12:42:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# #startUpdateAdvertisingAndListening should fail if start not called
,ok 261 specific error should be returned
,# teardown
,ok 262 must be stopped
,# setup
,2017-07-14 12:42:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 12:42:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:42:12 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:42:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 12:42:12 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 12:42:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 12:42:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-14 12:42:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# should be able to call #stopListeningForAdvertisements many times
,2017-07-14 12:42:12 - DEBUG thaliMobileNativeWrapper: 'listening 50580'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-14 12:42:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-14 12:42:12 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-14 12:42:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 263 no errors
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 12:42:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-14 12:42:12 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-14 12:42:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 264 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,2017-07-14 12:42:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:42:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 12:42:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:42:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 12:42:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 265 must be stopped
,# setup
,2017-07-14 12:42:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 12:42:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 12:42:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:42:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 12:42:12 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 12:42:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:42:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:42:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# should be able to call #startListeningForAdvertisements many times
,2017-07-14 12:42:12 - DEBUG thaliMobileNativeWrapper: 'listening 50581'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:731639BD-C5F7-4BC6-A66D-D59DD4E57692
,[ThaliCore] Browser.startListening
,2017-07-14 12:42:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 12:42:12 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-14 12:42:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 266 no errors
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-07-14 12:42:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 12:42:12 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 12:42:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 267 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 12:42:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 12:42:12 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-14 12:42:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-14 12:42:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:42:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 12:42:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 268 must be stopped
,# setup
,2017-07-14 12:42:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 12:42:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 12:42:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:42:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 12:42:12 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 12:42:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:42:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:42:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-07-14 12:42:12 - DEBUG thaliMobileNativeWrapper: 'listening 50582'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "30F5BBE0-1618-4DD2-AD91-B0DF3B6A8114", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:30F5BBE0-1618-4DD2-AD91-B0DF3B6A8114
,2017-07-14 12:42:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 12:42:12 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 12:42:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 269 no errors
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "30F5BBE0-1618-4DD2-AD91-B0DF3B6A8114", generation: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:30F5BBE0-1618-4DD2-AD91-B0DF3B6A,8114
,2017-07-14 12:42:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 12:42:12 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 12:42:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 270 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
,2017-07-14 12:42:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:42:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 12:42:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:42:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 12:42:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 271 must be stopped
,# setup
,2017-07-14 12:42:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 12:42:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 12:42:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:42:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 12:42:12 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 12:42:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:42:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:42:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# should be able to call #stopAdvertisingAndListening many times
,2017-07-14 12:42:13 - DEBUG thaliMobileNativeWrapper: 'listening 50585'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-14 12:42:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingAct,ive":false}'
2017-07-14 12:42:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 272 no errors
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-14 12:42:13 - DEBUG thaliMobileNativeWrapper: 'discover,yAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:42:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 273 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-14 12:42:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:42:13 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-14 12:42:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
,2017-07-14 12:42:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-14 12:42:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 274 must be stopped
,# setup
,2017-07-14 12:42:13 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 12:42:13 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:42:13 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:42:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 12:42:13 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-07-14 12:42:13 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 12:42:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
2017-07-14 12:42:13 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# can get the network status before starting
,ok 275 network status should have certain non-empty properties
,# teardown
,ok 276 must be stopped
,# setup
,2017-07-14 12:42:13 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 12:42:13 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:42:13 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:42:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 12:42:13 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 12:42:13 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 12:42:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-14 12:42:13 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# error returned with bad router
,2017-07-14 12:42:13 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a string'
ok 277 specific error expected
,# teardown
,ok 278 must be stopped
,# setup
,2017-07-14 12:42:13 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 12:42:13 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:42:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:42:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 12:42:13 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 12:42:13 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:42:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:42:13 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# all services are started when we call start
,2017-07-14 12:42:13 - DEBUG thaliMobileNativeWrapper: 'listening 50586'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:1BB568EC-6928-46F3-96AC-CC3DDBAE46D8
[ThaliCore] Browser.startListening
,2017-07-14 12:42:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 12:42:13 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-14 12:42:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "8D9EFEDD-6CEC-4EFA-839A-A02EF22BCB48", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:8D9EFEDD-6CEC-4EFA-839A-A02EF22BCB48
,2017-07-14 12:42:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-14 12:42:13 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 12:42:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
,ok 279 all connection succeed
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
2017-07-14 12:42:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-14 12:42:1,4 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkT,ype":null}})'
2017-07-14 12:42:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-14 12:42:14 - DEBUG tha,liMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:42:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-14 12:42:14 - DEBU,G, makeIntoCloseAllServer: 'closeAll called on server'
ok 280 must be stopped
,# setup
,2017-07-14 12:42:14 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 12:42:14 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:42:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:42:14 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 12:42:14 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 12:42:14 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:42:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:42:14 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# TCP Servers Manager should be null when we call start on iOS
,2017-07-14 12:42:14 - DEBUG thaliMobileNativeWrapper: 'listening 50589'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:7D6309C2-7FB3-4ADE-88A1-69C427DF12C6
[ThaliCore] Browser.startListening
,2017-07-14 12:42:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 12:42:14 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-14 12:42:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "F4AF49F7-B816-47E7-BC1B-1739C3A78C7A", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:F4AF49F7-B816-47E7-BC1B-1739C3A78C7A
,2017-07-14 12:42:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-14 12:42:14 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 12:42:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 281 TCP Servers Manager doesn't exists
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,2017-07-14 12:42:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-14 12:42:14 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 12:42:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-14 12:42:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:42:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 12:42:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 282 must be stopped
,# setup
,2017-07-14 12:42:14 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 12:42:14 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:42:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:42:14 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 12:42:14 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 12:42:14 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 12:42:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-14 12:42:14 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# all services are stopped when we call stop
,2017-07-14 12:42:14 - DEBUG thaliMobileNativeWrapper: 'listening 50591'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D4F10F36-8440-4F2B-BDA1-5F8B58E792E3
,[ThaliCore] Browser.startListening
,2017-07-14 12:42:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 12:42:14 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-14 12:42:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "55529710-3795-4AE6-8DEB-BA3F704756F5", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:55529710-3795-4AE6-8DEB-BA3F704756F5
,2017-07-14 12:42:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-14 12:42:14 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 12:42:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
2017-07-14 12:42:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 12:42:14 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-14 12:42:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-14 12:42:14 - DEBUG thaliMobileNativeW,rapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:42:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 12:42:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 283 is stopped after calling stop
,ok 284 connection should fail after stopping
,# teardown
,ok 285 must be stopped
,# setup
,2017-07-14 12:42:15 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 12:42:15 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:42:15 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:42:15 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 12:42:15 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 12:42:15 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 12:42:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-14 12:42:15 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# make sure terminateConnection is properly hooked up
,2017-07-14 12:42:15 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateConnection is properly hooked up''
,# teardown
,ok 286 must be stopped
,# setup
,2017-07-14 12:42:15 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 12:42:15 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:42:15 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:42:15 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 12:42:15 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 12:42:15 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 12:42:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-14 12:42:15 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# make sure terminateConnection is return error if we get called on iOS
,ok 287 error description matches
,# teardown
,ok 288 must be stopped
,# setup
,2017-07-14 12:42:16 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 12:42:16 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:42:16 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:42:16 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 12:42:16 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 12:42:16 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 12:42:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-14 12:42:16 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# make sure terminateListener is properly hooked up
,2017-07-14 12:42:16 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateListener is properly hooked up''
,# teardown
,ok 289 must be stopped
,# setup
,2017-07-14 12:42:16 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 12:42:16 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:42:16 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:42:16 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 12:42:16 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 12:42:16 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 12:42:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-14 12:42:16 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# make sure terminateListener is return error if we get called on iOS
,ok 290 error description matches
,# teardown
,ok 291 must be stopped
,# setup
,2017-07-14 12:42:17 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 12:42:17 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 12:42:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:42:17 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 12:42:17 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 12:42:17 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:42:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:42:17 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# make sure we actually call kill connections properly
,ok 292 IMPLEMENT ME!!!!!!
,# teardown
,ok 293 must be stopped
,# setup
,2017-07-14 12:42:17 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 12:42:17 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:42:17 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:42:17 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 12:42:17 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 12:42:17 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 12:42:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-14 12:42:17 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
,2017-07-14 12:42:17 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''
,# teardown
,ok 294 must be stopped
,# setup
,2017-07-14 12:42:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 12:42:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:42:18 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:42:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 12:42:18 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 12:42:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 12:42:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-14 12:42:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager
,2017-07-14 12:42:18 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''
,# teardown
,ok 295 must be stopped
,# setup
,2017-07-14 12:42:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 12:42:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:42:18 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:42:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 12:42:18 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 12:42:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 12:42:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-14 12:42:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# We fire failedNativeConnection event when we get failedConnection from multiConnectConnection
,2017-07-14 12:42:18 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 296 must be stopped
,# setup
,2017-07-14 12:42:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 12:42:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:42:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:42:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 12:42:18 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 12:42:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 12:42:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-14 12:42:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection
,2017-07-14 12:42:18 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 297 must be stopped
,# setup
,2017-07-14 12:42:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 12:42:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:42:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:42:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 12:42:19 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 12:42:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 12:42:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-14 12:42:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved
,ok 298 NOT IMPLEMENTED # SKIP
,# teardown
,ok 299 must be stopped
,# setup
,2017-07-14 12:42:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 12:42:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:42:19 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:42:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 12:42:19 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 12:42:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 12:42:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-14 12:42:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# make sure bad PSK connections fail
,2017-07-14 12:42:19 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure bad PSK connections fail''
,# teardown
,ok 300 must be stopped
,# setup
,2017-07-14 12:42:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 12:42:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:42:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:42:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 12:42:19 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 12:42:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 12:42:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-14 12:42:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# peer changes handled from a queue
,2017-07-14 12:42:19 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer changes handled from a queue''
,# teardown
,ok 301 must be stopped
,# setup
,2017-07-14 12:42:20 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 12:42:20 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:42:20 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:42:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 12:42:20 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 12:42:20 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 12:42:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-14 12:42:20 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# relaying discoveryAdvertisingStateUpdateNonTCP
,2017-07-14 12:42:20 - DEBUG CoordinatedClient: 'test was skipped, name: 'relaying discoveryAdvertisingStateUpdateNonTCP''
,# teardown
,ok 302 must be stopped
,# setup
,2017-07-14 12:42:20 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 12:42:20 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:42:20 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:42:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 12:42:20 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 12:42:20 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 12:42:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-14 12:42:20 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received
,2017-07-14 12:42:20 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''
,# teardown
,ok 303 must be stopped
,# setup
,2017-07-14 12:42:20 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 12:42:20 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:42:20 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:42:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 12:42:20 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 12:42:20 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 12:42:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-14 12:42:20 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# we successfully receive and replay discoveryAdvertisingStateUpdate
,2017-07-14 12:42:21 - DEBUG thaliMobileNativeWrapper: 'listening 50594'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:7C4A2EAF-28E0-419C-ADF2-648DE04A094F
[ThaliCore] Browser.st,artListening
2017-07-14 12:42:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-14 12:42:21 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 12:42:21 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
ok 304 discoveryActive matches
ok 305 advertisingActive matches
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-14 12:42:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonT,C,P: {"discoveryActive":true,"advertisingActive":false}'
2017-07-14 12:42:21 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 12:42:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisemen,ts()
[ThaliCore] Browser.stopListening()
2017-07-14 12:42:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:42:21 - INFO thaliMobile: 'Filtered out discoveryAd,vertisingStateUpdate (was in stopped state).'
ok 306 discoveryActive matches
ok 307 advertisingActive matches
2017-07-14 12:42:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 12:42:21 - DEBUG thaliMobileNativeWrapper: 'listening 50595'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "D56AD682-6B96-4E4B-A786-E6C46766CE3B", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:D56AD682-6B96-4E4B-A786-E6C46766CE3B
,2017-07-14 12:42:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 12:42:21 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 12:42:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 308 discoveryActive matches
ok 309 advertisingActive matches
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,2017-07-14 12:42:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:42:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 310 discoveryActive matches
,ok 311 advertisingActive matches
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 12:42:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:42:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
2017-07-14 12:42:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 12:42:21 - DEBUG thaliMobileNativeWrapper: 'listening 50597'
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 12:42:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:42:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 12:42:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:42:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 12:42:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 312 must be stopped
,# setup
,2017-07-14 12:42:21 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 12:42:21 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 12:42:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:42:21 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 12:42:21 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 12:42:21 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:42:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:42:21 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS
,2017-07-14 12:42:21 - DEBUG thaliMobileNativeWrapper: 'listening 50598'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:7E7F404C-123F-4CA2-B1CD-AD94407825EE
[ThaliCore] Browser.st,artListening
2017-07-14 12:42:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-14 12:42:21 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 12:42:21 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "7B98C49B-ECBB-43BA-B0CC-2DDC760B2D35", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID,:,7B98C49B-ECBB-43BA-B0CC-2DDC760B2D35
2017-07-14 12:42:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-14 12:42:21 - INFO thaliMobile: 'Received state ({"discoveryActi,ve":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 12:42:21 - INFO thaliMobile: ,'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BB105E64-5250-4426-A525-642D03982494:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BB105E64-5250-4426-A525-642D03982494", generation: 0)
2017-07-14 12:42:22 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"BB105E64-5250-4426-A525-642D03982494","generation":0}]'
2017-07-14 12:42:22 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"BB105E64-5250-4426-A525-642D03982494","generation":0}'
,2017-07-14 12:42:22 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"BB105E64-5250-4426-A525-642D03982494","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 12:42:22 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"BB105E64-5250-4426-A525-642D03982494","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 313 portNumber equal null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,2017-07-14 12:42:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-14 12:42:22 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 12:42:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-14 12:42:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:42:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 12:42:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 314 must be stopped
,# setup
,2017-07-14 12:42:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 12:42:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 12:42:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:42:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 12:42:22 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 12:42:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:42:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:42:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# can do HTTP requests between peers
,2017-07-14 12:42:22 - DEBUG thaliMobileNativeWrapper: 'listening 50600'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:00FF9654-BB0E-4289-89E5-D36EE19979CD
,[ThaliCore] Browser.startListening
,2017-07-14 12:42:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 12:42:22 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-14 12:42:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "A1B452C7-1CA9-493B-B5D2-61CAF3066822", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:A1B452C7-1CA9-493B-B5D2-61CAF3066822
,2017-07-14 12:42:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-14 12:42:22 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 12:42:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BB105E64-5250-4426-A525-642D03982494:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BB105E64-5250-4426-A525-642D03982494", generation: 0)
2017-07-14 12:42:23 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"BB105E64-5250-4426-A525-642D03982494","generation":0}]'
2017-07-14 12:42:23 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"BB105E64-5250-4426-A525-642D03982494","generation":0}'
,2017-07-14 12:42:23 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"BB105E64-5250-4426-A525-642D03982494","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 12:42:23 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"BB105E64-5250-4426-A525-642D03982494","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 12:42:23 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for BB105E64-5250-4426-A525-642D03982494 (syncValue: NvsNsOOXz4gr9m350UmiknBOxYB1ibXg)'
,2017-07-14 12:42:23 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "BB105E64-5250-4426-A525-642D03982494", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BB105E64-5250-4426-A525-642D03982494", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:BB105E64-5250-4426-A525-642D03982494:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CB92173D-6293-4EBE-A0FB-A434DD62F620:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CB92173D-6293-4EBE-A0FB-A434DD62F620", generation: 0)
2017-07-14 12:42:23 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"CB92173D-6293-4EBE-A0FB-A434DD62F620","generation":0}]'
2017-07-14 12:42:23 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"CB92173D-6293-4EBE-A0FB-A434DD62F620","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D8A1E24E-AAA7-492E-9A14-1611985D239C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D8A1E24E-AAA7-492E-9A14-1611985D239C", generation: 0)
2017-07-14 12:42:24 - DEBUG t,haliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"CB92173D-6293-4EBE-A0FB-A434DD62F620","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-14 12:42:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged ,from handlePeer {"peerIdentifier":"CB92173D-6293-4EBE-A0FB-A434DD62F620","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-14 12:42:24 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"CB92173,D-6293-4EBE-A0FB-A434DD62F620","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 12:42:24 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"D8A1E24E-AAA7-492E-9A14-1611985D239C","generation":0}]'
,2017-07-14 12:42:24 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"D8A1E24E-AAA7-492E-9A14-1611985D239C","generation":0}'
,2017-07-14 12:42:24 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"D8A1E24E-AAA7-492E-9A14-1611985D239C","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 12:42:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"D8A1E24E-AAA7-492E-9A14-1611985D239C","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-14 12:42:24 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"D8A1E24E-AAA7-492E-9A14-1611985D239C","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A1B452C7-1CA9-493B-B5D2-61CAF3066822:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A1B452C7-1CA9-493B-B5D2-61CAF3066822", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:BB105E64-5250-4426-A525-642D03982494:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "BB105E64-5250-4426-A525-642D03982494", generation: 0)
[ThaliCore] Session.disconnect() peer:BB105E64-5250-4426-A525-642D03982494:0
2017-07-14 12:42:28 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"BB105E64-5250-4426-A525-642D03982494","generation":0}]'
2017-07-14 12:42:,28 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"BB105E64-5250-4426-A525-642D03982494","generation":0}'
,2017-07-14 12:42:28 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"BB105E64-5250-4426-A525-642D03982494","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-14 12:42:28 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"BB105E64-5250-4426-A525-642D03982494","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:BB105E64-5250-4426-A525-642D03982494:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "BB105E64-5250-4426-A525-642D03982494", generation: 0)
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:BB105E64-5250-4426-A525-642D03982494:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "BB105E64-5250-4426-A525-642D03982494", genera,tion: 0)
2017-07-14 12:42:29 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"NvsNsOOXz4gr9m350UmiknBOxYB1ibXg","error":"Connection could not be established","portNumber":null}'
2017-07-14 12:42:29 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'NvsNsOOXz4gr9m350UmiknBOxYB1ibXg', error: 'Connection could not be established', listeningPort: '%s''
2017-07-14 12:42:29 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,t,ifier":"BB105E64-5250-4426-A525-642D03982494","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-14 12:42:29 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"BB105E64-5250-4426-A525-642D03982494","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-14 12:42:29 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"BB105E64-5250-4426-A525-642D03982494","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-14 12:42:29 - DEBUG thali,MobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"BB105E64-5250-4426-A525-642D03982494","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-14 12:42:29 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peer,Identifier":"BB105E64-5250-4426-A525-642D03982494","peerAvailable":true,"portNumber":null,"recreated":true}'
[ThaliCore] BrowserManager.disconnect peer:BB105E64-5250-4426-A525-642D03982494
2017-07-14 12:42:29 - ERROR thaliMobileNativeTestUtils: 'Fatal co,nnect error: 'Connection could not be established''
2017-07-14 12:42:29 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for CB92173D-6293-4EBE-A0FB-A434DD62F620 (syncValue: qerKA70O2xfsJSyZd5Y3vEKOV8b69KkV)'
2017-07-14 12:42:29 - DEBUG thaliMo,b,ileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "CB92173D-6293-4EBE-A0FB-A434DD62F620", generation: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:session,NotConnected:) Peer(uuid: "CB92173D-6293-4EBE-A0FB-A434DD62F620", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:CB92173D-6293-4EBE-A0FB-A434DD62F620:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtu,alSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:CB92173D-6293-4EBE-A0FB-A434DD62F620:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:6A25B447-0B97-4AF3-8976-F39B69238394
[ThaliCore] Advertiser: session connected Peer(uuid: "A1B452C7-1CA9-493B-B5D2-61CAF3066822", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:6A25B447-0B97-4AF3-8976-F39B69238394 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CB1D2901-E973-4AA9-BB6A-4759081EBB4A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CB1D2901-E973-4AA9-BB6A-4759081EBB4A", generation: 0)
2017-07-14 12:42:30 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"CB1D2901-E973-4AA9-BB6A-4759081EBB4A","generation":0}]'
2017-07-14 12:42:30 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"CB1D2901-E973-4AA9-BB6A-4759081EBB4A","generation":0}'
,2017-07-14 12:42:30 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"CB1D2901-E973-4AA9-BB6A-4759081EBB4A","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-14 12:42:30 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"CB1D2901-E973-4AA9-BB6A-4759081EBB4A","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-14 12:42:30 - DEBUG thaliMobileNativeTestUtils: 'We got a pe,er {"peerIdentifier":"CB1D2901-E973-4AA9-BB6A-4759081EBB4A","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:CB92173D-6293-4EBE-A0FB-A434DD62F620:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:CB92173D-6293-4EBE-A0FB-A434DD62F620:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "CB92173D-6293-4EBE-A0FB-A434DD62F620", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50605
2017-07-14 12:42:32 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"qerKA70O2xfsJSyZd5Y3vEKOV8b69KkV","error":null,"portN,umber":50605}'
,2017-07-14 12:42:32 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'qerKA70O2xfsJSyZd5Y3vEKOV8b69KkV', error: 'null', listeningPort: '50605''
,2017-07-14 12:42:32 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:CB92173D-6293-4EBE-A0FB-A434DD62F620:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:CB92173D-6293-4EBE-A0FB-A434DD62F620:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:12 [1, 3, 4, 10, 12]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-14 12:42:32 - DEBUG testUtils: 'Got response data'
2017-07-14 12:42:32 - DEBUG testUtils: 'Got end'
,ok 315 response body should match testData
ok 316 must be started
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:6A25B447-0B97-4AF3-8976-F39B69238394
,[ThaliCore] Session.session(_:peer:didChange:) peer:6A25B447-0B97-4AF3-8976-F39B69238394 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:6A25B447-0B97-4AF3-8976-F39B69238394
[ThaliCore] Session.startOutputStream(with:) peer:6A25B447-0B97-4AF3-8976-F39B69238394
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:13 [1, 3, 4, 10, 12, 13]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,2017-07-14 12:42:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-14 12:42:35 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 12:42:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-14 12:42:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:42:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 12:42:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 317 must be stopped
,[ThaliCore] BrowserManager.disconnect peer:CB92173D-6293-4EBE-A0FB-A434DD62F620
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50605
[ThaliCore] VirtualSocket.clos,eStreams() vsID:12
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:true
[ThaliCore] Session.disconnect() peer:CB92173D-6293-4EBE-A0FB-A434DD62F620:0
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socke,tDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:13
[ThaliCore] VirtualSocket.closeStreams() vs,ID:13
[ThaliCore] VirtualSocket exited RunLoop vsID:12
[ThaliCore] VirtualSocket.deinit vsID:12 [1, 3, 4, 10, 13]
,[ThaliCore] Session.session(_:peer:didChange:) peer:CB92173D-6293-4EBE-A0FB-A434DD62F620:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "CB92173D-6293-4EBE-A0FB-A434DD62F620", generation: 0)
[ThaliCore] Browser: s,ession notConnected removed relay for Peer(uuid: "CB92173D-6293-4EBE-A0FB-A434DD62F620", generation: 0)
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:13
[ThaliCore] VirtualSocket.deinit vsID:13 [1, 3, 4, 10]
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:6A25B447-0B97-4AF3-8976-F39B69238394 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "A1B452C7-1CA9-493B-B5D2-61CAF3066822", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:6A25B447-0B97-4AF3-8976-F39B69238394
,[ThaliCore] AdvertiserRelay.deinit
[ThaliCore] Session.deinit peer:6A25B447-0B97-4AF3-8976-F39B69238394
,2017-07-14 12:42:35 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 12:42:35 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:42:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:42:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 12:42:35 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 12:42:35 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 12:42:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-14 12:42:35 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# can still do HTTP requests between peers with coordinator
,2017-07-14 12:42:35 - DEBUG thaliMobileNativeWrapper: 'listening 50608'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:75023228-E093-46FB-8518-0D06A4A6D6C0
[ThaliCore] Browser.st,artListening
2017-07-14 12:42:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-14 12:42:35 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 12:42:35 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "530434CD-FD42-4B00-B7B0-D62CAE9735F1", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID,:,530434CD-FD42-4B00-B7B0-D62CAE9735F1
2017-07-14 12:42:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-14 12:42:35 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-14 12:42:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D8A1E24E-AAA7-492E-9A14-1611985D239C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D8A1E24E-AAA7-492E-9A14-1611985D239C", generation: 0)
2017-07-14 12:42:36 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"D8A1E24E-AAA7-492E-9A14-1611985D239C","generation":0}]'
2017-07-14 12:42:36 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"D8A1E24E-AAA7-492E-9A14-1611985D239C","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CB92173D-6293-4EBE-A0FB-A434DD62F620:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CB92173D-6293-4EBE-A0FB-A434DD62F620", generation: 0)
2017-07-14 12:42:36 - DEBUG t,haliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"D8A1E24E-AAA7-492E-9A14-1611985D239C","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-14 12:42:36 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"pe,erIdentifier":"D8A1E24E-AAA7-492E-9A14-1611985D239C","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-14 12:42:36 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for D8A1E24E-AAA7-492E-9A14-1611985D239C (syncValue: Vv83WlfAQH50T7l,oVakqsfaHjpzpfGGK)'
2017-07-14 12:42:36 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "D8A1E24E-AAA7-492E-9A14-1611985D239C", generation: 0) new relay
[Tha,l,iCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D8A1E24E-AAA7-492E-9A14-1611985D239C", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D8A1E24E-AAA7-492E-9A14-1611985D239C:0
[Th,aliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-14 12:42:36 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native l,ayer [{"peerAvailable":true,"peerIdentifier":"CB92173D-6293-4EBE-A0FB-A434DD62F620","generation":0}]'
,2017-07-14 12:42:36 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"CB92173D-6293-4EBE-A0FB-A434DD62F620","generation":0}'
,2017-07-14 12:42:36 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"CB92173D-6293-4EBE-A0FB-A434DD62F620","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-14 12:42:36 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"CB92173D-6293-4EBE-A0FB-A434DD62F620","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CFD7BC78-6165-4F86-9705-757C7CE0F24C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CFD7BC78-6165-4F86-9705-757C7CE0F24C", generation: 0)
2017-07-14 12:42:36 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"CFD7BC78-6165-4F86-9705-757C7CE0F24C","generation":0}]'
2017-07-14 12:42:36 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"CFD7BC78-6165-4F86-9705-757C7CE0F24C","generation":0}'
,2017-07-14 12:42:36 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"CFD7BC78-6165-4F86-9705-757C7CE0F24C","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 12:42:36 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"CFD7BC78-6165-4F86-9705-757C7CE0F24C","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-14 12:42:37 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"CFD7BC78-6165-4F86-9705-757C7CE0F24C","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DA5319DB-DF7F-4F8F-AF8F-6468B727A931:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DA5319DB-DF7F-4F8F-AF8F-6468B727A931", generation: 0)
2017-07-14 12:42:37 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"DA5319DB-DF7F-4F8F-AF8F-6468B727A931","generation":0}]'
2017-07-14 12:42:37 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"DA5319DB-DF7F-4F8F-AF8F-6468B727A931","generation":0}'
,2017-07-14 12:42:37 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"DA5319DB-DF7F-4F8F-AF8F-6468B727A931","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-14 12:42:37 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"DA5319DB-DF7F-4F8F-AF8F-6468B727A931","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-14 12:42:37 - DEBUG thaliMobileNativeTestUtils: 'We got a pe,er {"peerIdentifier":"DA5319DB-DF7F-4F8F-AF8F-6468B727A931","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:530434CD-FD42-4B00-B7B0-D62CAE9735F1:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "530434CD-FD42-4B00-B7B0-D62CAE9735F1", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:CB92173D-6293-4EBE-A0FB-A434DD62F620:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "CB92173D-6293-4EBE-A0FB-A434DD62F620", generation: 0)
2017-07-14 12:42:40 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"CB92173D-6293-4EBE-A0FB-A434DD62F620","generation":0}]'
2017-07-14 12:42:40 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"CB92173D-6293-4EBE-A0FB-A434DD62F620","generation":0}'
,2017-07-14 12:42:40 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"CB92173D-6293-4EBE-A0FB-A434DD62F620","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-14 12:42:40 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"CB92173D-6293-4EBE-A0FB-A434DD62F620","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:D8A1E24E-AAA7-492E-9A14-1611985D239C:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "D8A1E24E-AAA7-492E-9A14-1611985D239C", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:D8A1E24E-AAA7-492E-9A14-1611985D239C:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "D8A1E24E-AAA7-492E-9A14-1611985D239C", genera,tion: 0)
2017-07-14 12:42:42 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Vv83WlfAQH50T7loVakqsfaHjpzpfGGK","error":"Connection could not be established","portNumber":null}'
2017-07-14 12:42:42 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'Vv83WlfAQH50T7loVakqsfaHjpzpfGGK', error: 'Connection could not be established', listeningPort: '%s''
2017-07-14 12:42:42 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,t,ifier":"D8A1E24E-AAA7-492E-9A14-1611985D239C","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-14 12:42:42 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"D8A1E24E-AAA7-492E-9A14-161198,5D239C","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-14 12:42:42 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"D8A1E24E-AAA7-492E-9A14-1611985D239C","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-14 12:42:42 - DEBUG thali,Mobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"D8A1E24E-AAA7-492E-9A14-1611985D239C","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-14 12:42:42 - DEBUG thaliMobileNati,veWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"D8A1E24E-AAA7-492E-9A14-1611985D239C","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
2017-07-14 12:42:42 - DEBUG thaliMobile: 'Emitting peerAvailabilityChang,ed from handleRecreatedPeer {"peerIdentifier":"D8A1E24E-AAA7-492E-9A14-1611985D239C","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-14 12:42:42 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentif,i,er":"D8A1E24E-AAA7-492E-9A14-1611985D239C","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
2017-07-14 12:42:42 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-14 12:42:42 -, DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for CFD7BC78-6165-4F86-9705-757C7CE0F24C (syncValue: cWiFJVLNq1bMkTKlETR6OPab4jENNGpP)'
2017-07-14 12:42:42 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserMana,ger.connectToPeer(_:syncValue:completion:) Peer(uuid: "CFD7BC78-6165-4F86-9705-757C7CE0F24C", generation: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CFD7BC78-6165-4F86-9705-757C7CE0F24C", generati,on: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:CFD7BC78-6165-4F86-9705-757C7CE0F24C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:s,t,oppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:CFD7BC78-6165-4F86-9705-757C7CE0F24C:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:CFD7BC78-6165-4F86-9705-757C7CE0F24C:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:CFD7BC78-6165-4F86-9705-757C7CE0F24C:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "CFD7BC78-6165-4F86-9705-757C7CE0F24C", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50615
,2017-07-14 12:42:43 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"cWiFJVLNq1bMkTKlETR6OPab4jENNGpP","error":null,"portNumber":50615}'
,2017-07-14 12:42:43 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'cWiFJVLNq1bMkTKlETR6OPab4jENNGpP', error: 'null', listeningPort: '50615''
,2017-07-14 12:42:43 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:CFD7BC78-6165-4F86-9705-757C7CE0F24C:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:CFD7BC78-6165-4F86-9705-757C7CE0F24C:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:14 [1, 3, 4, 10, 14]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-14 12:42:44 - DEBUG testUtils: 'Got response data'
2017-07-14 12:42:44 - DEBUG testUtils: 'Got end'
ok 318 response body should match testData
ok 319 must be started
,# teardown
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:D8A1E24E-AAA7-492E-9A14-1611985D239C:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "D8A1E24E-AAA7-492E-9A14-1611985D239C", generation: 0)
2017-07-14 12:42:46 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"D8A1E24E-AAA7-492E-9A14-1611985D239C","generation":0}]'
2017-07-14 12:42:46 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"D8A1E24E-AAA7-492E-9A14-1611985D239C","generation":0}'
,2017-07-14 12:42:46 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"D8A1E24E-AAA7-492E-9A14-1611985D239C","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-14 12:42:46 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"D8A1E24E-AAA7-492E-9A14-1611985D239C","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
,2017-07-14 12:42:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 12:42:51 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-14 12:42:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-14 12:42:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:42:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 12:42:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 320 must be stopped
,[ThaliCore] BrowserManager.disconnect peer:CFD7BC78-6165-4F86-9705-757C7CE0F24C
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50615
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] VirtualSocket.closeStreams() vsID:14
,[ThaliCore] VirtualSocket exited RunLoop vsID:14
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:true
,[ThaliCore] VirtualSocket.deinit vsID:14 [1, 3, 4, 10]
,[ThaliCore] Session.disconnect() peer:CFD7BC78-6165-4F86-9705-757C7CE0F24C:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:CFD7BC78-6165-4F86-9705-757C7CE0F24C:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "CFD7BC78-6165-4F86-9705-757C7CE0F24C", generation: 0)
[ThaliCore] BrowserRel,ay.closeRelay() disconnecting:true
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "CFD7BC78-6165-4F86-9705-757C7CE0F24C", generation: 0)
,# setup
,2017-07-14 12:42:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 12:42:52 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:42:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:42:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 12:42:52 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 12:42:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 12:42:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-14 12:42:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# calls correct starts when network changes
,2017-07-14 12:42:52 - DEBUG CoordinatedClient: 'test was skipped, name: 'calls correct starts when network changes''
,# teardown
,ok 321 must be stopped
,# setup
,2017-07-14 12:42:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 12:42:52 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:42:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:42:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 12:42:52 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 12:42:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 12:42:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-14 12:42:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# test to coordinate connection cut
,# teardown
,ok 322 must be stopped
,# setup
,2017-07-14 12:42:53 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 12:42:53 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 12:42:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:42:53 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 12:42:53 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 12:42:53 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 12:42:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-14 12:42:53 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# can do HTTP requests after connections are cut
,2017-07-14 12:42:53 - DEBUG thaliMobileNativeWrapper: 'listening 50617'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:25CE863C-B9B2-414C-A6DF-F2C123B24601
,[ThaliCore] Browser.startListening
,2017-07-14 12:42:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 12:42:53 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 12:42:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "1012162F-2335-4678-93BD-74D50507EA9B", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:1012162F-2335-4678-93BD-74D50507EA9B
,2017-07-14 12:42:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-14 12:42:53 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-14 12:42:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DA5319DB-DF7F-4F8F-AF8F-6468B727A931:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DA5319DB-DF7F-4F8F-AF8F-6468B727A931", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:CFD7BC78-6165-4F86-9705-757C7CE0F24C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CFD7BC78-6165-4F86-9705-757C7CE0F24C", generation: 0)
2017-07-14 12:42:54 - DEBUG thaliMobileNativeWrapper: 'Rec,eived peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"DA5319DB-DF7F-4F8F-AF8F-6468B727A931","generation":0}]'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:67F286DC-98FD-4585-9BD1-6FD40C617,89A:0
2017-07-14 12:42:54 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"DA5319DB-DF7F-4F8F-AF8F-6468B727A931","generation":0}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Pee,r(uuid: "67F286DC-98FD-4585-9BD1-6FD40C61789A", generation: 0)
2017-07-14 12:42:54 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"CFD7BC78-6165-4F86-9705-757C7CE0F24C",",generation":0}]'
,2017-07-14 12:42:54 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"CFD7BC78-6165-4F86-9705-757C7CE0F24C","generation":0}'
,2017-07-14 12:42:54 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"67F286DC-98FD-4585-9BD1-6FD40C61789A","generation":0}]'
2017-07-14 12:42:54 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"67F286DC-98FD-4585-9BD1-6FD40C61789A","generation":0}'
,2017-07-14 12:42:54 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"DA5319DB-DF7F-4F8F-AF8F-6468B727A931","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 12:42:54 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"DA5319DB-DF7F-4F8F-AF8F-6468B727A931","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 12:42:54 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for DA5319DB-DF7F-4F8F-AF8F-6468B727A931 (syncValue: mOh7LakHRL59f0h0YAuRioVzfJcsaFSq)'
,2017-07-14 12:42:54 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "DA5319DB-DF7F-4F8F-AF8F-6468B727A931", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "DA5319DB-DF7F-4F8F-AF8F-6468B727A931", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:DA5319DB-DF7F-4F8F-AF8F-6468B727A931:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-14 12:42:54 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"CFD7BC78-6165-4F86-9705-757C7CE0F24C","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-14 12:42:54 - DEBUG thaliMobileNativeT,estUtils: 'We got a peer {"peerIdentifier":"CFD7BC78-6165-4F86-9705-757C7CE0F24C","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 12:42:54 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"67F286DC-98FD-4585-9BD1-6FD40C61789A","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 12:42:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"67F286DC-98FD-4585-9BD1-6FD40C61789A","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-14 12:42:54 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"67F286DC-98FD-4585-9BD1-6FD40C61789A","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1C8CE36E-EC3D-47B0-B0A5-661FC49CAF92:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1C8CE36E-EC3D-47B0-B0A5-661FC49CAF92", generation: 0)
2017-07-14 12:42:54 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"1C8CE36E-EC3D-47B0-B0A5-661FC49CAF92","generation":0}]'
2017-07-14 12:42:54 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"1C8CE36E-EC3D-47B0-B0A5-661FC49CAF92","generation":0}'
,2017-07-14 12:42:54 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"1C8CE36E-EC3D-47B0-B0A5-661FC49CAF92","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-14 12:42:54 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1C8CE36E-EC3D-47B0-B0A5-661FC49CAF92","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-14 12:42:54 - DEBUG thaliMobileNativeTestUtils: 'We got a pe,er {"peerIdentifier":"1C8CE36E-EC3D-47B0-B0A5-661FC49CAF92","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1012162F-2335-4678-93BD-74D50507EA9B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1012162F-2335-4678-93BD-74D50507EA9B", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:DA5319DB-DF7F-4F8F-AF8F-6468B727A931:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "DA5319DB-DF7F-4F8F-AF8F-6468B727A931", generation: 0)
[ThaliCore] Session.disconnect() peer:DA5319DB-DF7,F-4F8F-AF8F-6468B727A931:0
2017-07-14 12:42:58 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"DA5319DB-DF7F-4F8F-AF8F-6468B727A931","generation":0}]'
2017-07-14 12:42:,58 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"DA5319DB-DF7F-4F8F-AF8F-6468B727A931","generation":0}'
,2017-07-14 12:42:58 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"DA5319DB-DF7F-4F8F-AF8F-6468B727A931","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-14 12:42:58 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"DA5319DB-DF7F-4F8F-AF8F-6468B727A931","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:DA5319DB-DF7F-4F8F-AF8F-6468B727A931:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "DA5319DB-DF7F-4F8F-AF8F-6468B727A931", generation: 0)
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:DA5319DB-DF7F-4F8F-AF8F-6468B727A931:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "DA5319DB-DF7F-4F8F-AF8F-6468B727A931", genera,tion: 0)
2017-07-14 12:42:59 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"mOh7LakHRL59f0h0YAuRioVzfJcsaFSq","error":"Connection could not be established","portNumber":null}'
2017-07-14 12:42:59 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'mOh7LakHRL59f0h0YAuRioVzfJcsaFSq', error: 'Connection could not be established', listeningPort: '%s''
2017-07-14 12:42:59 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,t,ifier":"DA5319DB-DF7F-4F8F-AF8F-6468B727A931","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-14 12:42:59 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"DA5319DB-DF7F-4F8F-AF8F-6468B7,27A931","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-14 12:42:59 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"DA5319DB-DF7F-4F8F-AF8F-6468B727A931","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-14 12:42:59 - DEBUG thali,MobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"DA5319DB-DF7F-4F8F-AF8F-6468B727A931","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-14 12:42:59 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peer,Identifier":"DA5319DB-DF7F-4F8F-AF8F-6468B727A931","peerAvailable":true,"portNumber":null,"recreated":true}'
[ThaliCore] BrowserManager.disconnect peer:DA5319DB-DF7F-4F8F-AF8F-6468B727A931
2017-07-14 12:42:59 - ERROR thaliMobileNativeTestUtils: 'Fatal co,nnect error: 'Connection could not be established''
2017-07-14 12:42:59 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for CFD7BC78-6165-4F86-9705-757C7CE0F24C (syncValue: TXNPDT0xuPFXduNEruNwJMU4Sa2qCTdM)'
2017-07-14 12:42:59 - DEBUG thaliMo,b,ileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "CFD7BC78-6165-4F86-9705-757C7CE0F24C", generation: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:session,NotConnected:) Peer(uuid: "CFD7BC78-6165-4F86-9705-757C7CE0F24C", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:CFD7BC78-6165-4F86-9705-757C7CE0F24C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtu,alSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:CFD7BC78-6165-4F86-9705-757C7CE0F24C:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "CFD7BC78-6165-4F86-9705-757C7CE0F24C", generation: 0)
[ThaliCore] Session.disconnect() peer:CFD7BC78-616,5-4F86-9705-757C7CE0F24C:0
2017-07-14 12:43:01 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"CFD7BC78-6165-4F86-9705-757C7CE0F24C","generation":0}]'
2017-07-14 12:43:,01 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"CFD7BC78-6165-4F86-9705-757C7CE0F24C","generation":0}'
,2017-07-14 12:43:01 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"CFD7BC78-6165-4F86-9705-757C7CE0F24C","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-14 12:43:01 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"CFD7BC78-6165-4F86-9705-757C7CE0F24C","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:CFD7BC78-6165-4F86-9705-757C7CE0F24C:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "CFD7BC78-6165-4F86-9705-757C7CE0F24C", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:CFD7BC78-6165-4F86-9705-757C7CE0F24C:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "CFD7BC78-6165-4F86-9705-757C7CE0F24C", genera,tion: 0)
2017-07-14 12:43:05 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"TXNPDT0xuPFXduNEruNwJMU4Sa2qCTdM","error":"Connection could not be established","portNumber":null}'
2017-07-14 12:43:05 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'TXNPDT0xuPFXduNEruNwJMU4Sa2qCTdM', error: 'Connection could not be established', listeningPort: '%s''
2017-07-14 12:43:05 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdent,ifier":"CFD7BC78-6165-4F86-9705-757C7CE0F24C","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-14 12:43:05 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"CFD7BC78-6165-4F86-9705-757C7C,E0F24C","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-14 12:43:05 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"CFD7BC78-6165-4F86-9705-757C7CE0F24C","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-14 12:43:05 - DEBUG thali,MobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"CFD7BC78-6165-4F86-9705-757C7CE0F24C","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-14 12:43:05 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peer,Identifier":"CFD7BC78-6165-4F86-9705-757C7CE0F24C","peerAvailable":true,"portNumber":null,"recreated":true}'
[ThaliCore] BrowserManager.disconnect peer:CFD7BC78-6165-4F86-9705-757C7CE0F24C
2017-07-14 12:43:05 - ERROR thaliMobileNativeTestUtils: 'Fatal co,nnect error: 'Connection could not be established''
2017-07-14 12:43:05 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 67F286DC-98FD-4585-9BD1-6FD40C61789A (syncValue: RvGJNfUkRuyKqQ7zUctJ6fEP6PCFOBB8)'
2017-07-14 12:43:05 - DEBUG thaliMo,b,ileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "67F286DC-98FD-4585-9BD1-6FD40C61789A", generation: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "67F286DC-98FD-4585-9BD1-6FD40C61789A", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:67F286DC-98FD-4585-9BD1-6FD40C61789A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtu,alSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:67F286DC-98FD-4585-9BD1-6FD40C61789A:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:67F286DC-98FD-4585-9BD1-6FD40C61789A:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:67F286DC-98FD-4585-9BD1-6FD40C61789A:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "67F286DC-98FD-4585-9BD1-6FD40C61789A", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50626
2017-07-14 12:43:08 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"RvGJNfUkRuyKqQ7zUctJ6fEP6PCFOBB8",,"error":null,"portNumber":50626}'
2017-07-14 12:43:08 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'RvGJNfUkRuyKqQ7zUctJ6fEP6PCFOBB8', error: 'null', listeningPort: '50626''
,2017-07-14 12:43:08 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) pee,r:67F286DC-98FD-4585-9BD1-6FD40C61789A:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:67F286DC-98FD-4585-9BD1-6FD40C61789A:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:15 [1, 3, 4, 10, 15]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-14 12:43:09 - DEBUG testUtils: 'Got response data'
2017-07-14 12:43:09 - DEBUG testUtils: 'Got end'
ok 323 response body should match testData
ok 324 must be started
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
2017-07-14 12:43:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-14 12:43:09 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkT,ype":null}})'
2017-07-14 12:43:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-14 12:43:09 - DEBUG tha,liMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:43:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-14 12:43:09 - DEBU,G makeIntoCloseAllServer: 'closeAll called on server'
ok 325 must be stopped
[ThaliCore] BrowserManager.disconnect peer:67F286DC-98FD-4585-9BD1-6FD40C61789A
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50626
[ThaliCore] VirtualSocket.closeStreams() vsID:15
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnect,ing:true
[ThaliCore] Session.disconnect() peer:67F286DC-98FD-4585-9BD1-6FD40C61789A:0
[ThaliCore] VirtualSocket exited RunLoop vsID:15
[ThaliCore] VirtualSocket.deinit vsID:15 [1, 3, 4, 10]
[ThaliCore] Session.session(_:peer:didChange:) peer:67F286DC-9,8FD-4585-9BD1-6FD40C61789A:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "67F286DC-98FD-4585-9BD1-6FD40C61789A", generation: 0)
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "67F286DC-98,FD-4585-9BD1-6FD40C61789A", generation: 0)
# setup
,2017-07-14 12:43:09 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 12:43:09 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:43:09 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:43:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 12:43:09 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 12:43:09 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 12:43:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-14 12:43:09 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# will fail bad PSK connection between peers
,ok 326 FIX ME, PLEASE!!!
,# teardown
,ok 327 must be stopped
,# setup
,2017-07-14 12:43:10 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 12:43:10 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:43:10 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:43:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 12:43:10 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 12:43:10 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:43:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:43:10 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# We provide notification when a listener dies and we recreate it
,2017-07-14 12:43:10 - DEBUG CoordinatedClient: 'test was skipped, name: 'We provide notification when a listener dies and we recreate it''
,# teardown
,ok 328 must be stopped
,# setup
,2017-07-14 12:43:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 12:43:11 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:43:11 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:43:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 12:43:11 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 12:43:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 12:43:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-14 12:43:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated
,2017-07-14 12:43:11 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated''
,# teardown
,ok 329 must be stopped
,# setup
,ok 330 ThaliMobile should be stopped
,# #startListeningForAdvertisements should fail if start not called
,ok 331 specific error should be returned
,# teardown
,2017-07-14 12:43:11 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"CB1D2901-E973-4AA9-BB6A-4759081EBB4A","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-14, 12:43:11 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"67F286DC-98FD-4585-9BD1-6FD40C61789A","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-14 12:43:11 ,- DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"1C8CE36E-EC3D-47B0-B0A5-661FC49CAF92","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 332 error should be null
,ok 333 error should be null
,# setup
,ok 334 ThaliMobile should be stopped
,# #startUpdateAdvertisingAndListening should fail if start not called
,ok 335 specific error should be returned
,# teardown
,ok 336 error should be null
ok 337 error should be null
,# setup
,ok 338 ThaliMobile should be stopped
,# should be able to call #stopListeningForAdvertisements many times
,2017-07-14 12:43:12 - DEBUG thaliMobileNativeWrapper: 'listening 50628'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-14 12:43:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"ad,vertisingActive":false}'
ok 339 error should be null
ok 340 error should be null
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-14 12:43:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive,":false,"advertisingActive":false}'
ok 341 error should be null
ok 342 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-14 12:43:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:43:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-14 12:43:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:43:12 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-14 12:43:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 343 error should be null
ok 344 error should be null
,# setup
,ok 345 ThaliMobile should be stopped
,# should be able to call #startListeningForAdvertisements many times
,2017-07-14 12:43:12 - DEBUG thaliMobileNativeWrapper: 'listening 50629'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:BB06352F-A8BC-4787-9708-693C465794CE
[ThaliCore] Browser.st,artListening
2017-07-14 12:43:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
ok 346 error should be null
ok 347 error should be null
[ThaliCore] BrowserManager.startListe,ningForAdvertisements
,2017-07-14 12:43:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
ok 348 error should be null
ok 349 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-14 12:43:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-14 12:43:13 - INFO thaliMobile: 'Received state ({"d,iscoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
,2017-07-14 12:43:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-14 12:43:13 - DEBUG thaliMobileNativeW,rapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:43:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 12:43:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 350 error should be null
,ok 351 error should be null
,# setup
,ok 352 ThaliMobile should be stopped
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-07-14 12:43:13 - DEBUG thaliMobileNativeWrapper: 'listening 50630'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "93A1A02C-8772-4FA0-A753-7ED3192B2FA0", generation: 0)
[ThaliCore] Advertiser.startA,dvertising with peerID:93A1A02C-8772-4FA0-A753-7ED3192B2FA0
2017-07-14 12:43:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 353 error should be null
ok 354 error should, be null
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "93A1A02C-8772-4FA0-A753-7ED3192B2FA0", generation: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:93A1A02C-8772-4FA0-A753-7ED3192B2FA0
20,17-07-14 12:43:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 355 error should be null
ok 356 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
2017-07-14 12:43:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"adv,ertisingActive":false}'
2017-07-14 12:43:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-14 12:43:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:43:13 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-14 12:43:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 357 error should be null
ok 358 error should be null
,# setup
,ok 359 ThaliMobile should be stopped
,# should be able to call #stopAdvertisingAndListening many times
,2017-07-14 12:43:13 - DEBUG thaliMobileNativeWrapper: 'listening 50633'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-14 12:43:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingAct,ive":false}'
ok 360 error should be null
ok 361 error should be null
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-14 12:43:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActi,ve":false}'
,ok 362 error should be null
ok 363 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 12:43:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:43:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 12:43:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:43:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 12:43:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 364 error should be null
,ok 365 error should be null
,# setup
,ok 366 ThaliMobile should be stopped
,# #start - Causing native or wifi to fail will cause a promise reject 
,2017-07-14 12:43:14 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a Null'
,ok 367 This should not cause wifi to fail
ok 368 native router should be bad
,# teardown
,ok 369 error should be null
,ok 370 error should be null
,# setup
,ok 371 ThaliMobile should be stopped
,# #start should fail if called twice in a row
,2017-07-14 12:43:14 - DEBUG thaliMobileNativeWrapper: 'listening 50635'
,ok 372 first call should succeed
,ok 373 first call should succeed
,ok 374 specific error should be returned
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 12:43:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:43:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 12:43:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:43:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 12:43:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 375 error should be null
,ok 376 error should be null
,# setup
,ok 377 ThaliMobile should be stopped
,# #start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)
,2017-07-14 12:43:14 - DEBUG CoordinatedClient: 'test was skipped, name: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''
,# teardown
,ok 378 error should be null
ok 379 error should be null
,# setup
,ok 380 ThaliMobile should be stopped
,# does not emit duplicate discoveryAdvertisingStateUpdate
,2017-07-14 12:43:15 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not emit duplicate discoveryAdvertisingStateUpdate''
,# teardown
,ok 381 error should be null
,ok 382 error should be null
,# setup
,ok 383 ThaliMobile should be stopped
,# does not send duplicate availability changes
,2017-07-14 12:43:15 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"80d8ce94-c202-4bab-bae5-ee013893030a","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 384 should be called once
,ok 385 should not have been called more than once
,# teardown
,2017-07-14 12:43:15 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"80d8ce94-c202-4bab-bae5-ee013893030a","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 386 error should be null
,ok 387 error should be null
,# setup
,ok 388 ThaliMobile should be stopped
,# can get the network status
,ok 389 network status should have certain non-empty properties
,# teardown
,ok 390 error should be null
ok 391 error should be null
,# setup
,ok 392 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer added/removed to/from cache (native)
,ok 393 we have not added peer to the cache yet
2017-07-14 12:43:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"6b440bb7-c305-449c-be21-a5c94a374b45","connectionType":"MPCF","peerAvailable":true,"generation":0,,"newAddressPort":false}'
ok 394 peer should be available
ok 395 cache contains native peer
2017-07-14 12:43:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"6b440bb7-c305-449c-be21-a5c94a374b45","connectionTyp,e":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
ok 396 peer should be unavailable
ok 397 peer has been removed from cache
,# teardown
,ok 398 error should be null
ok 399 error should be null
,# setup
,ok 400 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer added/removed to/from cache (wifi)
,ok 401 we have not added peer to the cache yet
2017-07-14 12:43:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1a52c147-23d1-428a-9efd-9ca4b6213b52","connectionType":"tcp","peerAvailable":true,"generation":0,",newAddressPort":false}'
ok 402 peer should be available
ok 403 cache contains wifi peer
2017-07-14 12:43:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1a52c147-23d1-428a-9efd-9ca4b6213b52","connectionType":,"tcp","peerAvailable":false,"generation":0,"newAddressPort":null}'
ok 404 peer should be unavailable
ok 405 peer has been removed from cache
,# teardown
,ok 406 error should be null
ok 407 error should be null
,# setup
,ok 408 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored
,2017-07-14 12:43:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"58dab2be-8a5b-4b6c-ab59-5f74efec0e0f","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 409 first peer is available
2017-07-14 12:43:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"dac4157e-b511-4e58-90dc-1b371350c223","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":,false}'
ok 410 second peer is available
ok 411 first and second peers are different
,# teardown
,2017-07-14 12:43:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"58dab2be-8a5b-4b6c-ab59-5f74efec0e0f","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-14, 12:43:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"dac4157e-b511-4e58-90dc-1b371350c223","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 412 error should be null
ok 413 error should be null
,# setup
,ok 414 ThaliMobile should be stopped
,# native available - new peer is cached
,ok 415 should not be in cache at start
2017-07-14 12:43:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"a59b9f9e-911b-4845-88ae-d25786a382cb","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddr,essPort":false}'
,ok 416 peer is available
,# teardown
,2017-07-14 12:43:17 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"a59b9f9e-911b-4845-88ae-d25786a382cb","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 417 error should be null
ok 418 error should be null
,# setup
,ok 419 ThaliMobile should be stopped
,# native available - peer with same port and different generation is cached (BLUETOOTH)
,2017-07-14 12:43:17 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with same port and different generation is cached (BLUETOOTH)''
,# teardown
,ok 420 error should be null
ok 421 error should be null
,# setup
,ok 422 ThaliMobile should be stopped
,# native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)
,2017-07-14 12:43:17 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)''
,# teardown
,ok 423 error should be null
,ok 424 error should be null
,# setup
,ok 425 ThaliMobile should be stopped
,# native available - peer with greater generation is cached (MPCF)
,2017-07-14 12:43:17 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5763e68d-9ec5-48ac-884a-4b0e8c5af449","connectionType":"MPCF","peerAvailable":true,"generation":2,"newAddressPort":false}'
ok 426 peer should be available
,2017-07-14 12:43:17 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5763e68d-9ec5-48ac-884a-4b0e8c5af449","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
ok 427 peer should be ,available
ok 428 should store correct generation
,# teardown
,2017-07-14 12:43:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"5763e68d-9ec5-48ac-884a-4b0e8c5af449","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 429 error should be null
ok 430 error should be null
,# setup
,ok 431 ThaliMobile should be stopped
,# native available - peer with same or older generation is ignored (MPCF)
,2017-07-14 12:43:18 - DEBUG thaliMobileNativeWrapper: 'listening 50636'
2017-07-14 12:43:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5f70a94c-8aa3-459a-bf72-c7335d62a292","connectionType":"MPCF","peerAvaila,ble":true,"generation":2,"newAddressPort":false}'
ok 432 discovered correct peer
ok 433 got correct generation
,2017-07-14 12:43:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5f70a94c-8aa3-459a-bf72-c7335d62a292","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
ok 434 discovered corr,ect peer
ok 435 got correct generation
,# teardown
,2017-07-14 12:43:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"5f70a94c-8aa3-459a-bf72-c7335d62a292","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore,] AdvertiserManager.stopAdvertising()
2017-07-14 12:43:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:43:18 - INFO thaliMobile: 'Filtered out discoveryAdvert,isingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-14 12:43:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017,-07-14 12:43:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-14 12:43:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 436 error should be null
ok 437 error should be null
,# setup
,ok 438 ThaliMobile should be stopped
,# native unavailable - new peer is ignored
,2017-07-14 12:43:18 - DEBUG thaliMobileNativeWrapper: 'listening 50637'
,2017-07-14 12:43:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"e0b77e9b-4dfd-42a3-9bfa-0719fa569880","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 439 discovered available peer
ok 440 peer is available
,# teardown
,2017-07-14 12:43:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"e0b77e9b-4dfd-42a3-9bfa-0719fa569880","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore,] AdvertiserManager.stopAdvertising()
2017-07-14 12:43:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:43:18 - INFO thaliMobile: 'Filtered out discoveryAdvert,isingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-14 12:43:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017,-07-14 12:43:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-14 12:43:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 441 error should be null
ok 442 error should be null
,# setup
,ok 443 ThaliMobile should be stopped
,# native unavailable - cached peer is removed
,2017-07-14 12:43:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"278541c6-d7a1-436b-a6a9-e6eebd38f1b3","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 444 peer should be available
2017-07-14 12:43:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"278541c6-d7a1-436b-a6a9-e6eebd38f1b3","connectionType":"MPCF","peerAvailable":false,"generation":0,"newAddressPor,t":null}'
ok 445 peer should be unavailable
ok 446 should be removed from cache
,# teardown
,ok 447 error should be null
ok 448 error should be null
,# setup
,ok 449 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for wifi peers
,2017-07-14 12:43:19 - DEBUG thaliMobileNativeWrapper: 'listening 50638'
2017-07-14 12:43:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"c9263ca5-ea00-4553-be2d-3ab7ba35cb54","connectionType":"MPCF","peerAvaila,ble":true,"generation":0,"newAddressPort":false}'
ok 450 first peer is expected to be available
2017-07-14 12:43:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"87b7af8f-e3a4-47d6-aeb2-24bbee9656ad","connectio,nType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 451 second peer is expected to be available
2017-07-14 12:43:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"87b7af8f-e3a4-,47d6-aeb2-24bbee9656ad","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 452 peer became unavailable
,ok 453 it was wifi peer
2017-07-14 12:43:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"87b7af8f-e3a4-47d6-aeb2-24bbee9656ad","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}',
ok 454 we found peer again
ok 455 it was wifi peer
2017-07-14 12:43:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"87b7af8f-e3a4-47d6-aeb2-24bbee9656ad","connectionType":"tcp","peerAvailable":false,,"generation":null,"newAddressPort":null}'
ok 456 peer became unavailable
ok 457 it was wifi peer
,# teardown
,2017-07-14 12:43:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"c9263ca5-ea00-4553-be2d-3ab7ba35cb54","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore,] AdvertiserManager.stopAdvertising()
2017-07-14 12:43:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:43:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-14 12:43:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpd,ateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:43:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 12:43:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 458 error should be null
,ok 459 error should be null
,# setup
,ok 460 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)
,2017-07-14 12:43:19 - DEBUG CoordinatedClient: 'test was skipped, name: 'networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)''
,# teardown
,ok 461 error should be null
ok 462 error should be null
,# setup
,ok 463 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)
,2017-07-14 12:43:19 - DEBUG thaliMobileNativeWrapper: 'listening 50639'
2017-07-14 12:43:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"d95ab4bf-ba75-4c82-84c1-8b9cd7747310","connectionType":"MPCF","peerAvaila,ble":true,"generation":0,"newAddressPort":false}'
ok 464 first peer is expected to be available
2017-07-14 12:43:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"adbeb308-cc3c-4e84-8366-abe3b6467be4","connectio,nType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 465 second peer is expected to be available
,2017-07-14 12:43:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"d95ab4bf-ba75-4c82-84c1-8b9cd7747310","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 466 pee,r became unavailable
2017-07-14 12:43:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"adbeb308-cc3c-4e84-8366-abe3b6467be4","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPor,t":null}'
ok 467 peer became unavailable
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-14 12:43:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:43:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-14 12:43:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpd,ateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:43:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-14 12:43:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 468 error should be null
,ok 469 error should be null
,# setup
,ok 470 ThaliMobile should be stopped
,# multiconnect failure - new peer is ignored (MPCF)
,2017-07-14 12:43:20 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - new peer is ignored (MPCF)''
,# teardown
,ok 471 error should be null
ok 472 error should be null
,# setup
,ok 473 ThaliMobile should be stopped
,# multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)
,2017-07-14 12:43:20 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''
,# teardown
,ok 474 error should be null
,ok 475 error should be null
,# setup
,ok 476 ThaliMobile should be stopped
,# newAddressPort field (TCP_NATIVE)
,2017-07-14 12:43:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"192c6bb5-ac28-4a46-bc97-92dea7707311","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 477 peer discovered first time does not have new address
,2017-07-14 12:43:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"192c6bb5-ac28-4a46-bc97-92dea7707311","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddressPort":false}'
,ok 478 address has not been changed
,2017-07-14 12:43:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"192c6bb5-ac28-4a46-bc97-92dea7707311","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddressPort":true}'
,ok 479 new port handled correctly
,2017-07-14 12:43:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"192c6bb5-ac28-4a46-bc97-92dea7707311","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddressPort":true}'
,ok 480 new host handled correctly
,2017-07-14 12:43:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"192c6bb5-ac28-4a46-bc97-92dea7707311","connectionType":"tcp","peerAvailable":false,"generation":20,"newAddressPort":null}'
,ok 481 newAddressPort is null for unavailable peers
,# teardown
,ok 482 error should be null
ok 483 error should be null
,# setup
,ok 484 ThaliMobile should be stopped
,# newAddressPort field (BLUETOOTH)
,2017-07-14 12:43:20 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort field (BLUETOOTH)''
,# teardown
,ok 485 error should be null
ok 486 error should be null
,# setup
,ok 487 ThaliMobile should be stopped
,# newAddressPort field (MPCF)
,ok 488 NOT IMPLEMENTED # SKIP
,# teardown
,ok 489 error should be null
ok 490 error should be null
,# setup
,ok 491 ThaliMobile should be stopped
,# newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)
,2017-07-14 12:43:21 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)''
,# teardown
,ok 492 error should be null
ok 493 error should be null
,# setup
,ok 494 ThaliMobile should be stopped
,# #getPeerHostInfo - error when peer has not been discovered yet
,ok 495 should be equal
,# teardown
,ok 496 error should be null
ok 497 error should be null
,# setup
,ok 498 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)
,2017-07-14 12:43:21 - DEBUG CoordinatedClient: 'test was skipped, name: '#getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)''
,# teardown
,ok 499 error should be null
ok 500 error should be null
,# setup
,ok 501 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)
,2017-07-14 12:43:22 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 502 contains expected properties
ok 503 the same hostAddress
ok 504 the same portNumber
,# teardown
,2017-07-14 12:43:22 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 505 error should be null
ok 506 error should be null
,# setup
,ok 507 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached wifi peer
,2017-07-14 12:43:22 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 508 contains expected properties
,ok 509 the same hostAddress
,ok 510 the same portNumber
,# teardown
,2017-07-14 12:43:22 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 511 error should be null
,ok 512 error should be null
,# setup
,ok 513 ThaliMobile should be stopped
,# #disconnect fails on wifi peers
,2017-07-14 12:43:22 - DEBUG thaliMobileNativeWrapper: 'listening 50640'
2017-07-14 12:43:22 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"92932fdc-4018-477f-9308-281a50a14c03","connectionType":"tcp","peerAvailab,le":true,"generation":0,"newAddressPort":false}'
ok 514 Got specific error message
,# teardown
,2017-07-14 12:43:22 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"92932fdc-4018-477f-9308-281a50a14c03","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore], AdvertiserManager.stopAdvertising()
2017-07-14 12:43:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:43:22 - INFO thaliMobile: 'Filtered out discoveryAdverti,singStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-14 12:43:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:43:22 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-14 12:43:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 515 error should be null
,ok 516 error should be null
,# setup
,ok 517 ThaliMobile should be stopped
,# #disconnect delegates native peers to the native wrapper
,2017-07-14 12:43:23 - DEBUG thaliMobileNativeWrapper: 'listening 50641'
,2017-07-14 12:43:23 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"074b0d04-493a-4662-87d9-7d7c7afefc19","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] BrowserManager.disconnect peer:074b0d04-493a-4662-87d9-7d7c7afefc19
,ok 518 native wrapper `disconnect` called once
,ok 519 native wrapper `disconnect` called with peer data
,# teardown
,2017-07-14 12:43:23 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"074b0d04-493a-4662-87d9-7d7c7afefc19","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore,] AdvertiserManager.stopAdvertising()
2017-07-14 12:43:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:43:23 - INFO thaliMobile: 'Filtered out discoveryAdvert,isingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-14 12:43:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017,-07-14 12:43:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-14 12:43:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 520 error should be null
ok 521 error should be null
,# setup
,ok 522 ThaliMobile should be stopped
,# network changes emitted correctly
,2017-07-14 12:43:23 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes emitted correctly''
,# teardown
,ok 523 error should be null
ok 524 error should be null
,# setup
,ok 525 ThaliMobile should be stopped
,# network changes not emitted in started state
,2017-07-14 12:43:23 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes not emitted in started state''
,# teardown
,ok 526 error should be null
ok 527 error should be null
,# setup
,ok 528 ThaliMobile should be stopped
,# network changes not emitted in stopped state
,2017-07-14 12:43:24 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes not emitted in stopped state''
,# teardown
,ok 529 error should be null
,ok 530 error should be null
,# setup
,ok 531 ThaliMobile should be stopped
,# We properly fire peer unavailable and then available when connection fails on Android
,2017-07-14 12:43:24 - DEBUG CoordinatedClient: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on Android''
,# teardown
,ok 532 error should be null
ok 533 error should be null
,# setup
,ok 534 ThaliMobile should be stopped
,# We properly fire peer unavailable and then available when connection fails on iOS
,2017-07-14 12:43:24 - DEBUG CoordinatedClient: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on iOS''
,# teardown
,ok 535 error should be null
ok 536 error should be null
,# setup
,ok 537 ThaliMobile should be stopped
,# If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen
,2017-07-14 12:43:25 - DEBUG CoordinatedClient: 'test was skipped, name: 'If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen''
,# teardown
,ok 538 error should be null
ok 539 error should be null
,# setup
,ok 540 ThaliMobile should be stopped
,# does not fire duplicate events after peer listener recreation
,2017-07-14 12:43:25 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not fire duplicate events after peer listener recreation''
,# teardown
,ok 541 error should be null
ok 542 error should be null
,# setup
,ok 543 ThaliMobile should be stopped
,# #stop should change peers
,2017-07-14 12:43:25 - DEBUG thaliMobileNativeWrapper: 'listening 50642'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C3169BAF-2759-4C97-9BA0-7B0BED91D878
[ThaliCore] Browser.startListening
2017-07-14 12:43:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 12:43:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"39416cba-e15e-4ab8-beb5-444f07d30782","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 544 Peer availabili,ties has one entry for our connection type
2017-07-14 12:43:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"389a2d48-cdbb-4278-b662-5b45e6d26b27","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 545 Peer availabilities has one entry for our connection type
,2017-07-14 12:43:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"39416cba-e15e-4ab8-beb5-444f07d30782","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-14 12:43:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"389a2d48-cdbb-4278-b662-5b45e6d26b27","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 12:43:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 12:43:25 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"pskIdToSecret":[102,111,111],"networkType":"BOTH"}})'
,2017-07-14 12:43:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-14 12:43:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:43:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 12:43:25 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 12:43:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 546 No peers
,ok 547 No peers
,ok 548 No peers
,# teardown
,ok 549 error should be null
,ok 550 error should be null
,# setup
,ok 551 ThaliMobile should be stopped
,# If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted
,2017-07-14 12:43:26 - DEBUG thaliMobileNativeWrapper: 'listening 50643'
2017-07-14 12:43:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"8aa0addb-ad5b-4d60-a20f-4062a354c656","connectionType":"MPCF","peerAvaila,ble":true,"generation":0,"newAddressPort":false}'
ok 552 1
ok 553 2
2017-07-14 12:43:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"c4024806-5da3-4607-a3d4-3d92e81a9925","connectionType":"MPCF","peerAvailabl,e":true,"generation":0,"newAddressPort":false}'
,# teardown
,2017-07-14 12:43:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"8aa0addb-ad5b-4d60-a20f-4062a354c656","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-14, 12:43:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"c4024806-5da3-4607-a3d4-3d92e81a9925","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore] Advertis,erManager.stopAdvertising()
2017-07-14 12:43:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:43:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingState,Update (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-14 12:43:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12,:,43:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-14 12:43:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 554 error should be null
ok 555 error should be null
,# setup
,ok 556 ThaliMobile should be stopped
,# peer should be found once after listening and discovery started
,2017-07-14 12:43:26 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer should be found once after listening and discovery started''
,# teardown
,ok 557 error should be null
ok 558 error should be null
,# setup
,ok 559 ThaliMobile should be stopped
,# can get data from all participants
,2017-07-14 12:43:27 - DEBUG thaliMobileNativeWrapper: 'listening 50644'
ok 560 error should be null
ok 561 error should be null
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "1A1FA89B-152B-41D0-B735-F1,ABE32DB4DB", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:1A1FA89B-152B-41D0-B735-F1ABE32DB4DB
2017-07-14 12:43:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive,":true}'
ok 562 error should be null
ok 563 error should be null
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:80413BE2-FDC0-4EF3-BBAE-DD50B8E1A4D4
[ThaliCore] Browser.startLi,stening
2017-07-14 12:43:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
ok 564 error should be null
,ok 565 error should be null
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:67F286DC-98FD-4585-9BD1-6FD40C61789A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "67F286DC-98FD-4585-9BD1-6FD40C61789A", generation: 0)
,2017-07-14 12:43:27 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"67F286DC-98FD-4585-9BD1-6FD40C61789A","generation":0}]'
2017-07-14 12:43:27 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"67F286DC-98FD-4585-9BD1-6FD40C61789A","generation":0}'
,2017-07-14 12:43:27 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"67F286DC-98FD-4585-9BD1-6FD40C61789A","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 12:43:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"67F286DC-98FD-4585-9BD1-6FD40C61789A","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-14 12:43:27 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 67F286DC-98FD-4585-9BD1-6FD40C61789A (syncValue: 0)'
,2017-07-14 12:43:27 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "67F286DC-98FD-4585-9BD1-6FD40C61789A", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "67F286DC-98FD-4585-9BD1-6FD40C61789A", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:67F286DC-98FD-4585-9BD1-6FD40C61789A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:ECC53031-B0F7-42CA-96F9-B11DCF478A34:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "ECC53031-B0F7-42CA-96F9-B11DCF478A34", generation: 0)
2017-07-14 12:43:28 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"ECC53031-B0F7-42CA-96F9-B11DCF478A34","generation":0}]'
2017-07-14 12:43:28 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"ECC53031-B0F7-42CA-96F9-B11DCF478A34","generation":0}'
,2017-07-14 12:43:28 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"ECC53031-B0F7-42CA-96F9-B11DCF478A34","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-14 12:43:28 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"ECC53031-B0F7-42CA-96F9-B11DCF478A34","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0E72115A-8DB3-42E8-94B5-C3755B9B7A1B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0E72115A-8DB3-42E8-94B5-C3755B9B7A1B", generation: 0)
,2017-07-14 12:43:28 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"0E72115A-8DB3-42E8-94B5-C3755B9B7A1B","generation":0}]'
2017-07-14 12:43:28 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"0E72115A-8DB3-42E8-94B5-C3755B9B7A1B","generation":0}'
,2017-07-14 12:43:28 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"0E72115A-8DB3-42E8-94B5-C3755B9B7A1B","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 12:43:28 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"0E72115A-8DB3-42E8-94B5-C3755B9B7A1B","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1A1FA89B-152B-41D0-B735-F1ABE32DB4DB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1A1FA89B-152B-41D0-B735-F1ABE32DB4DB", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:67F286DC-98FD-4585-9BD1-6FD40C61789A:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "67F286DC-98FD-4585-9BD1-6FD40C61789A", generation: 0)
[ThaliCore] Session.disconnect() peer:67F286DC-98F,D-4585-9BD1-6FD40C61789A:0
2017-07-14 12:43:31 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"67F286DC-98FD-4585-9BD1-6FD40C61789A","generation":0}]'
2017-07-14 12:43:,31 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"67F286DC-98FD-4585-9BD1-6FD40C61789A","generation":0}'
,2017-07-14 12:43:31 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"67F286DC-98FD-4585-9BD1-6FD40C61789A","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-14 12:43:31 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"67F286DC-98FD-4585-9BD1-6FD40C61789A","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:67F286DC-98FD-4585-9BD1-6FD40C61789A:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "67F286DC-98FD-4585-9BD1-6FD40C61789A", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:67F286DC-98FD-4585-9BD1-6FD40C61789A:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "67F286DC-98FD-4585-9BD1-6FD40C61789A", genera,tion: 0)
2017-07-14 12:43:32 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"0","error":"Connection could not be established","portNumber":null}'
2017-07-14 12:43:32 - DEBUG thaliMobileNativeWrapper: 'Received peer availability cha,nged event with {"peerIdentifier":"67F286DC-98FD-4585-9BD1-6FD40C61789A","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-14 12:43:32 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"67,F,286DC-98FD-4585-9BD1-6FD40C61789A","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-14 12:43:32 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"67F286DC-98FD-4585-9BD1-6FD40C61789A","pee,rAvailable":false,"portNumber":null,"recreated":true}'
2017-07-14 12:43:32 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"67F286DC-98FD-4585-9BD1-6FD40C61789A","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-14 12:43:32 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for ECC53031-B0F7-42CA-96F9-B11DCF478A34 (syncValue: 1)'
2017-07-14 12:43:32 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPee,r(_:syncValue:completion:) Peer(uuid: "ECC53031-B0F7-42CA-96F9-B11DCF478A34", generation: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "ECC53031-B0F7-42CA-96F9-B11DCF478A34", generation: 0)
[ThaliCo,re] Session.init(session:identifier:connected:notConnected:) peer:ECC53031-B0F7-42CA-96F9-B11DCF478A34:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:),
2017-07-14 12:43:32 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"67F286DC-98FD-4585-9BD1-6FD40C61789A","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-14 12:43:32 - DEBUG th,a,liMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"67F286DC-98FD-4585-9BD1-6FD40C61789A","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-14 12:43:32 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"67F286DC-98FD-4585-9BD1-6FD40C61789A","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-14 12:43:32 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdenti,fier":"67F286DC-98FD-4585-9BD1-6FD40C61789A","peerAvailable":true,"portNumber":null,"recreated":true}'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9F88746E-DCBC-4143-A067-419AE121C4CF
[ThaliCore] Advertiser: session connected Peer(uuid: "1A1FA89B-152B-41D0-B735-F1ABE32DB4DB", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:9F88746E-DCBC-4143-A067-419AE121C4CF state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:ECC53031-B0F7-42CA-96F9-B11DCF478A34:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:9F88746E-DCBC-4143-A067-419AE121C4CF
,[ThaliCore] Session.session(_:peer:didChange:) peer:9F88746E-DCBC-4143-A067-419AE121C4CF state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9F88746E-DCBC-4143-A067-419AE121C4CF
[ThaliCore] Session.startOutputStream(with:) peer:9F88746E-DCBC-4143-A067-419AE121C4CF
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,6 [1, 3, 4, 10, 16]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:34220E5A-8F40-4411-9054-05CFE8F1F788
[ThaliCore] Advertiser: session connected Peer(uuid: "1A1FA89B-152B-41D0-B735-F1ABE32DB4DB", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:34220E5A-8F40-4411-9054-05CFE8F1F788 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:ECC53031-B0F7-42CA-96F9-B11DCF478A34:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:ECC53031-B0F7-42CA-96F9-B11DCF478A34:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "ECC53031-B0F7-42CA-96F9-B11DCF478A34", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50651
2017-07-14 12:43:39 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"1","error":null,"portNumber":50651,}'
,2017-07-14 12:43:39 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 0E72115A-8DB3-42E8-94B5-C3755B9B7A1B (syncValue: 2)'
2017-07-14 12:43:39 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPee,r(_:syncValue:completion:) Peer(uuid: "0E72115A-8DB3-42E8-94B5-C3755B9B7A1B", generation: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "0E72115A-8DB3-42E8-94B5-C3755B9B7A1B", generation: 0)
[ThaliCo,re] Session.init(session:identifier:connected:notConnected:) peer:0E72115A-8DB3-42E8-94B5-C3755B9B7A1B:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:),
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:ECC53031-B0F7-42CA-96F9-B11DCF478A34:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:ECC53031-B0F7-42CA-96F9-B11DCF478A34:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:17 [1, 3, 4, 10, 16, 17]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-14 12:43:39 - DEBUG testUtils: 'Got response data'
,2017-07-14 12:43:39 - DEBUG testUtils: 'Got end'
,[ThaliCore] Session.session(_:peer:didChange:) peer:0E72115A-8DB3-42E8-94B5-C3755B9B7A1B:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:34220E5A-8F40-4411-9054-05CFE8F1F788
,[ThaliCore] Session.session(_:peer:didChange:) peer:34220E5A-8F40-4411-9054-05CFE8F1F788 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:34220E5A-8F40-4411-9054-05CFE8F1F788
[ThaliCore] Session.startOutputStream(with:) peer:34220E5A-8F40-4411-9054-05CFE8F1F788
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,8 [1, 3, 4, 10, 16, 17, 18]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:0E72115A-8DB3-42E8-94B5-C3755B9B7A1B:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:0E72115A-8DB3-42E8-94B5-C3755B9B7A1B:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "0E72115A-8DB3-42E8-94B5-C3755B9B7A1B", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50656
,2017-07-14 12:43:42 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"2","error":null,"portNumber":50656}'
,[ThaliCore] BrowserManager.disconnect peer:67F286DC-98FD-4585-9BD1-6FD40C61789A
,[ThaliCore] BrowserManager.disconnect peer:67F286DC-98FD-4585-9BD1-6FD40C61789A
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:0E72115A-8DB3-42E8-94B5-C3755B9B7A1B:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0E72115A-8DB3-42E8-94B5-C3755B9B7A1B:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:19 [1, 3, 4, 10, 16, 17, 18, 19]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-14 12:43:42 - DEBUG testUtils: 'Got response data'
,2017-07-14 12:43:42 - DEBUG testUtils: 'Got end'
,ok 566 received all uuids
,# teardown
,2017-07-14 12:43:45 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"ECC53031-B0F7-42CA-96F9-B11DCF478A34","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-14, 12:43:45 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"0E72115A-8DB3-42E8-94B5-C3755B9B7A1B","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore] Advertis,erManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,2017-07-14 12:43:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-14 12:43:45 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
2017-07-14 12:43:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] Brows,erManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-14 12:43:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:43:45 - INFO ,thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-14 12:43:45 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:,O,ptional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
ok 567 error should be null
ok 568 error should be null
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisco,nnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:16
# setup
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:18
[ThaliCore] VirtualSocket.closeStreams() vsID:16
[ThaliCore] VirtualSocket.closeStreams() vsID:18
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disco,nnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:16
[ThaliCore] VirtualSocket.deinit vsID:16 [1, 3, 4, 10, 17, 18, 19]
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunL,oop vsID:18
[ThaliCore] VirtualSocket.deinit vsID:18 [1, 3, 4, 10, 17, 19]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:17
[ThaliCore] VirtualSocket.closeStreams() vsID:17
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:17
,[ThaliCore] VirtualSocket.deinit vsID:17 [1, 3, 4, 10, 19]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] Session.session(_:peer:didChange:) peer:34220E5A-8F40-4411-9054-05CFE8F1F788 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "1A1FA89B-152B-41D0-B735-F1ABE32DB4DB", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:34220E5A-8F40-4411-9054-05CFE8F1F788
,[ThaliCore] AdvertiserRelay.deinit
[ThaliCore] Session.deinit peer:34220E5A-8F40-4411-9054-05CFE8F1F788
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:19
[ThaliCore] VirtualSocket.closeStreams() vsID:19
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:19,
[ThaliCore] VirtualSocket.deinit vsID:19 [1, 3, 4, 10]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSoc,ketDisconnectHandler
,ok 569 ThaliMobile should be stopped
,# test for data corruption
,2017-07-14 12:43:56 - DEBUG CoordinatedClient: 'test was skipped, name: 'test for data corruption''
,# teardown
,ok 570 error should be null
ok 571 error should be null
,# setup
,# #testThaliPeerAction - test getters
,ok 572 getPeerIdentifier
ok 573 getConnectionType
ok 574 getActionType
,ok 575 getActionState
ok 576 getPskIdentity
ok 577 getPskKey
,# teardown
,# setup
,# #testThaliPeerAction - start and kill
,ok 578 initial state
ok 579 after start
,2017-07-14 12:43:58 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 580 after kill
,# teardown
,# setup
,# #testThaliPeerAction - double start
,ok 581 should be equal
,# teardown
,# setup
,# #testThaliPeerAction - start after kill
,2017-07-14 12:43:59 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 582 clean kill
,ok 583 should be equal
,# teardown
,# setup
,# #testThaliPeerAction - make sure ids are unique
,ok 584 should not be equal
,# teardown
,# setup
,# #testThaliPeerAction - check that forever agent can be destroyed
,ok 585 forever agent should have it's own destroy method
ok 586 agent's destroy should be called
ok 587 agent's destroy should not be called again
ok 588 agent is destroyed
,# teardown
,# setup
,# Test PeerDictionary basic functionality
,ok 589 Entry counter must be 1
,ok 590 Entry exists
ok 591 Size must be 1
ok 592 Entry counter must be 2
ok 593 Entry exists
ok 594 Size must be 2
ok 595 Entry counter must be 1
ok 596 Entry exists
ok 597 Size must be 3
ok 598 Entry counter must be 2
ok 599 Entry exists
ok 600 Size must be 4
ok 601 Entry 1_1 should not be found
ok 602 Entry 1_1 does not exist
ok 603 Size must be 3
ok 604 Entry 1_2 should not be found
ok 605 Entry 1_2 does not exist
ok 606 Size must be 2
ok 607 should be equal
ok 608 Entry 2_1 should not ,be found
ok 609 Entry 2_2 should not be found
ok 610 Entry 2_1 does not exist
ok 611 Entry 2_2 does not exist
,ok 612 Size must be 0
,# teardown
,# setup
,# Test PeerDictionary with multiple entries.
,ok 613 Size must be100
,ok 614 Entries between 20 and MAXSIZE + 20 should exist
,ok 615 WAITING state entry should not be removed
,# teardown
,# setup
,# RESOLVED entries are removed before WAITING state entry.
,ok 616 Entries between 6 and MAXSIZE + 4 should exist
,ok 617 Size should be MAXSIZE
ok 618 Size should be MAXSIZE+6
,# teardown
,# setup
,# WAITING entries are removed before CONTROLLED_BY_POOL state entry.
,ok 619 WAITING state entry should not be removed
,ok 620 Waiting entries between 6 and MAXSIZE + 4 should exist
,ok 621 Size should be MAXSIZE
,ok 622 entryCounter should be MAXSIZE+6
,# teardown
,# setup
,# When CONTROLLED_BY_POOL entry is removed and kill is called.
,ok 623 Kill should be called once
,ok 624 Size should be MAXSIZE
,# teardown
,# setup
,# #ThaliPeerPoolDefault - single action
,ok 625 is an agent
,ok 626 enqueue is fine
ok 627 Everything should be off the queue
,# teardown
,# setup
,# #ThaliPeerPoolDefault - multiple actions
,ok 628 is an agent
ok 629 first enqueue is fine
,ok 630 is an agent
ok 631 second enqueue is fine
ok 632 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
ok 633 Queue is empty
,# teardown
,# setup
,# #ThaliPeerPoolDefault - PSK Pool works
,ok 634 is an agent
ok 635 good enqueue
,ok 636 Identity should match
,2017-07-14 12:44:04 - DEBUG testUtils: 'Got response data'
,2017-07-14 12:44:04 - DEBUG testUtils: 'Got end'
,ok 637 Got expected response
,ok 638 Got psk call back
,# teardown
,2017-07-14 12:44:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #ThaliPeerPoolDefault - stop
,ok 639 is an agent
,ok 640 enqueue worked
,ok 641 is an agent
,ok 642 enqueue 2 worked
,ok 643 enqueue is not available when stopped
,ok 644 start action is killed
,ok 645 killed action is still killed
,ok 646 enqueued action when stopped is killed
,ok 647 inQueue is empty
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure that start verifies queue length
,ok 648 good start
,ok 649 good enqueue
,ok 650 queue is not empty
,# teardown
,# setup
,# #ThaliPeerPoolInterface - bad enqueues
,ok 651 null arg
ok 652 wrong arg type
ok 653 wrong arg type
,# teardown
,# setup
,# #ThaliPeerPoolInterface - do not allow same object type
,ok 654 good enqueue
ok 655 already enqueued
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure we catch kill and dequeue
,ok 656 good enqueue
ok 657 2nd good enqueue
ok 658 we are in the pool
ok 659 We are out of the pool
ok 660 Action was killed
ok 661 The original kill was called too
ok 662 second item is still in queue
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent
,ok 663 good enqueue
,ok 664 first kill
,ok 665 second NOOP kill
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure that stop removes all actions
,ok 666 1st good enqueue
ok 667 2nd good enqueue
ok 668 1st action is in the pool
ok 669 2nd action is in the pool
ok 670 1st action is out of the pool
ok 671 2st action is out of the pool
ok 672 pool is empty
,# teardown
,# setup
,# We reject unrecognized connection type
,2017-07-14 12:44:07 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 673 Got right error
,ok 674 Start should not be called
,ok 675 Kill should have been called at least once
,# teardown
,# setup
,# We reject unrecognized action type
,2017-07-14 12:44:07 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
2017-07-14 12:44:07 - ERROR thaliPeerPoolOneAtATime: 'Got unsupported action type: blah'
ok 676 Got right error
ok 677 Start should not be called
ok 678 Kill should have been called at least once
,# teardown
,# setup
,# One action on bluetooth
,2017-07-14 12:44:07 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 679 Got null
,2017-07-14 12:44:07 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerID'
,ok 680 is an agent
,2017-07-14 12:44:07 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerID'
,ok 681 Got killed at least once
,# teardown
,# setup
,# Two notification actions
,2017-07-14 12:44:08 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 682 Got Null
,ok 683 Got another null
,2017-07-14 12:44:08 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId1'
,ok 684 is an agent
,2017-07-14 12:44:08 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId1'
,2017-07-14 12:44:08 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
,ok 685 is an agent
,2017-07-14 12:44:08 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
,ok 686 Action 1 killed at least once
,ok 687 Action 1 went first
,ok 688 Action 2 killed at least once
,# teardown
,# setup
,# replicateThroughProblems
,2017-07-14 12:44:09 - DEBUG thaliPeerPoolOneAtATime: 'Action Started success'
,2017-07-14 12:44:09 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - success'
,2017-07-14 12:44:09 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,ok 689 should have gotten null
,2017-07-14 12:44:09 - DEBUG thaliPeerPoolOneAtATime: 'Action Started noActivityTimeOut'
,2017-07-14 12:44:09 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: No activity time out - noActivityTimeOut'
,ok 690 Should have stopped nicely
,2017-07-14 12:44:09 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButNotAvailable'
,2017-07-14 12:44:09 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButNotAvailable'
,ok 691 Still looking for null
,2017-07-14 12:44:09 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButAvailable'
,2017-07-14 12:44:09 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButAvailable'
,2017-07-14 12:44:09 - DEBUG thaliPeerPoolOneAtATime: 'Replication action failed badly so we are going to retry'
,2017-07-14 12:44:09 - DEBUG thaliPeerPoolOneAtATime: 'Action Started clone!'
,2017-07-14 12:44:09 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - clone!'
,2017-07-14 12:44:09 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,ok 692 Yup, another null
,ok 693 We cloned!
,# teardown
,# setup
,# Replication goes first
,2017-07-14 12:44:09 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 694 Null 1
,ok 695 (unnamed assert)
,2017-07-14 12:44:09 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,ok 696 is an agent
,ok 697 Null 3
,ok 698 Replication not yet called
,ok 699 Notification 2 not yet called
,2017-07-14 12:44:09 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,2017-07-14 12:44:09 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
,ok 700 is an agent
ok 701 Notification went first
ok 702 Notification 2 not called yet
,2017-07-14 12:44:09 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
2017-07-14 12:44:09 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,2017-07-14 12:44:09 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,ok 703 is an agent
,ok 704 Notification finished
,ok 705 Replication finished
,2017-07-14 12:44:09 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,# teardown
,# setup
,# wifi allows many parallel non-replication actions
,2017-07-14 12:44:10 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
2017-07-14 12:44:10 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
ok 706 is an agent
ok 707 First does, not throw
2017-07-14 12:44:10 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
ok 708 is an agent
,ok 709 Second does not throw
,2017-07-14 12:44:10 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
,truetruefalsetrue
,2017-07-14 12:44:10 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
,truetruetruetrue
,# teardown
,# setup
,# wifi allows no more than 2 simultaneous replication actions for same peerID
,2017-07-14 12:44:10 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-14 12:44:10 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 595, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,ok 710 is an agent
,ok 711 first ok
,2017-07-14 12:44:10 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 596, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,ok 712 is an agent
,ok 713 second ok
,ok 714 third ok
,2017-07-14 12:44:10 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 595, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,2017-07-14 12:44:10 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 596, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,2017-07-14 12:44:10 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,2017-07-14 12:44:10 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,# teardown
,# setup
,# Client to server request coordinated
,2017-07-14 12:44:11 - DEBUG CoordinatedClient: 'test was skipped, name: 'Client to server request coordinated''
,# teardown
,2017-07-14 12:44:11 - INFO testThaliNotification: 'Participants:0 Peers Replied to us:0 Peers requested to:0'
,# setup
,# Test BEACONS_RETRIEVED_AND_PARSED locally
,ok 715 peerIdentifier should match
,ok 716 generation should match
,ok 717 Response should be BEACONS_RETRIEVED_AND_PARSED
,ok 718 good beacon
,ok 719 good preAmble
,ok 720 public keys match!
,ok 721 must return null after successful call
,ok 722 Once start returns the action should be in KILLED state
,# teardown
,2017-07-14 12:44:11 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test HTTP_BAD_RESPONSE locally
,ok 723 Response should be HTTP_BAD_RESPONSE
,ok 724 must return null after successful call
,# teardown
,2017-07-14 12:44:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test NETWORK_PROBLEM locally
,ok 725 Response should be NETWORK_PROBLEM
ok 726 reject reason should be: Could not establish TCP connection
,# teardown
,2017-07-14 12:44:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Action fails when getPeerHostInfo fails
,ok 727 Resolution should be BAD_PEER
,ok 728 correct error message
,# teardown
,2017-07-14 12:44:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the start two times
,ok 729 Call start once
,ok 730 Response should be BEACONS_RETRIEVED_AND_PARSED
,ok 731 must return null after successful call.
,# teardown
,2017-07-14 12:44:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill before calling the start
,ok 732 Should be Killed
,ok 733 Start after killed
,# teardown
,2017-07-14 12:44:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill immediately after the start
,ok 734 Should be KILLED
,ok 735 must return null after successful kill
,# teardown
,2017-07-14 12:44:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill while waiting a response from the server
,ok 736 Should be KILLED
ok 737 must return null after successful kill
,# teardown
,2017-07-14 12:44:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test to exceed the max content size locally
,ok 738 HTTP_BAD_RESPONSE should be response when content size is exceeded
,ok 739 must return null after successful call
,# teardown
,2017-07-14 12:44:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Close the server socket while the client is waiting a response from the server. Local test.
,2017-07-14 12:44:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 740 Should be NETWORK_PROBLEM caused closing server socket
ok 741 Should be Could not establish TCP connection
,# teardown
,# setup
,# Close the client socket while the client is waiting a response from the server. Local test.
,ok 742 Should be NETWORK_PROBLEM caused closing client socket
ok 743 Should be Could not establish TCP connection
,# teardown
,2017-07-14 12:44:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #generatePreambleAndBeacons bad args
,ok 744 publicKeysToNotify cannot be null
ok 745 ecdh for local device cannot be null
ok 746 milliseconds cannot be less than 0
,ok 747 milliseconds cannot be 0
,ok 748 milliseconds cannot be greater than one_day
,# teardown
,# setup
,# #generatePreambleAndBeacons empty keys to notify
,ok 749 should be equal
,# teardown
,# setup
,# #generatePreambleAndBeacons multiple keys to notify
,ok 750 should be equal
,ok 751 should be equal
,ok 752 (unnamed assert)
,ok 753 should be equal
,# teardown
,# setup
,# #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
,ok 754 should throw
,# teardown
,# setup
,# #parseBeacons invalid expiration in beaconStreamWithPreAmble
,ok 755 Preamble expiration must be a 64 bit integer
,# teardown
,# setup
,# #parseBeacons expiration out of range lower
,ok 756 Expiration out of range
,# teardown
,# setup
,# #parseBeacons expiration out of range lower
,ok 757 Expiration out of range
,# teardown
,# setup
,# #parseBeacons no beacons returns null
,ok 758 should be equal
,# teardown
,# setup
,# #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
,ok 759 Malformed encrypted beacon key ID
,# teardown
,# setup
,# #parseBeacons addressBookCallback fails decrypt
,ok 760 should be equal
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns no matches
,ok 761 should be equal
,ok 762 should be equal
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns spurious match
,ok 763 should be equal
ok 764 should be equal
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns public key
,ok 765 right number of calls to address book
ok 766 good preAmble
,ok 767 good unencryptedKeyId
,ok 768 good beacon
,# teardown
,# setup
,# validate generatePskIdentityField
,ok 769 decoded buffers match
,# teardown
,# setup
,# validate generatePskSecret
,ok 770 secrets match
,# teardown
,# setup
,# validate generatePskSecrets
,ok 771 Matching numbers
,ok 772 We have an entry!
,ok 773 keys match
,ok 774 secrets match
,ok 775 We have an entry!
,ok 776 keys match
ok 777 secrets match
,ok 778 We have an entry!
,ok 779 keys match
,ok 780 secrets match
,# teardown
,# setup
,# validate generateBeaconStreamAndSecrets
,ok 781 Streams have same length
,ok 782 matching size
,ok 783 keys match
,ok 784 secrets match
,# teardown
,# setup
,# Add two Peers.
,ok 785 should be equal
ok 786 peerDictionalty contains 2 peers
ok 787 bluetooth peer's notification has correct connection type
ok 788 tcp peer's notification has correct connection type
,2017-07-14 12:44:30 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
2017-07-14 12:44:30 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-07-14 12:44:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# TCP_NATIVE peer loses DNS
,ok 789 notification peer dictionary contains exactly 1 peer
,2017-07-14 12:44:30 - WARN thaliNotificationClient: 'peer is not available'
,ok 790 notification peer dictionary does not contain any peers
,2017-07-14 12:44:30 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-07-14 12:44:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Received beacons with no values for us
,ok 791 entry exists
,ok 792 entry is resolved
,# teardown
,2017-07-14 12:44:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Notification action killed with a superseded
,ok 793 Action should be KILLED
,ok 794 Peer state should be RESOLVED
,# teardown
,2017-07-14 12:44:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally
,ok 795 hostAddress must match
ok 796 portNumber must match
,ok 797 suggestedTCPTimeout must match
,ok 798 connectionType must match
ok 799 peerIDs must match
,# teardown
,2017-07-14 12:44:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Emits error event when peerPool.enqueue throws
,ok 800 Correct error
,# teardown
,2017-07-14 12:44:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally using ThaliPeerPoolDefault
,ok 801 hostAddress must match
,ok 802 portNumber must match
,ok 803 suggestedTCPTimeout must match
,ok 804 connectionType must match
,ok 805 peerIds must match
,# teardown
,2017-07-14 12:44:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Action fails because of a bad hostname.
,2017-07-14 12:44:33 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 806 action should be resolved with NETWORK_PROBLEM error
,2017-07-14 12:44:33 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 807 action should be resolved with NETWORK_PROBLEM error
,2017-07-14 12:44:34 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 808 action should be resolved with NETWORK_PROBLEM error
,2017-07-14 12:44:34 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 809 action should be resolved with NETWORK_PROBLEM error
ok 810 correct number of requests
ok 811 correct number of failures
ok 812 correct final peer state
,# teardown
,2017-07-14 12:44:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# hostaddress is removed when the action is running. 
,2017-07-14 12:44:37 - WARN thaliNotificationClient: 'peer is not available'
2017-07-14 12:44:37 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 813 peerDictionary should become empty
,# teardown
,2017-07-14 12:44:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notificationClient does not retry action with BAD_PEER resolution
,2017-07-14 12:44:37 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 814 failed with expected error
ok 815 peer state should be RESOLVED
,# teardown
,2017-07-14 12:44:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notification client correctly handles peer availability changes of the same peer
,2017-07-14 12:44:38 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 816 First action failed
,ok 817 second action killed
# teardown
,2017-07-14 12:44:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Client to server request locally
,ok 818 secrets are equal
ok 819 Public key matches with the server key
,ok 820 hostAddress must match
ok 821 portNumber must match
,ok 822 suggestedTCPTimeout must match
ok 823 connectionType must match
,# teardown
,2017-07-14 12:44:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache clean and expiration
,ok 824 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE
,ok 825 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE-1
,ok 826 All entries should be expired after 1 second
# teardown
,2017-07-14 12:44:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache getSecret and getPublic
,ok 827 All keys need to be available in the cache
,ok 828 All entries should be expired after 1 second
# teardown
,2017-07-14 12:44:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache multiple entries
,ok 829 Size of the cache should be 2
ok 830 Cache doesn't contain dictionary1
,ok 831 Size of the cache should be 1
,ok 832 Cache doesn't contain beaconStreamAndSecretDictionary2
,# teardown
,2017-07-14 12:44:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Start and stop ThaliNotificationServer
,ok 833 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
ok 834 ThaliMobile.StopAdvertisingAndListeningshould be called once
,# teardown
,2017-07-14 12:44:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass an empty array to ThaliNotificationServer.start
,ok 835 StartUpdateAdvertisingAndListening should not be called
,ok 836 ThaliMobile.StopAdvertisingAndListening should be called once
,ok 837 no error
,ok 838 should be 204
,# teardown
,2017-07-14 12:44:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass a string to ThaliNotificationServer.start
,ok 839 StartUpdateAdvertisingAndListening should not be called
,# teardown
,2017-07-14 12:44:45 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass an empty parameter to ThaliNotificationServer.start
,ok 840 StartUpdateAdvertisingAndListening should not be called
,# teardown
,2017-07-14 12:44:45 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeacons
,ok 841 no error
,ok 842 should be 200
ok 843 should be equal
,ok 844 should be equal
,ok 845 (unnamed assert)
,ok 846 no error
,ok 847 should be 204
,# teardown
,2017-07-14 12:44:46 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeacons (no keys)
,ok 848 error should be null
,ok 849 should be 204
,# teardown
,2017-07-14 12:44:46 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeaconsbefore calling start
,ok 850 should be 404
# teardown
,2017-07-14 12:44:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure peerDictionaryKey is reasonable
,ok 851 equal keys
,ok 852 not equal connection type
,ok 853 same connection type, different buffer
,# teardown
,# setup
,# Make sure start works
,2017-07-14 12:44:47 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,ok 854 First start and on called correctly
,# teardown
,# setup
,# Make sure stop works
,ok 855 second cleared dictionary
2017-07-14 12:44:48 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 856 First start and on called correctly
,ok 857 First stop and removeListener called correctly
ok 858 first action kill called
,ok 859 second action kill called
ok 860 first cleared dictionary
,ok 861 first cleared pool
,ok 862 second cleared dictionary
,ok 863 second cleared pool
,# teardown
,# setup
,# Emits error event when peerPool.enqueue throws
,ok 864 Correct error
,# teardown
,# setup
,# Simple peer event
,2017-07-14 12:44:49 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 865 listener has been set
,ok 866 peer dictionary has expected number of entries
,ok 867 Dictionary and pool have same action
,ok 868 ads match
,ok 869 PouchDB matches
,ok 870 DB Names match
,ok 871 public keys match
,ok 872 peer dictionary has expected number of entries
,ok 873 Dictionary and pool have same action
,ok 874 ads match
,ok 875 PouchDB matches
,ok 876 DB Names match
,ok 877 public keys match
,2017-07-14 12:44:49 - DEBUG thaliReplicationPeerAction: 'We called _complete with  and it caused us to complete'
,ok 878 start called once
,ok 879 One entry left
,ok 880 Dictionary and pool have same action
,ok 881 Start never called
,ok 882 Kill called once
,ok 883 no entries left
,ok 884 Third action is dead
,ok 885 peer dictionary has expected number of entries
,ok 886 Dictionary and pool have same action
,ok 887 ads match
,ok 888 PouchDB matches
,ok 889 DB Names match
,ok 890 public keys match
,# teardown
,# setup
,# Coordinated pull replication from notification test
,2017-07-14 12:44:49 - DEBUG CoordinatedClient: 'test was skipped, name: 'Coordinated pull replication from notification test''
,# teardown
,# setup
,# Server is not there
,2017-07-14 12:44:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 12:44:50 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 connect ECONNREFUSED'
,2017-07-14 12:44:50 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: connect ECONNREFUSED  and it caused us to complete'
,ok 891 right error
,# teardown
,2017-07-14 12:44:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server accepts & closes connection
,2017-07-14 12:44:50 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 socket hang up'
,2017-07-14 12:44:50 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: socket hang up  and it caused us to complete'
,ok 892 right error
,# teardown
,2017-07-14 12:44:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 500
,2017-07-14 12:44:51 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 changes rejected'
,2017-07-14 12:44:51 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 893 Got error as expected
,# teardown
,2017-07-14 12:44:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 401
,2017-07-14 12:44:51 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  401 changes rejected'
,2017-07-14 12:44:51 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 894 Got error as expected
,# teardown
,2017-07-14 12:44:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 403
,2017-07-14 12:44:52 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  403 changes rejected'
,2017-07-14 12:44:52 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 895 Got error as expected
,# teardown
,2017-07-14 12:44:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure docs replicate with remote db with same name as local db
,2017-07-14 12:44:53 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-14 12:44:53 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-14 12:44:56 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
,ok 896 should be equal
ok 897 All tests passed!
,# teardown
,2017-07-14 12:44:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure docs replicate with remote db with different name than local db
,2017-07-14 12:44:59 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-14 12:45:00 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-14 12:45:02 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
,ok 898 should be equal
ok 899 All tests passed!
,# teardown
,2017-07-14 12:45:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Do nothing and make sure we time out
,2017-07-14 12:45:04 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-14 12:45:05 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2017-07-14 12:45:05 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
ok 900 action should be killed
ok 901 Error should be timed out
,ok 902 No doc found
,# teardown
,2017-07-14 12:45:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Do something and make sure we time out
,2017-07-14 12:45:07 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-14 12:45:07 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,ok 903 should be equal
,2017-07-14 12:45:09 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2017-07-14 12:45:09 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and s,o we ignored it'
,ok 904 action should be killed
ok 905 Error should be timed out
,# teardown
,2017-07-14 12:45:11 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Start replicating and then catch error when server goes
,ok 906 socket hung up
,# teardown
,2017-07-14 12:45:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure clone works
,ok 907 same getPeerAdvertisesDataForUs
ok 908 Same pouchdB
ok 909 same localDbName
ok 910 Same public key
,# teardown
,# setup
,# Coordinated replication action test - each device has the same local db name
,2017-07-14 12:45:13 - DEBUG CoordinatedClient: 'test was skipped, name: 'Coordinated replication action test - each device has the same local db name''
,# teardown
,# setup
,# Coordinated replication action test - each device has different local db name
,2017-07-14 12:45:14 - DEBUG thaliMobileNativeWrapper: 'listening 50784'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
[ThaliCore] Browser.startListening
,2017-07-14 12:45:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "9AD30652-AF46-462F-A2F8-6E33AB8997AB", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:9AD30652-AF46-462F-A2F8-6E33AB8997AB
,2017-07-14 12:45:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E2889C1F-9781-47EB-A87E-5FA42585CC92", generation: 0)
,2017-07-14 12:45:15 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"E2889C1F-9781-47EB-A87E-5FA42585CC92","generation":0}]'
,2017-07-14 12:45:15 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"E2889C1F-9781-47EB-A87E-5FA42585CC92","generation":0}'
,2017-07-14 12:45:15 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"E2889C1F-9781-47EB-A87E-5FA42585CC92","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 12:45:15 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"E2889C1F-9781-47EB-A87E-5FA42585CC92","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-14 12:45:15 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for E2889C1F-9781-47EB-A87E-5FA42585CC92 (syncValue: 3)'
,2017-07-14 12:45:15 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "E2889C1F-9781-47EB-A87E-5FA42585CC92", generation: 0) new relay
[ThaliCore] Browser.inviteToCo,nnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E2889C1F-9781-47EB-A87E-5FA42585CC92", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
[ThaliCore] BrowserRelay.ini,t(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F31DA80D-5F19-4969-9F65-323952DF140D:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F31DA80D-5F19-4969-9F65-323952DF140D", generation: 0)
,2017-07-14 12:45:15 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"F31DA80D-5F19-4969-9F65-323952DF140D","generation":0}]'
,2017-07-14 12:45:15 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"F31DA80D-5F19-4969-9F65-323952DF140D","generation":0}'
,2017-07-14 12:45:15 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"F31DA80D-5F19-4969-9F65-323952DF140D","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 12:45:15 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"F31DA80D-5F19-4969-9F65-323952DF140D","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
[ThaliCore] Session.in,it(session:identifier:connected:notConnected:) peer:E545EC0D-0ABE-4423-B60C-2395509F5937
[ThaliCore] Advertiser: session connected Peer(uuid: "9AD30652-AF46-462F-A2F8-6E33AB8997AB", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] T,CPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:E545EC0D-0ABE-4423-B60C-2395509F5937 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:10B0CD6D-69F3-4A6F-93D9-C349008463B8
[ThaliCore] Advertiser: session connected Peer(uuid: "9AD30652-AF46-462F-A2F8-6E33AB8997AB", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:10B0CD6D-69F3-4A6F-93D9-C349008463B8 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9AD30652-AF46-462F-A2F8-6E33AB8997AB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9AD30652-AF46-462F-A2F8-6E33AB8997AB", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:10B0CD6D-69F3-4A6F-93D9-C349008463B8
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:E545EC0D-0ABE-4423-B60C-2395509F5937
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:10B0CD6D-69F3-4A6F-93D9-C349008463B8 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:10B0CD6D-69F3-4A6F-93D9-C349008463B8
[ThaliCore] Session.startOutputStream(with:) peer:10B0CD6D-69F3-4A6F-93D9-C349008463B8
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2,0 [1, 3, 4, 10, 20]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:10B0CD6D-69F3-4A6F-93D9-C349008463B8
[ThaliCore] Session.startOutputStream(with:) peer:10B0CD6D-69F3-4A6F-93D9-C349008463B8
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:21 [1, 3, 4, 10, 20, 21]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:10B0CD6D-69F3-4A6F-93D9-C349008463B8
[ThaliCore] Session.startOutputStream(with:) peer:10B0CD6D-69F3-4A6F-93D9-C349008463B8
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:22 [1, 3, 4, 10, 20, 21, 22]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:10B0CD6D-69F3-4A6F-93D9-C349008463B8
[ThaliCore] Session.startOutputStream(with:) peer:10B0CD6D-69F3-4A6F-93D9-C349008463B8
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2,3 [1, 3, 4, 10, 20, 21, 22, 23]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] Session.session(_:peer:didChange:) peer:E545EC0D-0ABE-4423-B60C-2395509F5937 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "E2889C1F-9781-47EB-A87E-5FA42585CC92", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50791
,2017-07-14 12:45:18 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"3","error":null,"portNumber":50791}'
,2017-07-14 12:45:18 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for E2889C1F-9781-47EB-A87E-5FA42585CC92 (syncValue: 4)'
,2017-07-14 12:45:18 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "E2889C1F-9781-47EB-A87E-5FA42585CC92", generation: 0) found active relay
,2017-07-14 12:45:18 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"4","error":null,"portNumber":50791}'
,2017-07-14 12:45:18 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for E2889C1F-9781-47EB-A87E-5FA42585CC92 (syncValue: 5)'
,2017-07-14 12:45:18 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "E2889C1F-9781-47EB-A87E-5FA42585CC92", generation: 0) found active relay
,2017-07-14 12:45:18 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"5","error":null,"portNumber":50791}'
,2017-07-14 12:45:18 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for E2889C1F-9781-47EB-A87E-5FA42585CC92 (syncValue: 6)'
,2017-07-14 12:45:18 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "E2889C1F-9781-47EB-A87E-5FA42585CC92", generation: 0) found active relay
,2017-07-14 12:45:18 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"6","error":null,"portNumber":50791}'
,2017-07-14 12:45:18 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for F31DA80D-5F19-4969-9F65-323952DF140D (syncValue: 7)'
,2017-07-14 12:45:18 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "F31DA80D-5F19-4969-9F65-323952DF140D", generation: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F31DA80D-5F19-4969-9F65-,323952DF140D", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F31DA80D-5F19-4969-9F65-323952DF140D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[Th,aliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E545EC0D-0ABE-4423-B60C-2395509F5937
[ThaliCore] Session.startOutputStream(with:) peer:E545EC0D-0ABE-4423-B60C-2395509F5937
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:24 [1, 3, 4, 10, 20, 21, 22, 23, 24]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:25 [1, 3, 4, 10, 20, 21, 22, 23, 24, 25]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E545EC0D-0ABE-4423-B60C-2395509F5937
[ThaliCore] Session.startOutputStream(with:) peer:E545EC0D-0ABE-4423-B60C-2395509F5937
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:26 [1, 3, 4, 10, 20, 21, 22, 23, 24, 25, 26]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E545EC0D-0ABE-4423-B60C-2395509F5937
[ThaliCore] Session.startOutputStream(with:) peer:E545EC0D-0ABE-4423-B60C-2395509F5937
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:27 [1, 3, 4, 10, 20, 21, 22, 23, 24, 25, 26, 27]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E545EC0D-0ABE-4423-B60C-2395509F5937
[ThaliCore] Session.startOutputStream(with:) peer:E545EC0D-0ABE-4423-B60C-2395509F5937
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:28 [1, 3, 4, 10, 20, 21, 22, 23, 24, 25, 26, 27, 28]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:29 [1, 3, 4, 10, 20, 21, 22, 23, 24, 25, 26, 27, 28, 29]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:30 [1, 3, 4, 10, 20, 21, 22, 23, 24, 25, 26, 27, 28, 29, 30]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:31 [1, 3, 4, 10, 20, 21, 22, 23, 24, 25, 26, 27, 28, 29, 30, 31]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:25
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:25
[ThaliCore] VirtualSocket.deinit vsID:25 [1, 3, 4, 10, 20, 21, 22, 23, 24, 26, 27, 28, 29, 30, 31]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:26
[ThaliCore] VirtualSocket.closeStreams() vsID:26
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:24
[ThaliCore] VirtualSocket.closeStreams() vsID:24
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:26
[ThaliCore] VirtualSocket.deinit vsID:26 [1, 3, 4, 10, 20, 21, 22, 23, 24, 27, 28, 29, 30, 31]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket, exited RunLoop vsID:24
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] VirtualSocket.deinit vsID:24 [1, 3, 4, 10, 20, 21, 22, 23, 27, 28, 29, 30, 31]
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconn,ecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:28
[ThaliCore] VirtualSocket.closeStreams() vsID:28
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:27
[ThaliCore] VirtualSocket.closeStreams() vsID:27
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:28
[ThaliCore] VirtualSocket.deinit vsID:28 [1, 3, 4, 10, 20, 21, 22, 23, 27, 29, 30, 31]
[ThaliCore] TCPClient.socketDidDi,sconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:27
[ThaliCore] VirtualSocket.deinit vsID:27 [1, 3, 4, 10, 20, 21, 22, 23, 29, 30, 31]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:29
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:29
[ThaliCore] VirtualSocket.deinit vsID:29 [1, 3, 4, 10, 20, 21, 22, 23, 30, 31]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:30
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E545EC0D-0ABE-4423-B60C-2395509F5937
[ThaliCore] Session.startOutputStream(with:) peer:E545EC0D-0ABE-4423-B60C-2395509F5937
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3,2 [1, 3, 4, 10, 20, 21, 22, 23, 30, 31, 32]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:30
[ThaliCore] VirtualSocket.deinit vsID:30 [1, 3, 4, 10, 20, 21, 22, 23, 31, 32]
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:31
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:31
[ThaliCore] VirtualSocket.deinit vsID:31 [1, 3, 4, 10, 20, 21, 22, 23, 32]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:33 [1, 3, 4, 10, 20, 21, 22, 23, 32, 33]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:peer:didChange:) peer:F31DA80D-5F19-4969-9F65-323952DF140D:0 state: notConnected -> connecting
2017-07-14 12:45:18 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E545EC0D-0ABE-4423-B60C-2395509F5937
[ThaliCore] Session.startOutputStream(with:) peer:E545EC0D-0ABE-4423-B60C-2395509F5937
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:34 [1, 3, 4, 10, 20, 21, 22, 23, 32, 33, 34]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:21
[ThaliCore] VirtualSocket.closeStreams() vsID:21
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:21
[ThaliCore] VirtualSocket.deinit vsID:21 [1, 3, 4, 10, 20, 22, 23, 32, 33, 34]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:20
[ThaliCore] VirtualSocket.closeStreams() vsID:20
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:,20
[ThaliCore] VirtualSocket.deinit vsID:20 [1, 3, 4, 10, 22, 23, 32, 33, 34]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:22
[ThaliCore] VirtualSocket.closeStreams() vsID:22
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:35 [1, 3, 4, 10, 22, 23, 32, 33, 34, 35]
[ThaliCore] BrowserRelay.didOpenVirtualSocket,StreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:23
[ThaliCore] VirtualSocket.closeStreams() vsID:23
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:23
[ThaliCore] VirtualSocket.deinit vsID:23 [1, 3, 4, 10, 22, 32, 33, 34, 35]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[Thal,iCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:10B0CD6D-69F3-4A6F-93D9-C349008463B8
[ThaliCore] Session.startOutputStream(with:) peer:10B0CD6D-69F3-4A6F-93D9-C349008463B8
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:36 [1, 3, 4, 10, 22, 32, 33, 34, 35, 36]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0E72115A-8DB3-42E8-94B5-C3755B9B7A1B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0E72115A-8DB3-42E8-94B5-C3755B9B7A1B", generation: 0)
,2017-07-14 12:45:18 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"0E72115A-8DB3-42E8-94B5-C3755B9B7A1B","generation":0}]'
,2017-07-14 12:45:18 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"0E72115A-8DB3-42E8-94B5-C3755B9B7A1B","generation":0}'
,2017-07-14 12:45:18 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"0E72115A-8DB3-42E8-94B5-C3755B9B7A1B","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 12:45:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"0E72115A-8DB3-42E8-94B5-C3755B9B7A1B","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:10B0CD6D-69F3-4A6F-93D9-C349008463B8
[ThaliCore] Session.startOutputStream(with:) peer:10B0CD6D-69F3-4A6F-93D9-C349008463B8
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:37 [1, 3, 4, 10, 22, 32, 33, 34, 35, 36, 37]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:38 [1, 3, 4, 10, 22, 32, 33, 34, 35, 36, 37, 38]
[ThaliCore] BrowserRelay.didOpenVirtu,alSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E545EC0D-0ABE-4423-B60C-2395509F5937
[ThaliCore] Session.startOutputStream(with:) peer:E545EC0D-0ABE-4423-B60C-2395509F5937
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:39 [1, 3, 4, 10, 22, 32, 33, 34, 35, 36, 37, 38, 39]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:10B0CD6D-69F3-4A6F-93D9-C349008463B8
[ThaliCore] Session.startOutputStream(with:) peer:10B0CD6D-69F3-4A6F-93D9-C349008463B8
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:40 [1, 3, 4, 10, 22, 32, 33, 34, 35, 36, 37, 38, 39, 40]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E545EC0D-0ABE-4423-B60C-2395509F5937
,[ThaliCore] Session.startOutputStream(with:) peer:E545EC0D-0ABE-4423-B60C-2395509F5937
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:41 [1, 3, 4, 10, 22, 32, 33, 34, 35, 36, 37, 38, 39, 40, 41]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:42 [1, 3, 4, 10, 22, 32, 33, 34, 35, 36, 37, 38, 39, 40, 41, 42]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:43 [1, 3, 4, 10, 22, 32, 33, 34, 35, 36, 37, 38, 39, 40, 41, 42, 43]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E545EC0D-0ABE-4423-B60C-2395509F5937
[ThaliCore] Session.startOutputStream(with:) peer:E545EC0D-0ABE-4423-B60C-2395509F5937
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:44 [1, 3, 4, 10, 22, 32, 33, 34, 35, 36, 37, 38, 39, 40, 41, 42, 43, 44]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vs,ID:42
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:42
,[ThaliCore] VirtualSocket.deinit vsID:42 [1, 3, 4, 10, 22, 32, 33, 34, 35, 36, 37, 38, 39, 40, 41, 43, 44]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:10B0CD6D-69F3-4A6F-93D9-C349008463B8
[ThaliCore] Session.startOutputStream(with:) peer:10B0CD6D-69F3-4A6F-93D9-C349008463B8
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:45 [1, 3, 4, 10, 22, 32, 33, 34, 35, 36, 37, 38, 39, 40, 41, 43, 44, 45]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:46 [1, 3, 4, 10, 22, 32, 33, 34, 35, 36, 37, 38, 39, 40, 41, 43, 44, 45, 46]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:10B0CD6D-69F3-4A6F-93D9-C349008463B8
[ThaliCore] Session.startOutputStream(with:) peer:10B0CD6D-69F3-4A6F-93D9-C349008463B8
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:47 [1, 3, 4, 10, 22, 32, 33, 34, 35, 36, 37, 38, 39, 40, 41, 43, 44, 45, 46, 47]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:41
[ThaliCore] VirtualSocket.closeStreams() vsID:41
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:41
[ThaliCore] VirtualSocket.deinit vsID:41 [1, 3, 4, 10, 22, 32, 33, 34, 35, 36, 37, 38, 39, 40, 43, 44, 45, 46, 47]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:n,il
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-14 12:45:19 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:46
,[ThaliCore] VirtualSocket exited RunLoop vsID:46
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket.deinit vsID:46 [1, 3, 4, 10, 22, 32, 33, 34, 35, 36, 37, 38, 39, 40, 43, 44, 45, 47]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:45
[ThaliCore] VirtualSocket.closeStreams() vsID:45
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:45
[ThaliCore] VirtualSocket.deinit vsID:45 [1, 3, 4, 10, 22, 32, 33, 34, 35, 36, 37, 38, 39, 40, 43, 44, 47]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[Tha,liCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:10B0CD6D-69F3-4A6F-93D9-C349008463B8
[ThaliCore] Session.startOutputStream(with:) peer:10B0CD6D-69F3-4A6F-93D9-C349008463B8
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:48 [1, 3, 4, 10, 22, 32, 33, 34, 35, 36, 37, 38, 39, 40, 43, 44, 47, 48]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E545EC0D-0ABE-4423-B60C-2395509F5937
[ThaliCore] Session.startOutputStream(with:) peer:E545EC0D-0ABE-4423-B60C-2395509F5937
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:49 [1, 3, 4, 10, 22, 32, 33, 34, 35, 36, 37, 38, 39, 40, 43, 44, 47, 48, 49]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:48
[ThaliCore] VirtualSocket.closeStreams() vsID:48
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:48
[ThaliCore] VirtualSocket.deinit vsID:48 [1, 3, 4, 10, 22, 32, 33, 34, 35, 36, 37, 38, 39, 40, 43, 44, 47, 49]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:49
[ThaliCore] VirtualSocket.closeStreams() vsID:49
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:49
[ThaliCore] VirtualSocket.deinit vsID:49 [1, 3, 4, 10, 22, 32, 33, 34, 35, 36, 37, 38, 39, 40, 43, 44, 47]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[Tha,liCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:10B0CD6D-69F3-4A6F-93D9-C349008463B8
[ThaliCore] Session.startOutputStream(with:) peer:10B0CD6D-69F3-4A6F-93D9-C349008463B8
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:50 [1, 3, 4, 10, 22, 32, 33, 34, 35, 36, 37, 38, 39, 40, 43, 44, 47, 50]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:47
[ThaliCore] VirtualSocket.closeStreams() vsID:47
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:47
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] VirtualSocket.deinit vs,ID:47 [1, 3, 4, 10, 22, 32, 33, 34, 35, 36, 37, 38, 39, 40, 43, 44, 50]
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:10B0CD6D-69F3-4A6F-93D9-C349008463B8
[ThaliCore] Session.startOutputStream(with:) peer:10B0CD6D-69F3-4A6F-93D9-C349008463B8
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:51 [1, 3, 4, 10, 22, 32, 33, 34, 35, 36, 37, 38, 39, 40, 43, 44, 50, 51]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:50
[ThaliCore] VirtualSocket.closeStreams() vsID:50
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:50
[ThaliCore] VirtualSocket.deinit vsID:50 [1, 3, 4, 10, 22, 32, 33, 34, 35, 36, 37, 38, 39, 40, 43, 44, 51]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:0E72115A-8DB3-42E8-94B5-C3755B9B7A1B:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "0E72115A-8DB3-42E8-94B5-C3755B9B7A1B", generation: 0)
[ThaliCore] Session.disconnect() peer:0E72115A-8DB,3-42E8-94B5-C3755B9B7A1B:0
2017-07-14 12:45:20 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"0E72115A-8DB3-42E8-94B5-C3755B9B7A1B","generation":0}]'
2017-07-14 12:45:,20 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"0E72115A-8DB3-42E8-94B5-C3755B9B7A1B","generation":0}'
[ThaliCore] Session.session(_:peer:didChange:) peer:0E72115A-8DB3-42E8-94B5,-C3755B9B7A1B:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "0E72115A-8DB3-42E8-94B5-C3755B9B7A1B", generation: 0)
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] TCPListener.stopListening,F,orConnectionsAndDisconnectClients() port:50656
[ThaliCore] Session.disconnect() peer:0E72115A-8DB3-42E8-94B5-C3755B9B7A1B:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "0E72115A-8DB3-42E8-94B5-C3755B9B7A1B", generation: 0)
201,7-07-14 12:45:20 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"0E72115A-8DB3-42E8-94B5-C3755B9B7A1B","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-14 12:45:20 - DEBUG thaliMobile: 'Emitting pe,erAvailabilityChanged from handlePeer {"peerIdentifier":"0E72115A-8DB3-42E8-94B5-C3755B9B7A1B","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-14 12:45:20 - WARN thaliNotificationClient: 'peer is not availab,le'
2017-07-14 12:45:20 - WARN thaliNotificationClient: 'peer is not available'
2017-07-14 12:45:20 - WARN thaliNotificationClient: 'peer is not available'
2017-07-14 12:45:20 - WARN thaliNotificationClient: 'peer is not available'
[ThaliCore] TCPListe,ner.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:F31DA80D-5F19-4969-9F65-323952DF140D:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:F31DA80D-5F19-4969-9F65-323952DF140D:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "F31DA80D-5F19-4969-9F65-323952DF140D", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50822
,2017-07-14 12:45:20 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"7","error":null,"portNumber":50822}'
,2017-07-14 12:45:20 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for F31DA80D-5F19-4969-9F65-323952DF140D (syncValue: 8)'
,2017-07-14 12:45:20 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "F31DA80D-5F19-4969-9F65-323952DF140D", generation: 0) found active relay
,2017-07-14 12:45:20 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"8","error":null,"portNumber":50822}'
,2017-07-14 12:45:20 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for F31DA80D-5F19-4969-9F65-323952DF140D (syncValue: 9)'
,2017-07-14 12:45:20 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "F31DA80D-5F19-4969-9F65-323952DF140D", generation: 0) found active relay
,2017-07-14 12:45:20 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"9","error":null,"portNumber":50822}'
,2017-07-14 12:45:20 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for F31DA80D-5F19-4969-9F65-323952DF140D (syncValue: 10)'
,2017-07-14 12:45:20 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "F31DA80D-5F19-4969-9F65-323952DF140D", generation: 0) found active relay
,2017-07-14 12:45:20 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"10","error":null,"portNumber":50822}'
,2017-07-14 12:45:20 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 0E72115A-8DB3-42E8-94B5-C3755B9B7A1B (syncValue: 11)'
,2017-07-14 12:45:20 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "0E72115A-8DB3-42E8-94B5-C3755B9B7A1B", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "0E72115A-8DB3-42E8-94B5-C3755B9B7A1B", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) error:unavailablePeer
,2017-07-14 12:45:21 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"11","error":"Peer is unavailable","portNumber":null}'
,2017-07-14 12:45:21 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"0E72115A-8DB3-42E8-94B5-C3755B9B7A1B","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-14 12:45:21 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"0E72115A-8DB3-42E8-94B5-C3755B9B7A1B","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-14 12:45:21 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 0E72115A-8DB3-42E8-94B5-C3755B9B7A1B (syncValue: 12)'
,2017-07-14 12:45:21 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "0E72115A-8DB3-42E8-94B5-C3755B9B7A1B", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "0E72115A-8DB3-42E8-94B5-C3755B9B7A1B", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) error:unavailablePeer
,2017-07-14 12:45:21 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"12","error":"Peer is unavailable","portNumber":null}'
,2017-07-14 12:45:21 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"0E72115A-8DB3-42E8-94B5-C3755B9B7A1B","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-14 12:45:21 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"0E72115A-8DB3-42E8-94B5-C3755B9B7A1B","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-14 12:45:21 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 0E72115A-8DB3-42E8-94B5-C3755B9B7A1B (syncValue: 13)'
,2017-07-14 12:45:21 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "0E72115A-8DB3-42E8-94B5-C3755B9B7A1B", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "0E72115A-8DB3-42E8-94B5-C3755B9B7A1B", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) error:unavailablePeer
,2017-07-14 12:45:21 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"13","error":"Peer is unavailable","portNumber":null}'
,2017-07-14 12:45:21 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"0E72115A-8DB3-42E8-94B5-C3755B9B7A1B","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-14 12:45:21 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"0E72115A-8DB3-42E8-94B5-C3755B9B7A1B","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-14 12:45:21 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 0E72115A-8DB3-42E8-94B5-C3755B9B7A1B (syncValue: 14)'
,2017-07-14 12:45:21 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "0E72115A-8DB3-42E8-94B5-C3755B9B7A1B", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "0E72115A-8DB3-42E8-94B5-C3755B9B7A1B", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) error:unavailablePeer
,2017-07-14 12:45:21 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"14","error":"Peer is unavailable","portNumber":null}'
,2017-07-14 12:45:21 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"0E72115A-8DB3-42E8-94B5-C3755B9B7A1B","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-14 12:45:21 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"0E72115A-8DB3-42E8-94B5-C3755B9B7A1B","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-14 12:45:21 - DEBUG thaliPeerPoolDefault: 'Got err   Peer is unavailable'
,2017-07-14 12:45:21 - DEBUG thaliPeerPoolDefault: 'Got err   Peer is unavailable'
,2017-07-14 12:45:21 - DEBUG thaliPeerPoolDefault: 'Got err   Peer is unavailable'
,2017-07-14 12:45:21 - DEBUG thaliPeerPoolDefault: 'Got err   Peer is unavailable'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:F31DA80D-5F19-4969-9F65-323952DF140D:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:F31DA80D-5F19-4969-9F65-323952DF140D:0
,2017-07-14 12:45:21 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"0E72115A-8DB3-42E8-94B5-C3755B9B7A1B","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:F31DA80D-5F19-4969-9F65-323952DF140D:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F31DA80D-5F19-4969-9F65-323952DF140D:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:52 [1, 3, 4, 10, 22, 32, 33, 34, 35, 36, 37, 38, 39, 40, 43, 44, 51, 52]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:F31DA80D-5F19-4969-9F65-323952DF140D:0
,2017-07-14 12:45:21 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"0E72115A-8DB3-42E8-94B5-C3755B9B7A1B","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-14 12:45:21 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"0E72115A-8DB3-42E8-94B5-C3755B9B7A1B","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-14 12:45:21 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"0E72115A-8DB3-42E8-94B5-C3755B9B7A1B","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-14 12:45:21 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"0E72115A-8DB3-42E8-94B5-C3755B9B7A1B","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-14 12:45:21 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"0E72115A-8DB3-42E8-94B5-C3755B9B7A1B","peerAvailable":true,"portNumber":null,"recreated":true}'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F31DA80D-5F19-4969-9F65-323952DF140D:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:53 [1, 3, 4, 10, 22, 32, 33, 34, 35, 36, 37, 38, 39, 40, 43, 44, 51, 52, 53]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-14 12:45:21 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"0E72115A-8DB3-42E8-94B5-C3755B9B7A1B","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-14 12:45:21 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"0E72115A-8DB3-42E8-94B5-C3755B9B7A1B","peerAvailable":true,"portNumber":null,"recreated":true}'
,[ThaliCore] BrowserManager.disconnect peer:0E72115A-8DB3-42E8-94B5-C3755B9B7A1B
,[ThaliCore] BrowserManager.disconnect peer:0E72115A-8DB3-42E8-94B5-C3755B9B7A1B
,[ThaliCore] BrowserManager.disconnect peer:0E72115A-8DB3-42E8-94B5-C3755B9B7A1B
,[ThaliCore] BrowserManager.disconnect peer:0E72115A-8DB3-42E8-94B5-C3755B9B7A1B
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F31DA80D-5F19-4969-9F65-323952DF140D:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:54 [1, 3, 4, 10, 22, 32, 33, 34, 35, 36, 37, 38, 39, 40, 43, 44, 51, 52, 53, 54]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F31DA80D-5F19-4969-9F65-323952DF140D:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:55 [1, 3, 4, 10, 22, 32, 33, 34, 35, 36, 37, 38, 39, 40, 43, 44, 51, 52, 53, 54, 55]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vs,ID:53
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:53
,[ThaliCore] VirtualSocket.deinit vsID:53 [1, 3, 4, 10, 22, 32, 33, 34, 35, 36, 37, 38, 39, 40, 43, 44, 51, 52, 54, 55]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:52
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:52
,[ThaliCore] VirtualSocket.deinit vsID:52 [1, 3, 4, 10, 22, 32, 33, 34, 35, 36, 37, 38, 39, 40, 43, 44, 51, 54, 55]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:55
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:55
,[ThaliCore] VirtualSocket.deinit vsID:55 [1, 3, 4, 10, 22, 32, 33, 34, 35, 36, 37, 38, 39, 40, 43, 44, 51, 54]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vs,ID:54
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:54
,[ThaliCore] VirtualSocket.deinit vsID:54 [1, 3, 4, 10, 22, 32, 33, 34, 35, 36, 37, 38, 39, 40, 43, 44, 51]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:F31DA80D-5F19-4969-9F65-323952DF140D:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F31DA80D-5F19-4969-9F65-323952DF140D:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:56 [1, 3, 4, 10, 22, 32, 33, 34, 35, 36, 37, 38, 39, 40, 43, 44, 51, 56]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-14 12:45:21 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-14 12:45:21 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
,2017-07-14 12:45:21 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vs,ID:33
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:33
,[ThaliCore] VirtualSocket.deinit vsID:33 [1, 3, 4, 10, 22, 32, 34, 35, 36, 37, 38, 39, 40, 43, 44, 51, 56]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
,[ThaliCore] VirtualSocket.closeStreams() vsID:35
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:35
[ThaliCore] VirtualSocket.deinit vsID:35 [1, 3, 4, 10, 22, 32, 34, 36, 37, 38, 39, 40, 43, 44, 51, 56]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vs,ID:38
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:38
,[ThaliCore] VirtualSocket.deinit vsID:38 [1, 3, 4, 10, 22, 32, 34, 36, 37, 39, 40, 43, 44, 51, 56]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
,[ThaliCore] VirtualSocket.closeStreams() vsID:43
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:43
[ThaliCore] VirtualSocket.deinit vsID:43 [1, 3, 4, 10, 22, 32, 34, 36, 37, 39, 40, 44, 51, 56]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:F31DA80D-5F19-4969-9F65-323952DF140D:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F31DA80D-5F19-4969-9F65-323952DF140D:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:57 [1, 3, 4, 10, 22, 32, 34, 36, 37, 39, 40, 44, 51, 56, 57]
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:32
,[ThaliCore] VirtualSocket.closeStreams() vsID:32
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
[ThaliCore] VirtualSocket exited RunLoop vsID:32
,[ThaliCore] VirtualSocket.deinit vsID:32 [1, 3, 4, 10, 22, 34, 36, 37, 39, 40, 44, 51, 56, 57]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:34
[ThaliCore] VirtualSocket.closeStreams() vsID:34
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:34
[ThaliCore] VirtualSocket.deinit vsID:34 [1, 3, 4, 10, 22, 36, 37, 39, 40, 44, 51, 56, 57]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:39
[ThaliCore] VirtualSocket.closeStreams() vsID:39
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:39
[ThaliCore] VirtualSocket.deinit vsID:39 [1, 3, 4, 10, 22, 36, 37, 40, 44, 51, 56, 57]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:44
[ThaliCore] VirtualSocket.closeStreams() vsID:44
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:44
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] VirtualSocket.deinit vsID:44 [1, 3, 4, 10, 22, 36, 37, 40, 51, 56, 57]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:F31DA80D-5F19-4969-9F65-323952DF140D:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F31DA80D-5F19-4969-9F65-323952DF140D:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:58 [1, 3, 4, 10, 22, 36, 37, 40, 51, 56, 57, 58]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:F31DA80D-5F19-4969-9F65-323952DF140D:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F31DA80D-5F19-4969-9F65-323952DF140D:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:59 [1, 3, 4, 10, 22, 36, 37, 40, 51, 56, 57, 58, 59]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:10B0CD6D-69F3-4A6F-93D9-C349008463B8
[ThaliCore] Session.startOutputStream(with:) peer:10B0CD6D-69F3-4A6F-93D9-C349008463B8
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6,0 [1, 3, 4, 10, 22, 36, 37, 40, 51, 56, 57, 58, 59, 60]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(wi,th:) peer:F31DA80D-5F19-4969-9F65-323952DF140D:0
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F31DA80D-5F19-4969-9F65-323952DF140D:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:61 [1, 3, 4, 10, 22, 36, 37, 40, 51, 56, 57, 58, 59, 60, 61]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:60
[ThaliCore] VirtualSocket.closeStreams() vsID:60
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:60
[ThaliCore] VirtualSocket.deinit vsID:60 [1, 3, 4, 10, 22, 36, 37, 40, 51, 56, 57, 58, 59, 61]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:59
[ThaliCore] Browse,rRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:59
[ThaliCore] VirtualSocket.deinit vsID:59 [1, 3, 4, 10, 22, 36, 37, 40, 51, 56, 57, 58, 61]
,2017-07-14 12:45:22 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:36
[ThaliCore] VirtualSocket.closeStreams() vsID:36
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:36
[ThaliCore] VirtualSocket.deinit vsID:36 [1, 3, 4, 10, 22, 37, 40, 51, 56, 57, 58, 61]
[ThaliCore] TCPClient.socketDidDi,sconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket.handleEventOnInp,utStream endEncountered vsID:37
[ThaliCore] VirtualSocket.closeStreams() vsID:37
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:37
[ThaliCore] VirtualSocket.deinit vsID:,37 [1, 3, 4, 10, 22, 40, 51, 56, 57, 58, 61]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketD,i,sconnectHandler disconnecting:false
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:40
[ThaliCore] VirtualSocket.closeStreams() vsID:40
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCor,e] VirtualSocket.handleEventOnInputStream endEncountered vsID:51
[ThaliCore] VirtualSocket.closeStreams() vsID:51
[ThaliCore] VirtualSocket exited RunLoop vsID:40
[ThaliCore] VirtualSocket.deinit vsID:40 [1, 3, 4, 10, 22, 51, 56, 57, 58, 61]
[ThaliCore,] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] Adverti,serRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:51
[ThaliCore] VirtualSocket.deinit vsID:51 [1, 3, 4, 10, 22, 56, 57, 58, 61]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconn,e,cting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-14 12:45:23 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vs,ID:56
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:56
[ThaliCore] VirtualSocket.deinit vsID:56 [1, 3, 4, 10, 22, 57, 58, 61]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:57
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:57
,[ThaliCore] VirtualSocket.deinit vsID:57 [1, 3, 4, 10, 22, 58, 61]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:58
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:58
[ThaliCore] VirtualSocket.deinit vsID:58 [1, 3, 4, 10, 22, 61]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
,[ThaliCore] VirtualSocket.closeStreams() vsID:61
,[ThaliCore] VirtualSocket exited RunLoop vsID:61
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket.deinit vsID:61 [1, 3, 4, 10, 22]
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
2017-07-14 12:45:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 12:45:23 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"E2889C1F-9781-47EB-A87E-5FA42585CC92","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-14, 12:45:23 - WARN thaliNotificationClient: 'peer is not available'
2017-07-14 12:45:23 - WARN thaliNotificationClient: 'peer is not available'
2017-07-14 12:45:23 - WARN thaliNotificationClient: 'peer is not available'
2017-07-14 12:45:23 - DEBUG thaliMo,bile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"F31DA80D-5F19-4969-9F65-323952DF140D","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-14 12:45:23 - WARN thaliNotificationC,lient: 'peer is not available'
2017-07-14 12:45:23 - WARN thaliNotificationClient: 'peer is not available'
2017-07-14 12:45:23 - WARN thaliNotificationClient: 'peer is not available'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-14 12:45:23 ,- DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-14 12:45:23 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with t,arget ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
2017-07-14 12:45:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListen,ingForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-14 12:45:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:45:23 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-14 12:45:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 911 passed
,# teardown
,# setup
,# Coordinated replication action test - should throw error when wrong remote db name is provided
,2017-07-14 12:45:24 - DEBUG thaliMobileNativeWrapper: 'listening 50833'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D04E2705-213F-47BC-B6DE-BDE92F4BFA0D
[ThaliCore] Browser.startListening
,2017-07-14 12:45:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "DD9A9580-4877-495F-9C40-3FEB21F0DA73", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:DD9A9580-4877-495F-9C40-3FEB21F0DA73
,2017-07-14 12:45:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E2889C1F-9781-47EB-A87E-5FA42585CC92", generation: 0)
2017-07-14 12:45:24 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"E2889C1F-9781-47EB-A87E-5FA42585CC92","generation":0}]'
2017-07-14 12:45:24 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"E2889C1F-9781-47EB-A87E-5FA42585CC92","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F31DA80D-5F19-4969-9F65-323952DF140D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F31DA80D-5F19-4969-9F65-323952DF140D", generation: 0)
,2017-07-14 12:45:24 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"E2889C1F-9781-47EB-A87E-5FA42585CC92","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 12:45:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"E2889C1F-9781-47EB-A87E-5FA42585CC92","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-14 12:45:24 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for E2889C1F-9781-47EB-A87E-5FA42585CC92 (syncValue: 15)'
,2017-07-14 12:45:24 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "E2889C1F-9781-47EB-A87E-5FA42585CC92", generation: 0) found active relay
,2017-07-14 12:45:24 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"15","error":null,"portNumber":50791}'
,2017-07-14 12:45:24 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for E2889C1F-9781-47EB-A87E-5FA42585CC92 (syncValue: 16)'
,2017-07-14 12:45:24 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "E2889C1F-9781-47EB-A87E-5FA42585CC92", generation: 0) found active relay
,2017-07-14 12:45:24 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"16","error":null,"portNumber":50791}'
,2017-07-14 12:45:24 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for E2889C1F-9781-47EB-A87E-5FA42585CC92 (syncValue: 17)'
,2017-07-14 12:45:24 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "E2889C1F-9781-47EB-A87E-5FA42585CC92", generation: 0) found active relay
,2017-07-14 12:45:24 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"17","error":null,"portNumber":50791}'
,2017-07-14 12:45:24 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for E2889C1F-9781-47EB-A87E-5FA42585CC92 (syncValue: 18)'
,2017-07-14 12:45:24 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "E2889C1F-9781-47EB-A87E-5FA42585CC92", generation: 0) found active relay
,2017-07-14 12:45:24 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"18","error":null,"portNumber":50791}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:62 [1, 3, 4, 10, 22, 62]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:63 [1, 3, 4, 10, 22, 62, 63]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:62
[ThaliCore] VirtualSocket.closeStreams() vsID:62
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:62
[ThaliCore] VirtualSocket.deinit vsID:62 [1, 3, 4, 10, 22, 63]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) ac,cepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:64 [1, 3, 4, 10, 22, 63, 64]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandl,er
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:63
[ThaliCore] VirtualSocket.closeStreams() vsID:63
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:63
,[ThaliCore] VirtualSocket.deinit vsID:63 [1, 3, 4, 10, 22, 64]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:64
[ThaliCore] VirtualSocket.closeStreams() vsID:64
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:65 [1, 3, 4, 10, 22, 64, 65]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:65
[ThaliCore] VirtualSocket.closeStreams() vsID:65
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:65
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] VirtualSocket.deinit vsID:,65 [1, 3, 4, 10, 22, 64]
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-14 12:45:24 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"F31DA80D-5F19-4969-9F65-323952DF140D","generation":0}]'
,2017-07-14 12:45:24 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"F31DA80D-5F19-4969-9F65-323952DF140D","generation":0}'
,2017-07-14 12:45:24 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"F31DA80D-5F19-4969-9F65-323952DF140D","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 12:45:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"F31DA80D-5F19-4969-9F65-323952DF140D","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-14 12:45:24 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for F31DA80D-5F19-4969-9F65-323952DF140D (syncValue: 19)'
,2017-07-14 12:45:24 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "F31DA80D-5F19-4969-9F65-323952DF140D", generation: 0) found active relay
,2017-07-14 12:45:24 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"19","error":null,"portNumber":50822}'
,2017-07-14 12:45:24 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for F31DA80D-5F19-4969-9F65-323952DF140D (syncValue: 20)'
,2017-07-14 12:45:24 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "F31DA80D-5F19-4969-9F65-323952DF140D", generation: 0) found active relay
,2017-07-14 12:45:24 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"20","error":null,"portNumber":50822}'
,2017-07-14 12:45:24 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for F31DA80D-5F19-4969-9F65-323952DF140D (syncValue: 21)'
,2017-07-14 12:45:24 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "F31DA80D-5F19-4969-9F65-323952DF140D", generation: 0) found active relay
,2017-07-14 12:45:24 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"21","error":null,"portNumber":50822}'
,2017-07-14 12:45:24 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for F31DA80D-5F19-4969-9F65-323952DF140D (syncValue: 22)'
,2017-07-14 12:45:24 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "F31DA80D-5F19-4969-9F65-323952DF140D", generation: 0) found active relay
,2017-07-14 12:45:24 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"22","error":null,"portNumber":50822}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:F31DA80D-5F19-4969-9F65-323952DF140D:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:F31DA80D-5F19-4969-9F65-323952DF140D:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F31DA80D-5F19-4969-9F65-323952DF140D:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:66 [1, 3, 4, 10, 22, 64, 66]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:F31DA80D-5F19-4969-9F65-323952DF140D:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F31DA80D-5F19-4969-9F65-323952DF140D:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:67 [1, 3, 4, 10, 22, 64, 66, 67]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:66
[ThaliCore] VirtualSocket.closeStreams() vsID:66
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:66
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] VirtualSocket.deinit vsID:6,6 [1, 3, 4, 10, 22, 64, 67]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:F31DA80D-5F19-4969-9F65-323952DF140D:0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:67
[ThaliCore] VirtualSocket.closeStreams() vsID:67
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:67
[ThaliCore] VirtualSocket.deinit vsID:67 [1, 3, 4, 10, 22, 64]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) ac,cepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F31DA80D-5F19-4969-9F65-323952DF140D:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:68 [1, 3, 4, 10, 22, 64, 68]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-14 12:45:24 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:68
[ThaliCore] VirtualSocket.closeStreams() vsID:68
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F31DA80D-5F19-4969-9F65-323952DF140D:0
[ThaliCore] VirtualSocket exited RunLoop vsID:68
[ThaliCore] Virtua,lSocket.init(inputStream:outputStream:) vsID:69 [1, 3, 4, 10, 22, 64, 68, 69]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCor,e] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] VirtualSocket.deinit vsID:68 [1, 3, 4, 10, 22, 64, 69]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-14 12:45:24 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:69
[ThaliCore] VirtualSocket.closeStreams() vsID:69
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:69
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] VirtualSocket.deinit vsID:69 [1, 3, 4, 10, 22, 64]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:), socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-14 12:45:24 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,2017-07-14 12:45:24 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,2017-07-14 12:45:24 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,2017-07-14 12:45:24 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,2017-07-14 12:45:24 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,2017-07-14 12:45:24 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,2017-07-14 12:45:25 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for E2889C1F-9781-47EB-A87E-5FA42585CC92 (syncValue: 23)'
,2017-07-14 12:45:25 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "E2889C1F-9781-47EB-A87E-5FA42585CC92", generation: 0) found active relay
,2017-07-14 12:45:25 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"23","error":null,"portNumber":50791}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
,2017-07-14 12:45:25 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for E2889C1F-9781-47EB-A87E-5FA42585CC92 (syncValue: 24)'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:70 [1, 3, 4, 10, 22, 64, 70]
,2017-07-14 12:45:25 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "E2889C1F-9781-47EB-A87E-5FA42585CC92", generation: 0) found active relay
,2017-07-14 12:45:25 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"24","error":null,"portNumber":50791}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:70
[ThaliCore] VirtualSocket.closeStreams() vsID:70
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:70
,[ThaliCore] VirtualSocket.deinit vsID:70 [1, 3, 4, 10, 22, 64]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:71 [1, 3, 4, 10, 22, 64, 71]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:71
[ThaliCore] VirtualSocket.closeStreams() vsID:71
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:71
,[ThaliCore] VirtualSocket.deinit vsID:71 [1, 3, 4, 10, 22, 64]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-14 12:45:25 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,2017-07-14 12:45:25 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for F31DA80D-5F19-4969-9F65-323952DF140D (syncValue: 25)'
,2017-07-14 12:45:25 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "F31DA80D-5F19-4969-9F65-323952DF140D", generation: 0) found active relay
,2017-07-14 12:45:25 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"25","error":null,"portNumber":50822}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:F31DA80D-5F19-4969-9F65-323952DF140D:0
,2017-07-14 12:45:25 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for E2889C1F-9781-47EB-A87E-5FA42585CC92 (syncValue: 26)'
,2017-07-14 12:45:25 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F31DA80D-5F19-4969-9F65-323952DF140D:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:72 [1, 3, 4, 10, 22, 64, 72]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "E2889C1F-9781-47EB-A87E-5FA42585CC92", generation: 0) found active relay
,2017-07-14 12:45:25 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"26","error":null,"portNumber":50791}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:72
,[ThaliCore] VirtualSocket.closeStreams() vsID:72
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:72
,[ThaliCore] VirtualSocket.deinit vsID:72 [1, 3, 4, 10, 22, 64]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-14 12:45:25 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for F31DA80D-5F19-4969-9F65-323952DF140D (syncValue: 27)'
,2017-07-14 12:45:25 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "F31DA80D-5F19-4969-9F65-323952DF140D", generation: 0) found active relay
,2017-07-14 12:45:25 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"27","error":null,"portNumber":50822}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:F31DA80D-5F19-4969-9F65-323952DF140D:0
,2017-07-14 12:45:25 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for E2889C1F-9781-47EB-A87E-5FA42585CC92 (syncValue: 28)'
,2017-07-14 12:45:25 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "E2889C1F-9781-47EB-A87E-5FA42585CC92", generation: 0) found active relay
,2017-07-14 12:45:25 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"28","error":null,"portNumber":50791}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
,2017-07-14 12:45:25 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for F31DA80D-5F19-4969-9F65-323952DF140D (syncValue: 29)'
,2017-07-14 12:45:25 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "F31DA80D-5F19-4969-9F65-323952DF140D", generation: 0) found active relay
,2017-07-14 12:45:25 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"29","error":null,"portNumber":50822}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:F31DA80D-5F19-4969-9F65-323952DF140D:0
,2017-07-14 12:45:25 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for F31DA80D-5F19-4969-9F65-323952DF140D (syncValue: 30)'
,2017-07-14 12:45:25 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "F31DA80D-5F19-4969-9F65-323952DF140D", generation: 0) found active relay
,2017-07-14 12:45:25 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"30","error":null,"portNumber":50822}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:F31DA80D-5F19-4969-9F65-323952DF140D:0
,2017-07-14 12:45:25 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:73 [1, 3, 4, 10, 22, 64, 73]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-14 12:45:25 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:74 [1, 3, 4, 10, 22, 64, 73, 74]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F31DA80D-5F19-4969-9F65-323952DF140D:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:75 [1, 3, 4, 10, 22, 64, 73, 74, 75]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F31DA80D-5F19-4969-9F65-323952DF140D:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:76 [1, 3, 4, 10, 22, 64, 73, 74, 75, 76]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F31DA80D-5F19-4969-9F65-323952DF140D:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:77 [1, 3, 4, 10, 22, 64, 73, 74, 75, 76, 77]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:73
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:74
,[ThaliCore] VirtualSocket.closeStreams() vsID:73
[ThaliCore] VirtualSocket.closeStreams() vsID:74
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:73
,[ThaliCore] VirtualSocket.deinit vsID:73 [1, 3, 4, 10, 22, 64, 74, 75, 76, 77]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] VirtualSocket exited RunLoop vsID:74
,[ThaliCore] VirtualSocket.deinit vsID:74 [1, 3, 4, 10, 22, 64, 75, 76, 77]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:75
[ThaliCore] VirtualSocket.closeStreams() vsID:75
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:76
[ThaliCore] VirtualSocket.closeStreams() vsID:76
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:77
[ThaliCore] VirtualSocket.closeStreams() vsID:77
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[Thali,Core] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] VirtualSocket exited RunLoop vsID:75
[ThaliCore] VirtualSocket.deinit vsID:75 [1, 3, 4, 10, 22, 64, 76, 77]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[T,haliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] VirtualSocket exited RunLoop vsID:76
[ThaliCore] VirtualSocket.deinit vsID:76 [1, 3, 4, 10, 22, 64, 77]
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] VirtualSocket exited RunLoop vsID:77
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] VirtualSocket.deinit vsID:77 [1, 3, 4, 10, 22, 64]
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-14 12:45:25 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,2017-07-14 12:45:25 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,2017-07-14 12:45:25 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,2017-07-14 12:45:25 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,2017-07-14 12:45:25 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E545EC0D-0ABE-4423-B60C-2395509F5937
[ThaliCore] Session.startOutputStream(with:) peer:E545EC0D-0ABE-4423-B60C-2395509F5937
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:78 [1, 3, 4, 10, 22, 64, 78]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=0 "Undefined error: 0" UserInfo={NSLocalizedDescription=Undefined error: 0, NSLocalizedFailureReason=Error in connect() function})
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:78
[ThaliCore] VirtualSocket.closeStreams() vsID:78
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:78
,[ThaliCore] VirtualSocket.deinit vsID:78 [1, 3, 4, 10, 22, 64]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E545EC0D-0ABE-4423-B60C-2395509F5937
[ThaliCore] Session.startOutputStream(with:) peer:E545EC0D-0ABE-4423-B60C-2395509F5937
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:79 [1, 3, 4, 10, 22, 64, 79]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E545EC0D-0ABE-4423-B60C-2395509F5937
[ThaliCo,re] Session.startOutputStream(with:) peer:E545EC0D-0ABE-4423-B60C-2395509F5937
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:80 [1, 3, 4, 10, 22, 64, 79, 80]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E545EC0D-0ABE-4423-B60C-2395509F5937
[ThaliCore] Session.startOutputStream(with:) peer:E545EC0D-0ABE-4423-B60C-2395509F5937
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:81 [1, 3, 4, 10, 22, 64, 79, 80, 81]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=22 "Invalid argument" UserInfo={NSLocalizedDescription=Invalid argument, NSLocalizedFailureReason=Error in connect() func,tion})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:79
[ThaliCore] VirtualSocket.closeStreams() vsID:79
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=2 "No such file or directory" UserIn,fo={NSLocalizedDescription=No such file or directory, NSLocalizedFailureReason=Error in connect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual, socket vsID:80
[ThaliCore] VirtualSocket exited RunLoop vsID:79
,[ThaliCore] VirtualSocket.closeStreams() vsID:80
[ThaliCore] VirtualSocket.deinit vsID:79 [1, 3, 4, 10, 22, 64, 80, 81]
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] TCPClient.socketDidDisconnect(_:withE,rror:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=0 "Undefined error: 0" UserInfo={NSLocalizedDescription=Undefined error: 0, NSLocalizedFailureReason=Error in connect() function})
[ThaliCore] AdvertiserRelay.didSocketD,isconnectHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:80
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:81
[ThaliCore] VirtualSocket.closeStreams() vsID:81
[ThaliCore] VirtualSocket.deini,t vsID:80 [1, 3, 4, 10, 22, 64, 81]
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:81
[ThaliCore] VirtualSocket.deinit vsID:81 [1, 3, 4, 10, 22, 64]
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:430827BD-0DE6-4A3A-9F93-6F3DF46D2E1C
[ThaliCore] Advertiser: session connected Peer(uuid: "DD9A9580-4877-495F-9C40-3FEB21F0DA73", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:430827BD-0DE6-4A3A-9F93-6F3DF46D2E1C state: notConnected -> connecting
[ThaliCore] Session.init(session:identifier:connected:notConnected:,) peer:648234A4-5567-4B77-AEDF-D1DCB6E0B4B6
[ThaliCore] Advertiser: session connected Peer(uuid: "DD9A9580-4877-495F-9C40-3FEB21F0DA73", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:648234A4-5567-4B77-AEDF-D1DCB6E0B4B6 state: notConnected -> connecting
2017-07-14 12:45:25 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for E2889C1F-9781-47EB-A87E-5FA42585CC92 (syncValue: 31)',
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:F31DA80D-5F19-4969-9F65-323952DF140D:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "F31DA80D-5F19-4969-9F65-323952DF140D", generation: 0)
[ThaliCore] Session.disconnect() peer:F31DA80D-5F19-4969-9F65-323952DF140D:0
,2017-07-14 12:45:25 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] Session.session(_:peer:didChange:) peer:F31DA80D-5F19-4969-9F65-323952DF140D:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(u,uid: "F31DA80D-5F19-4969-9F65-323952DF140D", generation: 0)
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50822
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "E2889C1F-9781-47EB-A87E-5FA42585CC92", generation: 0) found active relay
[ThaliCore] Session.disconnect() peer:F31DA80D-5F19-4969-9F65-323952DF140D:0
2017-07-14 12:45:25 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"31","error":null,"portNumber":50791}'
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "F31DA80D-5F19-4969-9F65-323952DF140D", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CBB,F1823-F1CD-4A02-99F5-32B700AE83E7:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CBBF1823-F1CD-4A02-99F5-32B700AE83E7", generation: 0)
,2017-07-14 12:45:25 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for E2889C1F-9781-47EB-A87E-5FA42585CC92 (syncValue: 32)'
,2017-07-14 12:45:25 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "E2889C1F-9781-47EB-A87E-5FA42585CC92", generation: 0) found active relay
2017-07-14 12:45:25 -, DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"32","error":null,"portNumber":50791}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DD9A9580-4877-495F-9C40-3FEB21F0DA73:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DD9A9580-4877-495F-9C40-3FEB21F0DA73", generation: 0)
,2017-07-14 12:45:25 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"F31DA80D-5F19-4969-9F65-323952DF140D","generation":0}]'
,2017-07-14 12:45:25 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"F31DA80D-5F19-4969-9F65-323952DF140D","generation":0}'
,2017-07-14 12:45:25 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"CBBF1823-F1CD-4A02-99F5-32B700AE83E7","generation":0}]'
,2017-07-14 12:45:25 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"CBBF1823-F1CD-4A02-99F5-32B700AE83E7","generation":0}'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
[ThaliCore] Session.startOutputStream(with:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
,2017-07-14 12:45:25 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"F31DA80D-5F19-4969-9F65-323952DF140D","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-14 12:45:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"F31DA80D-5F19-4969-9F65-323952DF140D","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-14 12:45:25 - WARN thaliNotificationClient: 'peer is not available'
,2017-07-14 12:45:25 - WARN thaliNotificationClient: 'peer is not available'
,2017-07-14 12:45:25 - WARN thaliNotificationClient: 'peer is not available'
,2017-07-14 12:45:25 - WARN thaliNotificationClient: 'peer is not available'
,2017-07-14 12:45:25 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"CBBF1823-F1CD-4A02-99F5-32B700AE83E7","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 12:45:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"CBBF1823-F1CD-4A02-99F5-32B700AE83E7","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-14 12:45:25 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for CBBF1823-F1CD-4A02-99F5-32B700AE83E7 (syncValue: 33)'
,2017-07-14 12:45:25 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "CBBF1823-F1CD-4A02-99F5-32B700AE83E7", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CBBF1823-F1CD-4A02-99F5-32B700AE83E7", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:91E9A4F1-A2DD-4788-9B80-C8052C530F87:0
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:82 [1, 3, 4, 10, 22, 64, 82]
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "91E9A4F1-A2DD-4788-9B80-C8052C530F87", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:CBBF1823-F1C,D-4A02-99F5-32B700AE83E7:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:83 [1, 3, 4, 10, 22, 64, 82, 83]
,2017-07-14 12:45:25 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"91E9A4F1-A2DD-4788-9B80-C8052C530F87","generation":0}]'
2017-07-14 12:45:25 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"91E9A4F1-A2DD-4788-9B80-C8052C530F87","generation":0}'
,2017-07-14 12:45:25 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"91E9A4F1-A2DD-4788-9B80-C8052C530F87","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 12:45:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"91E9A4F1-A2DD-4788-9B80-C8052C530F87","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:82
[ThaliCore] VirtualSocket.closeStreams() vsID:82
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:82
[ThaliCore] VirtualSocket.deinit vsID:82 [1, 3, 4, 10, 22, 64, 83]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:83
[ThaliCore] VirtualSocket.closeStreams() vsID:83
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:83
[ThaliCore] VirtualSocket.deinit vsID:83 [1, 3, 4, 10, 22, 64]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-14 12:45:25 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,2017-07-14 12:45:25 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] Session.session(_:peer:didChange:) peer:CBBF1823-F1CD-4A02-99F5-32B700AE83E7:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:648234A4-5567-4B77-AEDF-D1DCB6E0B4B6
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:430827BD-0DE6-4A3A-9F93-6F3DF46D2E1C
,[ThaliCore] Session.session(_:peer:didChange:) peer:648234A4-5567-4B77-AEDF-D1DCB6E0B4B6 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:430827BD-0DE6-4A3A-9F93-6F3DF46D2E1C state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:430827BD-0DE6-4A3A-9F93-6F3DF46D2E1C
[ThaliCore] Session.startOutputStream(with:) peer:430827BD-0DE6-4A3A-9F93-6F3DF46D2E1C
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8,4 [1, 3, 4, 10, 22, 64, 84]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:430827BD-0DE6-4A3A-9F93-6F3DF46D2E1C
[ThaliCore] Session.startOutputStream(with:) peer:430827BD-0DE6-4A3A-9F93-6F3DF46D2E1C
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8,5 [1, 3, 4, 10, 22, 64, 84, 85]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:430827BD-0DE6-4A3A-9F93-6F3DF46D2E1C
[ThaliCore] Session.startOutputStream(with:) peer:430827BD-0DE6-4A3A-9F93-6F3DF46D2E1C
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:86 [1, 3, 4, 10, 22, 64, 84, 85, 86]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:430827BD-0DE6-4A3A-9F93-6F3DF46D2E1C
[ThaliCore] Session.startOutputStream(with:) peer:430827BD-0DE6-4A3A-9F93-6F3DF46D2E1C
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:87 [1, 3, 4, 10, 22, 64, 84, 85, 86, 87]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:648234A4-5567-4B77-AEDF-D1DCB6E0B4B6
[ThaliCore] Session.startOutputStream(with:) peer:648234A4-5567-4B77-AEDF-D1DCB6E0B4B6
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:88 [1, 3, 4, 10, 22, 64, 84, 85, 86, 87, 88]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:CBBF1823-F1CD-4A02-99F5-32B700AE83E7:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:648234A4-5567-4B77-AEDF-D1DCB6E0B4B6
[ThaliCore] Session.startOutputStream(with:) peer:648234A4-5567-4B77-AEDF-D1DCB6E0B4B6
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:89 [1, 3, 4, 10, 22, 64, 84, 85, 86, 87, 88, 89]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:648234A4-5567-4B77-AEDF-D1DCB6E0B4B6
[ThaliCore] Session.session(_:peer:didChange:) peer:CBBF1823-F1CD-4A02-99F5-32B700AE83E7:0 state: connecting -> connected
,[ThaliCore] Session.startOutputStream(with:) peer:648234A4-5567-4B77-AEDF-D1DCB6E0B4B6
,[ThaliCore] Browser: session connected to Peer(uuid: "CBBF1823-F1CD-4A02-99F5-32B700AE83E7", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:90 [1, 3, 4, 10, 22, 64, 84, 85, 86, 87, 88, 89, 90]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50864
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:648234A4-5567-4B77-AEDF-D1DCB6E0B4B6
[ThaliCore] Session.startOutputStream(with:) peer:648234A4-5567-4B77-AEDF-D1DCB6E0B4B6
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9,1 [1, 3, 4, 10, 22, 64, 84, 85, 86, 87, 88, 89, 90, 91]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,2017-07-14 12:45:28 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"33","error":null,"portNumber":50864}'
,2017-07-14 12:45:28 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for CBBF1823-F1CD-4A02-99F5-32B700AE83E7 (syncValue: 34)'
,2017-07-14 12:45:28 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "CBBF1823-F1CD-4A02-99F5-32B700AE83E7", generation: 0) found active relay
,2017-07-14 12:45:28 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"34","error":null,"portNumber":50864}'
,2017-07-14 12:45:28 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for CBBF1823-F1CD-4A02-99F5-32B700AE83E7 (syncValue: 35)'
,2017-07-14 12:45:28 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "CBBF1823-F1CD-4A02-99F5-32B700AE83E7", generation: 0) found active relay
,2017-07-14 12:45:28 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"35","error":null,"portNumber":50864}'
,2017-07-14 12:45:28 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for CBBF1823-F1CD-4A02-99F5-32B700AE83E7 (syncValue: 36)'
,2017-07-14 12:45:28 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "CBBF1823-F1CD-4A02-99F5-32B700AE83E7", generation: 0) found active relay
,2017-07-14 12:45:28 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"36","error":null,"portNumber":50864}'
,2017-07-14 12:45:28 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 91E9A4F1-A2DD-4788-9B80-C8052C530F87 (syncValue: 37)'
,2017-07-14 12:45:28 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "91E9A4F1-A2DD-4788-9B80-C8052C530F87", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "91E9A4F1-A2DD-4788-9B80-C8052C530F87", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:91E9A4F1-A2DD-4788-9B80-C8052C530F87:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:CBBF1823-F1CD-4A02-99F5-32B700AE83E7:0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:CBBF1823-F1CD-4A02-99F5-32B700AE83E7:0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCo,re] Session.startOutputStream(with:) peer:CBBF1823-F1CD-4A02-99F5-32B700AE83E7:0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:CBBF1823-F1CD-4A02-99F5-32B700AE83E7:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:CBBF1823-F1CD-4A02-99F5-32B700AE83E7:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:92 [1, 3, 4, 10, 22, 64, 84, 85, 86, 87, 88, 89, 90, 91, 92]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:CBBF1823-F1CD-4A02-99F5-32B700AE83E7:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:93 [1, 3, 4, 10, 22, 64, 84, 85, 86, 87, 88, 89, 90, 91, 92, 93]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:CBBF1823-F1CD-4A02-99F5-32B700AE83E7:0
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:94 [1, 3, 4, 10, 22, 64, 84, 85, 86, 87, 88, 89, 90, 91, 92, 93, 94]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:CBBF1823-F1CD-4A02-99F5-32B700AE83E7:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:95 [1, 3, 4, 10, 22, 64, 84, 85, 86, 87, 88, 89, 90, 91, 92, 93, 94, 95]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:84
[ThaliCore] VirtualSocket.closeStreams() vsID:84
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:84
,[ThaliCore] VirtualSocket.deinit vsID:84 [1, 3, 4, 10, 22, 64, 85, 86, 87, 88, 89, 90, 91, 92, 93, 94, 95]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:85
[ThaliCore] VirtualSocket.closeStreams() vsID:85
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:85
,[ThaliCore] VirtualSocket.deinit vsID:85 [1, 3, 4, 10, 22, 64, 86, 87, 88, 89, 90, 91, 92, 93, 94, 95]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:86
,[ThaliCore] VirtualSocket.closeStreams() vsID:86
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:86
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] VirtualSocket.deinit vsID:86 [1, 3, 4, 10, 22, 64, 87, 88, 89, 90, 91, 92, 93, 94, 95]
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:87
[ThaliCore] VirtualSocket.closeStreams() vsID:87
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:87
[ThaliCore] VirtualSocket.deinit vsID:87 [1, 3, 4, 10, 22, 64, 88, 89, 90, 91, 92, 93, 94, 95]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:430827BD-0DE6-4A3A-9F93-6F3DF46D2E1C
[ThaliCore] Session.startOutputStream(with:) peer:430827BD-0DE6-4A3A-9F93-6F3DF46D2E1C
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:96 [1, 3, 4, 10, 22, 64, 88, 89, 90, 91, 92, 93, 94, 95, 96]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:95
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:95
,[ThaliCore] VirtualSocket.deinit vsID:95 [1, 3, 4, 10, 22, 64, 88, 89, 90, 91, 92, 93, 94, 96]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:CBBF1823-F1CD-4A02-99F5-32B700AE83E7:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:CBBF1823-F1CD-4A02-99F5-32B700AE83E7:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:97 [1, 3, 4, 10, 22, 64, 88, 89, 90, 91, 92, 93, 94, 96, 97]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:92
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:92
[ThaliCore] VirtualSocket.deinit vsID:92 [1, 3, 4, 10, 22, 64, 88, 89, 90, 91, 93, 94, 96, 97]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vs,ID:93
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:93
[ThaliCore] VirtualSocket.deinit vsID:93 [1, 3, 4, 10, 22, 64, 88, 89, 90, 91, 94, 96, 97]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:94
[ThaliCore] Browse,rRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:94
[ThaliCore] VirtualSocket.deinit vsID:94 [1, 3, 4, 10, 22, 64, 88, 89, 90, 91, 96, 97]
,[ThaliCore] Session.session(_:peer:didChange:) peer:91E9A4F1-A2DD-4788-9B80-C8052C530F87:0 state: notConnected -> connecting
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:88
[ThaliCore] VirtualSocket.closeStreams() vsID:88
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:,88
[ThaliCore] VirtualSocket.deinit vsID:88 [1, 3, 4, 10, 22, 64, 89, 90, 91, 96, 97]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:90
[ThaliCore] VirtualSocket.closeStreams() vsID:90
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:,90
[ThaliCore] VirtualSocket.deinit vsID:90 [1, 3, 4, 10, 22, 64, 89, 91, 96, 97]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:91
[ThaliCore] VirtualSocket.closeStreams() vsID:91
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:,91
[ThaliCore] VirtualSocket.deinit vsID:91 [1, 3, 4, 10, 22, 64, 89, 96, 97]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[Thal,iCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:89
[ThaliCore] VirtualSocket.closeStreams() vsID:89
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:), peer:648234A4-5567-4B77-AEDF-D1DCB6E0B4B6
[ThaliCore] Session.startOutputStream(with:) peer:648234A4-5567-4B77-AEDF-D1DCB6E0B4B6
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket.init(inputStr,eam:outputStream:) vsID:98 [1, 3, 4, 10, 22, 64, 89, 96, 97, 98]
[ThaliCore] VirtualSocket exited RunLoop vsID:89
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] VirtualSocket.deinit vsID:89 [1, 3, 4, 10, 22, 64, 96, 97, 98]
[ThaliCore] T,CPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:96
[ThaliCore] VirtualSocket.closeStreams() vsID:96
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:,96
[ThaliCore] VirtualSocket.deinit vsID:96 [1, 3, 4, 10, 22, 64, 97, 98]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-14 12:45:28 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  404 no_db_file'
,2017-07-14 12:45:28 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: no_db_file  and it caused us to complete'
,ok 912 error should be 'no_db_file'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:97
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:97
[ThaliCore] VirtualSocket.deinit vsID:97 [1, 3, 4, 10, 22, 64, 98]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:98
[ThaliCore] VirtualSocket.closeStreams() vsID:98
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:98
[ThaliCore] VirtualSocket.deinit vsID:98 [1, 3, 4, 10, 22, 64]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:with,Error:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:91E9A4F1-A2DD-4788-9B80-C8052C530F87:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:91E9A4F1-A2DD-4788-9B80-C8052C530F87:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "91E9A4F1-A2DD-4788-9B80-C8052C530F87", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50876
2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"37","error":null,"portNumber":5087,6}'
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 91E9A4F1-A2DD-4788-9B80-C8052C530F87 (syncValue: 38)'
2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPe,er(_:syncValue:completion:) Peer(uuid: "91E9A4F1-A2DD-4788-9B80-C8052C530F87", generation: 0) found active relay
2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"38","error":null,"portNumber":50876}'
2017-07-14 1,2:45:31 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 91E9A4F1-A2DD-4788-9B80-C8052C530F87 (syncValue: 39)'
2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "91E9A4F1-A2DD-4788-9B80-C8052C530F87", generation: 0) found active relay
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"39","error":null,"portNumber":50876}'
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 91E9A4F1-A2DD-4788-9B80-C8052C530F87 (syncValue: 40)'
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "91E9A4F1-A2DD-4788-9B80-C8052C530F87", generation: 0) found active relay
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"40","error":null,"portNumber":50876}'
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for E2889C1F-9781-47EB-A87E-5FA42585CC92 (syncValue: 41)'
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "E2889C1F-9781-47EB-A87E-5FA42585CC92", generation: 0) found active relay
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"41","error":null,"portNumber":50791}'
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for E2889C1F-9781-47EB-A87E-5FA42585CC92 (syncValue: 42)'
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "E2889C1F-9781-47EB-A87E-5FA42585CC92", generation: 0) found active relay
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"42","error":null,"portNumber":50791}'
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for E2889C1F-9781-47EB-A87E-5FA42585CC92 (syncValue: 43)'
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "E2889C1F-9781-47EB-A87E-5FA42585CC92", generation: 0) found active relay
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"43","error":null,"portNumber":50791}'
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for E2889C1F-9781-47EB-A87E-5FA42585CC92 (syncValue: 44)'
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "E2889C1F-9781-47EB-A87E-5FA42585CC92", generation: 0) found active relay
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"44","error":null,"portNumber":50791}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:91E9A4F1-A2DD-4788-9B80-C8052C530F87:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:91E9A4F1-A2DD-4788-9B80-C8052C530F87:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:91E9A4F1-A2DD-4788-9B80-C8052C530F87:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:91E9A4F1-A2DD-4788-9B80-C8052C530F87:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:99 [1, 3, 4, 10, 22, 64, 99]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:91E9A4F1-A2DD-4788-9B80-C8052C530F87:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:91E9A4F1-A2DD-4788-9B80-C8052C530F87:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:100 [1, 3, 4, 10, 22, 64, 99, 100]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStream,sHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:91E9A4F1-A2DD-4788-9B80-C8052C530F87:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:101 [1, 3, 4, 10, 22, 64, 99, 100, 101]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
[ThaliCore] Session.session(_:didReceive:withName:fromPeer,:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:102 [1, 3, 4, 10, 22, 64, 99, 100, 101, 102]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:103 [1, 3, 4, 10, 22, 64, 99, 100, 101, 102, 103]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:102
[ThaliCore] VirtualSocket.closeStreams() vsID:102
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:102
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
,[ThaliCore] VirtualSocket.deinit vsID:102 [1, 3, 4, 10, 22, 64, 99, 100, 101, 103]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:104 [1, 3, 4, 10, 22, 64, 99, 100, 101, 103, 104]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:105 [1, 3, 4, 10, 22, 64, 99, 100, 101, 103, 104, 105]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:103
,[ThaliCore] VirtualSocket.closeStreams() vsID:103
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:103
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] VirtualSocket.deinit vsID:103 [1, 3, 4, 10, 22, 64, 99, 100, 101, 104, 105]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:104
[ThaliCore] VirtualSocket.closeStreams() vsID:104
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:104
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] VirtualSocket.deinit vsID:104 [1, 3, 4, 10, 22, 64, 99, 100, 101, 105]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:105
[ThaliCore] VirtualSocket.closeStreams() vsID:105
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:105
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] VirtualSocket.deinit vsID:105 [1, 3, 4, 10, 22, 64, 99, 100, 101]
,2017-07-14 12:45:31 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:91E9A4F1-A2DD-4788-9B80-C8052C530F87:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:106 [1, 3, 4, 10, 22, 64, 99, 100, 101, 106]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-14 12:45:31 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,2017-07-14 12:45:31 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,2017-07-14 12:45:31 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E545EC0D-0ABE-4423-B60C-2395509F5937
[ThaliCore] Session.startOutputStream(with:) peer:E545EC0D-0ABE-4423-B60C-2395509F5937
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:107 [1, 3, 4, 10, 22, 64, 99, 100, 101, 106, 107]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=48 "Address already in use" UserInfo={NSLocalizedDescription=Address already in use, NSLocalizedFailureReason=Error in connect() function})
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:107
[ThaliCore] VirtualSocket.closeStreams() vsID:107
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:107
[ThaliCore] VirtualSocket.deinit vsID:107 [1, 3, 4, 10, 22, 64, 99, 100, 101, 106]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E545EC0D-0ABE-4423-B60C-2395509F5937
[ThaliCore] Session.startOutputStream(with:) peer:E545EC0D-0ABE-4423-B60C-2395509F5937
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:108 [1, 3, 4, 10, 22, 64, 99, 100, 101, 106, 108]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=0 "Undefined error: 0" UserInfo={NSLocalizedDescription=Undefined error: 0, NSLocalizedFailureReason=Error in connect() f,unction})
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:108
[ThaliCore] VirtualSocket.closeStreams() vsID:108
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:108
[ThaliCore] VirtualSocket.deinit vsID:108 [1, 3, 4, 10, 22, 64, 99, 100, 101, 106]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E545EC0D-0ABE-4423-B60C-2395509F5937
[ThaliCore] Session.startOutputStream(with:) peer:E545EC0D-0ABE-4423-B60C-2395509F5937
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:109 [1, 3, 4, 10, 22, 64, 99, 100, 101, 106, 109]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=48 "Address already in use" UserInfo={NSLocalizedDescription=Address already in use, NSLocalizedFailureReason=Error in connect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:109
[ThaliCore] VirtualSocket.closeStreams() vsID:109
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:109
[ThaliCore] VirtualSocket.deinit vsID:109 [1, 3, 4, 10, 22, 64, 99, 100, 101, 106]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E545EC0D-0ABE-4423-B60C-2395509F5937
[ThaliCore] Session.startOutputStream(with:) peer:E545EC0D-0ABE-4423-B60C-2395509F5937
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:110 [1, 3, 4, 10, 22, 64, 99, 100, 101, 106, 110]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedDescription=Connection refused, NSLocalizedFailureReason=Error in connect() ,function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:110
[ThaliCore] VirtualSocket.closeStreams() vsID:110
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:110
,[ThaliCore] VirtualSocket.deinit vsID:110 [1, 3, 4, 10, 22, 64, 99, 100, 101, 106]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:99
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:99
[ThaliCore] VirtualSocket.deinit vsID:99 [1, 3, 4, 10, 22, 64, 100, 101, 106]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:100
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:100
[ThaliCore] VirtualSocket.deinit vsID:100 [1, 3, 4, 10, 22, 64, 101, 106]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:101
,[ThaliCore] VirtualSocket exited RunLoop vsID:101
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket.deinit vsID:101 [1, 3, 4, 10, 22, 64, 106]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
,[ThaliCore] VirtualSocket.closeStreams() vsID:106
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:106
[ThaliCore] VirtualSocket.deinit vsID:106 [1, 3, 4, 10, 22, 64]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:91E9A4F1-A2DD-4788-9B80-C8052C530F87:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:91E9A4F1-A2DD-4788-9B80-C8052C530F87:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:111 [1, 3, 4, 10, 22, 64, 111]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-14 12:45:31 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  404 no_db_file'
,2017-07-14 12:45:31 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: no_db_file  and it caused us to complete'
,ok 913 error should be 'no_db_file'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
,[ThaliCore] VirtualSocket.closeStreams() vsID:111
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:111
,[ThaliCore] VirtualSocket.deinit vsID:111 [1, 3, 4, 10, 22, 64]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E545EC0D-0ABE-4423-B60C-2395509F5937
[ThaliCore] Session.startOutputStream(with:) peer:E545EC0D-0ABE-4423-B60C-2395509F5937
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:112 [1, 3, 4, 10, 22, 64, 112]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=1 "Operation not permitted" UserInfo={NSLocalizedDescription=Operation not permitted, NSLocalizedFailureReason=Error in c,onnect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:112
[ThaliCore] VirtualSocket.closeStreams() vsID:112
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:112
[ThaliCore] VirtualSocket.deinit vsID:112 [1, 3, 4, 10, 22, 64]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E545EC0D-0ABE-4423-B60C-2395509F5937
[ThaliCore] Session.startOutputStream(with:) peer:E545EC0D-0ABE-4423-B60C-2395509F5937
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:113 [1, 3, 4, 10, 22, 64, 113]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=48 "Address already in use" UserInfo={NSLocalizedDescription=Address already in use, NSLocalizedFailureReason=Error in co,nnect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:113
[ThaliCore] VirtualSocket.closeStreams() vsID:113
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:113
,[ThaliCore] VirtualSocket.deinit vsID:113 [1, 3, 4, 10, 22, 64]
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for E2889C1F-9781-47EB-A87E-5FA42585CC92 (syncValue: 45)'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E545EC0D-0ABE-4423-B60C-2395509F5937
[ThaliCore] Session.startOutputStream(with:) peer:E545EC0D-0ABE-4423-B60C-2395509F5937
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,14 [1, 3, 4, 10, 22, 64, 114]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=70 "Stale NFS file handle" UserInfo={NSLocalizedDescription=Stale NFS file handle, NSLocalizedFailureReason=Error in conn,ect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:114
[ThaliCore] VirtualSocket.closeStreams() vsID:114
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:114
[ThaliCore] VirtualSocket.deinit vsID:114 [1, 3, 4, 10, 22, 64]
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "E2889C1F-9781-47EB-A87E-5FA42585CC92", generation: 0) found active relay
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"45","error":null,"portNumber":50791}'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E545EC0D-0ABE-4423-B60C-2395509F5937
[ThaliCore] Session.startOutputStream(with:) peer:E545EC0D-0ABE-4423-B60C-2395509F5937
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:115 [1, 3, 4, 10, 22, 64, 115]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=2 "No such file or directory" UserInfo={NSLocalizedDescription=No such file or directory, NSLocalizedFailureReason=Error ,in connect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:115
[ThaliCore] VirtualSocket.closeStreams() vsID:115
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:115
[ThaliCore] VirtualSocket.deinit vsID:115 [1, 3, 4, 10, 22, 64]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:116 [1, 3, 4, 10, 22, 64, 116]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:116
[ThaliCore] VirtualSocket.closeStreams() vsID:116
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:116
,[ThaliCore] VirtualSocket.deinit vsID:116 [1, 3, 4, 10, 22, 64]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-14 12:45:31 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for E2889C1F-9781-47EB-A87E-5FA42585CC92 (syncValue: 46)'
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "E2889C1F-9781-47EB-A87E-5FA42585CC92", generation: 0) found active relay
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"46","error":null,"portNumber":50791}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:117 [1, 3, 4, 10, 22, 64, 117]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:117
[ThaliCore] VirtualSocket.closeStreams() vsID:117
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:117
,[ThaliCore] VirtualSocket.deinit vsID:117 [1, 3, 4, 10, 22, 64]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-14 12:45:32 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,2017-07-14 12:45:32 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for E2889C1F-9781-47EB-A87E-5FA42585CC92 (syncValue: 47)'
,2017-07-14 12:45:32 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "E2889C1F-9781-47EB-A87E-5FA42585CC92", generation: 0) found active relay
,2017-07-14 12:45:32 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"47","error":null,"portNumber":50791}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:118 [1, 3, 4, 10, 22, 64, 118]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-14 12:45:32 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for E2889C1F-9781-47EB-A87E-5FA42585CC92 (syncValue: 48)'
,2017-07-14 12:45:32 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "E2889C1F-9781-47EB-A87E-5FA42585CC92", generation: 0) found active relay
,2017-07-14 12:45:32 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"48","error":null,"portNumber":50791}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:119 [1, 3, 4, 10, 22, 64, 118, 119]
[ThaliCore] VirtualSocket.handleEventOnInputStream, endEncountered vsID:118
[ThaliCore] VirtualSocket.closeStreams() vsID:118
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket exited RunLoop vsID:118
[ThaliCore] VirtualSocket.deinit vsID:118 [1, 3, 4, 10, 22, 64, 119]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:with,Error:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-14 12:45:32 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:119
[ThaliCore] VirtualSocket.closeStreams() vsID:119
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:119
,[ThaliCore] VirtualSocket.deinit vsID:119 [1, 3, 4, 10, 22, 64]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-14 12:45:32 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,2017-07-14 12:45:33 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for E2889C1F-9781-47EB-A87E-5FA42585CC92 (syncValue: 49)'
2017-07-14 12:45:33 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "E2889C1F-9781-47EB-A87E-5FA42585CC92", generation: 0) found active relay
2017-07-14 12:45:33 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"49","error":null,"portNumber":50791}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:120 [1, 3, 4, 10, 22, 64, 120]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:120
[ThaliCore] VirtualSocket.closeStreams() vsID:120
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:120
[ThaliCore] VirtualSocket.deinit vsID:120 [1, 3, 4, 10, 22, 64]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-14 12:45:33 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
2017-07-14 12:45:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-14 12:45:3,3 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"E2889C1F-9781-47EB-A87E-5FA42585CC92","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-14 12:45:33 - WARN t,haliNotificationClient: 'peer is not available'
2017-07-14 12:45:33 - WARN thaliNotificationClient: 'peer is not available'
2017-07-14 12:45:33 - WARN thaliNotificationClient: 'peer is not available'
2017-07-14 12:45:33 - DEBUG thaliMobile: 'Emitting pe,erAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"CBBF1823-F1CD-4A02-99F5-32B700AE83E7","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-14 12:45:33 - WARN thaliNotificationClient: 'peer is not available'
2017-07-14 12:45:33 - WARN thaliNotificationClient: 'peer is not available'
2017-07-14 12:45:33 - WARN thaliNotificationClient: 'peer is not available'
2017-07-14 12:45:33 - DEB,UG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"91E9A4F1-A2DD-4788-9B80-C8052C530F87","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-14 12:45:33 - WARN thaliNot,ificationClient: 'peer is not available'
,2017-07-14 12:45:33 - WARN thaliNotificationClient: 'peer is not available'
,2017-07-14 12:45:33 - WARN thaliNotificationClient: 'peer is not available'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 12:45:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 12:45:33 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
,2017-07-14 12:45:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-14 12:45:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:45:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 12:45:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 914 passed
,# teardown
,# setup
,# compareBufferArrays
,ok 915 should throw
,ok 916 should throw
,ok 917 (unnamed assert)
,ok 918 (unnamed assert)
,ok 919 (unnamed assert)
,ok 920 (unnamed assert)
,ok 921 (unnamed assert)
,# teardown
,# setup
,# Call start twice and get error
,ok 922 should throw
,# teardown
,# setup
,# Start and make sure it runs
,# teardown
,# setup
,# Make sure getTimeWhenRun is right after start
,ok 923 (unnamed assert)
,# teardown
,# setup
,# Make sure getTimeWhenRun is -1 after function is called
,ok 924 should be equal
# teardown
,# setup
,# Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running
,ok 925 should be equal
ok 926 should be equal
ok 927 should throw
,# teardown
,# setup
,# Test TransientState
,ok 928 should throw
ok 929 should throw
ok 930 should be equal
ok 931 should be equal
ok 932 should be equal
ok 933 should be equal
ok 934 (unnamed assert)
ok 935 (unnamed assert)
,# teardown
,# setup
,# No peers and empty database
,ok 936 verify failed
,ok 937 constructor called once
,ok 938 constructor called with right args
,ok 939 match start arg
,ok 940 start called once
,ok 941 stop called once
,ok 942 stop after start
,# teardown
,# setup
,# One peer and empty DB
,2017-07-14 12:45:38 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 943 verify failed
,ok 944 constructor called once
,ok 945 constructor called with right args
,ok 946 match start arg
,ok 947 start called once
,ok 948 stop called once
,ok 949 stop after start
,# teardown
,# setup
,# One peer with _Local set behind current seq
,2017-07-14 12:45:40 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 950 verify failed
,ok 951 constructor called once
,ok 952 constructor called with right args
,ok 953 match start arg
,ok 954 start called once
,ok 955 stop called once
,ok 956 stop after start
,# teardown
,# setup
,# One peer with _Local set equal to current seq
,2017-07-14 12:45:41 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 957 verify failed
,ok 958 constructor called once
,ok 959 constructor called with right args
,ok 960 match start arg
,ok 961 start called once
,ok 962 stop called once
,ok 963 stop after start
,# teardown
,# setup
,# One peer with _Local set ahead of current seq (and no this should not happen)
,2017-07-14 12:45:42 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 964 verify failed
,ok 965 constructor called once
,ok 966 constructor called with right args
,ok 967 match start arg
,ok 968 start called once
,ok 969 stop called once
,ok 970 stop after start
,# teardown
,# setup
,# Three peers, one not in DB, one behind and one ahead
,2017-07-14 12:45:42 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 971 verify failed
,ok 972 constructor called once
,ok 973 constructor called with right args
ok 974 match start arg
,ok 975 start called once
ok 976 stop called once
,ok 977 stop after start
,# teardown
,# setup
,# More than maximum peers, make sure we only send maximum allowed
,2017-07-14 12:45:43 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 978 verify failed
,ok 979 constructor called once
,ok 980 constructor called with right args
,ok 981 match start arg
,ok 982 start called once
,ok 983 stop called once
,ok 984 stop after start
,# teardown
,# setup
,# two peers with empty DB, update the doc
,2017-07-14 12:45:43 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,2017-07-14 12:45:43 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 985 verify failed
,ok 986 constructor called once
,ok 987 constructor called with right args
,ok 988 last start before stop
,ok 989 empty first start
,ok 990 full second start
,ok 991 only 2 timers
,# teardown
,# setup
,# add doc and make sure tokens refresh when they expire
,2017-07-14 12:45:44 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,2017-07-14 12:45:44 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,2017-07-14 12:45:44 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
ok 992 verify failed
ok 993 constructor called once
ok 994 constructor called with right args
ok 995 start befor,e stop
ok 996 We got at least 3 calls to start
ok 997 at least 3
ok 998 default 1
ok 999 1 run
,ok 1000 default 2
ok 1001 2 run
ok 1002 default 3
# teardown
,# setup
,# start and stop and start and stop
,ok 1003 start out null
,2017-07-14 12:45:45 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 1004 back to null
,2017-07-14 12:45:45 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 1005 still null
,ok 1006 verify failed
,ok 1007 constructor called once
,ok 1008 constructor called with right args
,ok 1009 first start before first stop
,ok 1010 first stop before second start
,ok 1011 second start before second stop
,# teardown
,# setup
,# two identical starts in a row
,2017-07-14 12:45:46 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 1012 verify failed
,ok 1013 constructor called once
,ok 1014 constructor called with right args
,ok 1015 (unnamed assert)
,# teardown
,# setup
,# two different starts in a row
,2017-07-14 12:45:47 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 1016 verify failed
,ok 1017 constructor called once
,ok 1018 constructor called with right args
,ok 1019 (unnamed assert)
,ok 1020 (unnamed assert)
,# teardown
,# setup
,# two stops and a start and two stops
,2017-07-14 12:45:49 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 1021 verify failed
,ok 1022 constructor called once
,ok 1023 constructor called with right args
,ok 1024 start before stop
,# teardown
,# setup
,# we properly enqueue requests so no then needed
,2017-07-14 12:45:50 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 1025 verify failed
,ok 1026 constructor called once
,ok 1027 constructor called with right args
,ok 1028 start before stop
,# teardown
,# setup
,# test calculateSeqPointKeyId
,ok 1029 should be equal
ok 1030 should be equal
,# teardown
,# setup
,# #_doImmediateSeqUpdate - server is not there
,2017-07-14 12:45:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 12:45:51 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}'
ok 1031 Got right error
# teardown
,2017-07-14 12:45:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - server accepts & closes connection
,2017-07-14 12:45:51 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNRESET","status":500}'
ok 1032 Got socket hang up
# teardown
,2017-07-14 12:45:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - server always returns 500
,2017-07-14 12:45:52 - DEBUG localSeqManager: 'Got an error trying to update seq []'
,ok 1033 Got 500 as expected
,# teardown
,2017-07-14 12:45:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - create new seq doc
,ok 1034 should be equal
,ok 1035 revs are equal
,# teardown
,2017-07-14 12:45:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - doc exists, need to get rev and update
,ok 1036 should be equal
,ok 1037 revs are equal
,# teardown
,2017-07-14 12:45:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - update seq three times
,ok 1038 should be equal
ok 1039 revs are equal
,ok 1040 should be equal
,ok 1041 revs are equal
,ok 1042 should be equal
,ok 1043 revs are equal
,# teardown
,2017-07-14 12:45:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - rev got changed under us
,(node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
,Trace: 
    at $3.prototype.trace@console.js:139:8
    at addListener@events.js:140:1
    at module.exports@/private/var/containers/Bundle/Application/83F91E1F-B78B-4AAD-A7C2-E59ED0838EAA/ThaliTest.app/www/jxcore/node_modules/pouchdb-all-dbs/lib/index.j,s:82:3
    at module.exports/<.start/<@/private/var/containers/Bundle/Application/83F91E1F-B78B-4AAD-A7C2-E59ED0838EAA/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/lib/index.js:143:9
    at tryCatcher@/private/var/containers/Bundle/Application/8,3F91E1F-B78B-4AAD-A7C2-E59ED0838EAA/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/util.js:16:16
    at module.exports/Promise.prototype._settlePromiseFromHandler@/private/var/containers/Bundle/Application/83F91E1F-,B78B-4AAD-A7C2-E59ED0838EAA/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:504:13
,2017-07-14 12:46:00 - DEBUG localSeqManager: 'Got an error trying to update seq {"error":"conflict","reason":"Document update conflict","name":"conflict","status":409,"message":"Document update conflict"}'
,ok 1044 Our rev is old so we should fail
,# teardown
,2017-07-14 12:46:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - fail if stop is called
,ok 1045 confirm stop caused failure
,(node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
,Trace: 
    at $3.prototype.trace@console.js:139:8
    at addListener@events.js:140:1
    at module.exports@/private/var/containers/Bundle/Application/83F91E1F-B78B-4AAD-A7C2-E59ED0838EAA/ThaliTest.app/www/jxcore/node_modules/pouchdb-all-dbs/lib/index.j,s:57:3
    at module.exports/<.start/<@/private/var/containers/Bundle/Application/83F91E1F-B78B-4AAD-A7C2-E59ED0838EAA/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/lib/index.js:143:9
    at tryCatcher@/private/var/containers/Bundle/Application/8,3F91E1F-B78B-4AAD-A7C2-E59ED0838EAA/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/util.js:16:16
    at module.exports/Promise.prototype._settlePromiseFromHandler@/private/var/containers/Bundle/Application/83F91E1F-,B78B-4AAD-A7C2-E59ED0838EAA/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:504:13
,# teardown
,2017-07-14 12:46:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - stop after get but before put fails right
,2017-07-14 12:46:02 - DEBUG localSeqManager: 'Got an error trying to update seq {"onPut":true}'
,ok 1046 stop caused us to fail
,ok 1047 We specifically failed on a stop before put
,# teardown
,2017-07-14 12:46:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - fail if stop is called
,ok 1048 failed due to stop
,ok 1049 failed due to stop
,# teardown
,2017-07-14 12:46:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - set seq for first time
,ok 1050 should be equal
,# teardown
,2017-07-14 12:46:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - Fail on bad seq value
,2017-07-14 12:46:06 - DEBUG localSeqManager: 'Got a bad seq, submitted seq 9, _nextSeqValueToSend: 10'
,ok 1051 Expected bad seq error
,# teardown
,2017-07-14 12:46:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - do we cancel timer properly on an immediate?
,ok 1052 Different promises
,ok 1053 Timer was cancelled
,ok 1054 should be equal
,# teardown
,2017-07-14 12:46:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - do we wait for blocked update
,ok 1055 One go and one blocked
ok 1056 All blocked
,ok 1057 Still blocked
,ok 1058 should be equal
,# teardown
,2017-07-14 12:46:11 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - test that we wait long enough
,ok 1059 We waited long enough
,ok 1060 should be equal
,# teardown
,2017-07-14 12:46:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - test that we pick up new sequences while we wait
,ok 1061 Should have gotten same timer promise
ok 1062 Still same timer promise
,ok 1063 We waited long enough
,ok 1064 should be equal
,# teardown
,2017-07-14 12:46:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Coordinated seq test
,2017-07-14 12:46:16 - DEBUG CoordinatedClient: 'test was skipped, name: 'Coordinated seq test''
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-14 12:46:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:46:17 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
,# setup
,# test thali manager spies
,2017-07-14 12:46:17 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
,2017-07-14 12:46:17 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
,2017-07-14 12:46:17 - DEBUG thaliManager: 'creating express pouchdb instance'
,ok 1065 expressPouchDB was called once
,ok 1066 expressPouchDB was called with 2 arguments
,ok 1067 expressPouchDB was called with 'PouchDB' as 1-st argument
,ok 1068 expressPouchDB was called with 'expressPouchDB options' as 2-st argument
,ok 1069 PouchDB was called once
ok 1070 PouchDB was called with 1 arguments
,ok 1071 PouchDB was called with 'dbName' as 1-st argument
,ok 1072 ThaliSendNotificationBasedOnReplication was called once
,ok 1073 ThaliSendNotificationBasedOnReplication was called with 4 arguments
,ok 1074 ThaliSendNotificationBasedOnReplication was called with 'express.Router instance' as 1-st argument
,ok 1075 ThaliSendNotificationBasedOnReplication was called with 'ecdhForLocalDevice' as 2-st argument
,ok 1076 ThaliSendNotificationBasedOnReplication was called with 'thaliConfig.BEACON_MILLISECONDS_TO_EXPIRE' as 3-st argument
,ok 1077 ThaliSendNotificationBasedOnReplication was called with 'PouchDB instance' as 4-st argument
,ok 1078 ThaliPullReplicationFromNotification was called once
,ok 1079 ThaliPullReplicationFromNotification was called with 4 arguments
,ok 1080 ThaliPullReplicationFromNotification was called with 'PouchDB' as 1-st argument
,ok 1081 ThaliPullReplicationFromNotification was called with 'dbName' as 2-st argument
,ok 1082 ThaliPullReplicationFromNotification was called with 'ThaliPeerPoolInterface instance' as 3-st argument
,ok 1083 ThaliPullReplicationFromNotification was called with 'ecdhForLocalDevice' as 4-st argument
,ok 1084 Salti was called once
,ok 1085 Salti was called with 4 arguments
,ok 1086 Salti was called with 'dbName' as 1-st argument
,ok 1087 Salti was called with 'acl' as 2-st argument
,ok 1088 Salti was called with 'thaliIdCallback' as 3-st argument
,ok 1089 Salti was called with 'options' as 4-st argument
,2017-07-14 12:46:17 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
,2017-07-14 12:46:17 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-07-14 12:46:17 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-07-14 12:46:17 - DEBUG thaliMobileNativeWrapper: 'listening 50968'
2017-07-14 12:46:17 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C3170A81-82E7-4ABD-A4FE-854DA6714FED
,[ThaliCore] Browser.startListening
,2017-07-14 12:46:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 12:46:17 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "85E5ECD1-1D5B-48EC-A0AD-78D3B25DE08E", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:85E5ECD1-1D5B-48EC-A0AD-78D3B25DE08E
,2017-07-14 12:46:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-14 12:46:17 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
,ok 1090 ThaliMobile.start was called once
,ok 1091 ThaliMobile.start was called with 3 arguments
,ok 1092 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
,ok 1093 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
,ok 1094 ThaliMobile.start was called with 'networkType' as 3-st argument
,ok 1095 ThaliMobile.startListeningForAdvertisements was called once
,ok 1096 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
,ok 1097 ThaliMobile.startUpdateAdvertisingAndListening was called once
,ok 1098 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
,ok 1099 ThaliSendNotificationBasedOnReplication.prototype.start was called once
,ok 1100 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
,ok 1101 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
,ok 1102 ThaliPullReplicationFromNotification.prototype.start was called once
,ok 1103 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
,ok 1104 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
,2017-07-14 12:46:17 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,2017-07-14 12:46:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-14 12:46:17 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})'
,2017-07-14 12:46:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-14 12:46:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:46:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-07-14 12:46:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 1105 ThaliMobile.stop was called once
,ok 1106 ThaliMobile.stop was called with 0 arguments
,ok 1107 ThaliSendNotificationBasedOnReplication.prototype.stop was called once
ok 1108 ThaliSendNotificationBasedOnReplication.prototype.stop was called with 0 arguments
,ok 1109 ThaliPullReplicationFromNotification.prototype.stop was called once
,ok 1110 ThaliPullReplicationFromNotification.prototype.stop was called with 0 arguments
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 12:46:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:46:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,# teardown
,# setup
,# test thali manager multiple starts and stops
,2017-07-14 12:46:18 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
,2017-07-14 12:46:18 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
,2017-07-14 12:46:18 - DEBUG thaliManager: 'creating express pouchdb instance'
,ok 1111 expressPouchDB was called once
,ok 1112 expressPouchDB was called with 2 arguments
ok 1113 expressPouchDB was called with 'PouchDB' as 1-st argument
,ok 1114 expressPouchDB was called with 'expressPouchDB options' as 2-st argument
ok 1115 PouchDB was called once
,ok 1116 PouchDB was called with 1 arguments
,ok 1117 PouchDB was called with 'dbName' as 1-st argument
,ok 1118 ThaliSendNotificationBasedOnReplication was called once
,ok 1119 ThaliSendNotificationBasedOnReplication was called with 4 arguments
,ok 1120 ThaliSendNotificationBasedOnReplication was called with 'express.Router instance' as 1-st argument
,ok 1121 ThaliSendNotificationBasedOnReplication was called with 'ecdhForLocalDevice' as 2-st argument
,ok 1122 ThaliSendNotificationBasedOnReplication was called with 'thaliConfig.BEACON_MILLISECONDS_TO_EXPIRE' as 3-st argument
,ok 1123 ThaliSendNotificationBasedOnReplication was called with 'PouchDB instance' as 4-st argument
,ok 1124 ThaliPullReplicationFromNotification was called once
,ok 1125 ThaliPullReplicationFromNotification was called with 4 arguments
,ok 1126 ThaliPullReplicationFromNotification was called with 'PouchDB' as 1-st argument
,ok 1127 ThaliPullReplicationFromNotification was called with 'dbName' as 2-st argument
,ok 1128 ThaliPullReplicationFromNotification was called with 'ThaliPeerPoolInterface instance' as 3-st argument
,ok 1129 ThaliPullReplicationFromNotification was called with 'ecdhForLocalDevice' as 4-st argument
,ok 1130 Salti was called once
,ok 1131 Salti was called with 4 arguments
,ok 1132 Salti was called with 'dbName' as 1-st argument
,ok 1133 Salti was called with 'acl' as 2-st argument
,ok 1134 Salti was called with 'thaliIdCallback' as 3-st argument
ok 1135 Salti was called with 'options' as 4-st argument
,2017-07-14 12:46:18 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
,2017-07-14 12:46:18 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-07-14 12:46:18 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-07-14 12:46:18 - DEBUG thaliMobileNativeWrapper: 'listening 50970'
2017-07-14 12:46:18 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:E9915BDD-03D4-4DD9-B96B-7EAA1FE0AD50
[ThaliCore] Browser.startListening
,2017-07-14 12:46:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 12:46:18 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C229710C-240B-4BE1-A2E2-32321E01C2B2", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:C229710C-240B-4BE1-A2E2-32321E01C2B2
,2017-07-14 12:46:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-14 12:46:18 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
,ok 1136 ThaliMobile.start was called once
,ok 1137 ThaliMobile.start was called with 3 arguments
,ok 1138 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
,ok 1139 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
,ok 1140 ThaliMobile.start was called with 'networkType' as 3-st argument
,ok 1141 ThaliMobile.startListeningForAdvertisements was called once
,ok 1142 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
,ok 1143 ThaliMobile.startUpdateAdvertisingAndListening was called once
,ok 1144 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
,ok 1145 ThaliSendNotificationBasedOnReplication.prototype.start was called once
,ok 1146 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
,ok 1147 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
,ok 1148 ThaliPullReplicationFromNotification.prototype.start was called once
,ok 1149 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
,ok 1150 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
,2017-07-14 12:46:18 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,2017-07-14 12:46:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-14 12:46:18 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})'
2017-07-14 12:46:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state,).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-14 12:46:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:46:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-14 12:46:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 12:46:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:46:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 1151 ThaliMobile.stop was called once
,ok 1152 ThaliMobile.stop was called with 0 arguments
,ok 1153 ThaliSendNotificationBasedOnReplication.prototype.stop was called once
,ok 1154 ThaliSendNotificationBasedOnReplication.prototype.stop was called with 0 arguments
,ok 1155 ThaliPullReplicationFromNotification.prototype.stop was called once
,ok 1156 ThaliPullReplicationFromNotification.prototype.stop was called with 0 arguments
,2017-07-14 12:46:18 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
,2017-07-14 12:46:18 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-07-14 12:46:18 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-07-14 12:46:18 - DEBUG thaliMobileNativeWrapper: 'listening 50972'
2017-07-14 12:46:18 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D22C93FA-793B-4F02-A254-F2A06BD9399F
[ThaliCore] Browser.startListening
,2017-07-14 12:46:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 12:46:18 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "E043E3B3-C55C-4495-8E7E-6372BD1AF48E", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:E043E3B3-C55C-4495-8E7E-6372BD1AF48E
,2017-07-14 12:46:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-14 12:46:18 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
,2017-07-14 12:46:18 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,2017-07-14 12:46:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-14 12:46:18 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})'
,2017-07-14 12:46:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-14 12:46:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:46:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 12:46:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 12:46:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:46:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 12:46:18 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
,2017-07-14 12:46:18 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-07-14 12:46:18 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-07-14 12:46:18 - DEBUG thaliMobileNativeWrapper: 'listening 50974'
2017-07-14 12:46:18 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:26C45CAD-18ED-4CF7-ACE7-6D192FFBE606
,[ThaliCore] Browser.startListening
,2017-07-14 12:46:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-14 12:46:18 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "0698D78D-09B1-467C-941D-1F046BFE19A2", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:0698D78D-09B1-467C-941D-1F046BFE19A2
,2017-07-14 12:46:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-14 12:46:18 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
,2017-07-14 12:46:18 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,2017-07-14 12:46:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-14 12:46:18 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})'
2017-07-14 12:46:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-14 12:46:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14, 12:46:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-14 12:46:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 12:46:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:46:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 12:46:18 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2017-07-14 12:46:18 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-07-14 12:46:18 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-07-14 12:46:18 - DEBUG thaliMobileNativeWrapper: 'listening 50976'
,2017-07-14 12:46:18 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:158BDDF9-735E-43E5-850D-33FBD2CBDA7E
[ThaliCore] Browser.startListening
,2017-07-14 12:46:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 12:46:18 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "9B63E3C7-8AB0-49CC-B65E-4310226AE027", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:9B63E3C7-8AB0-49CC-B65E-4310226AE027
,2017-07-14 12:46:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-14 12:46:18 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
,ok 1157 ThaliMobile.start was called once
,ok 1158 ThaliMobile.start was called with 3 arguments
,ok 1159 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
,ok 1160 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
,ok 1161 ThaliMobile.start was called with 'networkType' as 3-st argument
,ok 1162 ThaliMobile.startListeningForAdvertisements was called once
,ok 1163 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
,ok 1164 ThaliMobile.startUpdateAdvertisingAndListening was called once
,ok 1165 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
,ok 1166 ThaliSendNotificationBasedOnReplication.prototype.start was called once
,ok 1167 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
,ok 1168 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
,ok 1169 ThaliPullReplicationFromNotification.prototype.start was called once
,ok 1170 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
,ok 1171 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
,2017-07-14 12:46:18 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,2017-07-14 12:46:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-14 12:46:18 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})'
,2017-07-14 12:46:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-14 12:46:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:46:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 12:46:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 12:46:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:46:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,# teardown
,# setup
,# test write
,2017-07-14 12:46:19 - DEBUG CoordinatedClient: 'test was skipped, name: 'test write''
,# teardown
,# setup
,# test repeat write 1
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll can close even when connections open'
2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll with promise'
2017-07-14 12:46:20 - INFO, CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning set to false'
2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll works even with a server ,that is not listening yet witheatNotRunning set to true'
2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on a single db change'
2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOG,GER result: skipped - Call of multiple onCheckpointReached handlers on a single db change'
2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are in the checkpoin,ts plugin delay interval'
2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultDirectory'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultAdapter'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueue and run in order'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueueAtTop and run backwards'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - mix enqueue and enqueueAtTop'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - queues handled independently'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueued function are always executed asynchronously'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - exceptions in the executor are properly handled'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - basic'
2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - another'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - skip'
2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - another skip'
2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: pass,ed - test sinon sansbox spy'
2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub override'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox mock'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox restore after test end'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can pass data in setup'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Correctly parses/stringifies USN'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerLost calls jxcore'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerDiscovered calls jxcore'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopListeningForAdvertisements'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startListeningForAdvertisements twice is NOT an error'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling stopListeningForAdvertisements without calling start is NOT an error'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopUpdateAdvertisingAndListening'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startUpdateAdvertisingAndListening twice is NOT an error'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call stopUpdateAdvertisingAndListening twice without start and it is not an error'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChange is called'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can connect to a remote peer'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data via parallel connections'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data securely'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift large amounts of data'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We do not emit peerAvailabilityChanged events until one of the start methods is called'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Test updating advertising and parallel data transfer'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - discoveryAdvertisingStateUpdateNonTCP is called'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - cannot call connect when start listening for advertisements is not active'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Get error when trying to double connect to a peer on Android'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect when start listening for advertisements is not active'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with illegal peerID'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiConnect properly fails on legal but non-existent peerID'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with invalid syncValue'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call disconnect with invalid peer id'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - disconnect doesn't fail on plausible but bogus peer ID'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Get same port when trying to connect multiple times on iOS'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - initial peer discovery'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 1'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 2'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - check latest peer discovery'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Set up for no peer discovery test'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - no peer discovery'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling createNativeListener directly rejects'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits incomingConnectionState'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits routerPortConnectionFailed'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server connections all up'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming stream cleans outgoing socket'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming connection cleans outgoing socket'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing outgoing socket cleans associated mux stream'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing the whole server cleans everything up'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - we can get a ton of connections and data through and still clean up the server completely'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - simulate mux failure, make sure everything is cleaned up'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - timing out the incoming connection cleans everything up'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can create servers manager'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling stop without start causes error'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can start/stop servers manager'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - starting twice resolves with listening port'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminateIncomingConnection will terminate a connection'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminate an Outgoing connection'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single local http request'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single coordinated request ios native'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Multiple local http requests'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Multiple coordinated request ios native'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startListeningForAdvertisements should fail if start not called'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if start not called'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopListeningForAdvertisements many times'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startListeningForAdvertisements many times'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startUpdateAdvertisingAndListening many times'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopAdvertisingAndListening many times'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get the network status before starting'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - error returned with bad router'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - all services are started when we call start'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - TCP Servers Manager should be null when we call start on iOS'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - all services are stopped when we call stop'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure terminateConnection is properly hooked up'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure terminateConnection is return error if we get called on iOS'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure terminateListener is properly hooked up'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure terminateListener is return error if we get called on iOS'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure we actually call kill connections properly'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire failedNativeConnection event when we get failedConnection from multiConnectConnection'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure bad PSK connections fail'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - peer changes handled from a queue'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - relaying discoveryAdvertisingStateUpdateNonTCP'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - we successfully receive and replay discoveryAdvertisingStateUpdate'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can do HTTP requests between peers'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can still do HTTP requests between peers with coordinator'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - calls correct starts when network changes'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test to coordinate connection cut'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can do HTTP requests after connections are cut'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - will fail bad PSK connection between peers'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We provide notification when a listener dies and we recreate it'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startListeningForAdvertisements should fail if start not called'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if start not called'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopListeningForAdvertisements many times'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startListeningForAdvertisements many times'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startUpdateAdvertisingAndListening many times'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopAdvertisingAndListening many times'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #start - Causing native or wifi to fail will cause a promise reject '
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #start should fail if called twice in a row'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - does not emit duplicate discoveryAdvertisingStateUpdate'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - does not send duplicate availability changes'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get the network status'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer added/removed to/from cache (native)'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer added/removed to/from cache (wifi)'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - new peer is cached'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - native available - peer with same port and different generation is cached (BLUETOOTH)'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - peer with greater generation is cached (MPCF)'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - peer with same or older generation is ignored (MPCF)'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native unavailable - new peer is ignored'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native unavailable - cached peer is removed'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - networkChanged - fires peerAvailabilityChanged event for wifi peers'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiconnect failure - new peer is ignored (MPCF)'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - newAddressPort field (TCP_NATIVE)'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - newAddressPort field (BLUETOOTH)'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - newAddressPort field (MPCF)'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - error when peer has not been discovered yet'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - returns discovered cached wifi peer'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #disconnect fails on wifi peers'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #disconnect delegates native peers to the native wrapper'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes emitted correctly'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes not emitted in started state'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes not emitted in stopped state'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We properly fire peer unavailable and then available when connection fails on Android'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We properly fire peer unavailable and then available when connection fails on iOS'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - does not fire duplicate events after peer listener recreation'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #stop should change peers'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - peer should be found once after listening and discovery started'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get data from all participants'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - test for data corruption'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - test getters'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - start and kill'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - double start'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - start after kill'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - make sure ids are unique'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - check that forever agent can be destroyed'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test PeerDictionary basic functionality'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test PeerDictionary with multiple entries.'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - RESOLVED entries are removed before WAITING state entry.'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - WAITING entries are removed before CONTROLLED_BY_POOL state entry.'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - When CONTROLLED_BY_POOL entry is removed and kill is called.'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - single action'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - multiple actions'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - PSK Pool works'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - stop'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure that start verifies queue length'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - bad enqueues'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - do not allow same object type'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure we catch kill and dequeue'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure that stop removes all actions'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We reject unrecognized connection type'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We reject unrecognized action type'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - One action on bluetooth'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Two notification actions'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - replicateThroughProblems'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Replication goes first'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - wifi allows many parallel non-replication actions'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - wifi allows no more than 2 simultaneous replication actions for same peerID'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Client to server request coordinated'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test BEACONS_RETRIEVED_AND_PARSED locally'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test HTTP_BAD_RESPONSE locally'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test NETWORK_PROBLEM locally'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Action fails when getPeerHostInfo fails'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the start two times'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill before calling the start'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill immediately after the start'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill while waiting a response from the server'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test to exceed the max content size locally'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Close the server socket while the client is waiting a response from the server. Local test.'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Close the client socket while the client is waiting a response from the server. Local test.'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons bad args'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons empty keys to notify'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons multiple keys to notify'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid expiration in beaconStreamWithPreAmble'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons expiration out of range lower'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons expiration out of range lower'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons no beacons returns null'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback fails decrypt'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns no matches'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns spurious match'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns public key'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskIdentityField'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskSecret'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskSecrets'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generateBeaconStreamAndSecrets'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Add two Peers.'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - TCP_NATIVE peer loses DNS'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Received beacons with no values for us'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Notification action killed with a superseded'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Resolves an action locally'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Emits error event when peerPool.enqueue throws'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Resolves an action locally using ThaliPeerPoolDefault'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Action fails because of a bad hostname.'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - hostaddress is removed when the action is running. '
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - notificationClient does not retry action with BAD_PEER resolution'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - notification client correctly handles peer availability changes of the same peer'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Client to server request locally'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache clean and expiration'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache getSecret and getPublic'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache multiple entries'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Start and stop ThaliNotificationServer'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass an empty array to ThaliNotificationServer.start'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass a string to ThaliNotificationServer.start'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass an empty parameter to ThaliNotificationServer.start'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeacons'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeacons (no keys)'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeaconsbefore calling start'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure peerDictionaryKey is reasonable'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure start works'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure stop works'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Emits error event when peerPool.enqueue throws'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Simple peer event'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Coordinated pull replication from notification test'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server is not there'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server accepts & closes connection'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server always returns 500'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server always returns 401'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server always returns 403'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure docs replicate with remote db with same name as local db'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure docs replicate with remote db with different name than local db'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Do nothing and make sure we time out'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Do something and make sure we time out'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Start replicating and then catch error when server goes'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure clone works'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Coordinated replication action test - each device has the same local db name'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Coordinated replication action test - each device has different local db name'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Coordinated replication action test - should throw error when wrong remote db name is provided'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - compareBufferArrays'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call start twice and get error'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Start and make sure it runs'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure getTimeWhenRun is right after start'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure getTimeWhenRun is -1 after function is called'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test TransientState'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - No peers and empty database'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - One peer and empty DB'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - One peer with _Local set behind current seq'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - One peer with _Local set equal to current seq'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - One peer with _Local set ahead of current seq (and no this should not happen)'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Three peers, one not in DB, one behind and one ahead'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - More than maximum peers, make sure we only send maximum allowed'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - two peers with empty DB, update the doc'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - add doc and make sure tokens refresh when they expire'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - start and stop and start and stop'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - two identical starts in a row'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - two different starts in a row'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - two stops and a start and two stops'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - we properly enqueue requests so no then needed'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test calculateSeqPointKeyId'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - server is not there'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - server accepts & closes connection'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - server always returns 500'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - create new seq doc'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - doc exists, need to get rev and update'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - update seq three times'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - rev got changed under us'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - fail if stop is called'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - stop after get but before put fails right'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #update - fail if stop is called'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #update - set seq for first time'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #update - Fail on bad seq value'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #update - do we cancel timer properly on an immediate?'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #update - do we wait for blocked update'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #update - test that we wait long enough'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #update - test that we pick up new sequences while we wait'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Coordinated seq test'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test thali manager spies'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test thali manager multiple starts and stops'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - test write'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: failed - test repeat write 1, error: 'TypeError: thaliManager is undefined', stack: 'testRepeatWrite/<@/private/var/containers/Bundle/Application/83F91E1F-B78B-4AAD-A7C2-E59ED0838EAA/Tha,liTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js:279:7
CoordinatedClient.prototype._processEvent/</<@/private/var/containers/Bundle/Application/83F91E1F-B78B-4AAD-A7C2-E59ED0838EAA/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:471:9
canc,ellationExecute@/private/var/containers/Bundle/Application/83F91E1F-B78B-4AAD-A7C2-E59ED0838EAA/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/debuggability.js:320:9
module.exports/Promise.prototype._resolveFromExecutor@/private/var/containers/,Bundle/Application/83F91E1F-B78B-4AAD-A7C2-E59ED0838EAA/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:481:13
Promise@/private/var/containers/Bundle/Application/83F91E1F-B78B-4AAD-A7C2-E59ED0838EAA/ThaliTest.app/www/jxcore/node_modul,es/bluebird/js/release/promise.js:77:9
CoordinatedClient.prototype._processEvent/<@/private/var/containers/Bundle/Application/83F91E1F-B78B-4AAD-A7C2-E59ED0838EAA/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:428:14
tryCatcher@/private/var/containers,/Bundle/Application/83F91E1F-B78B-4AAD-A7C2-E59ED0838EAA/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/util.js:16:16
module.exports/Promise.prototype._settlePromiseFromHandler@/private/var/containers/Bundle/Application/83F91E1F-B78B-4AAD-A7C2-,E59ED0838EAA/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:510:13
module.exports/Promise.prototype._settlePromise@/private/var/containers/Bundle/Application/83F91E1F-B78B-4AAD-A7C2-E59ED0838EAA/ThaliTest.app/www/jxcore/node_modules/,bluebird/js/release/promise.js:567:13
module.exports/Promise.prototype._settlePromise0@/private/var/containers/Bundle/Application/83F91E1F-B78B-4AAD-A7C2-E59ED0838EAA/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:612:5
module.expor,ts/Promise.prototype._settlePromises@/private/var/containers/Bundle/Application/83F91E1F-B78B-4AAD-A7C2-E59ED0838EAA/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:691:13
Async.prototype._drainQueue@/private/var/containers/Bundle/App,lication/83F91E1F-B78B-4AAD-A7C2-E59ED0838EAA/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/async.js:138:13
Async.prototype._drainQueues@/private/var/containers/Bundle/Application/83F91E1F-B78B-4AAD-A7C2-E59ED0838EAA/ThaliTest.app/www/jxcore/n,ode_modules/bluebird/js/release/async.js:148:5
Async/this.drainQueues@/private/var/containers/Bundle/Application/83F91E1F-B78B-4AAD-A7C2-E59ED0838EAA/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/async.js:17:9
$v@timers.js:364:1
''
2017-07-,14 12:46:20 - ERROR CoordinatedClient: 'failed to run unit tests, platformName: 'ios''
,2017-07-14 12:49:21 - DEBUG CoordinatedClient: 'all tests completed'
,2017-07-14 12:49:21 - DEBUG CoordinatedClient: 'test client disconnected'
2017-07-14 12:49:21 - DEBUG CoordinatedClient: 'test client failed'
2017-07-14 12:49:21 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: TimeoutError: timeout exceeded, ,event: 'run_test repeat write 1_finished', test: 'test repeat write 1'', stack: 'CoordinatedClient.prototype._customError@/private/var/containers/Bundle/Application/83F91E1F-B78B-4AAD-A7C2-E59ED0838EAA/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:292:,27
Emitter.prototype.emit@/private/var/containers/Bundle/Application/83F91E1F-B78B-4AAD-A7C2-E59ED0838EAA/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7
Socket.prototype.onevent@/private/var/containers/Bundle/Application/83F91E1F-,B78B-4AAD-A7C2-E59ED0838EAA/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:263:5
Socket.prototype.onpacket@/private/var/containers/Bundle/Application/83F91E1F-B78B-4AAD-A7C2-E59ED0838EAA/ThaliTest.app/www/jxcore/node_modules/socket.,i,o-client/lib/socket.js:221:7
module.exports/<@/private/var/containers/Bundle/Application/83F91E1F-B78B-4AAD-A7C2-E59ED0838EAA/ThaliTest.app/www/jxcore/node_modules/component-bind/index.js:21:12
Emitter.prototype.emit@/private/var/containers/Bundle/Applic,ation/83F91E1F-B78B-4AAD-A7C2-E59ED0838EAA/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7''
2017-07-14 12:49:21 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'

```
