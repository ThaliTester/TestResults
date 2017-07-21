#### Test 113351851c966256_iOS_Iphone6sPlus-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/113351851c966256/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6s Plus 'Iphone6sPlus-1' (f70cda60583ea0f895d05ea355cd125983c27594) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/38767762-6A24-4B0E-80B6-18961095F767/fruitstrap-lldb-prep-cmds-f70cda60583ea0f895d05ea355cd125983c27594'
,Executing commands in '/tmp/38767762-6A24-4B0E-80B6-18961095F767/fruitstrap-lldb-prep-cmds-f70cda60583ea0f895d05ea355cd125983c27594'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/113351851c966256/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/113351851c966256/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/B9D1774A-DA75-4C08-98B8-DB88E3B59AC6/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55734"
,(lldb)     command script import "/tmp/38767762-6A24-4B0E-80B6-18961095F767/fruitstrap_f70cda60583ea0f895d05ea355cd125983c27594.py"
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
,2017-07-21 06:35:37 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 06:35:37 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 06:35:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:35:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 06:35:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:35:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:35:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
AppContextTests.test_didEnterForeground finished
,AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
,AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
AppContextTests.test_esonValue finished
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "B1C4EB6B-073D-4A51-B39E-6013499C3B05", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:B1C4EB6B-073D-4A51-B39E-6013499C3B05
Optional(true)
Optional(false)
,AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:38B233FF-A097-4831-8B16-7258C21410C9
[ThaliCore] Browser.startListening
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:8FDA3C9E-,E7F9-4B53-95C0-8E114D063A68
[ThaliCore] Browser.startListening
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C87DDCA6-90D3-45DA-A4F7-A804E2B2A3A9", generation: 0)
[ThaliCore] Advertiser.startAdvertisi,ng with peerID:C87DDCA6-90D3-45DA-A4F7-A804E2B2A3A9
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C87DDCA6-90D3-45DA-A4F7-A804E2B2A3A9:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C87DDCA6-90D3-45DA-A4F7-A804E2B2A3A9", generation: 0)
AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvaila,bilityConversion finished
AppContextTests.test_disconnectErrors finished
AppContextTests.test_connectReturnValueCorrect finished
AppContextTests finished
All tests finished
All tests finished
,2017-07-21 06:35:39 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
Number of passed tests:  13
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  1.480284929275513
,2017-07-21 06:35:39 - DEBUG UnitTest_app: 'My device name is: 'Apple-Iphone6sPlus-1''
,2017-07-21 06:35:39 - WARN testUtils: 'myNameCallback not set!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:C87DDCA6-90D3-45DA-A4F7-A804E2B2A3A9:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "C87DDCA6-90D3-45DA-A4F7-A804E2B2A3A9", generation: 0)
,2017-07-21 06:35:41 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-07-21 06:35:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B9D1774A-DA75-4C08-98B8-DB88E3B59AC6/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-07-21 06:35:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B9D1774A-DA75-4C08-98B8-DB88E3B59AC6/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-07-21 06:35:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B9D1774A-DA75-4C08-98B8-DB88E3B59AC6/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-07-21 06:35:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B9D1774A-DA75-4C08-98B8-DB88E3B59AC6/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-07-21 06:35:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B9D1774A-DA75-4C08-98B8-DB88E3B59AC6/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-07-21 06:35:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B9D1774A-DA75-4C08-98B8-DB88E3B59AC6/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-07-21 06:35:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B9D1774A-DA75-4C08-98B8-DB88E3B59AC6/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-07-21 06:35:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B9D1774A-DA75-4C08-98B8-DB88E3B59AC6/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-07-21 06:35:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B9D1774A-DA75-4C08-98B8-DB88E3B59AC6/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-07-21 06:35:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B9D1774A-DA75-4C08-98B8-DB88E3B59AC6/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-07-21 06:35:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B9D1774A-DA75-4C08-98B8-DB88E3B59AC6/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-07-21 06:35:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B9D1774A-DA75-4C08-98B8-DB88E3B59AC6/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-07-21 06:35:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B9D1774A-DA75-4C08-98B8-DB88E3B59AC6/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-07-21 06:35:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B9D1774A-DA75-4C08-98B8-DB88E3B59AC6/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-07-21 06:35:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B9D1774A-DA75-4C08-98B8-DB88E3B59AC6/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-07-21 06:35:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B9D1774A-DA75-4C08-98B8-DB88E3B59AC6/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-07-21 06:35:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B9D1774A-DA75-4C08-98B8-DB88E3B59AC6/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-07-21 06:35:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B9D1774A-DA75-4C08-98B8-DB88E3B59AC6/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-07-21 06:35:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B9D1774A-DA75-4C08-98B8-DB88E3B59AC6/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-07-21 06:35:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B9D1774A-DA75-4C08-98B8-DB88E3B59AC6/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-07-21 06:35:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B9D1774A-DA75-4C08-98B8-DB88E3B59AC6/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-07-21 06:35:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B9D1774A-DA75-4C08-98B8-DB88E3B59AC6/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-07-21 06:35:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B9D1774A-DA75-4C08-98B8-DB88E3B59AC6/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-07-21 06:35:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B9D1774A-DA75-4C08-98B8-DB88E3B59AC6/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-07-21 06:35:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B9D1774A-DA75-4C08-98B8-DB88E3B59AC6/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-07-21 06:35:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B9D1774A-DA75-4C08-98B8-DB88E3B59AC6/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-07-21 06:35:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B9D1774A-DA75-4C08-98B8-DB88E3B59AC6/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-07-21 06:35:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B9D1774A-DA75-4C08-98B8-DB88E3B59AC6/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-07-21 06:35:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B9D1774A-DA75-4C08-98B8-DB88E3B59AC6/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-07-21 06:35:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B9D1774A-DA75-4C08-98B8-DB88E3B59AC6/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-07-21 06:35:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B9D1774A-DA75-4C08-98B8-DB88E3B59AC6/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-07-21 06:35:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B9D1774A-DA75-4C08-98B8-DB88E3B59AC6/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-07-21 06:35:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B9D1774A-DA75-4C08-98B8-DB88E3B59AC6/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-07-21 06:35:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B9D1774A-DA75-4C08-98B8-DB88E3B59AC6/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-07-21 06:35:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B9D1774A-DA75-4C08-98B8-DB88E3B59AC6/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-07-21 06:35:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B9D1774A-DA75-4C08-98B8-DB88E3B59AC6/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-07-21 06:35:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B9D1774A-DA75-4C08-98B8-DB88E3B59AC6/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-07-21 06:35:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B9D1774A-DA75-4C08-98B8-DB88E3B59AC6/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-07-21 06:35:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B9D1774A-DA75-4C08-98B8-DB88E3B59AC6/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-07-21 06:35:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B9D1774A-DA75-4C08-98B8-DB88E3B59AC6/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-07-21 06:35:43 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-07-21 06:35:43 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
,2017-07-21 06:35:43 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
,# setup
,# closeAll can close even when connections open
,2017-07-21 06:37:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 1 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll with promise
,2017-07-21 06:37:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 2 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll properly throws when closing a non open server with eatNotRunning set to false
,2017-07-21 06:37:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
# teardown
,# setup
,# closeAll works even with a server that is not listening yet witheatNotRunning set to true
,2017-07-21 06:37:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
,# setup
,# Call of onCheckpointReached handler on a single db change
,2017-07-21 06:37:53 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on a single db change''
,# teardown
,# setup
,# Call of multiple onCheckpointReached handlers on a single db change
,2017-07-21 06:37:53 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of multiple onCheckpointReached handlers on a single db change''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
,2017-07-21 06:37:54 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
,2017-07-21 06:37:55 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''
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
ok 33 second
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
,2017-07-21 06:38:02 - DEBUG CoordinatedClient: 'test was skipped, name: 'skip''
,# teardown
,# setup
,# another skip
,2017-07-21 06:38:03 - DEBUG CoordinatedClient: 'test was skipped, name: 'another skip''
,# teardown
,# setup
,# test sinon sansbox spy
,2017-07-21 06:38:07 - DEBUG testTests: 'test spy method for global sinon sansbox'
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
ok 52 test participant has uuid
,ok 53 participant data matches
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
,2017-07-21 06:38:16 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
,# teardown
,2017-07-21 06:38:16 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 06:38:16 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 06:38:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:38:16 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 06:38:16 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 06:38:16 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 06:38:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 06:38:16 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# onPeerDiscovered calls jxcore
,2017-07-21 06:38:17 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
,# teardown
,2017-07-21 06:38:17 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 06:38:17 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 06:38:17 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:38:17 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 06:38:17 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-07-21 06:38:17 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 06:38:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 06:38:17 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopListeningForAdvertisements
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:42F7CD00-EBC1-437D-9D37-63F06DE8964F
[ThaliCore] Browser.startListening
2017-07-21 06:38:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 06:38:17 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-21 06:38:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 62 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvert,isements()
[ThaliCore] Browser.stopListening()
2017-07-21 06:38:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:38:17 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
ok 63 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:38:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:38:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:38:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 06:38:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:38:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 06:38:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 06:38:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:38:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 06:38:18 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 06:38:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 06:38:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 06:38:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startListeningForAdvertisements twice is NOT an error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:218216B2-7A1E-4F23-8042-37A1D6E511EB
[ThaliCore] Browser.startListening
,2017-07-21 06:38:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 06:38:19 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:38:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 64 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
2017-07-21 06:38:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"di,scoveryActive":true,"advertisingActive":false}'
2017-07-21 06:38:19 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":",B,OTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:38:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 65 Can call startListeningForAdvertisements twice without e,rror
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 06:38:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21, 06:38:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:38:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discovery,Active":false,"advertisingActive":false}'
2017-07-21 06:38:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 06:38:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to n,ative'
2017-07-21 06:38:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 06:38:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:38:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 06:38:19 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:38:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:38:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:38:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling stopListeningForAdvertisements without calling start is NOT an error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:38:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:38:19 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 66 Can call stopListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:38:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingAct,ive":false}'
2017-07-21 06:38:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 67 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:38:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:38:20 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:38:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 06:38:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:38:20 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 06:38:20 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 06:38:20 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:38:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 06:38:20 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 06:38:20 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 06:38:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 06:38:20 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopUpdateAdvertisingAndListening
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "D10D5DD9-A04A-45FC-A7A6-A53209951E37", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:D10D5DD9-A04A-45FC-A7A6-A53209951E37
,2017-07-21 06:38:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 06:38:20 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:38:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 68 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:D10D5DD9-A04A-45FC-A7A6-A53209951E37
2017-07-21 06:38:20 ,- DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:38:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 69 Can call s,topAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:38:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:38:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:38:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 06:38:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:38:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 06:38:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 06:38:22 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:38:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 06:38:22 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 06:38:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 06:38:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 06:38:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startUpdateAdvertisingAndListening twice is NOT an error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "FD785FDA-39AC-4A58-8D14-5BA53EDA2363", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:FD785FDA-39AC-4A58-8D14-5BA53EDA2363
,2017-07-21 06:38:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 06:38:25 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:38:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 70 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "FD785FDA-39AC-4A58-8D14-5BA53EDA2363", generation: 1)
[,ThaliCore] Advertiser.startAdvertising with peerID:FD785FDA-39AC-4A58-8D14-5BA53EDA2363
2017-07-21 06:38:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 06:38:25, ,- INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkTyp,e":null}})'
2017-07-21 06:38:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 71 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:38:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 06:38:26 - INFO thaliMobile: 'Receive,d state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:3,8:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:FD785FDA-39AC-4A58-8D14-5BA53EDA2363
[ThaliCore] Advertiser.s,topAdvertising() peerID:FD785FDA-39AC-4A58-8D14-5BA53EDA2363
,2017-07-21 06:38:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:38:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
2017-07-21 06:38:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 06:38:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 06:38:26 ,- DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:38:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:38:26 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:38:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:38:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:38:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:38:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:38:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 72 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:38:29 - DEBUG th,aliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:38:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 73 Can call stopAdverti,singAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:38:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:38:29 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:38:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 06:38:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:38:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 06:38:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 06:38:29 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:38:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 06:38:29 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 06:38:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 06:38:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 06:38:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peerAvailabilityChange is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "F4D14FDE-8DE6-45E2-8E38-F7FC8DBAAB38", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:F4D14FDE-8DE6-45E2-8E38-F7FC8DBAAB38
2017-07-21 0,6:38:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 06:38:30 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:38:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 74 Can call startUpdateAdvertisingAndListeningwithout error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:EBC32B80-F749-4E49-BC9C-D72CFD65AC8D
[Thali,C,ore] Browser.startListening
2017-07-21 06:38:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 06:38:30 - INFO thaliMobile: 'Received state ({"discoveryActive":true,,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:38:30 - INFO thaliMobile: 'Filtered, out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 75 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F4D14FDE-8DE6-45E2-8E38-F7FC8DBAAB38:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F4D14FDE-8DE6-45E2-8E38-F7FC8DBAAB38", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D9D1E844-1C42-470F-A71E-A77043BAEA21:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D9D1E844-1C42-470F-A71E-A77043BAEA21", generation: 0)
ok 76 peers must be an array,
ok 77 peers must not be zero-length
ok 78 peer must have only peerIdentifier, peerAvailable and generation properties
ok 79 peerIdentifier must be a string
ok 80 generation must be a number
,# teardown
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A467C47C-CEFB-4C72-95CA-82A2A5CDEBC5:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A467C47C-CEFB-4C72-95CA-82A2A5CDEBC5", generation: 0)
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 06:38:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 ,06:38:32 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-21 06:38:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:F4D14FDE-8DE6-45E2-8E38-F,7FC8DBAAB38
2017-07-21 06:38:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:38:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 06:38:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 06:38:32 - DEBUG thaliMo,bileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 06:38:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:38:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:38:32 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:38:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:38:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:38:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can connect to a remote peer
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "CBC5836A-0CD7-4B62-8474-DE0109A6D422", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:CBC5836A-0CD7-4B62-8474-DE0109A6D422
2017-07-21 0,6:38:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 06:38:36 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:38:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 81 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:A7A8EE40-0C65-4C05-924B-AB3F71D4BD30
[Thal,i,Core] Browser.startListening
2017-07-21 06:38:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 06:38:36 - INFO thaliMobile: 'Received state ({"discoveryActive":true,,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:38:36 - INFO thaliMobile: 'Filtere,d out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 82 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CBC5836A-0CD7-4B62-8474-DE0109A6D422:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CBC5836A-0CD7-4B62-8474-DE0109A6D422", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:72CDDB0B-4760-4EF6-BDA7-3C0D12FFAC88
[ThaliCore] Advertiser: session connected Peer(uuid: "CBC5836A-0CD7-4B62-8474-DE0109A6D422", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:72CDDB0B-4760-4EF6-BDA7-3C0D12FFAC88 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FB2AB890-F1BF-4397-BF7D-A08733E010B3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FB2AB890-F1BF-4397-BF7D-A08733E010B3", generation: 0)
2017-07-21 06:38:37 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"FB2AB890-F1BF-4397-BF7D-A08733E010B3","generation":0}'
2017-07-21 06:38:37 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for FB2AB890-F1BF-4397-BF7D-A08733E010B3 (syncValue: P3mJymeuGzhiwZZvNJEia4AOLANk9aVD)'
2017-07-21 06:38:37 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "FB2AB890-F1BF-4397-BF7D-A08733E,010B3", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FB2AB890-F1BF-4397-BF7D-A08733E010B3", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:,) peer:FB2AB890-F1BF-4397-BF7D-A08733E010B3:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:FB2AB890-F1BF-4397-BF7D-A08733E010B3:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9D6CB8CE-C3F1-4704-B10F-2DA50F9A3AFA:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9D6CB8CE-C3F1-4704-B10F-2DA50F9A3AFA", generation: 0)
2017-07-21 06:38:39 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"9D6CB8CE-C3F1-4704-B10F-2DA50F9A3AFA","generation":0}'
2017-07-21 06:38:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 06:38:39 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:6BC80DF9-E102-4A96-B233-A23AE4892516
[ThaliCore] Advertiser: session connected Peer(uuid: "CBC5836A-0CD7-4B62-8474-DE0109A6D422", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:6BC80DF9-E102-4A96-B233-A23AE4892516 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:72CDDB0B-4760-4EF6-BDA7-3C0D12FFAC88
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:FB2AB890-F1BF-4397-BF7D-A08733E010B3:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:72CDDB0B-4760-4EF6-BDA7-3C0D12FFAC88 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:FB2AB890-F1BF-4397-BF7D-A08733E010B3:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "FB2AB890-F1BF-4397-BF7D-A08733E010B3", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:55229
,2017-07-21 06:38:40 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"P3mJymeuGzhiwZZvNJEia4AOLANk9aVD","error":null,"portNumber":55229}'
,2017-07-21 06:38:40 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'P3mJymeuGzhiwZZvNJEia4AOLANk9aVD', error: 'null', listeningPort: '55229''
,2017-07-21 06:38:40 - INFO testThaliMobileNative: ''
,ok 83 Must have listeningPort
,ok 84 listeningPort must be a number
,ok 85 listening port should not be 0
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:6BC80DF9-E102-4A96-B233-A23AE4892516
,[ThaliCore] Session.session(_:peer:didChange:) peer:6BC80DF9-E102-4A96-B233-A23AE4892516 state: connecting -> connected
,2017-07-21 06:38:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 06:38:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 06:38:42 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:38:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:CBC5836A-0CD7-4B62-8474-DE0109A6D422
,2017-07-21 06:38:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:38:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.disconnect peer:FB2AB890-F1BF-4397-BF7D-A08733E010B3
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:55229
[ThaliCore] Session.disconnect,() peer:FB2AB890-F1BF-4397-BF7D-A08733E010B3:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:6BC80DF9-E102-4A96-B233-A23AE4892516 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "CBC5836A-0CD7-4B62-8474-DE0109A6D422", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:6BC80DF9-E102-4A96-B233-A23AE4892516
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:FB2AB890-F1BF-4397-BF7D-A08733E010B3:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-21 06:38:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 06:38:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 06:38:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:38:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:38:42 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:38:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:38:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:38:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:72CDDB0B-4760-4EF6-BDA7-3C0D12FFAC88 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "CBC5836A-0CD7-4B62-8474-DE0109A6D422", generation: 0)
,# Can shift data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "D4E56564-627F-4CDE-8EE4-041EC9428CC9", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:D4E56564-627F-4CDE-8EE4-041EC9428CC9
2017-07-21 0,6:38:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 06:38:43 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:38:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 86 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:0374A4A2-CFD5-4A01-8EED-739A3BA2EE57
[Thali,Core] Browser.startListening
2017-07-21 06:38:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 06:38:43 - INFO thaliMobile: 'Received state ({"discoveryActive":true,,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:38:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 87 Can call startListeningForAdvertisements without error
,[ThaliCore] Session.deinit peer:6BC80DF9-E102-4A96-B233-A23AE4892516
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:06CC9300-6053-4EA1-8322-38AA391E12D9:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "06CC9300-6053-4EA1-8322-38AA391E12D9", generation: 0)
2017-07-21 06:38:44 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"06CC9300-6053-4EA1-8322-38AA391E12D9","generation":0}'
2017-07-21 06:38:44 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 06CC9300-6053-4EA1-8322-38AA391E12D9, (syncValue: l0HCjWRGJsX54IsbZ7oPU7zfqwhqtima)'
2017-07-21 06:38:44 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "06CC9300-6053-4EA1-8322-38AA391,E12D9", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "06CC9300-6053-4EA1-8322-38AA391E12D9", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected,:) peer:06CC9300-6053-4EA1-8322-38AA391E12D9:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F686267D-A694-4320-B2FC-1287833C0E7C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F686267D-A694-4320-B2FC-1287833C0E7C", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D4E56564-627F-4CDE-8EE4-041EC9428CC9:0
2017-07-21 06:38:44 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"F686267D-A694-4320-B2FC-1287833C0E,7C","generation":0}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D4E56564-627F-4CDE-8EE4-041EC9428CC9", generation: 0)
2017-07-21 06:38:44 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 06:38:44 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:06CC9300-6053-4EA1-8322-38AA391E12D9:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:06CC9300-6053-4EA1-8322-38AA391E12D9:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:06CC9300-6053-4EA1-8322-38AA391E12D9:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "06CC9300-6053-4EA1-8322-38AA391E12D9", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:55233
,2017-07-21 06:38:47 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"l0HCjWRGJsX54IsbZ7oPU7zfqwhqtima","error":null,"portNumber":55233}'
,2017-07-21 06:38:47 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'l0HCjWRGJsX54IsbZ7oPU7zfqwhqtima', error: 'null', listeningPort: '55233''
,Connecting to the localhost:55233
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
Connected to the localhost:55233
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:06CC9300-6053-4EA1-8322-38AA391E12D9:0
2017-07-21 06:38:47 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-21 06:38:47 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:06CC9300-6053-4EA1-8322-38AA391E12D9:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1 [1]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 88 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pee,r})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams,() vsID:1
# teardown
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,2017-07-21 06:38:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 06:38:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 06:38:58 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:38:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:D4E56564-627F-4CDE-8EE4-041EC9428CC9
,2017-07-21 06:38:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:38:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:06CC9300-6053-4EA1-8322-38AA391E12D9
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:55233
[ThaliCore] Session.disconnect() p,eer:06CC9300-6053-4EA1-8322-38AA391E12D9:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:06CC9300-6053-4EA1-8322-38AA391E12D9:0
,2017-07-21 06:38:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 06:38:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 06:38:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:38:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:38:58 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:38:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:38:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:38:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data via parallel connections
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "CF64E8D0-156A-46BC-86D9-00A60E9CC36C", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:CF64E8D0-156A-46BC-86D9-00A60E9CC36C
2017-07-21 06:38:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 06:38:59 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:38:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 89 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:A928C67E-400B-4A0D-AE74-6DAE2631BABB
[Thal,i,Core] Browser.startListening
2017-07-21 06:38:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 06:38:59 - INFO thaliMobile: 'Received state ({"discoveryActive":true,,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:38:59 - INFO thaliMobile: 'Filtere,d out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 90 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F686267D-A694-4320-B2FC-1287833C0E7C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F686267D-A694-4320-B2FC-1287833C0E7C", generation: 0)
2017-07-21 06:38:59 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"F686267D-A694-4320-B2FC-1287833C0E7C","generation":0}'
2017-07-21 06:38:59 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for F686267D-A694-4320-B2FC-1287833C0E7C, (syncValue: Gv4j5t0gsVjEH9d2RGy9ghrvE1Uim0WF)'
2017-07-21 06:38:59 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F686267D-A694-4320-B2FC-1287833,C0E7C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F686267D-A694-4320-B2FC-1287833C0E7C", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected,:) peer:F686267D-A694-4320-B2FC-1287833C0E7C:0
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:06CC9300-6053-4EA1-8322-38AA391E12D9:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "06CC9300-6053-4EA1-8322-38AA391E12D9,", generation: 0)
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-21 06:38:59 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailabl,e":true,"peerIdentifier":"06CC9300-6053-4EA1-8322-38AA391E12D9","generation":0}'
2017-07-21 06:38:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 06:38:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CF64E8D0-156A-46BC-86D9-00A60E9CC36C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CF64E8D0-156A-46BC-86D9-00A60E9CC36C", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:68B8CE8A-2484-44B9-9163-E111100BA365:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "68B8CE8A-2484-44B9-9163-E111100BA365", generation: 0)
2017-07-21 06:39:00 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"68B8CE8A-2484-44B9-9163-E111100BA365","generation":0}'
2017-07-21 06:39:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 06:39:00 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-21 06:39:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F8950B91-FC0C-4B52-9139-38BC77A5B47C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F8950B91-FC0C-4B52-9139-38BC77A5B47C", generation: 0)
2017-07-21 06:39:00 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"F8950B91-FC0C-4B52-9139-38BC77A5B47C","generation":0}'
2017-07-21 06:39:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 06:39:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 06:39:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 06:39:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:F686267D-A694-4320-B2FC-1287833C0E7C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:F6,86267D-A694-4320-B2FC-1287833C0E7C:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "F686267D-A694-4320-B2FC-1287833C0E7C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F,686267D-A694-4320-B2FC-1287833C0E7C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F686267D-A694-4320-B2FC-1287833C0E7C", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:F686267D-A694-4320-B2FC-1287833C0E7C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:F686267D-A694-4320-B2FC-1287833C0E7C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:F686267D-A694-4320-B2FC-1287833C0E7C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:F6,86267D-A694-4320-B2FC-1287833C0E7C:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "F686267D-A694-4320-B2FC-1287833C0E7C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F,686267D-A694-4320-B2FC-1287833C0E7C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F686267D-A694-4320-B2FC-1287833C0E7C", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:F686267D-A694-4320-B2FC-1287833C0E7C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:F686267D-A694-4320-B2FC-1287833C0E7C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:F686267D-A694-4320-B2FC-1287833C0E7C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:F6,86267D-A694-4320-B2FC-1287833C0E7C:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "F686267D-A694-4320-B2FC-1287833C0E7C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F,686267D-A694-4320-B2FC-1287833C0E7C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F686267D-A694-4320-B2FC-1287833C0E7C", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:F686267D-A694-4320-B2FC-1287833C0E7C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:F686267D-A694-4320-B2FC-1287833C0E7C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:F686267D-A694-4320-B2FC-1287833C0E7C:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "F686267D-A694-4320-B2FC-1287833C0E7C", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:F686267D-A694-4320-B2FC-1287833C0E7C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:F6,86267D-A694-4320-B2FC-1287833C0E7C:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "F686267D-A694-4320-B2FC-1287833C0E7C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:F686267D,-A694-4320-B2FC-1287833C0E7C error: max retries exceeded
2017-07-21 06:39:10 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Gv4j5t0gsVjEH9d2RGy9ghrvE1Uim0WF","error":"Connection could not be established","portNumber":null}'
2017-0,7-21 06:39:10 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'Gv4j5t0gsVjEH9d2RGy9ghrvE1Uim0WF', error: 'Connection could not be established', listeningPort: '%s''
2017-07-21 06:39:10 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"F686267D-A694-4320-B2FC-1287833C0E7C","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 06:39:10 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent, due to not being in started state'
2017-07-21 06:39:10 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"F686267D-A694-4320-B2FC-1287833C0E7C","peerAvailable":true,"portNumber":null,"recreated":true}'
20,17-07-21 06:39:10 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 06:39:10 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-21 06:39:10 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 06CC9300-6053-4EA1-8322-38AA391E12D9 (syncValue: 6JmJvTG,lz8Q4wd2izAhfwHiYTSsUFSqU)'
2017-07-21 06:39:10 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "06CC9300-6053-4EA1-8322-38AA391E12D9", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "06CC9300-6053-4EA1-8322-38AA391E12D9", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:06CC9300-6053,-4EA1-8322-38AA391E12D9:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-21 06:39:10 - DEBUG thaliMobileNativeTestUtils: 'Already running tes,t,!'
2017-07-21 06:39:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 06:39:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:F686267D-A694-4320-B2FC-1287833C0E7C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:06CC9300-6053-4EA1-8322-38AA391E12D9:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "06CC9300-6053-4EA1-8322-38AA391E12D9", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:06CC9300-6053-4EA1-8322-38AA391E12D9:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:06,CC9300-6053-4EA1-8322-38AA391E12D9:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "06CC9300-6053-4EA1-8322-38AA391E12D9", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0,6CC9300-6053-4EA1-8322-38AA391E12D9", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "06CC9300-6053-4EA1-8322-38AA391E12D9", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 06:39:13 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"6JmJvTGlz8Q4wd2izAhfwHiYTSsUFSqU","error":"Peer is unavailable",,"portNumber":null}'
2017-07-21 06:39:13 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '6JmJvTGlz8Q4wd2izAhfwHiYTSsUFSqU', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-21 06:39:13 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"06CC9300-6053-4EA1-8322-38AA391E12D9","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 06:39:13 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-21 06:39:13 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"06CC9300-6053-4EA1-8322-38AA391E12D9","peerAvailable":true,"portNumber":null,"recreate,d,":true}'
2017-07-21 06:39:13 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 06:39:13 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-21 06:39:13 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 68B8CE8A-2484-44B9-9163-E111100BA365 (syncValue: yVHsYkwoYOOiPS81MeVdIaw,FzQ5JmxXh)'
2017-07-21 06:39:13 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "68B8CE8A-2484-44B9-9163-E111100BA365", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "68B8CE8A-2484-44B9-9163-E111100BA365", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:68B8CE8A-2484-44B9-9163-E1111,00BA365:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-21 06:39:13 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 ,0,6:39:13 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:06CC9300-6053-4EA1-8322-38AA391E12D9:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F03F61F2-0A23-48D5-9D1D-1B2D0F73AAB6
[ThaliCore] Advertiser: session connected Peer(uuid: "CF64E8D0-156A-46BC-86D9-00A60E9CC36C", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:F03F61F2-0A23-48D5-9D1D-1B2D0F73AAB6 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:68B8CE8A-2484-44B9-9163-E111100BA365:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:68B8CE8A-2484-44B9-9163-E111100BA365:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:68B8CE8A-2484-44B9-9163-E111100BA365:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "68B8CE8A-2484-44B9-9163-E111100BA365", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:55244
2017-07-21 06:39:16 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"yVHsYkwoYOOiPS81MeVdIawFzQ5JmxXh",,"error":null,"portNumber":55244}'
2017-07-21 06:39:16 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'yVHsYkwoYOOiPS81MeVdIawFzQ5JmxXh', error: 'null', listeningPort: '55244''
[ThaliCore] Session.session(_:didReceiveCertificate,:fromPeer:certificateHandler:) peer:F03F61F2-0A23-48D5-9D1D-1B2D0F73AAB6
Connecting to the localhost:55244
Connecting to the localhost:55244
Connecting to the localhost:55244
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,Connected to the localhost:55244
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] Session.startOutputStream(with:) peer:68B8CE8A-2484-44B9-9163-E111100BA365:0
Connected to the localhost:55244
,Connected to the localhost:55244
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:68B8CE8A-2484-44B9-9163-E111100BA365:0
,[ThaliCore] Session.startOutputStream(with:) peer:68B8CE8A-2484-44B9-9163-E111100BA365:0
[ThaliCore] Session.session(_:peer:didChange:) peer:F03F61F2-0A23-48D5-9D1D-1B2D0F73AAB6 state: connecting -> connected
[ThaliCore] Session.session(_:didReceive:with,Name:fromPeer:) peer:68B8CE8A-2484-44B9-9163-E111100BA365:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2 [1, 2]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:68B8CE8A-2484-44B9-9163-E111100BA365:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3 [1, 2, 3]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:68B8CE8A-2484-44B9-9163-E111100BA365:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4 [1, 2, 3, 4]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F03F61F2-0A23-48D5-9D1D-1B2D0F73AAB6
[ThaliCore] Session.startOutputStream(with:) peer:F03F61F2-0A23-48D5-9D1D-1B2D0F73AAB6
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5, [1, 2, 3, 4, 5]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F03F61F2-0A23-48D5-9D1D-1B2D0F73AAB6
[ThaliCore] Session.startOutputStream(with:) peer:F03F61F2-0A23-48D5-9D1D-1B2D0F73,AAB6
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6 [1, 2, 3, 4, 5, 6]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F03F61F2-0A23-48D5-9D1D-1B2D0F73AAB6
[ThaliCore] Session.startOutputStream(with:) peer:F03F61F2-0A23-48D5-9D1D-1B2D0F73AAB6
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7 [1, 2, 3, 4, 5, 6, 7]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,ok 91 correct string length
,2017-07-21 06:39:16 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 92 correct string length
,2017-07-21 06:39:16 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 93 correct string length
,2017-07-21 06:39:16 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,2017-07-21 06:39:16 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-21 06:39:16 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-21 06:39:16 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-21 06:39:16 - DEBUG testThaliMobileNative: 'Server received (14235 bytes):'
,2017-07-21 06:39:16 - DEBUG testThaliMobileNative: 'Server received (2149 bytes):'
,2017-07-21 06:39:16 - DEBUG testThaliMobileNative: 'Server received all data: GNHud1Llji4FG9404Iadv1ok1ZcJGrL0A02nIo7wQaYE0XaFVJx9q1YMwQO7sBh9eckVvPjG4NE44xBpkQz3PhJrKiYOQ3EhoIKDWfDJ0hivYRWEaDapfH3E7JlMbFMSvwVMF4IzvYMlu87kjS4SznDHSkchyZujLuch4qpRhu0uqWVYft,KHbaK6KDUDHbLuJJmhxpSyw8XwbSt6nexMIyKRzD2wymzJy8xMUGfR1lFH46cKa5mfXMcV32IC4vshILx91Q05cX0mIy4tCIF8KHgSM6zcSg1VroZlQzCMGyGMy3hW0DTxXqMokAdrbzMbIIHuSLyb3GPXncG33wa01ZbBFwNKoWXhGy70KIkgB5YUXyEsqIG8J0tQUVsh6kbdJFUtkwtyQPaj2BJ7rNdJro44j0txSWMa1dfYdWlIaFvrRtIkWX,gzd5O2G1hKT4IuTH7nTijYxEJuR2f1MisBfPl7HMtdsPPPkVTQZuQhG2gNI8rVi17F51L0AzN5JW99XZ9gwYHeHKfowse68nuwLKWchEGcXkEtk8Dtxz0q2cjlVqayPxviWS1NyXh25oXIHhwGcZuwPkhcC6cvZcOQMvV9y6sWro5PwX4fxirq79vhoJjtynqqckPumwr78vh07P4ugnsdt9XUVERGGl1updvIwtuVtcsb9SIHFMPt2kVFfEFbWh,VbVcn62qG0W2oh2ngyDzTzYJPKfzu5APMdh508NMtC1za4QjXExRI5COuutf9Ohr4LAe0F5aBIOtpeTHvDse9OlfmgGdBJdsn7IgNysYCiHshWM9KsEQqLBq5y0QsV0ZUuXLL95tpqCGqxXQvQRZ3S0IDzztBjydlbuIkuAJ0GFbnQGw0LtyzJ0XJ5MadWPfAdfQ4nyvLdUpJQJfTTJlvz4dQCgPw3zzaZVBnXiRMnaq5tC0CMUFAxikv7DEkwy,V,ONl7vCCf9LvRFWZp4JgoJSK4uX3PttAZJw2jFiRfq9zQOwjDS4JteuW4QgsXSB87ZfTEsXCeEXuhm10NZERgx4Ghmwz1QBRIQMnvs9QwhCn6bR3xsQBlKaiY0qXyD7mBK3BWexhntiQmBogiZ8FAoSex9MHc9KO3mC840saHFhMlFhrNuFBcdQlGr6uboOHPMjXSm0TzCkmDvzceBxJAzo8QneBT5mSE7GUdwLGtHTF2YNeVCMKRU9R0VTS33EFN,E5JflKbV56Mfx39GtI50s8Ee6fDWg1lDMH2iTFndZY9f48r6FgVM6AwmcSYZFD61CkLP5iEEro4QlI4bhakqQALYh8YnjgbhX300S6DdYWr2kMV2bPEHC65YAVvI91F9HPkLmgl330pJwxCj5v47ym9mkpzE7ZSYl2UAiYuwaRaGQmTC7JrPkcbpjLdkUg8OwlJzoRSMPcXvr77EN2IbL4J99bstyvdWiSSTbl1FJGM1Oc4AwMkb7Ek32clib0cS,TVsUeKIk7069nr0ySmaJ1JJDUdyjkPPMBqhFg1dKDH2kx8rwti52D4937Cuhxv9Yrmof84Pwe8hEi1b8ktCLlowOulgACNthMghk0Z1uH73cgWsJxgwULvZwG8MDdpcFLFZpwbuZbrfvbmqUNKMqEc0slV7w2318OC5slElSUh0kHOVtE1aRUdTCcGrOh5638gpybIYIdVF7B8pE7CVwkR3OA6nAkkWCEwSVCEVXiFvmA9ZR3qaxvFWwqmZOwRDy,ZV7fZv645Bz2IzyxPuxenuQtxmih9dUp87ZKpZFYsyOUp7a5D7sfRI0S7BCZO9Dv0xXXvzBlrn4f4gmSmc8qUwzfPZI1lQX8JiL11PBbjY5XyGhu4y488OpMUnpNuDDfwh5nRT9dJ8Jblwyo2tUs0OoIUzGqKVkgEr5LmxHoybMNfPpQBqByhO9cYalFkcJ5E6WQK23ukNhFaCyYodEhHlD46cSTmQ1H79seUGv8TJGbCkb8UoXOVisZPl6bjgk,6,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,l,ix1U1aazBlPek2Huqti3tkK0c5rIzCtBYhzn5oQnq5FdmqAhGtW85yObYzhfDgPSNCM1pOP7yY0O16KCb6J4i3L8G676LX9lpAsDYgh8PbFTacRn3x62rtqNhKOkJxo4aboRUt9aQzfjb6BhMH33yLWhR3VOwqVEE6ZM1Q29U1gGaGLUaQRTM0F57cTRkYiiEgbe8gtOeG9wklwv60zdm5mONCFnVdXzL3ZqZCvessn4Ovh8IuLXeS2LQSvmQxWc,jYScmZOuxr2mv8dX6PoPptJHo96goh5oTWUinDE8DfIESEi7g2dhvyd80RaAQw10By884UCZpHf3YMrJ9mqgOIZHIOK119waTKLEAFzwMT2wgiBLviIRc0gOwiZDyZKceIE8t2SPa4T7JrIVD1aqmm5RFcKrT4JZVYNULudXcVcAfAwTzKEwxp7q7isPUqzWSS604aNqzCTXQXIQIuVHJ30BZ10Cb8HvkSVA7Y2cuEByI8H72M1qHUZUG3jnGVyw,D5a8xNJ6MTSRsJoTqrsINNj4mKs3iTIp06qGsWX1PLYyvmvPcYxbz1Gnz0NSy2BAu0luMQYJ3zJLnyLvtK4Es9tltJD5HZL7iFcmlBjabbFgQ7SGVOQxnYdZCw8u9FjVHloudra3OmPygnaWBtXknCTAdQQwHZmC0vZVZPxx10kjc2VU1GnWrkBLKr6W2TckSVA6pfFjw9oj48ghDgnWZqNdeMcZjyVi0f5CARkXlE4G5YEz1X5vM0CJJhIPrCiL,TAowKkS0e06hOocIxl4zvKUH1BIOO76R6JSUuG3hP4cUkwXVtktDCICC99RfazeeGrETi8vQe6KrXR4Nwyl2o2jvUmvl41gMQs5Ito7ETPxy3q3hTknJ8v44Pn3mC5w1nyEi0mK3TmHhyxxwJkGS4PN4vVQRPPRIMe9DDo5oO4I6u0pUtBY3czXQF4DzDpWcSWcgfbXglx9wszdTElaQLFLaK82z86g7D7v1oJIbnnU8yMAmADqX2anW3qNa8FtC,o55TRpfaJa603jyWJztrSQayNYMaXlRrMpFEAPA7223kuo5ioSdttRDZxZMPTux96OOkxaXceQPFh8x2rKYxuPXgZCJnlKjfh68wOysCxGNSbfrj8A0dPKZa1DAEPCupqhOTnZruR0BtQ7NUNwulc21IddRrblYSM0QVRn1OQGQALm1Enn5p7kCgmXJK06ugp4SswmkI8B2vIxwI8qLgNL0ajyvxF5hUg3rI0IMk2N8GHg3OoyEEGzLNIONE8mMr,I37Urkl5tAllO8Cq1HNKGsRPQSv7GyB59gcIuwGAzLKHD0yMVOCjlgN5b1OvoYwxtnBfjwdJpiEf3SQcizUX2UPVniGGenXjaCKNeoemOtizybKkQQtf0f5nIYf4xW0xFGDyURiedjLm8cC5bEEVGvSlhv8PMoXOA0PBAq2UrZftg1d1lJAI3YdqRrhn9VUgmiO2Wu974sZcSQrUdsWyWMsY47OHo7xdQhF6LNm1UOpWyHjLPu6TWfgHoWUciO2j,GbgRBketYs5CQU7suw1YmGGU0mKyj3Ed9uWY0Ra9G4jTfVL70i9sIa53zG68e9L5YyhDGLchJino11RHjQlZL96mKGKEiQ3V8Q9VjcdXp9OiXjNz69UhIynmjdLVdjZYfPr98Keo2vWG89ZMPL4w4Qa6t2oKeAzgzpY5cVc8iuhSHLik8zBV7Nzs3EdhqGBPd3AaCfDl4nUI3OKinpu83gdraBDtdVarQ8kbtaIGvaPmeRvODmRN8VT3hOivMmeZ,NquNICvjl6hKMnu5Zr12DR0RDvHVSJb0hMwyB0QSBezcfYG9LaIJYg02VHGlraOvIJ3TqgyfAF6LtXuaUNDkMd2BDAJZv1J4OmPDhIhKOAt2b1FIPFKXVdkt9pyjHBCwhKnxqsDKU5VIVIEfTs1ua8idVWd3brPaVYeQ6xZC8XP2icV3eKLgNBrmGBC4eBGkoTICJKIyQ0FJl7NpHFvW77NaepU1cLq2vNOISFAvwyBKMde9C4krXBdKoo6S734,q,yLoBiiITfMa7elPiiTikCqSJKVfhC8u1Mb0eMhLE4zI2wkcetQ2kasA6ykDY8NQwg45mXDIeNRh22l7y8IFnZfFwubTJtkLlvyLFLd3ywJfeX8pJnyrdSQN31dRfwoXbwpNbj4WdtrQBxndaDKBJsyQZohxyRjyA0vgY9khIGIl6Se8ztTEtDb48eOmPoaL00DaIrnot9RsT93lptBnDG0GzlTTZ8FtPwAJ9dvCC2bn9ek0S50P4qpJuL0I7MRMr,cVSar8yrognKTkgvloI4VuRx5uPdTNEU1OC4akmJGwBonn2sWsdQB9nlV54IKN9qBGuopkCwzUd3ySLbiE6ST2aAgxPeDEahEeNJVSGkCsC7C5XwpCpifhvSHcrdch1RK23vO3aW2kuV6eQ7CUuNidS9pT2fRzYgtyycbUOmx2KpdNWy6FwdxVHEwkiRtMLDqVOEfok11Dm2JJlfSsadvrYYVv4ozdaR5u2i42Bx5HPvWjYhliG2UB1Lq4X8T4NURStdk47kTNpBKMjciGYxcbWDh9x9c4FhUJhhswk5LmzhBD0rRqHUz7bbAWx655HMQwQZFOMdYPOCBqzPQD8VaTzVe095i5LjtZRH79yTZ7sY0JUBIvNhnrT2244LJ6gYi55goZ1ifNIg0Isbl7zuDCaXULZCn4lJFr3yNcKBvvfxoC72SHvIaSLwWMaMDHdRs6GWYm3VPqNhvUuXiJBMKEYSob3g0PRqGiZvymlymNF7JLgsWoEM931tWV4ZeejK,cVaGM9lEtxciULhfjLaYTKBzwFDkR19DHkLvzoXQTEdtKezeQ89FPrHXwzJxF0zbzBrfeYSzHpQ6GU2YsSBxmGWvsNVgeSP8GBlaVd0PzbQ831xA4liy7YLw07cDRjHwclKIveO2pDgBtawzZbw67txUdFm0dMQ4leDlMtW8ST3AnLCw3SzalwD4DAVkhlIuEW0b9WqTkcKe4vMsuO6RU7MEutrS5lGqaHpNQTIUCLs53hZZtCPEUXjkSYAR3Qf,1,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,Y,kTCTwaAezl3ArKCKxVKxCPU6WFOiWCvbuGzZ82RLEFYDhCpXI2H3xklP7kiDoawR6DnRCwjgtDP3DVWwuUkVEjv2qe2Us5Eo4Zjsc60cT1YQBpZ10WYphUA1JfJU0ulGWFlKJTm7akYSShs9jQHMTz2SzdKKan1vxjX9KXzIimeMWY67vGvGPw58XRyyGCHZ3KkUARI7efyM4qnthNDEVbtFOgV4bvtx9oAouU9ngp0vEtOVCKRQ7w77R69lSctIADWmXNDepvRyqp7wf9FTy6BP1Kh0Js9vWRIxV9NndsM2PJNFMqWA8Y9QLrSSdz0r3F3oeyEuz0EHkbCLiwNFX2xOFefccoUSISRzGVrFM8tshP33Zet2lSBM83sH4K71quMEw1GFH4rM50FxDQZVP3BaK5MNQAb4O1f585aORLaW8evly6BGZpjFzCym8A9ijyTuIhalMt5fDTTKRIwtlGKqxR89lvFIALcXxz2MTqHpsa0xWbHylvrURh8cQ9mm,MbYJl9zFujWNy9jX4zYPS0jPDYAGrFS2rrNP9SbQkekdT5ewRf0LRESAGRHf7MhZ5V71pIOvvElmBPKlkqYpLfzIhHrHusuGcTGQn16827wv2UPsn9UxXL31iodYcZwnTtywJd9LUEWy24K212WG9sa1v8hFBUlVtDP1z78nVf7WzOqtEYKprMNUpfHt4Jzz4DXS3MvQcgZW5nXM1FJbEc2F50AAQoaqt8EBtCiKF8gUYsB24B3x0uqvjEHKoUbi,Ki2bolxhQqT95eJlnP7enVUQyVw2gO0CDucMXQJbW9XlzAi1rLmZORLTJZIcVJlcrIt242yn0niYEIImpJkQNFkF3qJWRiAbQbeOHNukmls71Ax9zYMhLLejv08bcesaaxMVHRGwhKE8P4QNwbGCKEBrUWiDLK6O1Uusw91tOPM4782XEpDFlm69PPbjSssmbYCe1NpF6pQDtWZWix47YZZERQ3tQhfocDaUBZp9Y7ecwFviys2W7boxX3HCm1O,y,ai3paBOFSFLu7Aj41u7ZZIr00o01htw918mxytZgWex0zaIdBtRcROOaU9qRfmX1snfbxn9sRqlF38YOHT5O54dE6aueoJ0aU9JJpKERaVqt4f5HlxyRcsjofGd3e1TXYOB2xLfKcjg0fiASmv9EtAEkJ4MpVynQedKjFXcJgUdIiyMVCUMwb97V8BJFoIhX6MF9Kbn1ZOBRrYcR7MWL0TqtanDVtELxbJdrYgwn4A72FsQtB9r6vLnai11fmBmS,xRmkDumNlYeg0U3y7FndeEoS26qgo47VIue6dfGqxMKwA74eUT7DJyg9JoYvhefsDResRjqFros9WiCBXWCLKLDBDNVLSDud5Rch5rvAKsOFVZM8sEHd0OxvzbBd5KSrovAsmIH1ado0WVBjW7OJ1pdhLhUSurKOs8RECNur97M50P2CVOc5cNPw58x6PqngZhjds2LBpUHpj75TiXyOI6Org4K8TCmpVcOngyJpaPmejuuFjxEE8m4I0l39r909,rlhBEQ8idigHxAqktEFjeAxbzuyou18mcMhLaaTirWUl6yevwMgT9EW1sVceLV5E1rBHEdszGwlDRMuctzSK5kTGb2u9vNuXI6ZyYknaUDKGx4MBviGIzo2ON3loTynGheLeWUQPnDA0JkllxMaDdi4yvhjUYKl25PEj9rN8lLwsZOs23QDXmdF6jPj599fy2LS3ox2CFeIIOtGTbFnMX5ggqOT7KJPWnjIAoYFwNIqd4397XaaFn7YlB1JrvuqQ,Idu0BDdZN3F8WVHonlsr3WD23QMViaNVNHnLtBg7rEhO8M5Pfx3vbQKtJQjAcR1qPQ2WnlfOuDLz1CdCMM1LNE0DX9FFkrCjW9ok4Y8PEdlu9dudxURD49qPhKLBbbbFVlDiDPwWv4z3CVM8tSduZktFluAqgR2cAW2DXujc0a5rrFs1oLSP165ekpZ3upK4LE5LFQiq15m5SwUwWC9xn7vSSyXqlNYsLQRFGJdyJCMVW6lVAwHSkDCt7HXPFjJH,qZB2aFVw7lhwV10WJnebw66SaQGjS1quns94SfhwTzO8NmukoMZEM8dXdwsKurKqSE0WFNeKdZ08pbJtijuv3CLCpWOkEq35TP6nyUm7sK9M2r7RmcoTLYtYrZXEjWZP53xtz8hLTRo686C9zPkGLmaB5QbzMboI8nEdMuhTH64vW0ONYg0vYRSxQlOYAx8l0W6rbExt28nT2KlCCQ7Rpl8CEC22k6TbSOmmTmFDBF3KhBMoBu56BIgRlZ3Zi7sU,SHc5JTBrMFG9EKIHB6O0ufBzcMkz1sNKRWHCwpA7yOJSYrNlwDn1nTxVC7MO6eGJFikoo8DkdxxVxtnIXHXTvTxTizOFyAKJOnBRQlL7Ytfuy4kfpGeSClkoBT24VoVLirCdAvpZDXgAej59y4EDpAptcEWgRvFBXz397nS8noz85cSvI3HzQta557GZONHsQQZZWYuFpCI5uWS7HKULo6wm1BzkYnsEN8V74tS5pF7o7QwPgSseVdbIDkgsvV0g,TK6mtlZa0yVZc6lQ3Kb7mPVYQfTfrGc03bYyZGmG7njxdPIpHW4LlTxHNLipRzeFL64X30GnXHzPm6f5pUWzwqfxJUluzLPcLDb9J1dAbfAJLSY3gwftpT879YY2quOpJAW2CZzULxmgfcIK6FYGDfOWNz4ezdkp0Px2wbaErnsMVRR0t1RW39rz36EOxVDw3Y4lxpZ9kcSusT3WnPN77YHVpWU8LI2BIkXIJJJ0a0uxhDwRPujMKeGC6gCK2E1J,BixsUWfIIZX4ni1oMFeJuo6bhgdjYbWGYPmV7XLYnIElYzNvrh0Sqj5BAjqJcEOdyXhiRbfqzrQqvKwAZD5cWKESylbYEALj4rfUgyO2u5IiVx9M4L0PJeY9uCXFwqEFH8TnO7Vc68a3VsbYi5d4dWFtv4ayqeeNxpN6MIRCVD9ULhKCEj4LhIqB7dUeHzSPkTBJxm4i0fHtd9VwCwNuBcFFbPKsCCja0cz9w4yvKyx5Mz9jG095hB2nMMoP5yZ,w,tIoX1LgXjcthQcZZVnhL3MUZQ38ZRn1xVBiltBFMja1ScGXSfNzqHnU8zTjQvsLrBxoAiSp8uSMPtwzuzdTU1Eqe5mOB1jN99rD9RCvSKvDeXwM13bhAlvePSjr9MkZoclziezXUIggn16NY0OK19yONFVIdODj446B0YdEd2DPxtyLmmY6sRYjySXgQHBVAt6X3k2gX8K0YYmcZAEZmDbZ4J1js3mpa0SF4AFos5mBocsgItGta81U5UA9QFWXm,IBWfXmJF536JgNvyx84J6GlAxwWYmo4trUEWsxU1Z1DbWU0UmNm6UDmEUHus5sVVbfXR1IaazhkKhA8ucp4kh75w6dYR5IoQ6VPbAiy61QMflAadyaLepzL6DH4colwiQbECmWx8BaavC6M2UOzckEKhmJhVpGwef3R0XRzIerRN9G3mvXtM3wZtlN6QytFesGLxESeNayuR56EET7NjsovW9ib60PBaG44KSwHN9Q27KgWqCFDFWA5TNCNOgpOk,iotPsT0KJRarryfKCtDzOq1EcaQtdTY4huHhTONQD3Ggday1mjMTYem2CASKbj17XQy4MxsEUzBk6MpnGaj8HkT3AX8VA4QTDGd5BCrAxu7IaMwxMttswIh0YN8ACyy3ul0KPZ2DmbXyK8DJBGQ4271meRL2Z5lVV4RPKwsVgpLOfEvJKHfpAPgMQaMeVNlRhcTy4aldPkef6SwBV9IliSJ5k23hsNFXuK9AwDpyxskbNxHxP8knOv0l2jXMsb4w,ruQuxNBVXTbmtTJDqVEx5jZGj1mEyRq1HIW7DfXIL9nMROQTx4y2wamZDgm7U6DphLE1TBecjfpUVs8cUmEy3XYzcacFGT9QYO4pKZPzceWVAAhiob4LZDhmOCU9jj5FUODRGI0LhNb8muFxlqN9o5KifFYw9g4KuzOy0O51LtNUybgs4Slb59xGoPejNC4TLeonu4PdtC66I7OsTINpyqVyNpgj58iRdINGvmGJ8hPbBU0iClRRflxfChd1GaE,D,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,7,CtB1n7PTP5UW0jN1QYIvIOmtAfV8a7iygQCjijb0IQUf604nLeFjNCjLAPku2Q3OGsrUev1e5uakgLVUocmXnT5DwN3wzdim3bXSEYSd6kMR7roaHmHCADCDgD1MROXGOiTJkbmU45Oell9nifqdWYIAZhXSjm6mmTny9qJsUEo9svfc6uC0nAG2CpPBqHfHIfe2nOCDYe6cVjZBDw8ZvRhQDMUa0irCNoTcYv1ljkENCtdeLp9tXbCOmKrsNSZU,yHhLVmUg7O5XieQAFSj4GlsOkG3o0pd1epmd1U8pI5WrcOwFJHoLkipxwWNNqShQgewJJpITdAvGdjuRlDnAbictpDI4moOLz12tKdvOs2qJzytgFfnjuJ6iOFnSpXNT2a9tdycXdbJTA6K5DstllGfvoqqAjlLIWaIqDdFPQMPfJ2c2UuocZyEtPsLvmwlKr3f02z42FP5x6GgXblKoB66cRgXM0sEiii1BRRf2CB4Tgpygi2elGWQhHTmvVeVZ,NWU6TuhMtzDnfqUQWvTsaxlTglOtTEYDjEtUZccAEq697i4QVEanAGYPvG7ElqKGaSa8srQFmaglBfDR1OUqtJW6UCeCJDv7U5X9HVyHcT7FJXuz5P5bFVq3or0k5Qno6AmcTgyXeEwd4dfEE1ojsDyBzF3zBrTAHeoYmEQnN1ehdUxov2VNFkunjAaDVhJqNX9L6Sg5B26jf0gkNR8rMYFvB0hp4Wa0UAZSmedHR90cvTuDbCrF89xRNM9widV4,7R8GlYXCgf9TopOG9lNdliH9y4HqmLwbe6NAGOQaNnxMjt1bw1bAyCo4Qh0uCZlw78upFrsQZN2lPb5vHJmTxk3SDxDkWKm1zKdmRHrdDN5UNmcB1GHblKZ2bHmPxP7jAOnfs1x05nmY2LQZI6PzDIGwVoFx7FplyvVelhvIbtEmYYm8yBP4thQgbDNVQDohgHau0ZJ74ypqa1vkmEdCLjE2oCzZdhQy9dxEHVoccdAbCPjmqBOgIZdiehuMQkm,l,IsCHkGkKQkaraviqSpAt4LE4Rc2VIKO9GZD6y0F8VuvGXSPzyfwOWjc6hN6cMvd72AjKgj5HOKoNon'
,2017-07-21 06:39:16 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-21 06:39:16 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-21 06:39:16 - DEBUG testThaliMobileNative: 'Server received (10950 bytes):'
,2017-07-21 06:39:16 - DEBUG testThaliMobileNative: 'Server received (5434 bytes):'
,2017-07-21 06:39:16 - DEBUG testThaliMobileNative: 'Server received all data: 1yVl3ofUHJj0QDcqi0XqQbRhY65aGOymCZVL1qfLAOaVXXEB1apD5Fa4QOGVkFJtMawobtESAy3LcFloL72FMsHdK0l0i0FNqQZTUdfBJf8MZKuFleJncH3KHkRtw4O9pZfpqNDzxjQa379ETiXCwUsFIfNLDrxZhRYA4QeLaFGRb5940B,nbElcsLh46TKyrTGVsZzGjfKHS8x08nemIOReZO1TZFNk0Xdie98IiptT83hlNdYkWmMoxhVZEfFduTq7u3L9pFSkVWaYGCxvvp2Rdl8KLLSOmCTMRYZ9ABhGotZgnEIeNUvOWkixv5pY3IwXrPLVK6018CRNDEHD39zebmiewF5w0av8QB26k9cokKODDceGMHlU0saKCm5lguZjaaNMYIZwJ4HSotZ4ry0iVRZJQPeRToFEI7hifdlPysC75NP,sKaqSbnmLMLahPUcxs0yS3waMmjQxPc5kEDU8gnuBJlyaw3laBv9SvmMpAaaWxgiFEo1s2XrRU8D5jYcYkDDE6Yb0zCXWHzbB3a11v1mgtIEhMY6VYNv5pUlsl2ZB6vEJQTYG2XkvMhfDQwyvIZNWXsTv4RLZvvgjwkLNB0rUa7S6RKhO6zVr99UTIHjVWi7w18oeO0XuGcNmL8x1BhQ2DYo2iDYT9mkYuFvVrIgemqwCsqvPvxAcsa6UH9wsyJE,PQghMXEZ0rSVGpCEyMJZqjuSFjYbl8tl1mFyi0b4WptbRe1YQvhhHrmWkzIIbdMMiWxHyf8LTsfEwrMUPl57DYkuzRd3QMUpQ3VmHSEabZKbIp2Y12gKiVS2TdBatyneij8Vi5cfKt9z8k6Xitftikg8BwNVADq5XGgeXer9efL2WflRhMVXEF797NAoXgYBTojzODBZzTRHYGaakED9fEQSooH24NwwaoBwqx9MrK9jJmZG5iXxABJLXBkiuaGA,irIu6x8ZMJmwremrMjN0pOzqBw5Dnnxx77ppy7Y4HmgcuxOqff08HbvHzalwNGK3XpxvW1H5SxTiot2hGPwneHeD3L3SfiAW4g2Fd9MnTagAOPk8CxDX5ikIr9v3CmXZ06OG8nJicusu0GC63Z17tX7ct8LnwMvsrySEBYqK6aDYlG3BpXIMO0rOlrw71cCTDchwIuDN4I5Y0MEX4hqgetBpP7PJ7FDSS8uX5d4ZbTElISJHJPhTgjt9FtpaJNNG,KFUtqPjhAuHqyEEadszFaD32WIo9XP3gV1FagVCDYdduRO3DVofdY4tqtB96DgBkn35rUbFqLWgxBlNg19QuOTGxd5Qj47CD7hvXBxrrT5saL0j0Unh1TO1ypE68UqaIiA3VIaLoD2mrFmvRiIuxPdbrwAiuuZRo5anCwUbS5udA1YoMWwlpIovfDOoFQpTFsgBxfwV9S66K0AXogiuTXrHR81v2F2Kf42javiRKYclajFG802JjYPjTE1LFBLOr,xOGgy06U4Y9tMwDjRQyC983UV5HWdTQQtF85j1x42E6omR4aohE2Gwtu3K4ERMKQzaAV0HkX4UW7hlwIWg8EMZHEJ8QaWEMGhz01sPR4MMHTGCngFdKHY9sY6CjvquNakKrlRazYZIATJFcEPlGK3mmHJfv2k7k79Towj3oPiOFnZTMljaqu3dCpYbtP385Jb6ccdq9MIszqMr9VGwPRGGiFS1w1HFWad7dN5JNqAUWQTcKv3ZbiISFqqtdxTHuO,vXDgWXF1p1cfFuBDA9JyLvYkoA3vwJTMBAwK0LQC6VKTPDofoIZVSUa5Ez0vid8tUtSZE29w5ZyBek80JsRmAnOO7DHxKXz1TNyJ733Zrdvumk8FGsfeyJfsKtutPS5zt6dHj5imgujGD64rB4Fo7fGU4YxJbHluRFsozutOipy1FIAQGwUCsqSDqlIDoo4lR5i0so7rHcMf6Wsm0Idl7se9t02JlHSWBFo80HZq1mvnz3S4mviDbICPLVJMDOM,y,8auyIWj9TRkiIL1Axo6EDcDvitPNqWetPA3TASkED2R9eqeJCPTjYb3Hdx968QwO1OWjViO4fMUTpMf3oFkDMIjlJqVcy2iaIhF9a7oUYMd0waYNuDYNNb2hXK1XEcvywhKJOGCZ03WORtqINw4aJRHmox78l37pArIBoJ7iSB4I3HJEEbjwnOnzGb4SwqLMan1XRw5FECeQqnREsYbY9QYGQMNImTf0HTqcPl3i0l29QcROtg28qWucsZQ421Bn,C55a0GPTJ6Cz6jgfmieVhT0W167lUQcc3ZnSMv7Zd1Mgk6axiwOHLtryVTWkgl5XRReKacaqfmt0S2Sy3MtR6hrElxWV0R7iG4p79b0RRpweDW7Gyefd3DIWHBjAoVQjrXeMqxJnPmDkI6d18Bwf7jYYdeQYFDB9bF6r3gymw5SnzyD8hPq2HOeo0SYGDXHcmaYliCdPZR9OV0wxn7adT6FixxR5xIOZ73o4y3eKaNefI5XolsTYYuvQqtH5w7y9,sykUacnunx3WcJwG1ynRLKTtj3VgsmXSJQmkW0FzgPSHWO0yuDTHjYf6Tjj2NpWPwyh62CLx2aegoZaHOupmKglIgE8witTqQclO3AJDBwEHiYfmjt9Nsv5ObOYCRfGe1ZeVZLs8FbNK1vuLj2lqMvulnE4S1iIAvXDZ0aN8ni7BIVFt2e6lq54GjJVaiTg3vNRtNepZt7UqfaugiNGCjmMRpSNnNAlKP5ehdBsX8ZhTa5FAm36LAeLX5ovxS2jT,1MYsTAxxLFZM2LdubAe2iGhTIB0vSnXBLdzfZKMnWRgMRehmk7cvPnunhVF9T7qIjKqz8YOmvedobbdT7g3kG3VVVA0QAa2mexLO7QkuwlcusOcTVblNm4yV7Y2cgXJX3K4Rs5MsVbOP6UNiLg6zeIDLawldh5tBx8r0MKn9Ta3hcWUSEBAgsfBlfe2GZAeJCCB0V5oQYj7VgsYU1ygibwQY3J2MhEIzb1gMecjDb4iRfNFeKo4bKNWETm5NYQF,e,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,c,oUKKht3qoAcF4tWUqhslcpDifZyIfGL9rBsPJMghxIfwXkHOTPlj24QdonLbJTDXRAwQmdIgdd1bzEzDz57QOvZOGPdFy24yRqniF5FovWrsq0uETFWhfaNPRmnnWnphYYePFScF3ifpQ0IBBWhxzgBymBqntx8eDZ5aao4EWlYPOieGtBLOdfhJu5JMIv5lQ1zEOOjO6N8tC1v6RtPdQLnktFWAOLX4VSryKvUFI3pHE9LrIk7RDJvfa6z0Y3JI,6lPQy9kmX1VOVN1V1hRY9uF8aRZtyqxxbvG2snJnqfEcsZ5FT78tS4LXn2KpL7t5S6eiy2s5j8XVLGJBF8zid5fRUdKiLximgRFTkibIuIeabOWoKDYehz04hj4BPTMK8Vl08etCzJ5D826Ql7xFyjJTYqX56tHQkLYFwbGhpu3l4e9gY1mhWLkGsvvHJnocYeKCnrC4sGayH2zYhOdn1fGafGqOLatg1UI7GOAaLhn52hsaAoxfQppXWYM6xaB0,Blv1vDzHpFBfeTVvJ8mbNfcdkam4pgtw2ImweOXVWpQP3izoZtVJREXTW3mRlgsmmhNEYR1GCXX1Unu0d9gW2N6AHca0jB1Kbt9XRK1rQyDvXzfvU8A65hjvJ5mWDVKndUlRcJ3Fc1NjGtwxFxLddElJABit3EKqzLVgno56Q02BNUblvVEq1Jko2y4ZNIoYejqKYWQED9DrTPgV9SpGibHd5kmBCGYtzRzxRRElNdKC80z8fOIrXnHEGTYiyI81,HMSThW6vdqYrMZbepjMTCPoNBwzOx3jcdbEnQiXFcTk5kodazYaN5VDo1hYRLLSIyLuVei4NBzMdJNstdHkbiWdB6GGx7CYub52DPflH0qCRP0VDwYXtmgrntppdmLOgrTTzYtgx1WWcmZKHSV3429YvucwJZmXred8n4HnWXWLbP94wUnNh8K1R7doKd6CDNtuZUOUtJVvfGd7L18bI1tEf7XTAHtvVLtyKKt5CmPW4HOJXn9xqcWYjJ4EG8fr,L,B5unvbsFA6wrsFaN8MV4DrGX6gvjq0rM7a34AM0meDaNpZCOvR9LkycbV0uzt1cD3MjepvJJyylTNzitPYSQLUOfMhMm9wYumDedFnIZ3UJQb8xo2Oy4dbsGL5Rb63fac4V4xDOlmUafwjN4I9eRloN8MLr4WV1yvlPoj9Ka371sT9uj8T4oXcOQaTEZGXB853yPh5MyjllGMcAsURtYQpgnJqvek3cBdt5JQ6hxvbjhJXMsHPw65XqxS4qRS4Le,jTZvqg61UKzUMHAmcqyz04hHXE1DW57W1b34obJDsLEMmSBcnC5ZnuZ4OdBCbmyYVtSTTkUi3GWoBzzfb6CFpTxt6MkDNVgm3lLFlfJzwx00x2crsEaMhpiUW4WhLYDArZtOzll2r4YjljrqvTGC8yJ1rzYbzydqOJsuOlWXX6l5zGlmIH3UdsbI3znEbz6Yfw8LMmzHeaAIWu5fmL8b8Py3eBBXlBHc1sPhVyyA6W6sCglnEvB5P0vuUnbzSCBD,LUI48K1DA8CqpHGnQasFJxTE16jP2rD8mrqYJCh95OaJZX5lkCH0WaO6qpqlWVGzfJO8WsUbkuaeJe0idsjWzlEr0eSOA3DLX0cU1nFGbYgT0dDBpGEIx4wVVll72GG9NhtLdvxohJJfOJRC7RaUgS8rQYkWt2q2IhKnaT3YA5dvdC77caWmxEdTx3SU7nEzcRZwXGLcUZYcS90KDUtwumQXAYsMlNrrULYiQN2kyKaLHZyYNKpYc7spD7wlvnT7,aUEwNgqqiqTrVmVyyAAZEogVFwzXveKNEM38ItLSIw5PgKy46xFv6Xik2rtYTZ12I0xgqG55hlhQNVwoihSXX5AytGdZ9QzUgbOn30J7yAonmvbLNBNltnpwOIR39WPqS0pkH0u0jUyBob17UnWmM6HRXlOSMJWQUWEjLc3B5gPiXE9ERVRxWuPqN6KdyCI2RphCOKt1AFkbQuCi5784AZpn7OuhNROmUJsq0ka7A9iFhImDlvEwWHugLDeDUQL,q,Wepw2vBBfZXZHdJhGlrTxvzFaq0iIUou1BCEdW4tXNpaAfiy79fOq9TeaIFH8MC5m0Q7W9EbxsIS4Oinyk2GaqjaBMI0jqcIMIeyCancNidZfGbRNW2mWgcMFDNjzuBx4CIvhFm0BiL3NLfjYVTS9uzPeN0QigZFKFet401UUEe0BIJyr7jKrBYLEkg0F7TxsWAuNsC6vwxX6vfdqrScgBnbAiNb4tRTKEiKA86XauiTzlideCHoQXttxZJ9dquS,qmJF6DQkenJt3leeg3ON77wueMImmZC3zZJSGyVnu28CID81jelrpGTRl7wofPHmiWyWhtv6Y9yFTduJf427QbTRrYBYvj1XS5Jg2B566Znr43yC6dYpxOrU3bHVqgvc1cFK959PzkB3Yl3XRhYr2QxR4e02zpdqErLbGhiHktqZ1XN7Fy9AIuzPMSDURTRmZdDiseetnQha0cgbk1y4uqItuAIQDAHLjBc7bGVZV618w9SZMajQeoXBGoZn3FyX,94bDJRokKWORM2LPiwX4Q1iRkFZWhNzcdjtbrPF8We3VVWVyzUy1Vovanl2MPS7AWFnEbkuoxtRXV5n0a8fSqBKsBsKlbaVR8o0ngHDVUcY0QQjzHBX41U1AmW9sN7Jfepb7hWjju8oRakV08iNOP2EUuzG6yQtwgOcW9PhDMtPioJ1i524GdasOa3BX6BFhLk1CU2jrSBl1dNhNN0L1MMlr7adtCVqUgdxDy1EZCxjVCkSMyRyajjzYBkyHbvON,w3uEyjGwbJsQ1JgHeaBA0GOivZnwN5imNkzoUdjPYemtbmH3oRv2IJh4vUuOnQQM3UPw9qcqePPJnoZjI4rcQt0kTxiroXFhqAqDfcj8BmpolxdKKukUUyJDw0Uzci3Q9toLV9sGvXDtyYQ7wOUa9liKIXst8HJAKw87NltBeieSyN3TQxWX0aN00WbjbP6Y1GozocZANVjD6wA6rh6CY63ykD1rkaEOI1kDKF3LuFfgP1fCOhvftJWnm5J1GtY,j,141nDtt3mprgzh4qigSMKOH8oshjdstccxCtzVPIjCqGY6UrF8BRYAxMIkgWwEAvX4GhSWHjwFThYy4gg3gFYZVRn8PzY4AkTq7urKgFgeICHaZTIzti42kQm7tARAFsA7jSi4bFWYe178iWTWut8Pre8LTs4FMQqedcwnFZs9YbEuv70PshKYALrX34bT6knr4ivwvEN1K8CTPBcKRQBBIW8nXsloa5ggL0H7x2SgwuZ1q75AFzZZG6HAOtml2g,nbK0q6VWhFIj8ymBLykqJLceOby7ShS9vcIUg3u3YGo5zSFInf3p4QY7j5JM2sctBi47tUjLnTWoxhe6a0qjCbB82wMO4z8ak6XLR5LxfDZZOKwgrD9orC5vY2SIPnzhZhh9yrzYDREBnKzbG1lmBtRcIMskegJWF79RzIItl5G7MvATqSoI3igCS75LwXTff3EwiSVArfZyupjb5nxAqfn9CDvLoOz14OL3sGB6Mks0iSMa8XVhbF8oX37LucU0,VUi3fsTKs4lMFXQHxRxKzFZjSwOQDmOyfAh3ByMcZfHKv1ExUFd1ewtCqesk9qIa7f7rOjBxiLpr3rlDxeC2yzpw0BUaTbSBXSGa2YgURJY9YjvX1TWL9jlzgDmyoNiZorfcFSnDLvh3DQ7TLGEW7Wk3iyxZTnu232cJccAPNbH8E63a4WFJv5G9udLNrwX7wjAWKUJIRsILKsafqTQdbykJkrzrDNpV5u4HayIYE68HT5vKBAlyTvpCIF2xWweO,wgbHhPzVc6RP1Y4wnrgmn1AYHzVSivKGUUtZmc7I5aj54sOP4Zmx3aMFlPjOqkH0M9oh832W5AutGl9mkSHpPnfDR1c0O8J5xFrch9iYo5SE6XoKBHk5f3JQjmJ1fFhXojMGNKo7mEr3tDvG7c2NgWzkNaHgJiJ7BCBO6aR8uDdVwSRP5N8pnZGjQl6Y0PrtA6rihROtPGp8xMNaBPIx1X2nQuZwbBiy6gWgkrB1yvgGxL6CbtUQJ5zNo1gvppm,j,k0eMzvjNwfsAx5oCVTsophbPrsKSRVYNBvQCbPx2mVvVCNEScO3KV9XC7ORHzdr45mFHLMsZp2XDSGprPbICtpuUHCCvIgNO0PKOwV5gSC5V9kEa294KytjFOiS10ZlYftqUUcfZ0y3fcUiA1R95dIT6EwFn6flbEhhvaU5ma5mSVJCw6K6WAhKwKATLm1oP52DGsLQezlrMbLBMTcly4pZ8LkfaojQSu9SFP0wWpn9n72i8nKYhtwpBrCtqI8NZ,S7Abp0pe88XQXoJwOiK3xtfoK52nJsnC63SbaXCd21tRpEASJaShUUI4mJIFgvjCYb9n5rAqa9betQ9J7nesEmbIWlPzI13VN8JmLjiyrdvPJPiVBo6Zf4kEkZTLwhJKsngTiTKFFjxuzEgsRvh2a5F3oRgb1jJBQ66mA3WQQ3m9d7Anr6VhaOS7oIVjZzX4N9jsyjrRf8zErhvmi1M8YGKOEAliyWJvWj36CCPXaUHRswUAFbFRafquwF0LtmAK,Oz7mmGpzpv9Zn2ml7VSJpyoxa5QfkAmUOjAN78z6ScGgZ2Jm0iNYIgMCWM4cZdZOuzXnntuZgeGLlmZfz6EAhl6M5sO5niEWS4uGuXCd8zYFsN5ylEaJ2eJB6OZEoa1zjceMIZxtAan0qzHRa45HVudK5JhzM3qI1GFl3DDTya3hgPp9kFIcwyjKySUUvqja8QvxOw8hJLejARuziSjL46WBTwzt0K510FFluPyZ6SEkF9nYjfiZpLAsldIDAksN,oGsSRmhHXiW4BkiDi9Rt3uykl9XFIqANOxvaTisoP5az77Mf8eMWJtLwPx8dvaEigMTJgaxEJVJO2PKMBxwPenMbfZFSFrthh2ujTEmW9KQxAg2y4tGECNZCe5lEZHpQbmCe6HOhM2nA85X00vrFdWrmWYGmzgEJh1SfmzOHs6gnvN8bRfY8XQ2qIeT95dWkKCgblIuRfhbanr8QqQJcjmphnn9uPM1BodbzeC0RfDiEXk1B8cj8V1tcrHERIp6,t,4f72Pw9Ksj2mjaZYln8sy4IwkGj7TDuHGA8ZpeYe7f0yUflwHSE2dcXAfmWy7mr62VOaoKj6EUriUcSIBxsq2KzKr0sTbXNiHo1U4jyBblMdjLoYeR0AUeNH01p4HeyU9bKT6T4uOetMqWxR3Rpdh0g7aHUHp2B3IAoVmJGmvrFYOwhoCexwPv3mZwy1ZTq1Ysq6GyaLXgf4YCTfkV7zHnztxESCejQdoivdQS0sCyeTYi49X8J7tU13Oid6vsAL,7x5XMwnN97pp9ZFrfR8OxyBuIZVblnDt2aUNE1Sh3ErqqmFoDvfiDxNyZVDvM2paTroYYnxQk6csad1P5CAOfaMsQWOGsvQilPxdkRxOpRg4dBbC9BaOYnvPHLq9fWdjTB6RyMdISoeHipWqhYI5Gpkllv3QyPLO231Z0ep0SZPQoilC1YLQG7cYURQf0LWXOpMuIJ7hv8Zh7PHAbdVXSZS9HSzBVb3yZ0MWDtlhtbl2JpuZ7VopgjQNMvd3niJc,NK3QjuGEXi9l3ynU2uSqw0bM5V36UGc1llvIxW4Z50iQJgsUJg5daIhExz4SrO5DDuW1VGdz9Hy5kHRrLoQaPZLRv07n6nF0BLEhgDMID0MW9J5Tev46gu8eoOVaYzOWCMXLo0MHIKoWfFAnTrpMYLZLdEj40KeOyzm2PAJh56Gzn9j2MAVHCybPhUYAFhoccl5h8YXXveGS8PYaUV8knZUYYNwS2JTanSyqRQvjvGTBBxGorfLcnQXs6bA0JnMV,iXsL83V64tz3Niec68XCq0GVfG7q2dLBSRd5wvhHO5D59lfJLKbJAGGtCT1JoWrMMZYHfRue9qwcNG40LeLiVGT8MIkWJDwrDJha1NbY1MXg0jpqVrAo8GDcfeawDjXxxoWiShd2ZOMm6DJXA8rbRciURklWKQM3oOhf6ZCW4esAusQ1BXMh7HK30wtQryssS2YRoFAcUr4ymjRrdgOS2AfPmMZILzlnNLfATeota5pL30cWUv9zVuGlTD3vvhj,7,TOrdG8wguQSo1qveXbcY0UwWtokTuGvBELAgW3w3pukjnqZCvM7LnyY17aKJUWTcRbwnGfKIHnp773j6MzF7BoGNvoAYoaEkigl7x8gVq8rWSm8Iv73bqxQhW9CXQCxN89tUYs7vddVev9vZC0HfWFbpErnfvzxm57iqDTaVYRLwX5JpkgNe5CAs8NXwWeO0fireVoyKBXAoPQQy0RIYssyDJXQ04Hk2fIzHWE1PO1znDthpC4mZAS1w5I65F3U9,CgSaHiXyZTXsEiiLVEYbzKARCo2yoLxbu0I3SbI0w3HEotzkQoa1u91Oajf0ER5ukkAQI60JUNPrLzCqgvwrRDbbIZBQOVOshgmdYZ8uDVHhS95C2k5q4ocQnxoRUcSX77hSOCDFmc8dbyOPaL7g7zKlJjSOX5r5c0J3JrPAdKA0jQIpHNDYyNNmKQMgDKGICGcuin4zUQ7QxaX5elO2vqUN3D3JA48IkfxHAg1fvDsO5OjSyDFdCM6ooCoxkmhF,pGb8u9PA8jSVA4O8aPPuMh92nHU6GzRTJ0geCacE5aVgLhsQ994egVBIzJy8jYKBpsKOgXAyAOf5rESyTuBoTmTkvVC2HZnMggQl2bhMiRsYsggUUAh4qhaNSeELTEqQZIwf8IaiNdcfxm0PRyQE8X07inx4wSji2A6BE26hTVpr5A0xVvVvrDKrys4KrGIesiBNEuJmTmjiUN28PYNmUcRXquudyScZcFnIpyeu9PtrZwTUs58ynHzzOql0VRzi,tyreiVSpnCrlpLP6kKaT2J9gj0Obvd1dqNT97L9z75wBs6lXLxg5NgAiEjOJ0ansZXIoJXWdLn6nQLoynfbyskdO3pzU5sxT9Eqr5ggnVRgWvdIfrfMwAIQjZjjNGEoqUUYOG2yX17gdEmwFiMMAP9Kun8laYsYLWXtPtx2MabSnG8NqpjfZEgori1i1rVGVDxmYht9o12lWSTiBqhiREBzrqqUl1f9fHU3NLaCh2eWMOcoWTXk3jNbwGKP4RI8,BmWHUJ0PKzDuYsaFMqivt855T9fDaf7JsEvoiystVRBcPv8creXppCMGYMRpkT8rqJT8zTwlCtyUd896pD573pVnTLSeMWZvA2efesE7IaRdvEaUcDHozZo00tH5XzxJbDpuH2VDhHOlOgvOIY77BfclAQ3oBifF0xQKfwbHLnEEttejcleRpnIDI39H6p34EpZS7MOWjF2lASyo8yZfXXqvbHo1PDFPEBigtaJKJQER6PwJRl753EmCxJjKjqUW,svAovbMarzLUitb63IPjsup79O4NFEODxoBHMv6ClJG2bi9iujdgQgJrITO0s6ELhVNVIeY8Dfgb0Z3vi6PNgczd0iPRfRHExMm9pOnIB13t8BzvUdDmPTg7nULgP37an9puLMy9xllPzbk1ArWaPgFMXYlLm6xd5rKHehoBSbvjx4nqvAELYa3bNbLeLlStMgIhXteR72mM0vMV61b4128LOROeh1F5LBK7v7sbocvUGTckFu0rK2x84lCd6mOp,DXn8WSAk94aPkD3LlnwLt5vvqMB6ddPaq0117tqIWImWQpYZtRWWIypPcLJfCrFRQyPTXX6ZqZHMJqx1Kr5hrYdJF4IPVwFab2NYlMf7hh4TsU9tkOZu8RL53591jRs8r1JxfqpSKE7AkB07xn6lbXb0RSzvvXS5TGAGB7k2ESvYjNcqNcMySF8zgnN0Cg8M6PyfdYNafa0PydPEZSgKnarPWybZKvLnN7ed3tqN1hyhBYicE1JUT7m97K1mKfp7,CcoJQDFhEizmyg9sSdzIn4Fs3GQFg1BWLY0x5vQpBFmPjKDuazD3yuHGt6E1Z4fPkFMBbCX6e1mb1toY2KXI35LMT6k5vqGLKvz65CXuOLtsYtQmlzJeO4XiVn5Gx0aOtFEVaNDqg0m3EMqr9gwyJgfcKnly6G7xxNDs2FtTR9SPT0CIAUo122FfKImiz89cSboZAYKiy9AlaFUTINwnhvd52OmKOkY3Fw0ndmyjg4IU0Lgi7TRDAp4UNdXjS85,Q,aw8i3cORVdU5xgzaUQ7h9rjfM00ebltE6vy0rY33ZqAejNdEIPznMznUVC9aWYbCvEHRei2cjDOiGhm1e2Rcf3wt848lDsRXEYvt5fZHCZJ6EeTUsZcT0D20inVBSWgMxxM8Xy01vWGjOnbiLeBCMu3hnEsGcUbR7wGA5NVTaYO87lwvXP1bxFenzMUVvtW39iMjU7iJmh5vrbhuHbW8arEx4jSI05UiGrb95osdLYNOKJIl5Zk55GyzJ5m0YWmR,d0pE7PlA1EbLdm3VZs2SXAWfxgFdpnP8EkTlYVdlq042hL32ee1PornQ7h0RSdMc3AtnoatDVCTyzjqOuqJHSJyFXSW5ReWIfl2iGaG2MQ3nLvxRGY1kDjA574oN4kzRv8aG2YgSsOLiA1mm6g55PMAKq8m7vpx4mzQe2kOwnuUQUTkI1dP0gutRsBobJXtMZ2oyX5aLamNz8ONscyZnTRvZ0E71cshYDcBmlrkBtH0MNqe48ZV8JRXtoVU61956,HV5mJrowImUMseZE7DKESkRDNGl2JhSdlw02vBYTV7PViFupU1oK9H5FPCqvfOGxsgNHpP1MXwhlvN4yEkwq6GqeFTO9HBIP0zav7YDg5Npl6Lmbroqb8FMDp3XME31jTefhknzyEAgDF3MStf5S5BCcHvMDXUEUX6YbUoR1vh2IuAwHvjNbdn7lWU9MvaEjJDA4k2HeAlP88Yo0nHytWeY6YWmxzBqPVnhWp9f6Z1s5hU9XEPQkc3MIScCWvCph,TpTLc9Xf8toiydLGQd9WNmjNNziAJ3Fs7dtLFYhsQl57wzPlha23WV8FVu2GjgjdNhEy3g5W3x5p2zbJS85uQjM0h4tjFNH2VMLMckKsC8iu19gVL3nyqg37Ajw40FMGbvKk42vxNMbBKK2aYsBxeF9QzWXGVwfmYwNiRR7U2KUPeqRMqsYfXiq8wfLvNR8tjirW94aFyAU3Gc853WnD2cVQimSfjjIZrxgFc1w6nHoLA9vMiq1iveq8QUvDAqx,P,mrtsxXSFf8ZIXE01ln9b0z5npU8kbXtmPBWU29OX0brxVUx5nKdND64SwCOnOCQ8ptH1dbG34Vzh371UqrBfiQ7tgUExa8gk5MbcrUJ3eQA27hO6t2fZysGmPshIKCrUVOIHOakzA1AVbSjGN8MvrNzjIacPENe5xYhNPzLZ0sTBuDvpSusinQ0Lcv0wKu7fknTripO5yY0i3YlTbZq5uRwKG5PsDx9ywDJvDPnDWgcK6t5X1db9ida0RhKCrGCF,OpVqd8QyQYm6oTPssMNcRZVoiY8Usy1bmYvg1elcfD9sldNtpiV2SPp0fDUUqz2nIkBRbtzFZNZeFRTcs8h57RbCz1yEfhqavz5h3Q2rRUYYbIZejbd8CfY0WqkpgBBtgyANFU0s2UVsGWWVJO3eCD6zr4Au29odi62nr4HgjQrU6qCFk9LfNNVzolDjfMWkBym9bdCRQG2yi2drJRfaTV4Ts9rpa1ml6C9oOoMOa7rrdkvherArIUEcinpugDSm,vHBSK6HQ3Agjm7ZmLUHVfAU4CRJelu0z3323VyWWRpZ1xOw4RJ4SyyDXOWODJCO9FjhYTBxuSumxydrZqZjQlHXIOrVERBGazkdScW4ulyVFt7MiJzVGJPiydhKpOYsaepjXaJOSXTBx1Lo5OeO5uTSksbiekw0hltGPEVfTtCVQYP5rx7N1bxo1JsJIDV0YsYvJ3LP7tdGwxDFIJeRFj7CkATNSuRfZ1s4uvCwku7rAllq4szMRrTlSsyz28Ru2,NWXNJHMfrI2EduHYBfqKtJo0ovgjGz2SSacLLivSEJBTPNN0qGf43ASvvMdQWTvEkjkd0a09VDWdodwZ3gsKBoNXDjxKsXXBqWj8x8QGrJ4dbPJyg7RJpq2w21EKFO4SCuNM5iKEdyPu4zxS0BDd4hJzobW9zP94mhP1F2q80SvuozEdy20Xu5saKCqpnkBpQKlkx5p9nBxP0WqGdaMv9O4ZJRBcQlLUpIciqo1osDSZJKHWUrynXSgtQQTY4kT,Y,5Fr8fzpxPC0Ymd1kKCpjnDdUInArcgYFKjNzTSyA9YAC3TLTNv5SBUT7moACH03sKGQFN4ICoxsVgsDnqzhvty50wJfMAnv8fHZKwwRpBBSPuli0UVTabqzYPm6k1Ok21EruZSI1AHkFyDiiT98V5HVgMd8FTLcUrEnjufwztfpqQAxTyadBeXVsgjCtBuR8lL9U8gyTRG61YWFkC1LwYQpcrrwVxeaURyqWNsdlQFD8t5cVj5mjK3bnQ8cVGWqu,HTfPByvW4HgyeK7Ftp5auADFYBPKdSnm2VgKBEJ55JHG2EqjUjCMkj6B3oHSKUPzP5vcdJ2i52ejzKgs6FXNtghJqJdQYKlhu2m6rYzPklPYvoHZ5nBaR245j7yjsK0h5TKZE3A1eF5VjYZvT9Vf1UxTD8Z0K1gww2rwuQZYuZoPkUdTRaIVoL7hCjxh1N51fZmoYn4mYujR3Odn8S71RHlmBsockmpXvcjaBxvFoVQBrE5mzzut8FMxPL0C5LNx,mgIkVcniLqIymoelH6euNf8L3UPfYwEAdZvrLYaQ5cn5I7ROd1lPUXpup8OXHtVGAHxBO2coH5cR9VwOaC3UL5KjAhg1BbOeG9ZF8Xev5buVz07dCyrnkL19f8LdU2qBN5QTMBlFvw6FxwGF217eV2NVjB4XNsHvdoEGhqsbvrk5p0TEQOmus9vYongf4TRGD6UGNgylQWYmIMpf4rgqA7wTZuvS01uCpJfMs2zL21bXWZ7wMZFScUwRpEtSD0gS,vWy2GHxzFUDTSdmiCM3RRlhDrtfu3NreJ5cxUpn3t7tOzV1S4lvCiMu7POrfa3NZkkjItheoMe90Jsno1EOQ2rP0bwymmjY2ORq9NSNBFVM3xgj7CQ8HX4VXSboduhp25JwB3YnbEwQizfyz0tJtvrC8SMeM0Gzi9gFhR1CJ8Xla9c19l0BM1JpX1jQacXWpvp5GNrKsFPku0OxWbhotHzoqeWK6SQ93qYoPAV4c6kLGa2QhlgBbLr2NwMW45QVN,O5yJFdpnhMIRlLfVi59eGZJzjCYstGidAcrhQuJOls3G2Mk0ujuk80VR7oQCopada9693wRgb8orBdj'
,2017-07-21 06:39:16 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-21 06:39:16 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-21 06:39:17 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 06:39:17 - DEBUG testThaliMobileNative: 'Server received (13140 bytes):'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:2
[ThaliCore] Browser,Relay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:2
[ThaliCore] VirtualSocket.deinit vsID:2 [1, 3, 4, 5, 6, 7]
,2017-07-21 06:39:17 - DEBUG testThaliMobileNative: 'Server received (2149 bytes):'
,2017-07-21 06:39:17 - DEBUG testThaliMobileNative: 'Server received all data: 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,m,s4Rsbm9zL3lqnsNO0v0vIqJmfPuCn0A2qyK5mVvrCoXlyihZmPnDopb3ZQPdCyVYau06uvyV8vMPsSMwIdFRgSzGChm1hsMYpvmKwRrzRfOkLREprBJcS83eO2XsQMRcbeXshz9tYFl2EEUcd0ZFopDKWd5tIhVtvtXoq1YaPEHmdH3i547jJj9gEFmgIcUrCAE7XYdezBXHHnuVo2t0WyXzdN7az0MrACpZ8dz3IvoA4NVBM8rWhY3M1F1DMtpk,jX2uUqWevnrXvSb6jw5ULvxH3CuEnfz0qGH6gmVEzlh5QFH2YDhprToXrpmx17wRoXDor1ek87tPeA17TwneH3KAopXIgIRErH1AGGV0fnDuWOTIHqRKCknhfQsA54os8IAP5j6pWtPuQwWVbU8duVIZDF4UaSk9xEuCfrwf5kCKiHu62HTUyEXIcQqtQdulHcqLhgNaYpkjrbngnaUcVdP2muntmP05zURoKlHVL07I1gLdv3apa4gFkp4270tJ,KPqA1AyhKekAhq0RJsyS3rdx0xU7eOLI8H2Iwmycrhff6F4xwv7dNMYuPtiDOannS8nJTjELW6HQmsSAw0Gbkadsf9HRvE2emfRdrzIDtIEWe1361Q1yqy2tLAT36eEuf1cLnQfWx0yn64wY5UeMpABsVvNBRtgh9ojcXBjhXEhOleUYAVhohHdbODfcKgH25fxJY8a3Lcesk9AjeIA6I0FibKufxv2YBph0ECgKlJrlRG3Rj7g1RvgrQUV8sunY,8IWt1ofyPvDafttpcZtmvO6W2bd30ywHRQqGrJJtra7WRmq8rbd9XknLNI4Kx5bSv6Hq54457HzqjC11FdhYZf6OjxVfhUlkVO02GMgB2Akfavjw3ssBfe3K8bifJICh3LMu031lOSdmnyeuszuZrwWZAUOjeZ65mMI6cq3a5xrYIdBLaeSj8rstBK8W1EFaI6Xtp9KZIDEo4aINcp2uMYHFWHgfVDndHyM6ZFuETbQI2j6DD7datZbVd3Nbaij,H,jgxLUryZad13hg1yuvrF6mUnA0bGC4oUJYXn1UgLPo6ZwcMjsFy4RwdErKDFdzWuOsdg0P7w3ImibjmaSBCFxRkxU2WCGLjWrMOKPqwry4xDx099XioAN0hjQNCrHk3G2eThiOu76p8nFNPNOelyo8PrKgQ1Ihe7ciO159zFPSzLSY9CFAQHRrEsI5xqRRdKRr0Bdb4fmD3BKjSHwGhBkvAlA1HRsT2qM8bAw7JPmgqHFX2LF48yNDxLJNRXcPOU,IdM18lvFtPqYldWlBFCSRV21CH373YLe14BkXeOSyOUXOUQ1dIZOAVCkbtoGQJ3YalB8cOFfShSjuAiKLTdtoV7A6dSu7ZVCoKl8g94VDz0BDr3U3jAla15LwRiZCcMoLgBKRWasEwzDSe2xbrzumjW3pjCJMfNpf1wHN6AEY95hDQP1nlbfXD6UmnrngP9SGt9nYWtcBhGmNY6dJ21Q1Cu14NGQrHh0nRMiFWoY8CoeUcDJvUjrFsmMWbpNfIDl,k3hf46XLCjY2rSdcrQfhlYTlUMCQjJ5jQH3g2tsLz6UkXgiRObKau2dh9IlAtFr9qEGUeZHH66ZTPNrDhinTYPxTmwDRu3R8ElJ7f6iCPII4SVYRFX26YiwHRAiQOTksx6WcHKgvva3ZuZd0hzOrWOy7wfBTvNcZ616XyuZXYRb01UJDHWYOOKHa54lD8TxXileRG1VDSlzXBStl2vY1z8GteRjZaxlKM9wHA9dnIDO1HJMv7lQjyFhtFbFizepj,VB6vgbQLcbit2L9x9ahBehiUX6GEgPXjHmNYIyvUfdJCQRTtnHICnah7GRSez0RCWrVJL40rmrdQVGr8tOsAfxHMoZnZhi1MQrEP47YGwywkjkbpH0FLAwS8nr2olMAIpgRQumaEuwYZLs01o2PpImhlPkYd7xTY5jh3oRDQvHDmHvGWjKMcLByrOTxa74CcWnBnTSUMdPSRKqw8xw3fL74eKBYik5WCndiQ8Hscewi7qdCVKNGk42epn7DllOxv,HvWkwgUVMlXJarqzfaAUIZq01Dx6QYQZLStAEQ45PeN2vgxrQUjGeVSlK1ruwCQfrohfdQntDGX1DsAO3z'
,2017-07-21 06:39:17 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-21 06:39:17 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:3
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,ok 94 got the same data back
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:5
[ThaliCore] VirtualSocket.closeStreams() vsID:5
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:5
[ThaliCore] VirtualSocket.deinit vsID:5 [1, 3, 4, 6, 7]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,ok 95 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:4
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:4
[ThaliCore] VirtualSocket.deinit vsID:4 [1, 3, 6, 7]
,ok 96 got the same data back
,# teardown
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:6
[ThaliCore] VirtualSocket.closeStreams() vsID:6
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:6
[ThaliCore] VirtualSocket.deinit vsID:6 [1, 3, 7]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client, disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:7
[ThaliCore] VirtualSocket.closeStreams() vsID:7
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-21 06:39:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 06:39:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 06:39:17 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:39:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:CF64E8D0-156A-46BC-86D9-00A60E9CC36C
2017-07-21 06:39:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06,:,39:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:68B8CE8A-2484-44B9-9163-E111100BA365
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:55244
[ThaliCore] Session.disconnect() p,eer:68B8CE8A-2484-44B9-9163-E111100BA365:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:F03F61F2-0A23-48D5-9D1D-1B2D0F73AAB6 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "CF64E8D0-156A-46BC-86D9-00A60E9CC36C", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
,[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:F03F61F2-0A23-48D5-9D1D-1B2D0F73AAB6
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:68B8CE8A-2484-44B9-9163-E111100BA365:0
,2017-07-21 06:39:17 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 06:39:17 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 06:39:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:39:17 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:39:17 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:39:17 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:39:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:39:17 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data securely
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C5B3F0A4-79DB-4081-A9E4-DEF6058D0780", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:C5B3F0A4-79DB-4081-A9E4-DEF6058D0780
,2017-07-21 06:39:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 06:39:18 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 06:39:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 97 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:AEBD38CB-E634-459B-A288-A86890FA81FA
,[ThaliCore] Browser.startListening
,2017-07-21 06:39:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 06:39:18 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-21 06:39:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 98 Can call startListeningForAdvertisements without error
,[ThaliCore] Session.deinit peer:F03F61F2-0A23-48D5-9D1D-1B2D0F73AAB6
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F8950B91-FC0C-4B52-9139-38BC77A5B47C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F8950B91-FC0C-4B52-9139-38BC77A5B47C", generation: 0)
2017-07-21 06:39:18 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"F8950B91-FC0C-4B52-9139-38BC77A5B47C","generation":0}'
2017-07-21 06:39:18 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for F8950B91-FC0C-4B52-9139-38BC77A5B47C, (syncValue: EsDP5Vd4ngfxlsvUEFC9WIdGd25kG6Ux)'
2017-07-21 06:39:18 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F8950B91-FC0C-4B52-9139-38BC77A,5B47C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F8950B91-FC0C-4B52-9139-38BC77A5B47C", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected,:,) peer:F8950B91-FC0C-4B52-9139-38BC77A5B47C:0
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:68B8CE8A-2484-44B9-9163-E111100BA365:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "68B8CE8A-2484-44B9-9163-E111100BA365", generation: 0)
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-21 06:39:18 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable,":true,"peerIdentifier":"68B8CE8A-2484-44B9-9163-E111100BA365","generation":0}'
2017-07-21 06:39:18 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 06:39:18 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:68B8CE8A-2484-44B9-9163-E111100BA365:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "68B8CE8A-2484-44B9-9163-E111100BA365", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C5B3F0A4-79DB-4081-A9E4-DEF6058D0780:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C5B3F0A4-79DB-4081-A9E4-DEF6058D0780", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:09A4E702-E613-48D9-B9A2-3D033F105286:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "09A4E702-E613-48D9-B9A2-3D033F105286", generation: 0)
2017-07-21 06:39:19 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"09A4E702-E613-48D9-B9A2-3D033F105286","generation":0}'
2017-07-21 06:39:19 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 06:39:19 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:AD6E5E06-F813-4297-B2A5-EC52EB430D2A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "AD6E5E06-F813-4297-B2A5-EC52EB430D2A", g,eneration: 0)
2017-07-21 06:39:19 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"AD6E5E06-F813-4297-B2A5-EC52EB430D2A","generation":0}'
2017-07-21 06:39:19 - DEBUG thaliMobileNativeTestUtils: 'Already running ,t,est!'
2017-07-21 06:39:19 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 06:39:19 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:F8950B91-FC0C-4B52-9139-38BC77A5B47C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:F8,950B91-FC0C-4B52-9139-38BC77A5B47C:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "F8950B91-FC0C-4B52-9139-38BC77A5B47C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F,8950B91-FC0C-4B52-9139-38BC77A5B47C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F8950B91-FC0C-4B52-9139-38BC77A5B47C", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:F8950B91-FC0C-4B52-9139-38BC77A5B47C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:F8950B91-FC0C-4B52-9139-38BC77A5B47C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:F8950B91-FC0C-4B52-9139-38BC77A5B47C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:F8950B91-FC0C-4B52-9139-38BC77A5B47C:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "F8950B91-FC0C-4B52-9139-38BC77A5B47C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F,8950B91-FC0C-4B52-9139-38BC77A5B47C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F8950B91-FC0C-4B52-9139-38BC77A5B47C", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:F8950B91-FC0C-4B52-9139-38BC77A5B47C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:F8950B91-FC0C-4B52-9139-38BC77A5B47C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:F8950B91-FC0C-4B52-9139-38BC77A5B47C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:F8,950B91-FC0C-4B52-9139-38BC77A5B47C:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "F8950B91-FC0C-4B52-9139-38BC77A5B47C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F,8950B91-FC0C-4B52-9139-38BC77A5B47C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F8950B91-FC0C-4B52-9139-38BC77A5B47C", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:F8950B91-FC0C-4B52-9139-38BC77A5B47C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:F8950B91-FC0C-4B52-9139-38BC77A5B47C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:F8950B91-FC0C-4B52-9139-38BC77A5B47C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:F8,950B91-FC0C-4B52-9139-38BC77A5B47C:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "F8950B91-FC0C-4B52-9139-38BC77A5B47C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:F8950B91,-FC0C-4B52-9139-38BC77A5B47C error: max retries exceeded
2017-07-21 06:39:29 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"EsDP5Vd4ngfxlsvUEFC9WIdGd25kG6Ux","error":"Connection could not be established","portNumber":null}'
2017-0,7-21 06:39:29 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'EsDP5Vd4ngfxlsvUEFC9WIdGd25kG6Ux', error: 'Connection could not be established', listeningPort: '%s''
2017-07-21 06:39:29 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"F8950B91-FC0C-4B52-9139-38BC77A5B47C","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 06:39:29 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent, due to not being in started state'
2017-07-21 06:39:29 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"F8950B91-FC0C-4B52-9139-38BC77A5B47C","peerAvailable":true,"portNumber":null,"recreated":true}'
20,17-07-21 06:39:29 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 06:39:29 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-21 06:39:29 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 09A4E702-E613-48D9-B9A2-3D033F105286 (syncValue: NomPLix,LeG1sKLzrZz1eYXVevT9UMmvW)'
2017-07-21 06:39:29 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "09A4E702-E613-48D9-B9A2-3D033F105286", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "09A4E702-E613-48D9-B9A2-3D033F105286", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:09A4E702-E613,-48D9-B9A2-3D033F105286:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-21 06:39:29 - DEBUG thaliMobileNativeTestUtils: 'Already running tes,t,!'
2017-07-21 06:39:29 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:F8950B91-FC0C-4B52-9139-38BC77A5B47C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:44610784-A0DB-4F9D-93DA-CC727176B199
[ThaliCore] Advertiser: session connected Peer(uuid: "C5B3F0A4-79DB-4081-A9E4-DEF6058D0780", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:44610784-A0DB-4F9D-93DA-CC727176B199 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:09A4E702-E613-48D9-B9A2-3D033F105286:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:F8950B91-FC0C-4B52-9139-38BC77A5B47C:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "F8950B91-FC0C-4B52-9139-38BC77A5B47C", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:44610784-A0DB-4F9D-93DA-CC727176B199
,[ThaliCore] Session.session(_:peer:didChange:) peer:44610784-A0DB-4F9D-93DA-CC727176B199 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:44610784-A0DB-4F9D-93DA-CC727176B199
[ThaliCore] Session.startOutputStream(with:) peer:44610784-A0DB-4F9D-93DA-CC727176B199
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8, [1, 3, 7, 8]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,Server received psk id: psk-id
,2017-07-21 06:39:33 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
2017-07-21 06:39:33 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
2017-07-21 06:39:33 - DEBUG testThaliMobileNative: 'Server sends data bac,k to client (20 bytes): '
2017-07-21 06:39:33 - DEBUG testThaliMobileNative: 'Server data flushed'
2017-07-21 06:39:33 - DEBUG testThaliMobileNative: 'Server's socket stream finished'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:8
[ThaliCore] VirtualSocket.closeSt,reams() vsID:8
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:8
[ThaliCore] VirtualSocket.deinit vsID:8 [1, 3, 7]
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:09A4E702-E613-48D9-B9A2-3D033F105286:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:09A4E702-E613-48D9-B9A2-3D033F105286:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "09A4E702-E613-48D9-B9A2-3D033F105286", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:55266
2017-07-21 06:39:34 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"NomPLixLeG1sKLzrZz1eYXVevT9UMmvW",,"error":null,"portNumber":55266}'
2017-07-21 06:39:34 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'NomPLixLeG1sKLzrZz1eYXVevT9UMmvW', error: 'null', listeningPort: '55266''
Connecting to the localhost:55266
[ThaliCore] TCPL,istener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:09A4E702-E613-48D9-B9A2-3D033F105286:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:09A4E702-E613-48D9-B9A2-3D033F105286:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9 [1, 3, 7, 9]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,Connected to the localhost:55266
,2017-07-21 06:39:34 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-21 06:39:34 - DEBUG testThaliMobileNative: 'Client data flushed'
,ok 99 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:9
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:9
[ThaliCore] VirtualSocket.deinit vsID:9 [1, 3, 7]
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E2E75EAA-EE8C-4128-95FA-49BA0AE47618
[ThaliCore] Advertiser: session connected Peer(uuid: "C5B3F0A4-79DB-4081-A9E4-DEF6058D0780", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:E2E75EAA-EE8C-4128-95FA-49BA0AE47618 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:E2E75EAA-EE8C-4128-95FA-49BA0AE47618
,[ThaliCore] Session.session(_:peer:didChange:) peer:E2E75EAA-EE8C-4128-95FA-49BA0AE47618 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E2E75EAA-EE8C-4128-95FA-49BA0AE47618
[ThaliCore] Session.startOutputStream(with:) peer:E2E75EAA-EE8C-4128-95FA-49BA0AE47618
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:10 [1, 3, 7, 10]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,Server received psk id: psk-id
,2017-07-21 06:39:41 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
2017-07-21 06:39:41 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-21 06:39:41 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes): '
,2017-07-21 06:39:41 - DEBUG testThaliMobileNative: 'Server data flushed'
2017-07-21 06:39:41 - DEBUG testThaliMobileNative: 'Server's socket stream finished'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:10
[ThaliCore] VirtualSocket.closeStreams() vsID:10
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:10
,[ThaliCore] VirtualSocket.deinit vsID:10 [1, 3, 7]
,2017-07-21 06:39:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 06:39:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 06:39:41 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:39:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:C5B3F0A4-79DB-4081-A9E4-DEF6058D0780
,2017-07-21 06:39:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:39:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,[ThaliCore] BrowserManager.disconnect peer:09A4E702-E613-48D9-B9A2-3D033F105286
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:55266
[ThaliCore] Session.disconnect() p,eer:09A4E702-E613-48D9-B9A2-3D033F105286:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:E2E75EAA-EE8C-4128-95FA-49BA0AE47618 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "C5B3F0A4-79DB-4081-A9E4-DEF6058D0780", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:E2E75EAA-EE8C-4128-95FA-49BA0AE47618
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:09A4E702-E613-48D9-B9A2-3D033F105286:0
[ThaliCore] BrowserRelay.deinit
,2017-07-21 06:39:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 06:39:41 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 06:39:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:39:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:39:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:39:41 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:39:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:39:41 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:44610784-A0DB-4F9D-93DA-CC727176B199 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "C5B3F0A4-79DB-4081-A9E4-DEF6058D0780", generation: 0)
,# Can shift large amounts of data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "345FB200-0861-4889-93A7-1CE465A33780", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:345FB200-0861-4889-93A7-1CE465A33780
,2017-07-21 06:39:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 06:39:42 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:39:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 100 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:4BA51407-3670-434D-885C-F7F9855EAF16
[ThaliCore] Browser.startListening
,2017-07-21 06:39:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 06:39:42 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:39:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
ok 101 Can call startListeningForAdvertisements without error
,[ThaliCore] Session.deinit peer:E2E75EAA-EE8C-4128-95FA-49BA0AE47618
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:AD6E5E06-F813-4297-B2A5-EC52EB430D2A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "AD6E5E06-F813-4297-B2A5-EC52EB430D2A", generation: 0)
2017-07-21 06:39:43 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"AD6E5E06-F813-4297-B2A5-EC52EB430D2A","generation":0}'
2017-07-21 06:39:43 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for AD6E5E06-F813-4297-B2A5-EC52EB430D2A, (syncValue: X1prj2cgIOwlbSsV1uBtSmBRrGjez3Tu)'
2017-07-21 06:39:43 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "AD6E5E06-F813-4297-B2A5-EC52EB4,30D2A", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "AD6E5E06-F813-4297-B2A5-EC52EB430D2A", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected,:,) peer:AD6E5E06-F813-4297-B2A5-EC52EB430D2A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:345FB200-0861-4889-93A7-1CE465A33780:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "345FB200-0861-4889-93A7-1CE465A33780", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8EDCF724-AD07-4005-8DDC-A283D1F0F2FD:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8EDCF724-AD07-4005-8DDC-A283D1F0F2FD", generation: 0)
2017-07-21 06:39:43 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"8EDCF724-AD07-4005-8DDC-A283D1F0F2FD","generation":0}'
2017-07-21 06:39:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 06:39:43 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9B868A43-5BE8-46E6-9795-88F123A46132:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9B868A43-5BE8-46E6-9795-88F123A46132", generation: 0)
2017-07-21 06:39:44 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"9B868A43-5BE8-46E6-9795-88F123A46132","generation":0}'
2017-07-21 06:39:44 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 06:39:44 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-21 06:39:44 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:AD6E5E06-F813-4297-B2A5-EC52EB430D2A:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:AD,6E5E06-F813-4297-B2A5-EC52EB430D2A:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "AD6E5E06-F813-4297-B2A5-EC52EB430D2A", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A,D6E5E06-F813-4297-B2A5-EC52EB430D2A", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "AD6E5E06-F813-4297-B2A5-EC52EB430D2A", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:AD6E5E06-F813-4297-B2A5-EC52EB430D2A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:AD6E5E06-F813-4297-B2A5-EC52EB430D2A:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:AD6E5E06-F813-4297-B2A5-EC52EB430D2A:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:AD,6E5E06-F813-4297-B2A5-EC52EB430D2A:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "AD6E5E06-F813-4297-B2A5-EC52EB430D2A", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A,D6E5E06-F813-4297-B2A5-EC52EB430D2A", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "AD6E5E06-F813-4297-B2A5-EC52EB430D2A", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:AD6E5E06-F813-4297-B2A5-EC52EB430D2A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:AD6E5E06-F813-4297-B2A5-EC52EB430D2A:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:AD6E5E06-F813-4297-B2A5-EC52EB430D2A:0 state: notConnected -> notConnected
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2967B371-2142-4D39-8DDA-E8E4121588B4
[ThaliCore] Adve,rtiser: session connected Peer(uuid: "345FB200-0861-4889-93A7-1CE465A33780", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:2967B371-21,42-4D39-8DDA-E8E4121588B4 state: notConnected -> connecting
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:AD6E5E06-F813-4297-B2A5-EC52EB430D2A:0
[ThaliCore] Browser: session ,notConnected retry count #2 for Peer(uuid: "AD6E5E06-F813-4297-B2A5-EC52EB430D2A", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "AD6E5E06-F813-4297-B2A5-EC52EB430D2A", generation: 0) creating a new, relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "AD6E5E06-F813-4297-B2A5-EC52EB430D2A", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:AD6E5E06-F813-4297-B2A5-EC52EB430D2A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:AD6E5E06-F813-4297-B2A5-EC52EB430D2A:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:2967B371-2142-4D39-8DDA-E8E4121588B4
,[ThaliCore] Session.session(_:peer:didChange:) peer:2967B371-2142-4D39-8DDA-E8E4121588B4 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2967B371-2142-4D39-8DDA-E8E4121588B4
[ThaliCore] Session.startOutputStream(with:) peer:2967B371-2142-4D39-8DDA-E8E4121588B4
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,1 [1, 3, 7, 11]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:AD6E5E06-F813-4297-B2A5-EC52EB430D2A:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:AD,6E5E06-F813-4297-B2A5-EC52EB430D2A:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "AD6E5E06-F813-4297-B2A5-EC52EB430D2A", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:AD6E5E06,-F813-4297-B2A5-EC52EB430D2A error: max retries exceeded
2017-07-21 06:39:54 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"X1prj2cgIOwlbSsV1uBtSmBRrGjez3Tu","error":"Connection could not be established","portNumber":null}'
2017-0,7-21 06:39:54 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'X1prj2cgIOwlbSsV1uBtSmBRrGjez3Tu', error: 'Connection could not be established', listeningPort: '%s''
2017-07-21 06:39:54 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"AD6E5E06-F813-4297-B2A5-EC52EB430D2A","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 06:39:54 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-21 06:39:54 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"AD6E5E06-F813-4297-B2A5-EC52EB430D2A","peerAvailable":true,"portNumber":null,"recreated":true}'
20,17-07-21 06:39:54 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 06:39:54 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
2017-07-21 06:39:54 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-21 06:39:54 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 8EDCF724-AD07-4005-8DDC-A283D1F0F2FD (syncValue: Diqy1QudF5zgBNLHeriCnbdKHSgDdP4b)'
2017-07-21 06:39:54 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:ret,ryCount:completion:) Peer(uuid: "8EDCF724-AD07-4005-8DDC-A283D1F0F2FD", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8EDCF724-AD07-4005-8DDC-A283D1F0F2FD", generation: 0)
[Th,aliCore] Session.init(session:identifier:connected:notConnected:) peer:8EDCF724-AD07-4005-8DDC-A283D1F0F2FD:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListe,n,ing:)
2017-07-21 06:39:54 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 06:39:54 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:AD6E5E06-F813-4297-B2A5-EC52EB430D2A:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F090AAFD-5C96-46E7-B54B-705E443D5365
[ThaliCore] Advertiser: session connected Peer(uuid: "345FB200-0861-4889-93A7-1CE465A33780", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] Session.session(_:peer:didChange:) peer:F090AAFD-5C96-46E7-B54B-705E443D5365 state: notConnected -> connecting
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
,2017-07-21 06:39:54 - DEBUG testThaliMobileNative: 'Server received (6499 bytes):'
,2017-07-21 06:39:54 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
,2017-07-21 06:39:54 - DEBUG testThaliMobileNative: 'Server received (3356 bytes):'
,2017-07-21 06:39:54 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-21 06:39:54 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 06:39:54 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
,2017-07-21 06:39:54 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-21 06:39:54 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
,2017-07-21 06:39:54 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 06:39:54 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
,2017-07-21 06:39:54 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 06:39:54 - DEBUG testThaliMobileNative: 'Server received (5475 bytes):'
,2017-07-21 06:39:54 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
,2017-07-21 06:39:54 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-21 06:39:54 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-21 06:39:54 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-21 06:39:54 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-21 06:39:54 - DEBUG testThaliMobileNative: 'Server received (5311 bytes):'
,2017-07-21 06:39:54 - DEBUG testThaliMobileNative: 'Server received all data: Nd3kZKMysvXGVtXC5DiByvpGzLlJ23Hh4gXiD3ECezAtr7ZFMFkkzYncPslJh4s4Aq1fhE1pvaFsRe3O5T3oZZ320GdByiS0fav0vh72vxHdiKduHp42U1qOqeNs6AZs6YUS6dUmbfr4ZoQkJuRIjO29XG4JRBpznAYIzPLfECnsArVte9,88PYvJj91AHKOWfg9T4LBe0Kv67rxPJ4nx7nD6vRBCKohAAoccld0HalicPISHMBdHfqUQ42FowKD5vg6WoAmAsSrUKFJK6jleMzSpbPbsmQvICUo6PtUQKZDs6xbFCVeyOiC2I7ey4xu32B7Mdzq4Rmms4zaoVeCqXbttoVWXV9X4DS5WzAN8IRLCsz22eBonuZmyikfASsJbyWvHxYInSrL5aYYWKigO3utacer6ipKOkeMEjU6bAEHbap6o1FxKZzD0z1JUPCF1YwNZ90WoQgTKsZk2OKAWZG4UVV2KFTtNWm4x9uUraF32Z8iOucaLoudQwZdhalCCVomvt2V1AjccCGqzszRJppRXVhRCXZnDRrDiL1SbnOm7SsDFH0om6KGK5FPGvmI0cGnqBp582YCHGe4YilWPplnMNdg6ttGjctj4Jc2hc8SUk7DNYxciXJL5lqFHXo4MkIi3MKUTxZgeR0DJBcDQIHdgPb0sA3GjiZtovGwV7wnJRsKfa41ti2mWIdRz7pqngykKdXEUmQ3mUXzCG6bC5mKEVGR7VWO875HmA8xeNAQczeT2l2dOaIGqcuFG1cHCBzFElRHidjRtKvSRCNLjRRPLQef5TCCNnXb7VAPVwGnApQaVRYXANlcNBYdEaN1naOlOupYZ7s2aVnNhwT3CERqFysZMarrn7vcpK1L7v3sFVQ5QPRs8gqpUGv3dWq55SS6ewWpARFviLY6fDznL1dilS2wmp2eYWDVd8ie20to1avRmtZSg5XocthtO3kvQ02Zd7FhmieUb2YTShsbL8jzhBHTQWttFpu5tRUA2nualrPphmmVOODRW5O0gPPYJ0Amd4ZlDBGC8KZ5S6PHPuX2wWhORm1GcOkR30uhlbmMSEhTjIPEgsLdznNy0fic0SRBA7Hkh5XK4KAT6UEnbRpF13SL4LidqtJkvteic65BssrfG4Roxqis5cYYJddcCTHD4CZuriSNgpD7Vk98KfG5JXNiJJo8CgSWWqEZzvraIi6VRG4fBASdRZGgc8s94JIggv1lBX7qZEoaQoCYaRlxz60B0yAzqjYOrfpR2SWottQdtVu3erUkzDwprqKw1iW8l6BPvWpOoKjQvAlhcp9Dpd4nvysYPx5sYIDhg2TJYk2yVbHbTPBhgic7dvGXIHLkezhGCsyAvUO0g9gXYNxXhmDv2PvEq8pPGhN56eMI0pa5iGZBw9GelGOampnoVAM79CCnlfbKnM33AGwYqh4mzzRDSRgdHkVTNAErnuz9oU2BOpcIrKNcMFtqViwUUexTSOmyBi7RJwg68KC8RE68lWjTbrTR3EiP86VfhuTMLex76IJFRca2GQSVjy6zEZM4P3ACS0fVpahufms5fNbmheueUV4h3I3GI6qm1QY4qdlIxxPN1tRtRNfuyNfhZQkMU0g2NyDi09KXC7VMWl8tYgXNEFCjdi862PFB7drGulHojBdRNZcwVnrKBdnObjh7o7pvWNZQM0rqwJStvippQSai5vlRA4dgF85iCOZs210p0ZNoAn0SZjRUekUwQuZwpCRvPT8GYZeHDa3WHDdpLnkCrwsjMcQYAi2U5Mmp3HWZcmerTQ14uEfd4fW42iN8ioof8AD3LPaEQouqQSqlmdHwXSB7B3McFuS7PupeKsxTcALZYfsYyqQh8LMcUfsUH2rmZPMNiB5TBcf1Xnzt3mxED9obMO1SaeEf8JDrvPfzNZDHszpFIvzzxyoU6CUMEOclyUjqegGpmAPAPwZpcKiXDgmNKoJp3OV7tZ5vjtLu6CbQe1c3KHWwJe8i6QKvmlRjZEcEFsyL25GKKlzO65f0FDpkhDFB41iW1d8BwE2Fsi9o74xYVw35gJqabKom7SD0xLaLiJl5su0eSlDMWLK3kAbxDphX78Bh8j9YpsQ7zxawJTDGcffRA25N9fk6cutr0HBkQhGyBkjQPW0AeSNgAaUSLIbI7BdoEMUMJ3LkKRI6RdWzAdnqzlzPgXRTuQ94C6NeTsoZWwg7oBYdDblr855zMRAbFjXJo3LsUCvUcyE6lpR9I3LxB5vHWPqq4O3XPd6K48XlE1ZtM9wRvfQ82coy5gbA4Zb77vPX9O3P0F6IAq4llbJCfIVH5pgY0Z7WAsvdDbrkzjMtlJKqRzSUtCTUNO1GzQj8xI8lkKDPoUP8dKakjJjFuEY6x6ZUer6Hm38tEcM1U5iVbOY0I0SSWYUvUU7UhZVXI5uV85vXtrhAUI6wIEZxIT3RC4mrI1EUYenPk2NGmRYHvYqDvFK7I50n0sCebsr1Gl7uoiLA1K2bVUOt0B9usD3DroePEqADTnCLVe6ksahULv74IcyZfOCwk40ZFZb8oLE2IoduSfRtYwTvHxyEYM4Pj7t1dH19RFd63QtIgjYBVd9pPdlAV1a8hYCueHthQ9D29ykBV3SOitYjB3BnpXtM1CMNzlhTR8Fom9ht5mqnJ0ikTL81FxsvHGHh9Akg6v7fVI8wYMACdPpMq29MiPFCxOwZaSa9aM4DZAbpIbUEeStZC5Va4HG0Czeif5mFuQyfCmNUz5XfIQB8Fx2ujpyH0RJFO8PY994NJIBNybDsXwcVosWQ4ZiOwRWWcbvczH1TxEuwOhss5jwDQhXBo7HYCndtBYdLFAlel6mim57sDIL7FZZPJuqbvDvVetMZVOiSQxE6PmBOoss5YcE98OMPUBc5UQ8ic3QA2KaO1ZXEFKZ23inNSR5rkzQZG2e7chUi6PsRe5xydsLSEkUU4MOCKOKDI0RYb9uoXWnjvXP3128BK3z0PeLBbyQitOGhmInXeytnFPi0FrBzqiqfHXUYFoG75WejUIaScU0vN8YcEkqZCgSXSStRdmJ5wMxpUDaZAXchJIeaTEP5hPLr4tXVjhoVAwXNJYtDO19fAnLcY1alwcoHVcmBGPWj38wVZDcb8deNBYYcJfY3FMmjMrUdm7vMTNCVIeIOdLsWYkrk6NryQoEbgIoJ64n57rQUi3mJQprhB4yj19wf2uWkFTOXujbWgOb5hhSdDPsSim2sZt9uvdmHwyalgT99iITpErfwZkm6P5yMg3KJEU6ZnjoPBvgtGzuGbLw57idlwhZCxyb0A63uujILdzVoFv6GwD3HGPEUr6F6ZBsSaenLyTvkDKGJZf02uhKSbDZoTlBpfxwbWpHO0YNNvvXuWI3QSZzYMWuE3xvZyrFE5eT3s6sMmevAffPrPCjqgvFyIHgxc1OiTQJsvs7GpqNtwT0bjKDvdJlzXpwYE9l47ZUM2Wp4yKqZuHx1JPn6A4eh2rardsQzOpyXGCYyzhksKD1JdzOzkJLfkbdzG2ld5CNJBvnUrMVXFy6IyR7mkKiOYT8FlxDCpGYGfxyzHDYL352t7PYo8VS0Z9BqRu8aGAhLyXTn6LZetV8HlUClTKZx8cXgQJ2CTF6Qm3xfeHi72Xve5CCI1voDzeDwrLZSCQkHWYL9TcjeekQOcjxl1pT2pTQm10OKdj8wfWPkhaxkMkHoIsnbWVgUacepMfS3lcJvILuMkIoZUehs8ISnbHJMU9Je6uNey7bvxxxov990hv3qe2Lhm0hmrKlw9p7NVvCUHuaK9BCusNCSdTVikICGeC3LPgGHO5GdywItSlTMDaQMrs47kvYz4qVA8MDRWBLpnq7icFbtPbVGtVAJxzNaE7idzYN34fgIdbbNMcpdFyMQzsKMupYoxSKYJ5TXKp3N8tPN4s3DpE4NoQy61hGsca8th4Zd5bNQAtcTxXl9MzpMEVc5I6ckvdnKpJZqJPfRrOCxiq6grj9tDQQtEtD4QmWsGJUPw5ODUtlKRiQYQBriB1KFPJ5cT5RNlNrlU4zvZmFAoN8hPp5vgGrgGdjxtifXvqLWITVaGV8E9PeZJR6JO468gXaak2g4OkmXfKBtkMrBQclQXyeIhQB5EVO7V183Zw9dms0I1IupNiqc083SBfdCJCUiyNkwiYXmCkq5sdpzWohLPSFbpbnvJEaca8yDWVRN2grfOHxaQ1pU3hyhGyf0OSDrrYIf9pGGAu7toabyvLfZnYiKRZJTmVt5nKIFs4ZwUbLNFq4vQM9h0tFZEz9gEVdM782MGaGaWyr29uXP7pq36Nx8rGlJCchxu3buQQQbWKzTrv6knnaDG3oGDgFzWo11NDrxqBJCbggdNEMUWAunx4HNlimwnneD95sOf64bwIJpSPqJqzaQFoYsRuPN6oOEMYeIOKrlwjJrHwwfBCQzA57HelRRbUUhiBhdYe4a2keH3sZCG31oU9rPJ9JyWBpRrCwCkjREeZZbQQVCVu8jY81noLQuoKCgKqCa40zHf7Po2Ue1jsmncZy2AepfGT7YbV4En0IWxw8wbzDbUiJg615xRTPMgHM94rmOe6WL0tbr4zVqbOEBfzNKTjynQLJHl1How2Re4uDeeF5g4G4QnLj0zIkWf7z0OACg8mGb4LBjlzABT1eSOnt6ZBJc7sgqm7ttFEahZiomsa8Qh4fCFPml2ylIpdo7ett1pzCymTCLCJK1KFOLt5DdbVezvgJiQNgmlPmjDC5meIQdEdRoN6EBmXxOqAfL4damVSmFV2bd20m2Z2imFvtrfc3VEvD71lXLeuP1z6IleeizD3LaFEaL5ybvY0frcFQgHlf8NrvAaE9syA3whmnZbvPz7H8c6DqAtC4rXtFBF09tYX9vYIuXV0X1URLlmiHnZnrnTRDJOVYphfl4eCuMot0NpdiLjLniuy8jfS9iFNYNFVmtVAdkq1QZLAiVzQw3etLFoGguc78B6AorQYvENl8eHKSskC1MnadVuFrKp9AngskUTd7za6cFzmUQDmMRJ45WmGRVLOvNSOByutZwUtpnYGvoJ8QftuYZXYDNT2ppbjH4JQGfru35gXdhLDAuYSKWiuHNqVjhrEWocJo40jRjnLYVac3EdeZAcHHTwlqOcYXp2YXxT3F7ozHRY33OYuPjeZFWSYjldCHhERvxB5W3YMNEquuyA6ZcyBdeXzsYv6jhHTRoK0jFCz8JlI5EJ0tXT5hreGOPIMZdNHf6rbEB4IMDQ5QsbbUloTdHUeUZYY8mT8HFtuZvByIXU5B6dkRBxI4mMCUy4NlSRtscx2aASWEO2xyn4frlNvtAGsnq4XO6Nkl2GJ74HGO1He7Pod3P4QyNDEBMi14ws7WIRyFApmDr64DwNT0XYbslRBVWc8YbI6DBJ48mUTOZ23uj7XHIwj67YmsMNDQ8L3EhjBfTVxrTMuoZ7L4Wz3D6zMdX4AtImxrH3nTfGf7f5LfOBm6nruuGp40XpyJhSs7ufz9iQ9pAbEt7PlbOwdcdmppWBK95GRUFjBSorgxuk9dMrFvIuW9Bh0oGwjhHfVPSh4Qpb84W798rFLcV7L04uVAQL8BaNZ6xP13kA595Kzv1g5RpAqwxaNVGl4QtEwXX7hi0ubNTL5K4MZID5hAy9nauMr3ymOswegEwf2KGM2u4owbgm0QSMF4PGqFGX53V5IJ6qrtLAPpZLVxZD3fY0YDrXPIgTKmE3UFaNo7xoRIe7wptdNFgP9sc5IuyN1ie6ExVB3acNtj9az4vjcOK7ldp4BTD3Sv5EHw8QmmKPxW35chJax0HR2LSU44ZNTmLNFoHyhN81JDioFFXYcYaJyjpBU00b2ROItmFOxTEc8attoOeXIueGdOYwcfjZvDxBAUNlQaE7dbsmRaRVnAzhKsbaI0XJkYcA2RATTlDE8i7vq6EKJTTnGsvL3vo0fspIv80ywxlivXzu1h5xaXt6wyGS6LyPdm41bBe99BwOh4GlckQNwjcQmgmb4GWNUTATqEjNTeTdDDFQ6sLmJJeCPAt1jkI9urgqJ8QS86zNHUJIqaKsNPKMHFRovKiB4bEst3Bl9RW4bPrisHpBeR0n8MhyexOclNBtNTRh0G21Zik3l1D7LqyxFgIrDCKjPeB1d0IeQNFjnLccnDs6zbMFysOai3J8HAAaTPfUwTRAZY1FK5CtPdM5ALbSUSMErPFNvMGfN86VUdn06R3wL0fBCu7T7Mq7RRKrlwIgU5ujMuBfLikHDjCGnEB1ikwtjvZh0x3rYlWoeNrFcW4EqdH8C90HxeRUSg57rwbS1MSOZMFiKIys3g2ffmxKwURRZsWoRGb3HWrYQRIV0HeuVeVkDLO8B1zFn8ypyusoTXJSOXsJLVRkM6wINYtkSL0T5Mhe9FIMd9ORuoc7IwbN4Yi78UqJaNzWm72HF0ZeSnftmDbrRGUczNgZNOoKgDf0ETmXvTwlZBqUyYZZtVtaljzrPwvmWUpKPQmrutNXTMwVShMPQjchE2VfjyNVWT6nUzUaynRqqlPHFLDls1NEk3KBNBGUttPCHoS2HzocrOnCc1MSmY8t7rcCmdpP5HhWb8RgluSqga5akQRUutTEjZfwQKBmrvbye67iVXznHpcdtdBnLssm3m14ShXbJU6DTVkjnxOOiQVMynZFFiI1q8mw1MCvsYuetqxGiBeCl49UqiGUXn9xLJ5eRoZR8ltxBwTunO3oDufBA0s4MsW5uAvXLjpvejitHMFvPk8z3EtvQKOGvvMyL077TWtc5j17jkCP5p6HSCwUChGAYi8lyZ8aSlChDspvnXxUhX31kZ0EB1aVRZ1tlpyLch1V8Zlotpt2Re06NgYpDwfU44yayhmloGW2y6ALvrsysP6LJdMPM16KzfYzm2A3fkx3gPnYjl2wCty8etGszWfr5FjvzUHSxBCLeoK5uugheJc1GNVJE1wLZYWOV9K1w9kmVB5t65oO93cEHAcIJKps6quIkwjkfVqzfIQ3bcomdllLBfczoyryWJiUYgRRC8fGS2mqcO3SGAT6yQ5P1ntdQ8D1F5Zy3083BlDyxJ9qbthBAFku5acF7RyEr3lTMMYFHqmVWgV7H92BLEUiOOXpx1P9CHvLCvB8p81rFD5G9kT9bIADXk2x2mG9QWI1EnzN1bXbaswDZa997VOQQUIJsGcHinL80TK4RehPZwfX81yoSnDx3XjxpSfQJLWeJ1qMUfmSdCRUnObkkAvtpENB2j3CyNsHq7CpBuEPfcQOuQ1Qq7fRdavMeSKJYUXc2zV8oOlsmai54LUDeeCkqYmL8BYgYov3SHAUzrIFkZOLnZGbCmg2BylxS3RX26WXzaR3gHr1QSi2Af0PaQIXt7ymddwwXsffTnbUogiIKlbfNcvdM4bDozZFe2UnXPC1Hm3z3Fgg8ZaIf97awlFmBHVwbrpxlUYgLjckGO8jxu0JojuB6GZR5vbF27qU41TbkiC2R97rZ5TFfgAsUgPvDGAQjKYN2LDKLqcrLJKHo8CgVTujve4PpxyW8UPjwmYVsXfeC5QBSGmYSKH6h23jJyi2oCRPMMcVaVNAQuC719dVO50uD0EeZ1hcj6X3BbocQEoMFJn9eu1Nn8sewdYu5jQAcPN6taoIIUiwdaQ0fuA9gHGBMH9P1ybMecRfCTTrIqtqOFfhAfEllL3NqRyVnvaMpU451YrrbEe7xNa3qcXhtYpDgxaUWFPtzZyre42zSQRF6Jog2frCezve6db2Jw2f9Dd8F1mEMIiCegDcWQDns9afyoL4nRXxzF4GQ0M6VLYbb0iEfRwpbeo8E8wQRFV0rfohjn8hOlVS44ljrZQRswnqeJ5FiFYVT0vkGbAnkK9ZJxBYeeenSDrpe9AVWWOU6xu2w8ojxYWCgR2McCil6PojDWBajB06uF246TBJaM7sPoguHXd0W935bCxVpB1AuauKcYblJ461Da0ld6aLZXaGXl03DdRrGOeJHDugD22tpSYcTqCbxkpTg7GBpDlbrtGgbu68B3b2feaalreYsGB1sP7jKi5M7H3lMBL4l6LQyQDiUrPAzF52yHpN4PcW7IYkl1QEA8lASIPA9rnISl761Ox2TSvqNIsond7MYju16JODTckdRH9pbdzZ7xaBkrJykDL002VXBVSHe5cNjW85P2ajFhwTJPVKM4S7cADdvKwT7NtZt9J8DBmtIb1aMq9xMNlepaelNjBqq0zOY84KPZor6nr9nPX6UTf8OgJyPciISDlUvMNKoh4ac7oJ6ooHxbresWZT6IwQENcGXEv1CpdQLZNlZPRDJeIe9kxLOZP9hgG6i7fw4CVRtHo6uineaOhK2wQxaNAGrSoWgq0TyJwLlkMH6fnYZ7dTOOur8xzbqkEont0bcCGMLY,L026BIBqI58bIHMcN5XmtLOBVULuio53qRjuODj8kOgR3SVkk9JcbftSzUC0y3WAaaKf3gVJOqEQFQLYm25hKCKnRlTfOkbBqMSY88SHNSrR3nTbwd8aNLZ9iCqftOcptJw2ahdScsLrHI7QK5HZO8mUityEcPfM8cEbG3cpJmYTjrzj5tirWvIuA1Qcoa8POPnwuuwvVqxjMl8pEgo6jBBqWjkr0yTCfUOKM1wdxs383cEFKWJBFzOPTKHu2wuTHoQD6bMPJJ7CVDSlOxoagyNSg25qWSWclFLS4MoWMbDRPlMVE8RwX6W568rQMLldbJUq1MyhPae6Nqc5mTLxjfu4MYAkyQMIQKmw0zjcm3bxEXdH1xoA1xhASM2KWjL5X7W0RTS49cqQ7mYrWk57ALfhHvCReopaHOzDmlrpGFNDteLTSo1KybW34nifKl5SPOvGuBNF9X27eYPeNrxt5GcjD1OJRNj6asQ1lBZW1ssmCwYbIYV1u0EVJZrNCW7yeAP6N16dXSD80tTi2dgDtvx49olMjzCPN4ftKaKdi6xNGU1fXfZEoV4q0xQymwYJwO2Ms6sbVKHOJAJGCngE7sKPZpj2qjlj2pzlAD5IedtiXZrz1igEkHRdSjabpXNAQoJgRAVaiKjNv21FcdlZ2kTykuQs2eiif85qokw2BRCEDQ9r600gOLCx69JtK1OWgpXFxJgsD4ZQnyNSf8SunQr9iSQIYBhiZt2HLGIn649UuPM5UwCrL57M9ZhB1g6gMPtaysWAg01WrvVimNnlkbdf4bZ94hERDWW8FqbQd4R112RNtpmbi8vAqCvKR3WbFBl0czttWLqRkWml6TA2Dqe3ctEdW8jxNUFftgTtIORJqtWXA7kmm7wPayaKvfTs8XfRANqRHHdxzhlYTFHZ3pl48xR6P6icjqw36gex0n0seLxt6t7O7ygemIhPcE37o8F66DYPyQvSVFyyIhExqmuKdo4Gnb1NINdHa4qolQ1KO2OZOGxdDb8enTuxlvsBNZkIJ6PyRoMJYWqkiqaYuZf292eSAxryrvxKxpXWsytBAjjgdYMsIHJC5SvEJShbVUinZAblcVGJ59ncim88Srgla8fSLmFop36VcgPVrA8KhnAxhLqttej8dbj3EmXCr6PKAwGPuP2CD8RwRnJRzzrBj3ewJCG8CERzuTdKMSB68rWxaQQ58Z8isp204hBZWOlocquL3hH2SHbiJ1HQ5GgEn8jCkSCuHsfjE0RXxigIsTggygjafJ0qRT3KUkpxnvFApHJQnUvlfmr4WV23XbvVScw0nSKAieN27nAS174w6Vj0cudR4j4ZNi7jILoh5KPObulyjiXpF77ULEnG6WiVGCOkOhV2FMhIL6za8oYXwvaqoOqXkhXDXCeN5FUPmZ2csOtAdCgYFVdeJGoyhqbYI4sMm9qgGag7kRyZf8revHzPIkKKocVxOHr8HZjZsgG2K90gCeRImoDCcbfNO6J0fujXQ3ZDp18wEHomKVLaVxda9DIzwdJT6dRa3qEE0d2vRl8lViIT0YcCLaBxOhy89txFduPVmZb9HcLNefsgAwN9TkclsDZhX6hSoeqR37s3MZ7tjv3FNJoqaxH0ll0JN4H0aCWNMxXV3XJr5AOF5TNQL3cRMiVtdHlMUN2z8KnAvF95SRurZKjtSMH9lm6sFx78LH0vIfVsXdpESRtdFtVns9Q8jsA4sp48GaIZnrwzzBFZLv3j3pcRFx0W5vwKhQOYT3DxQM7u6c1izamWR99i6MNIYGZpM5ydAhNH25aDneSzDn3Uy9MBEJuTFfQbY4D2htNFQCQP2sWJfSfO89pTNdI7ZExQx3PrpWilEvZx8kfKtTwKDUeJjSwqlIEPQGHPTtPYtD7uxXpOkd9Q7A1ZMyyJanX0l0PLzpoadVMo2oCDsD5TBDMQIOd8Mr9IW6xL4uytKnyAasaOKX9xELJnBfp5Q7cq0vafaj0vsHVI16OkK1Gq0cf8Uh8iZ0cFY3FYKEYQBx74Y2gfotHBMHToJYYEqnMe9slDgNfw13mgt4Y7ryeC7sGywwLHkV4tXYnkChwIQUY6iHDEOBZb15SSMC2xN3u5gmMGRaICxDIC4Ezn8fWatdLz1fZNiq8uED1JGk2T4xnI56dxc0fDZSFD0qgZnI8WQ9FCsujjAaUd0OBrEfswBkPITEqgCQwLjI9zJFuA44mI8me3kSlownCNtP0Y6FberIhcoKoiywmGaKcyhLqsHkXpMJpa3s9FJwsXM4QlbWy6kmTTSCHmix4GsrN52iwZYCgjpexB5RB9TM0wYUmjKZImOjFXzsnOgADRQoLjdzc6GFjlNviBiNcNi9n2CR3gOz08wK4bXXKfmqy8xBJjQYmNqxHKJbJQH2pUHyRew0yEUH8EWN7TxtQ4eM8ih4Ghn5LgyXCjfax2DUyRvdXQigvaqnhgYfOZ3QM8NiIHuWhRjrx7btI0KlUAhDUjPqyjyw1UWvt3GUVhshsn4uhy3LD6ec4Stg1jHLv821TJqixYRwSe6NruG2oAn9yTUH2umsUfZ8Jzums0HCMB4YIzNkiGreMZXcHyj5u7FpLKY4wry31dVMQj1L2hIQT7VicpgjroNbPb0I1qplHXKyFs3fVCY4IaQ5wtHcSgeiA577pdgsIvLYuGWCnfBel2vwgJIoiR5zul1u1ZNqy03JxOjCrxaPpsT6TqSFawUwWhxoVif3fvs8Rxtqsti348xI5Svp1wVmZC1vt9WiDFOe8vfG7jzVvMMZWPqOEVkWpMYUpF9vRnwmtv0eoq1M19jHfLUmIHappS,JSJrUhTPq6bV85WEDHRblSVRxiZ9ftuNiM5eSWKtpr37REvzVAYcGpizMEUfAbgu3e2a1N1TwllBOs8VxDaaMJKYGb339Bqw16KjvuXJFpjTnDm2SqR4MDE2utic1R7VtKI8wtuNcoSV4wpZLZYt7TNIXzk5s37IyrNmrAwZgb7SpJANnlqHcoBraVlxcdyiP1VI1EqXTzp3lmR0eysYJ2Wj70mG4k6oc9BwCBgwjd2q1atNagidhbGQQ2ROZAwa,ZzprUYMAB9ykbaiAppGhykDrfLTGPJhtaVtgHzodN5gnQd8FudXqHxLfqxMVd8SFWwUMXwPGlZe6ba1xKXQKuEOwcLt2sL7sZdm3d9fQSvNeJS2AV9VnFyD8FEnsOGM9BjltmqsFBRbZFzOqnt7bQc7zJXc6N67rqHp0bWKf0mACw540CLUH64b0VUkMrIKyrvORYsVZz3KaBxmmOKJuG6Os6GCpNOUl1Szi5YLsw2VghuBEQyCp8Ixk0l7ncfcv,0MR0gSX4ZoCA89EzxoRKbI8eOnmkG7cGB6BKEGKwnlsCMVBCsWYo7WctgevjQSNEclYB6OLFT5rDg1AhFiOBxDNSmNYOgl5S9uT9kObYkd3WVoIcdZzz8JrV3vtB6ih1Ux5zh2WBOV8lPqBF8fEXrpJPPNv1GoNWoq5MVyQBjXJBchR8mthg7VvgB4Xnnc2Ef3kXVBFTgLz4iulNU4DPnKj9TugsaZXWVlDFqt4RkM0PKo4K59syNgjBw6Nbg8Ui,KVuHFWhXailISX5rk0bqC3JsZJ1vFFLhbBE0eZchokmZmqzfxv9JJUfCiytR5v8V4l9lcBh3i9yvolm91H4HtYbyzVYjE76q0D7T2f9f4wLbW0BknJxbObB7cFR6fS9G2LoGIJcobfzWrsljPw8QPaqL80NuR6mmchwsYjPlJaNozGdcJXe1DN66gfRKZhMUpgT15dkNWgNFHreNpWVa0v7YFKzit5HyyW3gapxirfwUEOdd2lheWNO4U5DHBG5I,pDzrwUfxDzYxUxEtJggeVtJhHMrXZaH6DkU7ehsY0kaFkzsiPhe8iK5Ilf14M7obW4eUA1sYhYkC7e94heh2qgqGWbi1FjnobKQfj5jCqiEptFXHhqQaj9GN3CJ2hvMDDd9hgVE3fqukoOFYsuiFtmKwXSt2SlviHMYaFuCwq5EU00EEcxGJO6hdzxryYiTZdeUNHlH9iKcTLHifXO058kcbaYEsAD2bWfsaCovb8o3SMMj7Uh2u6Tn6xfyxt1qc,ZfhsXFsbhUHOTIkLdbEJ3HwPN5jFSk38qAfaYZGAetgksJHxq7VTRlgcaxIv60yH6CcZyRaL1vAq6JSoIfUt6xRF5MT8xdAFvWuzKIeBrydFKi02Ws3MBqerug27hcKCfoe2YuzQDERhqrQw6WInMZwoSOJdCw5FbC1bK9MUL7ZD7qJE6n2viEeCgiOTxxsWCOCMRTqtcsdcxInrKuuFyALrxIuLrI2XCMNVSvvoqq4D7aJQRYqJGUlLxKEHWCyF,kJDXpABLZAcwwpMJ6d1H7gmBfzNGxQZ50WLPrRm2OtctAzXezV27AmrjWf1VJETXxmTF8ALOWuYSDqPY1IHYXrGuD763tRrBDdgjYnSkpRfe8WkkGUDIjDyjiX5wI4dri4YNzu1r0F2s0V4NKCRFJrTYJpMzSKVD0HokJnv7XTxbKd643DY1AykY4FhfpDvtHVeq7KQf4GhoT5J08u39THqLR3T7HRJlRWmcMMKQeFaPrQEbwolZMJa08PCDuGbI,48tqguMowPViX7jzZ7J2yUbYQdH5rATaFjdW3Hg6W02HpBHeASr8UonOP1iasYp7FocPHqIXMb3qbU64nFCkXeexB4crEGSg76avhihwmqHMrE0oAlF9G2HmWG3KfJBWLqSjdpFmtifAscbhPQ052Hl83hHsklb2HrqEDLdmX4G9TCrHHYRJmcxUP2UHi5nEXLGb5qUtSqaMv1vvqmCianV5JBpnEzCTPoDWJsswrHjRSJlqtV7p45F1wqfZn8dx,JZWYD21NikS5FBCDhB0Cvvk06eqBOLtibajL0TYW7W2wMs3eFhT26NUJS0Y8pfE9NyukdGDvJtHUEVEkrEY1uz1JeVJ7yKwaVSzoPdx6XWxWOUCm3nzhmfavWYgyN9I6ASRaWwSRagXtty2ZR50OLYQOx6exmAXGlTIC9KjN2wnBCpKUNCyfzw9VPgfnDlA2886hL2hm3IRDykGEpSRtrtf4Oy60yOlxCHSizrEEGefIMjaKrey7ywmeAfvPvTe6,OggM6K7R34m18Z0W1VC1IwjJo2vOLYFNYC5UYyonsv5uq46MudqobrZvBlwa1jKhhWjica2RfresQSdV3OasmDHpemok5ouisC9HZBiUZMYmEPmkwlTTjx4aIxp3JNq10CbzW7cFKZyYDlSg66URraTFDx63W6m6Vherivv6WFloTw4X1zhIXG9pWL9rgnQQvREyHHyg52xOjGnsvFsbI18VIpcjWl2wKKZQZkdrinO6WINPKlrLA3Rr0g0baUjK,d9Whh2QcoF8H93lA6E08aSYpHv6DzqsmadjyZo9MbnmHBIl5ao0sKUxzhVZBVEfcSCSbmv2cj393iu468Ek8f32TyCDUHpwvSnD1jKgnarSV59dQ3zkAx9HHClSbqRcC3tMUZnLrQZr85n7RovLTp7gBoFrl3Hpz0lOHTf3pM12Q3qp4CfypQdSk2CF3dW6d35LUCsrtJGi75r5eQ1wZsLGybXE5G7L1K2VpnVhttnLYJXx1JsjcwsHdi3mBbVNk,94ATJwHQXAXdPlNuYNMHfOMms0vFyrMm9hDpSHsi30ihgCllzO25d2ZPg4BFvicUdpNJW3ru33iwMfwQqR1sVzEmwA3co1hwiKMgAMXIu5ODQgN0we0vYEu4DT0TUVtSqtsR6eaghcQisfNpRzJsmjpM3DF5v7WgBgQqdgqHAD1qhsDRGPyQyBPbvO6wBPRi0cyfp8hdiKQs7a5OmHO6JE7B90rjqwBRGoKNOnsiFwADhevi1HD8X1yscVaRWXzz,8xijkEEPWJdlv7NXqUiZm0dAZmUR56GrCvPXHCUuXoaWMuwNbUU7JQQdASO5rp2OFrNSS1ATo2vyj5roEA5630av8pXdW7dWPCLBeTsYYOTW7ggunfPNdvY8FraVnI4T3BesPYStb8ycZ1V8Ev7nNQTs0juiQZzXOUzAl5NINBWyeMpPxbqCeh8MhCzF9HkhgjYvCd7lkqNBPq8Im0Z64dmEAcqp2g6lG72uKKNTD3JLIKj2Pl3x7ncdNUakSlxf,zbvz8AMmZVoKZ2Fstv4Ny9aJ2gnj4fPvYtjh10ZtqLUzWE1x79LeBMzmlFz5qB5ciuZhSjLU0NIIDnk09A4sQORKOholqqCdkWcfh9UiNMuToPmnwa851vvw8D6ha524C3GGDKXL1WstEprrh9klWjCq9p547Tv2YO2r8UXro02fSSx9hpTajR1TIflQFrAzLN10oynd0HFxOoqVM58rEROttYmMUrM4enl4x0M6EllFjD8EWNYwU1jCpe5FUKx1,DL1aIHU28L6daiPbt9P5qanDP04lw4KZ8zELRGQB2rc8aB0RuvsxHtaVcsBPEZ5Ao07VoqkUdxInaJgG0aFpa8ySAdI4uIrOMzfl5lZfasQyuaNp6ILxdaqqPela1B7YNdQPh62HtJrDvDUZfjzIAhM2cfZS0nVx3NbvuOePIGLltVbZUFTIMAO8f0fjtmUr4Rkeywcij5xD8heTzwZqfSivSbA8N9tRQIyZvS1sD3msGDqecrxq90IUAxohZtv3,tr43OoqykVZlBWw9ZaiY25xQ0BHa7NIaTBu9dmU7B9myXFMqzrzGFEyddw0oYpN1zFIESb1SuH11h29zbvBHd9cH39tuzbIrPjcHCW5rFFkd5M8I0P8feEQoiwbtdDSLDaCNwNT4aObEi0jMOqbnxXbpPiQH4RfiO8cIiEislclJU6eVmDQdoYQao5jtxQfm3enV0orsPA2m4GS05JuGAgNM5WyqRbmgSFH7C73haSDI6jQOXhPCzZxAOMssHHmj,5zfh2q3EBOhG1aqlUPZLuGmP9bu10O6pb3CMsf5k6HYcQMJTxO3etIAR2DzAoIgXK9KH4jiAZs9q48itZeVSYhVpN4F2med0WahGjSSK9fvz7vzdq9Je6OBIAZMd0HgpuqmyzDAC5BQK8MPNmGNPlJ6srK5zS14edVRXIZ52q9FBLvPN5PgYjoOO6gOEHJNsqEI2stGNl34M0oOsILm9L3wq2PE5KmbvoOQrpRHUdfFC43GI2MO8O7RE1wXQuVmAARaCdRi2ohyQhT0Q45EkcQrBWooUsYOZqJjpLWtTYdRPMqw0JtwsOFiFWwFThQeHVeEUD1nxi8WSkypdahqRkMyOXfAqZfHe1jO03axXV3PsQ4w9EABFPNS1BG2t1Rp7On4zHZERo5kCdTpb6t4EJnxDxT5WxdXYRqiHCEdGsMbzagNtrkqd72fOco3TNQP1PHRJLj4aANuYZpr1iKDBKMlxcIg21uhwCzJAI2JEbHfDmfGvtmM7ZXGT8AcXaGhk,VxM7WmbdHJ981TOBNkFTO7MbfCe8BNFxDfkfd88InS1h2scwPh2zBgHtrCLFEEuiLyfxLZ4NlnodIOutrOeEjMjupNBrMbrmD6l9n68gP39v4gEooS20GFdmR7gY3DErIxYXeiX1haWOB9J4jeMb0Czd1qRCnomG5KNuTpG1aUFIpG7oSboG6BPC9uhYvBMKaaM5Mf75MbDtV58FhyfQA3fEh91aGjmjlN64YPR0hnnazZ9qqRKu9A7D3ht9J0gg,Sn3Cr8tKktGwhEEVx277pOYQJHMwsRv2Gf2wjjimbpEAVXf4M6498Ud0Lzve78RpO3pSeHMCL3Y4u2gyRNSMdfVxyxmQrO4UU4S7otlNUZYMnbzmw4YxZd0EjaotShh1qGPs2K9fX0YrGH22P7TCQBBFt5aZUUAlY27sMxMHCx2dT3gqsaGY40gsa9t8Ff8wpipLpC2mmFVobCYi8sTEn4vKvEFxyjPC52MLRjwnVO1FUUWZbQ3XHBGeVU7paLxJ,9rMPKec5cD29rpr8FrFICnDKFTZTXf4qo5ETTFF10tUOj35pna00H1OO36YpR6GsW49J1vt1CPzYXnnPG1wberITgOknFMqZkDLWpsZYG1KgrhYLLmka8IABqvVM4wTFFVZ8iUHUSNcXjdeERGP5ZLXzccKILVlQTrc2AlyqiOLkDf1daS9CERPqo4Mfw1C2l2LaawA61tW9QRhOIyB0jHstbCTi5RsP3ahxWlmoKYjtYLBzWRVCiy8oI3PNI89V,pjjU6poURXV2tIxE9N31JB2at5KLwNeTtUZHy65BKpbQQaC4SnbMGy9sq4mI2u5kwbueqDOTXn5S31iQNUByOiyB2s9myopRxPAYW2Rr8oLJUkaey3Xn8CcGOiOfBSSbNo0RWsLnJATA6LZRPvZ8Tn3SdRybNSVkzMLkeGE0fa7YEHqR89xphDHhDgW6XihMN95mseZ1Gwu6X3QYnkHziBeHfQJD04DJebrKeIAU2ix1qdpHSKqE5IfyEZSm3hJs,0tGV4x4slRmidiHx19FNk5FnnXZ0qYN9qhYuKoipzVjuy4ALfpp65v4guSWrE5TuIausx1yQY91be8d4PuaF3GG1SJAyKTcPtJHOU6aHWw2QhQXyXiybKHU00DaIVB0OeYFpd3moAxpGwcvRqnihm9gLhAeXxwfvh5M59wcAV7PwhFLiEZsLI60N5OHpbUOb7vRGcuepTkiPmmaT4npZyFbWbgc9fw9Xity6dk8rAF3TCvnk8bbByMRZLICKA1WH,sR6Zd9dVVFJAcRf0Ywm0A698IEbJMWo3PRlq6iT03PX3q9by24N81fHmuItcgrMApxVXzqmx2zD9mQpSjNZkTMhraRySvkbcXXu7eNm7ec4vmWbHhbVSBj5fikDydmlZ5HkIBOd0wxbq2iCoAV8L2UNZUsk0pOkWIVp3MFla1iE3lJkPoy04Tr3uk1JajkXNgjhcohIGQSvSYdefBoXQXE2N8GyKBldCEwOzIGOfalCJD19Yltfq62GqO1c08prp,LzE5LsHrwfkQFkpwpsnickXzRHUaaigOxJBUm4ms3wRMNvNqUZd1rvvdsxepEH1GzfFUQkj0zbRUZObTSlsSX2JX3biT3IWIV5BDfPfwj9pogwtUXGtIorU0aGeingF8s5JBklxZgINoSyiNmVjCIEPbRGexlWtXlIY4cMpybDm7rpd5KjTbT15NZQFhnk8NELnnVFAwdTNqjUsqTnywFtdrxicIuzvUByFDNciEK9skXizdtVR6Re45behZh2Ty,GrF7UwopfHJnw8ftEXXAayRBSLqNBBTRu7SshOPrKYjaTFSLoeoq2dlnrqYD2P991Q71O3sLTGefFddFQBdw7xsh6m4FlfmQWNaN1X1jqcGwciWZthtLfzHrsVmDFryL1UzuvQOsA0i94BbWrn5Wmz2WBVdmhPwpHm2xImcxRpOMBHi8Rvv53I6P6OCf6krAYrhQwCIWaIplqgzwOhsns2jUjwQdjFOliKVu3pO6tyX6bb40ZnG5QACCVCeKVhG1,LlseRj5BaMVHSHNWVJdZ0NI5bsjqyLGW32btBTgELmBkD85D5jpcm1sUCEPiAJubuu8zivU41VYvZz8PzZtpXfsRind3CSvQp2GFxeOdJEZUAnVonUARv8Lg4iuyy1tDn0B4C0sLe8lnDItEbfZtWZwQoUBz7Z53DYySRcbkeirEd8HWBDsT3KaeButhFpyEWl3hsGrA0eOhfHm28qI8Dv63oESFdBiHZS2UCeQamnCfsOZsBKDQh35n0ZRTusdb,2lNrUwHeP0NS0YhEKv5kvqHXxWfMAoauZSIlvFrbMDHHAxvNjlgDRfT1yw5c5I5rzBDgmSFjie6fawivWeae0mQW30d5Zq6ovdA7bOAd2AWbh5pGnp7gei0u0JHaFE39YuNSGrdLsb68KytH6iZQElKdNniWE0tK1qXTA3yi5ijHwiUjTA6JNZnHBBr9AHK2pw8oBvcHy3EoygmuQ1SMP9PZ18Yr6KP8DaHZr8Y7qLPYfdmkJu9gWRIvxXPm77dE,nSpv517zwizADet7nhNZcxNiTUiWs8rzDE4SKacVB4z1bBEdkGhhFE3INt5fesD4uhsxauoQUp9OXZKa19F89LdBibcTDUYqlfB3ko0zmUkm8CqpRSfjttLuiC9S8UXTjDkRsX9gjy4NcAadnXobwZkNcAdn6KGJh0hB8OzkUfxYHKV4oNdPySx6pm4HCrpUS24nOTXcjwgEqbE62GwJR60Z8WSXF0TOdbVsGOxyxFjOu24Aj2lKdOcJUhz2aieH,lR675XLvA2cYGnaP2s5EObUhRHErgbcARHo2OAnqMgXf3cQc6D2nzyraVVI3o3cdo98VtC8oP1OMwWI85CfWKynKvMff7E2sNy76VfCZJviVJZXy1JU6f45rSsdL0cFhA4R52DVBW7E2Cvi1a5ENmzhpB1sQDmAC1IYCEEYhLAq9mXXWJmJSw3m8NPcQxk1G5xRuYDvtfPoYBPx9CA7GyXP31FFgfxEbWLko9Wm8mKyR5tXVwRntwznSJvLCxCtO,Y6yXJnjfLqW9xTxMhV46qlbIZdJFZYYuJh8D06DUV7KiyZrUz0tMbZMYmVnsNMk6emFFbVMwMDAEkN6d12KlDykHgUzudYzr83mCxKKQQskdlUCaGyqK3e5YjKYIjdmI0AZE7YXbHPssFiUxxdMoK9q12MkHRArohRJAfAh18impbjHgsA7TR1sHSJIJzozV8xFEu6rVefTQPKLxgWlhCSjzEED41OltXen4pxEXw0oGYJ7y3fCUvPBLami4jxlU,la6P6BI4tVZXGhUJSZrW0lw0m9rjumXmoZtC5U1uzN45aJoRgS2J1OSzdz5AjxDNbbuOZxzM8Dhwu3AYHyQ8wkGy8tOOiDlroNJ8Rf86ZfuZFPdGZJz2fROO6sxVMbkl4B88JoUcK4z2O3k1xocMCVT7ESc0hKiJpKXguwCNdaSGK2ZGy5cRLKTlT1cd4sjV1A8F5kZKhbiqVqA4IvjNPLES8DQwvNGPOomiWsoXNamzNrM1zIcho9gEkXuM5wG0,0rDCwLvIqqxYX4JP5CdH0jQGNlJTnIdOAr4hgWAL1sca7Yz8xlQD9xN8vlDQh77RwOrTTIlcp0VADgvZaFimJrUkOIvPDb0zFscGJ8EnWclSRv7x1PrhOjbMFecJChWQaRWnfop5h16XkRZN8sHvKOFvrJHYn8XmJ4JWinmSHa8OEzNXo6366cIgsbtX2VhfQFrMxZ2Qdw04grcKDUCNvSFuakPgcGUKXSuUEknKWIovjJOF3liEP39u6BxEmNM0,kW5389gFFgMHQSzlD0YbtIjWeZ2q7MyhbvdTuRBuWRUREPeYN71GDBSQYDyhTnOFAa2uYnKVHa3nsIb20j0w0Iq1PzjN8QCqE5pKhDd0MX6eELIdtjx5XZTzmWLXStu8WM1jWoSoAztayxrkArcNHsjKubpMziOXkEtW9Emnj6JyI60QrF1yVC3bQgKTjtEAYD6t3gzVfcpv9W72QSdHcOF4GvIUOVII8Wc2OHXU9R9tegXX4UzMtQU2FJN0laTh,u3iVRewR9CDXZJLKjS7YhDnTsPnz7wabbhmgungF0PLqhM7roNLAehhuF7fpwkJlbZWWykUsIyooVQY7284TOAWvW4f89pp7NExIMBvzN2xvAt6NUeVZ4Ob6IcS8jBFFBlS8i3FDyG3bQWlP3T5CK9FqFxrA1LBwEmtzkbP0IeZYjh5HQh9Fq9xeJQozj6jfBQ5yvstaHCLJaEw4OgmxKJnorclTwUP2OMB2wfws6JPYg2kNLIi209yN1cG3SDJ7,idDAslImkymHseMvy7ZBF4MCOq0TZRjyu6cXCEceIr7peF2p1J4Bgyb8QZk04BCKtgOReAvO4yaiGOuyVVhLMPHBxjievtZCNPW2XUxMii9ZfC8L73rC2LSjGgmnLRlpwbcTTEi1k70uM4pGAsngG4dwPhCjrpUrwlZKeMbKbBmpSRR545TWtYQTV8WGYLg9F1BahEm8kXRSh73OtAKMzMou22W9gcSFlsQcnawRIkRq6dxuDtClYA3LRjHPmjdz,6E6gEUR2BNDllNrkbTpYaJttFTYHRNAGX1yOc1kJ2xYdZSdHrLEpZRyWIDxAsylVDGq0jyWT1pO4bMvxzWIErmoce2jLSmIWDiT6ZK4dEechgcD9ARPYFeFjh01clgjq1BMzj9mDLe80Ahn43PIeRgkJZTMyB1hgcqDHJXvQqyyuoAJZZUYTnOXrKlyHUzgMURDtP9yrTjiGtk8GbnSmdSPz5ezXlBW2KFVFnsIyAqHuczBzE9p0R3dIwoImkxIM,WMBQ9uDYTvM8MIjXEtFpGYIQewrUHKyLc8Mh5Fd5rFalIYdkKIp5OPiDbxbbdmH9Op3BOvyLnQRett6qKx3BhOAiNzPMwlYzRqTFKSHwg4kCDJMjnbVNRgObwhBGtQsjNeOVCqJkYxLMaVGZ7S2K4BCClnif03UYKZSQyIutKcrWIyusfyTjrplH9YF20o6C92Zws9ux7a863bULZx2PCiP0DGz4Wh70NSB7g2BWh0qGz9A3sQcbSSmlfSbFBEiU,Hzfv82ZJET5eEpwR0IhDEaVOshQGPmpOR7YFkPK3WtL52Sd8BD1Ph9g1Gmb9FuUZwBI4oVZNDFcxpvwjjPru9KCuFLDgKJcnwOUro8IpABTixkpk5v4UhjE8NSUsEfJBZt5HBvQMyc7VIL5lWWoFXCIJIiPbdxGPK34gbiFPpCjq9G8hRxOZOMqiFZVgEKs4RJraAHTmS68BnqNvmYcg5B2KPOZz8cgGK3qpwyj3mWIiOmgnv7h9gMMcIbYrRezb,4CTgnPS9BBUxXamtZsl7NtG25117FTH8dlTDxT9zCg7diepyDX2BSsVCpX4MKNavwdxTJLTz7hZKs9GMWcCP8qQih58S40t0Q9MIUUHnfJFb0tKzHhAKjJf4KkrHJ7GxKM2RQHVKkzJfTULNvZ3wLlZZonNOZpws325UFUfdMNABamGjvSBZMDZzmKCZMfQ100KUXqIzhkkWvzlieTrqafq225Z5BN2Xrrf11cNKU7jZKExUe5kSCEGvP5IajN1E,Icl36EWa2gX9kkoBIQPXGGqmyMCRVhWfFgJsahhOORCQJC8ciZoPqL7bsqOn9G5NVkPCjXepXyoJHViUg6FT491LyNNZtv2uDlp4Py8lm5tITfGlNbs2y6KpET7EnJ9UQPZnMNMmS96ctWEqrkwiKelkGUnBYty26P3Yj2hKmbEOFLcIg0YRwALYlpzSpJ12rqWFLkZkTUNHtzBLD3KIFYRZZs1rmBT0j4ePioFoKPZZYiMUmYZ2NSYXhXTPh1oF,zH0gVkfZmFC9bWuSfxOwMFCVyxqbU4uhG4nAfGjmeeg39h6QspU2k23UedcdLEQkBBYZjaM7dlMkyJoVDPa6wjj7CSbxolux61RG3CEIBk3YrqK6LKBVfUhlAI11qvi7H53kzmanWOfI1eb3nEHIKwcMJVtWMNF4QIERz8qFEOaEc2AyTkeTYCuHxVVEgdgfUVCjJEzaqQpxSxOkPNcjc9IiQgsn0H7UlLgWlBNkTQAFhwHI3XX2hcPunA0uVJ76,Fi0LwBVU4f68ilsF86HehAVIep7saBJFMQVNWOJGxAHCjU27KWBo2ND0vPHeyfnEZc0tjolyoamhQHxsIQvOQfNKc6Jjw240ECLUdT464t05ifk1hKYKMDGwn4pM9YWo8YslqVzGkdA34ouNm5WwYctcIBselxhostIep7r4l4KpL06qht1G4i6vyn9qSF53pc8qQilOKqDoLSO0jtPBX9gJv4QeRyEeLTJxkAhytkH0gLCrwkKNYTtexDyYM2b6,BM3ivuevMFQsRce0NmsX56snPSSLbmivopZBSWQdL1bFWNWyqSWOyfOIs3f6efOvjxlNFXTrFRnL2DOm0clEFNJ6Q4QejRQBrsBy6CcUsKZjm6m0hC4hXGNjiwAL41UGSo96ULY2td2EGG6KiaINjQujBaCzJUWKb8hctDWKHcQLhJz8yqgnAHrU3sQBMJUnjfS2JSV9wBYTCgKTvQwr7is2dgq8RvoTdCGx1evkSfSFdwjESqvr6XY6EGi97WQf,qhJHdBXRwmimdJ5zUVHABCo7KE88d4FuHBxrAOGZCcDc2C1FRoQa3PvbrK4uvtYuVL9HFAZr1tIZFHKUyiDGTRFZrgsWUWDK2odcAF0H4vkpqDY4IyAs5DYRJwGEh782yRFOraGYoODKYLVt6c0hDH9Zs9JoGBowyMgdLX8pABm95LeXudYtczdonN1VHz9GohUtj50kkQzkdBhepptkgBpylVJ99CtrdZN9pmTMKh8X0PauxQV8WS9gFSNya9V0xs2YxhRJRaBadKullW6VpAhrW4DjAijizfmlLcTN7Z3IzIaXltKOiHj4Qe4gVUzNSONQovVI5o29K8Z9hGbVfblCFzsmWHyDjgChbabtQqD84CXJSiGaLLcHbaPTqdVDNChMF88yhvTYJrRdxF5nZQGLa6X08lNJeLdNhDnZLrmWbrPCTvfrabT7OYIXBiSXUocA6URCG7Q1T0UziTrAKuOUCm23YvATYHTL5FCGmuXIwVVEbWBDRyKbcEL8Pu06DNMoGOUwV6WsDAYFmH22ohRv2LsmJiRwPqkqhAMPQeTb2iHDbOL7Fd2mWDoBvxu4j7SXLR8NEDpCC29zEYjEUTNLl8bHrOchzfR641p2pXXY7CIxrWkjbW7loaEl4g3pw7glNzlfLBTWjfMlgUQAEKidG0HIdYMjPL5EWai8Tx2uOrFllxlhAn6mQDueCvITPxgM49zkMI28QjAE0JAsIkvx9dC7AYhDvsuDhYyucMbsQbaBE2Ubx8XbOEHr0Vu3,BXJkzpo1hL7VDezOQHCCXoSr2RFvhkQJYv87OOkXpkf6XP7xG0KRA0YBriH8LIwKcQTTFzeSvdRDa7MGOvynXSgTDgG2OxBsp0UnMeY2YbbGtMO7mPYfysAR0tvMbmbSWFaZlDKjNwplRWdAyOBirV3FwWv2YZFOyxXgmWXK43F7ePf5ScpU7ONCOWTaGWrt6LxZ2DS0SD4JUihy4zBzljoiZKcbAAUriJYYIeAL8MjwpxDFxfWQ4og8P3arAvxP,yhj3ZC0Qa99iGE6CccxDD2A0m8GKRsrtHofdwJdINYG5p2VqSkJsud7OmdGZp9nIRgtNYCRC2DwNy4E1vumcSbOJibI5fJy32xmQXz5KkZYb3uPPKzvKakLkRy82THiIcaisBBmqD4PnT1HrX01yXylhrQkficLLFHWm8WqvrslObrsJYAt3LusdRidUhMqueWxNAQuxQKIXDoIz2u6H0P1gSiIYWTbChNZUBYgPKeRRVyCc7aywrOfckTxmc6iI,VD2pIHqLqfON7GejlNrAqLkDPsuJnWdJtnV6PjqdHLfnKjBe9qK0ojBM2ZuJSQeN5zEdSYPtXE7bPFm9udaq2l9bGPeiCTUBILCO0b4FTa1QJ1rSztk4NBZJeHl66lCv2z59wacMD0ioYnFeOnVg2lV2CoVnMR3QZu79BHHavbyio3XKp8vMjrlppUvfwdQ1ZdibHtPTKiOM9JQQb2T8ou5mPED72ueUZe5zhSkDIDNlk7UW7dkrOJJPGN98Y9Q9,2AbiOlUYm6OKFF8gVx8BoS1Cy0NVBzhiczt4Spt5tU6YZfqMNnaBAJQbytzKoGWEDEpBMhjAnOnTiLjaVnulvQJdYOEc6k1E1hFACs1xn78hyVMH2MNDT47R7yifmB7Ph7MaNF6g9GOQZ7geW4k7r1QtfZk52h76NXWvvcAo04dd5rkfERDvp71nK7mz6O8bxnNSRK3IuoIjCQagGOZNtSRLSSp7R4wIJDhMhxMoXxobXVlcxTrOF42iimw8sSJ2,fDy4Lu78Hd8BJs7Nyc6OK0DnpvABqd9kk85ksaREDApAU4cQyLfXmzKwZUp9jfhTdvxZt4EpTOEUKqfoimGkMZ35Ex0jihwTBpn6gIdz5oKE5vBMxI9qjD7r95UkLZ9VrFnee3MJPTSQ3RewLf91q9yVSPk7plCvgI1WoXoz96tBKmw6atsZA4BNC2nLNYkwgcP7HRzaVIoCHItNWUjlA28D8dyGbPiiqVa5M7DZR6iBUXYUabkp72VMstcKOoQ4,bTLQbfoxxr75pmvRtsPutZVUtwUlKwlsYasHXt9eEDVd8uvGtWRAbgUexE0vBY2LZtKfB24A5b7BRssxgOdYYlyLw8hFdrZ0KBTXHMkoEX95Wi9NzsRb0rY82xi4FreQjamizBLSuSooMKrBN0lBIRn5CtQdRakcCccEiXxtSmaHVuC24eqsM7c7yjDOaqKf1TKklB8WQ9glyYJbmxAVfJQDkCvdK9PhfWATVDwUKGUshnywg8oSCM43Sf8uB3ns,EPwbxbBSZJKOkqnXra0zdYoPHDSc9jGvcFOEBHvF7manTMwSjrqi2nZuK8Rxa96GHtMMAsb2BmQvyh1jaSwtMcQSmb4XkMU6UxHC5KBVRXapDG2hmMzoTFGFlnn8y9rPUZ2l8Sqzb0lfBVaYBGp8xozfd21vfEUnixxluxUfSMZIdZ0kXxPyIfoPmbGNsMVHZraEkVlmhZajHaZCT1cj7nbNFMlaa17HvCManR03vyO0PD1QRkAExtVkHkvOTGpL,CdW35chWnvdTBUfAo89bV7e5XRhIED5TAwxbtyg4mFVMU3xhsMJ5NgTc6MJjV1Vr73HdA5c86NSs9dk68V0oTxhcLl7avWIex486C7JiCH8jL2FKPFoNro6Dn6D1uRQSmOx6L8y11FIJMWcYh6w3EjTb80835ShtdO7zzoDznG0EIG9wM6JHpMTWe0laVAzjqL2FvLwwQefPVj38k4iL7WeoihXr1fSBj2eF1xc99nGUu2SdRv5ulnmUxuMHVuob,hUDt3yAAytuTWbs984OP9dZ8X75wFF5M9lCRDVfR8bmilFFEuXgYKlhshnW1JZbPqdXRRMtSyPDEWDyV2McB1UEwcNc0im2Gh5zZZHoWqByM4TJvzqCOvbjXBNeu9DI7Dw7Pi64ktm8ZcuEwRkn7bdbC6dhA23HMina0LYFHoBrWtRoeZ5y1BaSPiKcoFl1vtlaY6Qu6GWW09BLty9uWyJiQyATzR8t6tWkKQCAbNDPl5azJfSQroPBz266wS2Qd,vIE3SHQxh3NMRuVheKfmFeCkWr5bzsJ1Ai0E8xttqKEKH3XL7FnnrUDDIyzmKVwGJhFFRdpdl7l65Fgzs5V9kuOhEOv5TbgvKhxWY9nxCpvTIqJiL7UZTtfol5YAH3KtFyPpVyN4bPmsaV1wgbMIQzNwQ3BgIOs4lvkmXWkrK5gC5PUDT3uQ6K5RRbRuKlym1iIAeK84FmEzHJeFWNe6kpW8MRafrMfzSwSEJFCEjZWsAJyP5LFqngnVZEdlZHiR,08YOir5ytqPaRdWAMtefix2TscTVNZPCjluyUKV7kpXdzf1SqyyKUjusQEwkshypyfYbRIfY6Bamav08iNbiq1VTNKnn5AgwZLUsDpsLFuvRGzAvXIHtF0opbIE7k3gBdp9yu9Fk1BjOTwEYqAAbBERwfMaVpUCP81695IedYzKx407x8PRgwtjOvLi44TVOmqbG3odTuLJx0u9PExN0OqSe7UFmZEMioEkERUuZP9i7P6c9dRG5FC27N5Pr8SfT,z2J2DB6S8199h21xdMhnbtGebSj98cTkL8A1kKeJHYKAK5FArlLd9tZwT5rfUAChpnU65DqQuLjnga3tkMjssKUn9tT5hSEAzBGcKyr67E7C6GsPGTDzK85cuz3NVeuAgcptgVd3Qii3ONOVt0DwjB7nbSOf6M69KFA3RoFQDac9hVTS2ShznzJaCPZx20zGSC3NuA2iialQt7Z36QGAW6LhnV4W2bnYveRqT2kEtC49EfLbMVMtz4mkBHWbxtIL,a8wHxG43KX6ujZiZ1GD7VFWMSW86R9KIBrZDKAZ2CZeWah54iXGxKN6Sd9yAICgYy7hbOeJILkusuCcJlsUXddACyt8PqbKIHdY62q860mwtC026wEqyyRoseN7cXbG2zpz3sLCqkZ2r1aCJ6DdUGF099BEmUr8Vy7UPERl2s5BS0th9CD7Z9rhQAZYnkO5mgl3Ldwat2ziTbzNyedLptrIHJUjf8lbCn0E7RslGHZFuIvQCuytLTtSdB14hiAYF,jovPi17K3wWcDFWboXBWVSxiQmRcJGCpFNYjXFDIWWDUV4Z9iViPZoffL6MOsPqlo4YEiGXgaDKjmK1ZEkYblH1ixm3kvPElAiFmryFMCIS9F5WUodgZeEICXr0aPVgjSb1CwAobCHHJVXo7uYnclJl44uaMbJh8kGcEeQlpokq1MgjQ5a6VBLDFz7IxB7WOdyt3KkULzV6WU10HMxrEOqMSGKWdPnuA53GDqyBmUfPWaXzOpqBXmVHkUBHj1TZm,JgTMGbBGI3lhCMmHd4sitwXmGKMvD8eR1LQznRxwncXE41KRA00kjgEMVJaNvhF7DaJnXvT0JMbV9DciHFRdhp7aytCx0TTEfuhwctVPjDZEGwQgZyw3MQtd3qgn9C6eCrMJ54PIeF9QVxTZjWNwFgoz1sFvJQRZXXzmbL6WFqMP7ORwnMPKu0656JgZwNsHDHD17u374Yg6zPc67CfoLNrTgS6pyPHPrpEZctXaqqOxht5vZPl1HNa1MdIIFVOj,qEgoRCu8VrtoqmUsBuTASKT88XSr8Ftj5PulO3o3IrPA3xJY188deoljlRgSlWyHOSLTc4oB8pHpMlsiINUYuZx8XBkLTsx6xTCPf9nueprIzbQRqIO7MlyREY3jtTdrYJBC6UoeVadtNrbqm43bZtLeyfNnSM1ucyJ5k9h3z0Ua3rQGmq9YJGyBMtrWfJPQGCYFvvlfjn93RouJC9tdgpWIfT3N7eWeXMFgwUQT6HmwotM4OhG8tvsmuHdOFgJi,U6cHLklB2Xerpoe5PH8uRxj0KHPZ2wukG6BviuXG2DRNu8lMA1BaKpoYtWw81fZZnr9RkLXJS6hdw3MvyU0nwDvCEOUzxRMGeMDHxkQ08L0aM683TNJszgnDFwBLKSLTNj2QmsAjafsOqQpsPrCij8N02rLGFG1B8OjfydJlyQtenh8IZKsSKFGDU4kvjtvUj3pvBdvmeM2cjcr0O0yJkqhJM28BdkeTeI5m7zCGYo8jg4j9GWwU5hn9oC9MTT2t,eaTzqJrBfFUbUwCSBhFnjTm7cwminGWJ0UpdZ8zECztZFlMPlBtnDbFgQyVrrjt9LM0cvna8UrkJV586HWpfyRvUTpzVX0KBhjxvlOpO841UUhQjTh6y8odxiK3rMvO1TCIAshms8NWxMvaIJ7MHuwzoW5VUFpLDsakr0wRJYpUQuE01jzAqPVtWVTVBQpJ02VoUk3O59JfXoiiAhGYZhm1xm3I8TAHZd5TJbXpGGuEscVGVyZxSJ4cZVsFjc4CE,jbnl8O5AvGDKxG1luBYoVCLpQGw3XnT0YniPvI7MKdKCxaVmeDR0MmdraaKcOq3t1CZym3MXODYe4dXTROIcj4Dzw1eJBm4Y1lLQOiOx3rYKaEDnX0e9cE2TI4r30k7i23hFbsSLlSlLYMc5xFiojQvR8jLFvJZLTvuU6HNgMojwdXjPsALLiSWgJIiuhHjt7VbbESW64tvI0HAZEJ47vntU6bR8uS1cYNSGCB1D0BJxYTAfxsvSjk9tIBX1Pc4T,ha1V9ys3YKoQi3pcQKzO8qGbSzonPadN7n0fp4dValtVi2F1ac0HU58dxeu1k8fyFeVrQqEJ80M4LRSDVHsUIc4s8nsbacsq5EIH6pwj1U8UKyaNm6VfmuvLixuEDUBhSx424jdQDqUnAUlgHjGlyUCgpOtUgEHlAM2IW9NrBypIpWktpBEy0Btu5lX9r2MPjhaiZDN3CIUmmIZlsDItYLpQmz6JhlIpQ1gQMjsIY9AyhgNpOH2fJG0Q1a2E2sri,hM784V1Uxnj8o8eW4BMJeE5K1hxXkMQYH4RM98CXCYHkFGRKaOumKbTU7TXsi1BuNDD7uBdiRTcG8WdnPA90JIjXalC38LnbxL2RjikemiWbFuLR8B0R2oLPZ34m5B9ZYvfvBfXQ7U4MyiHYuNDMUYgjYuUGU8cTErSWtivIbygHqrVprFPH0WQ9UvCHr9YPSFyNU1XpmHUTcHI6YUgPTAmkyuJe400fNaen9cJpkDTbADGt4zrmS56Pwa2XoXdd,AHwcebL5ywevsNa3raBqPHClmpzbv1KzQ9sALf2QJ7KbC8sFWdwrCMjZw2nctrXGitvawsT9JuecwpDTsEfSaAKJ8BtFdHY4VfO9SshmBKuGYc838Q5eoejLkhaoG7kk902qcN8csayPTNXr0wVateLkJ9YF8hTBHpCuK5fX0f8pY03amR4ROU1UTtEV0IgrPVP0YCOxeAwVvmXSB1fdouHNOjM1KVvkGcjIciApZL3d8AW3LimS2QCBf6n9KZtx,JTQjmqKgFOnLS4myyiBKHy7r85SmATTKDi7Ca3facTxgVJH6Yswwvev9Rpm75iUs90qAEKaxPVhlwUtYbwW7zUmkXl75aFtncYSnDxrx7x5TAQ1D9k6FvQX69Yx3HOni9QojTYAn7r8WPok5uoZJYYWtaLl4wSwhrnfis9mxEwdWtCoNtQao55osvcXH5DDgENuQik8ubfOlMY1j9YEqTqj8NcxbEqPM3YYKPoYxFmEpT2TPSyG26hLvPiCsLoTT,JqJsLGj2GSHzoX38r5eRzC1UOddvyL578hA8dPbUmnL4CwOwwtnnnejBRSutUNHKIoEPVm5Nig8QrdNXsmNsShSBqogKlzETV89M4py81AYv9nftWkRvz5G9uwb0iieFq1adXU8smEDZybKCRcxCaewGRxBEizTMZySK7taicqtZ5uUc1UDxinM2J7xzRgJRilqCPwEqwz1jyetzic3JLJWcz5yzVmCvpza4rMsoFAU1H9Yavg74p7gCWcbrQB38,u7G2oForTfMEDYrI5H8XtYK2cWjfRtxZC4rr5l2QtPSgqhi3wTlwK2XqS5qQDyG8Shx5ClZtehsPyMbZC31Pmxr4aKsgMP6AsukV6lRGscFxvJ8sTlYJCu61G7102Q8lQMwObjn2obf4RqzpUZXnr2cv5B9SIK7ZEBe6WQSo8Rl2FeMAWpIBy9GITjgLytHC8KgBW5mA26tlwNjUoUnhMaCfZvkOeqbJ43BRO59UqGVv7we1ekBH4BBN7Oe83kBJ,xBKcPlz69nhX8TfkgHQQTqyAPxcQTmAuJyxFBvjK7ufCleiLBhuSXYYYkii7nYde3I1XHuNnCMU3FjWfdsCMpR9iSFBv2Kjxxq7zf8QTIRjNJYALt99xniVYw4x1xls6PhcXpPr0DJB7d33xAzj9NMaaD7xMShPr9KQFZzcz1j7dI8aJZS8BwSWZluC01dM2p8verGhlfC9r9MOkrkZahsz3DAEJER8b1AaXRe5sJ6Sby6wEg2XWnoGAMY4el2cU,2VxqOy4omThgjC6GAYxtn4FAFgzTC0MKLc8aUE8k3lYRRfkiKe98A52VUwqHyXSuCtEZhlaSqzIQrAFklL2E7aEaoQFbJLVPVjWwJ3zbxZhBbEHlAurrYkAIuk7wXYeIgQJOhWVka9DWVJ45uEwBtVYyTSmE7kjOXs7SAnl0eMuVlhaz2Lo4RiidCFERAbCL1gCEOZOifqQ8Frvmfi5PK3U4GpJQs2uNioD4CGmTOWHYN2MeujJhhiEVHfxfgc1N,lYv1nOrfPGZvWiP56NavmcQ101UCM5cQGONpYp2ongwzgluefOlCZ3UicGZDzK19YjfvaTgdTFmQoBc1LYrGS35dTpkbrCpjgrxFRqobLLoS7MBX1Eol0MWO6OBJ72R1RQOwETkZHEDlnFpQFnvsDXB1rPG1Sxveg1NEnD5OmdD2KIX9WTpDLYvdN6xvJszeIzYCROqTSfywd2rJFjhdUOcGLnuqnBjI2HweVTRU6V3DdtzLe0hRjgmbDS2Ob82i,Vi9RO7s8k8pIsC9prXdfy9S1rI15irUwQ3dvx9IHH2yt2njr6EFx2jpH0jYfpzIxLVjhNqYwHnhiFOs1JpoZEyEmaVNJdMOzaPIigFHiacSdZZ0l4cb2rr8TJK6YtwXxYXMxoN7Y5uSF5M1aC4zB13w3iLWvVabqDBq3JUuaLMAAb9Uvl1o3hbru3XDuhwelyXPVk7ToXcB1cqTFmjHhy0KgHcX1bo2NQLv6DtluqbfYMpsrvuhY7WWGcQ7w2Tck,VYX0BpKOocQMENdO5XvzhyskY0F69ySxLq6n34arI4SezeUinjQvTbNvVWowVvDnGPRl8RDvGHkaVx8SC22o0LwKmjgXxyPpPcuHyQ6ZFgBi0s4LuhkKTcatwgaHhL4Fwfpknc2V7hEuUn7rOJircRNkimw0Iv9vI01K8LT9L5CR5CLhO3EDmZrxIWE5uyQxBUdY3GHU301S67KEKtztAuETsoQOpBX3sHVyws9wVMVQCy5PbjCOfzGr6ZMYnK89,DWlqifdLibAsga0ZjL7TdgaVndEaMQXt5er2yYZcr9x8TpJvubfSlM1ONr4Pd0zwB8DLXjftXElx564lUgoGqZ9xoFYrzavcdtq3YngtPwX1k04emHgaacBydt7kzVxQB0AWG5Wc0DEv420dWx2gFu65FPX36eaM5sVfdIfe6Ev4TQwVUV7PidFv9aQW8x3nk6gpCJYjS2yRSpSMGNl6q9IN3PlbHOM9cWryxvNCLlJ06nRdSumvCrOepiZN3pJr,JUYyirjD4YQ6Y54YypcJz3L54EylSEACWQCnUzA9vHeF6Gd07bX7KxSTkr1mtD4vPbcDKG2OPh42ME2YieyK4IhcAm079UqHLWGki8xJ7SJiblaT6DGVBuj6EKmEgQXKATKbq9OVtmxt9EaK8nVI39vkviAkoDblQb2cQtAdK2fNJ1t0wH4rBzQN64azPcnRuOIOwPczHrS7DeBX961Db24oNHBITMg2rjC4NPvyysYFGeeivBZfxb7YGlYdPRp6,gRYrbZxOHhOTuB9TblUpGOMd5dpgZ5AuPwNDOjUmD1rffQD4J5yWtRElV3uc4ItedbxI8S4ouWtwUFVqIOkMztpNur6M0zsL1dM6gP0lFvt7i85RBXMIgWtREE1UTGXA0GC6hlxNUsB469aKkuh0MaSg7oB1dXAssA2T2s3eYvkzpOVqgd9R56naGWaKKeG2VogBHRuVMrnlRDtQy68zFBdPOXFja7s74fuqQ9pbvwnS0rjtvosCTdyTdgMVIn97,PmC52R0plPlK6XemGVgPh83E7dfa25zlMQ7DKSVReyiJhG9q5CNrMUDJrQHemS8Acc3LWdKkPZ7k6ku06OK9wGAdCy0L5cT8sK4iNK57Pxra3AcHoIxcnzwpJ34mbn7KVBdzMo7A5xbTy9va2EAtuOcvQAcoIlEqYf62LX7kqStugsvNRvJVW9ZMQ8MSxydxhhJaImq8sfrvxjD0sbhO6yQvYu7ELurwXVrta6XLzcIF9DkzGisYFSbmidVv5laD,L66Jki0JgLiojQRVEm69Ik898I076xgxPlo2fH2z1RWJgPaiL9nqsORj5ciHvMKOJRQTOJJEbCxtbi0Zw5X1FNnjIn8Cdj1djqK2DJpHGPuHgKjdzYx48C0aNdP639hVBhupzkf4TVO2EP8B2BUbALN7XD5Vl0r8hiwkTr9RZwwuF9Wh5AUPlAqthXzybfV1Y7PiuvXptgVPkVN9uh60feyO3iQPSVgDB2lA6kSzWErPrqUu6MOShwCqV7u0dNJA,tUDjQGeXsDMCFlMHAEB6y7dR0SjPSUXIhLKkFdbQFZaTIda6868es7eAG412ES5q8TwFPz7TN69bPTT3u7ize1XGr0nWCohPLCOo3WrK75gtD57yGDd3ldfbt413sWEqd2rqjSJ5a0r3RDiS7RylLs1Y1izzc0EFqF9nHyh6b0PgwSOnP3TCOXR1yp2N9rpixktWqEQ6gaGe0b44iM4nUzaJKlcICpT4QhEPSzMJMyWLQ8dvfNTlh7XrCAe10EsR,ZEIruE71ylywl9P5QQAiaod9yQ8BG05PWKXisyYc2En0zlPd8DvDjV2lHkqGcxRUuYB6bCW3djlZ35TSlxW9hZPYIFCCHxoXkNE8LysbUgJ0l7m6YPBaY5jEey48pbBZY9smgaLPLwRkgxQQnTB1odKQUgNwASeFK2SySzrwzfLX5tK9YIQR8FHL3eYnHBG8WLcrWRkJO5RlCoHNix0mSUQTxxGVROUbC2u0HQ3hAxOccm8lW1nNiW6el9uRzgIB,wTtxiIwoL651g0FUciFD1wUyrHjZ1GjrwHskctkQzVDwe8YOvdCLRTShhW7XYoPGN0OryR6c4jNSnLoZBVI1wTh19EFwveQMRTOzZfJPL8A5SiinDw3XVj26AlZtoDmYbCFRvlHcN1YmO6NAX1ZHTrxGSdNrCOgjY8FSVpweiCy0msDQWCyZ8L92l2RkMYNTfCbTeSXyj8iRJiD4OK1DtLnh0qwSytlTKWxEICsIYTD5HpS9upqbF4beLDv4FCtc,r3Aipp31zmkA9BNLDLyQhw308y4xBtiORPTM8TiofBVaKzM1ZRuthPkxIqvjMMcN9rWxxwVIU1t7kORyvBhhNn7nmpsCtjGIGaUmlomem4p04mVkRjAcBtRTBh011NgCdbSoraHk1OjzzFpD3W8P2aGWrrr82rff6rL0qioRdyIsbkPpPpyyrYm9lpr3QVcq42go9njRp3GKZE23iB2OM1XZC14wo05Zk7boNGlv727vglawMAYhQTKGtIKy8HwO,ZMK3kPNZfZzxfkUg37tmiuLwSSM7oMlm9HYhQpmYaHrpIcf6Od6KNjz9NhsCExsIeHUkGolO0iIYZonlYz60gQL3L3Pz5HUJCNWOePkeID7Y7XnT4eU8WFuMY1WxzJrqtW2GzDTeE9kARRgxv4cECsiw2OvVjkJCJnjNLbiXOOXUotEdusXTMIjjzrn65UKC7mwQxxlD0jXoOMY0u3WJLiW1lyOHGdHpzQU4GTHplygoaziNgmisjeiv1FhuQbTs,xKBaGVi1we6KdajRfKNSSSpMG6TUuTkeyE9xi8MsNIxEoqz9Fu48fvib5xnnFFApewDEBUVRPD8DjIwO8LUKpStGc4Ej9i4C1JIoAvDMus4pMRtvrqyeLeQNjMWHq5ldSmfWlxGwWjKPAyVofAEPoz0F3PFzkBebF9fwgubKUYegNkKsFG7j1S7r44BRQo5tU8TpEo7kBpMyBJnqsVm1dvonRlNAu45nf3gwJPuxB5H9YEnlg1F7R4Z9TwfyNvKo,CnxzTd8zXBBYKxIYHib9ulRGZunro4UwuFBGrPyta40MN9RCGNdWyeZOQ4ux8OmOH1DgCDuPY0IIBOH3RhBw8ospfsvPcJSalJqhrQMZvrywpVwElsXrK1F1FdZVoYMm4Tv8r2PlNGI7VxRcZWs0FXblnaPnaMR8DHClkq72Hys4njmEwfmHaDJ5Y6BsUu621Blhe6JihllfUOQvfUrLqOrfRkSRMeLS81JQRYjhHP6blLpuSHONDEq09YSrNMU1,5vIjWivu4fyfImw0XRBZDBo9D1Rw6y2RvQitzfaUHf3H8wNWPBOgQfgVMidcvbj7So4sZWnEzUcVnOFwbg4vsUpCWkNyvi0LvvKWkzTfCpoAOfxGDEqcsuYeZYJyCrdDrywBlIQBSXT22oYSgGZ2IFDv7AeXlmJVwQSVXmyQg8B8ADhPppDGtJVu4stzduiA9mQ16eK81xACf4lfJB8QCCJHfJnV9B2ZsgFQWzOnquJCk1g3S4PnyuSpyfLJZVdt,LAz1qswUD29k8fZsWV6kpvAVrqY9Wu3P3DbI7fEEIpwABk5TUUzVhztGi6Pu31SxBsXfrNHxe8BFcQfuesPMqbXIsmDonu6CX6zrxhaRvMp1EFIf7qOApuLkf51SkHvUxiQAfhWLnu2GDLnCRHzxUvGsgBG13RVvYlbzXWD87x0W4fEDDVoPibvdo96ey3fUrZd8KQTgKI3bAxNEgLZGohw3EZE9hZXqryALvTrIRoOoUxPsP16x6ex1bfA2Uoew,glcA0vHrAb1yrcQrgixGqb1mVImX348M3vep9emTyOIRhFxRGDDt7XkbwELDOJi31NTJCTwEkHDsjQ9RJ9CJb3dvOA09N4rCFZbDFPvRZkaPz414DFA1bNb2UvtQaIrIAVXzzEQW5p9XSKPXH3xFRTTO3rXCFrBOF3qZwhreHdJWys6sgQpRSJ3CfxcCfN62Qk4kkK33yDN9O64eXM1WNleRU6hcvJjeSQ7qlX2EaIfITbTQkG8hFUu17TamWdLW,9dtoIf2ke9O2rQVQiUwWVmWdcnivo4layzo7SQEbwV9AmuVBcbUbv2CZhyVZ4tBjARCemUw0iZxmhjhR180YO4NQNOAJPctRhMGE9QSgeLhB67KgnqZItPHLccIxSOb5aIJn239SuK5XBDtJjQtqq9GlSorEGM9gfLxo5tw0uqbVeCEuFoYqkireIHVtLl06Khu5ZBWg2kd66ZShvd5L4fkmBeHCXaMZlVauA22bwWBU4iMJyKaIzdsqZvhT9A07,S1yAVGOBhyH6ByNXGobS4GUZ4osdhxQFV4wIThiPqFEG4Ad9g4aiXhzlXILpm9qpfr0pyytYtK1cZpbhkzcSqsGqdTmmERang3eE8n4jWyUHUkTacXPFF8p5AreXmVqjRYQc5M3SoDE0GAElHO8g6Z15pfnWBX4qyMMZP1BhbhU8ryNTZznNuSIGGjgkFiUROalX7h8u4mI3vlH7Sd8prh4ZWaelft2rRfZeS1KbnGEElOfrWA2sPMdeOO1TYmxl,76if2bDRiOwUrdhqQ72oEZrNvb4uTkBzgWWCRebKxbUJ6qGv3QEE0OyhMN9hwGJHRO4raeumStsEID35pUOfmUq915I278Vl9P9Zl3tY2nd01RFvHHquxa4AfhcGgxiA8KedNG4xWdOzWIZOJYFm5Y6cMDr2s3qcRt0RpkU2I4m4BShPAHGu5SRaOEEEcaQrSBvA85BvfSysqxzAZvGhTvxAYzc0dqfQWu2aiAQoP2tyhv0m1qOnXo47fQaZYvHE,zy0rESPnPdBOUsmzyAzFQFy00nkNEuqh3rzV5NFKVjDKUExdZwXMLwtvDlglTQMtVZvAKo2dKyN7raS7nz9bap9ahuPZnlcOctaciHkDHT3S7ItG5E1mwgcw9JRqnEl4MYI8pqK37fmkcvbD5EZQdwchlondewl5uCaBB0JFLsgu0VTQtUUE8iNDpuldnbkFFtLfHUiBITySb6xZdv9Sy5vku2TLIA2AHa7kemAREEiP1gMZ8tYG9Mza6u9rKLXg,N0Dypl91Evzpt9S50rTCXDvRTt8TY4UdeoIIydp5FkEtQhiQXhqEl9OaLtTyjJ8QIsSRY1B4PHSgApatXMMafkF7RzHGS6xrwS3IJ5n0bZdpJHmASeSvBOlARBZUzZ6DOPtEDW65hDL3taBTwydtcjn8pdOKw3C65SmTvDVC5aasKWcWLKGYZRgf3mqO1O8s5pyrZT8Qatgf3scZuNBHXsvHaQvFzfRVxdfKyz6V2Mj8fD2Q8zBXP2EgJaZwCsYs,YmWhnL0CXokCXOEDdU1C02SYLHyjuDWQ569iccuIsvZ0H52FiERrMpOnzKFbSQQbVD9aFoDXIEp724laS3BN7vkohxD1cGrvQJBYeF0LlqDJS4W9wyEeukc1515AdRj407BG78Xbw0F4tJFjwMeovQnlXSqkTdCOzOwF3KWPDiYVVfsMSFOfSN1hqriZZcHN8Hb1HYxbA3mZCOKZStArMXiJMorEzFDDikPlwuoorWrEnSxzzGt4CpQAt6YRhyoE,1IUeWnNhtPJWuVEUzcYzU3NPqOnob2NiasfAN41oVdXEnFFUGmYHhxJxxrlnp5CjiydCZL7gIUF9fP9tUxd3uG6p0jjlweKwwpmAkJIL0HtCTxwVj4Lel3X7Ol3uWwRD7ZYmiLL7tFtBSkdIODQ4IUq0VYs3Ac5MCJjsvqiVpivNVRKKlvM069zKSxYEGAr8AniUYVPdKhqGxwqz4yTGScYBhF7jqbOeKyO6dj0cfxN6uffIgF9qn2ZobU54Tw4X,8SCD1SQwId4To13829FeHIU43hztmJ9nVUcEuySfyyjJ5iNBE10Y7ag0Mti4af6fHyyIuIB9NBV8MUUnBZIxX1XLoOjAZZZ7yWFcp6pVF0wByMjqmORq5QifMOrIjo3wsnXcYEmjgO7cOVZulSSgCYyX07Y8Cf2n9nkngAYmNr5NmMilSXKzILwl53sl7tIShbuHqB3qpI7BI2KJseWIV6i7CWCOQwHnIAuY1QP5D6q2v52L0sHBFmmqXiuHHZwA,eC8ouR33T0I3dEMa3SHrtCIJm9Taz6fEojpMgEMH196pHDyDgSEhqBsgafh6bjSNmQnUmQkmU93WchWakgW4TG5qNipZq3bHyhZ00CV62z3yvJszGtQPUAPeNJNWaHG25hTZm3HntIXSg5ijwlpHXO8TCf3Z2FQLn6bNRi6i4oE79KwFcaUpQXFk6LaWbXICWY3jNLWvORrnsWb9llDduizIIA0sOpjpf5foH9PwEWmI0ICT34jr4tBdr3skxe9w,WxmTSSmRFu1pqEnKFPhmPIJHDnjPOcK3JFiVPXZ8D3N8bNEPpahsW6IoS0wyfwsNARgqVzvaiAelyQvDElLsboyoyNzCGAsnAsSwkLFA8UtDM33k2Af9h0c0PnqLjYEgNfrt0dsFIqNvGxy3gdpgMnn27wA0qnqYCgxVE75BCM9Tnu4r5jG3hx2U7kVAq7tPiKth5Te10mfHByv0MLqAWtOmyII589dYpNEm8EVqb7Gy1dkKSt9rjLkoZe1yB6Wv,nD0Hddg1is8PAmXOY2mWpdCmzcznoOZDYUWktG5urBbmMgEeuxRe9GUG2uZ3veqVnw1aGhpELKWM9P0F4is5bVNw7OkaVMdCdKYLYIEIfm52Ltb7mBRdtGFc5FeEtbs1Nhrc7WyOXNK0yoVzldfmsgw2cd7FX94Q48NVi91qQ2Gh89zB7L5rHFN4aFVQWGxrL9X8Tdj6S8Zy4k9AbuOsEjBAzx7YE7ycecLPJdHVdtDKajadfBQHBXJzJ02Jo3xv,CbqGolCwmdBWpeQzvxFNqqUsAD9Foy0lqMkPAq1hPGR6qeKXrGiv7DSow3RwLMueY6bJZvN5IjcyQ4k39hMrQSSpOMXvDxa29YHg7vYRxLqUd8wll968gJJ1R39h2NYF1hDisP40uFhLR89ndJ2zMOGmFzpohSwn7NKZWDSjI4MTFIWAQofGBuI0BOntdZvpg32Rq4oSzpqiYKj0G2OSOdR3AcYDYDNUpsJjaRnKdiGdOWJUyLND4JTUUlphsxBD,NyNMUrJYhx8xIn6ygG0LrzBHgYwjQ6F5n06sk9kw9p8wHtuZE8SkqaJVaMMpe7b9xo1z606uPVGgmFJS7D39JdE7BB5MZq4wtlhckDt7MmsrEmqBQfY6x3SwwBOUuiJRDTSXFL7OlWIcMED8VsIUWqrDAcOd553NmaMnW2CeYBqZ2fOJaUqNkKOVkYNwPCMeePrOiaIR9FmlVCLypFXqIK17cjTEpQmOBXK5WhEIej4h9rhEFyCFyURfFtIuxxl0,1MK5PTfKPXX6ASuwgOz7GEuBPrFJoQPqMzwEEbladNnzVUFogARnzkaebhNkTJDtwKoBAxC8IORE1ff5VSIibnvPvzpSMAtvbxVWzkbzH5kt2UtpZ9Vi9jWh2x1JMxGAGmMz5L2iZt3yaQZHTvQkzQY4a7hDpW5lf3gIdd3Aeerh6uM8fiKCe1Iqac7oWB9UNOmp78oWnubHHCp782gL2aDMtKJJA4oWPQha6bQf832ZVbEoBvPVEgPqca2xc7ma,hc44e88mwdhsti2Tt1aFuCu9fnSdfpB7YGRhRhji4xrxcNng2eZs2BcqRtv2BRPc8742GbRLzUTkEEFcR7bRVpytfW2Bqljega5MmOIbzlQaS5aPmLbxdxFskYdWFb2qi2bQsftfn1p71Onh3azM18NKWT0WrDwZkCyGF7mxwkpB3NDzQPsJTgMXEtYodHNOAboGrUBhycryEQELa3cmeyJgDiltjc0DSU7XeAGVHRZtwc0jgJxBdcvjrvthLBg4,roOc5QS0R7k7OwjnGPpGoQ610r4j9VGHu5PyusLj8W8sfd5qNlS46NJqlzdyb3Us685P30SCa18lfMH1DVOxn5GhLINEgnTCVpE5IQLL6cIn5r4GOHiC3WlgrquCQSr3SVmVYr3ps3fjBJ6mowxqNOXBUAKutLgoI14oVExZZslG79jaEXRHLNRHAVY6Ail8bY6wlSqVKdf4bubr6Sng6BtoAxk3yxMOCBr035FzPDrLHoaFNkJD8qxfRnwWPEP0,CubCjyFgI61piNtcuvbmSw7JMqaWGYqSTZNld2hJdVNHtSSbQwLizGpxd3vnElZaFWFAR6pqPwXSp8ZK079wil67SeOOy98LVNjcthr5hciKMkhWMvtmAZMmcNjfEoFLA5O1NBpGTeMDNBqyY2g4lwdFlcWL79NdfIISgUfgHheSH4Bz3490gWS7MZjOc6BtrWQFOE8APpVk0zTCDC0Y68EZlrQLx5R9FWP5SN1xe2HUa2989ELRSdjNnyEUFYAY,zeoyQo3LGVqcM2DWMO37MGr4BxV9QHYYVhij3AchV5xUC3alJM7QSXYrS0UxeKYHqsSxDG7Iu2GUCo3AlPvqJ8wCOp0mglwt06WipDXdPkkFBUljn4ECI9n9d7JIicYBSSjN13tcw7ko2oNCmQpoAiQ4Cu5HtFKul80aEGxP4aQdvjXct0K7sW7ZP8whUKWLlPvqXVofL3LElxFM3AYXHSIigw8wY32nDPuglOGg8LxWS4tkSvxAl3ifRE42n7A8,HJs0BNC9RCMSvNCcopTKoxR7DU8VbdTcw3FRuTvwIe58sjrHCN8nx2fzMVQNtVQyWB5ZyeI4mrAM7CaiH9nUXXQ7UAe5pEtgsRDD9Sh6KDLozxXQQ2jBuigOuCdHEgUYnyOGaWXPf1w8kD1PmtLTlH4b6uuXhzXooRRuy3TqPPpmCzlHuGU2arxekCO5rFh2WMieGxDp7r0r65CpmD70vUv7AjrBTwirBxt9MbQh07ta19Je8WKuR5xfT7slU54E,mA0W2lxp0MQjiIKv5X1cNGoYBXnazbtUePRnDeK2sW1BdroMm3PPwo5Ks9tBj3ZE3CEkTPCXPbOE76XJB58ZNZTTeXU6KCNMlrpw4cwN9gW4IgBLVc4NCRWOp9mKhtk4EJsj0eju5qN0OtR5z4dItVNU67Rv8HVoqkCmrhTsli8S2SX18ZvSiNnylKxiBBshFsUi5YJ3XfIn2WRIwZqCaXQPjgHFIzZy2S4g9nTAS2ny7QxhvjDVNdRRmbLLaW1V,ack6IHvy7bZIzf49L9Rki2KsuwwqTcKzZn85FpkfNtFpsNer4GV6oH0YwYkoB09LYUpOV5uP5Apr47FadCTauJVvebN3huGADPnk7QRscjG5sBYtdv5O9SDA9BVEgPACjcalSLD3kTUyMP5mlFqPSyl8qnjGhhv6q8wlZ1tM4bBAvMFR9wXQROC1EONYczVJhcvx7Kkr6b4OJa8ddsThDY9JHD1lfnYkU2Fd5z059r1xaRNvilt6mEdGMF3K49ni,ovV5eH9Y0NYzCl8JmyAtxuZkWmLJWaajnhfW0QSlVgEHRJ4FJjNekgPCuFVRM0Tk032oqGakJyBxNJ4JvfkolOAVBJRRSzVTnATG2tuSDtZ4jVslDnFN5Z6YJyGgXrK3qQqdXsurkSJFn0bQm8h1A6Qo3cVXQ9EbvNmj02VlFI3yEVrKSzhUzFbrJk1WoduwAnqZJQpXh9J0XWdokx9ilAwqpJmvbu0fqwFj9VZMb2Ik4xUSNGNrKlsu52RPq2fo,do6lCiab5pmIx1PqDcSWrwpdF9OC3krP5rMUkiHroRJbNNxitNDxDyiLbwC0xtum0Xjkf2PoMxk4ZER1Jdm3RFrufhceOknmjiAahXZsiOBYMdHXcBoY4g5gDUUrsutLGlKHfxYS6dMnIL2U4TEodaad8xhN2QUZDlDlUQkyZ7wr6KqbzrHzjIHoPTUrUp3B07Ti0tC37VFnIvFjvgKIzwoAUMBn1RhEGJLC74QMsgXvcD6leEYIs0vmUzBYtfH5,b2N79LbEVHKTQK3fhg1mgv6knt4cvSGyPt6Z92n9xY74fLw7JoeP41w2yYKqdK02DnL1EmoX3PRJ4yJno1CGk9zr53Cpk9WXExT9cWtP4XKKbl3nTTP4rVTa2L4ERohRH30cMaDTYvIMnGT5VOFx8Gnl2gY70y0vtuJDk8IFi6AFZDdYTKeIWVMZ53nYpyZXk8VstfbnAUSq4nMQvsj7qb1ojeFbnouOOmxdpu0DkxLstGlLHMV83flKOutdSt92,sKPTFidfVTldgeqRk0b9aABVFPg9sxvnRNGxXVdAvZiX16JDRpi5alXKEIaKDLCFjDvX45XyiRmTlHJzXNOjM6BdjEJArCOryPh5IfKlBQQP0jpDzkfaCld66dwom9H1JfukEtktyqcXN9JgqtzWrnhEyYiyUBMApPocB979SZ6jjFNEhXM39FF0BPbqOS3d4hNqpuxG3ztlbNPCaQKm9n8uokEVDYYXsjAes1lyo7YyD6Mh6wZdH0xDgUAfDAMx,3dIfH0Bx7uB0Gx2ElpBDPO3k3ZSTx5dPqesjpndaSMnvss2RmrhepZQE69KsmwdJhfKVIy0YM2PxzQLg4tT2TqfD2v5tpkx10oTnPNarLlfgzyG0tVlvubviquHmGvmmibPTl170WsoFfyfBvFiQqEMsoaEoR82k83DuekB8dyFDsSvh4hgABEwmS1XyPjueedtbOp7sgfaDT4H00V1cWSVH5XFvgtRsQqloVI1NgAxNgs8xRM872uSpZNqTzgNc,76QOmG7ohkZs973ex6mUXcy1Is1OfSFAg03rSbTPpFc4Htw42WirPLlPWXeGY7NnHJQlMspMeFcJdACTQWAiXwGC8lJTDDWDnKt4Wp0Pt5FNcVl88ACTlKBcCl8kL7sbobv1lHEgTXZH5VMx2ZMYjMO6oLm17UsP9mcEHty4g1TmjEsSfd0spbH4UoRf3TF4Gn5BGpqgKmAvZHRMdkzCKOCf5h1cQbFuWMQY86rkBM9Q122uAi2SRbpJ5ij5JlMj,01ZKVqvoHtKILP3Ixzn9jL5tYBC6WbpZmu1EgErrCqAmctRQzY1aAzSjwenF43Pk2RvumVTSSJAjhacXq8IPrfr71ze0yREqFIH2t9Ury3lmTjgo0HWrayR6w6Qsvtuc7TBvtgvbnQqh42TvKUfmur6x709r4X3y9s3eLnc3S5ZvNYeajvSQ50Q9UMkKp37orxzhJfb7iW27dHTkXdxf7nWtw4XUL8J6FdpnzIpuWEzwN01ej3JkpmB1SYrs8Amu,tx6wLH7DKbZCXbkS43KhkErnLGcCU0B2gCwHI9rpgTGYgkSOQXMut60dHzHe7Avt0USJhhsq58FYjomgNZ2hYTUdIXpI9g1U2pWOkUEQZXhQmKPSUwbDNN6vM9VLJIGEbJxdFow8Z3Z5KGlyR7yHOQopZYT65HE8i1qnveiwVpSDMCVWnZWtumabsV68sv7ziLQpY36kXDAmg30q4YNv0GB6SFk47ip8QziIwSDLZxrPjJq6AdosdwpUnMnWnP7O,vMuiMgpS5x6yFB28UN8OUnZlfxhbGiyuG5EcVYxLPXVC0xtSjK2uM3QMF1j0Gq07XkdP7BKuW9WBCsUf7h2oB7gFVQZJJCA5IiX5zwgvy94qyeb4YtFFG47BiJqzY0uBz6vWXv1FRVm6MUL66lnI5UWSIzFhM4QLukFHWXWJCBUG2wTZNWL4jq8bvgOu3wDVjiGvjjXLwQdvBHG7ytuWuBjXEqqotBWDHJnRp9DvaNt6qo910ghcVi9zmamfx4xv,Ku1fnATRWitG1RPS4E2Gapu5USv7t6ZQqUF0GHxcaB0WBYyjavYVL6jgczNbEZ5IjMpE1XolYZTwUEa9hZz1nUJx3WXaOOiXuNw9CNq4cXPuwUe17GW68jo2s7bTjxMGjVuwq6NFB0L6UsNRbTekliMnIfzu6XM1vtLlwrrq6uypj4vkWMcy9AQrhlOTBGXTDUeZZYSqzgUPo00a45Z0LmNQIGQlHdy4AxUInrcFwS3pkBBm4dh3wj733akD5m93,dHTtCzLjfKw9F5MNq7XB4xRTzEieqrceQ1qBcIHr36LLb5tQ1J31ePtAfSX7vulHOo4AldcxXXq6lwd2wNaRjzxCkgfdRwKPoNgtF9XinEdDnx0tjhWMGoSthZUkygg84K4dYX913h67SMtEFv1bXF2TrN2esWC7OX25vGNlUC5hRfLCBAP42TYwhnnofPi0UrTSK0Irx6GwwulD4ccZYB4guM1oAuc8Y0KAnL7lIIlvAzzn5lME6C5sgzuSpH6R,tnZa5L7eJLeVXnM9uJzvo5VshQ47BV0u5SzYhH2PEAXpybtL6DTTGkPUdkL13LoJpIZcxxpFJy3QorfF5kwIn0HBO4aLEgncD1MfSCJvTZq4cyhATzyLHmiCkz5bPXjLkIvpYXtIy73T2yMMv0qJ6F7f1N6XhG8qKYmkTyW2FDhQ9sQ3pfKt7EedyLjR59ypxCAegwicOM80NZb8K0MwWrYZjWckFTyp5pXwt64SufLI44FMpo57lpMoUnwgZ2s1,bykfq6d8Vrnzvabr2X8wwJf1yu0I6bNykIHG5vyCpwtzZhoew0DFH9IhTXD9q89Vx9vOj6Ce2dRWTR3gOOQ88v8IZi6oi6fpuioIBSSl7TggSTVFRfRJR9JOniz8vCrwgbpvM2DH5UxAfvYX09uYPLEBsUKvYkgrAdDDrSnPMRKN4tytaAzkclc4NazJnOHPTvGeDy8JdZVervUu0fzSullKpRsr07Ez5fzhbRxx1zjXuJfHhEm1DbVDkntHdCg2,zQm8Aaatjzei83QNNGjd7P77JoYOEa5ob54OAO72m4ZgBONhEWT0zTfR3u5JbCSGVR2BFNYnmSdBlnAG9MzqXOHoevefVKh1OzbsNCPHaVMrc51w6dydcluOiOr0xsA3Nq2wzIdSPozDdeXEEBALDlEQSQxJ45l9hOxxlslMJvldwqVMuL4zU7DEXctSB4AQLcTALXTEPekiXBB0tP8pdbd2nTH2A9RdJjBhPEJNmGQyrM9JqOp9zxjp5lHfl5SM,9oZjdYxBZcQ7ViiRlIup6XunH2WExmPzwGZjx5EQ6vJ6MxGd9zeZWoJoekc6qFD4sUFwdX3XQAZPy1Yp7t7zRRjMNeqPxdCNfpcHFfDAv0IsK7Zbjon9mqpaxFtuJXIyTRCJOIU3x22OxrrhQHDzip12xwiYFQbsYm35BWfTimIp5YrB2x33uzKmMQZnNSSayUJGvJa4Pj9ngQ8UIeYUi1XkVT5SIlfPiOVx7OtCtoBz90MMr0mYe5NQ7xWdZJc7,EikxbRhdGXkq81Gdnlo0YPIouCHxSQxbK2D2ayGk39W7LwoxniRSMMMqF9k6cX9X3DCRRygcmAgrKJEY166BH0mGIZWwYghO7QglpZzgxBCZYTtEY68oH4aAD7iexcD9MnKpnsxf8j3QMZdCDrrradcUVr5NHs9f96Tsij7gZSLh11skBYqoYbSszB9zLYzKcEMbK6PXwSAORM55ynEs86DcvYjOu9gkUfbGidFWeq82g9V8XMspNBDCw1W67Qma,v9IcgGCSq7VzRFLoola3vmIteQD9F4IIFcO1e5XiLCAekgNYyRUgiFoaQBGrOJUqeocWOAEJx93ABTLj856lx4zLSfVIy0r7dG8WsnpqLuQBAXrFfP94FQvtN0dwjfk9UF3yFHpHytAbuz07lWaj4U7vD2RpHHIik1K4q0MHjfegNXRP7GCAl3wdeP3h40SbeSnveP99fQnJBVzcHWUHdNiNWyyhuRQGX4rtqswIYAAKFAg5eFvQuWT2OJ1tcPYH,TJEcS3aLyqtByb3zbT6Z9kIzZ7sQ9cOtdT8jmR2KlblISaQfDwT5X1sH8fe1L0XstXYXRTwfdAhovQqexeVrhbuJMyvw8bd5cnKeI3GHaqF8rbapGRWxnacrFV2UlcKW5TdKq5YEWLIklAoVCY7EM1CHAhxX4dDC65nziFtojk936KRVkUBgffxSusM1ek3ADnblccH3tNy6jTICTvURZd8BRmDSxZ8mpuvPXen6sqHyHbhO62F28MH3YF3cRFj2,D6rXlGluJAcAqPP8UiQ9APJUWVOUnIZHq3zKYfpAQVJ2zU1L9n6ee1XmSTvRmKjaZQuxNfFwu1IsGkglTe41Yq8mRfWKvTPv3nHFnostRbvDw36U2f7ryXfJzfukB6gPexwxRrkyIl4w22WtNgxmCzVThcOqUkjrqhVwKh8rEqYpmAOLEhyvw4uOiPQiTfgkZuOnwlE8BveeMPSrAel4u1WvJcC6g0uVqqpYu43QT8czIA3fls3pksUASwC9gMLW,hAmaJw9lk39E0d3OLxKsX1st4lyhUXrkLitiplHl0ct838lVV0mtsCQSfCRxH79bmoGRroqFM5b8HNtr0OvnnXtsBdZdAHGujgoIDHFBeLezqJRApydYTP8fKV8QO0On0ZwHeCi8TMrg6dHUPI206RyAu1b49RFqcWpwsNEnHFqHd4gMcC0RfcjKEQn8OForKalWJjRiJdZLRfo9H2UFhHhdjtb3C18kI6KlyqSdEKruDX9Zu7NHrO8oXjtpLp8L,BQv1EIE9JC60fyMs7DFzGRLm5NJXqfhZxJg2DcTusabYvBE3RsGoHjvPk8mVnbiZeUK4SOs1imBwINU60lCdsosz0cVfutgOK7uRUpVuqwIp4t9eYIdExD6uNzVcLFFwBFaieBgAMQyJVTisCgpMRtpOdYkywVExJVVrAjb84EmcjkjMfsPAmiEYQW05PjtOKca65f9t6yXWMe7hH5oXqXjSUGJpKxjjRCIPtRLFPCwEy1bKhLFBKPjrroLq0Xu0,rSP3L318VG6KCKyXTgmtiM9bx2TyMbvTPOTopPTsOPsCuDcAjZRfWVJRUfRhRATH0j0gTll7ObUVsgY7WuOxVql21NkdEabl4iGR1TQ28Hb89qxcIVErmZT9t9i0cN3kHtY2AIGUJGppDvXLiK2TI33bP0HIXCDklNceUFyGmpcgJlUGEC8twK0Auf1tDK89tulrW2fG45fRTZrh2AQWhyornKGfPYC3soYgbnCI5tActQb8B5bNPRpubgNcmW9Z,NGZQH7CUYIPJbZ9VvFHShlsT8xZ3He2rIJPiBlJrwRntyWhKIL6vWergq6oHN7H9UjyxOOlrhJn919Qm1ZiNiDO4AyIemwJdcTaRVFCTRJdGrQmDNZ9mtjjbdRPKnXXrI1dEyvf1p1k9cviKsHLHTEeZR38B8wfbA2dRheO0lqzgkQCYEwWq0QJ8KhHUF3xjAeVQVBUbC4Qkiu09cvEFswK0lCoPvFdYLCjHUshoW4g2pMrL6TrPISJXKKxoQ2dw,p31G3aG5yPHjFPsEVfMAL41n8MZpMCJyYFYZsmQxTyjMKfhmYi96s6s33gcrGqLAK5tXI8Z7qPmIpupCwod6qhzbgzMYiIzbhqhNW4KWmYsG0RH7jDWwkmgVwznaLmReUNvlDvhTJFCemDX8qA7DcyxQQX1bxWxHro1at6Jf9K8JFIfUQ1S0oukzTpJsgXW9UG43YKc6xktfae9Nu1leXFTBUX9T2ZjGNULgTzdqyzBEMkY3tGLr5mTOuY2NYwwC,oRAe5KiPAWxvMmRN6ZPZ7vtfza5ThMHEw2AYikXDcwueprJWtfsxU7MrO1sPhCQ84Ubfln8ebIycvRB3Tio0uovBUGXsOgk7dwEJwIHjRpnbzTOImQpFiMfbIKRozS46qNyn4Pp8MMMEWllJVybnmxUgtJigv2JPFoW3GJ8rH4TmiFyCbKR1srGnwX19jxOUNs7YucEUVbHzcfvURlChaU1IzL3b2PjfrLEZUs7e2Az4hF9sNAxmMUBpvyHo75ES,QUuViRl1yCLshsipV15egdSk7mkYZZh4bbcyeXXQ33A1MNj9BCciN6RYa1oo5XtlnZseJu0745eFdVlSKHwTLkB4baOIJAKlv5zQkbvZBJ1DleTmZEWn4nkPJ4136Zu939cKv9WNC33aW5YdzciVa1o7pNkECBvy2Y06Op8jS1coVL4Znknm86GnbV5wNFYLuYLFllJxpLWWj5BTEKV4GfJOqB4lBEKBrucW8dYuMMjWwKiAE9Y0MSvmTIlNWkdD,bUXSN8dfw0cgk4H2YtutaRJGuvlA9UvUF8GHTFMZ8pAGTsqHmGCMnAP0qt6oxfuHctF28TcgBHmHGUXvJSkItuIcOpqimKbDQ1MMx8pGOtbJbFBSMRrEfPDuLwZeTwumIQTaH2XuLXGAbTGucvpeJlJlIJStN4yGibZdPtvlyV8Ha1VQRxX6brVtcPTcZ6uWDgYbuWu9xxvmuTB1eQDHMt6OzE2AvbJKnz4vfnZUnDO3OrHIW6NnTk2lbzhNCqwg,SYx98c7RDL2PfFKknBaccVDuMOfTkWDk13PWqglGYXTOBtgBAJm1XZAyIpqYcts4OH1sM12KdYVm2gWyEAgkVUjfa5OoC4YEGPDLTx9U7HDoYM3uWFOFCAUvJEvR7vwfO8ahYbRtTgPcQlm2b7FnVyt4lA2pMMhFz3vT5zwhT6yIzg8AZ2YKiY8DHIPKrqbaMuSpbwuighbG5rfuMxjamdr3ls3M3Vot4jygyTVoCIFZcptv2w1fuTYNI27lgXTM,agN4eglP5TbN3L4FPPNGQThA9qmFBwFBqTuCXia0OcqppUPfNDnPLucPNLhYI8Yp0QBNe5YAyGMjEn9Hou0zZPORXVeUN29vIm5g0136P7fhFpjNM4BOZH6ygmNdSgpFCKAGx7EUzMkTyHtVuhNW64gvrDneo6k4nJ98QEM7WxNaf3yVNCZuekEYTBo7WLnVjW6Ybs1AqUQsymti3tzZlqMxTsNfaLk2qHWoPaVmDKaLVwoZaeqseDQ2VAS9rMtO,Lq2ChmvcRJY1RTdFezpaNT0PWW4jYqUH05dKJYDpkSsP9TQ0OKut1t3mQiovUuJL8IivdMMX51uHvwstHhvSUScoTAWPQScuMKrszbFMIsIMBnbKpbvcgb91TFW8XJRhbrsL5J028MFvGNFzPWk9Dy5T9353degcl0Sz4KTXOWC5kFqtcMDtUhUvD2fb6yz74RR4s8TMJJaoOZjEwcnsWPi8i6Y7nn6Vdt7NPrfPAbKXhCssUdp4YxiGQ4SibrR9,4EU2ZpvIz5nCvWvqd92juAaN1nVVHekyvrqLJB9P0y8oxr28cWfSlKQmUVuxO1vTD7HObRgUAMdG9AVkcVfYQapVKEHJhlyREn80mRb3tgEXXW3SLjgBA69IrKKkjW3qBR9n5WXSfY5O3VUZtwSTDzO9QGAoBYzEFFZVSdvdNhPcUVYaZkGntPjVON09LiqO8qzwX0mKOc8zZpNQvxUqNMprVLCSigWVaEIStoAC2zQlaDwIEENkRQJ81z0u5YwX,jbtXSqxtxomSuSDlP9NOoGctgivaldaUsq31Sk5bu2C36YtduV4SPvFV5FcA5X7zzRnYC3CwFhQPoktL8hNc0QosOthJWpsJC08EVCdfeocGrOMns4aRg9JzVcdMPukGk1qR9Xu1lkFKUSVHsE4nRI3DlW7k8e2B7AMwoAySRtZ7jk8mz178TriVCzPMbrEu0yOgc7Xr1x31AQ8XzBfIvhDwCUpKPONmywo1ZM2ju4OResKfu4llcT0D6yP7ctrR,xM0c6Evo3FB4uapgfVR06CUM5Rz399wH1aEh84xvxAUwsGeJJCkNyRZk4jIDCWGiu7x2MiuJiGDiA9SRDky4eywy8HQXjimHuNQEnM8QykXwBTlxObiqyf88XYrxAfb3m7fA48Yg4Sfy1Vo06111BIQ2zDMDkPxrnLODjWvvqSqtfStzgCsDa6O4t1fVt1NLAt47XH9t3sEMggbkmYdmPuR6yiT3HP5MrhiHxs6wcWmAfg03b9IeKAxTkEYp5ORP,8dNWnVbj1Ok8pjSsFNmA4ids7c8iwcHFPoTyopsSUa2qF26Ufrw89rW2pFriENlEhtKUixfoUHj7vIOSyHG224cz56TO8zXJ0uHgG7xfGHR0Y9hwcqWH2BF3qD3PU6HoptHhLg8QLmoSFt15SMDpaPaT6YfiBULjNMrRyYJsbnS9wdTKakUxKLxxJzEbhjDrMQvTVa9YMhy7Zl57Kc5q6aQKblsEfXkg8taDs7ldEIYYfWtCXCQOewJpuvWvK1Qw,ViILaxyqGZdM1WiIq4EjTkypRzgXJL80p6tiRPfTqwox6WE7y0IoqLff6Z7qoGokaJUdEHjCj0zK2r4v2B9ivctvZu9rcCo2X1hm3eX8J1wyHYvKUOTsE4XFuFUoxEmqxPs7WvdgI1dwaQVd8ZooLrRQMAMivutdbc7CpO4CC8v1ySzHiJlwv2FNlCNnT8uVU12MXn67iFxeRhk0vcLzlDGnNoqfXsBsneaiyDgBdC3pnfoPyjKmkoVtlIFWDDTO,tsPHQ9jtlAvmsyEh8Jfb478Ss433FKx2TgcfdhBubdjr4Rzrjka0zxiKleUWEXlzJf4ED90pZKkwx0SuRqa6k7Ul74krU7UzLjZ50IWG6jogFCBwC8DPOyysz8nLbrmtcY51uS4gsR9v1WWzyFiTM6RWwlPvu8uCd1KcMrUJb3IXmvKe5rwOuDTBX1FvWrE6IYdpJb9ralRhC7YYeQenvpmz84yvvsgKc5trEC8PwYnp20pRnPOLGV38fNUFmVtH,cu8n8wjNOB6wrJcLJ73vkVmqxeMMmP8YQWND5GbaFqWKiKtIRXeXSRZvcCJaRWEg52yTXy6raAGaLoKoj0ANMlOr7lTdvndJErNXdoNvbIYn4aKcaOmeO1EozzDBQfFf3pl1JCbejcWBQCvG6XKOMLSke988tSXEBjJtmnW10HnQhBgHEgH3hdsMvj55YESHOm2JoWGT6dsAUXnTOp8C5fkwDV3En5i00k7B9FRTIf2JtpyCYSqtsFGoRrSswFyx,sz19a1pqmHlw6IYtHHumNvqtDZ8OHTJkiWHH6Df7mzwxOfcX1hOoNJsE9B9dC3HtJR3mLoBWG3JHSNF9jiPJfVdlxgC1mRZkgDjQuLEDRs53IAm9PdQuG4s8kVgHMZHlH8RbvLD7J6LZ7aynM77Z3ADBnBJqsSWR4LvHSfSjhC7qHp4JmInMXmGQcUD5pjg1i1VBTLehfd958eVQpFHFCybV2qkqU3n6TuvILbH7Sjbni8gmgX8c9SGk2QYBUWHq,aKy3QT7rlm7tjxg9KgeBRiNdZhShBJvmS5zpM5VvBTMHrcGjjYSkt4qT3SshMQtpbO9ZlnvuQdXVwgwGLdRUqVJ1XVxiesILWmRA0QsObe46QNZThhWrDkVxaH9kQxrAmZXCco0ykJ9dJXWWTmMoKd2wUZPAYI7M7kHdtQIwtHCCHI0gWvCscZN4h9CQfrVohFxvAWWVK8rp1xTlj4L09koZ0CDFX8LG1dqWGQ6bamBXEH6GKaLHMfaR06ACcSV1,jlRZkM0RP8cB514pw3EmOOSsWzP5hrVPYFKh41f3I9jPWro58kl9pyxay8kamCMTGeBHoPffonpktSgp8dCRXTP9Pc9SlP9GjBcPpLhMedXaPrlez27ArwUVCbdqSPKbKE0Drw9LRWzzZIvP9UUqxV5RSc2gr82jFNODIGchcxwwOP6aXRO0yaYH1D9wfJRL7u9UEi906IS6R9kymUSoCw1ajR9iYsC9bAeuDLMOOdvYIk1MkYiupglwkjVdZHUb,dBi21MeOFqzMYBYsxdGjgNi2Rp3HoKTTOlJfPTVha7AaqMfkU8ympVsphLK09nIFR69YlyvxSqiZMZH5EYToc2OnejkhOLu3XIByPzY3gc7ZMk0xESxEj5qHAEjZMewf98uS2wMgayo9vQuSGIEklxWH0gKM3S2Q9MYWx9RqtY8LnSa7MIQ2NN3O4rVwCCeIh1LLxHuTFaAcbRMPX5GMaAL2YP7SfcTAznWPec2ILnpAUMAhuUAa8HP2r5Zufvw0QMZ7KVOvKDwY4q8c5RGMFVHmgGnCYLORkmOEo19oKkbVExTyM8Q5wdgJSC8wSyvkFArA8O9Q3VIbU7ksI3lvSwjKzTmMLQ12FwibUiMkr5cczuV4qubnad5eQvGLZYEYV6MchvLDR9m2oRDqmjEszeq3jaS4BWOFb9qAx2h5ilrJmTvlCU43nQHkMHxO9UVrR9IwGKPocXkj7zvRHhDARIBIZrYMBRjsWlIn6AiP9dTs7xJMvQ3vTLuB5Jh4OgaK,ZT2FbKRsnoVNug1H8jqPfbcPadLOSsd6O3CkNsawkz1pMJOxi5mcFTmPjspBRpwglkvy5DkPU2AiHsxFVA9K3XiAPymnIW8pzpLHlgFwl6FotGL1EG8LchacJWd5IinukDvOCZrtJhzF3L1ZaSyhUr9G2X32D8NXmzHU42lDETZp0BurVseCOj3xTxJZcKhQh6yChkmZXik9ULQtg1n9IJCncxW9dx5RapBNLpfgHTsBMlJtpZuQwyw03gCw5rKR,dlRDd1JK756B3BSs4zx6eH3BPIz0RmoqIvFWfiM9glIUHFmrApc2KRJn8IXzvhg3i9FvJZUSGZhyenQxpuEaQCgiLIHCC4hmhB9x5KBFasPm8JMWhf8jhS7nTK0ueiw3p1EkEq1jbiqEp4Lsru9JBhmHvtnhvsLQ9luWPbCVCDe5UtKYitpiFaEdAsA0NuROTcAAR3el8YHftPzjRKWHgeUfF1Ur41JLjQwNzS3znM38KGCvScRceC1WxM8ApFwk,rlxNLWIY3gN6G9xVvn3dIyajSIjhxnU0xdra1FF2FEPJkR7ZN3cnIuslvLOABCuUdeGlVAw94Q0cI9L8b0QnX7Mcemrj9ZaBFLa0M9vEG50gyesaWBypntHEt5neWBHCcxrpean57bsSR1CgeJCpWpqpovvKWimo1wmJVF9GoxbrRlxKWJ3Tts7tFliFeNKNZUQw2eNNk23M9OokkdIIsq4KGFiIvCP9YV9MNimvTQDX02NKbaSRPCLhKBTGNp9q,ttlJt3H18naIWmiececPEkeQhOUGXOxTkunmURiuDaPCB3dn9ttXFxWMZTB09m146fDlvZgHUqLuQf6PUSnxFklL1w84d5xhP8qhc7EgNXlOP7nFYoeIX6fzOeUdOROaM1bHmnw8qqDlJxzdHvIin0vB4yyD6rRjfidnRPiNahAI2qUKgDmZcs4U4ALg9dVpOQKSzyIftvJXmFJpih7pB5r73dl9tIMKU9wbm7Q9tjXbOf3PUqEWHmsDIUSxRuBL,WtpcGmbGdXy91A9sEQyjNeInpQEsP0jIIqXTD09vfYOi7E0xC4jphV6ID6JEUjuEr1b9AYm6DwYJ278DHCOBrkUv3k9LYJ8ufwV5wOkmLJEKTz2AqXIYMYbp6yropOQrnvc0ljeUC4S9rNL2NZ57pgye2y1TMQq7XixtG4LyzMsr1O4nPaf42nRobQ4cbybEi43a88v3F28nTkzFKiH8zxigxPUF9QL18WvRMoPxDgOhXiIq58u6914c7hdtN16h,Hx1ChKpEbTX21fmsEL38MnY0HSTYpz4s7pKtNMIkyTcsvtWpOcejEETE7ONIfMjmBZzI7v0tq8ibyRqdwIQXIHLpICdZswbvrGgfS5CjjmQzIcfogaz7r60XPYSdjXlR374PPGplyO4P1z0Y2EEk9LAwzYDJ8qCeL72J1RH8Pd5uax45LRayo4x4c04niuu0OQWAg3KC5uSuMb2qJEByI9sbsj6KA1epPS3zdbn36NsxsjPcii1UcvCdyQBfUlsy,RYV7mVK6yUHzLXyvKcrOL2RIXwMHjyOw9IvSCZY9FHYFFHTlrrPX0GV2s0mSOHCJqlml6MIAWTxgWpad6sDKiHhoYCXEbuplnbiWChsuuT5fsdjjxXLRIrJ4rfvDQx1Jynb7EkzLxh9sUTNy0ZOdYjezIfmHBKfuLFY7USEE81pTQiW08hU0TpzY3MSGbEasDgdxJiqxjnhoU7ErNkCvtB0wYfSkh3Rgn5JliI2msBafFoTDdhgbxjWxYdC5OPNx,P7KwH00maKNU9HTQIvPF7tAg4DozM04xiIK0oPBRvJyKF9rwcL6FHJz8EAjbZ4eVmq4vyD4tUfzlDZj3POhqHclr8j84ZsB0dFrAn37NMjzOuAg18Fw0FyaXbgNVbmfIJD8iqfvr5LMjZDBFvCHAYFVXR0Hjose2BIpjqXy5u8ZWOlEodrZjifoEKcWNnyzKqjyHaqncTRTwRlEjZYg1pBGq9hP8FXrTIUQmQX4ZJX0WAnI95IZeJB9Kjxkscnzo,8GaU4Xn2tmC1md16lG6c7U3a0bYKe8tz64e6H6uqyZrw02f849AK3xZYFmkMyqODEbYPiUmA5gfwQeucRYO7FtMYMVdTIO1UbK97fXOkSrzZNKUQu9ZrlK9BeKvm2v8CWTaDRKEW9EFaVcE76ha9e9GhAb1BMimGdcjbmo6Ymhr1GGpPmgSyF96uqHcCYeTWYLoRjmZ15WIN1XBcmCnrQUshbbbzqPYFRiul10eJqNtnL7neUKcSCZMrkRE0iE6t,UP06AhvzRPAutI61i1dyYDDW7tJLK0tZePtzsyshIsjUdpurzVUoIHTtIxhWYCPUo91rVGFTCC2rkpU8N3ClNX21xVeaOp5X1KmRETqHAaz23ZX25XsIHKe3O3cIu7TjCPodQWV5kWnKHzgbWuSyWqd3HliJ9mCw80A42uHqMiL2327Y8UqFlobYFo4sdt21ury4TCV3OfDz5VdLukUpggMGnh1FDPSHBmRaoqUExB9Lo8le6ehmPZa64JPNB8Mn,cKht9rNyteCF3fyuiSSV5ws38ryNm8DuAyTBArkempZfTxkbV2iRqW8YxySD6qvyeD4vC9vawCJzt8tF7T4hjaSGoYuexQaqwwp7wAYkKNRYZms2XVEOvvsQrajJpSjntQvZHDhHtN6sIjVCOhNZjF9RTmhkHO3S3ehTZBxLH7juoDneCH8tW48QdAdJwWxH4Lev6fQN7OdXg9cSudno4rPiUTK4M0nzd7RGhnEnMZ0pKj4VHp0eDv0TWAKTO8v5,hSFfDM8WgiqYA8c5Qzc8Yczfr88BL5BPSLrPTuyhicNfvCNemxI8u1IKZbE40pvvOfs3en2ot01qW1zLoPcgzIjWn6xIy8MC33FfosCeZA45QMTCibzW9hIVNjdC5H4QycBVQs8yCHmtwEbw02vaNVeDw0qeThfmkDf0aO0ADAXRJtHBRihJV1bkZI8xIifbxdsGjLE78y99sfDUsR8OruQTiTyM2wafSas2iOsbbjOW5wBLZQeWW7dfRMTcyzl5,0TxisCs5jNcH2sLnirb5dbeafw3vJlunwnuHAkzcq4kfkv0hO15KCs75rgiUGXnFfinxBrkqB7Xjr8vHMdcCORkEzjbMDF39DROul5CUiUpCEH1EiLxPEvNPtkBJnX96xdjiUI73ywecRkjmKb1CS6WKdCCLYIsgfze0THTfAl840j6B5TsGb0Z4H8FnRRv0AKjoQEIHFOdikMNV5kahLNT8MdyRoaTdhR8d5J7jx93MR7sfk0rF5uXGqsH6UFAr,umvoHt33wUOaXVEJJQrkllikgFRy9hHtBNj2Ob7MN3GAmAH3Ktl8XivVpVpImMYLUGO3HyMa6TwM68NQMsuRKpKAspD1qrwjeggpRFEvhlkpaLPUGKnRllggO1HZV0DRgxCmJ8XfhboxJOEJ8rMP59c6HuN4xvgKXB61Im7VPB439x9eedWzHF8MwPShZ6uBBaTUiKIUMUZqyf1jQcdj2bJD5Ozgeuu58VvcJipXzyjUWuh7FGy4GUJDTfi0kibu,wFet9ntaB7Yp9nUFAF0xll5AwlIb0YFiKKzZbj0iERlbx5hyRNgJ9hlVsKVcVZsgCYmXzX7LC5IBX0TrkyhrUoNYwIY9dyGmDEJFr6DIPCyQXIkvBjfptvSLSexXSbyARgH4paGgpGIDtczGw9yGCMfoUO8BOoy2Axd48U7lhSgX7uigXgo7OBmCYKhQQje84rbecYCEKamIVpXetWD0nDJw2aBFLj1nfohOWMVnJjUeg3Y19VQKAfcbzM22Mug6,kbgIRyQWP6kspm9N4UPC08KHI6PfDwZtGzh6TUATs12O5RVd4Re8NZuvcTOuztwZUkEdwhMs8UWEQLgwMrp4hhGvwzTrEqBuEUzN5QxWWD78hm52LLVz53u0B9VzCFh9oeyge0LalyArErYZFk6c3KFpi9mVvtkMRBY8g4upXmsGbQQYt0OsPMVQ6FLz2Csf6Rs29FTyWWle2sxkfCsCLOZPSRiSJLPBreniEzC6fxPejHUk8VTKNaTkU4dvGOOa,7CqbDNxNz0q6TJKZ0WziPoQzaB1OUumx9Ls3OylVqaMAuyvm3OIxcVErLye50wpJpLrN8QozohocRzLM9pj7MtQ5MSPSu9Wtn4zSSvcDsbfqjec3kIGoFYfjbTZS00XwjzWQz2arX9lUAHcDHL7gto8rwyzZER6vWk5CQY1NC4ifUI71c6PyNmZBj8Nyy0w8gJIzeWfIHYmpjpInTFys8pi4mErBo5vQDzNzKrzxAikAuz5Vvh6GctWI2GpIgTjD,XbmnDWcoT4mtLxcUyYCARSLxv7VZI6WOceI4gm0JSRSG6yZOiDPV8hHtt8Ob5BdinfXj30W0WxcG5S7lfWb95aGt2o1xdZkJFLuBapQ01m0y5usg6G6dWo8379SKEbDUbix26LQbn3LqFQtKOJCllXecfVKQPEZoPN7m0K1Inustnt1idMeXkN3GtOBiq4oT7MYqmhTi720OxSkjHnStpJwzDSPLBA55Cz940W2upY5nVKdZyubTH9LhKs0kzmWS,23ahEndGwMjJ4eYShqJ6ONV5nkJMsapjBpfEGcMgCGNboUCMrcHKL8ekX59OOrYvxpTbISTV4XWb05DFnF70Jwaj6aS5OTWtABljjjbKSEAkfF4yL8dEMtyhR0c8V6BThRcpmuln6aiYFfnwLe9UqPOh2fTgddPv9TZbsQTY5UJZYOdx13NlLGAyNJfYagGPJWQotv4gYGNMVxQFBlYL0YBpNOZAKWrREL58HLznISLPuAGiCOkVn0xVH8LtFgKGL4IeMYUushH4AYwQ0XxJaUA72En0CYFnFQ2b5P48BqXwerejUtqj5jOgM8NVLpEKCe5OY852aHScbnxLfoGGnoJkzKYetx5DMQJQL1aKPamM1WXyFdD58fv0AFedbD1RIlm7tADNJx8GYHe2BOEd9O1RL0mUCquEgFANTCT2cHmWtZ8mTFiGy4QIIXo3JHbT6Ozz1yODaYO6s9Qyeq0McIBpHf4C3PrsY7lGFufVTQDYOudMJh2yVBfHEUTj801p,zTMzYAo68zRGI5z6bKXZsc23Z568ISj6erGJK6fnCZFms1WaNcxp2Qe1Ixen0RlfuDDbYCHnyeTca5wk37X8EqdOGmbEhXZT5LS8eHiUv35gCV0LOBuyYJJtxYuLmlxaaYNwKEG1w54wgi8TtgDrPGoTKUl2e0l3YoDox19Mn92KYVgkpCTAjnMbOyKrWPcNCw5W1eIzqWEDtaT9RE8fPsgswCQFShFfvhSMLPa3CyAgDN79g1Mfl5r1yUsEKNyf,WvOHT9itROaYvi5UsYZbRcuGsVxcKVjlzkynYbxZKAFas1m45RnDWBqNgcPfGC3Bdks78lBMEFf4woiafP6rPcd3pnNJbjgsDNAp9ds6qoWJ9mZ41dkUzTHC0uaD0hTHZUh9qZ2GgdhpvcyrFi1NI3VAYp1GKyMNNZ19XQ8M5zDF8u9pHeuwODPnZDfWfmVIMiImKvogZWYdc7oukgKzQjN4eciBlrkYNVtSuMXxkAVPw1WxRn7aFyT730sSdrd3,Am4UWeTaJgWel4BVHbS2c6KKuLl97pkYaMFo51Q1yBEL2pqCC8egM36Z0CKTGuuUsS8A3S7s9k9TOBgrG3oJOMfrDHKMC79QSLrMx71Ez74w70N4OvRokkWkNatWPYn1qJ6z9z7jzCi8UBKsDAqK48HwOEgmAZ9aeGiK1bJ86mvrPbQkoAqUV6us3CfDvBPb672YkPik09QDxSWNaySUaGk94pHP4u5QlY9HXsmQSXFtVK6L69TBqTsfw2yGIpXe,KZ90RUW8KL5YYlBNWF01c11G9q8pCWk7FPal1g6L62AfrovnggDHlwE1MN7GGtzzp0BvrvMs3MRC3OGftWSSzYH8Hac5iyng6aB5pIbXvFW2V4YGqbLRQrpZPiVHEx8Weti0AoLPsA6DmcMq36uXmNke9l3K7DGPkht7ZywgwChhV1b0wsh3WKUlG9brN8igAFYdMz0Jb8tpHAIVnF7u8R212khtXPbyexffXzdvsORNk49g6ntSSFoUvMNdAVKA,f5ppr2Hm3loZkge6djRqefquxZQxLQwYM8dwGz2Yv7v2fqeSo8LS51j2U0M83mNYLqBUNRp5GspTEhQWb9sr6h8lB094W6giBFpPYkyH5Guelw1Ev5KthM6aq1PVF8zMDkPFhvBzLWAgV1l1svgUta8v2cn2nHa47LM7TJPZyHP0skAPTm2WQfvJw6eEKoFTaVncoFAkFYEnH9XDA2JS2FqxEP1zadnJPyMpZCqEuHs3R7483jvNa0VwMWC8efmZ,eRies8ZswonjKeaGj81RxzISCGDeYNvCMnIOj91cd8q4HQGCwgwk730zaSgKJllnylCGB31k9Yud1g3mm9PSAxQEBiWOIKPFdEUogaHgYeA9FlywxD5iQ1gzeeUsvUcSaS4RIYKcPF22zakRKCjS2R3zfQDD4mlm6MNnVrRLHqbf4qWxCEbzbkpZYzfgFa8yaw4UZgXL0V8dMqjqwN1rTiDZElxowBPywbqrI3znNwhqpM9owLENSBFiWHErXXyU,7Oo4qyXP52zCA383NT1D8LgwgAUbgUKLPDjv0ZCnfoLvlYnoYdSwYs9CB1TUpZDIBDLa4rQizQF563Rq0lDHJsYXIw2I0nu0DZXhCrstKMlg7PZEygYgjH57rT5TBKSKBUuDDfDkxnCzDvvwXrxTc5yma9VvECSXgGJAAmUgyH3zcJIgKXGKwo0TVv25rro3t6FBWVf3gthnrQxpsr3K8eA9N7JQM8aMCzFw6lOJkHfiNUXNnowaPwHucR9Bs1vV,YrXUQWQ4rzhz9vJ0otwnk6q4XmU3RZO6hXgiPW6syr2NoGAaK4CLI1nHAHhdN7SOZfDGSq9r9mNaYyJTYtJcpSpQzfzvuEiwImqj1UN6s5eoQtA6AdjfNApWOUpFDPDN0sQIARGMROx11FJNK6ecoZYQwFhRhtEbkr9yRmux0JUZ2lgMffGNmxMQ4S21csBikdggXQ4qPoiMZjvq05rawDFQ4IIEgJqoohQImjo5IqMNSv2djPlvcVGbP7cXayIc,e1YndteFYaAMFcfu9LRv6UOS6aK0K6URYn0dIYuI5W509YNYJOsSmPxwaMpwu2fXklgirWhVU5egLOzl4D9v7jpK7Gh07ApxJKPWUwoDvfRpIeYBNi7G96Wj1b8E62vkVgwX29bEyLIfIdNqhbYs2CwL61H8ocNhDVqe2fUDLIUJQfYosLbq7y5alZjn7xTrTCOVji7vJNWwe3cbaZzq4Wn33NnA6eQPSgAfoYzkKX9OYjFbmH4U9BmYxJeLpzw9,HYdWZcTyfzJQqd7EejT087bR574jtJGylo2MGUCMdyOmMZobYPAiuMp1AY6SIs5dazCiYy6WHYdnBpp4ghuZmtpnl47zrH9ScG6An7q86aoAgCSTcxFe6PKDMfvUx6aVVHERRgjUb2QI9KR0i4F64S23yGEGH3a0soaoAjTvXzJsauLVGWyJSuGS59VkrldTMye6oI4TrIACwuRJRFTNQAIUwqUi0qtOtZQ91TvxgsZaRJrsjHalI17KYu5UW1An,HehGTSt5odBlQSxpLn9E7wwzsmD5Hgs1eX9Y5EUmZqHhET2oyOKWG2iyG0M7ucqIZqbXtwMTLKChzbOto8irIAu2ExO2EIxydLFnmqZe4c4Bi0u1Fn8y7E2Wzz9MoFBaKmBH0sab5q8DgALetgT2uEacKCHmSCOOM3swD33KNDe7yaemViuNBnsGAsJu3bSbSPaYGwQDjuFNyD1uBROumEARHN5dC4aD4mBhJAqDavEUcz4XcZnakD5jCtrkTNwH,me5cidO7hOAJ40KF6g4czMdRRXqAdRuF9MzhHlNnU8Fz2e4xaWenkrG5grNC05dFyfaAzZpuYkihYAnZ2sPICZDmjLvFr92Cs3LKHb7SZTAdCMS1Tj2TytbT9qjcnjTwkGv8C8TmEpBiCOFy7Y3N4Zcvq2FxxgpXFcqPKarn0ObK0tzOLb0HpToFeIId9KMn9WPmLfiOk11YGPkekhENfwfY6C6v9atD4uvPul9BZ6FBdB47fwxn13UmXYnHy1zd,hgVlgCpX7qv5zMPmQFRZwcvla4Qn2r1mhHJw4peLGbl3vPko1UFi4nCuhtS0YkaBiYb0lBeOaLyp93TNj57YC0Eqf1EpQiqqqcPUiqjLPtIdNOAol17GmgBijPF6xdyWc7TLbK5YH5kk3fMVBgm2uKX1na8aTesP2YzyDG9r4AcnyiAmD6MHInCko7EbZPwPaYNZnSWHjXhO62eLv2gWMpPK9RT25AuGLJT5wmpFzFv2CzjO2Fm78fM9NBi9ZpWJ,uXPheKv9AvPQsrBirRhxcUaFniwfEALPfyEyAVk1oKBiRfqpDAWLX77dkBVQ3tXnX81is8XP1nab1GtpviSho44L24JjVS6EHMBNR1ujkvIai7GR1EnCWrbMMSR6nk7AckNNMixX4LISQ6W636hF7WqxI20DBKfsRI59zk5vEsaK7h6cIVlgQOjmnE1I3gqTLmWkNjZxJkLc8MK9DNpy0qswgengQkh4Yx0B2A6pDBarXoOegVosEtqo8XLmiwBQ,7zMdG2Xp6CTIQeflF7kKSfHAKRbvaPGj7QHF7SSYNyqf9ON9cSHDD8AF3lPA5SfTnE6ZGYZfmsbMFi9ZZTutoabqxW3PngucQTNkfwLyMhjZfCEFxiFD3HKgehkg7sqi8BSFvttDmHVlvD0igYCeYpriv7y7s5kjVs24Iy5RtgLsDBDXkNMYRJpGBepvoeWszenJcj1Uj5JpqWC8yJY2Iy1fMyvfF8h2Gn853HdzxFJC3tl34yv4vYQEJXtw7Xrq,OZJP2BDlUPwOxvXBGfRpoyCDqdlVETLoxTgvnIxGnxyF8Avkd7EWwgYb4D7OuwocavrrM2TQO78aBcNjj3FZnV8bq4HlrOcGLVrqqxn1mFSuoTJE5bEfxqdiUlKjq0obtnPRpQJvwwjJv8xaup5WaE1EGUkzly6kKLI5hyGen94YOlaZ13hQQET0knnDU3cAx854qhdJk8nXfnCbZH8kqMWTpxDl9hVuHhl3xutYqPcugQziDCB7jU4peq4pAvWE,My9zKblkWT4UzKq0nPMKZle3l3sZGZwnW5y0tQFh2Sc0Rp5VYkCBbiMfDLCjMcojmJ4O0KgARK8CgCiAdAgX7RdduHdG5HduRHX1QDIlsYc4oCkdK9Xv3Wwvp3Pw1kwVXQIneJ4XGiDFoEMweo1y9VgtdEVJzAoBf3TTCrWQ1a4Gu17lQBMTuYC5TJsqZJ2Ee6cCY7BmgCVdalfHdMquBTF4Z2IcVIgYvP5MbOO5jj5TumVNYxpGATzUr2w5bY8P,Q1kAHG4J5esOfZqNNERlrb44c8bXNH4UwUl59maOs1MvBLfrnNPN6bTrEE763WEGU5widKVANI8pqFPaMSpoznPhKLtcd28CsF2yZh3nZ9MNPQLahLaj3k4wRvNPV6qpEFtK1Pwelm7HUk4ByWhsRNgSasNgWvx7iZ0xUTerJOvH9XBKmzruFpcAuAhLmUqGY1W986TRAYe44W1YmnQpLmfJmtfuInAM26aM1ieQ4apoyxto0hqzorkWQWJFmNoR,ZmCZFo7y9Ysm7Kl1PEThWl2IMfH4T44BXm1YvEBi4PZR8wlav6eN5ps9ncIwd60K7c8TdkJ8MVE7SU040PKZ7ZM6061arOZr7tbk6JIBzpVsvnK567L6H8QMpZbJ2qqOHGw63jsXw2vu76iAyTHtpBYtgvGBNkHyVat22BgiG7tyEA0wCf5Co1paV7lbBoejBxfIOqiJA6yCk1H8d0q5m7AZRiED45qcchAjcIc8V0jRLE8eF4QqlxumIBkNgcNW,CCfwXihH6cJQyFUoIgDdIjzt7uQFGTl2Blh1vbkC17mmSeJdWTI6GPqSHeDwO0LsKdDQU7B2RI6ezLFaXbWvq4knUPhlu5tCGvYfEqq5SDbq7gM2E8RfLnEfa9V6vetLb9cBy9Ya5MndfGu8vRWmF7uzAcxD4PHubhBNOUT6gBLu9GGWuYVrl4yqGCOpwZ6NMUrpdviUagl0MU6zStVsSMtjf7venDLrnY8sAw77PTCC8nPoxBlEZU4awcx1ua5d,caH4g0AkKXn8UiYWpmwxJ73A3w8fyy1gLAPoLuAGK9Y5Lq1s7O0Qq1OV7e9GoZQ8fwDtEpi5ekDKiNNVBS5V03s5SBzyTemAMoOHADrLnsfoo8a60xyDokJnB2tpiQ8NX8RrT7vpIfovfKXzTBzfFmviXikdsLFcnDXd0Caki9GK8CMXpDz7YkxBKbeQ7kOpZaVVMJAUsnPq6Up2dnJDakwAuY6qty17lrIpJ3fbCrqVfNjcqJXVvlPZ396gr66W,TFdBiWcO2aegta9RP13Q8wOBfdRWktUScSjumDgSeal97YW0n3LgXMxW7zLqlwbtLZBmZTMNGijDVtq4PT3b6cZH3dLs7johTgRLM9bsnSAsJ7kRPJcArEar25j7PQ11R11561aFtsfnSsoz14HXOJuzer7C6CcmMTA0QBknNwKpLduy8mVubRyzUNb0ZEaBNZHuOtSBhHN70LucxIVTcXUM0BANXKY8bhGv6NE83111TZqG21aPw8oFOOq7TQWH,PfHWJIyssCeHs9NXwOTjGgEyz4lEbWu6MjCGQCbP7sWLx9g2anJKjQUkRVqOyt8E9VQvxG2dhZB2au804zZN9GP7jYKkWt3i7MsqtAeFUA0O7WHLbvpfhTZWx4XQMmmO27Z6nSP6Fl63OyrCWYy3ysGQfUARhZGzJs5kdAY3WO8sLRbsnHkyeqA7skbdWQ6ge5VEgP1AQ9RjFxThLzMvsgwBuBSnsaL8fQoXTED3U0e6TxrCgTeRNxI3cch524T4,sKxT94b22egM8dhpsiLhqARlYrYAGfKolNCJPaENS362ici5b435hHKpFFRGYe5y8IecWmZNn3EVBSHgrKxLJENE4PjaCFIQN7TZLQHntSYVksCb97IEOXsMEB3d3RuFEG26XFdc5IJpKnNRdpcZy9lgfwC51Z2qIA4JTFlwrPS2nqE5KvfdbAN14fIpZjbbC5nnzrbBUwnUzLLW5NbAj6efXnWMclEEPnTroA2m25qjv4t20qxmbwLkSlUYvHg0,bko2gYzq3ZG9zbCgsN1dvNg4Mwamq5rNmXiEUwX2mh3JLD6oJ1J2yQnlFxINBMFj5PU4zDsnG7RYNZ9E7rUgo9UfSirvSy4QItxXldHZJH6yv974C0euicON1sue6bBlyl4J0suafmKiWDjfx8RSXMvdq0mGFrt4IHbRmvBp93bJrROa8btIfVQfWfdqtpS3edGfn0IeFcWAgxPH87VjKnHtS7B3dxPcWVzT8GU3Ds8HR4eebLxTuVTxvqOoQosl,rvrf5R6zgLnuI6BUTLPCvI34UTWO2Xi1vwa27wYkD82jzffLwa71Jo8OnoTEcyASakBX1lxNuDDmtyTRG9nQrWEn3ixMTa6iXsUMIQkXRub9MO9nXp2GvhDNYyJElbfQC0PS6nyYnGsyVfRGYYOy102lDI957kLH7uifItoDphRvz1KkTAjNrdRyRUXiK3KiLQOmesXYnI7L7el7utb8iVwGi2FX2CFfAG68MTKeOQeGSb8koS6fHiQfc4SFDf1t,QkEOwtEobjNeRKftx3DtoxQUtzOji6naCtzc299upqDFt9COXvlhSW7AuGaVqGjfPkGoplwVJzQSy6wkiuMerHOg9HQ2hJZfQ7s8HeqwSXyvNE8jxzj0msCSIqIgdWGZew1fwxSP1IAbT2FiytHD4kEIjyfwg46CuvWSVqWtcTyoy7t9cGHBEdeDD8y5CABai9TYKBa2B22L68LLY2ZSdzZ1lWIZ6bmOg5imJoknlfEcrIBZbb7CsqCMk3uGEgxM,NzvcNlD12QIABWzsplJrypuSMrqPPMjxJ3ZNVkPG1dbRD0TZeHSWW8cdKZtP2YIyj2y6c5a90l0uOhu4vsVnJAdNTA56hxAuHaek8hSjo5fxJkBi8aqbhX7SEK9IQwv8QHdQMupDpmttwOUBZGN02lw24L04SQfnCKfCiHCO1edD5Snn0V7sgNJQjNmMpA3VDhT4HSexzjrzEWpucTQO9a42WVejQcGXMIFRXdaLYEfiP8r5fOrQ2uw5Vr0XjSMU,RoKnv3xD904AJlq2y10Q4BSHGLFkuo6TU8roTMJrYpBbEiNgJdqu9titWvJSNChLLDu3efUmxvKGlInN36c48lpfEAf4iaQTictbjA92x0lUgKyLSSy2XEYKXKJKkhdvixaGiApV5CTuj2axV7TNefGeziZzL7CUJATvJzF8PpqACVnp9OqlV5eOEULZFOsa50Dd0usLs2aTJ31AbvYDl1IRqrFt82uHIHanm3mwhUnaSLq1efpLr2enahG0Uuw3,zotzJohVqVruZLVGidsskBvou4gyrJwMsDSpDRsBmze6RYfmpyPJup2cNYLHCLDKWBI8wz7EcqP4Zo5b35QgAaA4L0Schh677mfO2JjCBPEJ8tx6FMczPGmeUW6V07PfuNVVRae7riPWP33zbZRF39tFx6yBxjj3Kirehl2HReDJ2fSJEQ77aJxbHK9pR7zfvzz746XBUx1NfgpozIcclPCHlGBsOl4O0TCmUOm68QUelfo4jSX1Z8SJ7iBnuudQ,bu9U3fxJemz3n5lX70p5Ux0VnrOMSb86WcMIuvy2zuzPrr49B5hxQEQCKaHaAqzb2ztATiO9sRs8G6eYTF5m5P0lLMCLzlRGJ8lNWl1OHueSUZ5kDd23fQT34hLdnbtOWK5AOhbD24CvRD67Mo3l5LHQrPNhyooQ8v57EbAVbv3XaH8wulA7tLPlsktnbSA1IqZzOvooPRsYf2Sdy9qnBHIk5gcOQDzVewzNFQNgaXWufA42VvQaBCPbY9wQ1gdH,xna7nrDK4lWIekTRCwBz6vRRnFBm38h7eO5LVJDh0NvsKUtrr86KPDwsy7oA8vcSum4ZgEMSfXMiqwXMrzePQsZ0BF8Vz0a2RtBJretu9B8jZNP5DqZxRtCZU8Hcop1q7BobRtsmnVPsngzzFeya3rzNUW5VNjM96fUGs9OTG10E4sCARS59oJJo1ypJOAgbJHsYGimPRte1xRkmFaWNXqoSXo9hT7jbjH6Khghi1zG7xkUF33MMXMj6oYzuIOYU,bEeo3ZySwXJHV4MHZlDlTzvK1o1Ybu8HeXh4PtCrIFySQ48DE44Nisg27hW3u8LcCzH8yMXMjIiggH8pXGU0J0eiVlQuVGKIeQkY0BZvMDbLNi8xXhsP6IOgVAy8RjEAHoNoApxRXNiUb1F7FduoeJufQBKNikvahbFyFTeMFn5M2zl5i3E9u62flN0CqYo6wSiZSeLJ9mDlYzE4l84qMurWn0Fc9luS4QunNR0HjmbT2mdNC9vFf1Qv4GFm4yhL,lGwNjHT4P2CmlFTesRy8kE9in2U176RTr4C8xk1muS5ySlIFkbstmlHzyXZHr72NDoN9csuusqFsEeWRDqhxrnSk5PV5Ej6tlx4YnM2AjdWYggHzqyf1nDw9ktrzpMsXKU7HdXRjDCTP9mlH1UcxAf9QmaYOe4qM79riZjMz4tCYSNh6RVS8FwZb1TppRhn6duaJfs5F37khldh5LKxe2FpVAPpyusswG0U6OndgavdOOKyMqbe3e5Vp2foslT07,d4uAi0MLIAoR9CUti6mLPkhbdjsgFceT75riXw4g9iBvx9YcsdD4odbDF4HounYazZYJgDZdybBsA50Enm7es8kioD0xyouBdkU3AAiRjBD2GMrzeVzY3DZ0bQiyaGeeAGT5G1p69uyV14ziBUrCq6q0YeRXN0fgaP9VVO5MiTsDQYqGVEmDCB8eoh9UXEce0kbCXG9hHN7HmpSzKJr0MMQowraRfbKD8hgW8qccoDrz1JVkjm6i5Veei5EexXBN,x5QlLB9nV8wAH544jwbZEm2gHgBZkdYfL4rWNfwuoaWk7EGX9CRgjcZVNh3wkVJc4JN3RfBymzwS6hWadH3XOYnb48KJgxXrO1Z2VPRlzGRyMxJht9a3A7aKseyMumDE3Ju1TRFUDB4Y2yAwymBNaDwdKNMNEmFqbZvavP4FAnZBt5SzcYh89f4tJ0Y3fk4Fvrs8FsGQ3NU3DgAgGCoJkR5r1nyLLVCS76wAAdbCwbJgPnTATRs6vdyKV59brwE8,6viOJp2u22jcGcr5GbyXDpJgVBP5MCsj9XsGk9VdKZpq2iJEkdP60WrSJO8kfnf3GMPJHNqOpolEZY1wcfSydrdD2ZVL7vXaj7gA5GATlfd7pGJBpkyTFxi8XW11wYLfBlFerkQHp0IT5HR7QzkEAbmKXqDjXHbVUd0h3Ttth2Axb96WjmmwHruTbvLWnG38Fif67B9kcQ4WJR0GKvEsdSJ4KCrM49xsWB0M5yy5qiicpcKxKArgyV9egmF2G6N2,zFicwjUdCyqa3MQa5Xnjeag1fdU1ulCvaZX9QkUCdBwmKIQV3IFTKD9EakXinQC5GXmUAiHvmmBDT9'
2017-07-21 06:39:54 - DEBUG testThaliMobileNative: 'Server sends data back to client (65536 bytes):'
2017-07-21 06:39:54 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:11
[ThaliCore] VirtualSocket.closeStreams() vsID:11
,[ThaliCore] Session.session(_:peer:didChange:) peer:8EDCF724-AD07-4005-8DDC-A283D1F0F2FD:0 state: notConnected -> connecting
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:8EDCF724-AD07-4005-8DDC-A283D1F0F2FD:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:8EDCF724-AD07-4005-8DDC-A283D1F0F2FD:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "8EDCF724-AD07-4005-8DDC-A283D1F0F2FD", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:55284
2017-07-21 06:39:56 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Diqy1QudF5zgBNLHeriCnbdKHSgDdP4b",,"error":null,"portNumber":55284}'
2017-07-21 06:39:56 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'Diqy1QudF5zgBNLHeriCnbdKHSgDdP4b', error: 'null', listeningPort: '55284''
,Connecting to the localhost:55284
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:8EDCF724-AD07-4005-8DDC-A283D1F0F2FD:0
Connected to the localh,ost:55284
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:8EDCF724-AD07-4005-8DDC-A283D1F0F2FD:0
,2017-07-21 06:39:56 - DEBUG testThaliMobileNative: 'Client sends data (65536 bytes):'
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:12 [1, 3, 7, 11, 12]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-21 06:39:57 - DEBUG testThaliMobileNative: 'Client data flushed'
,ok 102 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pe,er})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStream,s() vsID:12
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:12
[ThaliCore] VirtualSocket.deinit vsID:12 [1, 3, 7, 11]
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:F090AAFD-5C96-46E7-B54B-705E443D5365
,[ThaliCore] Session.session(_:peer:didChange:) peer:F090AAFD-5C96-46E7-B54B-705E443D5365 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F090AAFD-5C96-46E7-B54B-705E443D5365
[ThaliCore] Session.startOutputStream(with:) peer:F090AAFD-5C96-46E7-B54B-705E443D5365
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,3 [1, 3, 7, 11, 13]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-21 06:39:57 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
2017-07-21 06:39:57 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-21 06:39:57 - DEBUG testThaliMobileNative: 'Server received (21900 bytes):'
,2017-07-21 06:39:57 - DEBUG testThaliMobileNative: 'Server received (32850 bytes):'
,2017-07-21 06:39:57 - DEBUG testThaliMobileNative: 'Server received (5311 bytes):'
,2017-07-21 06:39:57 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-21 06:39:57 - DEBUG testThaliMobileNative: 'Server sends data back to client (65536 bytes):'
2017-07-21 06:39:57 - DEBUG testThaliMobileNative: 'Server data flushed',
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:13
[ThaliCore] VirtualSocket.closeStreams() vsID:13
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:13
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] VirtualSocket.deinit vsID:13 [1, 3, 7, 11]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-21 06:39:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,[ThaliCore] VirtualSocket exited RunLoop vsID:11
[ThaliCore] VirtualSocket.deinit vsID:11 [1, 3, 7]
2017-07-21 06:39:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07,-21 06:39:57 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":nul,l,"networkType":null}})'
2017-07-21 06:39:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:345FB200-0861-4889-93A7-1CE465A33780
,2017-07-21 06:39:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:39:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:8EDCF724-AD07-4005-8DDC-A283D1F0F2FD
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:55284
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:8EDCF724-AD07-4005-8DDC-A283D1F0F2FD:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:8EDCF724-AD07-4005-8DDC-A283D1F0F2FD:0 state: connected -> notConnected
,[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "8EDCF724-AD07-4005-8DDC-A283D1F0F2FD", generation: 0)
,2017-07-21 06:39:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 06:39:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 06:39:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,[ThaliCore] Session.session(_:peer:didChange:) peer:F090AAFD-5C96-46E7-B54B-705E443D5365 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "345FB200-0861-4889-93A7-1CE465A33780", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:F090AAFD-5C96-46E7-B54B-705E443D5365
[ThaliCore] AdvertiserRelay.deinit
,2017-07-21 06:39:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:39:57 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:39:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:39:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:39:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-21 06:39:57 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Diqy1QudF5zgBNLHeriCnbdKHSgDdP4b","error":"Session disconnected","portNumber":null}'
,2017-07-21 06:39:57 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"8EDCF724-AD07-4005-8DDC-A283D1F0F2FD","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-21 06:39:57 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 06:39:57 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"8EDCF724-AD07-4005-8DDC-A283D1F0F2FD","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 06:39:57 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Session.deinit peer:F090AAFD-5C96-46E7-B54B-705E443D5365
,[ThaliCore] Session.session(_:peer:didChange:) peer:2967B371-2142-4D39-8DDA-E8E4121588B4 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "345FB200-0861-4889-93A7-1CE465A33780", generation: 0)
,[ThaliCore] Session.deinit peer:8EDCF724-AD07-4005-8DDC-A283D1F0F2FD:0
[ThaliCore] BrowserRelay.deinit
,# We do not emit peerAvailabilityChanged events until one of the start methods is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:38F486D4-03D0-4917-A44A-DAF77BC65F86
[ThaliCore] Browser.startListening
2017-07-21 06:39:59 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 06:39:59 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:39:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 103 We should start ,listening fine
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "3DB33481-9DE4-4D7C-9156-69DB440E3787", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:3DB33481-9DE4-4D7C-9156-69DB440E3,7,87
2017-07-21 06:39:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 06:39:59 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true},) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:39:59 - INFO thaliMobile: 'Filtered out discoveryAdvertising,StateUpdate (was in stopped state).'
ok 104 We should start updating fine
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8EDCF724-AD07-4005-8DDC-A283D1F0F2FD:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8EDCF724-AD07-4005-8DDC-A283D1F0F2FD", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:AD6E5E06-F813-4297-B2A5-EC52EB430D2A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "AD6E5E06-F813-4297-B2A5-EC52EB430D2A", generation: 0)
2017-07-21 06:39:59 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"8EDCF724-AD07-4005-8DDC-A283D1F0F2FD","generation":0}]'
2017-07-21 06:39:59 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"8EDCF724-AD07-4005-8DDC-A283D1F0F2FD","generation":0}'
,2017-07-21 06:39:59 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 06:39:59 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"AD6E5E06-F813-4297-B2A5-EC52EB430D2A","generation":0}]'
,2017-07-21 06:39:59 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"AD6E5E06-F813-4297-B2A5-EC52EB430D2A","generation":0}'
,2017-07-21 06:39:59 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9E7DA81F-9EF9-447F-8F0A-8D715861C7B1:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9E7DA81F-9EF9-447F-8F0A-8D715861C7B1", generation: 0)
,2017-07-21 06:40:00 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"9E7DA81F-9EF9-447F-8F0A-8D715861C7B1","generation":0}]'
,2017-07-21 06:40:00 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"9E7DA81F-9EF9-447F-8F0A-8D715861C7B1","generation":0}'
,2017-07-21 06:40:00 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3DB33481-9DE4-4D7C-9156-69DB440E3787:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3DB33481-9DE4-4D7C-9156-69DB440E3787", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:AD6E5E06-F813-4297-B2A5-EC52EB430D2A:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "AD6E5E06-F813-4297-B2A5-EC52EB430D2A", generation: 0)
2017-07-21 06:40:01 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"AD6E5E06-F813-4297-B2A5-EC52EB430D2A","generation":0}]'
2017-07-21 06:40:01 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"AD6E5E06-F813-4297-B2A5-EC52EB430D2A","generation":0}'
2017-07-21 06:40:01 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 06:40:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 ,06:40:05 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-21 06:40:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:3DB33481-9DE4-4D7C-9156-6,9DB440E3787
,2017-07-21 06:40:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:40:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
2017-07-21 06:40:05 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 06:40:05 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 06:40:05 ,- DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:40:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:40:05 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:40:05 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:40:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:40:05 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Test updating advertising and parallel data transfer
,2017-07-21 06:40:05 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test updating advertising and parallel data transfer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:40:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:40:06 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:40:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 06:40:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:40:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 06:40:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 06:40:06 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:40:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 06:40:06 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 06:40:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 06:40:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 06:40:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# discoveryAdvertisingStateUpdateNonTCP is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C2B564EC-3FB6-4DB5-839A-4A1E01702633
[ThaliCore] Browser.startListening
,ok 105 discoveryActive should be false
ok 106 advertisingActive should be true
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C1AABD59-D659-475E-BB2A-2154AEAE06D4", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:C1AABD59-D659-475E-BB2A-2154AEAE06D4
ok 107 discoveryActive should be false
ok 108 advertisingActive should be true
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
ok 109 d,iscoveryActive should be false
ok 110 advertisingActive should be true
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:C1AABD59-D659-475E-BB2A-2154AEAE06D4
ok 111 discoveryActive should be false
ok 112 a,dvertisingActive should be true
ok 113 Can call startListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:40:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 06:40:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 06:40:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:40:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 06:40:06 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 06:40:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 06:40:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 06:40:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call connect when start listening for advertisements is not active
,2017-07-21 06:40:06 - DEBUG CoordinatedClient: 'test was skipped, name: 'cannot call connect when start listening for advertisements is not active''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 06:40:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:40:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 114 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 06:40:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:40:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 115 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# Get error when trying to double connect to a peer on Android
,2017-07-21 06:40:06 - DEBUG CoordinatedClient: 'test was skipped, name: 'Get error when trying to double connect to a peer on Android''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:40:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:40:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 116 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:40:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:40:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 117 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection
,2017-07-21 06:40:07 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:40:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:40:07 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 118 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:40:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:40:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 119 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection
,2017-07-21 06:40:08 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:40:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:40:08 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 120 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:40:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:40:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 121 Should be able to call stopAdvertisingAndListening in tea,rdown
,# setup
,# #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer
,2017-07-21 06:40:08 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:40:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:40:08 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 122 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:40:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:40:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 123 Should be able to call stopAdvertisingAndListening in tea,rdown
,# setup
,# #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer
,2017-07-21 06:40:08 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:40:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:40:09 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 124 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 06:40:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:40:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 125 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# cannot call multiConnect when start listening for advertisements is not active
,ok 126 Got null as expected
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:933b4ef9-d417-469e-b885-d83dd9396b59 error: startListeningNotActive
2017-07-21 06:40:09 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved:, {"syncValue":"auYxNQ0tmDE9Vr6BA7B6Yx7W72Uyo88a","error":"startListeningForAdvertisements is not active","portNumber":null}'
ok 127 Should only get called after multiConnect returned
ok 128 SyncValue matches
ok 129 Got right error
ok 130 listeningPort ,is null
2017-07-21 06:40:09 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"933b4ef9-d417-469e-b885-d83dd9396b59","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 06:40:09 - DEBUG t,haliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-21 06:40:09 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"933b4ef9-d417-469e-b885-d,8,3dd9396b59","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-21 06:40:09 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:40:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:40:09 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:40:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 06:40:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:40:09 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 06:40:09 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 06:40:09 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:40:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 06:40:09 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 06:40:09 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 06:40:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 06:40:09 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with illegal peerID
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C27C0FE1-4A18-41D6-9A13-E2CC2A382729
[ThaliCore] Browser.startListening
,2017-07-21 06:40:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 06:40:09 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:40:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 131 No error on starting
ok 132 Got null as expected
2017-07-21 06:40:09 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"TwCtc6R60zl7nu5HOsYA3dZYyYz7sfCY","error":"Illegal peerID","portNumber",:null}'
ok 133 Should only get called after multiConnect returned
ok 134 SyncValue matches
ok 135 Got right error
ok 136 listeningPort is null
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 06:40:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21, 06:40:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:40:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discovery,Active":false,"advertisingActive":false}'
2017-07-21 06:40:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:40:10 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 06:40:10 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 06:40:10 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:40:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 06:40:10 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 06:40:10 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 06:40:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 06:40:10 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# multiConnect properly fails on legal but non-existent peerID
,2017-07-21 06:40:10 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiConnect properly fails on legal but non-existent peerID''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:40:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:40:10 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:40:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 06:40:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:40:10 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 06:40:10 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 06:40:10 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:40:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 06:40:10 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 06:40:10 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 06:40:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 06:40:10 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with invalid syncValue
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:CCB72FF0-764D-4729-A09B-3A76C303F71D
[ThaliCore] Browser.startListening
2017-07-21 06:40:11 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 06:40:11 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-21 06:40:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 137 No error on starting
ok 138 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 06:40:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21, 06:40:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:40:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discovery,Active":false,"advertisingActive":false}'
2017-07-21 06:40:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:40:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 06:40:11 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 06:40:11 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:40:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 06:40:11 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:40:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:40:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:40:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call disconnect with invalid peer id
,ok 139 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:40:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:40:11 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:40:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 06:40:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 06:40:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 06:40:11 - DEBUG t,haliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 06:40:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:40:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 06:40:11 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 06:40:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 06:40:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
2017-07-21 06:40:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# disconnect doesn't fail on plausible but bogus peer ID
,[ThaliCore] BrowserManager.disconnect peer:78004df0-c5ec-45dc-8bd5-0225b10cc862
ok 140 No error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:40:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:40:12 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:40:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 06:40:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 06:40:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 06:40:12 - DEBUG t,haliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 06:40:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:40:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 06:40:12 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-07-21 06:40:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 06:40:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 06:40:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Get same port when trying to connect multiple times on iOS
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "6DBDADB5-5010-445C-87CD-6652E3BEFD76", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:6DBDADB5-5010-445C-87CD-6652E3BEFD76
2017-07-21 06:40:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 06:40:13, - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkTy,pe":null}})'
2017-07-21 06:40:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 141 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[Tha,liCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:BFB441C5-7BEF-4892-8B40-F564CC686D96
[ThaliCore] Browser.startListening
2017-07-21 06:40:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"adv,e,rtisingActive":true}'
2017-07-21 06:40:13 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"rou,ter":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:40:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 142 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8EDCF724-AD07-4005-8DDC-A283D1F0F2FD:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8EDCF724-AD07-4005-8DDC-A283D1F0F2FD", generation: 0)
2017-07-21 06:40:13 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"8EDCF724-AD07-4005-8DDC-A283D1F0F2FD","generation":0}'
,2017-07-21 06:40:13 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 8EDCF724-AD07-4005-8DDC-A283D1F0F2FD (syncValue: B0gdX3GkzX4y62IzE92D51zBcCduhMmc)'
,2017-07-21 06:40:13 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8EDCF724-AD07-4005-8DDC-A283D1F0F2FD", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8EDCF724-AD07-4005-8DDC-A283D1F0F2FD", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:8EDCF724-AD07-4005-8DDC-A283D1F0F2FD:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6DBDADB5-5010-445C-87CD-6652E3BEFD76:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6DBDADB5-5010-445C-87CD-6652E3BEFD76", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B9EF037C-0FF4-439D-8907-DDAF0D922FDC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B9EF037C-0FF4-439D-8907-DDAF0D922FDC", generation: 0)
2017-07-21 06:40:14 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B9EF037C-0FF4-439D-8907-DDAF0D922FDC","generation":0}'
2017-07-21 06:40:14 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 06:40:14 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:021BF204-4241-4C41-8F59-593ED61743DF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "021BF204-4241-4C41-8F59-593ED61743DF", generation: 0)
2017-07-21 06:40:14 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"021BF204-4241-4C41-8F59-593ED61743DF","generation":0}'
2017-07-21 06:40:14 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 06:40:14 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-21 06:40:14 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:221F9872-C922-40B1-8C2B-9ECE3E0D28CC
[ThaliCore] Advertiser: session connected Peer(uuid: "6DBDADB5-5010-445C-87CD-6652E3BEFD76", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:221F9872-C922-40B1-8C2B-9ECE3E0D28CC state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:8EDCF724-AD07-4005-8DDC-A283D1F0F2FD:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:8EDCF724-AD07-4005-8DDC-A283D1F0F2FD:0
,[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "8EDCF724-AD07-4005-8DDC-A283D1F0F2FD", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8EDCF724-AD07-4005-8DDC-A283D1F0F2FD", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8EDCF724-AD07-4005-8DDC-A283D1F0F2FD", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:8EDCF724-AD07-4005-8DDC-A283D1F0F2FD:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:8EDCF724-AD07-4005-8DDC-A283D1F0F2FD:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:221F9872-C922-40B1-8C2B-9ECE3E0D28CC
,[ThaliCore] Session.session(_:peer:didChange:) peer:221F9872-C922-40B1-8C2B-9ECE3E0D28CC state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:221F9872-C922-40B1-8C2B-9ECE3E0D28CC
[ThaliCore] Session.startOutputStream(with:) peer:221F9872-C922-40B1-8C2B-9ECE3E0D28CC
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,4 [1, 3, 7, 14]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:8EDCF724-AD07-4005-8DDC-A283D1F0F2FD:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:8EDCF724-AD07-4005-8DDC-A283D1F0F2FD:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "8EDCF724-AD07-4005-8DDC-A283D1F0F2FD", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,EDCF724-AD07-4005-8DDC-A283D1F0F2FD", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8EDCF724-AD07-4005-8DDC-A283D1F0F2FD", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:8EDCF724-AD07-4005-8DDC-A283D1F0F2FD:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:8EDCF724-AD07-4005-8DDC-A283D1F0F2FD:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:8EDCF724-AD07-4005-8DDC-A283D1F0F2FD:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:8E,DCF724-AD07-4005-8DDC-A283D1F0F2FD:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "8EDCF724-AD07-4005-8DDC-A283D1F0F2FD", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,EDCF724-AD07-4005-8DDC-A283D1F0F2FD", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8EDCF724-AD07-4005-8DDC-A283D1F0F2FD", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:8EDCF724-AD07-4005-8DDC-A283D1F0F2FD:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:8EDCF724-AD07-4005-8DDC-A283D1F0F2FD:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:6EE8EC57-30D9-4CC3-A908-6AC23295A5F8
[ThaliCore] Advertiser: session connected Peer(uuid: "6DBDADB5-5010-445C-87CD-6652E3BEFD76", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:6EE8EC57-30D9-4CC3-A908-6AC23295A5F8 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:8EDCF724-AD07-4005-8DDC-A283D1F0F2FD:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:8E,DCF724-AD07-4005-8DDC-A283D1F0F2FD:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "8EDCF724-AD07-4005-8DDC-A283D1F0F2FD", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:8EDCF724-AD07-4005-8DDC-A283D1F0F2FD error: max retries exceeded
,2017-07-21 06:40:24 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"B0gdX3GkzX4y62IzE92D51zBcCduhMmc","error":"Connection could not be established","portNumber":null}'
,2017-07-21 06:40:24 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'B0gdX3GkzX4y62IzE92D51zBcCduhMmc', error: 'Connection could not be established', listeningPort: '%s''
,2017-07-21 06:40:24 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"8EDCF724-AD07-4005-8DDC-A283D1F0F2FD","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-21 06:40:24 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-21 06:40:24 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"8EDCF724-AD07-4005-8DDC-A283D1F0F2FD","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-21 06:40:24 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 06:40:24 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-21 06:40:24 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B9EF037C-0FF4-439D-8907-DDAF0D922FDC (syncValue: 3DOf5Npaz0mbTnzo2ibuW9Fdp3hrhhBW)'
,2017-07-21 06:40:24 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B9EF037C-0FF4-439D-8907-DDAF0D922FDC", generation: 0) creating a new relay
[Tha,liCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B9EF037C-0FF4-439D-8907-DDAF0D922FDC", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B9EF037C-0FF4-439D-8907-DDAF0D922FDC:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-21 06:40:24 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 06:40:24 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:8EDCF724-AD07-4005-8DDC-A283D1F0F2FD:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:B9EF037C-0FF4-439D-8907-DDAF0D922FDC:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:8EDCF724-AD07-4005-8DDC-A283D1F0F2FD:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "8EDCF724-AD07-4005-8DDC-A283D1F0F2FD", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:6EE8EC57-30D9-4CC3-A908-6AC23295A5F8
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B9EF037C-0FF4-439D-8907-DDAF0D922FDC:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:6EE8EC57-30D9-4CC3-A908-6AC23295A5F8 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:B9EF037C-0FF4-439D-8907-DDAF0D922FDC:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "B9EF037C-0FF4-439D-8907-DDAF0D922FDC", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:55301
,2017-07-21 06:40:27 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"3DOf5Npaz0mbTnzo2ibuW9Fdp3hrhhBW","error":null,"portNumber":55301}'
,2017-07-21 06:40:27 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '3DOf5Npaz0mbTnzo2ibuW9Fdp3hrhhBW', error: 'null', listeningPort: '55301''
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B9EF037C-0FF4-439D-8907-DDAF0D922FDC:0
,ok 143 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B9EF037C-0FF4-439D-8907-DDAF0D922FDC", generation: 0) found active relay
,2017-07-21 06:40:27 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"DIgK3VolQ8koUDQhw5XNdKhXo5NeFSYi","error":null,"portNumber":55301}'
,ok 144 No error
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B9EF037C-0FF4-439D-8907-DDAF0D922FDC:0
ok 145 Ports equal
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:15 [1, 3, 7, 14, 15]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 146 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B9EF037C-0FF4-439D-8907-DDAF0D922FDC", generation: 0) found active relay
,2017-07-21 06:40:27 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"fRaPjvguEgeN94TRbBztsc19fZ84M8kN","error":null,"portNumber":55301}'
,ok 147 No error
,ok 148 Ports equal
,# teardown
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:6EE8EC57-30D9-4CC3-A908-6AC23295A5F8
[ThaliCore] Session.startOutputStream(with:) peer:6EE8EC57-30D9-4CC3-A908-6AC23295A5F8
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:16 [1, 3, 7, 14, 15, 16]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-21 06:40:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 06:40:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 06:40:28 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:40:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:6DBDADB5-5010-445C-87CD-6652E3BEFD76
2017-07-21 06:40:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06,:,40:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed, by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer", UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocke,tDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:14
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandl,e,r removed virtual socket vsID:16
[ThaliCore] VirtualSocket.closeStreams() vsID:14
[ThaliCore] BrowserManager.disconnect peer:B9EF037C-0FF4-439D-8907-DDAF0D922FDC
[ThaliCore] VirtualSocket.closeStreams() vsID:16
[ThaliCore] BrowserRelay.closeRelay() sta,te:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:55301
,[ThaliCore] VirtualSocket.closeStreams() vsID:15
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:14
,[ThaliCore] VirtualSocket.deinit vsID:14 [1, 3, 7, 15, 16]
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:16
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler ,state:disconnecting
[ThaliCore] VirtualSocket exited RunLoop vsID:15
[ThaliCore] VirtualSocket.deinit vsID:16 [1, 3, 7, 15]
[ThaliCore] Session.disconnect() peer:B9EF037C-0FF4-439D-8907-DDAF0D922FDC:0
[ThaliCore] VirtualSocket.closeStreams() vsID:15
[,ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket.deinit vsID:15 [1, 3, 7]
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:B9EF037C-0FF4-439D-8907-DDAF0D922FDC:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uui,d: "B9EF037C-0FF4-439D-8907-DDAF0D922FDC", generation: 0)
,2017-07-21 06:40:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 06:40:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 06:40:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:40:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:40:28 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:40:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:40:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:40:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-21 06:40:28 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"3DOf5Npaz0mbTnzo2ibuW9Fdp3hrhhBW","error":"Session disconnected","portNumber":null}'
,2017-07-21 06:40:28 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"B9EF037C-0FF4-439D-8907-DDAF0D922FDC","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-21 06:40:28 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 06:40:28 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"B9EF037C-0FF4-439D-8907-DDAF0D922FDC","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 06:40:28 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Session.session(_:peer:didChange:) peer:6EE8EC57-30D9-4CC3-A908-6AC23295A5F8 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "6DBDADB5-5010-445C-87CD-6652E3BEFD76", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:6EE8EC57-30D9-4CC3-A908-6AC23295A5F8
,[ThaliCore] Session.session(_:peer:didChange:) peer:221F9872-C922-40B1-8C2B-9ECE3E0D28CC state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "6DBDADB5-5010-445C-87CD-6652E3BEFD76", generation: 0)
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:B9EF037C-0FF4-439D-8907-DDAF0D922FDC:0
[ThaliCore] BrowserRelay.deinit
,# initial peer discovery
,2017-07-21 06:40:28 - DEBUG CoordinatedClient: 'test was skipped, name: 'initial peer discovery''
,# teardown
,2017-07-21 06:40:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 06:40:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 06:40:29 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:40:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 06:40:29 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 06:40:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 06:40:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 06:40:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.deinit peer:6EE8EC57-30D9-4CC3-A908-6AC23295A5F8
,# update peer discovery 1
,2017-07-21 06:40:29 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 1''
,# teardown
,2017-07-21 06:40:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 06:40:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 06:40:29 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:40:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 06:40:29 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 06:40:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 06:40:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 06:40:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 2
,2017-07-21 06:40:29 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 2''
,# teardown
,2017-07-21 06:40:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 06:40:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 06:40:29 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:40:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 06:40:29 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-07-21 06:40:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 06:40:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 06:40:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# check latest peer discovery
,2017-07-21 06:40:30 - DEBUG CoordinatedClient: 'test was skipped, name: 'check latest peer discovery''
,# teardown
,2017-07-21 06:40:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 06:40:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 06:40:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:40:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 06:40:30 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 06:40:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 06:40:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 06:40:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Set up for no peer discovery test
,2017-07-21 06:40:30 - DEBUG CoordinatedClient: 'test was skipped, name: 'Set up for no peer discovery test''
,# teardown
,2017-07-21 06:40:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 06:40:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 06:40:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:40:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 06:40:30 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 06:40:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 06:40:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 06:40:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# no peer discovery
,2017-07-21 06:40:30 - DEBUG CoordinatedClient: 'test was skipped, name: 'no peer discovery''
,# teardown
,2017-07-21 06:40:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 06:40:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 06:40:30 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:40:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 06:40:30 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 06:40:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 06:40:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 06:40:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calling createNativeListener directly rejects
,2017-07-21 06:40:31 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 06:40:31 - DEBUG createNativeListener: 'listening 55305'
,ok 149 Should throw
,# teardown
,2017-07-21 06:40:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 06:40:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 06:40:31 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits incomingConnectionState
,2017-07-21 06:40:31 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 06:40:31 - DEBUG createNativeListener: 'listening 55307'
,2017-07-21 06:40:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-21 06:40:31 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 150 initial connection state should be CONNECTED
,2017-07-21 06:40:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 151 final connection state should be DISCONNECTED
,# teardown
,2017-07-21 06:40:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 06:40:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 06:40:31 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits routerPortConnectionFailed
,2017-07-21 06:40:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 06:40:31 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 06:40:31 - DEBUG createNativeListener: 'listening 55310'
,2017-07-21 06:40:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-21 06:40:31 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 06:40:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-21 06:40:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - error Error: connect ECONNREFUSED'
,ok 152 tried to connect to right port
,ok 153 failed due to refused connection
,ok 154 routerPortConnectionFailed is emitted
,# teardown
,2017-07-21 06:40:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-21 06:40:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-21 06:40:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 06:40:32 - DEBUG createNativeListener: 'Native Server - close'
2017-07-21 06:40:32 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <,-> Mux - 0 - close'
,2017-07-21 06:40:32 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server connections all up
,2017-07-21 06:40:32 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-21 06:40:32 - DEBUG createNativeListener: 'listening 55314'
,2017-07-21 06:40:32 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-21 06:40:32 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 06:40:32 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2017-07-21 06:40:32 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,ok 155 Send/recvd #1 should be equal length
,ok 156 Send/recvd #1 should be same
,ok 157 Send/recvd #2 should be equal length
,ok 158 Send/recvd #2 should be same
,ok 159 Should be exactly 2 client sockets
,# teardown
,2017-07-21 06:40:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 06:40:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 06:40:32 - DEBUG createNativeListener: 'Native Server - close'
2017-07-21 06:40:32, - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-21 06:40:32 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
2017-07-21 06:40:32 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close',
2017-07-21 06:40:32 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
2017-07-21 06:40:32 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
2017-07-21 06:40:32 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection, to node - 0 - 0 - close'
,# native server - closing incoming stream cleans outgoing socket
,2017-07-21 06:40:32 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-21 06:40:32 - DEBUG createNativeListener: 'listening 55319'
,2017-07-21 06:40:32 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-21 06:40:32 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 06:40:32 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-21 06:40:32 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
2017-07-21 06:40:32 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node -, 0 - 0 - closed'
,ok 160 socket shouldn't close until after stream
ok 161 incoming remains open
# teardown
,2017-07-21 06:40:32 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-21 06:40:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 06:40:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 06:40:32 - DEBUG createNativeListener: 'Native Server - close'
2017-07-21 06:40:32, - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-21 06:40:32 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing incoming connection cleans outgoing socket
,2017-07-21 06:40:33 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-21 06:40:33 - DEBUG createNativeListener: 'listening 55323'
,2017-07-21 06:40:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-21 06:40:33 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 162 we should not have gotten an error
,2017-07-21 06:40:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-21 06:40:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2017-07-21 06:40:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 163 socket shouldn't close until after incoming
ok 164 incoming is cleaned up
# teardown
,2017-07-21 06:40:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-21 06:40:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 06:40:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 06:40:33 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - closing outgoing socket cleans associated mux stream
,2017-07-21 06:40:33 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 06:40:33 - DEBUG createNativeListener: 'listening 55327'
,2017-07-21 06:40:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-21 06:40:33 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 06:40:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-21 06:40:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-07-21 06:40:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-21 06:40:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,ok 165 stream was closed
,ok 166 incoming should survive
,ok 167 mux should have no streams
,# teardown
,2017-07-21 06:40:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 06:40:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 06:40:33 - DEBUG createNativeListener: 'Native Server - close'
2017-07-21 06:40:33, - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-21 06:40:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing the whole server cleans everything up
,2017-07-21 06:40:33 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 06:40:33 - DEBUG createNativeListener: 'listening 55331'
,2017-07-21 06:40:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-21 06:40:33 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 168 we should not have gotten an error
,2017-07-21 06:40:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 169 Buffers are identical
2017-07-21 06:40:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 06:40:33 - DEBUG createNativeListener: 'Native Server - close'
2017-07-21 06:40:33 - DEBUG createNativeListener: 'stream - mux stream, <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2017-07-21 06:40:33 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 170 native server is nulled out
ok 171 native server should be cl,osed
ok 172 incoming has been removed
ok 173 Incoming should be done
ok 174 The mux object should be closed
ok 175 The mux stream should be closed
2017-07-21 06:40:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection ,<-> Mux - 0 - close'
,# teardown
2017-07-21 06:40:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-21 06:40:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - we can get a ton of connections and data through and still clean up the server completely
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'listening 55335'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-21 06:40:34 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - created'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - created'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - created'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - created'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - created'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - created'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - created'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - created'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - created'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - created'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - created'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - created'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - created'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - created'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - created'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - created'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - created'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - created'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - created'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - created'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - created'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - created'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - created'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - created'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - created'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - created'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - created'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - created'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - created'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - created'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - created'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - created'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - created'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - created'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - created'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - created'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - created'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - created'
,2017-07-21 06:40:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - closed'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - closed'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - closed'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - closed'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - closed'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - closed'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - closed'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - closed'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - closed'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - closed'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - closed'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - closed'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - closed'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - closed'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - closed'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - closed'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - closed'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - closed'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - closed'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - closed'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - closed'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - closed'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - closed'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - closed'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - closed'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - closed'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - closed'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - closed'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - closed'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - closed'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - closed'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - closed'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - closed'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - closed'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - closed'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - closed'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - closed'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - closed'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,ok 176 native server is nulled out
,ok 177 native server should be closed
,ok 178 incoming has been removed
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - close'
2017-07-21 06:40:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - close'
2017-07-21 06:40:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - close'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - close'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - close'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - close'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - close'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - close'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - close'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - close'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - close'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - close'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - close'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - close'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - close'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - close'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - close'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - close'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - close'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - close'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - close'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - close'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - close'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - close'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - close'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - close'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - close'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - close'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - close'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - close'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - close'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - close'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - close'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - close'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - close'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - close'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - close'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - close'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-21 06:40:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - simulate mux failure, make sure everything is cleaned up
,2017-07-21 06:40:35 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 06:40:35 - DEBUG createNativeListener: 'listening 55387'
,2017-07-21 06:40:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-21 06:40:35 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 179 we should not have gotten an error
,2017-07-21 06:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 180 Buffers are identical
,2017-07-21 06:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-21 06:40:35 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-21 06:40:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 181 server should be fine
,ok 182 server should be open
,ok 183 incoming has been removed
,ok 184 The mux object should be closed
,ok 185 The mux stream should be closed
,2017-07-21 06:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-21 06:40:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 06:40:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 06:40:35 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - timing out the incoming connection cleans everything up
,2017-07-21 06:40:35 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-21 06:40:35 - DEBUG createNativeListener: 'listening 55391'
,2017-07-21 06:40:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-21 06:40:35 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 186 we should not have gotten an error
,2017-07-21 06:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 187 Buffers are identical
,2017-07-21 06:40:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - incoming socket timeout'
2017-07-21 06:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to ,node - 0 - 0 - closed'
2017-07-21 06:40:35 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2017-07-21 06:40:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux, - 0 - close'
ok 188 server should be fine
ok 189 server should be open
ok 190 incoming has been removed
ok 191 The mux object should be closed
ok 192 The mux stream should be closed
,# teardown
,2017-07-21 06:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-21 06:40:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 06:40:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 06:40:35 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# can create servers manager
,ok 193 serversManager must not be null
ok 194 serversManager must be an object
,# teardown
,# setup
,# calling stop without start causes error
,ok 195 We need to call start first
,# teardown
,# setup
,# can start/stop servers manager
,2017-07-21 06:40:36 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-21 06:40:36 - DEBUG createNativeListener: 'listening 55394'
,ok 196 port must be in range
,# teardown
,2017-07-21 06:40:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 06:40:36 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# starting twice resolves with listening port
,2017-07-21 06:40:36 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 06:40:36 - DEBUG createNativeListener: 'listening 55395'
ok 197 second start should return same port
,# teardown
,2017-07-21 06:40:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 06:40:36 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminateIncomingConnection will terminate a connection
,2017-07-21 06:40:36 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-21 06:40:36 - DEBUG createNativeListener: 'listening 55397'
,2017-07-21 06:40:36 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-21 06:40:36 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 198 we should be connected
2017-07-21 06:40:36 - DEB,UG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 199 now we are disconnected
,2017-07-21 06:40:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# teardown
,2017-07-21 06:40:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 06:40:37 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminate an Outgoing connection
,2017-07-21 06:40:37 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 32'
,ok 200 Passed bogus id
2017-07-21 06:40:37 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 901'
ok 201 Passed good id but bogus port
2017-07-21 06:40:37 - DEBUG thaliTcpServersManager: 'Terminate outgoing co,nnection called on peerID foo with port 900'
ok 202 Passed right context
ok 203 Right server
ok 204 No error should be set
,ok 205 Retry should be false
,ok 206 We called close server
,# teardown
,# setup
,# Single local http request
,listening on 55399
,ok 207 should be equal
# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 06:40:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:40:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 06:40:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:40:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:40:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 06:40:37 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 06:40:37 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 06:40:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:40:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:40:37 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:40:37 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:40:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:40:37 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Single coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "B229F4CE-E556-41EA-9DF9-305580986B89", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:B229F4CE-E556-41EA-9DF9-305580986B89
,2017-07-21 06:40:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 06:40:38 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:40:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 208 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:BDB2C972-83F7-4156-841C-F88D47B,911C5
[ThaliCore] Browser.startListening
2017-07-21 06:40:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 06:40:38 - INFO thaliMobile: 'Received state ({"discove,r,yActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:40:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 209 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B9EF037C-0FF4-439D-8907-DDAF0D922FDC:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B9EF037C-0FF4-439D-8907-DDAF0D922FDC", generation: 0)
,2017-07-21 06:40:38 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B9EF037C-0FF4-439D-8907-DDAF0D922FDC","generation":0}'
,2017-07-21 06:40:38 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B9EF037C-0FF4-439D-8907-DDAF0D922FDC (syncValue: Z4Gv2nRAEMFlTy6HtGVFovJ3pzO4Sq0M)'
,2017-07-21 06:40:38 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B9EF037C-0FF4-439D-8907-DDAF0D922FDC", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B9EF037C-0FF4-439D-8907-DDAF0D922FDC", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B9EF037C-0FF4-439D-8907-DDAF0D922FDC:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:97F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "97F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A", generation: 0)
2017-07-21 06:40:38 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"97F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A","generation":0}'
2017-07-21 06:40:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 06:40:38 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D80DF37F-49FA-4AA6-BEE5-74D7A3EC7F07:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D80DF37F-49FA-4AA6-BEE5-74D7A3EC7F07", generation: 0)
,2017-07-21 06:40:39 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"D80DF37F-49FA-4AA6-BEE5-74D7A3EC7F07","generation":0}'
2017-07-21 06:40:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 06:40:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 06:40:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B229F4CE-E556-41EA-9DF9-305580986B89:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B229F4CE-E556-41EA-9DF9-305580986B89", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:B9EF037C-0FF4-439D-8907-DDAF0D922FDC:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B9,EF037C-0FF4-439D-8907-DDAF0D922FDC:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "B9EF037C-0FF4-439D-8907-DDAF0D922FDC", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,9EF037C-0FF4-439D-8907-DDAF0D922FDC", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B9EF037C-0FF4-439D-8907-DDAF0D922FDC", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:B9EF037C-0FF4-439D-8907-DDAF0D922FDC:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:B9EF037C-0FF4-439D-8907-DDAF0D922FDC:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:B9EF037C-0FF4-439D-8907-DDAF0D922FDC:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "B9EF037C-0FF4-439D-8907-DDAF0D922FDC", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:B9EF037C-0FF4-439D-8907-DDAF0D922FDC:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B9,EF037C-0FF4-439D-8907-DDAF0D922FDC:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "B9EF037C-0FF4-439D-8907-DDAF0D922FDC", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,9EF037C-0FF4-439D-8907-DDAF0D922FDC", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B9EF037C-0FF4-439D-8907-DDAF0D922FDC", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 06:40:43 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Z4Gv2nRAEMFlTy6HtGVFovJ3pzO4Sq0M","error":"Peer is unavailable",,"portNumber":null}'
2017-07-21 06:40:43 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'Z4Gv2nRAEMFlTy6HtGVFovJ3pzO4Sq0M', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-21 06:40:43 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"B9EF037C-0FF4-439D-8907-DDAF0D922FDC","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 06:40:43 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-21 06:40:43 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"B9EF037C-0FF4-439D-8907-DDAF0D922FDC","peerAvailable":true,"portNumber":null,"recreate,d,":true}'
2017-07-21 06:40:43 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 06:40:43 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-21 06:40:43 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 97F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A (syncValue: cDhcPtqmWP8J6UIz56wepV5,gaRGj2vp5)'
2017-07-21 06:40:43 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "97F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "97F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:97F9C3ED-F1BD-4C12-A7FD-B7BF2,30EA03A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-21 06:40:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:B9EF037C-0FF4-439D-8907-DDAF0D922FDC:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:97F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:97F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:97F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "97F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:55405
2017-07-21 06:40:45 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"cDhcPtqmWP8J6UIz56wepV5gaRGj2vp5",,"error":null,"portNumber":55405}'
2017-07-21 06:40:45 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'cDhcPtqmWP8J6UIz56wepV5gaRGj2vp5', error: 'null', listeningPort: '55405''
,ok 210 should be equal
2017-07-21 06:40:45 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for D80DF37F-49FA-4AA6-BEE5-74D7A3EC7F07 (syncValue: R71NFxrUE0wUG3D5akZFiNZMLaRESp01)'
2017-07-21 06:40:45 - DEBUG thaliMobileNativeTestUtils: 'Got 'mul,tiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D80DF37F-49FA-4AA6-BEE5-74D7A3EC7F07", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConn,ected:) Peer(uuid: "D80DF37F-49FA-4AA6-BEE5-74D7A3EC7F07", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D80DF37F-49FA-4AA6-BEE5-74D7A3EC7F07:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocke,tTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:D80DF37F-49FA-4AA6-BEE5-74D7A3EC7F07:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D80DF37F-49FA-4AA6-BEE5-74D7A3EC7F07:0
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:AB595394-AD24-4AD2-964F-7F71E4BBADF2
[ThaliCore] Advertiser: session connected Peer(uuid: "B229F4CE-E556-41EA-9DF9-305580986B89", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:AB595394-AD24-4AD2-964F-7F71E4BBADF2 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:D80DF37F-49FA-4AA6-BEE5-74D7A3EC7F07:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "D80DF37F-49FA-4AA6-BEE5-74D7A3EC7F07", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:55409
,2017-07-21 06:40:50 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"R71NFxrUE0wUG3D5akZFiNZMLaRESp01","error":null,"portNumber":55409}'
,2017-07-21 06:40:50 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'R71NFxrUE0wUG3D5akZFiNZMLaRESp01', error: 'null', listeningPort: '55409''
,ok 211 should be equal
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:21094AAD-E96C-406C-ABAF-25B50B148D73
[ThaliCore] Advertiser: session connected Peer(uuid: "B229F4CE-E556-41EA-9DF9-305580986B89", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:21094AAD-E96C-406C-ABAF-25B50B148D73 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:AB595394-AD24-4AD2-964F-7F71E4BBADF2
,[ThaliCore] Session.session(_:peer:didChange:) peer:AB595394-AD24-4AD2-964F-7F71E4BBADF2 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:21094AAD-E96C-406C-ABAF-25B50B148D73
,[ThaliCore] Session.session(_:peer:didChange:) peer:21094AAD-E96C-406C-ABAF-25B50B148D73 state: connecting -> connected
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 06:40:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 06:40:55 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-21 06:40:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:B229F4CE-E556-41EA-9DF9-3,05580986B89
2017-07-21 06:40:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:40:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
[ThaliCore] BrowserManager.disconnect peer:97F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:55405
[ThaliCore] Sessi,on.disconnect() peer:97F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:97F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
,[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "97F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A", generation: 0)
,[ThaliCore] BrowserManager.disconnect peer:D80DF37F-49FA-4AA6-BEE5-74D7A3EC7F07
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:55409
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:D80DF37F-49FA-4AA6-BEE5-74D7A3EC7F07:0
,[ThaliCore] Session.deinit peer:D80DF37F-49FA-4AA6-BEE5-74D7A3EC7F07:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-21 06:40:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 06:40:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 06:40:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 06:40:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,[ThaliCore] Session.session(_:peer:didChange:) peer:AB595394-AD24-4AD2-964F-7F71E4BBADF2 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "B229F4CE-E556-41EA-9DF9-305580986B89", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:21094AAD-E96C-406C-ABAF-25B50B148D73
,2017-07-21 06:40:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 06:40:56 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:40:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:40:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:40:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-21 06:40:56 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"cDhcPtqmWP8J6UIz56wepV5gaRGj2vp5","error":"Session disconnected","portNumber":null}'
,2017-07-21 06:40:56 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"97F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-21 06:40:56 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 06:40:56 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"97F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 06:40:56 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Session.deinit peer:21094AAD-E96C-406C-ABAF-25B50B148D73
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:97F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A:0
[ThaliCore] BrowserRelay.deinit
,# Multiple local http requests
,listening on 55411
,ok 212 should be equal
ok 213 should be equal
ok 214 should be equal
# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:40:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:40:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:40:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 06:40:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:40:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 06:40:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 06:40:57 - DEBUG thaliMobileNativeWrapper: 'Method disc,overyAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 06:40:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:40:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:40:57 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:40:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:40:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:40:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Multiple coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "5689EEB6-FCF1-4CC7-9435-5FCCA56D8276", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:5689EEB6-FCF1-4CC7-9435-5FCCA56D8276
2017-07-21 06:40:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 06:40:57, - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkTy,pe":null}})'
2017-07-21 06:40:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 215 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[Tha,liCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:8AFF1BBF-CA5C-452B-A9E1-97A7293B6A78
[ThaliCore] Browser.startListening
2017-07-21 06:40:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"adv,e,rtisingActive":true}'
2017-07-21 06:40:57 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"rou,ter":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:40:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 216 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:97F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "97F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A", generation: 0)
2017-07-21 06:40:58 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"97F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A","generation":0}'
2017-07-21 06:40:58 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 97F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A, (syncValue: JQ6QKISjUwORJdK8PVEUZTLO9kDlrPbo)'
2017-07-21 06:40:58 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "97F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "97F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:97F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A:0,
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D80DF37F-49FA-4AA6-BEE5-74D7A3EC7F07:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedList,ening:)
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D80DF37F-49FA-4AA6-BEE5-74D7A3EC7F07", generation: 0)
2017-07-21 06:40:58 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"D80DF37F-49FA-4AA6-B,EE5-74D7A3EC7F07","generation":0}'
2017-07-21 06:40:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 06:40:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:97F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "97F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscov,eryInfo:) found peer:5689EEB6-FCF1-4CC7-9435-5FCCA56D8276:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5689EEB6-FCF1-4CC7-9435-5FCCA56D8276", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B4D260E1-1E5D-426D-8AB0-42B7621CD7F5:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B4D260E1-1E5D-426D-8AB0-42B7621CD7F5", generation: 0)
2017-07-21 06:40:59 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B4D260E1-1E5D-426D-8AB0-42B7621CD7F5","generation":0}'
2017-07-21 06:40:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 06:40:59 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1DEBA3A8-6191-44CA-9535-55D68D86F143:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1DEBA3A8-6191-44CA-9535-55D68D86F143", g,eneration: 0)
2017-07-21 06:40:59 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"1DEBA3A8-6191-44CA-9535-55D68D86F143","generation":0}'
2017-07-21 06:40:59 - DEBUG thaliMobileNativeTestUtils: 'Already running ,t,est!'
2017-07-21 06:40:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 06:40:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:D80DF37F-49FA-4AA6-BEE5-74D7A3EC7F07:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "D80DF37F-49FA-4AA6-BEE5-74D7A3EC7F07", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:97F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:97,F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "97F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,7F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "97F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 06:41:01 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"JQ6QKISjUwORJdK8PVEUZTLO9kDlrPbo","error":"Peer is unavailable",,"portNumber":null}'
2017-07-21 06:41:01 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'JQ6QKISjUwORJdK8PVEUZTLO9kDlrPbo', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-21 06:41:01 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"97F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 06:41:01 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-21 06:41:01 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"97F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A","peerAvailable":true,"portNumber":null,"recreate,d,":true}'
2017-07-21 06:41:01 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 06:41:01 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-21 06:41:01 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B4D260E1-1E5D-426D-8AB0-42B7621CD7F5 (syncValue: oe06LKGaP3EEMtf2ZAW9cFm,h35IiifSE)'
2017-07-21 06:41:01 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B4D260E1-1E5D-426D-8AB0-42B7621CD7F5", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B4D260E1-1E5D-426D-8AB0-42B7621CD7F5", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B4D260E1-1E5D-426D-8AB0-42B76,21CD7F5:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-21 06:41:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:97F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:B4D260E1-1E5D-426D-8AB0-42B7621CD7F5:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B4D260E1-1E5D-426D-8AB0-42B7621CD7F5:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:B4D260E1-1E5D-426D-8AB0-42B7621CD7F5:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "B4D260E1-1E5D-426D-8AB0-42B7621CD7F5", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:55422
2017-07-21 06:41:04 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"oe06LKGaP3EEMtf2ZAW9cFmh35IiifSE",,"error":null,"portNumber":55422}'
2017-07-21 06:41:04 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'oe06LKGaP3EEMtf2ZAW9cFmh35IiifSE', error: 'null', listeningPort: '55422''
,ok 217 should be equal
,ok 218 should be equal
,ok 219 should be equal
,2017-07-21 06:41:04 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 1DEBA3A8-6191-44CA-9535-55D68D86F143 (syncValue: K2JUTk2Cs9OQVkwFDkZs9z66z6I0bnZo)'
,2017-07-21 06:41:04 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1DEBA3A8-6191-44CA-9535-55D68D86F143", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1DEBA3A8-6191-44CA-9535-55D68D86F143", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1DEBA3A8-6191-44CA-9535-55D68D86F143:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:1DEBA3A8-6191-44CA-9535-55D68D86F143:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:1DEBA3A8-6191-44CA-9535-55D68D86F143:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:1DEBA3A8-6191-44CA-9535-55D68D86F143:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "1DEBA3A8-6191-44CA-9535-55D68D86F143", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:55428
,2017-07-21 06:41:07 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"K2JUTk2Cs9OQVkwFDkZs9z66z6I0bnZo","error":null,"portNumber":55428}'
,2017-07-21 06:41:07 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'K2JUTk2Cs9OQVkwFDkZs9z66z6I0bnZo', error: 'null', listeningPort: '55428''
,ok 220 should be equal
,ok 221 should be equal
,ok 222 should be equal
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:57936B90-F736-49DF-90BA-74ED9D908149
[ThaliCore] Advertiser: session connected Peer(uuid: "5689EEB6-FCF1-4CC7-9435-5FCCA56D8276", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:57936B90-F736-49DF-90BA-74ED9D908149 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:021BF204-4241-4C41-8F59-593ED61743DF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "021BF204-4241-4C41-8F59-593ED61743DF", generation: 0)
2017-07-21 06:41:09 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"021BF204-4241-4C41-8F59-593ED61743DF","generation":0}'
2017-07-21 06:41:09 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 021BF204-4241-4C41-8F59-593ED61743DF, (syncValue: skTaJFtuwpVVWKx2h6DFu6RfAbxMqrOB)'
2017-07-21 06:41:09 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "021BF204-4241-4C41-8F59-593ED61,743DF", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "021BF204-4241-4C41-8F59-593ED61743DF", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected,:,) peer:021BF204-4241-4C41-8F59-593ED61743DF:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:57936B90-F736-49DF-90BA-74ED9D908149
,[ThaliCore] Session.session(_:peer:didChange:) peer:021BF204-4241-4C41-8F59-593ED61743DF:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:021BF204-4241-4C41-8F59-593ED61743DF:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "021BF204-4241-4C41-8F59-593ED61743DF", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0,21BF204-4241-4C41-8F59-593ED61743DF", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "021BF204-4241-4C41-8F59-593ED61743DF", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:021BF204-4241-4C41-8F59-593ED61743DF:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:021BF204-4241-4C41-8F59-593ED61743DF:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:57936B90-F736-49DF-90BA-74ED9D908149 state: connecting -> connected
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:06107CC2-63F0-4466-8497-8FD5EA8F0376
[ThaliCore] Advertiser: session connected Peer(uuid: "5689EEB6-FCF1-4CC7-9435-5FCCA56D8276", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:06107CC2-63F0-4466-8497-8FD5EA8F0376 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:021BF204-4241-4C41-8F59-593ED61743DF:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:02,1BF204-4241-4C41-8F59-593ED61743DF:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "021BF204-4241-4C41-8F59-593ED61743DF", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0,21BF204-4241-4C41-8F59-593ED61743DF", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "021BF204-4241-4C41-8F59-593ED61743DF", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:021BF204-4241-4C41-8F59-593ED61743DF:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:021BF204-4241-4C41-8F59-593ED61743DF:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:06107CC2-63F0-4466-8497-8FD5EA8F0376
,[ThaliCore] Session.session(_:peer:didChange:) peer:06107CC2-63F0-4466-8497-8FD5EA8F0376 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:021BF204-4241-4C41-8F59-593ED61743DF:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:02,1BF204-4241-4C41-8F59-593ED61743DF:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "021BF204-4241-4C41-8F59-593ED61743DF", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0,21BF204-4241-4C41-8F59-593ED61743DF", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "021BF204-4241-4C41-8F59-593ED61743DF", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:021BF204-4241-4C41-8F59-593ED61743DF:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:021BF204-4241-4C41-8F59-593ED61743DF:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:021BF204-4241-4C41-8F59-593ED61743DF:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:02,1BF204-4241-4C41-8F59-593ED61743DF:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "021BF204-4241-4C41-8F59-593ED61743DF", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:021BF204,-4241-4C41-8F59-593ED61743DF error: max retries exceeded
2017-07-21 06:41:20 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"skTaJFtuwpVVWKx2h6DFu6RfAbxMqrOB","error":"Connection could not be established","portNumber":null}'
2017-0,7-21 06:41:20 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'skTaJFtuwpVVWKx2h6DFu6RfAbxMqrOB', error: 'Connection could not be established', listeningPort: '%s''
2017-07-21 06:41:20 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"021BF204-4241-4C41-8F59-593ED61743DF","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 06:41:20 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-21 06:41:20 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"021BF204-4241-4C41-8F59-593ED61743DF","peerAvailable":true,"portNumber":null,"recreated":true}'
20,17-07-21 06:41:20 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 06:41:20 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-21 06:41:20 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 021BF204-4241-4C41-8F59-593ED61743DF (syncValue: q1ZeC7V,MXtHNPp7AcU15mCfikWfWahaf)'
2017-07-21 06:41:20 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "021BF204-4241-4C41-8F59-593ED61743DF", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "021BF204-4241-4C41-8F59-593ED61743DF", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:021BF204-4241,-4C41-8F59-593ED61743DF:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:021BF204-4241-4C41-8F59-593ED61743DF:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:57936B90-F736-49DF-90BA-74ED9D908149 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "5689EEB6-FCF1-4CC7-9435-5FCCA56D8276", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:06107CC2-63F0-4466-8497-8FD5EA8F0376
,[ThaliCore] Session.session(_:peer:didChange:) peer:06107CC2-63F0-4466-8497-8FD5EA8F0376 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "5689EEB6-FCF1-4CC7-9435-5FCCA56D8276", generation: 0)
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 06:41:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 ,06:41:21 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-21 06:41:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:5689EEB6-FCF1-4CC7-9435-5,FCCA56D8276
2017-07-21 06:41:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
,[ThaliCore] BrowserManager.disconnect peer:B4D260E1-1E5D-426D-8AB0-42B7621CD7F5
[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:55422
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:B4D260E1-1E5D-426D-8AB0-42B7621CD7F5:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:B4D260E1-1E5D-426D-8AB0-42B7621CD7F5:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "B4D260E1-1E5D-426D-8AB0-42B7621CD7F5", generation: 0)
,[ThaliCore] BrowserManager.disconnect peer:1DEBA3A8-6191-44CA-9535-55D68D86F143
[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:55428
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:1DEBA3A8-6191-44CA-9535-55D68D86F143:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:1DEBA3A8-6191-44CA-9535-55D68D86F143:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "1DEBA3A8-6191-44CA-9535-55D68D86F143", generation: 0)
,2017-07-21 06:41:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 06:41:21 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 06:41:21 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 06:41:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:41:21 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:41:21 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:41:21 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:41:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:41:21 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-21 06:41:21 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"oe06LKGaP3EEMtf2ZAW9cFmh35IiifSE","error":"Session disconnected","portNumber":null}'
,2017-07-21 06:41:21 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'oe06LKGaP3EEMtf2ZAW9cFmh35IiifSE', error: 'Session disconnected', listeningPort: '%s''
,2017-07-21 06:41:21 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"K2JUTk2Cs9OQVkwFDkZs9z66z6I0bnZo","error":"Session disconnected","portNumber":null}'
,2017-07-21 06:41:21 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'K2JUTk2Cs9OQVkwFDkZs9z66z6I0bnZo', error: 'Session disconnected', listeningPort: '%s''
,2017-07-21 06:41:21 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"B4D260E1-1E5D-426D-8AB0-42B7621CD7F5","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-21 06:41:21 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 06:41:21 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"B4D260E1-1E5D-426D-8AB0-42B7621CD7F5","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 06:41:21 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 06:41:21 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"1DEBA3A8-6191-44CA-9535-55D68D86F143","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-21 06:41:21 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 06:41:21 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"1DEBA3A8-6191-44CA-9535-55D68D86F143","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 06:41:21 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 06:41:21 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Session disconnected''
,[ThaliCore] Session.deinit peer:06107CC2-63F0-4466-8497-8FD5EA8F0376
[ThaliCore] Session.deinit peer:B4D260E1-1E5D-426D-8AB0-42B7621CD7F5:0
[ThaliCore] BrowserRelay.deinit
[ThaliCore] Session.deinit peer:1DEBA3A8-6191-44CA-9535-55D68D86F143:0
[ThaliCor,e] BrowserRelay.deinit
,# #startListeningForAdvertisements should fail if start not called
,ok 223 specific error should be returned
,# teardown
,ok 224 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 06:41:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:41:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 06:41:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:41:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:41:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 06:41:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 06:41:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:41:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:41:22 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:41:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:41:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:41:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# #startUpdateAdvertisingAndListening should fail if start not called
,ok 225 specific error should be returned
,# teardown
,[ThaliCore] Session.session(_:peer:didChange:) peer:021BF204-4241-4C41-8F59-593ED61743DF:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:02,1BF204-4241-4C41-8F59-593ED61743DF:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "021BF204-4241-4C41-8F59-593ED61743DF", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:021BF204,-4241-4C41-8F59-593ED61743DF error: startListeningNotActive
2017-07-21 06:41:22 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"q1ZeC7VMXtHNPp7AcU15mCfikWfWahaf","error":"startListeningForAdvertisements is not active","portNumber":n,ull}'
2017-07-21 06:41:22 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"021BF204-4241-4C41-8F59-593ED61743DF","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 06:41:22 - DEBUG th,a,liMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-21 06:41:22 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"021BF204-4241-4C41-8F59-593E,D61743DF","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-21 06:41:22 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Session.deinit peer:021BF204-4241-4C41-8F59-593ED61743DF:0
[ThaliCore] BrowserRelay.deinit
,ok 226 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:41:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:23 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 06:41:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-07-21 06:41:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 06:41:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 06:41:23 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:41:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 06:41:23 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 06:41:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:41:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:41:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #stopListeningForAdvertisements many times
,2017-07-21 06:41:23 - DEBUG thaliMobileNativeWrapper: 'listening 55442'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 06:41:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:41:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 227 no errors
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 06:41:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:41:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 228 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:41:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:41:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
,2017-07-21 06:41:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 06:41:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 229 must be stopped
[ThaliCore] BrowserManager.stopListenin,gForAdvertisements()
2017-07-21 06:41:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate ,(was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:41:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:23 - INFO thaliM,obile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:41:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 06:41:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 06:41:23 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:41:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:41:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:41:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:41:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:41:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #startListeningForAdvertisements many times
,2017-07-21 06:41:23 - DEBUG thaliMobileNativeWrapper: 'listening 55443'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:CC3D793A-1F97-47FF-B26F-28639FD4D28D
[ThaliCore] Browser.startListening
,2017-07-21 06:41:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 06:41:23 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 06:41:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 230 no errors
[ThaliCore] BrowserManager.startListeningForAdvertisements
2017-07-21 06:41:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 06:41:23 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 06:41:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 231 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:41:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 06:41:24 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:41:24 - INFO ,thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 06:41:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisi,ngStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 06:41:24 - DEBUG makeIntoCloseAllServer: 'closeAll called, ,on server'
ok 232 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:41:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 ,06:41:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:41:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryA,ctive":false,"advertisingActive":false}'
2017-07-21 06:41:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:41:24 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 06:41:24 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 06:41:24 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:41:24 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:41:24 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:41:24 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:41:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:41:24 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-07-21 06:41:24 - DEBUG thaliMobileNativeWrapper: 'listening 55444'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "21337E5D-2359-43F2-AC3A-F64AD61A66B5", generation: 0)
[ThaliCore] Advertiser.startA,dvertising with peerID:21337E5D-2359-43F2-AC3A-F64AD61A66B5
2017-07-21 06:41:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 06:41:24 - INFO thaliMobile: 'Receive,d state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:4,1:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 233 no errors
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "21337E5D-2359-43F2-AC3A-F64AD61A66B5", ge,n,eration: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:21337E5D-2359-43F2-AC3A-F64AD61A66B5
2017-07-21 06:41:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 06:41:24 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":nu,ll,"networkType":null}})'
2017-07-21 06:41:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 234 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:21337E5D-2359-43F2-AC3A-F64AD61A66B5
[ThaliCore] Advertiser.stopAdvertising() peerID:21337E5D-2359-43F2-AC3A-F64AD61A66B5
2017-07-21 06:41:24 - DEBUG thaliMo,bileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stop,ListeningForAdvertisements()
2017-07-21 06:41:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
2017-07-21 06:41:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 235 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:41:24 - DEBUG thaliMobileNativeWrapper: ',d,iscoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
201,7-07-21 06:41:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:41:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:41:24 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 06:41:24 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 06:41:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:41:24 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:41:24 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:41:24 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:41:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:41:24 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #stopAdvertisingAndListening many times
,2017-07-21 06:41:25 - DEBUG thaliMobileNativeWrapper: 'listening 55447'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:41:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingAct,ive":false}'
2017-07-21 06:41:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 236 no errors
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:41:25 - DEBUG thaliMobileNativeWrapper: 'discover,yAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 237 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:41:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:41:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 06:41:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 06:41:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 238 must be stopped
[ThaliCore] BrowserManager.stopLi,steningForAdvertisements()
2017-07-21 06:41:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingState,U,pdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:41:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:26 - INFO ,thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:41:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 06:41:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 06:41:26 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:41:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:41:26 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:41:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:41:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:41:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can get the network status before starting
,ok 239 network status should have certain non-empty properties
,# teardown
,ok 240 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:41:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:26 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:41:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 06:41:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:41:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 06:41:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 06:41:26 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:41:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:41:26 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:41:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:41:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:41:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# error returned with bad router
,2017-07-21 06:41:26 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a string'
,ok 241 specific error expected
,# teardown
,ok 242 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:41:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:26 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:41:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 06:41:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:41:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 06:41:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 06:41:26 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:41:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 06:41:26 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-07-21 06:41:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 06:41:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 06:41:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# all services are started when we call start
,2017-07-21 06:41:26 - DEBUG thaliMobileNativeWrapper: 'listening 55448'
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:63BCA3AB-BE1F-45B8-8288-940034D5140E
,[ThaliCore] Browser.startListening
,2017-07-21 06:41:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 06:41:26 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 06:41:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "5ABC551C-8617-4C32-849E-EB4DCEA63779", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:5ABC551C-8617-4C32-849E-EB4DCEA63779
,2017-07-21 06:41:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 06:41:26 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 06:41:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 243 all connection succeed
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:5ABC551C-8617-4C32-849E-EB4DCEA63779
,2017-07-21 06:41:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 06:41:26 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 06:41:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 06:41:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:41:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:41:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 244 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 06:41:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:41:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 06:41:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:41:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:41:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 06:41:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 06:41:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:41:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:41:26 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:41:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:41:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:41:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# TCP Servers Manager should be null when we call start on iOS
,2017-07-21 06:41:27 - DEBUG thaliMobileNativeWrapper: 'listening 55451'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:FCC0AD62-33C4-452B-A160-D37C46A16497
[ThaliCore] Browser.st,artListening
2017-07-21 06:41:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 06:41:27 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:41:27 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "1BA17480-AFEC-4760-BA3E-ACF2C85D77B2", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID,:,1BA17480-AFEC-4760-BA3E-ACF2C85D77B2
2017-07-21 06:41:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 06:41:27 - INFO thaliMobile: 'Received state ({"discoveryActi,ve":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:41:27 - INFO thaliMobile: ,'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 245 TCP Servers Manager doesn't exists
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:1BA17480-AFEC-4760-BA3E-ACF2C85D77B2
,2017-07-21 06:41:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 06:41:27 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:41:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 06:41:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:41:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 06:41:27 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 246 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 06:41:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:41:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:27 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:41:27 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 06:41:27 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 06:41:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:41:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:41:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:41:27 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:41:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:41:27 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# all services are stopped when we call stop
,2017-07-21 06:41:27 - DEBUG thaliMobileNativeWrapper: 'listening 55453'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:8802591D-712E-49E6-A96E-7E80D02EBACE
[ThaliCore] Browser.startListening
2017-07-21 06:41:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 06:41:27 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:41:27 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "5EDF3819-0B74-4D90-9853-4B995C10A2A5", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID,:,5EDF3819-0B74-4D90-9853-4B995C10A2A5
2017-07-21 06:41:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 06:41:27 - INFO thaliMobile: 'Received state ({"discoveryActi,ve":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:41:27 - INFO thaliMobile: ,'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:5EDF3819-0B74-4D90-9853-4B995C10A2A5
2017-07-21 06:41:27 - DEBUG thaliMobileNativeWrap,per: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 06:41:27 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"lis,tening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:41:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 06:41:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
2017-07-21 06:41:27 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 247 is stopped after calling stop
,ok 248 connection should fail after stopping
,# teardown
,ok 249 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 06:41:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:41:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 06:41:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:41:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:41:27 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 06:41:27 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 06:41:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:41:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:41:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:41:27 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:41:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:41:27 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateConnection is properly hooked up
,2017-07-21 06:41:28 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateConnection is properly hooked up''
,# teardown
,ok 250 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 06:41:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:41:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 06:41:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:41:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:41:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 06:41:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 06:41:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:41:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:41:28 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:41:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:41:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:41:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateConnection is return error if we get called on iOS
,ok 251 error description matches
,# teardown
,ok 252 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:41:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 06:41:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-07-21 06:41:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 06:41:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 06:41:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:41:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 06:41:28 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 06:41:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 06:41:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 06:41:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is properly hooked up
,2017-07-21 06:41:29 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateListener is properly hooked up''
,# teardown
,ok 253 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:41:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:29 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:41:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-21 06:41:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:41:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 06:41:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 06:41:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:41:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 06:41:29 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 06:41:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 06:41:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 06:41:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is return error if we get called on iOS
,ok 254 error description matches
,# teardown
,ok 255 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:41:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:29 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:41:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-21 06:41:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:41:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 06:41:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 06:41:29 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:41:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 06:41:29 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 06:41:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 06:41:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 06:41:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure we actually call kill connections properly
,ok 256 IMPLEMENT ME!!!!!!
,# teardown
,ok 257 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:41:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:30 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:41:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-21 06:41:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:41:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 06:41:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 06:41:30 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:41:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 06:41:30 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 06:41:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 06:41:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 06:41:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
,2017-07-21 06:41:30 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''
,# teardown
,ok 258 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:41:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:30 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:41:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-21 06:41:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:41:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 06:41:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 06:41:30 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:41:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 06:41:30 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 06:41:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 06:41:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 06:41:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager
,2017-07-21 06:41:30 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''
,# teardown
,ok 259 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:41:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 06:41:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:41:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 06:41:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 06:41:30 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:41:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 06:41:30 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 06:41:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 06:41:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 06:41:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from multiConnectConnection
,2017-07-21 06:41:31 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 260 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:41:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:31 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 06:41:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:41:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 06:41:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 06:41:31 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:41:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 06:41:31 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 06:41:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 06:41:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 06:41:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection
,2017-07-21 06:41:31 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 261 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:41:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 06:41:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-07-21 06:41:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 06:41:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 06:41:31 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:41:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 06:41:31 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 06:41:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 06:41:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 06:41:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved
,ok 262 NOT IMPLEMENTED # SKIP
,# teardown
,ok 263 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:41:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 06:41:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-07-21 06:41:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 06:41:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 06:41:31 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:41:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 06:41:31 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 06:41:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 06:41:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 06:41:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure bad PSK connections fail
,2017-07-21 06:41:31 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure bad PSK connections fail''
,# teardown
,ok 264 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:41:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:32 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:41:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 06:41:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:41:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 06:41:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 06:41:32 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:41:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 06:41:32 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-07-21 06:41:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 06:41:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 06:41:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peer changes handled from a queue
,2017-07-21 06:41:32 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer changes handled from a queue''
,# teardown
,ok 265 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:41:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:32 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:41:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 06:41:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:41:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 06:41:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 06:41:32 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:41:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 06:41:32 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 06:41:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 06:41:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 06:41:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# relaying discoveryAdvertisingStateUpdateNonTCP
,2017-07-21 06:41:32 - DEBUG CoordinatedClient: 'test was skipped, name: 'relaying discoveryAdvertisingStateUpdateNonTCP''
,# teardown
,ok 266 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:41:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:41:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-21 06:41:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:41:33 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 06:41:33 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 06:41:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:41:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 06:41:33 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-07-21 06:41:33 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 06:41:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 06:41:33 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received
,2017-07-21 06:41:33 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''
,# teardown
,ok 267 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:41:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:33 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:41:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 06:41:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:41:33 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 06:41:33 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 06:41:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:41:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 06:41:33 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 06:41:33 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 06:41:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 06:41:33 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# we successfully receive and replay discoveryAdvertisingStateUpdate
,2017-07-21 06:41:33 - DEBUG thaliMobileNativeWrapper: 'listening 55456'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:1650A3A3-00FD-40B8-A24C-AAFE6570A9ED
[ThaliCore] Browser.st,artListening
2017-07-21 06:41:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 06:41:33 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:41:33 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
ok 268 discoveryActive matches
ok 269 advertisingActive matches
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:41:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonT,C,P: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 06:41:33 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-21 06:41:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 06:41:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21, 06:41:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 270 discoveryActive matches
ok 271 advertisingActive matches
2017-07-21 06:41:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 06:41:33 - DEBUG thaliMobileNativeWrapper: 'listening 55457'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "DBCD31F7-060C-40BE-BCEB-B3C02D223C05", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:DBCD31F7-060C-40BE-BCEB-B3C02D223C05
,2017-07-21 06:41:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 06:41:33 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:41:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 272 discoveryActive matches
ok 273 advertisingActive matches
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:DBCD31F7-060C-40BE-BCEB-B3C02D223C05
,2017-07-21 06:41:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,ok 274 discoveryActive matches
,ok 275 advertisingActive matches
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:41:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06,:41:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:41:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 06:41:33 - DEBUG thaliMobileNativeWrapper: 'listening 55459'
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:41:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:34 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:41:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
,2017-07-21 06:41:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 06:41:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 276 must be stopped
[ThaliCore] BrowserManager.stopListenin,gForAdvertisements()
2017-07-21 06:41:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate ,(was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:41:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:34 - INFO thaliM,obile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:41:34 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 06:41:34 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 06:41:34 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:41:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:41:34 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:41:34 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:41:34 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:41:34 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS
,2017-07-21 06:41:34 - DEBUG thaliMobileNativeWrapper: 'listening 55460'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:9A39A71B-2C7A-4388-8F92-43B10570D125
[ThaliCore] Browser.st,artListening
2017-07-21 06:41:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 06:41:34 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:41:34 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "92269F1E-5F98-4DF6-91E3-B78B83019B41", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID,:,92269F1E-5F98-4DF6-91E3-B78B83019B41
2017-07-21 06:41:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 06:41:34 - INFO thaliMobile: 'Received state ({"discoveryActi,ve":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:41:34 - INFO thaliMobile: ,'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B4D260E1-1E5D-426D-8AB0-42B7621CD7F5:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B4D260E1-1E5D-426D-8AB0-42B7621CD7F5", generation: 0)
,2017-07-21 06:41:35 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"B4D260E1-1E5D-426D-8AB0-42B7621CD7F5","generation":0}]'
,2017-07-21 06:41:35 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"B4D260E1-1E5D-426D-8AB0-42B7621CD7F5","generation":0}'
,2017-07-21 06:41:35 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"B4D260E1-1E5D-426D-8AB0-42B7621CD7F5","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 06:41:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"B4D260E1-1E5D-426D-8AB0-42B7621CD7F5","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 277 portNumber equal null
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:92269F1E-5F98-4DF6-91E3-B78B83019B41:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "92269F1E-5F98-4DF6-91E3-B78B83019B41", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:848C26D1-5A2F-494E-B34B-2D176DF42AF7:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "848C26D1-5A2F-494E-B34B-2D176DF42AF7", generation: 0)
2017-07-21 06:41:35 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"848C26D1-5A2F-494E-B34B-2D176DF42AF7","generation":0}]'
2017-07-21 06:41:35 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"848C26D1-5A2F-494E-B34B-2D176DF42AF7","generation":0}'
,2017-07-21 06:41:35 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"848C26D1-5A2F-494E-B34B-2D176DF42AF7","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-21 06:41:35 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"848C26D1-5A2F-494E-B34B-2D176DF42AF7","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:353DCE66-3E1C-4FC6-910A-7333D0DEDF6E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "353DCE66-3E1C-4FC6-910A-7333D0DEDF6E", generation: 0)
2017-07-21 06:41:36 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"353DCE66-3E1C-4FC6-910A-7333D0DEDF6E","generation":0}]'
2017-07-21 06:41:36 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"353DCE66-3E1C-4FC6-910A-7333D0DEDF6E","generation":0}'
,2017-07-21 06:41:36 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"353DCE66-3E1C-4FC6-910A-7333D0DEDF6E","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-21 06:41:36 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"353DCE66-3E1C-4FC6-910A-7333D0DEDF6E","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:92269F1E-5F98-4DF6-91E3-B78B83019B41
2017-07-21 06:41:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-07-21 06:41:36 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:41:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stop,Listening()
,2017-07-21 06:41:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
2017-07-21 06:41:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 278 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:41:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdate,NonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:41:36 - DEBUG thali,MobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 06:41:36 - DEBUG ,t,haliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 06:41:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 06:41:36 - DEBUG thaliMobileNativeWrapper:, 'Method multiConnectResolved registered to native'
,2017-07-21 06:41:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:41:36 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:41:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:41:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:41:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can do HTTP requests between peers
,2017-07-21 06:41:36 - DEBUG CoordinatedClient: 'test was skipped, name: 'can do HTTP requests between peers''
,# teardown
,ok 279 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:41:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:36 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:41:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-21 06:41:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:41:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 06:41:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 06:41:36 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:41:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 06:41:36 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 06:41:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 06:41:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 06:41:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can still do HTTP requests between peers with coordinator
,2017-07-21 06:41:36 - DEBUG CoordinatedClient: 'test was skipped, name: 'can still do HTTP requests between peers with coordinator''
,# teardown
,ok 280 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:41:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:36 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:41:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 06:41:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:41:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 06:41:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 06:41:36 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:41:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 06:41:36 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:41:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:41:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:41:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calls correct starts when network changes
,2017-07-21 06:41:36 - DEBUG CoordinatedClient: 'test was skipped, name: 'calls correct starts when network changes''
,# teardown
,ok 281 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:41:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:37 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:41:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-21 06:41:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:41:37 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 06:41:37 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 06:41:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:41:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:41:37 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:41:37 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:41:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:41:37 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# test to coordinate connection cut
,# teardown
,ok 282 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:41:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:37 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:41:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 06:41:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:41:37 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 06:41:37 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 06:41:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:41:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 06:41:37 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 06:41:37 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 06:41:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 06:41:37 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can do HTTP requests after connections are cut
,2017-07-21 06:41:37 - DEBUG thaliMobileNativeWrapper: 'listening 55462'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:956657AF-9654-4C83-928E-E4B8E61A74E6
,[ThaliCore] Browser.startListening
,2017-07-21 06:41:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 06:41:37 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:41:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "82989E42-3B69-4258-A0E7-2C851A40B621", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:82989E42-3B69-4258-A0E7-2C851A40B621
,2017-07-21 06:41:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 06:41:37 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:41:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B4D260E1-1E5D-426D-8AB0-42B7621CD7F5:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B4D260E1-1E5D-426D-8AB0-42B7621CD7F5", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:353DCE66-3E1C-4FC6-910A-7333D0DEDF6E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "353DCE66-3E1C-4FC6-910A-7333D0DEDF6E", generation: 0)
,2017-07-21 06:41:37 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"B4D260E1-1E5D-426D-8AB0-42B7621CD7F5","generation":0}]'
,2017-07-21 06:41:37 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"B4D260E1-1E5D-426D-8AB0-42B7621CD7F5","generation":0}'
2017-07-21 06:41:37 - DEBUG thaliMobileNativeWrapper: 'Rece,ived peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"353DCE66-3E1C-4FC6-910A-7333D0DEDF6E","generation":0}]'
,2017-07-21 06:41:37 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"353DCE66-3E1C-4FC6-910A-7333D0DEDF6E","generation":0}'
,2017-07-21 06:41:37 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"B4D260E1-1E5D-426D-8AB0-42B7621CD7F5","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 06:41:37 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"B4D260E1-1E5D-426D-8AB0-42B7621CD7F5","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 06:41:37 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B4D260E1-1E5D-426D-8AB0-42B7621CD7F5 (syncValue: qDWufcCXrNrLv5kBbYDp5Ctr6tfjFBOg)'
,2017-07-21 06:41:37 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B4D260E1-1E5D-426D-8AB0-42B7621CD7F5", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B4D260E1-1E5D-426D-8AB0-42B7621CD7F5", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B4D260E1-1E5D-426D-8AB0-42B7621CD7F5:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
2017-07-21 06:41:38 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"353DCE66-3E1C-4FC6-910A-7333D0DEDF6E","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 06:41:38 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"353DCE66-3E1C-4FC6-910A-7333D0DEDF6E","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FD7FAF55-856C-48D4-87B6-76198D675423:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FD7FAF55-856C-48D4-87B6-76198D675423", generation: 0)
2017-07-21 06:41:39 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"FD7FAF55-856C-48D4-87B6-76198D675423","generation":0}]'
2017-07-21 06:41:39 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"FD7FAF55-856C-48D4-87B6-76198D675423","generation":0}'
,2017-07-21 06:41:39 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"FD7FAF55-856C-48D4-87B6-76198D675423","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 06:41:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"FD7FAF55-856C-48D4-87B6-76198D675423","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 06:41:39 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"FD7FAF55-856C-48D4-87B6-76198D675423","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:964F0DD7-1B92-4F4E-A048-636C8BB301EE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "964F0DD7-1B92-4F4E-A048-636C8BB301EE", generation: 0)
2017-07-21 06:41:39 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"964F0DD7-1B92-4F4E-A048-636C8BB301EE","generation":0}]'
2017-07-21 06:41:39 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"964F0DD7-1B92-4F4E-A048-636C8BB301EE","generation":0}'
,2017-07-21 06:41:39 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"964F0DD7-1B92-4F4E-A048-636C8BB301EE","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-21 06:41:39 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"964F0DD7-1B92-4F4E-A048-636C8BB301EE","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-21 06:41:39 - DEBUG thaliMobileNativeTestUtils: 'We got a pe,er {"peerIdentifier":"964F0DD7-1B92-4F4E-A048-636C8BB301EE","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:82989E42-3B69-4258-A0E7-2C851A40B621:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "82989E42-3B69-4258-A0E7-2C851A40B621", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:B4D260E1-1E5D-426D-8AB0-42B7621CD7F5:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B4,D260E1-1E5D-426D-8AB0-42B7621CD7F5:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "B4D260E1-1E5D-426D-8AB0-42B7621CD7F5", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,4D260E1-1E5D-426D-8AB0-42B7621CD7F5", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B4D260E1-1E5D-426D-8AB0-42B7621CD7F5", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:B4D260E1-1E5D-426D-8AB0-42B7621CD7F5:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:B4D260E1-1E5D-426D-8AB0-42B7621CD7F5:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:353DCE66-3E1C-4FC6-910A-7333D0DEDF6E:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "353DCE66-3E1C-4FC6-910A-7333D0DEDF6E", generation: 0)
2017-07-21 06:41:43 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"353DCE66-3E1C-4FC6-910A-7333D0DEDF6E","generation":0}]'
2017-07-21 06:41:43 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"353DCE66-3E1C-4FC6-910A-7333D0DEDF6E","generation":0}'
,2017-07-21 06:41:43 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"353DCE66-3E1C-4FC6-910A-7333D0DEDF6E","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-21 06:41:43 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"353DCE66-3E1C-4FC6-910A-7333D0DEDF6E","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:B4D260E1-1E5D-426D-8AB0-42B7621CD7F5:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B4,D260E1-1E5D-426D-8AB0-42B7621CD7F5:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "B4D260E1-1E5D-426D-8AB0-42B7621CD7F5", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,4D260E1-1E5D-426D-8AB0-42B7621CD7F5", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B4D260E1-1E5D-426D-8AB0-42B7621CD7F5", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:B4D260E1-1E5D-426D-8AB0-42B7621CD7F5:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:B4D260E1-1E5D-426D-8AB0-42B7621CD7F5:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:AE28369A-9858-4880-839F-FA3276B0D04B
[ThaliCore] Advertiser: session connected Peer(uuid: "82989E42-3B69-4258-A0E7-2C851A40B621", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:AE28369A-9858-4880-839F-FA3276B0D04B state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:AE28369A-9858-4880-839F-FA3276B0D04B
,[ThaliCore] Session.session(_:peer:didChange:) peer:B4D260E1-1E5D-426D-8AB0-42B7621CD7F5:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B4,D260E1-1E5D-426D-8AB0-42B7621CD7F5:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "B4D260E1-1E5D-426D-8AB0-42B7621CD7F5", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,4D260E1-1E5D-426D-8AB0-42B7621CD7F5", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B4D260E1-1E5D-426D-8AB0-42B7621CD7F5", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:B4D260E1-1E5D-426D-8AB0-42B7621CD7F5:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:B4D260E1-1E5D-426D-8AB0-42B7621CD7F5:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:AE28369A-9858-4880-839F-FA3276B0D04B state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:AE28369A-9858-4880-839F-FA3276B0D04B
[ThaliCore] Session.startOutputStream(with:) peer:AE28369A-9858-4880-839F-FA3276B0D04B
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:17 [1, 3, 7, 17]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:B4D260E1-1E5D-426D-8AB0-42B7621CD7F5:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B4,D260E1-1E5D-426D-8AB0-42B7621CD7F5:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "B4D260E1-1E5D-426D-8AB0-42B7621CD7F5", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:B4D260E1,-1E5D-426D-8AB0-42B7621CD7F5 error: max retries exceeded
2017-07-21 06:41:48 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"qDWufcCXrNrLv5kBbYDp5Ctr6tfjFBOg","error":"Connection could not be established","portNumber":null}'
2017-0,7-21 06:41:48 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'qDWufcCXrNrLv5kBbYDp5Ctr6tfjFBOg', error: 'Connection could not be established', listeningPort: '%s''
2017-07-21 06:41:48 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"B4D260E1-1E5D-426D-8AB0-42B7621CD7F5","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 06:41:48 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"B4D260E1-1E5D-426D-8AB0-42B7621CD7F5","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-21 06:41:48 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"B4D260E1-1E5D-426D-8AB0-42B7621CD7F5","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-21 06:41:48 - DEBUG thali,Mobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"B4D260E1-1E5D-426D-8AB0-42B7621CD7F5","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-21 06:41:48 - DEBUG thaliMobileNati,veWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"B4D260E1-1E5D-426D-8AB0-42B7621CD7F5","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
2017-07-21 06:41:48 - DEBUG thaliMobile: 'Emitting peerAvailabilityChang,ed from handleRecreatedPeer {"peerIdentifier":"B4D260E1-1E5D-426D-8AB0-42B7621CD7F5","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-21 06:41:48 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentif,i,er":"B4D260E1-1E5D-426D-8AB0-42B7621CD7F5","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
2017-07-21 06:41:48 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-21 06:41:48 -, DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for FD7FAF55-856C-48D4-87B6-76198D675423 (syncValue: FoEj5CwOrykrhkHziOU05tNQrmjwxjU4)'
2017-07-21 06:41:48 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserMana,ger.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "FD7FAF55-856C-48D4-87B6-76198D675423", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FD7FAF55-856C-48D4-87B6-7,6198D675423", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FD7FAF55-856C-48D4-87B6-76198D675423:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with,:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:B4D260E1-1E5D-426D-8AB0-42B7621CD7F5:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:FD7FAF55-856C-48D4-87B6-76198D675423:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:FD7FAF55-856C-48D4-87B6-76198D675423:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:FD7FAF55-856C-48D4-87B6-76198D675423:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "FD7FAF55-856C-48D4-87B6-76198D675423", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:55475
2017-07-21 06:41:51 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"FoEj5CwOrykrhkHziOU05tNQrmjwxjU4","error":null,"portNumber":55475}'
2017-07-21 06:41:51 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'FoEj5CwOrykrhkHziOU05tNQrmjwxjU4', error: 'null', listeningPort: '55475''
,2017-07-21 06:41:51 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) pee,r:FD7FAF55-856C-48D4-87B6-76198D675423:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FD7FAF55-856C-48D4-87B6-76198D675423:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:18 [1, 3, 7, 17, 18]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-21 06:41:51 - DEBUG thaliMobileNativeTestUtils: 'Test timeout reached. Restarting test.'
,2017-07-21 06:41:51 - DEBUG testUtils: 'Got response data'
2017-07-21 06:41:51 - DEBUG testUtils: 'Got end'
ok 283 response body should match testData
ok 284 must be started
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:158AC3FC-E7FF-48C5-8A09-09E89B48A8FF
[ThaliCore] Advertiser: session connected Peer(uuid: "82989E42-3B69-4258-A0E7-2C851A40B621", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:158AC3FC-E7FF-48C5-8A09-09E89B48A8FF state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:B4D260E1-1E5D-426D-8AB0-42B7621CD7F5:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "B4D260E1-1E5D-426D-8AB0-42B7621CD7F5", generation: 0)
2017-07-21 06:41:58 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"B4D260E1-1E5D-426D-8AB0-42B7621CD7F5","generation":0}]'
2017-07-21 06:41:58 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"B4D260E1-1E5D-426D-8AB0-42B7621CD7F5","generation":0}'
,2017-07-21 06:41:58 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"B4D260E1-1E5D-426D-8AB0-42B7621CD7F5","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-21 06:41:58 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"B4D260E1-1E5D-426D-8AB0-42B7621CD7F5","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:158AC3FC-E7FF-48C5-8A09-09E89B48A8FF
,[ThaliCore] Session.session(_:peer:didChange:) peer:158AC3FC-E7FF-48C5-8A09-09E89B48A8FF state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:158AC3FC-E7FF-48C5-8A09-09E89B48A8FF
[ThaliCore] Session.startOutputStream(with:) peer:158AC3FC-E7FF-48C5-8A09-09E89B48A8FF
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:19 [1, 3, 7, 17, 18, 19]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:82989E42-3B69-4258-A0E7-2C851A40B621
,2017-07-21 06:42:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 06:42:00 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 06:42:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 06:42:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21, 06:42:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:42:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 285 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote pe,er" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSoc,ketDisconnectHandler removed virtual socket vsID:17
2017-07-21 06:42:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
[ThaliCore] VirtualSocket.closeStreams() vsID:17
2017-,07-21 06:42:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(E,r,ror Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
2017-07-21 06:42:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":fal,se,"advertisingActive":false}'
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:17
2017-07-21 06:42:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] VirtualSocket.deinit vsID:17 [1, 3, 7, 18, 19]
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDiscon,nectHandler removed virtual socket vsID:19
[ThaliCore] VirtualSocket.closeStreams() vsID:19
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:19
,[ThaliCore] VirtualSocket.deinit vsID:19 [1, 3, 7, 18]
,[ThaliCore] BrowserManager.disconnect peer:FD7FAF55-856C-48D4-87B6-76198D675423
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:55475
,[ThaliCore] VirtualSocket.closeStreams() vsID:18
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[T,haliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket exited RunLoop vsID:18
,[ThaliCore] Session.disconnect() peer:FD7FAF55-856C-48D4-87B6-76198D675423:0
,[ThaliCore] VirtualSocket.closeStreams() vsID:18
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] Session.deinit peer:FD7FAF55-856C-48D4-87B6-76198D675423:0
[ThaliCore] VirtualSocket.deinit vsID:18 [1, 3, 7]
[ThaliCore] TCPListener.deinit
[ThaliCore] BrowserRelay.deinit
,2017-07-21 06:42:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 06:42:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 06:42:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:42:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:42:00 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:42:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:42:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:42:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:158AC3FC-E7FF-48C5-8A09-09E89B48A8FF state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "82989E42-3B69-4258-A0E7-2C851A40B621", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
,[ThaliCore] Session.disconnect() peer:158AC3FC-E7FF-48C5-8A09-09E89B48A8FF
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:AE28369A-9858-4880-839F-FA3276B0D04B state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "82989E42-3B69-4258-A0E7-2C851A40B621", generation: 0)
,[ThaliCore] Session.deinit peer:158AC3FC-E7FF-48C5-8A09-09E89B48A8FF
,# will fail bad PSK connection between peers
,ok 286 FIX ME, PLEASE!!!
,# teardown
,ok 287 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:42:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:42:01 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:42:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 06:42:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:42:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 06:42:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 06:42:01 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:42:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 06:42:01 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 06:42:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 06:42:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 06:42:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We provide notification when a listener dies and we recreate it
,2017-07-21 06:42:01 - DEBUG CoordinatedClient: 'test was skipped, name: 'We provide notification when a listener dies and we recreate it''
,# teardown
,ok 288 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:42:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:42:03 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:42:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 06:42:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:42:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 06:42:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 06:42:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:42:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 06:42:03 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 06:42:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 06:42:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 06:42:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated
,2017-07-21 06:42:03 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated''
,# teardown
,ok 289 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:42:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:42:04 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:42:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 06:42:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:42:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 06:42:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 06:42:04 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:42:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:42:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:42:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:42:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:42:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,ok 290 ThaliMobile should be stopped
,# #startListeningForAdvertisements should fail if start not called
,ok 291 specific error should be returned
,# teardown
,2017-07-21 06:42:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"848C26D1-5A2F-494E-B34B-2D176DF42AF7","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-21, 06:42:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"FD7FAF55-856C-48D4-87B6-76198D675423","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-21 06:42:05 ,- DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"964F0DD7-1B92-4F4E-A048-636C8BB301EE","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
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
,2017-07-21 06:42:05 - DEBUG thaliMobileNativeWrapper: 'listening 55478'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:42:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"ad,vertisingActive":false}'
ok 299 error should be null
ok 300 error should be null
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 06:42:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
ok 301 error should be null
ok 302 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:42:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:42:05 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:42:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:42:06 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 06:42:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 303 error should be null
ok 304 error should be null
,# setup
,ok 305 ThaliMobile should be stopped
,# should be able to call #startListeningForAdvertisements many times
,2017-07-21 06:42:06 - DEBUG thaliMobileNativeWrapper: 'listening 55479'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:1B12265E-4087-46C0-BC46-3BDD5E743026
[ThaliCore] Browser.st,artListening
2017-07-21 06:42:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
ok 306 error should be null
ok 307 error should be null
[ThaliCore] BrowserManager.startListe,ningForAdvertisements
2017-07-21 06:42:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
ok 308 error should be null
ok 309 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:42:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 06:42:06 - INFO thaliMobile: 'Received state ({"d,iscoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
2017-07-21 06:42:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateU,pdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 06:42:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advert,isingActive":false}'
,2017-07-21 06:42:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:42:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 310 error should be null
,ok 311 error should be null
,# setup
,ok 312 ThaliMobile should be stopped
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-07-21 06:42:07 - DEBUG thaliMobileNativeWrapper: 'listening 55480'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "EB989EDE-D8E7-4B7A-82C1-962C24924AC2", generation: 0)
[ThaliCore] Advertiser.startA,dvertising with peerID:EB989EDE-D8E7-4B7A-82C1-962C24924AC2
2017-07-21 06:42:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 313 error should be null
ok 314 error should, be null
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "EB989EDE-D8E7-4B7A-82C1-962C24924AC2", generation: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:EB989EDE-D8E7-4B7A-82C1-962C24924AC2
20,17-07-21 06:42:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 315 error should be null
ok 316 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:EB989EDE-D8E7-4B7A-82C1-962C24924AC2
[ThaliCore] Advertiser.stopAdvertising() peerID:EB989EDE-D8E7-4B7A-82C1-962C24924AC2
2017-07-21 06:42:07 - DEBUG thaliMo,bileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:42:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stop,ListeningForAdvertisements()
2017-07-21 06:42:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:42:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
,2017-07-21 06:42:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 317 error should be null
,ok 318 error should be null
,# setup
,ok 319 ThaliMobile should be stopped
,# should be able to call #stopAdvertisingAndListening many times
,2017-07-21 06:42:08 - DEBUG thaliMobileNativeWrapper: 'listening 55483'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:42:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingAct,ive":false}'
ok 320 error should be null
ok 321 error should be null
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:42:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActi,ve":false}'
ok 322 error should be null
,ok 323 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:42:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:42:08 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 06:42:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:42:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
2017-07-21 06:42:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 324 error should be null
ok 325 error should be null
,# setup
,ok 326 ThaliMobile should be stopped
,# #start - Causing native or wifi to fail will cause a promise reject 
,2017-07-21 06:42:08 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a Null'
,ok 327 This should not cause wifi to fail
ok 328 native router should be bad
,# teardown
,ok 329 error should be null
ok 330 error should be null
,# setup
,ok 331 ThaliMobile should be stopped
,# #start should fail if called twice in a row
,2017-07-21 06:42:09 - DEBUG thaliMobileNativeWrapper: 'listening 55484'
ok 332 first call should succeed
ok 333 first call should succeed
ok 334 specific error should be returned
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:42:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:42:10 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 06:42:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:42:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
2017-07-21 06:42:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 335 error should be null
ok 336 error should be null
,# setup
,ok 337 ThaliMobile should be stopped
,# #start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)
,2017-07-21 06:42:10 - DEBUG CoordinatedClient: 'test was skipped, name: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''
,# teardown
,ok 338 error should be null
ok 339 error should be null
,# setup
,ok 340 ThaliMobile should be stopped
,# does not emit duplicate discoveryAdvertisingStateUpdate
,2017-07-21 06:42:10 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not emit duplicate discoveryAdvertisingStateUpdate''
,# teardown
,ok 341 error should be null
ok 342 error should be null
,# setup
,ok 343 ThaliMobile should be stopped
,# does not send duplicate availability changes
,2017-07-21 06:42:11 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"0036f635-449d-4aeb-b264-ddde034cde7f","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 344 should be called once
ok 345 should not have been called more than once
,# teardown
,2017-07-21 06:42:11 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"0036f635-449d-4aeb-b264-ddde034cde7f","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
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
,2017-07-21 06:42:14 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"d9d8a7b0-9474-498c-b95c-ba28d19648db","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 354 peer should be available
,ok 355 cache contains native peer
,2017-07-21 06:42:14 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"d9d8a7b0-9474-498c-b95c-ba28d19648db","connectionType":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
,ok 356 peer should be unavailable
,ok 357 peer has been removed from cache
,# teardown
,ok 358 error should be null
,ok 359 error should be null
,# setup
,ok 360 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer added/removed to/from cache (wifi)
,ok 361 we have not added peer to the cache yet
2017-07-21 06:42:14 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"faf0ec2f-e14f-4e92-b75e-7e56db3d1b89","connectionType":"tcp","peerAvailable":true,"generation":0,",newAddressPort":false}'
ok 362 peer should be available
ok 363 cache contains wifi peer
2017-07-21 06:42:14 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"faf0ec2f-e14f-4e92-b75e-7e56db3d1b89","connectionType":,"tcp","peerAvailable":false,"generation":0,"newAddressPort":null}'
ok 364 peer should be unavailable
ok 365 peer has been removed from cache
,# teardown
,ok 366 error should be null
ok 367 error should be null
,# setup
,ok 368 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored
,2017-07-21 06:42:15 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"6216c6ad-5aaa-4942-a6f5-2718ff851ad1","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 369 first peer is available
2017-07-21 06:42:15 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5387f410-bd03-46fc-9abf-c5bed0b95508","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":,false}'
ok 370 second peer is available
ok 371 first and second peers are different
,# teardown
,2017-07-21 06:42:15 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"6216c6ad-5aaa-4942-a6f5-2718ff851ad1","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-21 06:42:15 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"5387f410-bd03-46fc-9abf-c5bed0b95508","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 372 error should be null
ok 373 error should be null
,# setup
,ok 374 ThaliMobile should be stopped
,# native available - new peer is cached
,ok 375 should not be in cache at start
2017-07-21 06:42:15 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"0b2ad6d2-5584-45ce-9d6b-8ca10c996e54","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddr,essPort":false}'
ok 376 peer is available
,# teardown
,2017-07-21 06:42:15 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"0b2ad6d2-5584-45ce-9d6b-8ca10c996e54","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 377 error should be null
ok 378 error should be null
,# setup
,ok 379 ThaliMobile should be stopped
,# native available - peer with same port and different generation is cached (BLUETOOTH)
,2017-07-21 06:42:15 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with same port and different generation is cached (BLUETOOTH)''
,# teardown
,ok 380 error should be null
ok 381 error should be null
,# setup
,ok 382 ThaliMobile should be stopped
,# native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)
,2017-07-21 06:42:15 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)''
,# teardown
,ok 383 error should be null
ok 384 error should be null
,# setup
,ok 385 ThaliMobile should be stopped
,# native available - peer with greater generation is cached (MPCF)
,2017-07-21 06:42:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"91f8c507-c4fe-4950-b3ac-2613e74ae4d9","connectionType":"MPCF","peerAvailable":true,"generation":2,"newAddressPort":false}'
ok 386 peer should be available
,2017-07-21 06:42:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"91f8c507-c4fe-4950-b3ac-2613e74ae4d9","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
ok 387 peer should be available
ok 388 should store correct generation
,# teardown
,2017-07-21 06:42:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"91f8c507-c4fe-4950-b3ac-2613e74ae4d9","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 389 error should be null
ok 390 error should be null
,# setup
,ok 391 ThaliMobile should be stopped
,# native available - peer with same or older generation is ignored (MPCF)
,2017-07-21 06:42:16 - DEBUG thaliMobileNativeWrapper: 'listening 55485'
2017-07-21 06:42:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"3c582b71-f4f0-40f5-8bc8-46be05a2b8f1","connectionType":"MPCF","peerAvaila,ble":true,"generation":2,"newAddressPort":false}'
ok 392 discovered correct peer
ok 393 got correct generation
,2017-07-21 06:42:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"3c582b71-f4f0-40f5-8bc8-46be05a2b8f1","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
ok 394 discovered corr,ect peer
ok 395 got correct generation
,# teardown
,2017-07-21 06:42:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"3c582b71-f4f0-40f5-8bc8-46be05a2b8f1","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore,] AdvertiserManager.stopAdvertising()
2017-07-21 06:42:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:42:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:42:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpd,ateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:42:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 06:42:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server',
,ok 396 error should be null
ok 397 error should be null
,# setup
,ok 398 ThaliMobile should be stopped
,# native unavailable - new peer is ignored
,2017-07-21 06:42:17 - DEBUG thaliMobileNativeWrapper: 'listening 55486'
,2017-07-21 06:42:17 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"81c90d90-9000-4fab-a385-aef4785af88e","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 399 discovered available peer
ok 400 peer is available
,# teardown
,2017-07-21 06:42:17 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"81c90d90-9000-4fab-a385-aef4785af88e","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:42:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:42:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:42:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpd,ateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:42:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 06:42:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server',
,ok 401 error should be null
ok 402 error should be null
,# setup
,ok 403 ThaliMobile should be stopped
,# native unavailable - cached peer is removed
,2017-07-21 06:42:17 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7bdf18aa-b0c0-4d13-b98d-d306c390dbc1","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 404 peer should be available
2017-07-21 06:42:17 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7bdf18aa-b0c0-4d13-b98d-d306c390dbc1","connectionType":"MPCF","peerAvailable":false,"generation":0,"newAddressPor,t":null}'
ok 405 peer should be unavailable
ok 406 should be removed from cache
,# teardown
,ok 407 error should be null
ok 408 error should be null
,# setup
,ok 409 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for wifi peers
,2017-07-21 06:42:18 - DEBUG thaliMobileNativeWrapper: 'listening 55487'
2017-07-21 06:42:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"b33ead00-4ff0-4f11-b095-2fd9564d531f","connectionType":"MPCF","peerAvaila,ble":true,"generation":0,"newAddressPort":false}'
ok 410 first peer is expected to be available
2017-07-21 06:42:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"d4a7432f-c173-48af-9ea0-43d526aea9bd","connectio,nType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 411 second peer is expected to be available
2017-07-21 06:42:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"d4a7432f-c173-,48af-9ea0-43d526aea9bd","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 412 peer became unavailable
ok 413 it was wifi peer
2017-07-21 06:42:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handle,P,eer {"peerIdentifier":"d4a7432f-c173-48af-9ea0-43d526aea9bd","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 414 we found peer again
ok 415 it was wifi peer
2017-07-21 06:42:18 - DEBUG thaliMobile: 'Emitting peerAv,ailabilityChanged from emitPeerUnavailable {"peerIdentifier":"d4a7432f-c173-48af-9ea0-43d526aea9bd","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 416 peer became unavailable
ok 417 it was wifi peer
,# teardown
,2017-07-21 06:42:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"b33ead00-4ff0-4f11-b095-2fd9564d531f","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore,] AdvertiserManager.stopAdvertising()
2017-07-21 06:42:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:42:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:42:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpd,ateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:42:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 06:42:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 418 error should be null
ok 419 error should be null
,# setup
,ok 420 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)
,2017-07-21 06:42:18 - DEBUG CoordinatedClient: 'test was skipped, name: 'networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)''
,# teardown
,ok 421 error should be null
ok 422 error should be null
,# setup
,ok 423 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)
,2017-07-21 06:42:18 - DEBUG thaliMobileNativeWrapper: 'listening 55488'
2017-07-21 06:42:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"a9642b94-73b9-4930-b0a0-e605f4db2a6d","connectionType":"MPCF","peerAvaila,ble":true,"generation":0,"newAddressPort":false}'
ok 424 first peer is expected to be available
2017-07-21 06:42:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"e8398b6d-355b-48ac-be1a-40fdf013c402","connectio,nType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 425 second peer is expected to be available
,2017-07-21 06:42:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"a9642b94-73b9-4930-b0a0-e605f4db2a6d","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 426 pee,r became unavailable
2017-07-21 06:42:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"e8398b6d-355b-48ac-be1a-40fdf013c402","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPor,t":null}'
ok 427 peer became unavailable
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:42:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:42:18 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:42:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 06:42:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 06:42:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 428 error should be null
ok 429 error should be null
,# setup
,ok 430 ThaliMobile should be stopped
,# multiconnect failure - new peer is ignored (MPCF)
,2017-07-21 06:42:19 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - new peer is ignored (MPCF)''
,# teardown
,ok 431 error should be null
ok 432 error should be null
,# setup
,ok 433 ThaliMobile should be stopped
,# multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)
,2017-07-21 06:42:19 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''
,# teardown
,ok 434 error should be null
ok 435 error should be null
,# setup
,ok 436 ThaliMobile should be stopped
,# newAddressPort field (TCP_NATIVE)
,2017-07-21 06:42:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"740a693e-0e04-4c13-882a-e50370c276bb","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 437 peer discovered first time does not have new address
2017-07-21 06:42:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"740a693e-0e04-4c13-882a-e50370c276bb","connectionType":"tcp","peerAvailable":true,"ge,neration":20,"newAddressPort":false}'
ok 438 address has not been changed
2017-07-21 06:42:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"740a693e-0e04-4c13-882a-e50370c276bb","connectionType":"tcp","peerAvai,lable":true,"generation":20,"newAddressPort":true}'
ok 439 new port handled correctly
2017-07-21 06:42:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"740a693e-0e04-4c13-882a-e50370c276bb","connectionType":"tc,p","peerAvailable":true,"generation":20,"newAddressPort":true}'
ok 440 new host handled correctly
2017-07-21 06:42:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"740a693e-0e04-4c13-882a-e50370c276bb","connec,t,ionType":"tcp","peerAvailable":false,"generation":20,"newAddressPort":null}'
ok 441 newAddressPort is null for unavailable peers
,# teardown
,ok 442 error should be null
ok 443 error should be null
,# setup
,ok 444 ThaliMobile should be stopped
,# newAddressPort field (BLUETOOTH)
,2017-07-21 06:42:19 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort field (BLUETOOTH)''
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
,2017-07-21 06:42:20 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)''
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
,2017-07-21 06:42:21 - DEBUG CoordinatedClient: 'test was skipped, name: '#getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)''
,# teardown
,ok 459 error should be null
,ok 460 error should be null
,# setup
,ok 461 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)
,2017-07-21 06:42:21 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 462 contains expected properties
ok 463 the same hostAddress
ok 464 the same portNumber
,# teardown
,2017-07-21 06:42:21 - DEBUG thaliMobileNativeTestUtils: 'Test timeout reached. Restarting test.'
,2017-07-21 06:42:21 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 465 error should be null
ok 466 error should be null
,# setup
,ok 467 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached wifi peer
,2017-07-21 06:42:21 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 468 contains expected properties
ok 469 the same hostAddress
ok 470 the same portNumber
,# teardown
,2017-07-21 06:42:21 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 471 error should be null
ok 472 error should be null
,# setup
,ok 473 ThaliMobile should be stopped
,# #disconnect fails on wifi peers
,2017-07-21 06:42:22 - DEBUG thaliMobileNativeWrapper: 'listening 55489'
2017-07-21 06:42:22 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"cea57a17-48b9-4304-b8e3-9c7208a99da2","connectionType":"tcp","peerAvailab,le":true,"generation":0,"newAddressPort":false}'
ok 474 Got specific error message
,# teardown
,2017-07-21 06:42:22 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"cea57a17-48b9-4304-b8e3-9c7208a99da2","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:42:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:42:22 - INFO thaliMobile: 'Filtered out discoveryAdverti,singStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:42:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:42:22 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 06:42:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 475 error should be null
ok 476 error should be null
,# setup
,ok 477 ThaliMobile should be stopped
,# #disconnect delegates native peers to the native wrapper
,2017-07-21 06:42:22 - DEBUG thaliMobileNativeWrapper: 'listening 55490'
2017-07-21 06:42:22 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"83af9ec6-ae98-4c3a-bdf1-0ab60bb6e56a","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
[ThaliCore] BrowserManager.disconnect peer:83af9ec6-ae98-4c3a-bdf1-0ab60bb6e56a
,ok 478 native wrapper `disconnect` called once
ok 479 native wrapper `disconnect` called with peer data
,# teardown
,2017-07-21 06:42:22 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"83af9ec6-ae98-4c3a-bdf1-0ab60bb6e56a","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:42:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:42:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:42:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpd,ateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:42:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 06:42:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server',
,ok 480 error should be null
ok 481 error should be null
,# setup
,ok 482 ThaliMobile should be stopped
,# network changes emitted correctly
,2017-07-21 06:42:22 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes emitted correctly''
,# teardown
,ok 483 error should be null
ok 484 error should be null
,# setup
,ok 485 ThaliMobile should be stopped
,# network changes not emitted in started state
,2017-07-21 06:42:23 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes not emitted in started state''
,# teardown
,ok 486 error should be null
ok 487 error should be null
,# setup
,ok 488 ThaliMobile should be stopped
,# network changes not emitted in stopped state
,2017-07-21 06:42:23 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes not emitted in stopped state''
,# teardown
,ok 489 error should be null
,ok 490 error should be null
,# setup
,ok 491 ThaliMobile should be stopped
,# We properly fire peer unavailable and then available when connection fails on Android
,2017-07-21 06:42:23 - DEBUG CoordinatedClient: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on Android''
,# teardown
,ok 492 error should be null
,ok 493 error should be null
,# setup
,ok 494 ThaliMobile should be stopped
,# We properly fire peer unavailable and then available when connection fails on iOS
,2017-07-21 06:42:23 - DEBUG CoordinatedClient: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on iOS''
,# teardown
,ok 495 error should be null
ok 496 error should be null
,# setup
,ok 497 ThaliMobile should be stopped
,# If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen
,2017-07-21 06:42:24 - DEBUG CoordinatedClient: 'test was skipped, name: 'If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen''
,# teardown
,ok 498 error should be null
ok 499 error should be null
,# setup
,ok 500 ThaliMobile should be stopped
,# does not fire duplicate events after peer listener recreation
,2017-07-21 06:42:24 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not fire duplicate events after peer listener recreation''
,# teardown
,ok 501 error should be null
ok 502 error should be null
,# setup
,ok 503 ThaliMobile should be stopped
,# #stop should change peers
,2017-07-21 06:42:24 - DEBUG thaliMobileNativeWrapper: 'listening 55491'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:A3252F84-9672-4D92-9DCC-37E06E493CFB
[ThaliCore] Browser.startListening
2017-07-21 06:42:24 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 06:42:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"f34e6da5-bd3b-4880-a9eb-7537462d3f77","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 504 Peer availabilities has one entry for our connection type
,2017-07-21 06:42:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"70337701-90ba-4799-a631-b7b0af1c7f37","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 505 Peer availabilities has one entry for our connection type
,2017-07-21 06:42:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"f34e6da5-bd3b-4880-a9eb-7537462d3f77","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-21 06:42:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"70337701-90ba-4799-a631-b7b0af1c7f37","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 06:42:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 06:42:24 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"pskIdToSecret":[102,111,111],"networkType":"BOTH"}})'
,2017-07-21 06:42:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 06:42:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:42:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:42:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 06:42:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 506 No peers
,ok 507 No peers
,ok 508 No peers
,# teardown
,ok 509 error should be null
ok 510 error should be null
,# setup
,ok 511 ThaliMobile should be stopped
,# If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted
,2017-07-21 06:42:25 - DEBUG thaliMobileNativeWrapper: 'listening 55492'
2017-07-21 06:42:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"ecc63b26-74f5-4cbd-bd41-d501322b2026","connectionType":"MPCF","peerAvaila,ble":true,"generation":0,"newAddressPort":false}'
ok 512 1
ok 513 2
2017-07-21 06:42:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"6dadc310-d1ae-42e4-8bdd-236d4ca0cce2","connectionType":"MPCF","peerAvailabl,e":true,"generation":0,"newAddressPort":false}'
,# teardown
,2017-07-21 06:42:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"ecc63b26-74f5-4cbd-bd41-d501322b2026","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-21, 06:42:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"6dadc310-d1ae-42e4-8bdd-236d4ca0cce2","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:42:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:42:25 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:42:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 06:42:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 06:42:25 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 514 error should be null
ok 515 error should be null
,# setup
,ok 516 ThaliMobile should be stopped
,# peer should be found once after listening and discovery started
,2017-07-21 06:42:26 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer should be found once after listening and discovery started''
,# teardown
,ok 517 error should be null
ok 518 error should be null
,# setup
,ok 519 ThaliMobile should be stopped
,# can get data from all participants
,2017-07-21 06:42:26 - DEBUG thaliMobileNativeWrapper: 'listening 55493'
ok 520 error should be null
ok 521 error should be null
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "69FD4252-E919-4997-B366-3B,BAAB44C78C", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:69FD4252-E919-4997-B366-3BBAAB44C78C
2017-07-21 06:42:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive,":true}'
ok 522 error should be null
ok 523 error should be null
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:98B4E5E0-88EA-406D-8B47-4F416DFAA8DD
[ThaliCore] Browser.startLi,stening
2017-07-21 06:42:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
ok 524 error should be null
ok 525 error should be null
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:88123B38-04CB-418B-87E1-B5C818C67E9F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "88123B38-04CB-418B-87E1-B5C818C67E9F", generation: 0)
2017-07-21 06:42:27 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"88123B38-04CB-418B-87E1-B5C818C67E9F","generation":0}]'
2017-07-21 06:42:27 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"88123B38-04CB-418B-87E1-B5C818C67E9F","generation":0}'
,2017-07-21 06:42:27 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"88123B38-04CB-418B-87E1-B5C818C67E9F","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-21 06:42:27 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"88123B38-04CB-418B-87E1-B5C818C67E9F","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-21 06:42:27 - DEBUG thaliMobileNativeWrapper: 'Issuing multi,Connect for 88123B38-04CB-418B-87E1-B5C818C67E9F (syncValue: 0)'
2017-07-21 06:42:27 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "88123B38-04CB-418B,-87E1-B5C818C67E9F", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "88123B38-04CB-418B-87E1-B5C818C67E9F", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:,notConnected:) peer:88123B38-04CB-418B-87E1-B5C818C67E9F:0
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:83431272-1D7E-45BE-9C4D-076F715AA398:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "83431272-1D7E-45BE-9C4D-,076F715AA398", generation: 0)
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-21 06:42:27 - DEBUG thaliMobileNativeWrapper: 'Received peerAvail,abilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"83431272-1D7E-45BE-9C4D-076F715AA398","generation":0}]'
2017-07-21 06:42:27 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":t,rue,"peerIdentifier":"83431272-1D7E-45BE-9C4D-076F715AA398","generation":0}'
,2017-07-21 06:42:27 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"83431272-1D7E-45BE-9C4D-076F715AA398","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-21 06:42:27 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"83431272-1D7E-45BE-9C4D-076F715AA398","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1021915A-7DC2-4A2E-9966-C5EE31927BA1
[ThaliCore] Advertiser: session connected Peer(uuid: "69FD4252-E919-4997-B366-3BBAAB44C78C", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:1021915A-7DC2-4A2E-9966-C5EE31927BA1 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:69FD4252-E919-4997-B366-3BBAAB44C78C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "69FD4252-E919-4997-B366-3BBAAB44C78C", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:88123B38-04CB-418B-87E1-B5C818C67E9F:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:1021915A-7DC2-4A2E-9966-C5EE31927BA1
,[ThaliCore] Session.session(_:peer:didChange:) peer:1021915A-7DC2-4A2E-9966-C5EE31927BA1 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:1021915A-7DC2-4A2E-9966-C5EE31927BA1
[ThaliCore] Session.startOutputStream(with:) peer:1021915A-7DC2-4A2E-9966-C5EE31927BA1
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2,0 [1, 3, 7, 20]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:88123B38-04CB-418B-87E1-B5C818C67E9F:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:88123B38-04CB-418B-87E1-B5C818C67E9F:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "88123B38-04CB-418B-87E1-B5C818C67E9F", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:55497
,2017-07-21 06:42:30 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"0","error":null,"portNumber":55497}'
,2017-07-21 06:42:30 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 83431272-1D7E-45BE-9C4D-076F715AA398 (syncValue: 1)'
2017-07-21 06:42:30 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPee,r(_:syncValue:retryCount:completion:) Peer(uuid: "83431272-1D7E-45BE-9C4D-076F715AA398", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "83431272-1D7E-45BE-9C4D-076F715AA398", ge,neration: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:83431272-1D7E-45BE-9C4D-076F715AA398:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnec,ted:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:88123B38-04CB-418B-87E1-B5C818C67E9F:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:88123B38-04CB-418B-87E1-B5C818C67E9F:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:21 [1, 3, 7, 20, 21]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-21 06:42:31 - DEBUG testUtils: 'Got response data'
,2017-07-21 06:42:31 - DEBUG testUtils: 'Got end'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F43D14D4-FBCA-4ED5-903E-91ED1EBB5599
[ThaliCore] Advertiser: session connected Peer(uuid: "69FD4252-E919-4997-B366-3BBAAB44C78C", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:F43D14D4-FBCA-4ED5-903E-91ED1EBB5599 state: notConnected -> connecting
[ThaliCore] Session.session(_:peer:didChange:) peer:83431272-1D7E-4,5BE-9C4D-076F715AA398:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:83431272-1D7E-45BE-9C4D-076F715AA398:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:83431272-1D7E-45BE-9C4D-076F715AA398:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "83431272-1D7E-45BE-9C4D-076F715AA398", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:55501
,2017-07-21 06:42:33 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"1","error":null,"portNumber":55501}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:83431272-1D7E-45BE-9C4D-076F715AA398:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:83431272-1D7E-45BE-9C4D-076F715AA398:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:22 [1, 3, 7, 20, 21, 22]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-21 06:42:33 - DEBUG testUtils: 'Got response data'
,2017-07-21 06:42:33 - DEBUG testUtils: 'Got end'
,ok 526 received all uuids
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:F43D14D4-FBCA-4ED5-903E-91ED1EBB5599
,[ThaliCore] Session.session(_:peer:didChange:) peer:F43D14D4-FBCA-4ED5-903E-91ED1EBB5599 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F43D14D4-FBCA-4ED5-903E-91ED1EBB5599
[ThaliCore] Session.startOutputStream(with:) peer:F43D14D4-FBCA-4ED5-903E-91ED1EBB5599
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2,3 [1, 3, 7, 20, 21, 22, 23]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-21 06:42:34 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"88123B38-04CB-418B-87E1-B5C818C67E9F","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-21, 06:42:34 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"83431272-1D7E-45BE-9C4D-076F715AA398","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore] Advertis,erManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:69FD4252-E919-4997-B366-3BBAAB44C78C
2017-07-21 06:42:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":fal,se}'
2017-07-21 06:42:34 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
2017-07-21 06,:,42:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 06:42:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:42:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 06:42:34 - DEBUG makeIntoCloseAllServer: 'clo,seAll called on server'
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote, peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:20
[ThaliC,ore] VirtualSocket.closeStreams() vsID:20
ok 527 error should be null
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:23
[ThaliCore] VirtualSocket.closeStreams() vsID:23
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited R,unLoop vsID:20
[ThaliCore] VirtualSocket.deinit vsID:20 [1, 3, 7, 21, 22, 23]
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:23
[ThaliCore] VirtualSocket.deinit vsID:23 [1, 3, 7, 21, 22]
,ok 528 error should be null
,# setup
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:21
[ThaliCore] VirtualSocket.closeStreams() vsID:21
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] VirtualSocket exited RunLoop vsID:21
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] VirtualSocket.deinit vsID:21 [1, 3, 7, 22]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:22
[ThaliCore] VirtualSocket.closeStreams() vsID:22
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:22
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] VirtualSocket.deinit vsID:22 [1, 3, 7]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,ok 529 ThaliMobile should be stopped
,# test for data corruption
,2017-07-21 06:42:35 - DEBUG CoordinatedClient: 'test was skipped, name: 'test for data corruption''
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
,ok 539 after start
,2017-07-21 06:42:36 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 540 after kill
,# teardown
,# setup
,# #testThaliPeerAction - double start
,ok 541 should be equal
,# teardown
,# setup
,# #testThaliPeerAction - start after kill
,2017-07-21 06:42:37 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
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
,ok 554 Size must be 2
,ok 555 Entry counter must be 1
,ok 556 Entry exists
,ok 557 Size must be 3
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
ok 584 Size should be MAXSIZE
,# teardown
,# setup
,# #ThaliPeerPoolDefault - single action
,ok 585 is an agent
,ok 586 enqueue is fine
,ok 587 Everything should be off the queue
,# teardown
,# setup
,# #ThaliPeerPoolDefault - multiple actions
,ok 588 is an agent
,ok 589 first enqueue is fine
,ok 590 is an agent
,ok 591 second enqueue is fine
,ok 592 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
,ok 593 Queue is empty
,# teardown
,# setup
,# #ThaliPeerPoolDefault - PSK Pool works
,ok 594 is an agent
ok 595 good enqueue
,ok 596 Identity should match
,2017-07-21 06:42:41 - DEBUG testUtils: 'Got response data'
2017-07-21 06:42:41 - DEBUG testUtils: 'Got end'
ok 597 Got expected response
ok 598 Got psk call back
,# teardown
,2017-07-21 06:42:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
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
,ok 610 queue is not empty
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
,ok 618 we are in the pool
,ok 619 We are out of the pool
,ok 620 Action was killed
,ok 621 The original kill was called too
,ok 622 second item is still in queue
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent
,ok 623 good enqueue
,ok 624 first kill
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
,2017-07-21 06:42:46 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 633 Got right error
ok 634 Start should not be called
ok 635 Kill should have been called at least once
,# teardown
,# setup
,# We reject unrecognized action type
,2017-07-21 06:42:47 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-21 06:42:47 - ERROR thaliPeerPoolOneAtATime: 'Got unsupported action type: blah'
,ok 636 Got right error
,ok 637 Start should not be called
,ok 638 Kill should have been called at least once
,# teardown
,# setup
,# One action on bluetooth
,2017-07-21 06:42:47 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
ok 639 Got null
2017-07-21 06:42:47 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier,: peerID'
ok 640 is an agent
2017-07-21 06:42:47 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerID'
,ok 641 Got killed at least once
,# teardown
,# setup
,# Two notification actions
,2017-07-21 06:42:48 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
ok 642 Got Null
ok 643 Got another null
2017-07-21 06:42:48 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidB,luetooth, Peer Identifier: peerId1'
ok 644 is an agent
2017-07-21 06:42:48 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peer,Id1'
,2017-07-21 06:42:48 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
ok 645 is an agent
2017-07-21 06:42:48 - DEBUG thaliPeerPoolOneAtATime: 'acti,on returned successfully from start - Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
,ok 646 Action 1 killed at least once
,ok 647 Action 1 went first
,ok 648 Action 2 killed at least once
,# teardown
,# setup
,# replicateThroughProblems
,2017-07-21 06:42:48 - DEBUG thaliPeerPoolOneAtATime: 'Action Started success'
2017-07-21 06:42:48 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - success'
,2017-07-21 06:42:48 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,ok 649 should have gotten null
,2017-07-21 06:42:48 - DEBUG thaliPeerPoolOneAtATime: 'Action Started noActivityTimeOut'
,2017-07-21 06:42:48 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: No activity time out - noActivityTimeOut'
,ok 650 Should have stopped nicely
,2017-07-21 06:42:48 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButNotAvailable'
,2017-07-21 06:42:48 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButNotAvailable'
,ok 651 Still looking for null
,2017-07-21 06:42:48 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButAvailable'
,2017-07-21 06:42:48 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButAvailable'
,2017-07-21 06:42:48 - DEBUG thaliPeerPoolOneAtATime: 'Replication action failed badly so we are going to retry'
,2017-07-21 06:42:48 - DEBUG thaliPeerPoolOneAtATime: 'Action Started clone!'
,2017-07-21 06:42:48 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - clone!'
,2017-07-21 06:42:48 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,ok 652 Yup, another null
,ok 653 We cloned!
,# teardown
,# setup
,# Replication goes first
,2017-07-21 06:42:49 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 654 Null 1
ok 655 (unnamed assert)
2017-07-21 06:42:49 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
ok 656 is an agent
ok 657 ,Null 3
ok 658 Replication not yet called
ok 659 Notification 2 not yet called
2017-07-21 06:42:49 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBluetoot,h, Peer Identifier: notificationAction'
2017-07-21 06:42:49 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
ok 660 is an agent
ok 661, Notification went first
ok 662 Notification 2 not called yet
,2017-07-21 06:42:49 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
2017-07-21 06:42:49 - DEBUG thaliPeerPoo,lOneAtATime: 'Got a replication response with no error!'
2017-07-21 06:42:49 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
ok 663 is, an agent
ok 664 Notification finished
ok 665 Replication finished
2017-07-21 06:42:49 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Ide,ntifier: notificationAction'
,# teardown
,# setup
,# wifi allows many parallel non-replication actions
,2017-07-21 06:42:49 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
2017-07-21 06:42:49 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
ok 666 is an agent
ok 667 First does, not throw
2017-07-21 06:42:49 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
ok 668 is an agent
ok 669 Second does not throw
,2017-07-21 06:42:49 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
,truetruefalsetrue
,2017-07-21 06:42:49 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
,truetruetruetrue
,# teardown
,# setup
,# wifi allows no more than 2 simultaneous replication actions for same peerID
,2017-07-21 06:42:50 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
2017-07-21 06:42:50 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 595, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
ok 670 is an agent
ok 671 first ok
,2017-07-21 06:42:50 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 596, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,ok 672 is an agent
,ok 673 second ok
,ok 674 third ok
,2017-07-21 06:42:50 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 595, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
2017-07-21 06:42:50 - DEBUG thaliPeerPoolOneAtATime: 'action returned, successfully from start - Action ID: 596, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
2017-07-21 06:42:50 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
2017-07-21 06:42:50 - DEBUG thaliPeerPoo,lOneAtATime: 'Got a replication response with no error!'
# teardown
,# setup
,# Client to server request coordinated
,2017-07-21 06:42:50 - DEBUG CoordinatedClient: 'test was skipped, name: 'Client to server request coordinated''
,# teardown
,2017-07-21 06:42:50 - INFO testThaliNotification: 'Participants:0 Peers Replied to us:0 Peers requested to:0'
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
,2017-07-21 06:42:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test HTTP_BAD_RESPONSE locally
,2017-07-21 06:42:51 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test HTTP_BAD_RESPONSE locally''
,2017-07-21 06:42:51 - DEBUG thaliMobileNativeTestUtils: 'Test timeout reached. Restarting test.'
,# teardown
,2017-07-21 06:42:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test NETWORK_PROBLEM locally
,ok 683 Response should be NETWORK_PROBLEM
,ok 684 reject reason should be: Could not establish TCP connection
,# teardown
,2017-07-21 06:42:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Action fails when getPeerHostInfo fails
,ok 685 Resolution should be BAD_PEER
,ok 686 correct error message
,# teardown
,2017-07-21 06:42:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the start two times
,ok 687 Call start once
,ok 688 Response should be BEACONS_RETRIEVED_AND_PARSED
ok 689 must return null after successful call.
,# teardown
,2017-07-21 06:42:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill before calling the start
,ok 690 Should be Killed
,ok 691 Start after killed
,# teardown
,2017-07-21 06:42:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill immediately after the start
,ok 692 Should be KILLED
,ok 693 must return null after successful kill
,# teardown
,2017-07-21 06:42:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill while waiting a response from the server
,ok 694 Should be KILLED
ok 695 must return null after successful kill
,# teardown
,2017-07-21 06:42:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test to exceed the max content size locally
,ok 696 HTTP_BAD_RESPONSE should be response when content size is exceeded
,ok 697 must return null after successful call
,# teardown
,2017-07-21 06:42:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Close the server socket while the client is waiting a response from the server. Local test.
,2017-07-21 06:43:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 698 Should be NETWORK_PROBLEM caused closing server socket
ok 699 Should be Could not establish TCP connection
,# teardown
,# setup
,# Close the client socket while the client is waiting a response from the server. Local test.
,ok 700 Should be NETWORK_PROBLEM caused closing client socket
,ok 701 Should be Could not establish TCP connection
,# teardown
,2017-07-21 06:43:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #generatePreambleAndBeacons bad args
,ok 702 publicKeysToNotify cannot be null
,ok 703 ecdh for local device cannot be null
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
,2017-07-21 06:43:08 - DEBUG CoordinatedClient: 'test was skipped, name: '#parseBeacons addressBookCallback returns no matches''
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns spurious match
,ok 719 should be equal
ok 720 should be equal
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
,ok 735 keys match
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
,2017-07-21 06:43:12 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,2017-07-21 06:43:12 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-07-21 06:43:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# TCP_NATIVE peer loses DNS
,ok 745 notification peer dictionary contains exactly 1 peer
,2017-07-21 06:43:13 - WARN thaliNotificationClient: 'peer is not available'
,ok 746 notification peer dictionary does not contain any peers
,2017-07-21 06:43:13 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-07-21 06:43:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Received beacons with no values for us
,ok 747 entry exists
ok 748 entry is resolved
,# teardown
,2017-07-21 06:43:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Notification action killed with a superseded
,ok 749 Action should be KILLED
,ok 750 Peer state should be RESOLVED
,# teardown
,2017-07-21 06:43:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally
,ok 751 hostAddress must match
ok 752 portNumber must match
,ok 753 suggestedTCPTimeout must match
ok 754 connectionType must match
,ok 755 peerIDs must match
,# teardown
,2017-07-21 06:43:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Emits error event when peerPool.enqueue throws
,ok 756 Correct error
,# teardown
,2017-07-21 06:43:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally using ThaliPeerPoolDefault
,ok 757 hostAddress must match
,ok 758 portNumber must match
,ok 759 suggestedTCPTimeout must match
,ok 760 connectionType must match
,ok 761 peerIds must match
,# teardown
,2017-07-21 06:43:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Action fails because of a bad hostname.
,2017-07-21 06:43:17 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 762 action should be resolved with NETWORK_PROBLEM error
,2017-07-21 06:43:17 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 763 action should be resolved with NETWORK_PROBLEM error
,2017-07-21 06:43:18 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 764 action should be resolved with NETWORK_PROBLEM error
,2017-07-21 06:43:18 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 765 action should be resolved with NETWORK_PROBLEM error
ok 766 correct number of requests
ok 767 correct number of failures
ok 768 correct final peer state
,# teardown
,2017-07-21 06:43:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# hostaddress is removed when the action is running. 
,2017-07-21 06:43:21 - WARN thaliNotificationClient: 'peer is not available'
2017-07-21 06:43:21 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 769 peerDictionary should become empty
# teardown
,2017-07-21 06:43:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notificationClient does not retry action with BAD_PEER resolution
,2017-07-21 06:43:21 - DEBUG thaliMobileNativeTestUtils: 'Test timeout reached. Restarting test.'
,2017-07-21 06:43:22 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 770 failed with expected error
ok 771 peer state should be RESOLVED
,# teardown
,2017-07-21 06:43:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notification client correctly handles peer availability changes of the same peer
,2017-07-21 06:43:22 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 772 First action failed
,ok 773 second action killed
# teardown
,2017-07-21 06:43:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Client to server request locally
,ok 774 secrets are equal
,ok 775 Public key matches with the server key
ok 776 hostAddress must match
,ok 777 portNumber must match
,ok 778 suggestedTCPTimeout must match
,ok 779 connectionType must match
,# teardown
,2017-07-21 06:43:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache clean and expiration
,ok 780 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE
ok 781 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE-1
,ok 782 All entries should be expired after 1 second
# teardown
,2017-07-21 06:43:25 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache getSecret and getPublic
,ok 783 All keys need to be available in the cache
,ok 784 All entries should be expired after 1 second
,# teardown
,2017-07-21 06:43:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache multiple entries
,ok 785 Size of the cache should be 2
ok 786 Cache doesn't contain dictionary1
,ok 787 Size of the cache should be 1
ok 788 Cache doesn't contain beaconStreamAndSecretDictionary2
# teardown
,2017-07-21 06:43:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Start and stop ThaliNotificationServer
,ok 789 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
,ok 790 ThaliMobile.StopAdvertisingAndListeningshould be called once
,# teardown
,2017-07-21 06:43:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass an empty array to ThaliNotificationServer.start
,ok 791 StartUpdateAdvertisingAndListening should not be called
,ok 792 ThaliMobile.StopAdvertisingAndListening should be called once
,ok 793 no error
,ok 794 should be 204
,# teardown
,2017-07-21 06:43:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass a string to ThaliNotificationServer.start
,ok 795 StartUpdateAdvertisingAndListening should not be called
,# teardown
,2017-07-21 06:43:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass an empty parameter to ThaliNotificationServer.start
,ok 796 StartUpdateAdvertisingAndListening should not be called
,# teardown
,2017-07-21 06:43:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeacons
,ok 797 no error
,ok 798 should be 200
ok 799 should be equal
,ok 800 should be equal
,ok 801 (unnamed assert)
,ok 802 no error
ok 803 should be 204
,# teardown
,2017-07-21 06:43:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeacons (no keys)
,ok 804 error should be null
ok 805 should be 204
# teardown
,2017-07-21 06:43:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeaconsbefore calling start
,ok 806 should be 404
,# teardown
,2017-07-21 06:43:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure peerDictionaryKey is reasonable
,ok 807 equal keys
,ok 808 not equal connection type
,ok 809 same connection type, different buffer
,# teardown
,# setup
,# Make sure start works
,2017-07-21 06:43:34 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,ok 810 First start and on called correctly
,# teardown
,# setup
,# Make sure stop works
,ok 811 second cleared dictionary
,2017-07-21 06:43:34 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,ok 812 First start and on called correctly
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
,2017-07-21 06:43:35 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,ok 821 listener has been set
ok 822 peer dictionary has expected number of entries
ok 823 Dictionary and pool have same action
ok 824 ads match
ok 825 PouchDB matches
ok 826 DB Names match
,ok 827 public keys match
,ok 828 peer dictionary has expected number of entries
,ok 829 Dictionary and pool have same action
,ok 830 ads match
,ok 831 PouchDB matches
,ok 832 DB Names match
,ok 833 public keys match
,2017-07-21 06:43:35 - DEBUG thaliReplicationPeerAction: 'We called _complete with  and it caused us to complete'
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
,2017-07-21 06:43:35 - DEBUG CoordinatedClient: 'test was skipped, name: 'Coordinated pull replication from notification test''
,# teardown
,# setup
,# Server is not there
,2017-07-21 06:43:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 06:43:36 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 connect ECONNREFUSED'
,2017-07-21 06:43:36 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: connect ECONNREFUSED  and it caused us to complete'
,ok 847 right error
,# teardown
,2017-07-21 06:43:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server accepts & closes connection
,2017-07-21 06:43:37 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 socket hang up'
,2017-07-21 06:43:37 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: socket hang up  and it caused us to complete'
,ok 848 right error
,# teardown
,2017-07-21 06:43:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 500
,2017-07-21 06:43:38 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 changes rejected'
,2017-07-21 06:43:38 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 849 Got error as expected
,# teardown
,2017-07-21 06:43:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 401
,2017-07-21 06:43:39 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  401 changes rejected'
,2017-07-21 06:43:39 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 850 Got error as expected
,# teardown
,2017-07-21 06:43:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 403
,2017-07-21 06:43:39 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  403 changes rejected'
,2017-07-21 06:43:39 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 851 Got error as expected
,# teardown
,2017-07-21 06:43:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure docs replicate with remote db with same name as local db
,2017-07-21 06:43:41 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-21 06:43:41 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-21 06:43:43 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
,ok 852 should be equal
ok 853 All tests passed!
,# teardown
,2017-07-21 06:43:45 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure docs replicate with remote db with different name than local db
,2017-07-21 06:43:46 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-21 06:43:46 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-21 06:43:49 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
,ok 854 should be equal
ok 855 All tests passed!
,# teardown
,2017-07-21 06:43:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Do nothing and make sure we time out
,2017-07-21 06:43:51 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-21 06:43:51 - DEBUG thaliMobileNativeTestUtils: 'Test timeout reached. Restarting test.'
,2017-07-21 06:43:52 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2017-07-21 06:43:52 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and s,o we ignored it'
ok 856 action should be killed
ok 857 Error should be timed out
,ok 858 No doc found
,# teardown
,2017-07-21 06:43:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Do something and make sure we time out
,2017-07-21 06:43:53 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-21 06:43:54 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,ok 859 should be equal
,2017-07-21 06:43:56 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
,2017-07-21 06:43:56 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
,ok 860 action should be killed
,ok 861 Error should be timed out
,# teardown
,2017-07-21 06:43:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Start replicating and then catch error when server goes
,ok 862 socket hung up
,# teardown
,2017-07-21 06:43:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure clone works
,ok 863 same getPeerAdvertisesDataForUs
ok 864 Same pouchdB
ok 865 same localDbName
ok 866 Same public key
,# teardown
,# setup
,# Coordinated replication action test - each device has the same local db name
,2017-07-21 06:43:59 - DEBUG CoordinatedClient: 'test was skipped, name: 'Coordinated replication action test - each device has the same local db name''
,# teardown
,# setup
,# Coordinated replication action test - each device has different local db name
,2017-07-21 06:44:00 - DEBUG thaliMobileNativeWrapper: 'listening 55630'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:830C9201-47E3-42BA-B571-27A4F2619A13
[ThaliCore] Browser.startListening
,2017-07-21 06:44:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "439F642B-C473-4E6B-8743-D49D9B8F5AA6", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:439F642B-C473-4E6B-8743-D49D9B8F5AA6
,2017-07-21 06:44:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:53FC0754-967F-4DFA-92BF-B582F6BBCA26
[ThaliCore] Advertiser: session connected Peer(uuid: "439F642B-C473-4E6B-8743-D49D9B8F5AA6", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:53FC0754-967F-4DFA-92BF-B582F6BBCA26 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:68E27EF3-CB0B-4051-8D0D-E00E7665799C
[ThaliCore] Advertiser: session connected Peer(uuid: "439F642B-C473-4E6B-8743-D49D9B8F5AA6", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:68E27EF3-CB0B-4051-8D0D-E00E7665799C state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FE28E071-97B0-472F-81FD-46A648C78A9F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FE28E071-97B0-472F-81FD-46A648C78A9F", generation: 0)
2017-07-21 06:44:01 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"FE28E071-97B0-472F-81FD-46A648C78A9F","generation":0}]'
2017-07-21 06:44:01 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"FE28E071-97B0-472F-81FD-46A648C78A9F","generation":0}'
,2017-07-21 06:44:01 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"FE28E071-97B0-472F-81FD-46A648C78A9F","peerAvailable":true,"generation":0,"portNumber":null}'
[ThaliCore] Browser.browser(_:foundPeer:withDi,scoveryInfo:) found peer:5187EC00-26E2-4DBA-9E49-8E9F4B5E9607:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5187EC00-26E2-4DBA-9E49-8E9F4B5E9607", generation: 0)
2017-07-21 06:44:01 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged ,from handlePeer {"peerIdentifier":"FE28E071-97B0-472F-81FD-46A648C78A9F","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-21 06:44:01 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for FE28E071-97B0-472F-81FD-46A648C78A9F (syncValue: 2)'
2017-07-21 06:44:01 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "FE28E071-97B0-472F-81FD-46A648C78A9F", generati,on: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FE28E071-97B0-472F-81FD-46A648C78A9F", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FE28E071-,97B0-472F-81FD-46A648C78A9F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 06:44:01 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"5187EC00-26E2-4DBA-9E49-8E9F4B5E9607","generation":0}]'
,2017-07-21 06:44:01 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"5187EC00-26E2-4DBA-9E49-8E9F4B5E9607","generation":0}'
,2017-07-21 06:44:01 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"5187EC00-26E2-4DBA-9E49-8E9F4B5E9607","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 06:44:01 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5187EC00-26E2-4DBA-9E49-8E9F4B5E9607","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:439F642B-C473-4E6B-8743-D49D9B8F5AA6:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "439F642B-C473-4E6B-8743-D49D9B8F5AA6", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:FE28E071-97B0-472F-81FD-46A648C78A9F:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:68E27EF3-CB0B-4051-8D0D-E00E7665799C
,[ThaliCore] Session.session(_:peer:didChange:) peer:68E27EF3-CB0B-4051-8D0D-E00E7665799C state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:68E27EF3-CB0B-4051-8D0D-E00E7665799C
[ThaliCore] Session.startOutputStream(with:) peer:68E27EF3-CB0B-4051-8D0D-E00E7665799C
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:24 [1, 3, 7, 24]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:24
[ThaliCore] VirtualSocket.closeStreams() vsID:24
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] Session.session(_:didReceive:withN,ame:fromPeer:) peer:68E27EF3-CB0B-4051-8D0D-E00E7665799C
[ThaliCore] Session.startOutputStream(with:) peer:68E27EF3-CB0B-4051-8D0D-E00E7665799C
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:25 [1, 3, 7, 24, 25]
[ThaliCore] TCPClient.con,nectToLocalhost(onPort:)
[ThaliCore] VirtualSocket exited RunLoop vsID:24
[ThaliCore] VirtualSocket.deinit vsID:24 [1, 3, 7, 25]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDi,dDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:53FC0754-967F-4DFA-92BF-B582F6BBCA26
,[ThaliCore] Session.session(_:peer:didChange:) peer:53FC0754-967F-4DFA-92BF-B582F6BBCA26 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:68E27EF3-CB0B-4051-8D0D-E00E7665799C
[ThaliCore] Session.startOutputStream(with:) peer:68E27EF3-CB0B-4051-8D0D-E00E7665799C
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:26 [1, 3, 7, 25, 26]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:53FC0754-967F-4DFA-92BF-B582F6BBCA26
[ThaliCore] Session.startOutputStream(with:) peer:53FC0754-967F-4DFA-92BF-B582F6BBCA26
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2,7 [1, 3, 7, 25, 26, 27]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:FE28E071-97B0-472F-81FD-46A648C78A9F:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:FE28E071-97B0-472F-81FD-46A648C78A9F:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "FE28E071-97B0-472F-81FD-46A648C78A9F", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:55637
,2017-07-21 06:44:04 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"2","error":null,"portNumber":55637}'
,2017-07-21 06:44:04 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 5187EC00-26E2-4DBA-9E49-8E9F4B5E9607 (syncValue: 3)'
2017-07-21 06:44:04 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5187EC00-26E2-4DBA-9E49-8E9F4B5E9607", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "51,87EC00-26E2-4DBA-9E49-8E9F4B5E9607", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5187EC00-26E2-4DBA-9E49-8E9F4B5E9607:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore,] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:FE28E071-97B0-472F-81FD-46A648C78A9F:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FE28E071-97B0-472F-81FD-46A648C78A9F:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:28 [1, 3, 7, 25, 26, 27, 28]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:27
[ThaliCore] VirtualSocket.closeStreams() vsID:27
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:27
,[ThaliCore] VirtualSocket.deinit vsID:27 [1, 3, 7, 25, 26, 28]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:53FC0754-967F-4DFA-92BF-B582F6BBCA26
[ThaliCore] Session.startOutputStream(with:) peer:53FC0754-967F-4DFA-92BF-B582F6BBCA26
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:29 [1, 3, 7, 25, 26, 28, 29]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:28
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:28
[ThaliCore] VirtualSocket.deinit vsID:28 [1, 3, 7, 25, 26, 29]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:FE28E071-97B0-472F-81FD-46A648C78A9F:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FE28E071-97B0-472F-81FD-46A648C78A9F:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:30 [1, 3, 7, 25, 26, 29, 30]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:68E27EF3-CB0B-4051-8D0D-E00E7665799C
[ThaliCore] Session.startOutputStream(with:) peer:68E27EF3-CB0B-4051-8D0D-E00E7665799C
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:31 [1, 3, 7, 25, 26, 29, 30, 31]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:53FC0754-967F-4DFA-92BF-B582F6BBCA26
[ThaliCore] Session.startOutputStream(with:) peer:53FC0754-967F-4DFA-92BF-B582F6BBCA26
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:32 [1, 3, 7, 25, 26, 29, 30, 31, 32]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:peer:didChange:) peer:5187EC00-26E2-4DBA-9E49-8E9F4B5E9607:0 state: notConnected -> connecting
,2017-07-21 06:44:05 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:68E27EF3-CB0B-4051-8D0D-E00E7665799C
[ThaliCore] Session.startOutputStream(with:) peer:68E27EF3-CB0B-4051-8D0D-E00E7665799C
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3,3 [1, 3, 7, 25, 26, 29, 30, 31, 32, 33]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:FE28E071-97B0-472F-81FD-46A648C78A9F:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FE28E071-97B0-472F-81FD-46A648C78A9F:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:34 [1, 3, 7, 25, 26, 29, 30, 31, 32, 33, 34]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:68E27EF3-CB0B-4051-8D0D-E00E7665799C
[ThaliCore] Session.startOutputStream(with:) peer:68E27EF3-CB0B-4051-8D0D-E00E7665799C
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:35 [1, 3, 7, 25, 26, 29, 30, 31, 32, 33, 34, 35]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:33
[ThaliCore] VirtualSocket.closeStreams() vsID:33
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:33
,[ThaliCore] VirtualSocket.deinit vsID:33 [1, 3, 7, 25, 26, 29, 30, 31, 32, 34, 35]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[,ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:53FC0754-967F-4DFA-92BF-B582F6BBCA26
[ThaliCore] Session.startOutputStream(with:) peer:53FC0754-967F-4DFA-92BF-B582F6BBCA26
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:36 [1, 3, 7, 25, 26, 29, 30, 31, 32, 34, 35, 36]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:FE28E071-97B0-472F-81FD-46A648C78A9F:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:53FC0754-967F-4DFA-92BF-B582F6BBCA26
[ThaliCore] Session.startOutputStream(with:) peer:53FC0754-967F-4DFA-92BF-B582F6BBCA26
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:37 [1, 3, 7, 25, 26, 29, 30, 31, 32, 34, 35, 36, 37]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FE28E071-97B0-472F-81FD-46A648C78A9F:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:38 [1, 3, 7, 25, 26, 29, 30, 31, 32, 34, 35, 36, 37, 38]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:68E27EF3-CB0B-4051-8D0D-E00E7665799C
[ThaliCore] Session.startOutputStream(with:) peer:68E27EF3-CB0B-4051-8D0D-E00E7665799C
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:39 [1, 3, 7, 25, 26, 29, 30, 31, 32, 34, 35, 36, 37, 38, 39]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:FE28E071-97B0-472F-81FD-46A648C78A9F:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FE28E071-97B0-472F-81FD-46A648C78A9F:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:40 [1, 3, 7, 25, 26, 29, 30, 31, 32, 34, 35, 36, 37, 38, 39, 40]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:53FC0754-967F-4DFA-92BF-B582F6BBCA26
,[ThaliCore] Session.startOutputStream(with:) peer:53FC0754-967F-4DFA-92BF-B582F6BBCA26
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:41 [1, 3, 7, 25, 26, 29, 30, 31, 32, 34, 35, 36, 37, 38, 39, 40, 41]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:39
,[ThaliCore] VirtualSocket.closeStreams() vsID:39
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:39
[ThaliCore] VirtualSocket.deinit vsID:39 [1, 3, 7, 25, 26, 29, 30, 31, 32, 34, 35, 36, 37, 38, 40, 41]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:68E27EF3-CB0B-4051-8D0D-E00E7665799C
[ThaliCore] Session.startOutputStream(with:) peer:68E27EF3-CB0B-4051-8D0D-E00E7665799C
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:42 [1, 3, 7, 25, 26, 29, 30, 31, 32, 34, 35, 36, 37, 38, 40, 41, 42]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:83431272-1D7E-45BE-9C4D-076F715AA398:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "83431272-1D7E-45BE-9C4D-076F715AA398", generation: 0)
,2017-07-21 06:44:05 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"83431272-1D7E-45BE-9C4D-076F715AA398","generation":0}]'
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:37
[ThaliCore] VirtualSocket.closeStreams() vsID:37
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:37
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] VirtualSocket.deinit vsID:37 [1, 3, 7, 25, 26, 29, 30, 31, 32, 34, 35, 36, 38, 40, 41, 42]
[ThaliCo,re] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-21 06:44:05 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"83431272-1D7E-45BE-9C4D-076F715AA398","generation":0}'
,2017-07-21 06:44:05 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"83431272-1D7E-45BE-9C4D-076F715AA398","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 06:44:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"83431272-1D7E-45BE-9C4D-076F715AA398","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:FE28E071-97B0-472F-81FD-46A648C78A9F:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FE28E071-97B0-472F-81FD-46A648C78A9F:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:43 [1, 3, 7, 25, 26, 29, 30, 31, 32, 34, 35, 36, 38, 40, 41, 42, 43]
[ThaliCore] Brows,erRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:43
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:43
[ThaliCore] VirtualSocket.deinit vsID:43 [1, 3, 7, 25, 26, 29, 30, 31, 32, 34, 35, 36, 38, 40, 41, 42]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:68E27EF3-CB0B-4051-8D0D-E00E7665799C
[ThaliCore] Session.startOutputStream(with:) peer:68E27EF3-CB0B-4051-8D0D-E00E7665799C
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4,4 [1, 3, 7, 25, 26, 29, 30, 31, 32, 34, 35, 36, 38, 40, 41, 42, 44]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:35
[ThaliCore] VirtualSocket.closeStreams() vsID:35
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 5
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] Adv,ertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:35
[ThaliCore] VirtualSocket.deinit vsID:35 [1, 3, 7, 25, 26, 29, 30, 31, 32, 34, 36, 38, 40, 41, 42, 44]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:42
[ThaliCore] VirtualSocket.closeStreams() vsID:42
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:42
[ThaliCore] VirtualSocket.deinit vsID:42 [1, 3, 7, 25, 26, 29, 30, 31, 32, 34, 36, 38, 40, 41, 44]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:FE28E071-97B0-472F-81FD-46A648C78A9F:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FE28E071-97B0-472F-81FD-46A648C78A9F:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:45 [1, 3, 7, 25, 26, 29, 30, 31, 32, 34, 36, 38, 40, 41, 44, 45]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:53FC0754-967F-4DFA-92BF-B582F6BBCA26
[ThaliCore] Session.startOutputStream(with:) peer:53FC0754-967F-4DFA-92BF-B582F6BBCA26
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:46 [1, 3, 7, 25, 26, 29, 30, 31, 32, 34, 36, 38, 40, 41, 44, 45, 46]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,2017-07-21 06:44:05 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vs,ID:45
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:45
[ThaliCore] VirtualSocket.deinit vsID:45 [1, 3, 7, 25, 26, 29, 30, 31, 32, 34, 36, 38, 40, 41, 44, 46]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:46
[ThaliCore] VirtualSocket.closeStreams() vsID:46
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:46
,[ThaliCore] VirtualSocket.deinit vsID:46 [1, 3, 7, 25, 26, 29, 30, 31, 32, 34, 36, 38, 40, 41, 44]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:5187EC00-26E2-4DBA-9E49-8E9F4B5E9607:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:5187EC00-26E2-4DBA-9E49-8E9F4B5E9607:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "5187EC00-26E2-4DBA-9E49-8E9F4B5E9607", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:55659
2017-07-21 06:44:07 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"3","error":null,"portNumber":55659,}'
,2017-07-21 06:44:07 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 83431272-1D7E-45BE-9C4D-076F715AA398 (syncValue: 4)'
2017-07-21 06:44:07 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPee,r(_:syncValue:retryCount:completion:) Peer(uuid: "83431272-1D7E-45BE-9C4D-076F715AA398", generation: 0) found active relay
2017-07-21 06:44:07 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"4","error":null,"portNumber":55501}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:5187EC00-26E2-4DBA-9E49-8E9F4B5E9607:0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:83431272-1D7E-45BE-9C4D-076F715AA398:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:83431272-1D7E-45BE-9C4D-076F715AA398:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:47 [1, 3, 7, 25, 26, 29, 30, 31, 32, 34, 36, 38, 40, 41, 44, 47]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:47
[ThaliCore] VirtualSocket.closeStreams() vsID:47
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] VirtualSocket exited RunLoop vsID:47
,[ThaliCore] VirtualSocket.deinit vsID:47 [1, 3, 7, 25, 26, 29, 30, 31, 32, 34, 36, 38, 40, 41, 44]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5187EC00-26E2-4DBA-9E49-8E9F4B5E9607:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:48 [1, 3, 7, 25, 26, 29, 30, 31, 32, 34, 36, 38, 40, 41, 44, 48]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-21 06:44:07 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:48
,[ThaliCore] VirtualSocket exited RunLoop vsID:48
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:48 [1, 3, 7, 25, 26, 29, 30, 31, 32, 34, 36, 38, 40, 41, 44]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:5187EC00-26E2-4DBA-9E49-8E9F4B5E9607:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5187EC00-26E2-4DBA-9E49-8E9F4B5E9607:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:49 [1, 3, 7, 25, 26, 29, 30, 31, 32, 34, 36, 38, 40, 41, 44, 49]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-21 06:44:07 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 83431272-1D7E-45BE-9C4D-076F715AA398 (syncValue: 5)'
,2017-07-21 06:44:07 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "83431272-1D7E-45BE-9C4D-076F715AA398", generation: 0) found active relay
,2017-07-21 06:44:07 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"5","error":null,"portNumber":55501}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:83431272-1D7E-45BE-9C4D-076F715AA398:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:83431272-1D7E-45BE-9C4D-076F715AA398:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:50 [1, 3, 7, 25, 26, 29, 30, 31, 32, 34, 36, 38, 40, 41, 44, 49, 50]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:50
[ThaliCore] VirtualSocket.closeStreams() vsID:50
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:50
,[ThaliCore] VirtualSocket.deinit vsID:50 [1, 3, 7, 25, 26, 29, 30, 31, 32, 34, 36, 38, 40, 41, 44, 49]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-21 06:44:07 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,2017-07-21 06:44:08 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:5187EC00-26E2-4DBA-9E49-8E9F4B5E9607:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5187EC00-26E2-4DBA-9E49-8E9F4B5E9607:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:51 [1, 3, 7, 25, 26, 29, 30, 31, 32, 34, 36, 38, 40, 41, 44, 49, 51]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:29
[ThaliCore] VirtualSocket.closeStreams() vsID:29
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] TCPClient.socketDidDisconnect(_:wi,thError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket.handleEventOnInputStream endE,ncountered vsID:32
[ThaliCore] VirtualSocket.closeStreams() vsID:32
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:41
[ThaliCore] VirtualSocket.closeStreams() vsID:41
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:36
[ThaliCore] VirtualSocket exited RunLoop vsID:32
[ThaliCore] VirtualSocket.closeStreams() vsID:36
[ThaliCore] VirtualSocket.deinit vsID:32 [1, 3, 7, 25, 26, 29, 30, 31, 34, 36, 38, 40, 41, 44, 49, 51]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconn,ecting:false
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:41
,[ThaliCore] VirtualSocket.deinit vsID:41 [1, 3, 7, 25, 26, 29, 30, 31, 34, 36, 38, 40, 44, 49, 51]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:36
[ThaliCore] VirtualSocket.deinit vsID:36 [1, 3, 7, 25, 26, 29, 30, 31, 34, 38, 40, 44, 49, 51]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-21 06:44:08 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 83431272-1D7E-45BE-9C4D-076F715AA398 (syncValue: 6)'
,2017-07-21 06:44:08 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "83431272-1D7E-45BE-9C4D-076F715AA398", generation: 0) found active relay
,2017-07-21 06:44:08 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"6","error":null,"portNumber":55501}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:83431272-1D7E-45BE-9C4D-076F715AA398:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:83431272-1D7E-45BE-9C4D-076F715AA398:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:52 [1, 3, 7, 25, 26, 29, 30, 31, 34, 38, 40, 44, 49, 51, 52]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-21 06:44:08 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
,2017-07-21 06:44:08 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:52
,[ThaliCore] VirtualSocket.closeStreams() vsID:52
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:52
,[ThaliCore] VirtualSocket.deinit vsID:52 [1, 3, 7, 25, 26, 29, 30, 31, 34, 38, 40, 44, 49, 51]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:30
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:30
[ThaliCore] VirtualSocket.deinit vsID:30 [1, 3, 7, 25, 26, 29, 31, 34, 38, 40, 44, 49, 51]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vs,ID:34
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:34
[ThaliCore] VirtualSocket.deinit vsID:34 [1, 3, 7, 25, 26, 29, 31, 38, 40, 44, 49, 51]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:38
[ThaliCore] Browse,rRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:38
[ThaliCore] VirtualSocket.deinit vsID:38 [1, 3, 7, 25, 26, 29, 31, 40, 44, 49, 51]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:40
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:40
[ThaliCore] VirtualSocket.deinit vsID:40 [1, 3, 7, 25, 26, 29, 31, 44, 49, 51]
,2017-07-21 06:44:08 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:25
[ThaliCore] VirtualSocket.closeStreams() vsID:25
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:25
,[ThaliCore] VirtualSocket.deinit vsID:25 [1, 3, 7, 26, 29, 31, 44, 49, 51]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:26
,[ThaliCore] VirtualSocket.closeStreams() vsID:26
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:26
[ThaliCore] VirtualSocket.deinit vsID:26 [1, 3, 7, 29, 31, 44, 49, 51]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:31
,[ThaliCore] VirtualSocket.closeStreams() vsID:31
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:31
[ThaliCore] VirtualSocket.deinit vsID:31 [1, 3, 7, 29, 44, 49, 51]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:44
[ThaliCore] VirtualSocket.closeStreams() vsID:44
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:44
,[ThaliCore] VirtualSocket.deinit vsID:44 [1, 3, 7, 29, 49, 51]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:5187EC00-26E2-4DBA-9E49-8E9F4B5E9607:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5187EC00-26E2-4DBA-9E49-8E9F4B5E9607:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:53 [1, 3, 7, 29, 49, 51, 53]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:49
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:49
[ThaliCore] VirtualSocket.deinit vsID:49 [1, 3, 7, 29, 51, 53]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:51
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:51
,[ThaliCore] VirtualSocket.deinit vsID:51 [1, 3, 7, 29, 53]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:5187EC00-26E2-4DBA-9E49-8E9F4B5E9607:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vs,ID:53
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:53
[ThaliCore] VirtualSocket.deinit vsID:53 [1, 3, 7, 29]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5187EC00-26E2-4DBA-9E49-8E9F4B5E9607:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:54 [1, 3, 7, 29, 54]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-21 06:44:08 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 socket hang up -1'
,2017-07-21 06:44:08 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: socket hang up -1  but we are already killed and so we ignored it'
,2017-07-21 06:44:09 - DEBUG localSeqManager: 'Got an error trying to update seq {"onPut":true}'
2017-07-21 06:44:09 - DEBUG thaliReplicationPeerAction: 'Got error in update:  Stop Called, but we are already killed and so we ignored it'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:439F642B-C473-4E6B-8743-D49D9B8F5AA6
2017-07-21 06:44:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-07-21 06:44:09 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"FE28E071-97B0-472F-81FD-46A648C78A9F","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddre,ssPort":null}'
2017-07-21 06:44:09 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"5187EC00-26E2-4DBA-9E49-8E9F4B5E9607","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":nu,ll}'
2017-07-21 06:44:09 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"83431272-1D7E-45BE-9C4D-076F715AA398","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 06:44:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 06:44:09 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
,2017-07-21 06:44:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-21 06:44:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:44:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:44:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 867 passed
,# teardown
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:54
[ThaliCore] VirtualSocket.closeStreams() vsID:54
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:54
,[ThaliCore] VirtualSocket.deinit vsID:54 [1, 3, 7, 29]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,# setup
,# Coordinated replication action test - should throw error when wrong remote db name is provided
,2017-07-21 06:44:10 - DEBUG thaliMobileNativeWrapper: 'listening 55668'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:ACBCE97F-51A6-414B-B118-5F9CA3C998BC
,[ThaliCore] Browser.startListening
,2017-07-21 06:44:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "72682503-3E6C-4AF3-B364-3A3C1540F4CE", generation: 0)
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:53FC0754-967F-4DFA-92BF-B582F6BBCA26,
[ThaliCore] Session.startOutputStream(with:) peer:53FC0754-967F-4DFA-92BF-B582F6BBCA26
[ThaliCore] Advertiser.startAdvertising with peerID:72682503-3E6C-4AF3-B364-3A3C1540F4CE
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:55 [1, 3, 7, ,29, 55]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,2017-07-21 06:44:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=1 "Operation not permitted" UserInfo={NSLocalizedDescription=Operation not permitted, NSLocalizedFailureReason=Error in c,onnect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:55
[ThaliCore] VirtualSocket.closeStreams() vsID:55
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:55
[ThaliCore] VirtualSocket.deinit vsID:55 [1, 3, 7, 29]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:53FC0754-967F-4DFA-92BF-B582F6BBCA26
[ThaliCore] Session.startOutputStream(with:) peer:53FC0754-967F-4DFA-92BF-B582F6BBCA26
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5,6 [1, 3, 7, 29, 56]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedDescription=Connection refused, NSLocalizedFailureReason=Error in connect() ,function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:56
[ThaliCore] VirtualSocket.closeStreams() vsID:56
[ThaliCore] AdvertiserRelay.did,CloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:56
[ThaliCore] VirtualSocket.deinit vsID:56 [1, 3, 7, 29]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:68E27EF3-CB0B-4051-8D0D-E00E7665799C
[ThaliCore] Session.startOutputStream(with:) peer:68E27EF3-CB0B-4051-8D0D-E00E7665799C
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:57 [1, 3, 7, 29, 57]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=1 "Operation not permitted" UserInfo={NSLocalizedDescription=Operation not permitted, NSLocalizedFailureReason=Error in c,onnect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:57
,[ThaliCore] VirtualSocket.closeStreams() vsID:57
,[ThaliCore] VirtualSocket exited RunLoop vsID:57
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket.deinit vsID:57 [1, 3, 7, 29]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:68E27EF3-CB0B-4051-8D0D-E00E7665799C
[ThaliCore] Session.startOutputStream(with:) peer:68E27EF3-CB0B-4051-8D0D-E00E7665799C
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:58 [1, 3, 7, 29, 58]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=0 "Undefined error: 0" UserInfo={NSLocalizedDescription=Undefined error: 0, NSLocalizedFailureReason=Error in connect() f,unction})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:58
[ThaliCore] VirtualSocket.closeStreams() vsID:58
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:58
,[ThaliCore] VirtualSocket.deinit vsID:58 [1, 3, 7, 29]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:53FC0754-967F-4DFA-92BF-B582F6BBCA26
[ThaliCore] Session.startOutputStream(with:) peer:53FC0754-967F-4DFA-92BF-B582F6BBCA26
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:59 [1, 3, 7, 29, 59]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=0 "Undefined error: 0" UserInfo={NSLocalizedDescription=Undefined error: 0, NSLocalizedFailureReason=Error in connect() f,unction})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:59
[ThaliCore] VirtualSocket.closeStreams() vsID:59
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:59
[ThaliCore] VirtualSocket.deinit vsID:59 [1, 3, 7, 29]
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:AB619F55-D26A-4861-90D3-606452E7D484
[ThaliCore] Advertiser: session connected Peer(uuid: "72682503-3E6C-4AF3-B364-3A3C1540F4CE", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:AB619F55-D26A-4861-90D3-606452E7D484 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:809FFB37-9982-4C97-A2BF-0029EAC1537F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "809FFB37-9982-4C97-A2BF-0029EAC1537F", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:FE28E071-97B0-472F-81FD-46A648C78A9F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FE28E071-97B0-472F-81FD-46A648C78A9F", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:,) found peer:83431272-1D7E-45BE-9C4D-076F715AA398:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "83431272-1D7E-45BE-9C4D-076F715AA398", generation: 0)
2017-07-21 06:44:11 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"809FFB37-9982-4C97-A2BF-0029EAC1537F","generation":0}]'
2017-07-21 06:44:11 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIden,tifier":"809FFB37-9982-4C97-A2BF-0029EAC1537F","generation":0}'
2017-07-21 06:44:11 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"FE28E071-97B0-472F-81FD-46A648C78A9F","generation":0}]'
2017-07-21 06:44:11 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"FE28E071-97B0-472F-81FD-46A648C78A9F","generation":0}'
2017-07-21 06:44:11 - DEBUG thaliMobileN,ativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"83431272-1D7E-45BE-9C4D-076F715AA398","generation":0}]'
2017-07-21 06:44:11 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"83431272-1D7E-45BE-9C4D-076F715AA398","generation":0}'
,2017-07-21 06:44:11 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"809FFB37-9982-4C97-A2BF-0029EAC1537F","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-21 06:44:11 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"809FFB37-9982-4C97-A2BF-0029EAC1537F","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-21 06:44:11 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"FE28E071-97B0-472F-81FD-46A648C78A9F","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-21 06:44:11 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"FE28E071-97B0-472F-81FD-46A648C78A9F","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-21 06:44:11 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"83431272-1D7E-45BE-9C,4D-076F715AA398","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-21 06:44:11 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"83431272-1D7E-45BE-9C4D-076F715AA398","connectionType":"MPCF","peerAvail,able":true,"generation":0,"newAddressPort":false}'
2017-07-21 06:44:11 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 809FFB37-9982-4C97-A2BF-0029EAC1537F (syncValue: 7)'
2017-07-21 06:44:11 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "809FFB37-9982-4C97-A2BF-0029EAC1537F", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) P,eer(uuid: "809FFB37-9982-4C97-A2BF-0029EAC1537F", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:809FFB37-9982-4C97-A2BF-0029EAC1537F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:,)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B4FF2BEA-7864-4B7F-9E73-4EB43842BCC7:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B4FF2BEA-7864-4B7F-9E73-4EB43842BCC7", generation: 0)
,2017-07-21 06:44:11 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"B4FF2BEA-7864-4B7F-9E73-4EB43842BCC7","generation":0}]'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:72682503-3E6C-4AF3-B364-3A3C1540F4CE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "72682503-3E6C-4AF3-B364-3A3C1540F4CE", generation: 0)
2017-07-21 06:44:11 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"B4FF2BEA-7864-4B7F-9E73-4EB43842BCC7","generation":0}'
,2017-07-21 06:44:11 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"B4FF2BEA-7864-4B7F-9E73-4EB43842BCC7","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 06:44:11 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"B4FF2BEA-7864-4B7F-9E73-4EB43842BCC7","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:23B7BBA8-16B5-423D-BF5D-94DBC2506C9D
[ThaliCore] Session.session(_:peer:didChange:) peer:23B7BBA8-16B5-423D-BF5D-94DBC2506C9D state: notConnected -> connecting
[ThaliCore] Advertis,er: session connected Peer(uuid: "72682503-3E6C-4AF3-B364-3A3C1540F4CE", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:809FFB37-9982-4C97-A2BF-0029EAC1537F:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:AB619F55-D26A-4861-90D3-606452E7D484
,[ThaliCore] Session.session(_:peer:didChange:) peer:AB619F55-D26A-4861-90D3-606452E7D484 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:AB619F55-D26A-4861-90D3-606452E7D484
[ThaliCore] Session.startOutputStream(with:) peer:AB619F55-D26A-4861-90D3-606452E7D484
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6,0 [1, 3, 7, 29, 60]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:FE28E071-97B0-472F-81FD-46A648C78A9F:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "FE28E071-97B0-472F-81FD-46A648C78A9F", generation: 0)
[ThaliCore] BrowserRelay.closeRelay() state:connec,ted
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:55637
[ThaliCore] Session.disconnect() peer:FE28E071-97B0-472F-81FD-46A648C78A9F:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[,ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:FE28E071-97B0-472F-81FD-46A648C78A9F:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "FE28E071-97B0-472F-81FD-46A648C78A9F", generation: 0) relay removed
[ThaliCore] BrowserRelay.deinit
,2017-07-21 06:44:14 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"FE28E071-97B0-472F-81FD-46A648C78A9F","generation":0}]'
,2017-07-21 06:44:14 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"FE28E071-97B0-472F-81FD-46A648C78A9F","generation":0}'
,2017-07-21 06:44:14 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"FE28E071-97B0-472F-81FD-46A648C78A9F","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-21 06:44:14 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"FE28E071-97B0-472F-81FD-46A648C78A9F","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-21 06:44:14 - WARN thaliNotificationClient: 'peer is not available'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:60
[ThaliCore] VirtualSocket.closeStreams() vsID:60
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:,60
[ThaliCore] VirtualSocket.deinit vsID:60 [1, 3, 7, 29]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRel,ay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:AB619F55-D26A-4861-90D3-606452E7D484
[ThaliCore] Session.startOutputStream(with:) peer:AB619F55-D26A-4861-90D3-606452E7D484
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:61 [1, 3, 7, 29, 61]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:61
[ThaliCore] VirtualSocket.closeStreams() vsID:61
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:,61
[ThaliCore] VirtualSocket.deinit vsID:61 [1, 3, 7, 29]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRel,ay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:23B7BBA8-16B5-423D-BF5D-94DBC2506C9D
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:809FFB37-9982-4C97-A2BF-0029EAC1537F:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:23B7BBA8-16B5-423D-BF5D-94DBC2506C9D state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:809FFB37-9982-4C97-A2BF-0029EAC1537F:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "809FFB37-9982-4C97-A2BF-0029EAC1537F", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:55678
,2017-07-21 06:44:14 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"7","error":null,"portNumber":55678}'
,2017-07-21 06:44:14 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for FE28E071-97B0-472F-81FD-46A648C78A9F (syncValue: 8)'
,2017-07-21 06:44:14 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "FE28E071-97B0-472F-81FD-46A648C78A9F", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FE28E071-97B0-472F-81FD-46A648C78A9F", generation: 0)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:23B7BBA8-16B5-423D-BF5D-94DBC2506C9D
[ThaliCore] Session.startOutputStream(with:) peer:23B7BBA8-16B5-423D-BF5D-94DBC2506C9D
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:62 [1, 3, 7, 29, 62]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
,2017-07-21 06:44:14 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"8","error":"Peer is unavailable","portNumber":null}'
,2017-07-21 06:44:14 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"FE28E071-97B0-472F-81FD-46A648C78A9F","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-21 06:44:14 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"FE28E071-97B0-472F-81FD-46A648C78A9F","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 06:44:14 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 83431272-1D7E-45BE-9C4D-076F715AA398 (syncValue: 9)'
,2017-07-21 06:44:14 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "83431272-1D7E-45BE-9C4D-076F715AA398", generation: 0) found active relay
,2017-07-21 06:44:14 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"9","error":null,"portNumber":55501}'
,2017-07-21 06:44:14 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for B4FF2BEA-7864-4B7F-9E73-4EB43842BCC7 (syncValue: 10)'
,2017-07-21 06:44:14 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B4FF2BEA-7864-4B7F-9E73-4EB43842BCC7", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B4FF2BEA-7864-4B7F-9E73-4EB43842BCC7", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B4FF2BEA-7864-4B7F-9E73-4EB43842BCC7:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 06:44:14 - DEBUG thaliPeerPoolDefault: 'Got err   Peer is unavailable'
,2017-07-21 06:44:14 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"FE28E071-97B0-472F-81FD-46A648C78A9F","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:809FFB37-9982-4C97-A2BF-0029EAC1537F:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:809FFB37-9982-4C97-A2BF-0029EAC1537F:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:63 [1, 3, 7, 29, 62, 63]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:83431272-1D7E-45BE-9C4D-076F715AA398:0
,2017-07-21 06:44:14 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"FE28E071-97B0-472F-81FD-46A648C78A9F","peerAvailable":true,"portNumber":null,"recreated":true}'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:83431272-1D7E-45BE-9C4D-076F715AA398:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:64 [1, 3, 7, 29, 62, 63, 64]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vs,ID:63
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:63
[ThaliCore] VirtualSocket.deinit vsID:63 [1, 3, 7, 29, 62, 64]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:809FFB37-9982-4C97-A2BF-0029EAC1537F:0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:62
,[ThaliCore] VirtualSocket.closeStreams() vsID:62
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:62
[ThaliCore] VirtualSocket.deinit vsID:62 [1, 3, 7, 29, 64]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:809FFB37-9982-4C97-A2BF-0029EAC1537F:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:65 [1, 3, 7, 29, 64, 65]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:23B7BBA8-16B5-423D-BF5D-94DBC2506C9D
[ThaliCore] Session.startOutputStream(with:) peer:23B7BBA8-16B5-423D-BF5D-94DBC2506C9D
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:66 [1, 3, 7, 29, 64, 65, 66]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-21 06:44:15 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  404 no_db_file'
,2017-07-21 06:44:15 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: no_db_file  and it caused us to complete'
,ok 868 error should be 'no_db_file'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:65
[ThaliCore] Browse,rRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:65
[ThaliCore] VirtualSocket.deinit vsID:65 [1, 3, 7, 29, 64, 66]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:66
[ThaliCore] VirtualSocket.closeStreams() vsID:66
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:64
[ThaliCore] VirtualSocket.closeStreams() vsID:64
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:64
[ThaliCore] VirtualSocket.deinit vsID:64 [1, 3, 7, 29, 66]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-21 06:44:15 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] Session.session(_:peer:didChange:) peer:B4FF2BEA-7864-4B7F-9E73-4EB43842BCC7:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:68E27EF3-CB0B-4051-8D0D-E00E7665799C
[ThaliCore] Session.startOutputStream(with:) peer:68E27EF3-CB0B-4051-8D0D-E00E7665799C
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6,7 [1, 3, 7, 29, 66, 67]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=1 "Operation not permitted" UserInfo={NSLocalizedDescription=Operation not permitted, NSLocalizedFailureReason=Error in c,onnect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:67
[ThaliCore] VirtualSocket.closeStreams() vsID:67
[ThaliCore] Advertiser,Relay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:67
[ThaliCore] VirtualSocket.deinit vsID:67 [1, 3, 7, 29, 66]
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B4FF2BEA-7864-4B7F-9E73-4EB43842BCC7:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:B4FF2BEA-7864-4B7F-9E73-4EB43842BCC7:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "B4FF2BEA-7864-4B7F-9E73-4EB43842BCC7", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:55687
2017-07-21 06:44:17 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"10","error":null,"portNumber":55687}'
,[ThaliCore] BrowserManager.disconnect peer:FE28E071-97B0-472F-81FD-46A648C78A9F
2017-07-21 06:44:17 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 83431272-1D7E-45BE-9C4D-076F715AA398 (syncValue: 11)'
2017-07-21 06:44:17 - DEBUG thaliMobileN,ativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "83431272-1D7E-45BE-9C4D-076F715AA398", generation: 0) found active relay
2017-07-21 06:44:17 - DEBUG thaliMobileNativeWrapp,er: 'multiConnectResolved: {"syncValue":"11","error":null,"portNumber":55501}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B4FF2BEA-7864-4B7F-9E73-4EB43842BCC7:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:83431272-1D7E-45BE-9C4D-076F715AA398:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B4FF2BEA-7864-4B7F-9E73-4EB43842BCC7:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:68 [1, 3, 7, 29, 66, 68]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:83431272-1D7E-45BE-9C4D-076F715AA398:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:69 [1, 3, 7, 29, 66, 68, 69]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:69
,[ThaliCore] VirtualSocket.closeStreams() vsID:69
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:69
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisc,onnectHandler
[ThaliCore] VirtualSocket.deinit vsID:69 [1, 3, 7, 29, 66, 68]
,2017-07-21 06:44:18 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:53FC0754-967F-4DFA-92BF-B582F6BBCA26
,[ThaliCore] Session.startOutputStream(with:) peer:53FC0754-967F-4DFA-92BF-B582F6BBCA26
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:70 [1, 3, 7, 29, 66, 68, 70]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=1 "Operation not permitted" UserInfo={NSLocalizedDescription=Operation not permitted, NSLocalizedFailureReason=Error in connect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:70
[ThaliCore] VirtualSocket.closeStreams() vsID:70
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:70
,[ThaliCore] VirtualSocket.deinit vsID:70 [1, 3, 7, 29, 66, 68]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vs,ID:68
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:68
,[ThaliCore] VirtualSocket.deinit vsID:68 [1, 3, 7, 29, 66]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B4FF2BEA-7864-4B7F-9E73-4EB43842BCC7:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B4FF2BEA-7864-4B7F-9E73-4EB43842BCC7:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:71 [1, 3, 7, 29, 66, 71]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-21 06:44:18 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  404 no_db_file'
,2017-07-21 06:44:18 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: no_db_file  and it caused us to complete'
,ok 869 error should be 'no_db_file'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vs,ID:71
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:71
,[ThaliCore] VirtualSocket.deinit vsID:71 [1, 3, 7, 29, 66]
,2017-07-21 06:44:18 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 83431272-1D7E-45BE-9C4D-076F715AA398 (syncValue: 12)'
,2017-07-21 06:44:18 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "83431272-1D7E-45BE-9C4D-076F715AA398", generation: 0) found active relay
,2017-07-21 06:44:18 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"12","error":null,"portNumber":55501}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:83431272-1D7E-45BE-9C4D-076F715AA398:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:83431272-1D7E-45BE-9C4D-076F715AA398:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:72 [1, 3, 7, 29, 66, 72]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:72
[ThaliCore] VirtualSocket.closeStreams() vsID:72
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:72
,[ThaliCore] VirtualSocket.deinit vsID:72 [1, 3, 7, 29, 66]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-21 06:44:18 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:68E27EF3-CB0B-4051-8D0D-E00E7665799C
[ThaliCore] Session.startOutputStream(with:) peer:68E27EF3-CB0B-4051-8D0D-E00E7665799C
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:73 [1, 3, 7, 29, 66, 73]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=0 "Undefined error: 0" UserInfo={NSLocalizedDescription=Undefined error: 0, NSLocalizedFailureReason=Error in connect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:73
[ThaliCore] VirtualSocket.closeStreams() vsID:73
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:73
,[ThaliCore] VirtualSocket.deinit vsID:73 [1, 3, 7, 29, 66]
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:83431272-1D7E-45BE-9C4D-076F715AA398:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "83431272-1D7E-45BE-9C4D-076F715AA398", generation: 0)
,[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:55501
,[ThaliCore] Session.disconnect() peer:83431272-1D7E-45BE-9C4D-076F715AA398:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:83431272-1D7E-45BE-9C4D-076F715AA398:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "83431272-1D7E-45BE-9C4D-076F715AA398", generation: 0) relay removed
[ThaliCore] BrowserRelay.deinit
,2017-07-21 06:44:18 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"83431272-1D7E-45BE-9C4D-076F715AA398","generation":0}]'
,2017-07-21 06:44:18 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"83431272-1D7E-45BE-9C4D-076F715AA398","generation":0}'
,2017-07-21 06:44:18 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"83431272-1D7E-45BE-9C4D-076F715AA398","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-21 06:44:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"83431272-1D7E-45BE-9C4D-076F715AA398","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-21 06:44:18 - WARN thaliNotificationClient: 'peer is not available'
,[ThaliCore] Session.session(_:peer:didChange:) peer:53FC0754-967F-4DFA-92BF-B582F6BBCA26 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "439F642B-C473-4E6B-8743-D49D9B8F5AA6", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:68E27EF3-CB0B-4051-8D0D-E00E7665799C
[ThaliCore] Sessio,n.deinit peer:68E27EF3-CB0B-4051-8D0D-E00E7665799C
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:72682503-3E6C-4AF3-B364-3A3C1540F4CE
,2017-07-21 06:44:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 06:44:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"809FFB37-9982-4C97-A2BF-0029EAC1537F","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-21 06:44:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"B4FF2BEA-7864-4B7F-9E73-4EB43842BCC7","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 06:44:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 06:44:18 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
,2017-07-21 06:44:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,[ThaliCore] VirtualSocket exited RunLoop vsID:66
[ThaliCore] VirtualSocket.deinit vsID:66 [1, 3, 7, 29]
,2017-07-21 06:44:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:44:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:44:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 870 passed
,# teardown
,# setup
,# compareBufferArrays
,ok 871 should throw
,ok 872 should throw
,ok 873 (unnamed assert)
,ok 874 (unnamed assert)
,ok 875 (unnamed assert)
,ok 876 (unnamed assert)
,ok 877 (unnamed assert)
,# teardown
,# setup
,# Call start twice and get error
,2017-07-21 06:44:21 - DEBUG thaliMobileNativeTestUtils: 'Test timeout reached. Restarting test.'
not ok 878 Too many test retries!
  ---
    operator: fail
  ...
2017-07-21 06:44:21 - ERROR CoordinatedClient: 'unexpected result, error: 'Error: Too man,y test retries!', stack: 'assert@/private/var/containers/Bundle/Application/B9D1774A-DA75-4C08-98B8-DB88E3B59AC6/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:203:54
bound@/private/var/containers/Bundle/Application/B9D1774A-DA75-4C08-98B8-DB88E3B,59AC6/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:62:28
Test.prototype.fail@/private/var/containers/Bundle/Application/B9D1774A-DA75-4C08-98B8-DB88E3B59AC6/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:268:1
bound@/private/var/contain,ers/Bundle/Application/B9D1774A-DA75-4C08-98B8-DB88E3B59AC6/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:62:28
tryToConnect/testTimeout<@/private/var/containers/Bundle/Application/B9D1774A-DA75-4C08-98B8-DB88E3B59AC6/ThaliTest.app/www/jxcore/li,b,/thaliMobileNativeTestUtils.js:420:9
$9@timers.js:120:1', original result: '{"id":8,"ok":false,"name":"Too many test retries!","operator":"fail","error":{}}''
,ok 879 should throw
,# teardown
,# setup
,# Start and make sure it runs
,# teardown
,# setup
,# Make sure getTimeWhenRun is right after start
,ok 880 (unnamed assert)
,# teardown
,# setup
,# Make sure getTimeWhenRun is -1 after function is called
,ok 881 should be equal
# teardown
,# setup
,# Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running
,ok 882 should be equal
ok 883 should be equal
ok 884 should throw
,# teardown
,# setup
,# Test TransientState
,ok 885 should throw
,ok 886 should throw
ok 887 should be equal
ok 888 should be equal
ok 889 should be equal
ok 890 should be equal
ok 891 (unnamed assert)
ok 892 (unnamed assert)
,# teardown
,# setup
,# No peers and empty database
,ok 893 verify failed
,ok 894 constructor called once
,ok 895 constructor called with right args
,ok 896 match start arg
,ok 897 start called once
,ok 898 stop called once
,ok 899 stop after start
,# teardown
,# setup
,# One peer and empty DB
,2017-07-21 06:44:25 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 900 verify failed
,ok 901 constructor called once
,ok 902 constructor called with right args
,ok 903 match start arg
,ok 904 start called once
,ok 905 stop called once
,ok 906 stop after start
,# teardown
,# setup
,# One peer with _Local set behind current seq
,2017-07-21 06:44:25 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 907 verify failed
,ok 908 constructor called once
,ok 909 constructor called with right args
,ok 910 match start arg
,ok 911 start called once
,ok 912 stop called once
,ok 913 stop after start
,# teardown
,# setup
,# One peer with _Local set equal to current seq
,2017-07-21 06:44:26 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 914 verify failed
,ok 915 constructor called once
,ok 916 constructor called with right args
,ok 917 match start arg
,ok 918 start called once
,ok 919 stop called once
,ok 920 stop after start
,# teardown
,# setup
,# One peer with _Local set ahead of current seq (and no this should not happen)
,2017-07-21 06:44:27 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 921 verify failed
,ok 922 constructor called once
,ok 923 constructor called with right args
,ok 924 match start arg
,ok 925 start called once
,ok 926 stop called once
,ok 927 stop after start
,# teardown
,# setup
,# Three peers, one not in DB, one behind and one ahead
,2017-07-21 06:44:28 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 928 verify failed
ok 929 constructor called once
ok 930 constructor called with right args
,ok 931 match start arg
,ok 932 start called once
,ok 933 stop called once
,ok 934 stop after start
,# teardown
,# setup
,# More than maximum peers, make sure we only send maximum allowed
,2017-07-21 06:44:29 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 935 verify failed
,ok 936 constructor called once
,ok 937 constructor called with right args
,ok 938 match start arg
,ok 939 start called once
,ok 940 stop called once
ok 941 stop after start
,# teardown
,# setup
,# two peers with empty DB, update the doc
,2017-07-21 06:44:30 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,2017-07-21 06:44:30 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 942 verify failed
,ok 943 constructor called once
,ok 944 constructor called with right args
,ok 945 last start before stop
,ok 946 empty first start
,ok 947 full second start
,ok 948 only 2 timers
,# teardown
,# setup
,# add doc and make sure tokens refresh when they expire
,2017-07-21 06:44:31 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,2017-07-21 06:44:31 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,2017-07-21 06:44:31 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
ok 949 verify failed
ok 950 constructor called once
ok 951 constructor called with right args
ok 952 start before stop
ok 953 We got at least 3 calls to start
ok 954 at least 3
ok 955 default 1
ok 956 1 run
ok 957 default 2
,ok 958 2 run
ok 959 default 3
# teardown
,# setup
,# start and stop and start and stop
,ok 960 start out null
,2017-07-21 06:44:32 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 961 back to null
,2017-07-21 06:44:32 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 962 still null
,ok 963 verify failed
,ok 964 constructor called once
,ok 965 constructor called with right args
,ok 966 first start before first stop
,ok 967 first stop before second start
,ok 968 second start before second stop
,# teardown
,# setup
,# two identical starts in a row
,2017-07-21 06:44:32 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 969 verify failed
,ok 970 constructor called once
,ok 971 constructor called with right args
,ok 972 (unnamed assert)
,# teardown
,# setup
,# two different starts in a row
,2017-07-21 06:44:33 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 973 verify failed
,ok 974 constructor called once
,ok 975 constructor called with right args
,ok 976 (unnamed assert)
,ok 977 (unnamed assert)
,# teardown
,# setup
,# two stops and a start and two stops
,2017-07-21 06:44:34 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 978 verify failed
,ok 979 constructor called once
,ok 980 constructor called with right args
,ok 981 start before stop
,# teardown
,# setup
,# we properly enqueue requests so no then needed
,2017-07-21 06:44:35 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 982 verify failed
,ok 983 constructor called once
,ok 984 constructor called with right args
,ok 985 start before stop
,# teardown
,# setup
,# test calculateSeqPointKeyId
,ok 986 should be equal
ok 987 should be equal
,# teardown
,# setup
,# #_doImmediateSeqUpdate - server is not there
,2017-07-21 06:44:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 06:44:36 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}'
ok 988 Got right error
# teardown
,2017-07-21 06:44:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - server accepts & closes connection
,2017-07-21 06:44:36 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNRESET","status":500}'
ok 989 Got socket hang up
# teardown
,2017-07-21 06:44:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - server always returns 500
,2017-07-21 06:44:37 - DEBUG localSeqManager: 'Got an error trying to update seq []'
,ok 990 Got 500 as expected
,# teardown
,2017-07-21 06:44:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - create new seq doc
,ok 991 should be equal
,ok 992 revs are equal
,# teardown
,2017-07-21 06:44:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - doc exists, need to get rev and update
,ok 993 should be equal
,ok 994 revs are equal
,# teardown
,2017-07-21 06:44:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - update seq three times
,ok 995 should be equal
ok 996 revs are equal
,ok 997 should be equal
,ok 998 revs are equal
,ok 999 should be equal
,ok 1000 revs are equal
,# teardown
,2017-07-21 06:44:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - rev got changed under us
,(node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
,Trace: 
    at $3.prototype.trace@console.js:139:8
    at addListener@events.js:140:1
    at module.exports@/private/var/containers/Bundle/Application/B9D1774A-DA75-4C08-98B8-DB88E3B59AC6/ThaliTest.app/www/jxcore/node_modules/pouchdb-all-dbs/lib/index.j,s:82:3
    at module.exports/<.start/<@/private/var/containers/Bundle/Application/B9D1774A-DA75-4C08-98B8-DB88E3B59AC6/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/lib/index.js:143:9
    at tryCatcher@/private/var/containers/Bundle/Application/B,9D1774A-DA75-4C08-98B8-DB88E3B59AC6/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/util.js:16:16
    at module.exports/Promise.prototype._settlePromiseFromHandler@/private/var/containers/Bundle/Application/B9D1774A-,DA75-4C08-98B8-DB88E3B59AC6/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:504:13
,2017-07-21 06:44:43 - DEBUG localSeqManager: 'Got an error trying to update seq {"error":"conflict","reason":"Document update conflict","name":"conflict","status":409,"message":"Document update conflict"}'
,ok 1001 Our rev is old so we should fail
,# teardown
,2017-07-21 06:44:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - fail if stop is called
,ok 1002 confirm stop caused failure
,(node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
Trace: 
    at $3.prototype.trace@console.js:139:8
    at addListener@events.js:140:1
    at module.exports@/private/var/co,ntainers/Bundle/Application/B9D1774A-DA75-4C08-98B8-DB88E3B59AC6/ThaliTest.app/www/jxcore/node_modules/pouchdb-all-dbs/lib/index.js:57:3
    at module.exports/<.start/<@/private/var/containers/Bundle/Application/B9D1774A-DA75-4C08-98B8-DB88E3B59AC6/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/lib/index.js:143:9
    at tryCatcher@/private/var/containers/Bundle/Application/B9D1774A-DA75-4C08-98B8-DB88E3B59AC6/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/uti,l.js:16:16
    at module.exports/Promise.prototype._settlePromiseFromHandler@/private/var/containers/Bundle/Application/B9D1774A-DA75-4C08-98B8-DB88E3B59AC6/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:,504:13
,# teardown
,2017-07-21 06:44:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - stop after get but before put fails right
,2017-07-21 06:44:44 - DEBUG localSeqManager: 'Got an error trying to update seq {"onPut":true}'
,ok 1003 stop caused us to fail
,ok 1004 We specifically failed on a stop before put
,# teardown
,2017-07-21 06:44:45 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - fail if stop is called
,ok 1005 failed due to stop
,ok 1006 failed due to stop
,# teardown
,2017-07-21 06:44:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - set seq for first time
,ok 1007 should be equal
,# teardown
,2017-07-21 06:44:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - Fail on bad seq value
,2017-07-21 06:44:49 - DEBUG localSeqManager: 'Got a bad seq, submitted seq 9, _nextSeqValueToSend: 10'
,ok 1008 Expected bad seq error
,# teardown
,2017-07-21 06:44:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - do we cancel timer properly on an immediate?
,ok 1009 Different promises
,ok 1010 Timer was cancelled
,ok 1011 should be equal
,# teardown
,2017-07-21 06:44:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - do we wait for blocked update
,ok 1012 One go and one blocked
,ok 1013 All blocked
,ok 1014 Still blocked
,ok 1015 should be equal
,# teardown
,2017-07-21 06:44:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - test that we wait long enough
,ok 1016 We waited long enough
,ok 1017 should be equal
,# teardown
,2017-07-21 06:44:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - test that we pick up new sequences while we wait
,ok 1018 Should have gotten same timer promise
,ok 1019 Still same timer promise
,ok 1020 We waited long enough
,ok 1021 should be equal
,# teardown
,2017-07-21 06:44:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Coordinated seq test
,2017-07-21 06:45:00 - DEBUG CoordinatedClient: 'test was skipped, name: 'Coordinated seq test''
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:45:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:45:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,# setup
,# test thali manager spies
,2017-07-21 06:45:01 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
,2017-07-21 06:45:01 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
,2017-07-21 06:45:01 - DEBUG thaliManager: 'creating express pouchdb instance'
,ok 1022 expressPouchDB was called once
ok 1023 expressPouchDB was called with 2 arguments
,ok 1024 expressPouchDB was called with 'PouchDB' as 1-st argument
,ok 1025 expressPouchDB was called with 'expressPouchDB options' as 2-st argument
ok 1026 PouchDB was called once
,ok 1027 PouchDB was called with 1 arguments
,ok 1028 PouchDB was called with 'dbName' as 1-st argument
,ok 1029 ThaliSendNotificationBasedOnReplication was called once
,ok 1030 ThaliSendNotificationBasedOnReplication was called with 4 arguments
,ok 1031 ThaliSendNotificationBasedOnReplication was called with 'express.Router instance' as 1-st argument
,ok 1032 ThaliSendNotificationBasedOnReplication was called with 'ecdhForLocalDevice' as 2-st argument
,ok 1033 ThaliSendNotificationBasedOnReplication was called with 'thaliConfig.BEACON_MILLISECONDS_TO_EXPIRE' as 3-st argument
,ok 1034 ThaliSendNotificationBasedOnReplication was called with 'PouchDB instance' as 4-st argument
,ok 1035 ThaliPullReplicationFromNotification was called once
,ok 1036 ThaliPullReplicationFromNotification was called with 4 arguments
,ok 1037 ThaliPullReplicationFromNotification was called with 'PouchDB' as 1-st argument
,ok 1038 ThaliPullReplicationFromNotification was called with 'dbName' as 2-st argument
,ok 1039 ThaliPullReplicationFromNotification was called with 'ThaliPeerPoolInterface instance' as 3-st argument
,ok 1040 ThaliPullReplicationFromNotification was called with 'ecdhForLocalDevice' as 4-st argument
,ok 1041 Salti was called once
,ok 1042 Salti was called with 4 arguments
,ok 1043 Salti was called with 'dbName' as 1-st argument
,ok 1044 Salti was called with 'acl' as 2-st argument
,ok 1045 Salti was called with 'thaliIdCallback' as 3-st argument
,ok 1046 Salti was called with 'options' as 4-st argument
,2017-07-21 06:45:01 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
,2017-07-21 06:45:01 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-07-21 06:45:01 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-07-21 06:45:01 - DEBUG thaliMobileNativeWrapper: 'listening 55763'
2017-07-21 06:45:01 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:34AD929A-702B-427D-9121-5B3C4BFB8CBB
,[ThaliCore] Browser.startListening
,2017-07-21 06:45:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 06:45:01 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "F89D86AD-94E3-4169-B6C8-0BE6593C06D1", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:F89D86AD-94E3-4169-B6C8-0BE6593C06D1
,2017-07-21 06:45:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 06:45:01 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
,ok 1047 ThaliMobile.start was called once
,ok 1048 ThaliMobile.start was called with 3 arguments
,ok 1049 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
,ok 1050 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
,ok 1051 ThaliMobile.start was called with 'networkType' as 3-st argument
,ok 1052 ThaliMobile.startListeningForAdvertisements was called once
,ok 1053 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
,ok 1054 ThaliMobile.startUpdateAdvertisingAndListening was called once
,ok 1055 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
,ok 1056 ThaliSendNotificationBasedOnReplication.prototype.start was called once
,ok 1057 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
,ok 1058 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
,ok 1059 ThaliPullReplicationFromNotification.prototype.start was called once
,ok 1060 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
,ok 1061 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
,2017-07-21 06:45:01 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:F89D86AD-94E3-4169-B6C8-0BE6593C06D1
,2017-07-21 06:45:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 06:45:01 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})'
2017-07-21 06:45:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 06:45:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:45:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 06:45:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 1062 ThaliMobile.stop was called once
,ok 1063 ThaliMobile.stop was called with 0 arguments
,ok 1064 ThaliSendNotificationBasedOnReplication.prototype.stop was called once
,ok 1065 ThaliSendNotificationBasedOnReplication.prototype.stop was called with 0 arguments
,ok 1066 ThaliPullReplicationFromNotification.prototype.stop was called once
,ok 1067 ThaliPullReplicationFromNotification.prototype.stop was called with 0 arguments
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 06:45:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:45:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,# teardown
,# setup
,# test thali manager multiple starts and stops
,2017-07-21 06:45:02 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
,2017-07-21 06:45:02 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
,2017-07-21 06:45:02 - DEBUG thaliManager: 'creating express pouchdb instance'
,ok 1068 expressPouchDB was called once
ok 1069 expressPouchDB was called with 2 arguments
,ok 1070 expressPouchDB was called with 'PouchDB' as 1-st argument
,ok 1071 expressPouchDB was called with 'expressPouchDB options' as 2-st argument
ok 1072 PouchDB was called once
,ok 1073 PouchDB was called with 1 arguments
ok 1074 PouchDB was called with 'dbName' as 1-st argument
,ok 1075 ThaliSendNotificationBasedOnReplication was called once
,ok 1076 ThaliSendNotificationBasedOnReplication was called with 4 arguments
,ok 1077 ThaliSendNotificationBasedOnReplication was called with 'express.Router instance' as 1-st argument
,ok 1078 ThaliSendNotificationBasedOnReplication was called with 'ecdhForLocalDevice' as 2-st argument
,ok 1079 ThaliSendNotificationBasedOnReplication was called with 'thaliConfig.BEACON_MILLISECONDS_TO_EXPIRE' as 3-st argument
,ok 1080 ThaliSendNotificationBasedOnReplication was called with 'PouchDB instance' as 4-st argument
,ok 1081 ThaliPullReplicationFromNotification was called once
,ok 1082 ThaliPullReplicationFromNotification was called with 4 arguments
,ok 1083 ThaliPullReplicationFromNotification was called with 'PouchDB' as 1-st argument
,ok 1084 ThaliPullReplicationFromNotification was called with 'dbName' as 2-st argument
,ok 1085 ThaliPullReplicationFromNotification was called with 'ThaliPeerPoolInterface instance' as 3-st argument
,ok 1086 ThaliPullReplicationFromNotification was called with 'ecdhForLocalDevice' as 4-st argument
,ok 1087 Salti was called once
,ok 1088 Salti was called with 4 arguments
,ok 1089 Salti was called with 'dbName' as 1-st argument
,ok 1090 Salti was called with 'acl' as 2-st argument
,ok 1091 Salti was called with 'thaliIdCallback' as 3-st argument
,ok 1092 Salti was called with 'options' as 4-st argument
,2017-07-21 06:45:02 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
,2017-07-21 06:45:02 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-07-21 06:45:02 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-07-21 06:45:02 - DEBUG thaliMobileNativeWrapper: 'listening 55765'
2017-07-21 06:45:02 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:6CC477D7-BAFF-438D-B54F-C571F3DD3053
,[ThaliCore] Browser.startListening
,2017-07-21 06:45:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 06:45:02 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "364A28DF-78D5-4CC0-9945-BD9BA9A26712", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:364A28DF-78D5-4CC0-9945-BD9BA9A26712
,2017-07-21 06:45:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 06:45:02 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
,ok 1093 ThaliMobile.start was called once
,ok 1094 ThaliMobile.start was called with 3 arguments
,ok 1095 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
,ok 1096 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
,ok 1097 ThaliMobile.start was called with 'networkType' as 3-st argument
,ok 1098 ThaliMobile.startListeningForAdvertisements was called once
,ok 1099 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
,ok 1100 ThaliMobile.startUpdateAdvertisingAndListening was called once
,ok 1101 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
,ok 1102 ThaliSendNotificationBasedOnReplication.prototype.start was called once
,ok 1103 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
,ok 1104 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
,ok 1105 ThaliPullReplicationFromNotification.prototype.start was called once
,ok 1106 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
,ok 1107 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
,2017-07-21 06:45:02 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:364A28DF-78D5-4CC0-9945-BD9BA9A26712
,2017-07-21 06:45:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 06:45:02 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})',
2017-07-21 06:45:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 06:45:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:45:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 06:45:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 06:45:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:45:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 1108 ThaliMobile.stop was called once
ok 1109 ThaliMobile.stop was called with 0 arguments
,ok 1110 ThaliSendNotificationBasedOnReplication.prototype.stop was called once
,ok 1111 ThaliSendNotificationBasedOnReplication.prototype.stop was called with 0 arguments
,ok 1112 ThaliPullReplicationFromNotification.prototype.stop was called once
,ok 1113 ThaliPullReplicationFromNotification.prototype.stop was called with 0 arguments
,2017-07-21 06:45:02 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
,2017-07-21 06:45:02 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-07-21 06:45:02 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-07-21 06:45:02 - DEBUG thaliMobileNativeWrapper: 'listening 55767'
,2017-07-21 06:45:02 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:7655483A-981B-4CA0-AE84-748ED475B80D
[ThaliCore] Browser.startListening
,2017-07-21 06:45:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 06:45:02 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "0992F149-F9FE-4095-8E40-D0E296271079", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:0992F149-F9FE-4095-8E40-D0E296271079
,2017-07-21 06:45:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 06:45:02 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
,2017-07-21 06:45:02 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:0992F149-F9FE-4095-8E40-D0E296271079
,2017-07-21 06:45:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 06:45:02 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})'
2017-07-21 06:45:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state,).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-21 06:45:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:45:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:45:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 06:45:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:45:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:45:02 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
,2017-07-21 06:45:02 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-07-21 06:45:02 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-07-21 06:45:02 - DEBUG thaliMobileNativeWrapper: 'listening 55769'
2017-07-21 06:45:02 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:BBA2BD59-016B-4B39-B8D0-61872AE6B401
[ThaliCore] Browser.startListening
,2017-07-21 06:45:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 06:45:02 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "841FE803-AE92-4174-AD20-DE49713AB951", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:841FE803-AE92-4174-AD20-DE49713AB951
,2017-07-21 06:45:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 06:45:02 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
,2017-07-21 06:45:02 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:841FE803-AE92-4174-AD20-DE49713AB951
,2017-07-21 06:45:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 06:45:02 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})',
,2017-07-21 06:45:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 06:45:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:45:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:45:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 06:45:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:45:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:45:02 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
,2017-07-21 06:45:02 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-07-21 06:45:02 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-07-21 06:45:02 - DEBUG thaliMobileNativeWrapper: 'listening 55771'
,2017-07-21 06:45:02 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:8D6758B6-4029-45B5-A0DE-B022599E230E
[ThaliCore] Browser.startListening
,2017-07-21 06:45:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 06:45:02 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "FEABE8A5-7BE0-49E2-865C-1BA0FCAEFADD", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:FEABE8A5-7BE0-49E2-865C-1BA0FCAEFADD
,2017-07-21 06:45:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 06:45:02 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
,ok 1114 ThaliMobile.start was called once
ok 1115 ThaliMobile.start was called with 3 arguments
,ok 1116 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
,ok 1117 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
,ok 1118 ThaliMobile.start was called with 'networkType' as 3-st argument
,ok 1119 ThaliMobile.startListeningForAdvertisements was called once
,ok 1120 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
,ok 1121 ThaliMobile.startUpdateAdvertisingAndListening was called once
,ok 1122 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
,ok 1123 ThaliSendNotificationBasedOnReplication.prototype.start was called once
,ok 1124 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
,ok 1125 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
,ok 1126 ThaliPullReplicationFromNotification.prototype.start was called once
,ok 1127 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
,ok 1128 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
,2017-07-21 06:45:02 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:FEABE8A5-7BE0-49E2-865C-1BA0FCAEFADD
,2017-07-21 06:45:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 06:45:02 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})'
2017-07-21 06:45:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-21 06:45:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:45:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:45:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:45:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:45:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,# teardown
,# setup
,# test write
,2017-07-21 06:45:04 - DEBUG CoordinatedClient: 'test was skipped, name: 'test write''
,# teardown
,# setup
,# test repeat write 1
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll can close even when connections open'
2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll with promise'
2017-07-21 06:45:05 - INFO, CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning set to false'
2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll works even with a server ,that is not listening yet witheatNotRunning set to true'
2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on a single db change'
2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOG,GER result: skipped - Call of multiple onCheckpointReached handlers on a single db change'
2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are in the checkpoi,n,ts plugin delay interval'
2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval'
2017-07-21 06:45:05 - INFO Coordin,atedClient: '***TEST_LOGGER result: passed - test defaultDirectory'
2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultAdapter'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueue and run in order'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueueAtTop and run backwards'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - mix enqueue and enqueueAtTop'
2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - queues handled independently'
2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueued function are always executed asynchronously'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - exceptions in the executor are properly handled'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - basic'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - another'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - skip'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - another skip'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox spy'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub override'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox mock'
2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox restore after test end'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can pass data in setup'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Correctly parses/stringifies USN'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerLost calls jxcore'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerDiscovered calls jxcore'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopListeningForAdvertisements'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startListeningForAdvertisements twice is NOT an error'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling stopListeningForAdvertisements without calling start is NOT an error'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopUpdateAdvertisingAndListening'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startUpdateAdvertisingAndListening twice is NOT an error'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call stopUpdateAdvertisingAndListening twice without start and it is not an error'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChange is called'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can connect to a remote peer'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data via parallel connections'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data securely'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift large amounts of data'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We do not emit peerAvailabilityChanged events until one of the start methods is called'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Test updating advertising and parallel data transfer'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - discoveryAdvertisingStateUpdateNonTCP is called'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - cannot call connect when start listening for advertisements is not active'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Get error when trying to double connect to a peer on Android'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect when start listening for advertisements is not active'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with illegal peerID'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiConnect properly fails on legal but non-existent peerID'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with invalid syncValue'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call disconnect with invalid peer id'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - disconnect doesn't fail on plausible but bogus peer ID'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Get same port when trying to connect multiple times on iOS'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - initial peer discovery'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 1'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 2'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - check latest peer discovery'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Set up for no peer discovery test'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - no peer discovery'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling createNativeListener directly rejects'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits incomingConnectionState'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits routerPortConnectionFailed'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server connections all up'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming stream cleans outgoing socket'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming connection cleans outgoing socket'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing outgoing socket cleans associated mux stream'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing the whole server cleans everything up'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - we can get a ton of connections and data through and still clean up the server completely'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - simulate mux failure, make sure everything is cleaned up'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - timing out the incoming connection cleans everything up'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can create servers manager'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling stop without start causes error'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can start/stop servers manager'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - starting twice resolves with listening port'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminateIncomingConnection will terminate a connection'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminate an Outgoing connection'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single local http request'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single coordinated request ios native'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Multiple local http requests'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Multiple coordinated request ios native'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startListeningForAdvertisements should fail if start not called'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if start not called'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopListeningForAdvertisements many times'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startListeningForAdvertisements many times'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startUpdateAdvertisingAndListening many times'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopAdvertisingAndListening many times'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get the network status before starting'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - error returned with bad router'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - all services are started when we call start'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - TCP Servers Manager should be null when we call start on iOS'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - all services are stopped when we call stop'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure terminateConnection is properly hooked up'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure terminateConnection is return error if we get called on iOS'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure terminateListener is properly hooked up'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure terminateListener is return error if we get called on iOS'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure we actually call kill connections properly'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire failedNativeConnection event when we get failedConnection from multiConnectConnection'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure bad PSK connections fail'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - peer changes handled from a queue'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - relaying discoveryAdvertisingStateUpdateNonTCP'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - we successfully receive and replay discoveryAdvertisingStateUpdate'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - can do HTTP requests between peers'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - can still do HTTP requests between peers with coordinator'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - calls correct starts when network changes'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test to coordinate connection cut'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can do HTTP requests after connections are cut'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - will fail bad PSK connection between peers'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We provide notification when a listener dies and we recreate it'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startListeningForAdvertisements should fail if start not called'
2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListe,ning should fail if start not called'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopListeningForAdvertisements many times'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startListeningForAdvertisements many times'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startUpdateAdvertisingAndListening many times'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopAdvertisingAndListening many times'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #start - Causing native or wifi to fail will cause a promise reject '
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #start should fail if called twice in a row'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - does not emit duplicate discoveryAdvertisingStateUpdate'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - does not send duplicate availability changes'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get the network status'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer added/removed to/from cache (native)'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer added/removed to/from cache (wifi)'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - new peer is cached'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - native available - peer with same port and different generation is cached (BLUETOOTH)'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - peer with greater generation is cached (MPCF)'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - peer with same or older generation is ignored (MPCF)'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native unavailable - new peer is ignored'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native unavailable - cached peer is removed'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - networkChanged - fires peerAvailabilityChanged event for wifi peers'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiconnect failure - new peer is ignored (MPCF)'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - newAddressPort field (TCP_NATIVE)'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - newAddressPort field (BLUETOOTH)'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - newAddressPort field (MPCF)'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - error when peer has not been discovered yet'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - returns discovered cached wifi peer'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #disconnect fails on wifi peers'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #disconnect delegates native peers to the native wrapper'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes emitted correctly'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes not emitted in started state'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes not emitted in stopped state'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We properly fire peer unavailable and then available when connection fails on Android'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We properly fire peer unavailable and then available when connection fails on iOS'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - does not fire duplicate events after peer listener recreation'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #stop should change peers'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - peer should be found once after listening and discovery started'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get data from all participants'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - test for data corruption'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - test getters'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - start and kill'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - double start'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - start after kill'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - make sure ids are unique'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - check that forever agent can be destroyed'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test PeerDictionary basic functionality'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test PeerDictionary with multiple entries.'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - RESOLVED entries are removed before WAITING state entry.'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - WAITING entries are removed before CONTROLLED_BY_POOL state entry.'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - When CONTROLLED_BY_POOL entry is removed and kill is called.'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - single action'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - multiple actions'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - PSK Pool works'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - stop'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure that start verifies queue length'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - bad enqueues'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - do not allow same object type'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure we catch kill and dequeue'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure that stop removes all actions'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We reject unrecognized connection type'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We reject unrecognized action type'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - One action on bluetooth'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Two notification actions'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - replicateThroughProblems'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Replication goes first'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - wifi allows many parallel non-replication actions'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - wifi allows no more than 2 simultaneous replication actions for same peerID'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Client to server request coordinated'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test BEACONS_RETRIEVED_AND_PARSED locally'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Test HTTP_BAD_RESPONSE locally'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test NETWORK_PROBLEM locally'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Action fails when getPeerHostInfo fails'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the start two times'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill before calling the start'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill immediately after the start'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill while waiting a response from the server'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test to exceed the max content size locally'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Close the server socket while the client is waiting a response from the server. Local test.'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Close the client socket while the client is waiting a response from the server. Local test.'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons bad args'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons empty keys to notify'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons multiple keys to notify'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid expiration in beaconStreamWithPreAmble'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons expiration out of range lower'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons expiration out of range lower'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons no beacons returns null'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback fails decrypt'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #parseBeacons addressBookCallback returns no matches'
2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns ,spurious match'
2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns public key'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskIdentityField'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskSecret'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskSecrets'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generateBeaconStreamAndSecrets'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Add two Peers.'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - TCP_NATIVE peer loses DNS'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Received beacons with no values for us'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Notification action killed with a superseded'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Resolves an action locally'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Emits error event when peerPool.enqueue throws'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Resolves an action locally using ThaliPeerPoolDefault'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Action fails because of a bad hostname.'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - hostaddress is removed when the action is running. '
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - notificationClient does not retry action with BAD_PEER resolution'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - notification client correctly handles peer availability changes of the same peer'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Client to server request locally'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache clean and expiration'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache getSecret and getPublic'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache multiple entries'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Start and stop ThaliNotificationServer'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass an empty array to ThaliNotificationServer.start'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass a string to ThaliNotificationServer.start'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass an empty parameter to ThaliNotificationServer.start'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeacons'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeacons (no keys)'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeaconsbefore calling start'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure peerDictionaryKey is reasonable'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure start works'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure stop works'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Emits error event when peerPool.enqueue throws'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Simple peer event'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Coordinated pull replication from notification test'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server is not there'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server accepts & closes connection'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server always returns 500'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server always returns 401'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server always returns 403'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure docs replicate with remote db with same name as local db'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure docs replicate with remote db with different name than local db'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Do nothing and make sure we time out'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Do something and make sure we time out'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Start replicating and then catch error when server goes'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure clone works'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Coordinated replication action test - each device has the same local db name'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Coordinated replication action test - each device has different local db name'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Coordinated replication action test - should throw error when wrong remote db name is provided'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - compareBufferArrays'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: failed - unknown, error: 'Error: Too many test retries!', stack: 'assert@/private/var/containers/Bundle/Application/B9D1774A-DA75-4C08-98B8-DB88E3B59AC6/ThaliTest.app/www/jxcore/node_mod,ules/tape/lib/test.js:203:54
bound@/private/var/containers/Bundle/Application/B9D1774A-DA75-4C08-98B8-DB88E3B59AC6/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:62:28
Test.prototype.fail@/private/var/containers/Bundle/Application/B9D1774A-DA75-4,C08-98B8-DB88E3B59AC6/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:268:1
bound@/private/var/containers/Bundle/Application/B9D1774A-DA75-4C08-98B8-DB88E3B59AC6/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:62:28
tryToConnect/testTimeout,<@/private/var/containers/Bundle/Application/B9D1774A-DA75-4C08-98B8-DB88E3B59AC6/ThaliTest.app/www/jxcore/lib/thaliMobileNativeTestUtils.js:420:9
$9@timers.js:120:1''
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call start twice and get error'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Start and make sure it runs'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure getTimeWhenRun is right after start'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure getTimeWhenRun is -1 after function is called'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test TransientState'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - No peers and empty database'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - One peer and empty DB'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - One peer with _Local set behind current seq'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - One peer with _Local set equal to current seq'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - One peer with _Local set ahead of current seq (and no this should not happen)'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Three peers, one not in DB, one behind and one ahead'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - More than maximum peers, make sure we only send maximum allowed'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - two peers with empty DB, update the doc'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - add doc and make sure tokens refresh when they expire'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - start and stop and start and stop'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - two identical starts in a row'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - two different starts in a row'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - two stops and a start and two stops'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - we properly enqueue requests so no then needed'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test calculateSeqPointKeyId'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - server is not there'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - server accepts & closes connection'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - server always returns 500'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - create new seq doc'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - doc exists, need to get rev and update'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - update seq three times'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - rev got changed under us'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - fail if stop is called'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - stop after get but before put fails right'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #update - fail if stop is called'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #update - set seq for first time'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #update - Fail on bad seq value'
2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #update - do we cancel timer properly on an immediate?'
2017-07,-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #update - do we wait for blocked update'
2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #update - test that we wait long enough'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #update - test that we pick up new sequences while we wait'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Coordinated seq test'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test thali manager spies'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test thali manager multiple starts and stops'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - test write'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: failed - test repeat write 1, error: 'TypeError: thaliManager is undefined', stack: 'testRepeatWrite/<@/private/var/containers/Bundle/Application/B9D1774A-DA75-4C08-98B8-DB88E3B59AC6/Tha,liTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js:285:7
CoordinatedClient.prototype._processEvent/</<@/private/var/containers/Bundle/Application/B9D1774A-DA75-4C08-98B8-DB88E3B59AC6/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:471:9
canc,ellationExecute@/private/var/containers/Bundle/Application/B9D1774A-DA75-4C08-98B8-DB88E3B59AC6/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/debuggability.js:320:9
module.exports/Promise.prototype._resolveFromExecutor@/private/var/containers/,Bundle/Application/B9D1774A-DA75-4C08-98B8-DB88E3B59AC6/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:481:13
Promise@/private/var/containers/Bundle/Application/B9D1774A-DA75-4C08-98B8-DB88E3B59AC6/ThaliTest.app/www/jxcore/node_modul,es/bluebird/js/release/promise.js:77:9
CoordinatedClient.prototype._processEvent/<@/private/var/containers/Bundle/Application/B9D1774A-DA75-4C08-98B8-DB88E3B59AC6/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:428:14
tryCatcher@/private/var/containers,/Bundle/Application/B9D1774A-DA75-4C08-98B8-DB88E3B59AC6/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/util.js:16:16
module.exports/Promise.prototype._settlePromiseFromHandler@/private/var/containers/Bundle/Application/B9D1774A-DA75-4C08-98B8-,DB88E3B59AC6/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:510:13
module.exports/Promise.prototype._settlePromise@/private/var/containers/Bundle/Application/B9D1774A-DA75-4C08-98B8-DB88E3B59AC6/ThaliTest.app/www/jxcore/node_modules/,bluebird/js/release/promise.js:567:13
module.exports/Promise.prototype._settlePromise0@/private/var/containers/Bundle/Application/B9D1774A-DA75-4C08-98B8-DB88E3B59AC6/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:612:5
module.expo,rts/Promise.prototype._settlePromises@/private/var/containers/Bundle/Application/B9D1774A-DA75-4C08-98B8-DB88E3B59AC6/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:691:13
Async.prototype._drainQueue@/private/var/containers/Bundle/Ap,plication/B9D1774A-DA75-4C08-98B8-DB88E3B59AC6/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/async.js:138:13
Async.prototype._drainQueues@/private/var/containers/Bundle/Application/B9D1774A-DA75-4C08-98B8-DB88E3B59AC6/ThaliTest.app/www/jxcore/,node_modules/bluebird/js/release/async.js:148:5
Async/this.drainQueues@/private/var/containers/Bundle/Application/B9D1774A-DA75-4C08-98B8-DB88E3B59AC6/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/async.js:17:9
$v@timers.js:364:1
''
2017-07,-21 06:45:05 - ERROR CoordinatedClient: 'failed to run unit tests, platformName: 'ios''
,2017-07-21 06:48:05 - DEBUG CoordinatedClient: 'all tests completed'
,2017-07-21 06:48:06 - DEBUG CoordinatedClient: 'test client disconnected'
2017-07-21 06:48:06 - DEBUG CoordinatedClient: 'test client failed'
2017-07-21 06:48:06 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: TimeoutError: timeout exceeded, ,event: 'run_test repeat write 1_finished', test: 'test repeat write 1'', stack: 'CoordinatedClient.prototype._customError@/private/var/containers/Bundle/Application/B9D1774A-DA75-4C08-98B8-DB88E3B59AC6/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:292:,27
Emitter.prototype.emit@/private/var/containers/Bundle/Application/B9D1774A-DA75-4C08-98B8-DB88E3B59AC6/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7
Socket.prototype.onevent@/private/var/containers/Bundle/Application/B9D1774A-,DA75-4C08-98B8-DB88E3B59AC6/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:263:5
Socket.prototype.onpacket@/private/var/containers/Bundle/Application/B9D1774A-DA75-4C08-98B8-DB88E3B59AC6/ThaliTest.app/www/jxcore/node_modules/socket.,i,o-client/lib/socket.js:221:7
module.exports/<@/private/var/containers/Bundle/Application/B9D1774A-DA75-4C08-98B8-DB88E3B59AC6/ThaliTest.app/www/jxcore/node_modules/component-bind/index.js:21:12
Emitter.prototype.emit@/private/var/containers/Bundle/Applic,ation/B9D1774A-DA75-4C08-98B8-DB88E3B59AC6/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7''
2017-07-21 06:48:06 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'

```
