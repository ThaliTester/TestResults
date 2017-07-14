#### Test 113351851ac4367c_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/113351851ac4367c/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6s Plus 'Iphone6sPlus-1' (f70cda60583ea0f895d05ea355cd125983c27594).
,(lldb) command source -s 0 '/tmp/A0C51F47-CE90-4366-AD53-88E20CA3B698/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/A0C51F47-CE90-4366-AD53-88E20CA3B698/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/113351851ac4367c/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/113351851ac4367c/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/C8C91A98-AF9F-4F81-8796-8AAA5FDEE39E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61162"
,(lldb)     command script import "/tmp/A0C51F47-CE90-4366-AD53-88E20CA3B698/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-07-14 12:39:05 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 12:39:05 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 12:39:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:39:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 12:39:05 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:39:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:39:05 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
,AppContextTests.test_didEnterForeground finished
,AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
,AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
AppContextTests.test_esonValue finished
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "18750450-41E3-4154-89,5F-2E41EA98822C", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:18750450-41E3-4154-895F-2E41EA98822C
Optional(true)
Optional(false)
,AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:0354A261-66E7-4F35-B3E0-AB80C2C1DA4F
[ThaliCore] Browser.startListening
Optional(false)
Optional(true)
AppContextTests.test_liste,ningAdvertisingUpdateOnStartListening finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:F22CB324-C24F-423A-AF54-A7C12A9DA7E2
[ThaliCore] Browser.startListening
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "252367E3-2E11-4121-8FB1-52ACF974F01A", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:252367E3-2E11-4121-8FB1-52ACF974F01A
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:252367E3-2E11-4121-8FB1-52ACF974F01A:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "252367E3-2E11-4121-8FB1-52ACF974F01A", generation: 0)
,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
,AppContextTests.test_connectReturnValueCorrect finished
AppContextTests finished
All tests finished
All tests finished
,2017-07-14 12:39:07 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
Number of passed tests:  13
Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  1.461888015270233
,2017-07-14 12:39:07 - DEBUG UnitTest_app: 'My device name is: 'Apple-iphone-5s-1''
,2017-07-14 12:39:07 - WARN testUtils: 'myNameCallback not set!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:252367E3-2E11-4121-8FB1-52ACF974F01A:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "252367E3-2E11-4121-8FB1-52ACF974F01A", generation: 0)
,2017-07-14 12:39:10 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-07-14 12:39:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C8C91A98-AF9F-4F81-8796-8AAA5FDEE39E/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-07-14 12:39:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C8C91A98-AF9F-4F81-8796-8AAA5FDEE39E/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-07-14 12:39:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C8C91A98-AF9F-4F81-8796-8AAA5FDEE39E/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-07-14 12:39:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C8C91A98-AF9F-4F81-8796-8AAA5FDEE39E/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-07-14 12:39:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C8C91A98-AF9F-4F81-8796-8AAA5FDEE39E/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-07-14 12:39:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C8C91A98-AF9F-4F81-8796-8AAA5FDEE39E/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-07-14 12:39:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C8C91A98-AF9F-4F81-8796-8AAA5FDEE39E/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-07-14 12:39:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C8C91A98-AF9F-4F81-8796-8AAA5FDEE39E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-07-14 12:39:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C8C91A98-AF9F-4F81-8796-8AAA5FDEE39E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-07-14 12:39:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C8C91A98-AF9F-4F81-8796-8AAA5FDEE39E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-07-14 12:39:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C8C91A98-AF9F-4F81-8796-8AAA5FDEE39E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-07-14 12:39:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C8C91A98-AF9F-4F81-8796-8AAA5FDEE39E/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-07-14 12:39:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C8C91A98-AF9F-4F81-8796-8AAA5FDEE39E/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-07-14 12:39:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C8C91A98-AF9F-4F81-8796-8AAA5FDEE39E/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-07-14 12:39:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C8C91A98-AF9F-4F81-8796-8AAA5FDEE39E/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-07-14 12:39:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C8C91A98-AF9F-4F81-8796-8AAA5FDEE39E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-07-14 12:39:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C8C91A98-AF9F-4F81-8796-8AAA5FDEE39E/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-07-14 12:39:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C8C91A98-AF9F-4F81-8796-8AAA5FDEE39E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-07-14 12:39:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C8C91A98-AF9F-4F81-8796-8AAA5FDEE39E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-07-14 12:39:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C8C91A98-AF9F-4F81-8796-8AAA5FDEE39E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-07-14 12:39:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C8C91A98-AF9F-4F81-8796-8AAA5FDEE39E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-07-14 12:39:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C8C91A98-AF9F-4F81-8796-8AAA5FDEE39E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-07-14 12:39:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C8C91A98-AF9F-4F81-8796-8AAA5FDEE39E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-07-14 12:39:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C8C91A98-AF9F-4F81-8796-8AAA5FDEE39E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-07-14 12:39:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C8C91A98-AF9F-4F81-8796-8AAA5FDEE39E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-07-14 12:39:14 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C8C91A98-AF9F-4F81-8796-8AAA5FDEE39E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-07-14 12:39:14 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C8C91A98-AF9F-4F81-8796-8AAA5FDEE39E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-07-14 12:39:14 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C8C91A98-AF9F-4F81-8796-8AAA5FDEE39E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-07-14 12:39:14 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C8C91A98-AF9F-4F81-8796-8AAA5FDEE39E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-07-14 12:39:14 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C8C91A98-AF9F-4F81-8796-8AAA5FDEE39E/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-07-14 12:39:14 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C8C91A98-AF9F-4F81-8796-8AAA5FDEE39E/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-07-14 12:39:14 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C8C91A98-AF9F-4F81-8796-8AAA5FDEE39E/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-07-14 12:39:14 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C8C91A98-AF9F-4F81-8796-8AAA5FDEE39E/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-07-14 12:39:14 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C8C91A98-AF9F-4F81-8796-8AAA5FDEE39E/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-07-14 12:39:14 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C8C91A98-AF9F-4F81-8796-8AAA5FDEE39E/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-07-14 12:39:14 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C8C91A98-AF9F-4F81-8796-8AAA5FDEE39E/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-07-14 12:39:14 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C8C91A98-AF9F-4F81-8796-8AAA5FDEE39E/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-07-14 12:39:14 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C8C91A98-AF9F-4F81-8796-8AAA5FDEE39E/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-07-14 12:39:14 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C8C91A98-AF9F-4F81-8796-8AAA5FDEE39E/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-07-14 12:39:14 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C8C91A98-AF9F-4F81-8796-8AAA5FDEE39E/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-07-14 12:39:14 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-07-14 12:39:14 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
,2017-07-14 12:39:14 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
,# setup
,# closeAll can close even when connections open
,2017-07-14 12:39:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 1 not possible to connect to the server anymore
# teardown
,# setup
,# closeAll with promise
,2017-07-14 12:39:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 2 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll properly throws when closing a non open server with eatNotRunning set to false
,2017-07-14 12:39:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
,# teardown
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
2017-07-14 12:39:26 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of multiple onCheckpointReached handlers on a single db change''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
,2017-07-14 12:39:30 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
,2017-07-14 12:39:31 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''
,# teardown
,# setup
,# test defaultDirectory
,ok 4 should be equal
ok 5 should be equal
ok 6 should be equal
,# teardown
,# setup
,# test defaultAdapter
,ok 7 should be equal
ok 8 should be equal
ok 9 should be equal
ok 10 should be equal
ok 11 should be equal
ok 12 should be equal
,ok 13 should be equal
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
,# teardown
,# setup
,# enqueueAtTop and run backwards
,ok 24 thirdPromise - first to run
ok 25 thirdPromise - in resolve
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
,# teardown
,# setup
,# queues handled independently
,ok 40 all short operations completed before the long resolves
# teardown
,# setup
,# enqueued function are always executed asynchronously
,ok 41 executor is not called here
,ok 42 executors is called
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
,ok 46 test sandbox spy works correctly
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
,ok 60 throws if usn has invalid generation
ok 61 correctly stringifies peer
,# teardown
,# setup
,# onPeerLost calls jxcore
,2017-07-14 12:39:44 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
,# teardown
,2017-07-14 12:39:45 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 12:39:45 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:39:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:39:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 12:39:45 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 12:39:45 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:39:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:39:45 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# onPeerDiscovered calls jxcore
,2017-07-14 12:39:45 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
,# teardown
,2017-07-14 12:39:46 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 12:39:46 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:39:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:39:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 12:39:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 12:39:46 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:39:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:39:46 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-14 12:39:46 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 12:39:46 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 12:39:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:39:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 12:39:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 12:39:46 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:39:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:39:46 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can call start/stopListeningForAdvertisements
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:76EDC631-8E9F-4A81-90CF-050D353286BF
,[ThaliCore] Browser.startListening
,2017-07-14 12:39:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 12:39:46 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 12:39:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 62 Can call startListeningForAdvertisements without error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-14 12:39:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:39:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 63 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 12:39:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:39:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 64 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-14 12:39:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisin,gActive":false}'
2017-07-14 12:39:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 65 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-14 12:39:47 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 12:39:47 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:39:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:39:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 12:39:47 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 12:39:47 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:39:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:39:47 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Calling startListeningForAdvertisements twice is NOT an error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:A697E961-86F2-4715-BE1C-18DD3A2C665F
[ThaliCore] Browser.startListening
2017-07-14 12:39:48 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-14 12:39:48 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 12:39:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 66 Can call startLis,teningForAdvertisements without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
2017-07-14 12:39:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 12:39:48 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-14 12:39:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 67 Can call startListeningForAdvertisements twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-14 12:39:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:39:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 68 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-14 12:39:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisin,gActive":false}'
2017-07-14 12:39:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 69 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-14 12:39:50 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 12:39:50 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:39:50 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:39:50 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 12:39:50 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 12:39:50 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:39:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:39:50 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Calling stopListeningForAdvertisements without calling start is NOT an error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-14 12:39:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:39:50 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 70 Can call stopListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-14 12:39:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdver,tisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:39:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 71 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 12:39:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:39:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 72 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-14 12:39:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisin,gActive":false}'
2017-07-14 12:39:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 73 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-14 12:39:53 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 12:39:53 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 12:39:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:39:53 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 12:39:53 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 12:39:53 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:39:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:39:53 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can call start/stopUpdateAdvertisingAndListening
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "16F89E5B-CCF2-4F2E-8D1E-3DE44874260F", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:16F89E5B-CCF2-4F2E-8D1E-3DE44874260F
2017-07-14 1,2:39:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 12:39:55 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 12:39:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 74 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
2017-07-14 12:39:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertising,StateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:39:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 75 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 12:39:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:39:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 76 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 12:39:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:39:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 77 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-14 12:39:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 12:39:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:39:56 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:39:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 12:39:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 12:39:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:39:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:39:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Calling startUpdateAdvertisingAndListening twice is NOT an error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "B7FC5990-036C-41D9-8A70-6498ED73D21A", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:B7FC5990-036C-41D9-8A70-6498ED73D21A
2017-07-14 1,2:39:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 12:39:58 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 12:39:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 78 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "B7FC5990-036C-41D9-8A70-6498ED73D21A", generation: 1)
[ThaliCore] ,A,dvertiser.startAdvertising with peerID:B7FC5990-036C-41D9-8A70-6498ED73D21A
2017-07-14 12:39:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 12:39:58 - INFO thali,Mobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})',
2017-07-14 12:39:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 79 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 12:40:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-14 12:40:00 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-14 12:40:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 80 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,2017-07-14 12:40:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:40:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 81 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-14 12:40:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 12:40:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:40:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:40:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 12:40:08 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 12:40:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:40:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:40:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-14 12:40:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:40:24 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
ok 82 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-14 12:40:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNon,TCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:40:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 83 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 12:40:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:40:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 84 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 12:40:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:40:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 85 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-14 12:40:27 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 12:40:27 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 12:40:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:40:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 12:40:28 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 12:40:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:40:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:40:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# peerAvailabilityChange is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "EBFCCF03-A21B-4FC3-AD11-14753B232823", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:EBFCCF03-A21B-4FC3-AD11-14753B232823
2017-07-14 1,2:40:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 12:40:28 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 12:40:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 86 Can call startUpdateAdvertisingAndListeningwithout error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:606A22A4-14D4-43B4-BED2-D54BD5DFB48C
[ThaliC,ore] Browser.startListening
,2017-07-14 12:40:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-14 12:40:28 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 12:40:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 87 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D768C9AD-0186-4DCA-B627-720F1CFF507B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D768C9AD-0186-4DCA-B627-720F1CFF507B", generation: 0)
,ok 88 peers must be an array
,ok 89 peers must not be zero-length
,ok 90 peer must have only peerIdentifier, peerAvailable and generation properties
,ok 91 peerIdentifier must be a string
,ok 92 generation must be a number
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3C925756-E54C-43A8-85BF-9E1651BC74ED:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3C925756-E54C-43A8-85BF-9E1651BC74ED", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:EBFCCF03-A21B-4FC3-AD11-14753B232823:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "EBFCCF03-A21B-4FC3-AD11-14753B232823", generation: 0)
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-14 12:40:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 12:40:29 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 12:40:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 93 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
2017-07-14 12:40:29 - DEBUG thaliMobileNativeWrapper: 'd,iscoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:40:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 94 Should be able to call stopAdvertisingAndList,ening in teardown
,# setup
,2017-07-14 12:40:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 12:40:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 12:40:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:40:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 12:40:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 12:40:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:40:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:40:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can connect to a remote peer
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "381534BF-0A7C-4DD9-BB76-E7FC86950E7A", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:381534BF-0A7C-4DD9-BB76-E7FC86950E7A
2017-07-14 1,2:40:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 12:40:33 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 12:40:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 95 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:DC378D7C-FBBE-465D-A82A-96AFD7A5FDD0
[Thali,Core] Browser.startListening
,2017-07-14 12:40:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-14 12:40:33 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 12:40:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 96 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CAC774EE-985F-4EB8-98CB-836275DBB8DB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CAC774EE-985F-4EB8-98CB-836275DBB8DB", generation: 0)
,2017-07-14 12:40:33 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"CAC774EE-985F-4EB8-98CB-836275DBB8DB","generation":0}'
,2017-07-14 12:40:33 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for CAC774EE-985F-4EB8-98CB-836275DBB8DB (syncValue: envJbj1EYChxSOk4FjuzBCJtaWWHNiY9)'
,2017-07-14 12:40:33 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "CAC774EE-985F-4EB8-98CB-836275DBB8DB", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CAC774EE-985F-4EB8-98CB-836275DBB8DB", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:CAC774EE-985F-4EB8-98CB-836275DBB8DB:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:CAC774EE-985F-4EB8-98CB-836275DBB8DB:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0D72AE22-FA55-4054-B2AE-210720329C10:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0D72AE22-FA55-4054-B2AE-210720329C10", generation: 0)
2017-07-14 12:40:34 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"0D72AE22-FA55-4054-B2AE-210720329C10","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:381534BF-0A7C-4DD9-BB76-E7FC86950E7A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "381534BF-0A7C-4DD9-BB76-E7FC86950E7A", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:CAC774EE-985F-4EB8-98CB-836275DBB8DB:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:CAC774EE-985F-4EB8-98CB-836275DBB8DB:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "CAC774EE-985F-4EB8-98CB-836275DBB8DB", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50399
,2017-07-14 12:40:36 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"envJbj1EYChxSOk4FjuzBCJtaWWHNiY9","error":null,"portNumber":50399}'
,2017-07-14 12:40:36 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'envJbj1EYChxSOk4FjuzBCJtaWWHNiY9', error: 'null', listeningPort: '50399''
,2017-07-14 12:40:36 - INFO testThaliMobileNative: ''
,ok 97 Must have listeningPort
,ok 98 listeningPort must be a number
,ok 99 listening port should not be 0
,# teardown
,[ThaliCore] Session.session(_:peer:didChange:) peer:CAC774EE-985F-4EB8-98CB-836275DBB8DB:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "CAC774EE-985F-4EB8-98CB-836275DBB8DB", generation: 0)
[ThaliCore] BrowserRel,ay.closeRelay() disconnecting:false
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50399
[ThaliCore] Session.disconnect() peer:CAC774EE-985F-4EB8-98CB-836275DBB8DB:0
[ThaliCore] Browser: session notConnected removed relay, for Peer(uuid: "CAC774EE-985F-4EB8-98CB-836275DBB8DB", generation: 0)
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,2017-07-14 12:40:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-14 12:40:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-14 12:40:38 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-14 12:40:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 100 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdv,ertising()
[ThaliCore] Advertiser.stopAdvertising()
2017-07-14 12:40:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:40:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 101 Should be able to call stopAdvertisingAndListening in teardown
,[ThaliCore] BrowserManager.disconnect peer:CAC774EE-985F-4EB8-98CB-836275DBB8DB
,# setup
,2017-07-14 12:40:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 12:40:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 12:40:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:40:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 12:40:38 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 12:40:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:40:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:40:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can shift data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "B5A79CA8-4B6D-42E9-A632-564AB2A52DDA", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:B5A79CA8-4B6D-42E9-A632-564AB2A52DDA
2017-07-14 1,2:40:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 12:40:38 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 12:40:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 102 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:2A15EA3D-07F0-4C9B-BCB0-EAF858D5FCFA
,[ThaliCore] Browser.startListening
,2017-07-14 12:40:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-14 12:40:38 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 12:40:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 103 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CAC774EE-985F-4EB8-98CB-836275DBB8DB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CAC774EE-985F-4EB8-98CB-836275DBB8DB", generation: 0)
2017-07-14 12:40:39 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"CAC774EE-985F-4EB8-98CB-836275DBB8DB","generation":0}'
2017-07-14 12:40:39 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for CAC774EE-985F-4EB8-98CB-836275DBB8DB, (syncValue: 2sxrXtlhtmvv20MNm6rnNKSWHoZda7v9)'
2017-07-14 12:40:39 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "CAC774EE-985F-4EB8-98CB-836275DBB8DB", gen,eration: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CAC774EE-985F-4EB8-98CB-836275DBB8DB", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:CAC774EE-985F-4EB8-98CB-836275DBB8DB:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DBC05482-D5B6-4F51-A692-E8C2855F7F2F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DBC05482-D5B6-4F51-A692-E8C2855F7F2F", generation: 0)
,2017-07-14 12:40:39 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"DBC05482-D5B6-4F51-A692-E8C2855F7F2F","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B5A79CA8-4B6D-42E9-A632-564AB2A52DDA:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B5A79CA8-4B6D-42E9-A632-564AB2A52DDA", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4AAB776C-211D-47ED-BBDD-F924EF51954D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4AAB776C-211D-47ED-BBDD-F924EF51954D", generation: 0)
2017-07-14 12:40:40 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"4AAB776C-211D-47ED-BBDD-F924EF51954D","generation":0}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:CAC774EE-985F-4EB8-98CB-836275DBB8DB:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "CAC774EE-985F-4EB8-98CB-836275DBB8DB", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:CAC774EE-985F-4EB8-98CB-836275DBB8DB:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "CAC774EE-985F-4EB8-98CB-836275DBB8DB", genera,tion: 0)
2017-07-14 12:40:45 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"2sxrXtlhtmvv20MNm6rnNKSWHoZda7v9","error":"Connection could not be established","portNumber":null}'
2017-07-14 12:40:45 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: '2sxrXtlhtmvv20MNm6rnNKSWHoZda7v9', error: 'Connection could not be established', listeningPort: '%s''
2017-07-14 12:40:45 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,tifier":"CAC774EE-985F-4EB8-98CB-836275DBB8DB","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-14 12:40:45 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-14, 12:40:45 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"CAC774EE-985F-4EB8-98CB-836275DBB8DB","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-14 12:40:45 - DEBUG thaliMobileNativeWrap,per: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-14 12:40:45 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-14 12:40:45 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for DBC05482-D5B6-4F51-A692-E8C2855F7F2F (syncValue: tqsoeGc,WkU9FkWbcLlpwLk2DLOQaL5U1)'
2017-07-14 12:40:45 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "DBC05482-D5B6-4F51-A692-E8C2855F7F2F", generation: 0) new rela,y
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "DBC05482-D5B6-4F51-A692-E8C2855F7F2F", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:DBC05482-D5B6-4F51-A692-E8C2855F7F2,F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:DBC05482-D5B6-4F51-A692-E8C2855F7F2F:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:DBC05482-D5B6-4F51-A692-E8C2855F7F2F:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:DBC05482-D5B6-4F51-A692-E8C2855F7F2F:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "DBC05482-D5B6-4F51-A692-E8C2855F7F2F", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50404
2017-07-14 12:40:48 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"tqsoeGcWkU9FkWbcLlpwLk2DLOQaL5U1",,"error":null,"portNumber":50404}'
2017-07-14 12:40:48 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'tqsoeGcWkU9FkWbcLlpwLk2DLOQaL5U1', error: 'null', listeningPort: '50404''
,Connecting to the localhost:50404
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:DBC05482-D5B6-4F51-A692-E8C2855F7F2F:0
Connected to the localh,ost:50404
,2017-07-14 12:40:48 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-14 12:40:48 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:DBC05482-D5B6-4F51-A692-E8C2855F7F2F:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1 [1]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 104 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pe,er})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStream,s() vsID:1
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:1
[ThaliCore] VirtualSocket.deinit vsID:1 []
,# teardown
,2017-07-14 12:40:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-14 12:40:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 12:40:48 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 12:40:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 105 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
,2017-07-14 12:40:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:40:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,ok 106 Should be able to call stopAdvertisingAndListening in teardown
[ThaliCore] BrowserManager.disconnect peer:DBC05482-D5B6-4F51-A692-E8C2855F7F2F
,[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50404
[ThaliCore] Session.disconnect() peer:DBC05482-D5B6-4F51-A692-E8C2855F7F2F:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] Session.session(_:peer:didChange:) peer:DBC05482-D5B6-4F51-A692-E8C2855F7F2F:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "DBC05482-D5B6-4F51-A692-E8C2855F7F2F", generation: 0)
[ThaliCore] Browser: s,ession notConnected removed relay for Peer(uuid: "DBC05482-D5B6-4F51-A692-E8C2855F7F2F", generation: 0)
,# setup
,2017-07-14 12:40:48 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 12:40:48 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:40:48 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:40:48 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 12:40:48 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 12:40:48 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:40:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:40:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can shift data via parallel connections
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "9A4807DE-B800-467B-855C-24982A72E20C", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:9A4807DE-B800-467B-855C-24982A72E20C
,2017-07-14 12:40:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 12:40:49 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 12:40:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 107 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D2157855-2EF0-4AE0-96DA-6B541B5D560A
[ThaliCore] Browser.startList,ening
,2017-07-14 12:40:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-14 12:40:49 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-14 12:40:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 108 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4AAB776C-211D-47ED-BBDD-F924EF51954D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4AAB776C-211D-47ED-BBDD-F924EF51954D", generation: 0)
2017-07-14 12:40:49 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"4AAB776C-211D-47ED-BBDD-F924EF51954D","generation":0}'
2017-07-14 12:40:49 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 4AAB776C-211D-47ED-BBDD-F924EF51954D, (syncValue: vFKowRTPY66NVQaAhV8OXPrjdMYLt7it)'
2017-07-14 12:40:49 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "4AAB776C-211D-47ED-BBDD-F924EF51954D", gen,eration: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4AAB776C-211D-47ED-BBDD-F924EF51954D", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4AAB776C-211D-47ED-BBDD-F924EF51954D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D131BF9A-C3B7-4266-80FA-0A8E3B2B40CE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D131BF9A-C3B7-4266-80FA-0A8E3B2B40CE", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:99ECCC86-6352-4B09-8204-FA460094AD9F:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "99ECCC86-6352-4B09-8204-FA460094AD9F", generation: 0)
,2017-07-14 12:40:50 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"D131BF9A-C3B7-4266-80FA-0A8E3B2B40CE","generation":0}'
2017-07-14 12:40:50 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":t,rue,"peerIdentifier":"99ECCC86-6352-4B09-8204-FA460094AD9F","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9A4807DE-B800-467B-855C-24982A72E20C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9A4807DE-B800-467B-855C-24982A72E20C", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:4AAB776C-211D-47ED-BBDD-F924EF51954D:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "4AAB776C-211D-47ED-BBDD-F924EF51954D", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:4AAB776C-211D-47ED-BBDD-F924EF51954D:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "4AAB776C-211D-47ED-BBDD-F924EF51954D", genera,tion: 0)
2017-07-14 12:40:55 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"vFKowRTPY66NVQaAhV8OXPrjdMYLt7it","error":"Connection could not be established","portNumber":null}'
2017-07-14 12:40:55 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'vFKowRTPY66NVQaAhV8OXPrjdMYLt7it', error: 'Connection could not be established', listeningPort: '%s''
2017-07-14 12:40:55 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,t,ifier":"4AAB776C-211D-47ED-BBDD-F924EF51954D","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-14 12:40:55 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-14 ,12:40:55 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"4AAB776C-211D-47ED-BBDD-F924EF51954D","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-14 12:40:55 - DEBUG thaliMobileNativeWrapp,er: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-14 12:40:55 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-14 12:40:55 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for D131BF9A-C3B7-4266-80FA-0A8E3B2B40CE (syncValue: SJY1c7y,TU5bh0rwBie5RzRi53gLyyEFj)'
2017-07-14 12:40:55 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "D131BF9A-C3B7-4266-80FA-0A8E3B2B40CE", generation: 0) new rela,y
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D131BF9A-C3B7-4266-80FA-0A8E3B2B40CE", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D131BF9A-C3B7-4266-80FA-0A8E3B2B40C,E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FCF21A84-2512-4267-BF7A-293E7CDC55CD
[ThaliCore] Advertiser: session connected Peer(uuid: "9A4807DE-B800-467B-855C-24982A72E20C", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] Session.session(_:peer:didChange:) peer:FCF21A84-2512-4267-BF7A-293E7CDC55CD state: notConnected -> connecting
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:D131BF9A-C3B7-4266-80FA-0A8E3B2B40CE:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:7B5CC7F3-8D3F-4850-93C3-9132A7C933D9
[ThaliCore] Advertiser: session connected Peer(uuid: "9A4807DE-B800-467B-855C-24982A72E20C", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:7B5CC7F3-8D3F-4850-93C3-9132A7C933D9 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:4AAB776C-211D-47ED-BBDD-F924EF51954D:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "4AAB776C-211D-47ED-BBDD-F924EF51954D", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D131BF9A-C3B7-4266-80FA-0A8E3B2B40CE:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:D131BF9A-C3B7-4266-80FA-0A8E3B2B40CE:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "D131BF9A-C3B7-4266-80FA-0A8E3B2B40CE", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50413
,2017-07-14 12:40:58 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"SJY1c7yTU5bh0rwBie5RzRi53gLyyEFj","error":null,"portNumber":50413}'
2017-07-14 12:40:58 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'S,JY1c7yTU5bh0rwBie5RzRi53gLyyEFj', error: 'null', listeningPort: '50413''
[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:FCF21A84-2512-4267-BF7A-293E7CDC55CD
,Connecting to the localhost:50413
,Connecting to the localhost:50413
Connecting to the localhost:50413
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:D131BF9A-C3B7-4266-80FA-0A8E3B2B40CE:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:D131BF9A-C3B7-4266-80FA-0A8E3B2B40CE:0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[Th,aliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:D131BF9A-C3B7-4266-80FA-0A8E3B2B40CE:0
,Connected to the localhost:50413
,Connected to the localhost:50413
,Connected to the localhost:50413
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D131BF9A-C3B7-4266-80FA-0A8E3B2B40CE:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2 [2]
[ThaliCore] Session.session(_:peer:didChange:) peer:FCF21A84-2512-4267-BF7A-293E,7CDC55CD state: connecting -> connected
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D131BF9A-C3B7-4266-80FA-0A8E3B2B40CE:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3 [2, 3]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D131BF9A-C3B7-4266-80FA-0A8E3B2B40CE:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4 [2, 3, 4]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FCF21A84-2512-4267-BF7A-293E7CDC55CD
[ThaliCore] Session.startOutputStream(with:) peer:FCF21A84-2512-4267-BF7A-293E7CDC55CD
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5 [2, 3, 4, 5]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FCF21A84-2512-4267-BF7A-293E7CDC55CD
[ThaliCore] Session.startOutputStream(with:) peer:FCF21A84-2512-4267-BF7A-293E7CDC55CD
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6, [2, 3, 4, 5, 6]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FCF21A84-2512-4267-BF7A-293E7CDC55CD
[ThaliCore] Session.startOutputStream(with:) peer:FCF21A84-2512-4267-BF7A-293E7CDC55CD
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7 [2, 3, 4, 5, 6, 7]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,ok 109 correct string length
,2017-07-14 12:40:58 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 110 correct string length
,2017-07-14 12:40:58 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 111 correct string length
,2017-07-14 12:40:58 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,2017-07-14 12:40:58 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-14 12:40:58 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-14 12:40:58 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-14 12:40:58 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,2017-07-14 12:40:58 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-14 12:40:58 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-14 12:40:58 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-14 12:40:58 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,2017-07-14 12:40:58 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-14 12:40:58 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:5
[ThaliCore] VirtualSocket.closeStreams() vsID:5
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:5
[ThaliCore] VirtualSocket.deinit vsID:5 [2, 3, 4, 6, 7]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-14 12:40:58 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-14 12:40:58 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,2017-07-14 12:40:58 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-14 12:40:58 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-14 12:40:58 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
,[ThaliCore] VirtualSocket.closeStreams() vsID:2
,[ThaliCore] VirtualSocket exited RunLoop vsID:2
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket.deinit vsID:2 [3, 4, 6, 7]
,ok 112 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vs,ID:3
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:3
,[ThaliCore] VirtualSocket.deinit vsID:3 [4, 6, 7]
,ok 113 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:4
,[ThaliCore] VirtualSocket exited RunLoop vsID:4
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket.deinit vsID:4 [6, 7]
,ok 114 got the same data back
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:6
,[ThaliCore] VirtualSocket.closeStreams() vsID:6
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:7
[ThaliCore] VirtualSocket.closeStreams() vsID:7
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:7
,[ThaliCore] VirtualSocket.deinit vsID:7 [6]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:7B5CC7F3-8D3F-4850-93C3-9132A7C933D9
,[ThaliCore] Session.session(_:peer:didChange:) peer:7B5CC7F3-8D3F-4850-93C3-9132A7C933D9 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7B5CC7F3-8D3F-4850-93C3-9132A7C933D9
[ThaliCore] Session.startOutputStream(with:) peer:7B5CC7F3-8D3F-4850-93C3-9132A7C933D9
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8 [6, 8]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7B5CC7F3-8D3F-4850-93C3-9132A7C933D9
[ThaliCore] Session.startOutputStream(with:) peer:7B5CC7F3-8D3F-4850-93C3-9132A7C933D9
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9 [6, 8, 9]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7B5CC7F3-8D3F-4850-93C3-9132A7C933D9
[ThaliCore] Session.startOutputStream(with:) peer:7B5CC7F3-8D3F-4850-93C3-9132A7C933D9
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:10 [6, 8, 9, 10]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,2017-07-14 12:40:59 - DEBUG testThaliMobileNative: 'Server received (3072 bytes):'
,2017-07-14 12:40:59 - DEBUG testThaliMobileNative: 'Server received (1308 bytes):'
,2017-07-14 12:40:59 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-14 12:40:59 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-14 12:40:59 - DEBUG testThaliMobileNative: 'Server received (3072 bytes):'
,2017-07-14 12:40:59 - DEBUG testThaliMobileNative: 'Server received (213 bytes):'
,2017-07-14 12:40:59 - DEBUG testThaliMobileNative: 'Server received (4339 bytes):'
,2017-07-14 12:40:59 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-14 12:40:59 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-14 12:40:59 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-14 12:40:59 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,2017-07-14 12:41:00 - DEBUG testThaliMobileNative: 'Server received all data: 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,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:8
[ThaliCore] VirtualSocket.closeStreams() vsID:8
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:8
,[ThaliCore] VirtualSocket.deinit vsID:8 [6, 9, 10]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,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'
2017-07-14 12:41:00 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-14 12:41:00 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-14 12:41:00 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,2017-07-14 12:41:00 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-14 12:41:00 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:9
[ThaliCore] VirtualSocket.closeStreams() vsID:9
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:9
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] VirtualSocket.deinit vsID:9 [6, 10]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-14 12:41:00 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:10
[ThaliCore] VirtualSocket.closeStreams() vsID:10
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:10
[ThaliCore] VirtualSocket.deinit vsID:10 [6]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-14 12:41:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-14 12:41:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 12:41:00 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 12:41:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 115 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,[ThaliCore] Session.session(_:peer:didChange:) peer:7B5CC7F3-8D3F-4850-93C3-9132A7C933D9 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "9A4807DE-B800-467B-855C-24982A72E20C", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
,[ThaliCore] Session.disconnect() peer:7B5CC7F3-8D3F-4850-93C3-9132A7C933D9
[ThaliCore] AdvertiserRelay.deinit
[ThaliCore] Session.deinit peer:7B5CC7F3-8D3F-4850-93C3-9132A7C933D9
,2017-07-14 12:41:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:41:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 116 Should be able to call stopAdvertisingAndListening in teardown
,[ThaliCore] BrowserManager.disconnect peer:D131BF9A-C3B7-4266-80FA-0A8E3B2B40CE
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50413
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] Session.disconnect() peer:D131BF9A-C3B7-4266-80FA-0A8E3B2B40CE:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:D131BF9A-C3B7-4266-80FA-0A8E3B2B40CE:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "D131BF9A-C3B7-4266-80FA-0A8E3B2B40CE", generation: 0)
[ThaliCore] BrowserRel,ay.closeRelay() disconnecting:true
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "D131BF9A-C3B7-4266-80FA-0A8E3B2B40CE", generation: 0)
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:FCF21A84-2512-4267-BF7A-293E7CDC55CD state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "9A4807DE-B800-467B-855C-24982A72E20C", generation: 0)
,2017-07-14 12:41:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 12:41:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 12:41:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:41:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 12:41:01 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 12:41:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:41:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:41:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can shift data securely
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "FD9E51BC-9FE1-45FD-9E88-E6A08077A58D", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:FD9E51BC-9FE1-45FD-9E88-E6A08077A58D
,2017-07-14 12:41:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 12:41:01 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 12:41:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 117 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:A71FE476-0307-4F55-9AA0-968301ACCEBC
[ThaliCore] Browser.startListening
,2017-07-14 12:41:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-14 12:41:01 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 12:41:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 118 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D131BF9A-C3B7-4266-80FA-0A8E3B2B40CE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D131BF9A-C3B7-4266-80FA-0A8E3B2B40CE", generation: 0)
,2017-07-14 12:41:01 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"D131BF9A-C3B7-4266-80FA-0A8E3B2B40CE","generation":0}'
,2017-07-14 12:41:01 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for D131BF9A-C3B7-4266-80FA-0A8E3B2B40CE (syncValue: cyYiBAA9ctV64Fuk2QwulYvr00rpYSoa)'
,2017-07-14 12:41:01 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "D131BF9A-C3B7-4266-80FA-0A8E3B2B40CE", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D131BF9A-C3B7-4266-80FA-0A8E3B2B40CE", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D131BF9A-C3B7-4266-80FA-0A8E3B2B40CE:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:27B2CA8B-3D18-4D1B-BBCA-23DEE60C715D:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "27B2CA8B-3D18-4D1B-BBCA-23DEE60C715D", generation: 0)
,2017-07-14 12:41:02 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"27B2CA8B-3D18-4D1B-BBCA-23DEE60C715D","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:794CF4E2-DF66-4642-B5B9-3D4ACD297C95:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "794CF4E2-DF66-4642-B5B9-3D4ACD297C95", generation: 0)
,2017-07-14 12:41:02 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"794CF4E2-DF66-4642-B5B9-3D4ACD297C95","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FD9E51BC-9FE1-45FD-9E88-E6A08077A58D:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FD9E51BC-9FE1-45FD-9E88-E6A08077A58D", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:D131BF9A-C3B7-4266-80FA-0A8E3B2B40CE:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "D131BF9A-C3B7-4266-80FA-0A8E3B2B40CE", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:D131BF9A-C3B7-4266-80FA-0A8E3B2B40CE:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "D131BF9A-C3B7-4266-80FA-0A8E3B2B40CE", genera,tion: 0)
2017-07-14 12:41:07 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"cyYiBAA9ctV64Fuk2QwulYvr00rpYSoa","error":"Connection could not be established","portNumber":null}'
2017-07-14 12:41:07 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'cyYiBAA9ctV64Fuk2QwulYvr00rpYSoa', error: 'Connection could not be established', listeningPort: '%s''
2017-07-14 12:41:07 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,tifier":"D131BF9A-C3B7-4266-80FA-0A8E3B2B40CE","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-14 12:41:07 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-14, 12:41:07 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"D131BF9A-C3B7-4266-80FA-0A8E3B2B40CE","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-14 12:41:07 - DEBUG thaliMobileNativeWrap,per: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-14 12:41:07 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-14 12:41:07 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 27B2CA8B-3D18-4D1B-BBCA-23DEE60C715D (syncValue: Q0yXAIk,rPiJLfbTpoLsoSMQjzKz8M38C)'
2017-07-14 12:41:07 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "27B2CA8B-3D18-4D1B-BBCA-23DEE60C715D", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "27B2CA8B-3D18-4D1B-BBCA-23DEE60C715D", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:27B2CA8B-3D18-4D1B-BBCA-23DEE60C715D:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:27B2CA8B-3D18-4D1B-BBCA-23DEE60C715D:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:27B2CA8B-3D18-4D1B-BBCA-23DEE60C715D:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:27B2CA8B-3D18-4D1B-BBCA-23DEE60C715D:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "27B2CA8B-3D18-4D1B-BBCA-23DEE60C715D", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50430
,2017-07-14 12:41:10 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Q0yXAIkrPiJLfbTpoLsoSMQjzKz8M38C","error":null,"portNumber":50430}'
,2017-07-14 12:41:10 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'Q0yXAIkrPiJLfbTpoLsoSMQjzKz8M38C', error: 'null', listeningPort: '50430''
,Connecting to the localhost:50430
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:27B2CA8B-3D18-4D1B-BBCA-23DEE60C715D:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:27B2CA8B-3D18-4D1B-BBCA-23DEE60C715D:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:11 [6, 11]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,Connected to the localhost:50430
,2017-07-14 12:41:10 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-14 12:41:10 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:11
,[ThaliCore] VirtualSocket.closeStreams() vsID:11
,ok 119 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:11
[ThaliCore] Browse,rRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:11
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket.deinit vsID:11 [6]
,# teardown
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:D131BF9A-C3B7-4266-80FA-0A8E3B2B40CE:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "D131BF9A-C3B7-4266-80FA-0A8E3B2B40CE", generation: 0)
,2017-07-14 12:41:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-14 12:41:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 12:41:15 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 12:41:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 120 Should be able to call stopListeni,ngForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
2017-07-14 12:41:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertising,A,ctive":false}'
2017-07-14 12:41:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 121 Should be able to call stopAdvertisingAndListening in teardown
,[ThaliCore] BrowserManager.disconnect peer:27B2CA8B-3D18-4D1B-BBCA-23DEE60C715D
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50430
[ThaliCore] Session.disconnect,() peer:27B2CA8B-3D18-4D1B-BBCA-23DEE60C715D:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] Session.session(_:peer:didChange:) peer:27B2CA8B-3D18-4D1B-BBCA-23DEE60C715D:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "27B2CA8B-3D18-4D1B-BBCA-23DEE60C715D", generation: 0)
[ThaliCore] Browser: s,ession notConnected removed relay for Peer(uuid: "27B2CA8B-3D18-4D1B-BBCA-23DEE60C715D", generation: 0)
,# setup
,2017-07-14 12:41:16 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 12:41:16 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 12:41:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:41:16 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 12:41:16 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 12:41:16 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:41:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:41:16 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can shift large amounts of data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "CB1D2901-E973-4AA9-BB6A-4759081EBB4A", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:CB1D2901-E973-4AA9-BB6A-4759081EBB4A
,2017-07-14 12:41:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 12:41:16 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 12:41:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 122 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:34F8A776-667A-422C-9196-2202DC36D9E4
[ThaliCore] Browser.startListening
,2017-07-14 12:41:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-14 12:41:16 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 12:41:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 123 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:794CF4E2-DF66-4642-B5B9-3D4ACD297C95:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "794CF4E2-DF66-4642-B5B9-3D4ACD297C95", generation: 0)
2017-07-14 12:41:16 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"794CF4E2-DF66-4642-B5B9-3D4ACD297C95","generation":0}'
2017-07-14 12:41:16 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 794CF4E2-DF66-4642-B5B9-3D4ACD297C95, (syncValue: m3RGsjBKdh3ygYx6ur0TQHFgjsw1osXS)'
2017-07-14 12:41:16 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "794CF4E2-DF66-4642-B5B9-3D4ACD297C95", gen,eration: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "794CF4E2-DF66-4642-B5B9-3D4ACD297C95", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:794CF4E2-DF66-4642-B5B9-3D4ACD297C95:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8ABBC275-0A33-4834-8930-987F8EE3835A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8ABBC275-0A33-4834-8930-987F8EE3835A", generation: 0)
2017-07-14 12:41:17 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"8ABBC275-0A33-4834-8930-987F8EE3835A","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CB1D2901-E973-4AA9-BB6A-4759081EBB4A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CB1D2901-E973-4AA9-BB6A-4759081EBB4A", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:05F6B8F2-51F6-437E-B02A-47E24E1B1558:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "05F6B8F2-51F6-437E-B02A-47E24E1B1558", generation: 0)
2017-07-14 12:41:18 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"05F6B8F2-51F6-437E-B02A-47E24E1B1558","generation":0}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:794CF4E2-DF66-4642-B5B9-3D4ACD297C95:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "794CF4E2-DF66-4642-B5B9-3D4ACD297C95", generation: 0)
[ThaliCore] Session.disconnect() peer:794CF4E2-DF6,6-4642-B5B9-3D4ACD297C95:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:794CF4E2-DF66-4642-B5B9-3D4ACD297C95:0 state: notConnected -> notConnected
,[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "794CF4E2-DF66-4642-B5B9-3D4ACD297C95", generation: 0)
,[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:794CF4E2-DF66-4642-B5B9-3D4ACD297C95:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "794CF4E2-DF66-4642-B5B9-3D4ACD297C95", generation: 0)
,2017-07-14 12:41:22 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"m3RGsjBKdh3ygYx6ur0TQHFgjsw1osXS","error":"Connection could not be established","portNumber":null}'
,2017-07-14 12:41:22 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'm3RGsjBKdh3ygYx6ur0TQHFgjsw1osXS', error: 'Connection could not be established', listeningPort: '%s''
,2017-07-14 12:41:22 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"794CF4E2-DF66-4642-B5B9-3D4ACD297C95","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-14 12:41:22 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-14 12:41:22 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"794CF4E2-DF66-4642-B5B9-3D4ACD297C95","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-14 12:41:22 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-14 12:41:22 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-14 12:41:22 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 8ABBC275-0A33-4834-8930-987F8EE3835A (syncValue: b3t2QRv6Lv1TDQ2N8Am7K3exkwNQpXHA)'
,2017-07-14 12:41:22 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "8ABBC275-0A33-4834-8930-987F8EE3835A", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8ABBC275-0A33-4834-8930-987F8EE3835A", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:8ABBC275-0A33-4834-8930-987F8EE3835A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:8ABBC275-0A33-4834-8930-987F8EE3835A:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:8ABBC275-0A33-4834-8930-987F8EE3835A:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:8ABBC275-0A33-4834-8930-987F8EE3835A:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "8ABBC275-0A33-4834-8930-987F8EE3835A", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50439
,2017-07-14 12:41:25 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"b3t2QRv6Lv1TDQ2N8Am7K3exkwNQpXHA","error":null,"portNumber":50439}'
,2017-07-14 12:41:25 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'b3t2QRv6Lv1TDQ2N8Am7K3exkwNQpXHA', error: 'null', listeningPort: '50439''
,Connecting to the localhost:50439
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:8ABBC275-0A33-4834-8930-987F8EE3835A:0
,Connected to the localhost:50439
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:8ABBC275-0A33-4834-8930-987F8EE3835A:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:12 [6, 12]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-14 12:41:25 - DEBUG testThaliMobileNative: 'Client sends data (65536 bytes):'
2017-07-14 12:41:25 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
,[ThaliCore] VirtualSocket.closeStreams() vsID:12
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:12
,[ThaliCore] VirtualSocket.deinit vsID:12 [6]
,ok 124 got the same data back
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4AAB776C-211D-47ED-BBDD-F924EF51954D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4AAB776C-211D-47ED-BBDD-F924EF51954D", generation: 0)
2017-07-14 12:41:29 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"4AAB776C-211D-47ED-BBDD-F924EF51954D","generation":0}'
,2017-07-14 12:41:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-14 12:41:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 12:41:31 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 12:41:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 125 Should be able to call stopListeni,ngForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
2017-07-14 12:41:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertising,A,ctive":false}'
2017-07-14 12:41:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 126 Should be able to call stopAdvertisingAndListening in teardown
[ThaliCore] BrowserManager.disconnect peer:8ABBC275-0A33-,4834-8930-987F8EE3835A
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50439
[ThaliCore] Session.disconnect() peer:8ABBC275-0A33-4834-8930-987F8EE3835A:0
[ThaliCor,e] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] Session.session(_:peer:didChange:) peer:8ABBC275-0A33-4834-8930-987F8EE3835A:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "8ABBC275-0A33-4834-8930-987F8EE3835A", generation: 0)
[ThaliCore] Browser: s,ession notConnected removed relay for Peer(uuid: "8ABBC275-0A33-4834-8930-987F8EE3835A", generation: 0)
,# setup
,2017-07-14 12:41:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 12:41:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 12:41:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:41:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 12:41:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 12:41:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:41:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:41:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# We do not emit peerAvailabilityChanged events until one of the start methods is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:3A0DC24D-0D7D-404D-B308-A94277F8A34F
,[ThaliCore] Browser.startListening
,2017-07-14 12:41:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 12:41:32 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-14 12:41:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 127 We should start listening fine
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C9B187BB-C74A-4332-BEEC-8E80FFCFA986", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:C9B187BB-C74A-4332-BEEC-8E80FFCFA986
,2017-07-14 12:41:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-14 12:41:32 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-14 12:41:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 128 We should start updating fine
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:05F6B8F2-51F6-437E-B02A-47E24E1B1558:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "05F6B8F2-51F6-437E-B02A-47E24E1B1558", generation: 0)
2017-07-14 12:41:32 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"05F6B8F2-51F6-437E-B02A-47E24E1B1558","generation":0}]'
2017-07-14 12:41:32 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"05F6B8F2-51F6-437E-B02A-47E24E1B1558","generation":0}'
2017-07-14 12:41:32 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started sta,te'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4AAB776C-211D-47ED-BBDD-F924EF51954D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4AAB776C-211D-47ED-BBDD-F924EF51954D", generation: 0)
2017-07-14 12:41:32 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"4AAB776C-211D-47ED-BBDD-F924EF51954D","generation":0}]'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8ABB,C275-0A33-4834-8930-987F8EE3835A:0
2017-07-14 12:41:32 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"4AAB776C-211D-47ED-BBDD-F924EF51954D","generation":0}'
[ThaliCore] BrowserMana,ger.foundPeerHandler peer:Peer(uuid: "8ABBC275-0A33-4834-8930-987F8EE3835A", generation: 0)
2017-07-14 12:41:32 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-14 12:41:32 - DE,BUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"8ABBC275-0A33-4834-8930-987F8EE3835A","generation":0}]'
,2017-07-14 12:41:32 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"8ABBC275-0A33-4834-8930-987F8EE3835A","generation":0}'
,2017-07-14 12:41:32 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C9B187BB-C74A-4332-BEEC-8E80FFCFA986:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C9B187BB-C74A-4332-BEEC-8E80FFCFA986", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1383F40C-96B4-4A21-A631-CDF40A05698D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1383F40C-96B4-4A21-A631-CDF40A05698D", generation: 0)
2017-07-14 12:41:33 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"1383F40C-96B4-4A21-A631-CDF40A05698D","generation":0}]'
2017-07-14 12:41:33 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"1383F40C-96B4-4A21-A631-CDF40A05698D","generation":0}'
2017-07-14 12:41:33 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started sta,te'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:8ABBC275-0A33-4834-8930-987F8EE3835A:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "8ABBC275-0A33-4834-8930-987F8EE3835A", generation: 0)
2017-07-14 12:41:34 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"8ABBC275-0A33-4834-8930-987F8EE3835A","generation":0}]'
2017-07-14 12:41:34 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"8ABBC275-0A33-4834-8930-987F8EE3835A","generation":0}'
2017-07-14 12:41:34 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:05F6B8F2-51F6-437E-B02A-47E24E1B1558:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "05F6B8F2-51F6-437E-B02A-47E24E1B1558", generation: 0)
2017-07-14 12:41:36 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"05F6B8F2-51F6-437E-B02A-47E24E1B1558","generation":0}]'
2017-07-14 12:41:36 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"05F6B8F2-51F6-437E-B02A-47E24E1B1558","generation":0}'
2017-07-14 12:41:36 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-14 12:41:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-14 12:41:38 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 12:41:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 129 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
,2017-07-14 12:41:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:41:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 130 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-14 12:41:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 12:41:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 12:41:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:41:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 12:41:38 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 12:41:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:41:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:41:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Test updating advertising and parallel data transfer
,2017-07-14 12:41:38 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test updating advertising and parallel data transfer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 12:41:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:41:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 131 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 12:41:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:41:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 132 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-14 12:41:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 12:41:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 12:41:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:41:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 12:41:38 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 12:41:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:41:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:41:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# discoveryAdvertisingStateUpdateNonTCP is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:709F8F89-0F61-453D-9B95-4EB79FF4D29D
,[ThaliCore] Browser.startListening
,ok 133 discoveryActive should be false
,ok 134 advertisingActive should be true
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C2D7C722-8FCE-4817-A6FD-D5ACBD656E12", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:C2D7C722-8FCE-4817-A6FD-D5ACBD656E12
,ok 135 discoveryActive should be false
ok 136 advertisingActive should be true
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
ok 137 discoveryActive should be false
ok 138 advertisingActive should be tr,ue
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
ok 139 discoveryActive should be false
,ok 140 advertisingActive should be true
,ok 141 Can call startListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,ok 142 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,ok 143 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# cannot call connect when start listening for advertisements is not active
,2017-07-14 12:41:38 - DEBUG CoordinatedClient: 'test was skipped, name: 'cannot call connect when start listening for advertisements is not active''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,ok 144 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,ok 145 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# Get error when trying to double connect to a peer on Android
,2017-07-14 12:41:39 - DEBUG CoordinatedClient: 'test was skipped, name: 'Get error when trying to double connect to a peer on Android''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
ok 146 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
ok 147 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection
,2017-07-14 12:41:39 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,ok 148 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
ok 149 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection
,2017-07-14 12:41:40 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,ok 150 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,ok 151 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer
,2017-07-14 12:41:40 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,ok 152 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
ok 153 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer
,2017-07-14 12:41:41 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,ok 154 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
ok 155 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-14 12:41:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 12:41:41 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 12:41:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:41:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 12:41:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 12:41:41 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:41:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:41:41 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# cannot call multiConnect when start listening for advertisements is not active
,ok 156 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) peer:fe1f459b-0d4f-4c77-af93-ab0a347fe568 error: startListeningNotActive
,2017-07-14 12:41:41 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"O46Tj1rxfqkmV6QB8mapW6Fh1NtthI92","error":"startListeningForAdvertisements is not active","portNumber":null}'
,ok 157 Should only get called after multiConnect returned
,ok 158 SyncValue matches
,ok 159 Got right error
,ok 160 listeningPort is null
,2017-07-14 12:41:41 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"fe1f459b-0d4f-4c77-af93-ab0a347fe568","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-14 12:41:41 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-14 12:41:41 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"fe1f459b-0d4f-4c77-af93-ab0a347fe568","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-14 12:41:41 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 12:41:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:41:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 161 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 12:41:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:41:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 162 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-14 12:41:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 12:41:41 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 12:41:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:41:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 12:41:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 12:41:41 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:41:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:41:41 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# cannot call multiConnect with illegal peerID
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:67FB26F5-8F20-46C9-A59A-1F5E43E284DF
,[ThaliCore] Browser.startListening
,2017-07-14 12:41:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 12:41:41 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-14 12:41:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 163 No error on starting
ok 164 Got null as expected
,2017-07-14 12:41:41 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"BWPutw6iPLGrmJrVppAutBtsLZFaSI2u","error":"Illegal peerID","portNumber":null}'
,ok 165 Should only get called after multiConnect returned
,ok 166 SyncValue matches
,ok 167 Got right error
ok 168 listeningPort is null
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1383F40C-96B4-4A21-A631-CDF40A05698D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1383F40C-96B4-4A21-A631-CDF40A05698D", generation: 0)
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4AAB776C-211D-47ED-BBDD-F924EF51954D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4AAB776C-211D-47ED-BBDD-F924EF51954D", generation: 0)
2017-07-14 12:41:41 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"1383F40C-96B4-4A21-A631-CDF40A05698D","generation":0}]'
2017-07-14 12:41:41 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"1383F40C-96B4-4A21-A631-CDF40A05698D","generation":0}'
,2017-07-14 12:41:41 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-14 12:41:41 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"4AAB776C-211D-47ED-BBDD-F924EF51954D","generation":0}]'
,2017-07-14 12:41:41 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"4AAB776C-211D-47ED-BBDD-F924EF51954D","generation":0}'
,2017-07-14 12:41:41 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-14 12:41:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:41:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 169 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-14 12:41:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:41:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 170 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-14 12:41:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 12:41:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:41:42 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
,ok 171 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 12:41:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:41:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
,# cannot call multiConnect with invalid syncValue
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:6E2B711B-D647-4190-BC8D-C639BB6DE4E6
[ThaliCore] Browser.startListening
2017-07-14 12:41:42 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-14 12:41:42 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 12:41:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 173 No error on star,ting
,ok 174 Got right error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1383F40C-96B4-4A21-A631-CDF40A05698D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1383F40C-96B4-4A21-A631-CDF40A05698D", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4AAB776C-211D-47ED-BBDD-F924EF51954D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4AAB776C-211D-47ED-BBDD-F924EF51954D", generation: 0)
,# teardown
,2017-07-14 12:41:42 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"1383F40C-96B4-4A21-A631-CDF40A05698D","generation":0}]'
,2017-07-14 12:41:42 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"1383F40C-96B4-4A21-A631-CDF40A05698D","generation":0}'
,2017-07-14 12:41:42 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-14 12:41:42 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"4AAB776C-211D-47ED-BBDD-F924EF51954D","generation":0}]'
,2017-07-14 12:41:42 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"4AAB776C-211D-47ED-BBDD-F924EF51954D","generation":0}'
,2017-07-14 12:41:42 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-14 12:41:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:41:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 175 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 12:41:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:41:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 176 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-14 12:41:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 12:41:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 12:41:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:41:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 12:41:42 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 12:41:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:41:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:41:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# cannot call disconnect with invalid peer id
,ok 177 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 12:41:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:41:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 178 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 12:41:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:41:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 179 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-14 12:41:43 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 12:41:43 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:41:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:41:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 12:41:43 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 12:41:43 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:41:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:41:43 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# disconnect doesn't fail on plausible but bogus peer ID
,[ThaliCore] BrowserManager.disconnect peer:d71984ed-f229-43a6-8421-45ce7e62dcd7
,ok 180 No error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-14 12:41:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:41:43 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 181 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-14 12:41:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:41:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 182 Should be able to call stopAdvertisingAndListening in tea,rdown
,# setup
,2017-07-14 12:41:43 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 12:41:43 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:41:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:41:44 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 12:41:44 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 12:41:44 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:41:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:41:44 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Get same port when trying to connect multiple times on iOS
,2017-07-14 12:41:44 - DEBUG CoordinatedClient: 'test was skipped, name: 'Get same port when trying to connect multiple times on iOS''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-14 12:41:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:41:44 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 183 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-14 12:41:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:41:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 184 Should be able to call stopAdvertisingAndListening in tea,rdown
,# setup
,# initial peer discovery
,2017-07-14 12:41:44 - DEBUG CoordinatedClient: 'test was skipped, name: 'initial peer discovery''
,# teardown
,2017-07-14 12:41:44 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 12:41:44 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:41:44 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:41:44 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 12:41:44 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 12:41:44 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:41:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:41:44 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 1
,2017-07-14 12:41:45 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 1''
,# teardown
,2017-07-14 12:41:45 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 12:41:45 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 12:41:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:41:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 12:41:45 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 12:41:45 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:41:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:41:45 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 2
,2017-07-14 12:41:45 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 2''
,# teardown
,2017-07-14 12:41:45 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 12:41:45 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:41:45 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:41:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 12:41:45 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 12:41:45 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:41:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:41:45 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# check latest peer discovery
,2017-07-14 12:41:45 - DEBUG CoordinatedClient: 'test was skipped, name: 'check latest peer discovery''
,# teardown
,2017-07-14 12:41:46 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 12:41:46 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:41:46 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:41:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 12:41:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 12:41:46 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:41:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:41:46 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Set up for no peer discovery test
,2017-07-14 12:41:46 - DEBUG CoordinatedClient: 'test was skipped, name: 'Set up for no peer discovery test''
,# teardown
,2017-07-14 12:41:46 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 12:41:46 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 12:41:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
,2017-07-14 12:41:46 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 12:41:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:41:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 12:41:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 12:41:46 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:41:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:41:46 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calling createNativeListener directly rejects
,2017-07-14 12:41:46 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-14 12:41:46 - DEBUG createNativeListener: 'listening 50444'
,ok 185 Should throw
,# teardown
,2017-07-14 12:41:46 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-14 12:41:46 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-14 12:41:46 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits incomingConnectionState
,2017-07-14 12:41:46 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-14 12:41:46 - DEBUG createNativeListener: 'listening 50446'
,2017-07-14 12:41:46 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-14 12:41:46 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 186 initial connection state should be CONNECTED
,2017-07-14 12:41:47 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 187 final connection state should be DISCONNECTED
,# teardown
,2017-07-14 12:41:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 12:41:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 12:41:47 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits routerPortConnectionFailed
,2017-07-14 12:41:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 12:41:47 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-14 12:41:47 - DEBUG createNativeListener: 'listening 50449'
,2017-07-14 12:41:47 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-14 12:41:47 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-14 12:41:47 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-14 12:41:47 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - error Error: connect ECONNREFUSED'
,ok 188 tried to connect to right port
,ok 189 failed due to refused connection
,ok 190 routerPortConnectionFailed is emitted
,# teardown
,2017-07-14 12:41:47 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-14 12:41:47 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-14 12:41:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 12:41:47 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-14 12:41:47 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-14 12:41:47 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server connections all up
,2017-07-14 12:41:47 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-14 12:41:47 - DEBUG createNativeListener: 'listening 50453'
,2017-07-14 12:41:47 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-14 12:41:47 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-14 12:41:47 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-14 12:41:47 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,ok 191 Send/recvd #1 should be equal length
,ok 192 Send/recvd #1 should be same
,ok 193 Send/recvd #2 should be equal length
,ok 194 Send/recvd #2 should be same
,ok 195 Should be exactly 2 client sockets
,# teardown
,2017-07-14 12:41:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 12:41:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 12:41:48 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-14 12:41:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-14 12:41:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
,2017-07-14 12:41:48 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-14 12:41:48 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,2017-07-14 12:41:48 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-07-14 12:41:48 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# native server - closing incoming stream cleans outgoing socket
,2017-07-14 12:41:48 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-14 12:41:48 - DEBUG createNativeListener: 'listening 50458'
,2017-07-14 12:41:48 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-14 12:41:48 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-14 12:41:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-14 12:41:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-07-14 12:41:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,ok 196 socket shouldn't close until after stream
,ok 197 incoming remains open
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
2017-07-14 12:41:48 - DEBUG createNativeListener: 'listening 50462'
,2017-07-14 12:41:48 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-14 12:41:48 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 198 we should not have gotten an error
,2017-07-14 12:41:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-14 12:41:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-14 12:41:48 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 199 socket shouldn't close until after incoming
,ok 200 incoming is cleaned up
,# teardown
,2017-07-14 12:41:48 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-14 12:41:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 12:41:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-14 12:41:48 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - closing outgoing socket cleans associated mux stream
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-14 12:41:49 - DEBUG createNativeListener: 'listening 50466'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-14 12:41:49 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,ok 201 stream was closed
,ok 202 incoming should survive
,ok 203 mux should have no streams
,# teardown
,2017-07-14 12:41:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 12:41:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing the whole server cleans everything up
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'listening 50470'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 204 we should not have gotten an error
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 205 Buffers are identical
,2017-07-14 12:41:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 206 native server is nulled out
,ok 207 native server should be closed
,ok 208 incoming has been removed
,ok 209 Incoming should be done
,ok 210 The mux object should be closed
,ok 211 The mux stream should be closed
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# teardown
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-14 12:41:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - we can get a ton of connections and data through and still clean up the server completely
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'listening 50474'
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
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - created'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - created'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - created'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - created'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - created'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - created'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - created'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - created'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - created'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - created'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - created'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - created'
,2017-07-14 12:41:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - closed'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - closed'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - closed'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - closed'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - closed'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - closed'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - closed'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - closed'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - closed'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - closed'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - closed'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - closed'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - closed'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - closed'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - closed'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - closed'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - closed'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - closed'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - closed'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - closed'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - closed'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - closed'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - closed'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - closed'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - closed'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - closed'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - closed'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - closed'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - closed'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - closed'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - closed'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - closed'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - closed'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - closed'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - closed'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - closed'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - closed'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - closed'
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,ok 212 native server is nulled out
,ok 213 native server should be closed
,ok 214 incoming has been removed
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
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - close'
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
,2017-07-14 12:41:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - simulate mux failure, make sure everything is cleaned up
,2017-07-14 12:41:55 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-14 12:41:55 - DEBUG createNativeListener: 'listening 50526'
,2017-07-14 12:41:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-14 12:41:55 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 215 we should not have gotten an error
,2017-07-14 12:41:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 216 Buffers are identical
,2017-07-14 12:41:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-14 12:41:55 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-14 12:41:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 217 server should be fine
,ok 218 server should be open
,ok 219 incoming has been removed
,ok 220 The mux object should be closed
,ok 221 The mux stream should be closed
,2017-07-14 12:41:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-14 12:41:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-14 12:41:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-14 12:41:55 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - timing out the incoming connection cleans everything up
,2017-07-14 12:41:55 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-14 12:41:55 - DEBUG createNativeListener: 'listening 50530'
,2017-07-14 12:41:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-14 12:41:55 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 222 we should not have gotten an error
,2017-07-14 12:41:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 223 Buffers are identical
,2017-07-14 12:41:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - incoming socket timeout'
,2017-07-14 12:41:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-14 12:41:55 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-14 12:41:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 224 server should be fine
,ok 225 server should be open
,ok 226 incoming has been removed
,ok 227 The mux object should be closed
,ok 228 The mux stream should be closed
,# teardown
,2017-07-14 12:41:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-14 12:41:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-14 12:41:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-14 12:41:55 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# can create servers manager
,ok 229 serversManager must not be null
ok 230 serversManager must be an object
,# teardown
,# setup
,# calling stop without start causes error
,ok 231 We need to call start first
,# teardown
,# setup
,# can start/stop servers manager
,2017-07-14 12:41:56 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-14 12:41:56 - DEBUG createNativeListener: 'listening 50533'
ok 232 port must be in range
,# teardown
,2017-07-14 12:41:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-14 12:41:57 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# starting twice resolves with listening port
,2017-07-14 12:41:57 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-14 12:41:57 - DEBUG createNativeListener: 'listening 50534'
ok 233 second start should return same port
,# teardown
,2017-07-14 12:41:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 12:41:57 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminateIncomingConnection will terminate a connection
,2017-07-14 12:41:57 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-14 12:41:57 - DEBUG createNativeListener: 'listening 50536'
,2017-07-14 12:41:57 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-14 12:41:57 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 234 we should be connected
,2017-07-14 12:41:57 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 235 now we are disconnected
,2017-07-14 12:41:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# teardown
,2017-07-14 12:41:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 12:41:57 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminate an Outgoing connection
,2017-07-14 12:41:58 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 32'
,ok 236 Passed bogus id
,2017-07-14 12:41:58 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 901'
,ok 237 Passed good id but bogus port
,2017-07-14 12:41:58 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 900'
,ok 238 Passed right context
,ok 239 Right server
,ok 240 No error should be set
,ok 241 Retry should be false
,ok 242 We called close server
,# teardown
,# setup
,# Single local http request
,listening on 50538
,ok 243 should be equal
,# teardown
,2017-07-14 12:41:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Single coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "66FCBB9A-2036-4526-9064-41C06DEDA815", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:66FCBB9A-2036-4526-9064-41C06DEDA815
2017-07-14 1,2:41:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 12:41:59 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 12:41:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 244 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:176B5A53-E1B9-4695-BE7A-233BFCE90948
[ThaliCore] Browser.startListening
2017-07-14 12:41:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,",advertisingActive":true}'
2017-07-14 12:41:59 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 12:41:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 245 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2", generation: 0)
2017-07-14 12:41:59 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2","generation":0}'
2017-07-14 12:41:59 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2, (syncValue: 4CtjMrHZgSeIzb0k1sWu9hTeP3ac6gOC)'
2017-07-14 12:41:59 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2", gen,eration: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4AAB776C-211D-47ED-BBDD-F924EF51954D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4AAB776C-211D-47ED-BBDD-F924EF51954D", generation: 0)
,2017-07-14 12:41:59 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"4AAB776C-211D-47ED-BBDD-F924EF51954D","generation":0}'
,2017-07-14 12:42:00 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 4AAB776C-211D-47ED-BBDD-F924EF51954D (syncValue: Nqmotrjks2trz2RaugG9GSjDatSk15qY)'
,2017-07-14 12:42:00 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "4AAB776C-211D-47ED-BBDD-F924EF51954D", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4AAB776C-211D-47ED-BBDD-F924EF51954D", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4AAB776C-211D-47ED-BBDD-F924EF51954D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:72BF5322-2BE1-4356-B635-4EBC6052DD67
[ThaliCore] Advertiser: session connected Peer(uuid: "66FCBB9A-2036-4526-9064-41C06DEDA815", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:72BF5322-2BE1-4356-B635-4EBC6052DD67 state: notConnected -> connecting
[ThaliCore] Session.init(session:identifier:connected:notConnected:,) peer:FC300130-5B0C-4E41-A003-41F0F159FE44
[ThaliCore] Advertiser: session connected Peer(uuid: "66FCBB9A-2036-4526-9064-41C06DEDA815", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:FC300130-5B0C-4E41-A003-41F0F159FE44 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49", generation: 0)
,2017-07-14 12:42:00 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49","generation":0}'
,2017-07-14 12:42:00 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49 (syncValue: FOxyJ7WurlghXNZ8vNKNkAi3pA0HqVzf)'
,2017-07-14 12:42:00 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:66FCBB9A-2036-4526-9064-41C06DEDA815:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "66FCBB9A-2036-4526-9064-41C06DEDA815", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50546
,2017-07-14 12:42:02 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"4CtjMrHZgSeIzb0k1sWu9hTeP3ac6gOC","error":null,"portNumber":50546}'
,2017-07-14 12:42:02 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '4CtjMrHZgSeIzb0k1sWu9hTeP3ac6gOC', error: 'null', listeningPort: '50546''
,2017-07-14 12:42:02 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '4CtjMrHZgSeIzb0k1sWu9hTeP3ac6gOC', error: 'null', listeningPort: '50546''
,2017-07-14 12:42:02 - WARN thaliMobileNativeTestUtils: 'multiConnectResolved received invalid syncValue: '4CtjMrHZgSeIzb0k1sWu9hTeP3ac6gOC', originalSyncValue: 'Nqmotrjks2trz2RaugG9GSjDatSk15qY''
,2017-07-14 12:42:02 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '4CtjMrHZgSeIzb0k1sWu9hTeP3ac6gOC', error: 'null', listeningPort: '50546''
,2017-07-14 12:42:02 - WARN thaliMobileNativeTestUtils: 'multiConnectResolved received invalid syncValue: '4CtjMrHZgSeIzb0k1sWu9hTeP3ac6gOC', originalSyncValue: 'FOxyJ7WurlghXNZ8vNKNkAi3pA0HqVzf''
,ok 246 should be equal
,ok 247 (unnamed assert)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:72BF5322-2BE1-4356-B635-4EBC6052DD67
,[ThaliCore] Session.session(_:peer:didChange:) peer:72BF5322-2BE1-4356-B635-4EBC6052DD67 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:FC300130-5B0C-4E41-A003-41F0F159FE44
,[ThaliCore] Session.session(_:peer:didChange:) peer:FC300130-5B0C-4E41-A003-41F0F159FE44 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50548
,2017-07-14 12:42:03 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"FOxyJ7WurlghXNZ8vNKNkAi3pA0HqVzf","error":null,"portNumber":50548}'
,2017-07-14 12:42:03 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'FOxyJ7WurlghXNZ8vNKNkAi3pA0HqVzf', error: 'null', listeningPort: '50548''
,2017-07-14 12:42:03 - WARN thaliMobileNativeTestUtils: 'multiConnectResolved received invalid syncValue: 'FOxyJ7WurlghXNZ8vNKNkAi3pA0HqVzf', originalSyncValue: 'Nqmotrjks2trz2RaugG9GSjDatSk15qY''
,2017-07-14 12:42:03 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'FOxyJ7WurlghXNZ8vNKNkAi3pA0HqVzf', error: 'null', listeningPort: '50548''
,ok 248 should be equal
,# teardown
,[ThaliCore] BrowserManager.disconnect peer:83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50546
[ThaliCore] Session.disconnect,() peer:83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] BrowserManager.disconnect peer:4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49
[ThaliCore] BrowserRelay.closeRelay() dis,connecting:false
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50548
[ThaliCore] Session.disconnect() peer:4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket, error:nil
[ThaliCore] Session.session(_:peer:didChange:) peer:83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2", generation: 0)
[ThaliCore,] Browser: session notConnected removed relay for Peer(uuid: "83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:72BF5322-2BE1-4356-B635-4EBC6052DD67 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "66FCBB9A-2036-4526-9064-41C06DEDA815", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:FC300130-5B0C-4E41-A003-41F0F159FE44
[ThaliCore] Browse,r: session notConnected removed relay for Peer(uuid: "4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49", generation: 0)
[ThaliCore] Session.deinit peer:FC300130-5B0C-4E41-A003-41F0F159FE44
2017-07-14 12:42:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on serve,r'
,# setup
,# Multiple local http requests
,listening on 50550
,ok 249 should be equal
,ok 250 should be equal
,ok 251 should be equal
,# teardown
,2017-07-14 12:42:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Multiple coordinated request ios native
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "66FCBB9A-2036-4526-9064-41C06DEDA815", generation: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:66FCBB9A-2036-4526-9064-41C06DEDA815
2017-07-14 1,2:42:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-14 12:42:05 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match ,with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 12:42:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was, in stopped state).'
ok 252 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-07-14 12:42:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-14 12:42:05 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 12:42:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 253 Can call startListeningForAdvertisements without error
,[ThaliCore] Session.session(_:peer:didChange:) peer:4AAB776C-211D-47ED-BBDD-F924EF51954D:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "4AAB776C-211D-47ED-BBDD-F924EF51954D", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:4AAB776C-211D-47ED-BBDD-F924EF51954D:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "4AAB776C-211D-47ED-BBDD-F924EF51954D", genera,tion: 0)
2017-07-14 12:42:05 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Nqmotrjks2trz2RaugG9GSjDatSk15qY","error":"Connection could not be established","portNumber":null}'
2017-07-14 12:42:05 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'Nqmotrjks2trz2RaugG9GSjDatSk15qY', error: 'Connection could not be established', listeningPort: '%s''
2017-07-14 12:42:05 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,t,ifier":"4AAB776C-211D-47ED-BBDD-F924EF51954D","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-14 12:42:05 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-14 ,12:42:05 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"4AAB776C-211D-47ED-BBDD-F924EF51954D","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-14 12:42:05 - DEBUG thaliMobileNativeWrapp,er: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-14 12:42:05 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-14 12:42:05 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 4AAB776C-211D-47ED-BBDD-F924EF51954D (syncValue: TY6Lomj,wuxc90AlvRd9CVyl05fNUKyZE)'
2017-07-14 12:42:05 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "4AAB776C-211D-47ED-BBDD-F924EF51954D", generation: 0) new rela,y
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4AAB776C-211D-47ED-BBDD-F924EF51954D", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4AAB776C-211D-47ED-BBDD-F924EF51954,D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49:1
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49", generation: 1)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2:1
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2", generation: 1)
2017-07-14 12:42:06 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49","generation":1}'
,2017-07-14 12:42:06 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49 (syncValue: G11i9TBPX5Ao5iJmTqjw4rh9fFLpYNJr)'
,2017-07-14 12:42:06 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49", generation: 1) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49", generation: 1)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49:1,
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-14 12:42:06 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2","generation":1}'
,2017-07-14 12:42:06 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2 (syncValue: Htfh6DU5O0rrEGCSyI0NHGkwnyVH24jE)'
2017-07-14 12:42:06 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[T,haliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2", generation: 1) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "83C7AA4B-9036-4E41-8DBF-DD,A2A5861AC2", generation: 1)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2:1
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:,socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:72BF5322-2BE1-4356-B635-4EBC6052DD67
[ThaliCore] Advertiser: session connected Peer(uuid: "66FCBB9A-2036-4526-9064-41C06DEDA815", generation: 1)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:72BF5322-2BE1-4356-B635-4EBC6052DD67 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:66FCBB9A-2036-4526-9064-41C06DEDA815:1
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "66FCBB9A-2036-4526-9064-41C06DEDA815", generation: 1)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FC300130-5B0C-4E41-A003-41F0F159FE44
[ThaliCore] Session.session(_:peer:didChange:) peer:FC300130-5B0C-4E41-A003-41F0F159FE44 state: notConnected -> connecting
[ThaliCore] Advertis,er: session connected Peer(uuid: "66FCBB9A-2036-4526-9064-41C06DEDA815", generation: 1)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2:1 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49:1 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:4AAB776C-211D-47ED-BBDD-F924EF51954D:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "4AAB776C-211D-47ED-BBDD-F924EF51954D", generation: 0)
[ThaliCore] Session.disconnect() peer:4AAB776C-211,D-47ED-BBDD-F924EF51954D:0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2:1
,[ThaliCore] Session.session(_:peer:didChange:) peer:83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2:1 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2", generation: 1)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50560
,2017-07-14 12:42:09 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Htfh6DU5O0rrEGCSyI0NHGkwnyVH24jE","error":null,"portNumber":50560}'
,2017-07-14 12:42:09 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'Htfh6DU5O0rrEGCSyI0NHGkwnyVH24jE', error: 'null', listeningPort: '50560''
,2017-07-14 12:42:09 - WARN thaliMobileNativeTestUtils: 'multiConnectResolved received invalid syncValue: 'Htfh6DU5O0rrEGCSyI0NHGkwnyVH24jE', originalSyncValue: 'TY6Lomjwuxc90AlvRd9CVyl05fNUKyZE''
,2017-07-14 12:42:09 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'Htfh6DU5O0rrEGCSyI0NHGkwnyVH24jE', error: 'null', listeningPort: '50560''
2017-07-14 12:42:09 - WARN thaliMobileNativeTestUtils: 'multiConnectResolved received ,invalid syncValue: 'Htfh6DU5O0rrEGCSyI0NHGkwnyVH24jE', originalSyncValue: 'G11i9TBPX5Ao5iJmTqjw4rh9fFLpYNJr''
,2017-07-14 12:42:09 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'Htfh6DU5O0rrEGCSyI0NHGkwnyVH24jE', error: 'null', listeningPort: '50560''
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49:1
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:FC300130-5B0C-4E41-A003-41F0F159FE44
,[ThaliCore] Session.session(_:peer:didChange:) peer:4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49:1 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49", generation: 1)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50562
,ok 254 should be equal
,ok 255 (unnamed assert)
,2017-07-14 12:42:09 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"G11i9TBPX5Ao5iJmTqjw4rh9fFLpYNJr","error":null,"portNumber":50562}'
,2017-07-14 12:42:09 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'G11i9TBPX5Ao5iJmTqjw4rh9fFLpYNJr', error: 'null', listeningPort: '50562''
,2017-07-14 12:42:09 - WARN thaliMobileNativeTestUtils: 'multiConnectResolved received invalid syncValue: 'G11i9TBPX5Ao5iJmTqjw4rh9fFLpYNJr', originalSyncValue: 'TY6Lomjwuxc90AlvRd9CVyl05fNUKyZE''
,2017-07-14 12:42:09 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'G11i9TBPX5Ao5iJmTqjw4rh9fFLpYNJr', error: 'null', listeningPort: '50562''
,[ThaliCore] Session.session(_:peer:didChange:) peer:FC300130-5B0C-4E41-A003-41F0F159FE44 state: connecting -> connected
,ok 256 should be equal
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:72BF5322-2BE1-4356-B635-4EBC6052DD67
,[ThaliCore] Session.session(_:peer:didChange:) peer:72BF5322-2BE1-4356-B635-4EBC6052DD67 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:4AAB776C-211D-47ED-BBDD-F924EF51954D:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "4AAB776C-211D-47ED-BBDD-F924EF51954D", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:4AAB776C-211D-47ED-BBDD-F924EF51954D:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "4AAB776C-211D-47ED-BBDD-F924EF51954D", genera,tion: 0)
2017-07-14 12:42:10 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"TY6Lomjwuxc90AlvRd9CVyl05fNUKyZE","error":"Connection could not be established","portNumber":null}'
,2017-07-14 12:42:10 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'TY6Lomjwuxc90AlvRd9CVyl05fNUKyZE', error: 'Connection could not be established', listeningPort: '%s''
,2017-07-14 12:42:10 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"4AAB776C-211D-47ED-BBDD-F924EF51954D","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-14 12:42:10 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-14 12:42:10 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"4AAB776C-211D-47ED-BBDD-F924EF51954D","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-14 12:42:10 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-14 12:42:10 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-14 12:42:10 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 4AAB776C-211D-47ED-BBDD-F924EF51954D (syncValue: NnRpqOb,qmurdy6D4nyYfq715gSsn76fP)'
2017-07-14 12:42:10 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "4AAB776C-211D-47ED-BBDD-F924EF51954D", generation: 0) new rela,y
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4AAB776C-211D-47ED-BBDD-F924EF51954D", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) error:unavailablePeer
,2017-07-14 12:42:10 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"NnRpqObqmurdy6D4nyYfq715gSsn76fP","error":"Peer is unavailable","portNumber":null}'
,2017-07-14 12:42:10 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'NnRpqObqmurdy6D4nyYfq715gSsn76fP', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-14 12:42:10 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"4AAB776C-211D-47ED-BBDD-F924EF51954D","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-14 12:42:10 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-14 12:42:10 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"4AAB776C-211D-47ED-BBDD-F924EF51954D","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-14 12:42:10 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-14 12:42:10 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,[ThaliCore] BrowserManager.disconnect peer:83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50560
[ThaliCore] Session.disconnect() peer:83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2:1
[ThaliCore] Session.session(_:peer:didChange:) peer:72BF5322-2BE1-4356-B635-4EBC6052DD67 sta,te: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "66FCBB9A-2036-4526-9064-41C06DEDA815", generation: 1)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCP,Client.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:FC300130-5B0C-4E41-A003-41F0F159FE44
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] Session.deinit peer:FC300130-5B0C-4E41-A003-41F0F159FE44
[ThaliCore] BrowserManager.disconnect peer:4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49
,[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50562
,[ThaliCore] Session.disconnect() peer:4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49:1
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] Session.session(_:peer:didChange:) peer:83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2:1 s,tate: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2", generation: 1)
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2", gen,eration: 1)
[ThaliCore] Session.session(_:peer:didChange:) peer:4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49:1 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49", generation: 1)
[ThaliCor,e] Browser: session notConnected removed relay for Peer(uuid: "4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49", generation: 1)
2017-07-14 12:42:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,2017-07-14 12:42:10 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 12:42:10 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 12:42:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,[ThaliCore] AdvertiserRelay.deinit
,2017-07-14 12:42:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 12:42:10 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 12:42:10 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:42:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:42:10 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# #startListeningForAdvertisements should fail if start not called
,ok 257 specific error should be returned
,# teardown
,ok 258 must be stopped
,# setup
,2017-07-14 12:42:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 12:42:11 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:42:11 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:42:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 12:42:11 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 12:42:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:42:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:42:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# #startUpdateAdvertisingAndListening should fail if start not called
,ok 259 specific error should be returned
,# teardown
,ok 260 must be stopped
,# setup
,2017-07-14 12:42:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 12:42:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:42:12 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:42:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 12:42:12 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 12:42:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:42:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:42:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# should be able to call #stopListeningForAdvertisements many times
,2017-07-14 12:42:12 - DEBUG thaliMobileNativeWrapper: 'listening 50564'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-14 12:42:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 12:42:12 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 12:42:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 261 no errors
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 12:42:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-14 12:42:12 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-14 12:42:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 262 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,2017-07-14 12:42:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:42:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 12:42:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:42:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 12:42:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 263 must be stopped
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
,2017-07-14 12:42:12 - DEBUG thaliMobileNativeWrapper: 'listening 50565'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:73081CB5-8941-49D2-AF42-2561EC46B08C
,[ThaliCore] Browser.startListening
,2017-07-14 12:42:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-14 12:42:12 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 12:42:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 264 no errors
[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-07-14 12:42:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 12:42:12 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-14 12:42:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 265 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-14 12:42:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-14 12:42:12 - INFO thaliMobile: 'Received state ({"d,iscoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 12:42:12 - INFO ,thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-14 12:42:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisi,ngStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:42:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-14 12:42:12 - DEBUG makeIntoCloseAllServer: 'closeAll called, on server'
,ok 266 must be stopped
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
,2017-07-14 12:42:12 - DEBUG thaliMobileNativeWrapper: 'listening 50566'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "471DE75B-527B-4CF0-B8FA-6F47BCCC9CF7", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:471DE75B-527B-4CF0-B8FA-6F47BCCC9CF7
,2017-07-14 12:42:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 12:42:12 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 12:42:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 267 no errors
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "471DE75B-527B-4CF0-B8FA-6F47BCCC9CF7", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:471DE75B-527B-4CF0-B8FA-6F47BCCC9CF7
,2017-07-14 12:42:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 12:42:12 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 12:42:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 268 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
2017-07-14 12:42:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:42:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-14 12:42:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpd,ateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:42:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 12:42:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 269 must be stopped
,# setup
,2017-07-14 12:42:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 12:42:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 12:42:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:42:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 12:42:12 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-07-14 12:42:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:42:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:42:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# should be able to call #stopAdvertisingAndListening many times
,2017-07-14 12:42:13 - DEBUG thaliMobileNativeWrapper: 'listening 50569'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 12:42:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:42:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 270 no errors
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 12:42:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:42:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 271 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 12:42:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:42:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 12:42:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:42:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 12:42:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 272 must be stopped
,# setup
,2017-07-14 12:42:13 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 12:42:13 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:42:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:42:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 12:42:13 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 12:42:13 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:42:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:42:13 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# can get the network status before starting
,ok 273 network status should have certain non-empty properties
,# teardown
,ok 274 must be stopped
,# setup
,2017-07-14 12:42:13 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 12:42:13 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:42:13 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:42:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 12:42:13 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 12:42:13 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:42:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:42:13 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# error returned with bad router
,2017-07-14 12:42:13 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a string'
,ok 275 specific error expected
,# teardown
,ok 276 must be stopped
,# setup
,2017-07-14 12:42:13 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 12:42:13 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 12:42:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:42:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 12:42:13 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 12:42:13 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:42:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:42:13 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# all services are started when we call start
,2017-07-14 12:42:13 - DEBUG thaliMobileNativeWrapper: 'listening 50570'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:30F00533-730C-4587-BE3C-AE8A9839D6D3
,[ThaliCore] Browser.startListening
,2017-07-14 12:42:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 12:42:13 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-14 12:42:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "35ADDFAF-6ADB-4BD3-96C0-36A2988E6D91", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:35ADDFAF-6ADB-4BD3-96C0-36A2988E6D91
,2017-07-14 12:42:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-14 12:42:13 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 12:42:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 277 all connection succeed
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
,2017-07-14 12:42:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 12:42:14 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-14 12:42:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-14 12:42:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:42:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 12:42:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 278 must be stopped
,# setup
,2017-07-14 12:42:14 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 12:42:14 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 12:42:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:42:14 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 12:42:14 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 12:42:14 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:42:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:42:14 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# TCP Servers Manager should be null when we call start on iOS
,2017-07-14 12:42:14 - DEBUG thaliMobileNativeWrapper: 'listening 50573'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:50631D4A-6BDC-433A-BD01-455ACCE2C15C
,[ThaliCore] Browser.startListening
,2017-07-14 12:42:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 12:42:14 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 12:42:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "366B83F7-2370-4678-9414-3DB98B67E140", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:366B83F7-2370-4678-9414-3DB98B67E140
,2017-07-14 12:42:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-14 12:42:14 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 12:42:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 279 TCP Servers Manager doesn't exists
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
,2017-07-14 12:42:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 12:42:14 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 12:42:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-14 12:42:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:42:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 12:42:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 280 must be stopped
,# setup
,2017-07-14 12:42:14 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 12:42:14 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 12:42:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:42:14 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 12:42:14 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 12:42:14 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:42:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:42:14 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# all services are stopped when we call stop
,2017-07-14 12:42:14 - DEBUG thaliMobileNativeWrapper: 'listening 50575'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:DA69D83F-4EBC-4829-BA61-3E550E19EB54
,[ThaliCore] Browser.startListening
,2017-07-14 12:42:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 12:42:14 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 12:42:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49", generation: 0)
[ThaliCore] AdvertiserManager,.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "F71F1629-1698-4EFD-A66B-0100BE615CA4", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:F71F1629-1698-4EFD-A66B-0100BE615CA4
,2017-07-14 12:42:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-14 12:42:14 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 12:42:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
2017-07-14 12:42:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-14 12:42:1,4 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkT,ype":null}})'
,2017-07-14 12:42:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-14 12:42:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:42:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
2017-07-14 12:42:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 281 is stopped after calling stop
,2017-07-14 12:42:14 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49","generation":0}]'
,2017-07-14 12:42:14 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49","generation":0}'
,2017-07-14 12:42:14 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,ok 282 connection should fail after stopping
,# teardown
,ok 283 must be stopped
,# setup
,2017-07-14 12:42:15 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 12:42:15 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 12:42:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:42:15 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 12:42:15 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 12:42:15 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:42:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:42:15 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# make sure terminateConnection is properly hooked up
,2017-07-14 12:42:15 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateConnection is properly hooked up''
,# teardown
,ok 284 must be stopped
,# setup
,2017-07-14 12:42:15 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 12:42:15 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:42:15 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:42:15 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 12:42:15 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 12:42:15 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:42:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:42:15 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# make sure terminateConnection is return error if we get called on iOS
,ok 285 error description matches
,# teardown
,ok 286 must be stopped
,# setup
,2017-07-14 12:42:16 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 12:42:16 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:42:16 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:42:16 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 12:42:16 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 12:42:16 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:42:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:42:16 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# make sure terminateListener is properly hooked up
,2017-07-14 12:42:16 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateListener is properly hooked up''
,# teardown
,ok 287 must be stopped
,# setup
,2017-07-14 12:42:16 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 12:42:16 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 12:42:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:42:16 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 12:42:16 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 12:42:16 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:42:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:42:16 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# make sure terminateListener is return error if we get called on iOS
,ok 288 error description matches
,# teardown
,ok 289 must be stopped
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
,ok 290 IMPLEMENT ME!!!!!!
,# teardown
,ok 291 must be stopped
,# setup
,2017-07-14 12:42:17 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 12:42:17 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:42:17 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:42:17 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 12:42:17 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 12:42:17 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:42:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:42:17 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
,2017-07-14 12:42:17 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''
,# teardown
,ok 292 must be stopped
,# setup
,2017-07-14 12:42:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 12:42:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:42:18 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:42:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 12:42:18 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 12:42:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:42:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:42:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager
,2017-07-14 12:42:18 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''
,# teardown
,ok 293 must be stopped
,# setup
,2017-07-14 12:42:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 12:42:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 12:42:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:42:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 12:42:18 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 12:42:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:42:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:42:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# We fire failedNativeConnection event when we get failedConnection from multiConnectConnection
,2017-07-14 12:42:18 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 294 must be stopped
,# setup
,2017-07-14 12:42:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 12:42:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 12:42:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:42:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 12:42:18 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 12:42:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:42:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:42:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection
,2017-07-14 12:42:18 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 295 must be stopped
,# setup
,2017-07-14 12:42:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 12:42:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:42:19 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:42:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 12:42:19 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 12:42:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:42:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:42:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved
,ok 296 NOT IMPLEMENTED # SKIP
,# teardown
,ok 297 must be stopped
,# setup
,2017-07-14 12:42:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 12:42:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 12:42:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:42:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 12:42:19 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 12:42:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:42:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:42:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# make sure bad PSK connections fail
,2017-07-14 12:42:19 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure bad PSK connections fail''
,# teardown
,ok 298 must be stopped
,# setup
,2017-07-14 12:42:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 12:42:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 12:42:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:42:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 12:42:19 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 12:42:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:42:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:42:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# peer changes handled from a queue
,2017-07-14 12:42:19 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer changes handled from a queue''
,# teardown
,ok 299 must be stopped
,# setup
,2017-07-14 12:42:20 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 12:42:20 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:42:20 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:42:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 12:42:20 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 12:42:20 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:42:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:42:20 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# relaying discoveryAdvertisingStateUpdateNonTCP
,2017-07-14 12:42:20 - DEBUG CoordinatedClient: 'test was skipped, name: 'relaying discoveryAdvertisingStateUpdateNonTCP''
,# teardown
,ok 300 must be stopped
,# setup
,2017-07-14 12:42:20 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 12:42:20 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 12:42:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:42:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 12:42:20 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 12:42:20 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:42:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:42:20 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received
,2017-07-14 12:42:20 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''
,# teardown
,ok 301 must be stopped
,# setup
,2017-07-14 12:42:20 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 12:42:20 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 12:42:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:42:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 12:42:20 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 12:42:20 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:42:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:42:20 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# we successfully receive and replay discoveryAdvertisingStateUpdate
,2017-07-14 12:42:21 - DEBUG thaliMobileNativeWrapper: 'listening 50578'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:AA4BB6B0-F1A8-4963-B681-FDA73FB27531
,[ThaliCore] Browser.startListening
,2017-07-14 12:42:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 12:42:21 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-14 12:42:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 302 discoveryActive matches
,ok 303 advertisingActive matches
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2", generation: 0)
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 12:42:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 12:42:21 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-14 12:42:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-14 12,:42:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:42:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 304 discoveryActive matches
,ok 305 advertisingActive matches
2017-07-14 12:42:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 12:42:21 - DEBUG thaliMobileNativeWrapper: 'listening 50579'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "6F546E36-F6C7-48DD-8ABF-5AF31F664860", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:6F546E36-F6C7-48DD-8ABF-5AF31F664860
,2017-07-14 12:42:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 12:42:21 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 12:42:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 306 discoveryActive matches
ok 307 advertisingActive matches
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
2017-07-14 12:42:21 - DEBUG thaliMobileNativeWrapper: 'discover,yAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:42:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 308 discoveryActive matches
ok 309 advertisingActive matches
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 12:42:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:42:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 12:42:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 12:42:21 - DEBUG thaliMobileNativeWrapper: 'listening 50581'
,# teardown
,2017-07-14 12:42:21 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2","generation":0}]'
,2017-07-14 12:42:21 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2","generation":0}'
,2017-07-14 12:42:21 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 12:42:21 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 12:42:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:42:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 12:42:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:42:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 12:42:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 310 must be stopped
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
,2017-07-14 12:42:21 - DEBUG thaliMobileNativeWrapper: 'listening 50582'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:CB7FBDB3-51C5-4D58-9CBD-5FD8FDBD18FC
,[ThaliCore] Browser.startListening
,2017-07-14 12:42:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 12:42:21 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 12:42:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49", generation: 0)
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "6980841D-D3F4-4446-9794-FA01462D60CD", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:6980841D-D3F4-4446-9794-FA01462D60CD
2017-07-14 12:42:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-14 12:42:21 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-14 12:42:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2:1
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2", generation: 1)
,2017-07-14 12:42:21 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49","generation":0}]'
,2017-07-14 12:42:21 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49","generation":0}'
,2017-07-14 12:42:21 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2","generation":0}]'
,2017-07-14 12:42:21 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2","generation":0}'
,2017-07-14 12:42:21 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2","generation":1}]'
,2017-07-14 12:42:21 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2","generation":1}'
,2017-07-14 12:42:21 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 12:42:21 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 311 portNumber equal null
,2017-07-14 12:42:21 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 12:42:21 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2","peerAvailable":true,"generation":1,"portNumber":null}'
,2017-07-14 12:42:21 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2","connectionType":"MPCF","peerAvailable":true,"generation":1,"newAddressPort":false}'
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BB105E64-5250-4426-A525-642D03982494:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BB105E64-5250-4426-A525-642D03982494", generation: 0)
2017-07-14 12:42:22 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"BB105E64-5250-4426-A525-642D03982494","generation":0}]'
2017-07-14 12:42:22 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"BB105E64-5250-4426-A525-642D03982494","generation":0}'
,2017-07-14 12:42:22 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"BB105E64-5250-4426-A525-642D03982494","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-14 12:42:22 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"BB105E64-5250-4426-A525-642D03982494","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,2017-07-14 12:42:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 12:42:22 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 12:42:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-14 12:42:22 - DEBUG thaliMobileNativeW,rapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:42:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-14 12:42:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 312 must be stopped
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
,2017-07-14 12:42:22 - DEBUG thaliMobileNativeWrapper: 'listening 50584'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:28370A2A-E219-4A5F-8A3C-00058FE10BD5
,[ThaliCore] Browser.startListening
,2017-07-14 12:42:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 12:42:22 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 12:42:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "CB92173D-6293-4EBE-A0FB-A434DD62F620", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:CB92173D-6293-4EBE-A0FB-A434DD62F620
2017-07-14 1,2:42:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-14 12:42:22 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-14 12:42:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BB105E64-5250-4426-A525-642D03982494:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BB105E64-5250-4426-A525-642D03982494", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2:1
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2", generation: 1)
,2017-07-14 12:42:23 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49","generation":0}]'
,2017-07-14 12:42:23 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49","generation":0}'
,2017-07-14 12:42:23 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"BB105E64-5250-4426-A525-642D03982494","generation":0}]'
,2017-07-14 12:42:23 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"BB105E64-5250-4426-A525-642D03982494","generation":0}'
,2017-07-14 12:42:23 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2","generation":0}]'
,2017-07-14 12:42:23 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2","generation":0}'
,2017-07-14 12:42:23 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2","generation":1}]'
,2017-07-14 12:42:23 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2","generation":1}'
,2017-07-14 12:42:23 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 12:42:23 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 12:42:23 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49 (syncValue: o1Zpp73LRgxeLPKEUN4l5ED8MXBtOb8M)'
,2017-07-14 12:42:23 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49", generation: 1) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49", generation: 1)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) error:unavailablePeer
,2017-07-14 12:42:23 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"o1Zpp73LRgxeLPKEUN4l5ED8MXBtOb8M","error":"Peer is unavailable","portNumber":null}'
,2017-07-14 12:42:23 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'o1Zpp73LRgxeLPKEUN4l5ED8MXBtOb8M', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-14 12:42:23 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-14 12:42:23 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-14 12:42:23 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"BB105E64-5250-4426-A525-642D03982494","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 12:42:23 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"BB105E64-5250-4426-A525-642D03982494","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 12:42:23 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 12:42:23 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 12:42:23 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2","peerAvailable":true,"generation":1,"portNumber":null}'
,2017-07-14 12:42:23 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2","peerAvailable":true,"generation":1,"portNumber":null}'
,2017-07-14 12:42:23 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-14 12:42:23 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-14 12:42:23 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-14 12:42:23 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-14 12:42:23 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-14 12:42:23 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,2017-07-14 12:42:23 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for BB105E64-5250-4426-A525-642D03982494 (syncValue: EX5tddtWguadQG9D4TE9lHBNXPx6Qi3M)'
,2017-07-14 12:42:23 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "BB105E64-5250-4426-A525-642D03982494", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BB105E64-5250-4426-A525-642D03982494", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:BB105E64-5250-4426-A525-642D03982494:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CB92173D-6293-4EBE-A0FB-A434DD62F620:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CB92173D-6293-4EBE-A0FB-A434DD62F620", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D8A1E24E-AAA7-492E-9A14-1611985D239C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D8A1E24E-AAA7-492E-9A14-1611985D239C", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49", generation: 0)
2017-07-14 12:42:24 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"D8A1E24E-AAA7-492E-9A14-1611985D239C","generation":0}]'
2017-07-14 12:42:24 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event ,with {"peerAvailable":true,"peerIdentifier":"D8A1E24E-AAA7-492E-9A14-1611985D239C","generation":0}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2:1
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2", generation: 1)
,2017-07-14 12:42:24 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"D8A1E24E-AAA7-492E-9A14-1611985D239C","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 12:42:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"D8A1E24E-AAA7-492E-9A14-1611985D239C","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-14 12:42:24 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"D8A1E24E-AAA7-492E-9A14-1611985D239C","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A1B452C7-1CA9-493B-B5D2-61CAF3066822:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A1B452C7-1CA9-493B-B5D2-61CAF3066822", generation: 0)
2017-07-14 12:42:24 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"pee,rIdentifier":"83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2","generation":1}]'
,2017-07-14 12:42:24 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2","generation":1}'
,2017-07-14 12:42:24 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"A1B452C7-1CA9-493B-B5D2-61CAF3066822","generation":0}]'
,2017-07-14 12:42:24 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"A1B452C7-1CA9-493B-B5D2-61CAF3066822","generation":0}'
,2017-07-14 12:42:24 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-14 12:42:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-14 12:42:24 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"A1B452C7-1CA9-493B-B5D2-61CAF3066822","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 12:42:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"A1B452C7-1CA9-493B-B5D2-61CAF3066822","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-14 12:42:24 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"A1B452C7-1CA9-493B-B5D2-61CAF3066822","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:BB105E64-5250-4426-A525-642D03982494:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "BB105E64-5250-4426-A525-642D03982494", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:BB105E64-5250-4426-A525-642D03982494:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "BB105E64-5250-4426-A525-642D03982494", genera,tion: 0)
2017-07-14 12:42:29 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"EX5tddtWguadQG9D4TE9lHBNXPx6Qi3M","error":"Connection could not be established","portNumber":null}'
2017-07-14 12:42:29 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'EX5tddtWguadQG9D4TE9lHBNXPx6Qi3M', error: 'Connection could not be established', listeningPort: '%s''
2017-07-14 12:42:29 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,tifier":"BB105E64-5250-4426-A525-642D03982494","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-14 12:42:29 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"BB105E64-5250-4426-A525-642D0,3982494","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-14 12:42:29 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"BB105E64-5250-4426-A525-642D03982494","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-14 12:42:29 - DEBUG thali,Mobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"BB105E64-5250-4426-A525-642D03982494","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-14 12:42:29 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"BB105E64-5250-4426-A525-642D03982494","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-14 12:42:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"BB105E64-5250-4426-A525-642D03982494","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-14 12,:42:29 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"BB105E64-5250-4426-A525-642D03982494","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
2017-07-14 12:42:29 - ERROR thaliMobileNativeTestUtils: 'Fatal conn,ect error: 'Connection could not be established''
,2017-07-14 12:42:29 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for D8A1E24E-AAA7-492E-9A14-1611985D239C (syncValue: cfGbU2Hu921IQzi5CVze7OBVmSP32z0Z)'
,2017-07-14 12:42:29 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:00FF9654-BB0E-4289-89E5-D36EE19979CD
[ThaliCore] Advertiser: session connected Peer(uuid: "CB9,2173D-6293-4EBE-A0FB-A434DD62F620", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:00FF9654-BB0E-4289-89E5-D36EE19979CD state: notConne,cted -> connecting
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "D8A1E24E-AAA7-492E-9A14-1611985D239C", generation: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D8A1,E24E-AAA7-492E-9A14-1611985D239C", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D8A1E24E-AAA7-492E-9A14-1611985D239C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] ,TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:BB105E64-5250-4426-A525-642D03982494:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "BB105E64-5250-4426-A525-642D03982494", generation: 0)
2017-07-14 12:42:30 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"BB105E64-5250-4426-A525-642D03982494","generation":0}]'
2017-07-14 12:42:30 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"BB105E64-5250-4426-A525-642D03982494","generation":0}'
,2017-07-14 12:42:30 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"BB105E64-5250-4426-A525-642D03982494","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-14 12:42:30 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"BB105E64-5250-4426-A525-642D03982494","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:D8A1E24E-AAA7-492E-9A14-1611985D239C:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:00FF9654-BB0E-4289-89E5-D36EE19979CD
,[ThaliCore] Session.session(_:peer:didChange:) peer:00FF9654-BB0E-4289-89E5-D36EE19979CD state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:00FF9654-BB0E-4289-89E5-D36EE19979CD
,[ThaliCore] Session.startOutputStream(with:) peer:00FF9654-BB0E-4289-89E5-D36EE19979CD
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:13 [6, 13]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D8A1E24E-AAA7-492E-9A14-1611985D239C:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:D8A1E24E-AAA7-492E-9A14-1611985D239C:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "D8A1E24E-AAA7-492E-9A14-1611985D239C", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50590
2017-07-14 12:42:35 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"cfGbU2Hu921IQzi5CVze7OBVmSP32z0Z",,"error":null,"portNumber":50590}'
2017-07-14 12:42:35 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'cfGbU2Hu921IQzi5CVze7OBVmSP32z0Z', error: 'null', listeningPort: '50590''
,2017-07-14 12:42:35 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:D8A1E24E-AAA7-492E-9A14-1611985D239C:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D8A1E24E-AAA7-492E-9A14-1611985D239C:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:14 [6, 13, 14]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-14 12:42:35 - DEBUG testUtils: 'Got response data'
,2017-07-14 12:42:35 - DEBUG testUtils: 'Got end'
,ok 313 response body should match testData
ok 314 must be started
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,2017-07-14 12:42:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 12:42:35 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 12:42:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-14 12:42:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:42:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 12:42:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:13
[ThaliCore] Virt,ualSocket.closeStreams() vsID:13
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:13
[ThaliCore] VirtualSocket.deinit vsID:13 [6, 14]
,ok 315 must be stopped
,[ThaliCore] BrowserManager.disconnect peer:D8A1E24E-AAA7-492E-9A14-1611985D239C
,[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50590
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] VirtualSocket.closeStreams() vsID:14
,[ThaliCore] VirtualSocket exited RunLoop vsID:14
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:true
,[ThaliCore] VirtualSocket.deinit vsID:14 [6]
[ThaliCore] Session.disconnect() peer:D8A1E24E-AAA7-492E-9A14-1611985D239C:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:D8A1E24E-AAA7-492E-9A14-1611985D239C:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "D8A1E24E-AAA7-492E-9A14-1611985D239C", generation: 0)
[ThaliCore] BrowserRel,ay.closeRelay() disconnecting:true
,[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "D8A1E24E-AAA7-492E-9A14-1611985D239C", generation: 0)
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:00FF9654-BB0E-4289-89E5-D36EE19979CD state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "CB92173D-6293-4EBE-A0FB-A434DD62F620", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:00FF9654-BB0E-4289-89E5-D36EE19979CD
,[ThaliCore] AdvertiserRelay.deinit
[ThaliCore] Session.deinit peer:00FF9654-BB0E-4289-89E5-D36EE19979CD
,2017-07-14 12:42:35 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 12:42:35 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:42:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:42:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 12:42:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 12:42:35 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:42:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:42:35 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# can still do HTTP requests between peers with coordinator
,2017-07-14 12:42:35 - DEBUG thaliMobileNativeWrapper: 'listening 50592'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:F7E52BED-B2B5-4FE4-A2B1-5D74D7D0FA3F
,[ThaliCore] Browser.startListening
,2017-07-14 12:42:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 12:42:35 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-14 12:42:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "CFD7BC78-6165-4F86-9705-757C7CE0F24C", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:CFD7BC78-6165-4F86-9705-757C7CE0F24C
,2017-07-14 12:42:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-14 12:42:35 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 12:42:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A1B452C7-1CA9-493B-B5D2-61CAF3066822:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A1B452C7-1CA9-493B-B5D2-61CAF3066822", generation: 0)
,2017-07-14 12:42:36 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"A1B452C7-1CA9-493B-B5D2-61CAF3066822","generation":0}]'
,2017-07-14 12:42:36 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"A1B452C7-1CA9-493B-B5D2-61CAF3066822","generation":0}'
,2017-07-14 12:42:36 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"A1B452C7-1CA9-493B-B5D2-61CAF3066822","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 12:42:36 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"A1B452C7-1CA9-493B-B5D2-61CAF3066822","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 12:42:36 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for A1B452C7-1CA9-493B-B5D2-61CAF3066822 (syncValue: AqQmgogujRKztYvK71GmgdyjomAnOub4)'
,2017-07-14 12:42:36 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "A1B452C7-1CA9-493B-B5D2-61CAF3066822", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A1B452C7-1CA9-493B-B5D2-61CAF3066822", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:A1B452C7-1CA9-493B-B5D2-61CAF3066822:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CFD7BC78-6165-4F86-9705-757C7CE0F24C:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CFD7BC78-6165-4F86-9705-757C7CE0F24C", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DA5319DB-DF7F-4F8F-AF8F-6468B727A931:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DA5319DB-DF7F-4F8F-AF8F-6468B727A931", generation: 0)
,2017-07-14 12:42:37 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"DA5319DB-DF7F-4F8F-AF8F-6468B727A931","generation":0}]'
,2017-07-14 12:42:37 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"DA5319DB-DF7F-4F8F-AF8F-6468B727A931","generation":0}'
,2017-07-14 12:42:37 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"DA5319DB-DF7F-4F8F-AF8F-6468B727A931","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 12:42:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"DA5319DB-DF7F-4F8F-AF8F-6468B727A931","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-14 12:42:37 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"DA5319DB-DF7F-4F8F-AF8F-6468B727A931","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:530434CD-FD42-4B00-B7B0-D62CAE9735F1:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "530434CD-FD42-4B00-B7B0-D62CAE9735F1", generation: 0)
2017-07-14 12:42:37 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"530434CD-FD42-4B00-B7B0-D62CAE9735F1","generation":0}]'
2017-07-14 12:42:37 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"530434CD-FD42-4B00-B7B0-D62CAE9735F1","generation":0}'
,2017-07-14 12:42:37 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"530434CD-FD42-4B00-B7B0-D62CAE9735F1","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-14 12:42:37 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"530434CD-FD42-4B00-B7B0-D62CAE9735F1","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-14 12:42:37 - DEBUG thaliMobileNativeTestUtils: 'We got a pe,er {"peerIdentifier":"530434CD-FD42-4B00-B7B0-D62CAE9735F1","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:A1B452C7-1CA9-493B-B5D2-61CAF3066822:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "A1B452C7-1CA9-493B-B5D2-61CAF3066822", generation: 0)
[ThaliCore] Session.disconnect() peer:A1B452C7-1CA,9-493B-B5D2-61CAF3066822:0
2017-07-14 12:42:40 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"A1B452C7-1CA9-493B-B5D2-61CAF3066822","generation":0}]'
2017-07-14 12:42:,40 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"A1B452C7-1CA9-493B-B5D2-61CAF3066822","generation":0}'
,2017-07-14 12:42:40 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"A1B452C7-1CA9-493B-B5D2-61CAF3066822","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-14 12:42:40 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"A1B452C7-1CA9-493B-B5D2-61CAF3066822","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:75023228-E093-46FB-8518-0D06A4A6D6C0
[ThaliCore] Advertiser: session connected Peer(uuid: "CFD7BC78-6165-4F86-9705-757C7CE0F24C", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:75023228-E093-46FB-8518-0D06A4A6D6C0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:A1B452C7-1CA9-493B-B5D2-61CAF3066822:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "A1B452C7-1CA9-493B-B5D2-61CAF3066822", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:A1B452C7-1CA9-493B-B5D2-61CAF3066822:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "A1B452C7-1CA9-493B-B5D2-61CAF3066822", genera,tion: 0)
2017-07-14 12:42:42 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"AqQmgogujRKztYvK71GmgdyjomAnOub4","error":"Connection could not be established","portNumber":null}'
2017-07-14 12:42:42 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'AqQmgogujRKztYvK71GmgdyjomAnOub4', error: 'Connection could not be established', listeningPort: '%s''
2017-07-14 12:42:42 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdent,ifier":"A1B452C7-1CA9-493B-B5D2-61CAF3066822","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-14 12:42:42 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"A1B452C7-1CA9-493B-B5D2-61CAF3066822","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-14 12:42:42 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"A1B452C7-1CA9-493B-B5D2-61CAF3066822","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-14 12:42:42 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"A1B452C7-1CA9-493B-B5D2-61CAF3066822","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-14 12:42:42 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"A1B452C7-1CA9-493B-B5D2-61CAF3066822","peerAvailable":true,"portNumber":null,"recreated":true}'
,[ThaliCore] BrowserManager.disconnect peer:A1B452C7-1CA9-493B-B5D2-61CAF3066822
,2017-07-14 12:42:42 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-14 12:42:42 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for DA5319DB-DF7F-4F8F-AF8F-6468B727A931 (syncValue: 3yYT1glD9dEkoclEJ1X2PDndCDEjnUR8)'
,2017-07-14 12:42:42 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "DA5319DB-DF7F-4F8F-AF8F-6468B727A931", generation: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "DA5319DB-DF7F-4F8F-AF8F-6468B727A931", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:DA5319DB-DF7F-4F8F-AF8F-6468B727A931:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:75023228-E093-46FB-8518-0D06A4A6D6C0
,[ThaliCore] Session.session(_:peer:didChange:) peer:DA5319DB-DF7F-4F8F-AF8F-6468B727A931:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:75023228-E093-46FB-8518-0D06A4A6D6C0 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:75023228-E093-46FB-8518-0D06A4A6D6C0
[ThaliCore] Session.startOutputStream(with:) peer:75023228-E093-46FB-8518-0D06A4A6D6C0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:15 [6, 15]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:DA5319DB-DF7F-4F8F-AF8F-6468B727A931:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:DA5319DB-DF7F-4F8F-AF8F-6468B727A931:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "DA5319DB-DF7F-4F8F-AF8F-6468B727A931", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50600
,2017-07-14 12:42:46 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"3yYT1glD9dEkoclEJ1X2PDndCDEjnUR8","error":null,"portNumber":50600}'
,2017-07-14 12:42:46 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '3yYT1glD9dEkoclEJ1X2PDndCDEjnUR8', error: 'null', listeningPort: '50600''
,2017-07-14 12:42:46 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:DA5319DB-DF7F-4F8F-AF8F-6468B727A931:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:DA5319DB-DF7F-4F8F-AF8F-6468B727A931:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:16 [6, 15, 16]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-14 12:42:46 - DEBUG testUtils: 'Got response data'
,2017-07-14 12:42:46 - DEBUG testUtils: 'Got end'
,ok 316 response body should match testData
,ok 317 must be started
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:44494DD4-12BC-4559-8F3E-EEA02B4449F7
[ThaliCore] Advertiser: session connected Peer(uuid: "CFD7BC78-6165-4F86-9705-757C7CE0F24C", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:44494DD4-12BC-4559-8F3E-EEA02B4449F7 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:44494DD4-12BC-4559-8F3E-EEA02B4449F7
,[ThaliCore] Session.session(_:peer:didChange:) peer:44494DD4-12BC-4559-8F3E-EEA02B4449F7 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:44494DD4-12BC-4559-8F3E-EEA02B4449F7
[ThaliCore] Session.startOutputStream(with:) peer:44494DD4-12BC-4559-8F3E-EEA02B4449F7
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:17 [6, 15, 16, 17]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
2017-07-14 12:42:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 12:42:51 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-14 12:42:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:16
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:17
[ThaliCore] VirtualSocket.closeStreams() vsID:17
,[ThaliCore] VirtualSocket.closeStreams() vsID:16
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:17
[ThaliCore] VirtualSocket exited RunLoop vsID:16
[ThaliCore] VirtualSocket.deinit vsID:17 [6, 15, 16]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] VirtualSocket.deinit vsID:16 [6, 15]
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-14 12:42:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:42:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 12:42:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:15
[ThaliCore] VirtualSocket.closeStreams() vsID:15
[ThaliCore] Session.session(_:peer:didChange:) peer:44494DD4-12BC-4559-8F3E-EEA02B4449F7 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "CFD7BC78-6165-4F86-9705-757C7CE0F24C", gen,eration: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:44494DD4-12BC-4559-8F3,E-EEA02B4449F7
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:15
[ThaliCore] VirtualSocket.deinit vsID:15 [6]
,ok 318 must be stopped
,[ThaliCore] BrowserManager.disconnect peer:DA5319DB-DF7F-4F8F-AF8F-6468B727A931
,[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50600
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] Session.disconnect() peer:DA5319DB-DF7F-4F8F-AF8F-6468B727A931:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:DA5319DB-DF7F-4F8F-AF8F-6468B727A931:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "DA5319DB-DF7F-4F8F-AF8F-6468B727A931", generation: 0)
[ThaliCore] BrowserRel,ay.closeRelay() disconnecting:true
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "DA5319DB-DF7F-4F8F-AF8F-6468B727A931", generation: 0)
,[ThaliCore] AdvertiserRelay.deinit
[ThaliCore] Session.deinit peer:44494DD4-12BC-4559-8F3E-EEA02B4449F7
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:75023228-E093-46FB-8518-0D06A4A6D6C0 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "CFD7BC78-6165-4F86-9705-757C7CE0F24C", generation: 0)
,2017-07-14 12:42:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 12:42:52 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:42:52 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:42:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 12:42:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 12:42:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:42:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:42:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# calls correct starts when network changes
,2017-07-14 12:42:52 - DEBUG CoordinatedClient: 'test was skipped, name: 'calls correct starts when network changes''
,# teardown
,ok 319 must be stopped
,# setup
,2017-07-14 12:42:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 12:42:52 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:42:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:42:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 12:42:52 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 12:42:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:42:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:42:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# test to coordinate connection cut
,# teardown
,ok 320 must be stopped
,# setup
,2017-07-14 12:42:53 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 12:42:53 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 12:42:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:42:53 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 12:42:53 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 12:42:53 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:42:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:42:53 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# can do HTTP requests after connections are cut
,2017-07-14 12:42:53 - DEBUG thaliMobileNativeWrapper: 'listening 50603'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:AB8AEFDF-8E8F-43B2-99C9-1B68A7B09E2A
,[ThaliCore] Browser.startListening
,2017-07-14 12:42:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 12:42:53 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-14 12:42:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "1C8CE36E-EC3D-47B0-B0A5-661FC49CAF92", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:1C8CE36E-EC3D-47B0-B0A5-661FC49CAF92
,2017-07-14 12:42:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-14 12:42:53 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 12:42:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DA5319DB-DF7F-4F8F-AF8F-6468B727A931:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DA5319DB-DF7F-4F8F-AF8F-6468B727A931", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:67F286DC-98FD-4585-9BD1-6FD40C61789A:0
2017-07-14 12:42:54 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdent,ifier":"DA5319DB-DF7F-4F8F-AF8F-6468B727A931","generation":0}]'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "67F286DC-98FD-4585-9BD1-6FD40C61789A", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5304,34CD-FD42-4B00-B7B0-D62CAE9735F1:0
2017-07-14 12:42:54 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"DA5319DB-DF7F-4F8F-AF8F-6468B727A931","generation":0}'
[ThaliCore] BrowserMana,ger.foundPeerHandler peer:Peer(uuid: "530434CD-FD42-4B00-B7B0-D62CAE9735F1", generation: 0)
2017-07-14 12:42:54 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"67F286DC-9,8FD-4585-9BD1-6FD40C61789A","generation":0}]'
,2017-07-14 12:42:54 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"67F286DC-98FD-4585-9BD1-6FD40C61789A","generation":0}'
,2017-07-14 12:42:54 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"530434CD-FD42-4B00-B7B0-D62CAE9735F1","generation":0}]'
,2017-07-14 12:42:54 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"530434CD-FD42-4B00-B7B0-D62CAE9735F1","generation":0}'
,2017-07-14 12:42:54 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"DA5319DB-DF7F-4F8F-AF8F-6468B727A931","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 12:42:54 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"DA5319DB-DF7F-4F8F-AF8F-6468B727A931","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 12:42:54 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for DA5319DB-DF7F-4F8F-AF8F-6468B727A931 (syncValue: poc7vS6uKmgCQZvNYTfvNzJueLbjn7CK)'
,2017-07-14 12:42:54 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "DA5319DB-DF7F-4F8F-AF8F-6468B727A931", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "DA5319DB-DF7F-4F8F-AF8F-6468B727A931", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:DA5319DB-DF7F-4F8F-AF8F-6468B727A931:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-14 12:42:54 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"67F286DC-98FD-4585-9BD1-6FD40C61789A","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 12:42:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"67F286DC-98FD-4585-9BD1-6FD40C61789A","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-14 12:42:54 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"67F286DC-98FD-4585-9BD1-6FD40C61789A","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 12:42:54 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"530434CD-FD42-4B00-B7B0-D62CAE9735F1","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 12:42:54 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"530434CD-FD42-4B00-B7B0-D62CAE9735F1","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1012162F-2335-4678-93BD-74D50507EA9B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1012162F-2335-4678-93BD-74D50507EA9B", generation: 0)
,2017-07-14 12:42:54 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"1012162F-2335-4678-93BD-74D50507EA9B","generation":0}]'
2017-07-14 12:42:54 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"1012162F-2335-4678-93BD-74D50507EA9B","generation":0}'
,2017-07-14 12:42:54 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"1012162F-2335-4678-93BD-74D50507EA9B","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 12:42:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1012162F-2335-4678-93BD-74D50507EA9B","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-14 12:42:54 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"1012162F-2335-4678-93BD-74D50507EA9B","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1C8CE36E-EC3D-47B0-B0A5-661FC49CAF92:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1C8CE36E-EC3D-47B0-B0A5-661FC49CAF92", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:530434CD-FD42-4B00-B7B0-D62CAE9735F1:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "530434CD-FD42-4B00-B7B0-D62CAE9735F1", generation: 0)
2017-07-14 12:42:56 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"530434CD-FD42-4B00-B7B0-D62CAE9735F1","generation":0}]'
2017-07-14 12:42:56 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"530434CD-FD42-4B00-B7B0-D62CAE9735F1","generation":0}'
,2017-07-14 12:42:56 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"530434CD-FD42-4B00-B7B0-D62CAE9735F1","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-14 12:42:56 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"530434CD-FD42-4B00-B7B0-D62CAE9735F1","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3A70640C-9134-4850-92C0-7DC030DA6AFA
[ThaliCore] Advertiser: session connected Peer(uuid: "1C8CE36E-EC3D-47B0-B0A5-661FC49CAF92", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:3A70640C-9134-4850-92C0-7DC030DA6AFA state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:DA5319DB-DF7F-4F8F-AF8F-6468B727A931:0 state: notConnected -> notConnected
,[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "DA5319DB-DF7F-4F8F-AF8F-6468B727A931", generation: 0)
,[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:DA5319DB-DF7F-4F8F-AF8F-6468B727A931:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "DA5319DB-DF7F-4F8F-AF8F-6468B727A931", generati,on: 0)
2017-07-14 12:42:59 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"poc7vS6uKmgCQZvNYTfvNzJueLbjn7CK","error":"Connection could not be established","portNumber":null}'
,2017-07-14 12:42:59 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'poc7vS6uKmgCQZvNYTfvNzJueLbjn7CK', error: 'Connection could not be established', listeningPort: '%s''
,2017-07-14 12:42:59 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"DA5319DB-DF7F-4F8F-AF8F-6468B727A931","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-14 12:42:59 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"DA5319DB-DF7F-4F8F-AF8F-6468B727A931","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-14 12:42:59 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"DA5319DB-DF7F-4F8F-AF8F-6468B727A931","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-14 12:42:59 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"DA5319DB-DF7F-4F8F-AF8F-6468B727A931","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-14 12:42:59 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"DA5319DB-DF7F-4F8F-AF8F-6468B727A931","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-14 12:42:59 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"DA5319DB-DF7F-4F8F-AF8F-6468B727A931","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-14 12:42:59 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"DA5319DB-DF7F-4F8F-AF8F-6468B727A931","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-14 12:42:59 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-14 12:42:59 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 67F286DC-98FD-4585-9BD1-6FD40C61789A (syncValue: rtkSsSwxgmcgNrZRy1KjHR4flO0VQ6dr)'
,2017-07-14 12:42:59 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "67F286DC-98FD-4585-9BD1-6FD40C61789A", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "67F286DC-98FD-4585-9BD1-6FD40C61789A", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:67F286DC-98FD-4585-9BD1-6FD40C61789A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:67F286DC-98FD-4585-9BD1-6FD40C61789A:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:DA5319DB-DF7F-4F8F-AF8F-6468B727A931:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "DA5319DB-DF7F-4F8F-AF8F-6468B727A931", generation: 0)
2017-07-14 12:43:00 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"DA5319DB-DF7F-4F8F-AF8F-6468B727A931","generation":0}]'
2017-07-14 12:43:00 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"DA5319DB-DF7F-4F8F-AF8F-6468B727A931","generation":0}'
,2017-07-14 12:43:00 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"DA5319DB-DF7F-4F8F-AF8F-6468B727A931","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-14 12:43:00 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"DA5319DB-DF7F-4F8F-AF8F-6468B727A931","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:3A70640C-9134-4850-92C0-7DC030DA6AFA
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:67F286DC-98FD-4585-9BD1-6FD40C61789A:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:3A70640C-9134-4850-92C0-7DC030DA6AFA state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3A70640C-9134-4850-92C0-7DC030DA6AFA
,[ThaliCore] Session.startOutputStream(with:) peer:3A70640C-9134-4850-92C0-7DC030DA6AFA
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:18 [6, 18]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:67F286DC-98FD-4585-9BD1-6FD40C61789A:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "67F286DC-98FD-4585-9BD1-6FD40C61789A", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50612
,2017-07-14 12:43:03 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"rtkSsSwxgmcgNrZRy1KjHR4flO0VQ6dr","error":null,"portNumber":50612}'
,2017-07-14 12:43:03 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'rtkSsSwxgmcgNrZRy1KjHR4flO0VQ6dr', error: 'null', listeningPort: '50612''
,2017-07-14 12:43:03 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:67F286DC-98FD-4585-9BD1-6FD40C61789A:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:67F286DC-98FD-4585-9BD1-6FD40C61789A:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:19 [6, 18, 19]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-14 12:43:03 - DEBUG testUtils: 'Got response data'
,2017-07-14 12:43:03 - DEBUG testUtils: 'Got end'
,ok 321 response body should match testData
,ok 322 must be started
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
2017-07-14 12:43:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-14 12:43:0,9 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkT,ype":null}})'
2017-07-14 12:43:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-14 12:43:09 - DEBUG tha,liMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:43:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 12:43:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 323 must be stopped
[ThaliCore] BrowserManager.disconnect peer:67F286DC-98FD-4585-9BD1-6FD40C61789A
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50612
,[ThaliCore] VirtualSocket.closeStreams() vsID:19
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:18
[ThaliCore] VirtualSocket.closeStreams() vsID:18
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:true
[ThaliCore] Session.disconnect() peer:67F286DC-98FD-4585-9BD1-6FD40C61789A:0
,[ThaliCore] VirtualSocket exited RunLoop vsID:19
[ThaliCore] VirtualSocket.deinit vsID:19 [6, 18]
,[ThaliCore] Session.session(_:peer:didChange:) peer:67F286DC-98FD-4585-9BD1-6FD40C61789A:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "67F286DC-98FD-4585-9BD1-6FD40C61789A", generation: 0)
[ThaliCore] Browser: s,ession notConnected removed relay for Peer(uuid: "67F286DC-98FD-4585-9BD1-6FD40C61789A", generation: 0)
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:18
,[ThaliCore] VirtualSocket.deinit vsID:18 [6]
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:3A70640C-9134-4850-92C0-7DC030DA6AFA state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "1C8CE36E-EC3D-47B0-B0A5-661FC49CAF92", generation: 0)
,[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:3A70640C-9134-4850-92C0-7DC030DA6AFA
,2017-07-14 12:43:09 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 12:43:09 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 12:43:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:43:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 12:43:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-07-14 12:43:09 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:43:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:43:09 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# will fail bad PSK connection between peers
,[ThaliCore] AdvertiserRelay.deinit
[ThaliCore] Session.deinit peer:3A70640C-9134-4850-92C0-7DC030DA6AFA
,ok 324 FIX ME, PLEASE!!!
,# teardown
,ok 325 must be stopped
,# setup
,2017-07-14 12:43:10 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 12:43:10 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:43:10 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:43:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 12:43:10 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 12:43:10 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 12:43:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
,2017-07-14 12:43:10 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# We provide notification when a listener dies and we recreate it
,2017-07-14 12:43:10 - DEBUG CoordinatedClient: 'test was skipped, name: 'We provide notification when a listener dies and we recreate it''
,# teardown
,ok 326 must be stopped
,# setup
,2017-07-14 12:43:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 12:43:11 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:43:11 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:43:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 12:43:11 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 12:43:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:43:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:43:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated
,2017-07-14 12:43:11 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated''
,# teardown
,ok 327 must be stopped
,# setup
,ok 328 ThaliMobile should be stopped
,# #startListeningForAdvertisements should fail if start not called
,ok 329 specific error should be returned
,# teardown
,2017-07-14 12:43:11 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-14, 12:43:11 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"D8A1E24E-AAA7-492E-9A14-1611985D239C","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-14 12:43:11 ,- DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"67F286DC-98FD-4585-9BD1-6FD40C61789A","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-14 12:43:11 - DEBUG th,aliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"1012162F-2335-4678-93BD-74D50507EA9B","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 330 error should be null
,ok 331 error should be null
,# setup
,ok 332 ThaliMobile should be stopped
,# #startUpdateAdvertisingAndListening should fail if start not called
,ok 333 specific error should be returned
,# teardown
,ok 334 error should be null
,ok 335 error should be null
,# setup
,ok 336 ThaliMobile should be stopped
,# should be able to call #stopListeningForAdvertisements many times
,2017-07-14 12:43:12 - DEBUG thaliMobileNativeWrapper: 'listening 50614'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 12:43:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 337 error should be null
,ok 338 error should be null
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 12:43:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 339 error should be null
,ok 340 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 12:43:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:43:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 12:43:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:43:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 12:43:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 341 error should be null
,ok 342 error should be null
,# setup
,ok 343 ThaliMobile should be stopped
,# should be able to call #startListeningForAdvertisements many times
,2017-07-14 12:43:12 - DEBUG thaliMobileNativeWrapper: 'listening 50615'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:38BCA379-E352-48EC-BAFA-9316AC03F265
[ThaliCore] Browser.st,artListening
2017-07-14 12:43:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
ok 344 error should be null
ok 345 error should be null
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-07-14 12:43:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,ok 346 error should be null
,ok 347 error should be null
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:67F286DC-98FD-4585-9BD1-6FD40C61789A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "67F286DC-98FD-4585-9BD1-6FD40C61789A", generation: 0)
,2017-07-14 12:43:12 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"67F286DC-98FD-4585-9BD1-6FD40C61789A","generation":0}]'
,2017-07-14 12:43:12 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"67F286DC-98FD-4585-9BD1-6FD40C61789A","generation":0}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:), found peer:1012162F-2335-4678-93BD-74D50507EA9B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1012162F-2335-4678-93BD-74D50507EA9B", generation: 0)
2017-07-14 12:43:13 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - E,mitting {"peerIdentifier":"67F286DC-98FD-4585-9BD1-6FD40C61789A","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 12:43:13 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"67F286DC-98FD-4585-9BD1-6FD40C61789A","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-14 12:43:13 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"1012162F-2335-4678-93BD-74D50507EA9B","generation":0}]'
2017-07-14 12:43:13 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"1012162F-2335-4678-93BD-74D50507EA9B","generation":0}'
,2017-07-14 12:43:13 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"1012162F-2335-4678-93BD-74D50507EA9B","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 12:43:13 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1012162F-2335-4678-93BD-74D50507EA9B","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-14 12:43:13 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"67F286DC-98FD-4585-9BD1-6FD40C61789A","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-14 12:43:13 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"1012162F-2335-4678-93BD-74D50507EA9B","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 12:43:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 12:43:13 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
,2017-07-14 12:43:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-14 12:43:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:43:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 12:43:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 348 error should be null
,ok 349 error should be null
,# setup
,ok 350 ThaliMobile should be stopped
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-07-14 12:43:13 - DEBUG thaliMobileNativeWrapper: 'listening 50616'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "E1E1CA11-4FE5-41F2-8103-311AA253D5A3", generation: 0)
[ThaliCore] Advertiser.startA,dvertising with peerID:E1E1CA11-4FE5-41F2-8103-311AA253D5A3
2017-07-14 12:43:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 351 error should be null
,ok 352 error should be null
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "E1E1CA11-4FE5-41F2-8103-311AA253D5A3", generation: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:E1E1CA11-4FE5-41F2-8103-311AA253D5A3
,2017-07-14 12:43:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 353 error should be null
,ok 354 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
,2017-07-14 12:43:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:43:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 12:43:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:43:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 12:43:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 355 error should be null
,ok 356 error should be null
,# setup
,ok 357 ThaliMobile should be stopped
,# should be able to call #stopAdvertisingAndListening many times
,2017-07-14 12:43:13 - DEBUG thaliMobileNativeWrapper: 'listening 50619'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 12:43:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 358 error should be null
,ok 359 error should be null
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 12:43:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 360 error should be null
,ok 361 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 12:43:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:43:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 12:43:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:43:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 12:43:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 362 error should be null
,ok 363 error should be null
,# setup
,ok 364 ThaliMobile should be stopped
,# #start - Causing native or wifi to fail will cause a promise reject 
,2017-07-14 12:43:14 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a Null'
,ok 365 This should not cause wifi to fail
,ok 366 native router should be bad
,# teardown
,ok 367 error should be null
ok 368 error should be null
,# setup
,ok 369 ThaliMobile should be stopped
,# #start should fail if called twice in a row
,2017-07-14 12:43:14 - DEBUG thaliMobileNativeWrapper: 'listening 50620'
,ok 370 first call should succeed
,ok 371 first call should succeed
,ok 372 specific error should be returned
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 12:43:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:43:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 12:43:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:43:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 12:43:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 373 error should be null
,ok 374 error should be null
,# setup
,ok 375 ThaliMobile should be stopped
,# #start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)
,2017-07-14 12:43:14 - DEBUG CoordinatedClient: 'test was skipped, name: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''
,# teardown
,ok 376 error should be null
ok 377 error should be null
,# setup
,ok 378 ThaliMobile should be stopped
,# does not emit duplicate discoveryAdvertisingStateUpdate
,2017-07-14 12:43:15 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not emit duplicate discoveryAdvertisingStateUpdate''
,# teardown
,ok 379 error should be null
ok 380 error should be null
,# setup
,ok 381 ThaliMobile should be stopped
,# does not send duplicate availability changes
,2017-07-14 12:43:15 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"220ec4ed-d3f5-41b8-8aeb-818e8b7bb7f9","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 382 should be called once
,ok 383 should not have been called more than once
,# teardown
,2017-07-14 12:43:15 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"220ec4ed-d3f5-41b8-8aeb-818e8b7bb7f9","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 384 error should be null
,ok 385 error should be null
,# setup
,ok 386 ThaliMobile should be stopped
,# can get the network status
,ok 387 network status should have certain non-empty properties
,# teardown
,ok 388 error should be null
ok 389 error should be null
,# setup
,ok 390 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer added/removed to/from cache (native)
,ok 391 we have not added peer to the cache yet
,2017-07-14 12:43:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"318f9ce6-30c7-4569-80f0-0a54bce9f778","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 392 peer should be available
,ok 393 cache contains native peer
,2017-07-14 12:43:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"318f9ce6-30c7-4569-80f0-0a54bce9f778","connectionType":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
,ok 394 peer should be unavailable
,ok 395 peer has been removed from cache
,# teardown
,ok 396 error should be null
,ok 397 error should be null
,# setup
,ok 398 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer added/removed to/from cache (wifi)
,ok 399 we have not added peer to the cache yet
,2017-07-14 12:43:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"acf566d6-8319-4593-826d-1b976e2f9f00","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 400 peer should be available
,ok 401 cache contains wifi peer
,2017-07-14 12:43:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"acf566d6-8319-4593-826d-1b976e2f9f00","connectionType":"tcp","peerAvailable":false,"generation":0,"newAddressPort":null}'
,ok 402 peer should be unavailable
,ok 403 peer has been removed from cache
,# teardown
,ok 404 error should be null
ok 405 error should be null
,# setup
,ok 406 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored
,2017-07-14 12:43:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"cfc123da-627b-4eb7-9e5e-fdc85eaf5091","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 407 first peer is available
,2017-07-14 12:43:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"fb43a74b-1298-4085-8060-67dc4168fb59","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 408 second peer is available
,ok 409 first and second peers are different
,# teardown
,2017-07-14 12:43:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"cfc123da-627b-4eb7-9e5e-fdc85eaf5091","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-14 12:43:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"fb43a74b-1298-4085-8060-67dc4168fb59","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 410 error should be null
,ok 411 error should be null
,# setup
,ok 412 ThaliMobile should be stopped
,# native available - new peer is cached
,ok 413 should not be in cache at start
,2017-07-14 12:43:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"a927ff5e-c928-44cf-ad56-2102c5141c34","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 414 peer is available
,# teardown
,2017-07-14 12:43:17 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"a927ff5e-c928-44cf-ad56-2102c5141c34","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 415 error should be null
,ok 416 error should be null
,# setup
,ok 417 ThaliMobile should be stopped
,# native available - peer with same port and different generation is cached (BLUETOOTH)
,2017-07-14 12:43:17 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with same port and different generation is cached (BLUETOOTH)''
,# teardown
,ok 418 error should be null
,ok 419 error should be null
,# setup
,ok 420 ThaliMobile should be stopped
,# native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)
,2017-07-14 12:43:17 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)''
,# teardown
,ok 421 error should be null
ok 422 error should be null
,# setup
,ok 423 ThaliMobile should be stopped
,# native available - peer with greater generation is cached (MPCF)
,2017-07-14 12:43:17 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"8af00178-ccab-4bd7-b544-34522f9ec856","connectionType":"MPCF","peerAvailable":true,"generation":2,"newAddressPort":false}'
ok 424 peer should be ,available
,2017-07-14 12:43:17 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"8af00178-ccab-4bd7-b544-34522f9ec856","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
ok 425 peer should be ,available
ok 426 should store correct generation
,# teardown
,2017-07-14 12:43:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"8af00178-ccab-4bd7-b544-34522f9ec856","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 427 error should be null
ok 428 error should be null
,# setup
,ok 429 ThaliMobile should be stopped
,# native available - peer with same or older generation is ignored (MPCF)
,2017-07-14 12:43:18 - DEBUG thaliMobileNativeWrapper: 'listening 50621'
,2017-07-14 12:43:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"8eeda5ce-0031-4941-858e-739b6cef087b","connectionType":"MPCF","peerAvailable":true,"generation":2,"newAddressPort":false}'
,ok 430 discovered correct peer
,ok 431 got correct generation
,2017-07-14 12:43:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"8eeda5ce-0031-4941-858e-739b6cef087b","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
,ok 432 discovered correct peer
,ok 433 got correct generation
,# teardown
,2017-07-14 12:43:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"8eeda5ce-0031-4941-858e-739b6cef087b","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 12:43:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:43:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 12:43:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:43:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 12:43:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 434 error should be null
,ok 435 error should be null
,# setup
,ok 436 ThaliMobile should be stopped
,# native unavailable - new peer is ignored
,2017-07-14 12:43:18 - DEBUG thaliMobileNativeWrapper: 'listening 50622'
,2017-07-14 12:43:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"728a0843-4ad5-430f-b793-b500801cb3cf","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 437 discovered available peer
,ok 438 peer is available
,# teardown
,2017-07-14 12:43:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"728a0843-4ad5-430f-b793-b500801cb3cf","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 12:43:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:43:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 12:43:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:43:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 12:43:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 439 error should be null
,ok 440 error should be null
,# setup
,ok 441 ThaliMobile should be stopped
,# native unavailable - cached peer is removed
,2017-07-14 12:43:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9ccdc33d-9fec-4fc6-83cb-4dd69aa04728","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 442 peer should be available
,2017-07-14 12:43:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9ccdc33d-9fec-4fc6-83cb-4dd69aa04728","connectionType":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
,ok 443 peer should be unavailable
,ok 444 should be removed from cache
,# teardown
,ok 445 error should be null
,ok 446 error should be null
,# setup
,ok 447 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for wifi peers
,2017-07-14 12:43:19 - DEBUG thaliMobileNativeWrapper: 'listening 50623'
,2017-07-14 12:43:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1b2e34df-e324-48b3-96bf-11154d7d4263","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 448 first peer is expected to be available
,2017-07-14 12:43:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"0dbeaca4-eb5a-4fea-a8ec-e09363b6a381","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 449 second peer is expected to be available
,2017-07-14 12:43:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"0dbeaca4-eb5a-4fea-a8ec-e09363b6a381","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 450 peer became unavailable
,ok 451 it was wifi peer
,2017-07-14 12:43:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"0dbeaca4-eb5a-4fea-a8ec-e09363b6a381","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 452 we found peer again
,ok 453 it was wifi peer
,2017-07-14 12:43:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"0dbeaca4-eb5a-4fea-a8ec-e09363b6a381","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 454 peer became unavailable
,ok 455 it was wifi peer
,# teardown
,2017-07-14 12:43:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"1b2e34df-e324-48b3-96bf-11154d7d4263","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 12:43:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:43:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 12:43:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:43:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 12:43:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 456 error should be null
,ok 457 error should be null
,# setup
,ok 458 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)
,2017-07-14 12:43:19 - DEBUG CoordinatedClient: 'test was skipped, name: 'networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)''
,# teardown
,ok 459 error should be null
ok 460 error should be null
,# setup
,ok 461 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)
,2017-07-14 12:43:19 - DEBUG thaliMobileNativeWrapper: 'listening 50624'
,2017-07-14 12:43:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"e9a54ac5-ff7b-4fee-961d-170fa0dff83a","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 462 first peer is expected to be available
,2017-07-14 12:43:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5a049b1c-312d-40fa-8678-a8b8c91c2d08","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 463 second peer is expected to be available
,2017-07-14 12:43:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"e9a54ac5-ff7b-4fee-961d-170fa0dff83a","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 464 peer became unavailable
,2017-07-14 12:43:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"5a049b1c-312d-40fa-8678-a8b8c91c2d08","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 465 peer became unavailable
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 12:43:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:43:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 12:43:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:43:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 12:43:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 466 error should be null
,ok 467 error should be null
,# setup
,ok 468 ThaliMobile should be stopped
,# multiconnect failure - new peer is ignored (MPCF)
,2017-07-14 12:43:20 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - new peer is ignored (MPCF)''
,# teardown
,ok 469 error should be null
,ok 470 error should be null
,# setup
,ok 471 ThaliMobile should be stopped
,# multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)
,2017-07-14 12:43:20 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''
,# teardown
,ok 472 error should be null
,ok 473 error should be null
,# setup
,ok 474 ThaliMobile should be stopped
,# newAddressPort field (TCP_NATIVE)
,2017-07-14 12:43:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1d331dd0-7d34-4016-a1cd-b8c59f4ccd0e","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 475 peer discovered first time does not have new address
,2017-07-14 12:43:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1d331dd0-7d34-4016-a1cd-b8c59f4ccd0e","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddressPort":false}'
,ok 476 address has not been changed
,2017-07-14 12:43:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1d331dd0-7d34-4016-a1cd-b8c59f4ccd0e","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddressPort":true}'
,ok 477 new port handled correctly
,2017-07-14 12:43:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1d331dd0-7d34-4016-a1cd-b8c59f4ccd0e","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddressPort":true}'
,ok 478 new host handled correctly
,2017-07-14 12:43:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1d331dd0-7d34-4016-a1cd-b8c59f4ccd0e","connectionType":"tcp","peerAvailable":false,"generation":20,"newAddressPort":null}'
,ok 479 newAddressPort is null for unavailable peers
,# teardown
,ok 480 error should be null
,ok 481 error should be null
,# setup
,ok 482 ThaliMobile should be stopped
,# newAddressPort field (BLUETOOTH)
,2017-07-14 12:43:20 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort field (BLUETOOTH)''
,# teardown
,ok 483 error should be null
,ok 484 error should be null
,# setup
,ok 485 ThaliMobile should be stopped
,# newAddressPort field (MPCF)
,ok 486 NOT IMPLEMENTED # SKIP
,# teardown
,ok 487 error should be null
,ok 488 error should be null
,# setup
,ok 489 ThaliMobile should be stopped
,# newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)
,2017-07-14 12:43:21 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)''
,# teardown
,ok 490 error should be null
,ok 491 error should be null
,# setup
,ok 492 ThaliMobile should be stopped
,# #getPeerHostInfo - error when peer has not been discovered yet
,ok 493 should be equal
,# teardown
,ok 494 error should be null
,ok 495 error should be null
,# setup
,ok 496 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)
,2017-07-14 12:43:21 - DEBUG CoordinatedClient: 'test was skipped, name: '#getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)''
,# teardown
,ok 497 error should be null
ok 498 error should be null
,# setup
,ok 499 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)
,2017-07-14 12:43:22 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 500 contains expected properties
,ok 501 the same hostAddress
,ok 502 the same portNumber
,# teardown
,2017-07-14 12:43:22 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 503 error should be null
,ok 504 error should be null
,# setup
,ok 505 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached wifi peer
,2017-07-14 12:43:22 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 506 contains expected properties
,ok 507 the same hostAddress
,ok 508 the same portNumber
,# teardown
,2017-07-14 12:43:22 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 509 error should be null
,ok 510 error should be null
,# setup
,ok 511 ThaliMobile should be stopped
,# #disconnect fails on wifi peers
,2017-07-14 12:43:22 - DEBUG thaliMobileNativeWrapper: 'listening 50625'
,2017-07-14 12:43:22 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9d719f56-2230-4479-8cc9-0406df05ca0e","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 512 Got specific error message
,# teardown
,2017-07-14 12:43:23 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"9d719f56-2230-4479-8cc9-0406df05ca0e","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 12:43:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:43:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 12:43:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:43:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 12:43:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 513 error should be null
,ok 514 error should be null
,# setup
,ok 515 ThaliMobile should be stopped
,# #disconnect delegates native peers to the native wrapper
,2017-07-14 12:43:23 - DEBUG thaliMobileNativeWrapper: 'listening 50626'
2017-07-14 12:43:23 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"ecee45a8-1c74-4369-acdf-84f77925abd8","connectionType":"MPCF","peerAvaila,ble":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] BrowserManager.disconnect peer:ecee45a8-1c74-4369-acdf-84f77925abd8
,ok 516 native wrapper `disconnect` called once
,ok 517 native wrapper `disconnect` called with peer data
,# teardown
,2017-07-14 12:43:23 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"ecee45a8-1c74-4369-acdf-84f77925abd8","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore,] AdvertiserManager.stopAdvertising()
2017-07-14 12:43:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:43:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 12:43:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:43:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 12:43:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 518 error should be null
,ok 519 error should be null
,# setup
,ok 520 ThaliMobile should be stopped
,# network changes emitted correctly
,2017-07-14 12:43:23 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes emitted correctly''
,# teardown
,ok 521 error should be null
,ok 522 error should be null
,# setup
,ok 523 ThaliMobile should be stopped
,# network changes not emitted in started state
,2017-07-14 12:43:23 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes not emitted in started state''
,# teardown
,ok 524 error should be null
ok 525 error should be null
,# setup
,ok 526 ThaliMobile should be stopped
,# network changes not emitted in stopped state
,2017-07-14 12:43:24 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes not emitted in stopped state''
,# teardown
,ok 527 error should be null
ok 528 error should be null
,# setup
,ok 529 ThaliMobile should be stopped
,# We properly fire peer unavailable and then available when connection fails on Android
,2017-07-14 12:43:24 - DEBUG CoordinatedClient: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on Android''
,# teardown
,ok 530 error should be null
,ok 531 error should be null
,# setup
,ok 532 ThaliMobile should be stopped
,# We properly fire peer unavailable and then available when connection fails on iOS
,2017-07-14 12:43:24 - DEBUG CoordinatedClient: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on iOS''
,# teardown
,ok 533 error should be null
,ok 534 error should be null
,# setup
,ok 535 ThaliMobile should be stopped
,# If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen
,2017-07-14 12:43:25 - DEBUG CoordinatedClient: 'test was skipped, name: 'If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen''
,# teardown
,ok 536 error should be null
,ok 537 error should be null
,# setup
,ok 538 ThaliMobile should be stopped
,# does not fire duplicate events after peer listener recreation
,2017-07-14 12:43:25 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not fire duplicate events after peer listener recreation''
,# teardown
,ok 539 error should be null
,ok 540 error should be null
,# setup
,ok 541 ThaliMobile should be stopped
,# #stop should change peers
,2017-07-14 12:43:25 - DEBUG thaliMobileNativeWrapper: 'listening 50627'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:EA4AF1E6-9DC8-4A32-8C92-24E7990EF6F8
,[ThaliCore] Browser.startListening
,2017-07-14 12:43:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 12:43:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"c29b4c0b-bd29-4ab0-9c23-e55bc59c0070","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 542 Peer availabilities has one entry for our connection type
,2017-07-14 12:43:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"04711f74-950d-4243-ad1c-1f7dc3e9c9cb","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 543 Peer availabilities has one entry for our connection type
,2017-07-14 12:43:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"c29b4c0b-bd29-4ab0-9c23-e55bc59c0070","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-14 12:43:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"04711f74-950d-4243-ad1c-1f7dc3e9c9cb","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 12:43:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 12:43:25 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"pskIdToSecret":[102,111,1,11],"networkType":"BOTH"}})'
,2017-07-14 12:43:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-14 12:43:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:43:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 12:43:25 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 12:43:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 544 No peers
,ok 545 No peers
,ok 546 No peers
,# teardown
,ok 547 error should be null
,ok 548 error should be null
,# setup
,ok 549 ThaliMobile should be stopped
,# If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted
,2017-07-14 12:43:26 - DEBUG thaliMobileNativeWrapper: 'listening 50628'
,2017-07-14 12:43:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7ad0b410-dd47-446e-bd82-08c040d82ae5","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 550 1
,ok 551 2
,2017-07-14 12:43:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"3baba91d-1d5d-46b0-922c-0bf583b21539","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,# teardown
,2017-07-14 12:43:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"7ad0b410-dd47-446e-bd82-08c040d82ae5","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-14 12:43:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"3baba91d-1d5d-46b0-922c-0bf583b21539","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 12:43:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:43:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 12:43:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:43:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 12:43:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 552 error should be null
,ok 553 error should be null
,# setup
,ok 554 ThaliMobile should be stopped
,# peer should be found once after listening and discovery started
,2017-07-14 12:43:26 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer should be found once after listening and discovery started''
,# teardown
,ok 555 error should be null
,ok 556 error should be null
,# setup
,ok 557 ThaliMobile should be stopped
,# can get data from all participants
,2017-07-14 12:43:27 - DEBUG thaliMobileNativeWrapper: 'listening 50629'
,ok 558 error should be null
,ok 559 error should be null
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "0E72115A-8DB3-42E8-94B5-C3755B9B7A1B", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:0E72115A-8DB3-42E8-94B5-C3755B9B7A1B
,2017-07-14 12:43:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,ok 560 error should be null
,ok 561 error should be null
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:34220E5A-8F40-4411-9054-05CFE8F1F788
,[ThaliCore] Browser.startListening
,2017-07-14 12:43:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,ok 562 error should be null
,ok 563 error should be null
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:67F286DC-98FD-4585-9BD1-6FD40C61789A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "67F286DC-98FD-4585-9BD1-6FD40C61789A", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:1012162F-2335-4678-93BD-74D50507EA9B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1012162F-2335-4678-93BD-74D50507EA9B", generation: 0)
,2017-07-14 12:43:28 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"67F286DC-98FD-4585-9BD1-6FD40C61789A","generation":0}]'
,2017-07-14 12:43:28 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"67F286DC-98FD-4585-9BD1-6FD40C61789A","generation":0}'
,2017-07-14 12:43:28 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"1012162F-2335-4678-93BD-74D50507EA9B","generation":0}]'
,2017-07-14 12:43:28 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"1012162F-2335-4678-93BD-74D50507EA9B","generation":0}'
,2017-07-14 12:43:28 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"67F286DC-98FD-4585-9BD1-6FD40C61789A","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 12:43:28 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"67F286DC-98FD-4585-9BD1-6FD40C61789A","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-14 12:43:28 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"1012162F-2335-4678-93BD-74D50507EA9B","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 12:43:28 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1012162F-2335-4678-93BD-74D50507EA9B","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-14 12:43:28 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 67F286DC-98FD-4585-9BD1-6FD40C61789A (syncValue: 0)'
,2017-07-14 12:43:28 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "67F286DC-98FD-4585-9BD1-6FD40C61789A", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "67F286DC-98FD-4585-9BD1-6FD40C61789A", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:67F286DC-98FD-4585-9BD1-6FD40C61789A:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1A1FA89B-152B-41D0-B735-F1ABE32DB4DB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1A1FA89B-152B-41D0-B735-F1ABE32DB4DB", generation: 0)
,2017-07-14 12:43:28 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"1A1FA89B-152B-41D0-B735-F1ABE32DB4DB","generation":0}]'
,2017-07-14 12:43:28 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"1A1FA89B-152B-41D0-B735-F1ABE32DB4DB","generation":0}'
,2017-07-14 12:43:28 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"1A1FA89B-152B-41D0-B735-F1ABE32DB4DB","peerAvailable":true,"generation":0,"portNumber":null}'
[ThaliCore] Browser.browser(_:foundPeer:withDi,scoveryInfo:) found peer:ECC53031-B0F7-42CA-96F9-B11DCF478A34:0
2017-07-14 12:43:28 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1A1FA89B-152B-41D0-B735-F1ABE32DB4DB","connectionType":"MPCF","peerAvailable":tru,e,"generation":0,"newAddressPort":false}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "ECC53031-B0F7-42CA-96F9-B11DCF478A34", generation: 0)
,2017-07-14 12:43:28 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"ECC53031-B0F7-42CA-96F9-B11DCF478A34","generation":0}]'
2017-07-14 12:43:28 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"ECC53031-B0F7-42CA-96F9-B11DCF478A34","generation":0}'
,2017-07-14 12:43:28 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"ECC53031-B0F7-42CA-96F9-B11DCF478A34","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 12:43:28 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"ECC53031-B0F7-42CA-96F9-B11DCF478A34","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0E72115A-8DB3-42E8-94B5-C3755B9B7A1B:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0E72115A-8DB3-42E8-94B5-C3755B9B7A1B", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:67F286DC-98FD-4585-9BD1-6FD40C61789A:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "67F286DC-98FD-4585-9BD1-6FD40C61789A", generation: 0)
[ThaliCore] Session.disconnect() peer:67F286DC-98F,D-4585-9BD1-6FD40C61789A:0
[ThaliCore] Browser.browser(_:lostPeer:) lost peer:1012162F-2335-4678-93BD-74D50507EA9B:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "1012162F-2335-4678-93BD-74D50507EA9B", generation: 0)
2017-07-14 12:43:30 - ,DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"67F286DC-98FD-4585-9BD1-6FD40C61789A","generation":0}]'
,2017-07-14 12:43:30 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"67F286DC-98FD-4585-9BD1-6FD40C61789A","generation":0}'
,2017-07-14 12:43:30 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"1012162F-2335-4678-93BD-74D50507EA9B","generation":0}]'
,2017-07-14 12:43:30 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"1012162F-2335-4678-93BD-74D50507EA9B","generation":0}'
,2017-07-14 12:43:30 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"67F286DC-98FD-4585-9BD1-6FD40C61789A","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-14 12:43:30 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"67F286DC-98FD-4585-9BD1-6FD40C61789A","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-14 12:43:30 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnav,ailable - Emitting {"peerIdentifier":"1012162F-2335-4678-93BD-74D50507EA9B","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-14 12:43:30 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1012162F-2335-4678-93BD-74D50507EA9B","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1012162F-2335-4678-93BD-74D50507EA9B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1012162F-2335-4678-93BD-74D50507EA9B", generation: 0)
2017-07-14 12:43:30 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"1012162F-2335-4678-93BD-74D50507EA9B","generation":0}]'
2017-07-14 12:43:30 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"1012162F-2335-4678-93BD-74D50507EA9B","generation":0}'
,2017-07-14 12:43:30 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"1012162F-2335-4678-93BD-74D50507EA9B","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 12:43:30 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1012162F-2335-4678-93BD-74D50507EA9B","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:67F286DC-98FD-4585-9BD1-6FD40C61789A:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "67F286DC-98FD-4585-9BD1-6FD40C61789A", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:67F286DC-98FD-4585-9BD1-6FD40C61789A:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "67F286DC-98FD-4585-9BD1-6FD40C61789A", genera,tion: 0)
2017-07-14 12:43:33 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"0","error":"Connection could not be established","portNumber":null}'
2017-07-14 12:43:33 - DEBUG thaliMobileNativeWrapper: 'Received peer availability cha,nged event with {"peerIdentifier":"67F286DC-98FD-4585-9BD1-6FD40C61789A","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-14 12:43:33 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"67,F,286DC-98FD-4585-9BD1-6FD40C61789A","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-14 12:43:33 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"67F286DC-98FD-4585-9BD1-6FD40C61789A","pee,rAvailable":false,"portNumber":null,"recreated":true}'
2017-07-14 12:43:33 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"67F286DC-98FD-4585-9BD1-6FD40C61789A","peerAvailable":true,"portNumber":null,"re,created":true}'
,2017-07-14 12:43:33 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 1012162F-2335-4678-93BD-74D50507EA9B (syncValue: 1)'
2017-07-14 12:43:33 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPee,r(_:syncValue:completion:) Peer(uuid: "1012162F-2335-4678-93BD-74D50507EA9B", generation: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1012162F-2335-4678-93BD-74D50507EA9B", generation: 0)
[ThaliCo,re] Session.init(session:identifier:connected:notConnected:) peer:1012162F-2335-4678-93BD-74D50507EA9B:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:),
2017-07-14 12:43:33 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"67F286DC-98FD-4585-9BD1-6FD40C61789A","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-14 12:43:33 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"67F286DC-98FD-4585-9BD1-6FD40C61789A","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-14 12:43:33 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"67F286DC-98FD-4585-9BD1-6FD40C61789A","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-14 12:43:33 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"67F286DC-98FD-4585-9BD1-6FD40C61789A","peerAvailable":true,"portNumber":null,"recreated":true}'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9F88746E-DCBC-4143-A067-419AE121C4CF
[ThaliCore] Advertiser: session connected Peer(uuid: "0E72115A-8DB3-42E8-94B5-C3755B9B7A1B", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:9F88746E-DCBC-4143-A067-419AE121C4CF state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:1012162F-2335-4678-93BD-74D50507EA9B:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "1012162F-2335-4678-93BD-74D50507EA9B", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:1012162F-2335-4678-93BD-74D50507EA9B:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "1012162F-2335-4678-93BD-74D50507EA9B", genera,tion: 0)
2017-07-14 12:43:38 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"1","error":"Connection could not be established","portNumber":null}'
2017-07-14 12:43:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availability cha,nged event with {"peerIdentifier":"1012162F-2335-4678-93BD-74D50507EA9B","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-14 12:43:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"1012162F-2335-4678-93BD-74D50507EA9B","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-14 12:43:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"1012162F-2335-4678-93BD-74D50507EA9B","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-14 12:43:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"1012162F-2335-4678-93BD-74D50507EA9B","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-14 12:43:38 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 1A1FA89B-152B-41D0-B735-F1ABE32DB4DB (syncValue: 2)'
,2017-07-14 12:43:38 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "1A1FA89B-152B-41D0-B735-F1ABE32DB4DB", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1A1FA89B-152B-41D0-B735-F1ABE32DB4DB", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1A1FA89B-152B-41D0-B735-F1ABE32DB4DB:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-14 12:43:39 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"1012162F-2335-4678-93BD-74D50507EA9B","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-14 12:43:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"1012162F-2335-4678-93BD-74D50507EA9B","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-14 12:43:39 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"1012162F-2335-4678-93BD-74D50507EA9B","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-14 12:43:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"1012162F-2335-4678-93BD-74D50507EA9B","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-14 12:43:39 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"1012162F-2335-4678-93BD-74D50507EA9B","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-14 12:43:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"1012162F-2335-4678-93BD-74D50507EA9B","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-14 12:43:39 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"1012162F-2335-4678-93BD-74D50507EA9B","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-14 12:43:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"1012162F-2335-4678-93BD-74D50507EA9B","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:1A1FA89B-152B-41D0-B735-F1ABE32DB4DB:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:9F88746E-DCBC-4143-A067-419AE121C4CF
,[ThaliCore] Session.session(_:peer:didChange:) peer:9F88746E-DCBC-4143-A067-419AE121C4CF state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9F88746E-DCBC-4143-A067-419AE121C4CF
[ThaliCore] Session.startOutputStream(with:) peer:9F88746E-DCBC-4143-A067-419AE121C4CF
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:20 [6, 20]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:80413BE2-FDC0-4EF3-BBAE-DD50B8E1A4D4
[ThaliCore] Advertiser: session connected Peer(uuid: "0E72115A-8DB3-42E8-94B5-C3755B9B7A1B", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:80413BE2-FDC0-4EF3-BBAE-DD50B8E1A4D4 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:1A1FA89B-152B-41D0-B735-F1ABE32DB4DB:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:1A1FA89B-152B-41D0-B735-F1ABE32DB4DB:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "1A1FA89B-152B-41D0-B735-F1ABE32DB4DB", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50638
2017-07-14 12:43:41 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"2","error":null,"portNumber":50638,}'
,2017-07-14 12:43:41 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for ECC53031-B0F7-42CA-96F9-B11DCF478A34 (syncValue: 3)'
,2017-07-14 12:43:41 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "ECC53031-B0F7-42CA-96F9-B11DCF478A34", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "ECC53031-B0F7-42CA-96F9-B11DCF478A34", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:ECC53031-B0F7-42CA-96F9-B11DCF478A34:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:1A1FA89B-152B-41D0-B735-F1ABE32DB4DB:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:1A1FA89B-152B-41D0-B735-F1ABE32DB4DB:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:21 [6, 20, 21]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-14 12:43:42 - DEBUG testUtils: 'Got response data'
,2017-07-14 12:43:42 - DEBUG testUtils: 'Got end'
,[ThaliCore] Session.session(_:peer:didChange:) peer:ECC53031-B0F7-42CA-96F9-B11DCF478A34:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:80413BE2-FDC0-4EF3-BBAE-DD50B8E1A4D4
,[ThaliCore] Session.session(_:peer:didChange:) peer:80413BE2-FDC0-4EF3-BBAE-DD50B8E1A4D4 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:80413BE2-FDC0-4EF3-BBAE-DD50B8E1A4D4
[ThaliCore] Session.startOutputStream(with:) peer:80413BE2-FDC0-4EF3-BBAE-DD50B8E1A4D4
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:22 [6, 20, 21, 22]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:ECC53031-B0F7-42CA-96F9-B11DCF478A34:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:ECC53031-B0F7-42CA-96F9-B11DCF478A34:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "ECC53031-B0F7-42CA-96F9-B11DCF478A34", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50643
2017-07-14 12:43:45 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"3","error":null,"portNumber":50643,}'
,2017-07-14 12:43:45 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 1012162F-2335-4678-93BD-74D50507EA9B (syncValue: 4)'
,2017-07-14 12:43:45 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "1012162F-2335-4678-93BD-74D50507EA9B", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1012162F-2335-4678-93BD-74D50507EA9B", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1012162F-2335-4678-93BD-74D50507EA9B:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:ECC53031-B0F7-42CA-96F9-B11DCF478A34:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:ECC53031-B0F7-42CA-96F9-B11DCF478A34:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:23 [6, 20, 21, 22, 23]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-14 12:43:45 - DEBUG testUtils: 'Got response data'
,2017-07-14 12:43:45 - DEBUG testUtils: 'Got end'
,ok 564 received all uuids
,# teardown
,2017-07-14 12:43:45 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"1A1FA89B-152B-41D0-B735-F1ABE32DB4DB","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-14 12:43:45 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"ECC53031-B0F7-42CA-96F9-B11DCF478A34","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-14 12:43:45 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"1012162F-2335-4678-93BD-74D50507EA9B","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:21
,[ThaliCore] VirtualSocket.closeStreams() vsID:21
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:21
,[ThaliCore] VirtualSocket.deinit vsID:21 [6, 20, 22, 23]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:23
[ThaliCore] VirtualSocket.closeStreams() vsID:23
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:23
,[ThaliCore] VirtualSocket.deinit vsID:23 [6, 20, 22]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:1A1FA89B-152B-41D0-B735-F1ABE32DB4DB:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "1A1FA89B-152B-41D0-B735-F1ABE32DB4DB", generation: 0)
[ThaliCore] Session.disconnect() peer:1A1FA89B-152B-41D0-B735-F1ABE32DB4DB:0
,2017-07-14 12:43:48 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"1A1FA89B-152B-41D0-B735-F1ABE32DB4DB","generation":0}]'
[ThaliCore] Session.session(_:peer:didChange:,) peer:1A1FA89B-152B-41D0-B735-F1ABE32DB4DB:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "1A1FA89B-152B-41D0-B735-F1ABE32DB4DB", generation: 0)
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCo,re] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50638
[ThaliCore] Session.disconnect() peer:1A1FA89B-152B-41D0-B735-F1ABE32DB4DB:0
2017-07-14 12:43:48 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with, {"peerAvailable":false,"peerIdentifier":"1A1FA89B-152B-41D0-B735-F1ABE32DB4DB","generation":0}'
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,2017-07-14 12:43:48 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"1A1FA89B-152B-41D0-B735-F1ABE32DB4DB","peerAvailable":false,"generation":null,"portNumber":null}'
,[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "1A1FA89B-152B-41D0-B735-F1ABE32DB4DB", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:1012162F-2335-4678-93BD-74D50507EA9B:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "1012162F-2335-4678-93BD-74D50507EA9B", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:1012162F-2335-4678-93BD-74D50507EA9B:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "1012162F-2335-4678-93BD-74D50507EA9B", genera,tion: 0)
2017-07-14 12:43:50 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"4","error":"Connection could not be established","portNumber":null}'
,2017-07-14 12:43:50 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"1012162F-2335-4678-93BD-74D50507EA9B","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-14 12:43:50 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"1012162F-2335-4678-93BD-74D50507EA9B","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-14 12:43:50 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"1012162F-2335-4678-93BD-74D50507EA9B","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-14 12:43:50 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"1012162F-2335-4678-93BD-74D50507EA9B","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,[ThaliCore] BrowserManager.disconnect peer:67F286DC-98FD-4585-9BD1-6FD40C61789A
,[ThaliCore] BrowserManager.disconnect peer:67F286DC-98FD-4585-9BD1-6FD40C61789A
,2017-07-14 12:43:50 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 1012162F-2335-4678-93BD-74D50507EA9B (syncValue: 5)'
,2017-07-14 12:43:50 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "1012162F-2335-4678-93BD-74D50507EA9B", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1012162F-2335-4678-93BD-74D50507EA9B", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1012162F-2335-4678-93BD-74D50507EA9B:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-14 12:43:50 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"1012162F-2335-4678-93BD-74D50507EA9B","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-14 12:43:50 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"1012162F-2335-4678-93BD-74D50507EA9B","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-14 12:43:50 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"1012162F-2335-4678-93BD-74D50507EA9B","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-14 12:43:50 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"1012162F-2335-4678-93BD-74D50507EA9B","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:1012162F-2335-4678-93BD-74D50507EA9B:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "1012162F-2335-4678-93BD-74D50507EA9B", generation: 0)
[ThaliCore] Session.disconnect() peer:1012162F-233,5-4678-93BD-74D50507EA9B:0
2017-07-14 12:43:52 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"1012162F-2335-4678-93BD-74D50507EA9B","generation":0}]'
,2017-07-14 12:43:52 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"1012162F-2335-4678-93BD-74D50507EA9B","generation":0}'
,2017-07-14 12:43:52 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"1012162F-2335-4678-93BD-74D50507EA9B","peerAvailable":false,"generation":null,"portNumber":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:1012162F-2335-4678-93BD-74D50507EA9B:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "1012162F-2335-4678-93BD-74D50507EA9B", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:1012162F-2335-4678-93BD-74D50507EA9B:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "1012162F-2335-4678-93BD-74D50507EA9B", genera,tion: 0)
2017-07-14 12:43:55 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"5","error":"Connection could not be established","portNumber":null}'
,2017-07-14 12:43:55 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"1012162F-2335-4678-93BD-74D50507EA9B","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-14 12:43:55 - DEBUG thaliMobil,eNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"1012162F-2335-4678-93BD-74D50507EA9B","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-14 12:43:55 - DEBUG thaliMobileNativeWrapper: 'Received peer availabi,lity changed event with {"peerIdentifier":"1012162F-2335-4678-93BD-74D50507EA9B","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-14 12:43:55 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifi,er":"1012162F-2335-4678-93BD-74D50507EA9B","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-14 12:43:55 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 1012162F-2335-4678-93BD-74D50507EA9B (syncValue: 6)'
2017-07-14 12:43:55 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPee,r(_:syncValue:completion:) Peer(uuid: "1012162F-2335-4678-93BD-74D50507EA9B", generation: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1012162F-2335-4678-93BD-74D50507EA9B", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) error:unavailablePeer
2017-07-14 12:43:56 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"6","error":"Peer is unavailable","portNumber":null}'
2017-07-14 12:43:56 - ,DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"1012162F-2335-4678-93BD-74D50507EA9B","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-14 12:43:56 - DEBUG thaliMobileNativeWrapper: 'Recei,ved peer availability changed event with {"peerIdentifier":"1012162F-2335-4678-93BD-74D50507EA9B","peerAvailable":true,"portNumber":null,"recreated":true}'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
2017-07-,14 12:43:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 12:43:56 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
2017-07-14 12:43:56 ,- INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-14 12:43:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:43:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 12:43:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:20
[ThaliCore] VirtualSocket.closeStreams() vsID:20
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:22
[ThaliCore] VirtualSocket.closeS,treams() vsID:22
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:20
[ThaliCore] VirtualSocket.deinit vsID:20 [6, 22]
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:22
,[ThaliCore] VirtualSocket.deinit vsID:22 [6]
,2017-07-14 12:43:56 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"1012162F-2335-4678-93BD-74D50507EA9B","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-14 12:43:56 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"1012162F-2335-4678-93BD-74D50507EA9B","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-14 12:43:56 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"1012162F-2335-4678-93BD-74D50507EA9B","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,[ThaliCore] BrowserManager.disconnect peer:1012162F-2335-4678-93BD-74D50507EA9B
,2017-07-14 12:43:56 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"1012162F-2335-4678-93BD-74D50507EA9B","peerAvailable":true,"portNumber":null,"recreated":true}'
,[ThaliCore] BrowserManager.disconnect peer:1012162F-2335-4678-93BD-74D50507EA9B
,2017-07-14 12:43:56 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"1012162F-2335-4678-93BD-74D50507EA9B","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,[ThaliCore] BrowserManager.disconnect peer:1012162F-2335-4678-93BD-74D50507EA9B
,[ThaliCore] BrowserManager.disconnect peer:1012162F-2335-4678-93BD-74D50507EA9B
,2017-07-14 12:43:56 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"1012162F-2335-4678-93BD-74D50507EA9B","peerAvailable":true,"portNumber":null,"recreated":true}'
,ok 565 error should be null
,ok 566 error should be null
,[ThaliCore] BrowserManager.disconnect peer:1012162F-2335-4678-93BD-74D50507EA9B
,# setup
,ok 567 ThaliMobile should be stopped
,# test for data corruption
,2017-07-14 12:43:56 - DEBUG CoordinatedClient: 'test was skipped, name: 'test for data corruption''
,# teardown
,ok 568 error should be null
ok 569 error should be null
,# setup
,# #testThaliPeerAction - test getters
,ok 570 getPeerIdentifier
,ok 571 getConnectionType
,ok 572 getActionType
,ok 573 getActionState
,ok 574 getPskIdentity
,ok 575 getPskKey
,# teardown
,# setup
,# #testThaliPeerAction - start and kill
,ok 576 initial state
ok 577 after start
2017-07-14 12:43:58 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 578 after kill
,# teardown
,# setup
,# #testThaliPeerAction - double start
,ok 579 should be equal
,# teardown
,# setup
,# #testThaliPeerAction - start after kill
,2017-07-14 12:43:58 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 580 clean kill
,ok 581 should be equal
,# teardown
,# setup
,# #testThaliPeerAction - make sure ids are unique
,ok 582 should not be equal
,# teardown
,# setup
,# #testThaliPeerAction - check that forever agent can be destroyed
,ok 583 forever agent should have it's own destroy method
,ok 584 agent's destroy should be called
,ok 585 agent's destroy should not be called again
,ok 586 agent is destroyed
,# teardown
,# setup
,# Test PeerDictionary basic functionality
,ok 587 Entry counter must be 1
,ok 588 Entry exists
,ok 589 Size must be 1
,ok 590 Entry counter must be 2
,ok 591 Entry exists
,ok 592 Size must be 2
,ok 593 Entry counter must be 1
,ok 594 Entry exists
,ok 595 Size must be 3
,ok 596 Entry counter must be 2
,ok 597 Entry exists
,ok 598 Size must be 4
,ok 599 Entry 1_1 should not be found
,ok 600 Entry 1_1 does not exist
,ok 601 Size must be 3
,ok 602 Entry 1_2 should not be found
,ok 603 Entry 1_2 does not exist
,ok 604 Size must be 2
,ok 605 should be equal
,ok 606 Entry 2_1 should not be found
,ok 607 Entry 2_2 should not be found
,ok 608 Entry 2_1 does not exist
,ok 609 Entry 2_2 does not exist
,ok 610 Size must be 0
,# teardown
,# setup
,# Test PeerDictionary with multiple entries.
,ok 611 Size must be100
,ok 612 Entries between 20 and MAXSIZE + 20 should exist
,ok 613 WAITING state entry should not be removed
,# teardown
,# setup
,# RESOLVED entries are removed before WAITING state entry.
,ok 614 Entries between 6 and MAXSIZE + 4 should exist
,ok 615 Size should be MAXSIZE
,ok 616 Size should be MAXSIZE+6
,# teardown
,# setup
,# WAITING entries are removed before CONTROLLED_BY_POOL state entry.
,ok 617 WAITING state entry should not be removed
,ok 618 Waiting entries between 6 and MAXSIZE + 4 should exist
,ok 619 Size should be MAXSIZE
,ok 620 entryCounter should be MAXSIZE+6
,# teardown
,# setup
,# When CONTROLLED_BY_POOL entry is removed and kill is called.
,ok 621 Kill should be called once
,ok 622 Size should be MAXSIZE
,# teardown
,# setup
,# #ThaliPeerPoolDefault - single action
,ok 623 is an agent
ok 624 enqueue is fine
ok 625 Everything should be off the queue
,# teardown
,# setup
,# #ThaliPeerPoolDefault - multiple actions
,ok 626 is an agent
,ok 627 first enqueue is fine
,ok 628 is an agent
,ok 629 second enqueue is fine
,ok 630 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
,ok 631 Queue is empty
,# teardown
,# setup
,# #ThaliPeerPoolDefault - PSK Pool works
,ok 632 is an agent
,ok 633 good enqueue
,ok 634 Identity should match
,2017-07-14 12:44:04 - DEBUG testUtils: 'Got response data'
,2017-07-14 12:44:04 - DEBUG testUtils: 'Got end'
,ok 635 Got expected response
,ok 636 Got psk call back
,# teardown
,2017-07-14 12:44:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #ThaliPeerPoolDefault - stop
,ok 637 is an agent
,ok 638 enqueue worked
,ok 639 is an agent
,ok 640 enqueue 2 worked
,ok 641 enqueue is not available when stopped
,ok 642 start action is killed
,ok 643 killed action is still killed
,ok 644 enqueued action when stopped is killed
,ok 645 inQueue is empty
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure that start verifies queue length
,ok 646 good start
,ok 647 good enqueue
,ok 648 queue is not empty
,# teardown
,# setup
,# #ThaliPeerPoolInterface - bad enqueues
,ok 649 null arg
ok 650 wrong arg type
ok 651 wrong arg type
,# teardown
,# setup
,# #ThaliPeerPoolInterface - do not allow same object type
,ok 652 good enqueue
ok 653 already enqueued
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure we catch kill and dequeue
,ok 654 good enqueue
ok 655 2nd good enqueue
ok 656 we are in the pool
ok 657 We are out of the pool
,ok 658 Action was killed
ok 659 The original kill was called too
ok 660 second item is still in queue
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent
,ok 661 good enqueue
ok 662 first kill
ok 663 second NOOP kill
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure that stop removes all actions
,ok 664 1st good enqueue
,ok 665 2nd good enqueue
,ok 666 1st action is in the pool
,ok 667 2nd action is in the pool
,ok 668 1st action is out of the pool
,ok 669 2st action is out of the pool
,ok 670 pool is empty
,# teardown
,# setup
,# We reject unrecognized connection type
,2017-07-14 12:44:07 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 671 Got right error
,ok 672 Start should not be called
,ok 673 Kill should have been called at least once
,# teardown
,# setup
,# We reject unrecognized action type
,2017-07-14 12:44:07 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
2017-07-14 12:44:07 - ERROR thaliPeerPoolOneAtATime: 'Got unsupported action type: blah'
,ok 674 Got right error
,ok 675 Start should not be called
,ok 676 Kill should have been called at least once
,# teardown
,# setup
,# One action on bluetooth
,2017-07-14 12:44:07 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 677 Got null
,2017-07-14 12:44:07 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerID'
,ok 678 is an agent
,2017-07-14 12:44:07 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerID'
,ok 679 Got killed at least once
,# teardown
,# setup
,# Two notification actions
,2017-07-14 12:44:08 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
ok 680 Got Null
ok 681 Got another null
2017-07-14 12:44:08 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidB,luetooth, Peer Identifier: peerId1'
ok 682 is an agent
2017-07-14 12:44:08 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peer,Id1'
,2017-07-14 12:44:08 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
,ok 683 is an agent
,2017-07-14 12:44:08 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
,ok 684 Action 1 killed at least once
,ok 685 Action 1 went first
,ok 686 Action 2 killed at least once
,# teardown
,# setup
,# replicateThroughProblems
,2017-07-14 12:44:09 - DEBUG thaliPeerPoolOneAtATime: 'Action Started success'
,2017-07-14 12:44:09 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - success'
,2017-07-14 12:44:09 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,ok 687 should have gotten null
,2017-07-14 12:44:09 - DEBUG thaliPeerPoolOneAtATime: 'Action Started noActivityTimeOut'
,2017-07-14 12:44:09 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: No activity time out - noActivityTimeOut'
,ok 688 Should have stopped nicely
,2017-07-14 12:44:09 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButNotAvailable'
,2017-07-14 12:44:09 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButNotAvailable'
,ok 689 Still looking for null
,2017-07-14 12:44:09 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButAvailable'
,2017-07-14 12:44:09 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButAvailable'
,2017-07-14 12:44:09 - DEBUG thaliPeerPoolOneAtATime: 'Replication action failed badly so we are going to retry'
,2017-07-14 12:44:09 - DEBUG thaliPeerPoolOneAtATime: 'Action Started clone!'
,2017-07-14 12:44:09 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - clone!'
,2017-07-14 12:44:09 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,ok 690 Yup, another null
,ok 691 We cloned!
,# teardown
,# setup
,# Replication goes first
,2017-07-14 12:44:09 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 692 Null 1
,ok 693 (unnamed assert)
,2017-07-14 12:44:09 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,ok 694 is an agent
,ok 695 Null 3
,ok 696 Replication not yet called
,ok 697 Notification 2 not yet called
,2017-07-14 12:44:09 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,2017-07-14 12:44:09 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
,ok 698 is an agent
,ok 699 Notification went first
,ok 700 Notification 2 not called yet
,2017-07-14 12:44:09 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
,2017-07-14 12:44:09 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,2017-07-14 12:44:09 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,ok 701 is an agent
,ok 702 Notification finished
,ok 703 Replication finished
,2017-07-14 12:44:09 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,# teardown
,# setup
,# wifi allows many parallel non-replication actions
,2017-07-14 12:44:10 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-14 12:44:10 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
,ok 704 is an agent
,ok 705 First does not throw
,2017-07-14 12:44:10 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
,ok 706 is an agent
,ok 707 Second does not throw
,2017-07-14 12:44:10 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
,truetruefalsetrue
,2017-07-14 12:44:10 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
,truetruetruetrue
,# teardown
,# setup
,# wifi allows no more than 2 simultaneous replication actions for same peerID
,2017-07-14 12:44:10 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-14 12:44:10 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 595, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,ok 708 is an agent
,ok 709 first ok
,2017-07-14 12:44:10 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 596, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,ok 710 is an agent
,ok 711 second ok
,ok 712 third ok
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
,ok 713 peerIdentifier should match
,ok 714 generation should match
,ok 715 Response should be BEACONS_RETRIEVED_AND_PARSED
,ok 716 good beacon
,ok 717 good preAmble
,ok 718 public keys match!
,ok 719 must return null after successful call
,ok 720 Once start returns the action should be in KILLED state
,# teardown
,2017-07-14 12:44:11 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test HTTP_BAD_RESPONSE locally
,ok 721 Response should be HTTP_BAD_RESPONSE
,ok 722 must return null after successful call
,# teardown
,2017-07-14 12:44:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test NETWORK_PROBLEM locally
,ok 723 Response should be NETWORK_PROBLEM
,ok 724 reject reason should be: Could not establish TCP connection
,# teardown
,2017-07-14 12:44:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Action fails when getPeerHostInfo fails
,ok 725 Resolution should be BAD_PEER
,ok 726 correct error message
,# teardown
,2017-07-14 12:44:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the start two times
,ok 727 Call start once
,ok 728 Response should be BEACONS_RETRIEVED_AND_PARSED
,ok 729 must return null after successful call.
,# teardown
,2017-07-14 12:44:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill before calling the start
,ok 730 Should be Killed
,ok 731 Start after killed
,# teardown
,2017-07-14 12:44:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill immediately after the start
,ok 732 Should be KILLED
,ok 733 must return null after successful kill
,# teardown
,2017-07-14 12:44:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill while waiting a response from the server
,ok 734 Should be KILLED
ok 735 must return null after successful kill
,# teardown
,2017-07-14 12:44:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test to exceed the max content size locally
,ok 736 HTTP_BAD_RESPONSE should be response when content size is exceeded
,ok 737 must return null after successful call
,# teardown
,2017-07-14 12:44:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Close the server socket while the client is waiting a response from the server. Local test.
,2017-07-14 12:44:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 738 Should be NETWORK_PROBLEM caused closing server socket
,ok 739 Should be Could not establish TCP connection
,# teardown
,# setup
,# Close the client socket while the client is waiting a response from the server. Local test.
,ok 740 Should be NETWORK_PROBLEM caused closing client socket
ok 741 Should be Could not establish TCP connection
,# teardown
,2017-07-14 12:44:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #generatePreambleAndBeacons bad args
,ok 742 publicKeysToNotify cannot be null
ok 743 ecdh for local device cannot be null
ok 744 milliseconds cannot be less than 0
ok 745 milliseconds cannot be 0
,ok 746 milliseconds cannot be greater than one_day
,# teardown
,# setup
,# #generatePreambleAndBeacons empty keys to notify
,ok 747 should be equal
,# teardown
,# setup
,# #generatePreambleAndBeacons multiple keys to notify
,ok 748 should be equal
ok 749 should be equal
,ok 750 (unnamed assert)
,ok 751 should be equal
,# teardown
,# setup
,# #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
,ok 752 should throw
,# teardown
,# setup
,# #parseBeacons invalid expiration in beaconStreamWithPreAmble
,ok 753 Preamble expiration must be a 64 bit integer
,# teardown
,# setup
,# #parseBeacons expiration out of range lower
,ok 754 Expiration out of range
,# teardown
,# setup
,# #parseBeacons expiration out of range lower
,ok 755 Expiration out of range
,# teardown
,# setup
,# #parseBeacons no beacons returns null
,ok 756 should be equal
,# teardown
,# setup
,# #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
,ok 757 Malformed encrypted beacon key ID
,# teardown
,# setup
,# #parseBeacons addressBookCallback fails decrypt
,ok 758 should be equal
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns no matches
,ok 759 should be equal
ok 760 should be equal
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns spurious match
,ok 761 should be equal
,ok 762 should be equal
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns public key
,ok 763 right number of calls to address book
ok 764 good preAmble
,ok 765 good unencryptedKeyId
,ok 766 good beacon
,# teardown
,# setup
,# validate generatePskIdentityField
,ok 767 decoded buffers match
# teardown
,# setup
,# validate generatePskSecret
,ok 768 secrets match
,# teardown
,# setup
,# validate generatePskSecrets
,ok 769 Matching numbers
,ok 770 We have an entry!
,ok 771 keys match
,ok 772 secrets match
,ok 773 We have an entry!
,ok 774 keys match
,ok 775 secrets match
,ok 776 We have an entry!
,ok 777 keys match
,ok 778 secrets match
,# teardown
,# setup
,# validate generateBeaconStreamAndSecrets
,ok 779 Streams have same length
,ok 780 matching size
,ok 781 keys match
,ok 782 secrets match
,# teardown
,# setup
,# Add two Peers.
,ok 783 should be equal
,ok 784 peerDictionalty contains 2 peers
ok 785 bluetooth peer's notification has correct connection type
ok 786 tcp peer's notification has correct connection type
,2017-07-14 12:44:30 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,2017-07-14 12:44:30 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-07-14 12:44:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# TCP_NATIVE peer loses DNS
,ok 787 notification peer dictionary contains exactly 1 peer
2017-07-14 12:44:30 - WARN thaliNotificationClient: 'peer is not available'
,ok 788 notification peer dictionary does not contain any peers
,2017-07-14 12:44:30 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-07-14 12:44:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Received beacons with no values for us
,ok 789 entry exists
,ok 790 entry is resolved
,# teardown
,2017-07-14 12:44:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Notification action killed with a superseded
,ok 791 Action should be KILLED
ok 792 Peer state should be RESOLVED
,# teardown
,2017-07-14 12:44:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally
,ok 793 hostAddress must match
,ok 794 portNumber must match
,ok 795 suggestedTCPTimeout must match
,ok 796 connectionType must match
,ok 797 peerIDs must match
,# teardown
,2017-07-14 12:44:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Emits error event when peerPool.enqueue throws
,ok 798 Correct error
,# teardown
,2017-07-14 12:44:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally using ThaliPeerPoolDefault
,ok 799 hostAddress must match
,ok 800 portNumber must match
,ok 801 suggestedTCPTimeout must match
,ok 802 connectionType must match
,ok 803 peerIds must match
,# teardown
,2017-07-14 12:44:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Action fails because of a bad hostname.
,2017-07-14 12:44:33 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 804 action should be resolved with NETWORK_PROBLEM error
,2017-07-14 12:44:33 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 805 action should be resolved with NETWORK_PROBLEM error
,2017-07-14 12:44:34 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 806 action should be resolved with NETWORK_PROBLEM error
,2017-07-14 12:44:34 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 807 action should be resolved with NETWORK_PROBLEM error
ok 808 correct number of requests
ok 809 correct number of failures
ok 810 correct final peer state
,# teardown
,2017-07-14 12:44:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# hostaddress is removed when the action is running. 
,2017-07-14 12:44:37 - WARN thaliNotificationClient: 'peer is not available'
2017-07-14 12:44:37 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 811 peerDictionary should become empty
,# teardown
,2017-07-14 12:44:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notificationClient does not retry action with BAD_PEER resolution
,2017-07-14 12:44:37 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 812 failed with expected error
,ok 813 peer state should be RESOLVED
,# teardown
,2017-07-14 12:44:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notification client correctly handles peer availability changes of the same peer
,2017-07-14 12:44:38 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 814 First action failed
,ok 815 second action killed
# teardown
,2017-07-14 12:44:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Client to server request locally
,ok 816 secrets are equal
ok 817 Public key matches with the server key
,ok 818 hostAddress must match
,ok 819 portNumber must match
,ok 820 suggestedTCPTimeout must match
,ok 821 connectionType must match
,# teardown
,2017-07-14 12:44:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache clean and expiration
,ok 822 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE
,ok 823 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE-1
,ok 824 All entries should be expired after 1 second
# teardown
,2017-07-14 12:44:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache getSecret and getPublic
,ok 825 All keys need to be available in the cache
,ok 826 All entries should be expired after 1 second
,# teardown
,2017-07-14 12:44:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache multiple entries
,ok 827 Size of the cache should be 2
ok 828 Cache doesn't contain dictionary1
,ok 829 Size of the cache should be 1
ok 830 Cache doesn't contain beaconStreamAndSecretDictionary2
# teardown
,2017-07-14 12:44:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Start and stop ThaliNotificationServer
,ok 831 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
,ok 832 ThaliMobile.StopAdvertisingAndListeningshould be called once
,# teardown
,2017-07-14 12:44:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass an empty array to ThaliNotificationServer.start
,ok 833 StartUpdateAdvertisingAndListening should not be called
,ok 834 ThaliMobile.StopAdvertisingAndListening should be called once
,ok 835 no error
,ok 836 should be 204
,# teardown
,2017-07-14 12:44:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass a string to ThaliNotificationServer.start
,ok 837 StartUpdateAdvertisingAndListening should not be called
,# teardown
,2017-07-14 12:44:45 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass an empty parameter to ThaliNotificationServer.start
,ok 838 StartUpdateAdvertisingAndListening should not be called
,# teardown
,2017-07-14 12:44:45 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeacons
,ok 839 no error
ok 840 should be 200
,ok 841 should be equal
,ok 842 should be equal
,ok 843 (unnamed assert)
,ok 844 no error
,ok 845 should be 204
,# teardown
,2017-07-14 12:44:46 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeacons (no keys)
,ok 846 error should be null
,ok 847 should be 204
,# teardown
,2017-07-14 12:44:46 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeaconsbefore calling start
,ok 848 should be 404
,# teardown
,2017-07-14 12:44:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure peerDictionaryKey is reasonable
,ok 849 equal keys
,ok 850 not equal connection type
,ok 851 same connection type, different buffer
,# teardown
,# setup
,# Make sure start works
,2017-07-14 12:44:47 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 852 First start and on called correctly
,# teardown
,# setup
,# Make sure stop works
,ok 853 second cleared dictionary
,2017-07-14 12:44:48 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,ok 854 First start and on called correctly
,ok 855 First stop and removeListener called correctly
,ok 856 first action kill called
,ok 857 second action kill called
,ok 858 first cleared dictionary
,ok 859 first cleared pool
,ok 860 second cleared dictionary
,ok 861 second cleared pool
,# teardown
,# setup
,# Emits error event when peerPool.enqueue throws
,ok 862 Correct error
,# teardown
,# setup
,# Simple peer event
,2017-07-14 12:44:49 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,ok 863 listener has been set
,ok 864 peer dictionary has expected number of entries
,ok 865 Dictionary and pool have same action
,ok 866 ads match
,ok 867 PouchDB matches
,ok 868 DB Names match
,ok 869 public keys match
,ok 870 peer dictionary has expected number of entries
,ok 871 Dictionary and pool have same action
,ok 872 ads match
,ok 873 PouchDB matches
,ok 874 DB Names match
,ok 875 public keys match
,2017-07-14 12:44:49 - DEBUG thaliReplicationPeerAction: 'We called _complete with  and it caused us to complete'
,ok 876 start called once
,ok 877 One entry left
,ok 878 Dictionary and pool have same action
,ok 879 Start never called
,ok 880 Kill called once
,ok 881 no entries left
,ok 882 Third action is dead
,ok 883 peer dictionary has expected number of entries
,ok 884 Dictionary and pool have same action
,ok 885 ads match
,ok 886 PouchDB matches
,ok 887 DB Names match
,ok 888 public keys match
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
,ok 889 right error
,# teardown
,2017-07-14 12:44:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server accepts & closes connection
,2017-07-14 12:44:50 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 socket hang up'
,2017-07-14 12:44:50 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: socket hang up  and it caused us to complete'
,ok 890 right error
,# teardown
,2017-07-14 12:44:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 500
,2017-07-14 12:44:51 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 changes rejected'
,2017-07-14 12:44:51 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 891 Got error as expected
,# teardown
,2017-07-14 12:44:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 401
,2017-07-14 12:44:51 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  401 changes rejected'
,2017-07-14 12:44:51 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 892 Got error as expected
,# teardown
,2017-07-14 12:44:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 403
,2017-07-14 12:44:52 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  403 changes rejected'
,2017-07-14 12:44:52 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 893 Got error as expected
,# teardown
,2017-07-14 12:44:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure docs replicate with remote db with same name as local db
,2017-07-14 12:44:54 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-14 12:44:55 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-14 12:44:57 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
,ok 894 should be equal
,ok 895 All tests passed!
,# teardown
,2017-07-14 12:44:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure docs replicate with remote db with different name than local db
,2017-07-14 12:45:00 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-14 12:45:01 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-14 12:45:03 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
,ok 896 should be equal
ok 897 All tests passed!
,# teardown
,2017-07-14 12:45:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Do nothing and make sure we time out
,2017-07-14 12:45:04 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-14 12:45:05 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2017-07-14 12:45:05 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and s,o we ignored it'
ok 898 action should be killed
ok 899 Error should be timed out
,ok 900 No doc found
,# teardown
,2017-07-14 12:45:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Do something and make sure we time out
,2017-07-14 12:45:08 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-14 12:45:08 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,ok 901 should be equal
,2017-07-14 12:45:10 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
,2017-07-14 12:45:10 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
,ok 902 action should be killed
,ok 903 Error should be timed out
,# teardown
,2017-07-14 12:45:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Start replicating and then catch error when server goes
,ok 904 socket hung up
,# teardown
,2017-07-14 12:45:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure clone works
,ok 905 same getPeerAdvertisesDataForUs
,ok 906 Same pouchdB
,ok 907 same localDbName
,ok 908 Same public key
,# teardown
,# setup
,# Coordinated replication action test - each device has the same local db name
,2017-07-14 12:45:13 - DEBUG CoordinatedClient: 'test was skipped, name: 'Coordinated replication action test - each device has the same local db name''
,# teardown
,# setup
,# Coordinated replication action test - each device has different local db name
,2017-07-14 12:45:14 - DEBUG thaliMobileNativeWrapper: 'listening 50775'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:E545EC0D-0ABE-4423-B60C-2395509F5937
,[ThaliCore] Browser.startListening
,2017-07-14 12:45:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "E2889C1F-9781-47EB-A87E-5FA42585CC92", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:E2889C1F-9781-47EB-A87E-5FA42585CC92
,2017-07-14 12:45:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9AD30652-AF46-462F-A2F8-6E33AB8997AB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9AD30652-AF46-462F-A2F8-6E33AB8997AB", generation: 0)
,2017-07-14 12:45:15 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"9AD30652-AF46-462F-A2F8-6E33AB8997AB","generation":0}]'
,2017-07-14 12:45:15 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"9AD30652-AF46-462F-A2F8-6E33AB8997AB","generation":0}'
,2017-07-14 12:45:15 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"9AD30652-AF46-462F-A2F8-6E33AB8997AB","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 12:45:15 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9AD30652-AF46-462F-A2F8-6E33AB8997AB","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-14 12:45:15 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 9AD30652-AF46-462F-A2F8-6E33AB8997AB (syncValue: 7)'
,2017-07-14 12:45:15 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "9AD30652-AF46-462F-A2F8-6E33AB8997AB", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9AD30652-AF46-462F-A2F8-6E33AB8997AB", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9AD30652-AF46-462F-A2F8-6E33AB8997AB:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
[ThaliCore] Advertiser: session connected Peer(uuid: "E2889C1F-9781-47EB-A87E-5FA42585CC92", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F31DA80D-5F19-4969-9F65-323952DF140D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F31DA80D-5F19-4969-9F65-323952DF140D", generation: 0)
,2017-07-14 12:45:15 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"F31DA80D-5F19-4969-9F65-323952DF140D","generation":0}]'
,2017-07-14 12:45:15 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"F31DA80D-5F19-4969-9F65-323952DF140D","generation":0}'
,2017-07-14 12:45:15 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"F31DA80D-5F19-4969-9F65-323952DF140D","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 12:45:15 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"F31DA80D-5F19-4969-9F65-323952DF140D","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E2889C1F-9781-47EB-A87E-5FA42585CC92", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:9AD30652-AF46-462F-A2F8-6E33AB8997AB:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:9AD30652-AF46-462F-A2F8-6E33AB8997AB:0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:10B0CD6D-69F3-4A6F-93D9-C349008463B8
[ThaliCore] Session.session(_:peer:didChange:) peer:10B0CD6D-69F3-4A6F-93D9-C349008463B8 state: notConnected -> connecting
[ThaliCore] Advertis,er: session connected Peer(uuid: "E2889C1F-9781-47EB-A87E-5FA42585CC92", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:9AD30652-AF46-462F-A2F8-6E33AB8997AB:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "9AD30652-AF46-462F-A2F8-6E33AB8997AB", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8 state: connecting -> connected
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50778
,2017-07-14 12:45:18 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"7","error":null,"portNumber":50778}'
,2017-07-14 12:45:18 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 9AD30652-AF46-462F-A2F8-6E33AB8997AB (syncValue: 8)'
,2017-07-14 12:45:18 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "9AD30652-AF46-462F-A2F8-6E33AB8997AB", generation: 0) found active relay
,2017-07-14 12:45:18 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"8","error":null,"portNumber":50778}'
,2017-07-14 12:45:18 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 9AD30652-AF46-462F-A2F8-6E33AB8997AB (syncValue: 9)'
,2017-07-14 12:45:18 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "9AD30652-AF46-462F-A2F8-6E33AB8997AB", generation: 0) found active relay
,2017-07-14 12:45:18 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"9","error":null,"portNumber":50778}'
,2017-07-14 12:45:18 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 9AD30652-AF46-462F-A2F8-6E33AB8997AB (syncValue: 10)'
,2017-07-14 12:45:18 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "9AD30652-AF46-462F-A2F8-6E33AB8997AB", generation: 0) found active relay
,2017-07-14 12:45:18 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"10","error":null,"portNumber":50778}'
,2017-07-14 12:45:18 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for F31DA80D-5F19-4969-9F65-323952DF140D (syncValue: 11)'
,2017-07-14 12:45:18 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "F31DA80D-5F19-4969-9F65-323952DF140D", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F31DA80D-5F19-4969-9F65-323952DF140D", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F31DA80D-5F19-4969-9F65-323952DF140D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
[ThaliCore] Session.startOutputStream(with:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:24 [6, 24]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:9AD30652-AF46-462F-A2F8-6E33AB8997AB:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9AD30652-AF46-462F-A2F8-6E33AB8997AB:0
[ThaliCore] Session.startOutputStream(with:) peer:9AD30652-AF46-462F-A2F8-6E33AB8997AB:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:25 [6, 24, 25]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
,[ThaliCore] Session.startOutputStream(with:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9AD30652-AF46-462F-A2F8-6E33AB8997AB:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:26 [6, 24, 25, 26]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:9AD30652-AF46-462F-A2F8-6E33AB8997AB:0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:9AD30652-AF46-462F-A2F8-6E33AB8997AB:0
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9AD30652-AF46-462F-A2F8-6E33AB8997AB:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:27 [6, 24, 25, 26, 27]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9AD30652-AF46-462F-A2F8-6E33AB8997AB:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:28 [6, 24, 25, 26, 27, 28]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:29 [6, 24, 25, 26, 27, 28, 29]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
,[ThaliCore] Session.startOutputStream(with:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:30 [6, 24, 25, 26, 27, 28, 29, 30]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
[ThaliCore] Session.startOutputStream(with:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:31 [6, 24, 25, 26, 27, 28, 29, 30, 31]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vs,ID:26
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vs,ID:25
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:25
,[ThaliCore] VirtualSocket.deinit vsID:25 [6, 24, 26, 27, 28, 29, 30, 31]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:24
[ThaliCore] VirtualSocket.closeStreams() vsID:24
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:24
,[ThaliCore] VirtualSocket.deinit vsID:24 [6, 26, 27, 28, 29, 30, 31]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] Adv,ertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vs,ID:27
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:27
,[ThaliCore] VirtualSocket.deinit vsID:27 [6, 26, 28, 29, 30, 31]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:28
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:28
,[ThaliCore] VirtualSocket.deinit vsID:28 [6, 26, 29, 30, 31]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:9AD30652-AF46-462F-A2F8-6E33AB8997AB:0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:29
[ThaliCore] VirtualSocket.closeStreams() vsID:29
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:29
,[ThaliCore] VirtualSocket.deinit vsID:29 [6, 26, 30, 31]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9AD30652-AF46-462F-A2F8-6E33AB8997AB:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:32 [6, 26, 30, 31, 32]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:30
[ThaliCore] VirtualSocket.closeStreams() vsID:30
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:30
[ThaliCore] VirtualSocket.deinit vsID:30 [6, 26, 31, 32]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:,) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:31
[ThaliCore] VirtualSocket.closeStreams() vsID:31
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:31
[ThaliCore] VirtualSocket.deinit vsID:31 [6, 26, 32]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecti,ng:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
[ThaliCore] Session.startOutputStream(with:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:33 [6, 26, 32, 33]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-14 12:45:18 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:9AD30652-AF46-462F-A2F8-6E33AB8997AB:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9AD30652-AF46-462F-A2F8-6E33AB8997AB:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:34 [6, 26, 32, 33, 34]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:peer:didChange:) peer:F31DA80D-5F19-4969-9F65-323952DF140D:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
[ThaliCore] Session.startOutputStream(with:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:35 [6, 26, 32, 33, 34, 35]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
[ThaliCore] Session.startOutputStream(with:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:36 [6, 26, 32, 33, 34, 35, 36]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:9AD30652-AF46-462F-A2F8-6E33AB8997AB:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9AD30652-AF46-462F-A2F8-6E33AB8997AB:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:37 [6, 26, 32, 33, 34, 35, 36, 37]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:9AD30652-AF46-462F-A2F8-6E33AB8997AB:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9AD30652-AF46-462F-A2F8-6E33AB8997AB:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:38 [6, 26, 32, 33, 34, 35, 36, 37, 38]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
[ThaliCore] Session.startOutputStream(with:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:39 [6, 26, 32, 33, 34, 35, 36, 37, 38, 39]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
,[ThaliCore] Session.startOutputStream(with:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:40 [6, 26, 32, 33, 34, 35, 36, 37, 38, 39, 40]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:9AD30652-AF46-462F-A2F8-6E33AB8997AB:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9AD30652-AF46-462F-A2F8-6E33AB8997AB:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:41 [6, 26, 32, 33, 34, 35, 36, 37, 38, 39, 40, 41]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:39
,[ThaliCore] VirtualSocket.closeStreams() vsID:39
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:39
,[ThaliCore] VirtualSocket.deinit vsID:39 [6, 26, 32, 33, 34, 35, 36, 37, 38, 40, 41]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
[ThaliCore] Session.startOutputStream(with:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:42 [6, 26, 32, 33, 34, 35, 36, 37, 38, 40, 41, 42]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:38
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:38
[ThaliCore] VirtualSocket.deinit vsID:38 [6, 26, 32, 33, 34, 35, 36, 37, 40, 41, 42]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:42
,[ThaliCore] VirtualSocket.closeStreams() vsID:42
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:42
,[ThaliCore] VirtualSocket.deinit vsID:42 [6, 26, 32, 33, 34, 35, 36, 37, 40, 41]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:9AD30652-AF46-462F-A2F8-6E33AB8997AB:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9AD30652-AF46-462F-A2F8-6E33AB8997AB:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:43 [6, 26, 32, 33, 34, 35, 36, 37, 40, 41, 43]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-14 12:45:19 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:43
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:43
,[ThaliCore] VirtualSocket.deinit vsID:43 [6, 26, 32, 33, 34, 35, 36, 37, 40, 41]
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:10B0CD6D-69F3-4A6F-93D9-C349008463B8
,[ThaliCore] Session.session(_:peer:didChange:) peer:10B0CD6D-69F3-4A6F-93D9-C349008463B8 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:10B0CD6D-69F3-4A6F-93D9-C349008463B8
[ThaliCore] Session.startOutputStream(with:) peer:10B0CD6D-69F3-4A6F-93D9-C349008463B8
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4,4 [6, 26, 32, 33, 34, 35, 36, 37, 40, 41, 44]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:10B0CD6D-69F3-4A6F-93D9-C349008463B8
[ThaliCore] Session.startOutputStream(with:) peer:10B0CD6D-69F3-4A6F-93D9-C349008463B8
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4,5 [6, 26, 32, 33, 34, 35, 36, 37, 40, 41, 44, 45]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:10B0CD6D-69F3-4A6F-93D9-C349008463B8
,[ThaliCore] Session.startOutputStream(with:) peer:10B0CD6D-69F3-4A6F-93D9-C349008463B8
[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:46 [6, 26, 32, 33, 34, 35, 36, 37, 40, 41, 44, 45, 46]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:10B0CD6D-69F3-4A6F-93D9-C349008463B8
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.startOutputStream(with:) peer:10B0CD6D-69F3-4A6F-93D9-C349008463B8
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:47 [6, 26, 32, 33, 34, 35, 36, 37, 40, 41, 44, 45, 46, 47]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:46
,[ThaliCore] VirtualSocket.closeStreams() vsID:46
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:46
,[ThaliCore] VirtualSocket.deinit vsID:46 [6, 26, 32, 33, 34, 35, 36, 37, 40, 41, 44, 45, 47]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:44
[ThaliCore] VirtualSocket.closeStreams() vsID:44
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:44
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] VirtualSocket.deinit vsID:44 [6, 26, 32, 33, 34, 35, 36, 37, 40, 41, 45, 47]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:45
[ThaliCore] VirtualSocket.closeStreams() vsID:45
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:45
,[ThaliCore] VirtualSocket.deinit vsID:45 [6, 26, 32, 33, 34, 35, 36, 37, 40, 41, 47]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:47
[ThaliCore] VirtualSocket.closeStreams() vsID:47
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:47
[ThaliCore] VirtualSocket.deinit vsID:47 [6, 26, 32, 33, 34, 35, 36, 37, 40, 41]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDi,dDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:10B0CD6D-69F3-4A6F-93D9-C349008463B8
[ThaliCore] Session.startOutputStream(with:) peer:10B0CD6D-69F3-4A6F-93D9-C349008463B8
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:48 [6, 26, 32, 33, 34, 35, 36, 37, 40, 41, 48]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:10B0CD6D-69F3-4A6F-93D9-C349008463B8
[ThaliCore] Session.startOutputStream(with:) peer:10B0CD6D-69F3-4A6F-93D9-C349008463B8
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:49 [6, 26, 32, 33, 34, 35, 36, 37, 40, 41, 48, 49]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:peer:didChange:) peer:80413BE2-FDC0-4EF3-BBAE-DD50B8E1A4D4 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "0E72115A-8DB3-42E8-94B5-C3755B9B7A1B", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:80413BE2-FDC0-4EF3-BBAE-DD50B8E1A4D4
[ThaliCore] AdvertiserRelay.deinit
[ThaliCore] Session.deinit peer:80413BE2-FDC0-4EF3-BBAE-DD50B8E1A4D4
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:10B0CD6D-69F3-4A6F-93D9-C349008463B8
,[ThaliCore] Session.startOutputStream(with:) peer:10B0CD6D-69F3-4A6F-93D9-C349008463B8
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:50 [6, 26, 32, 33, 34, 35, 36, 37, 40, 41, 48, 49, 50]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:F31DA80D-5F19-4969-9F65-323952DF140D:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:F31DA80D-5F19-4969-9F65-323952DF140D:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "F31DA80D-5F19-4969-9F65-323952DF140D", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50808
,2017-07-14 12:45:21 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"11","error":null,"portNumber":50808}'
,2017-07-14 12:45:21 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for F31DA80D-5F19-4969-9F65-323952DF140D (syncValue: 12)'
,2017-07-14 12:45:21 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "F31DA80D-5F19-4969-9F65-323952DF140D", generation: 0) found active relay
,2017-07-14 12:45:21 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"12","error":null,"portNumber":50808}'
,2017-07-14 12:45:21 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for F31DA80D-5F19-4969-9F65-323952DF140D (syncValue: 13)'
,2017-07-14 12:45:21 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "F31DA80D-5F19-4969-9F65-323952DF140D", generation: 0) found active relay
,2017-07-14 12:45:21 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"13","error":null,"portNumber":50808}'
,2017-07-14 12:45:21 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for F31DA80D-5F19-4969-9F65-323952DF140D (syncValue: 14)'
,2017-07-14 12:45:21 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "F31DA80D-5F19-4969-9F65-323952DF140D", generation: 0) found active relay
,2017-07-14 12:45:21 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"14","error":null,"portNumber":50808}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:F31DA80D-5F19-4969-9F65-323952DF140D:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F31DA80D-5F19-4969-9F65-323952DF140D:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:51 [6, 26, 32, 33, 34, 35, 36, 37, 40, 41, 48, 49, 50, 51]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:F31DA80D-5F19-4969-9F65-323952DF140D:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F31DA80D-5F19-4969-9F65-323952DF140D:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:52 [6, 26, 32, 33, 34, 35, 36, 37, 40, 41, 48, 49, 50, 51, 52]
[ThaliCore] BrowserRela,y.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:F31DA80D-5F19-4969-9F65-323952DF140D:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F31DA80D-5F19-4969-9F65-323952DF140D:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:53 [6, 26, 32, 33, 34, 35, 36, 37, 40, 41, 48, 49, 50, 51, 52, 53]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:F31DA80D-5F19-4969-9F65-323952DF140D:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F31DA80D-5F19-4969-9F65-323952DF140D:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:54 [6, 26, 32, 33, 34, 35, 36, 37, 40, 41, 48, 49, 50, 51, 52, 53, 54]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:52
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:52
,[ThaliCore] VirtualSocket.deinit vsID:52 [6, 26, 32, 33, 34, 35, 36, 37, 40, 41, 48, 49, 50, 51, 53, 54]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:51
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:51
,[ThaliCore] VirtualSocket.deinit vsID:51 [6, 26, 32, 33, 34, 35, 36, 37, 40, 41, 48, 49, 50, 53, 54]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:53
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:53
,[ThaliCore] VirtualSocket.deinit vsID:53 [6, 26, 32, 33, 34, 35, 36, 37, 40, 41, 48, 49, 50, 54]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:54
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:54
,[ThaliCore] VirtualSocket.deinit vsID:54 [6, 26, 32, 33, 34, 35, 36, 37, 40, 41, 48, 49, 50]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:F31DA80D-5F19-4969-9F65-323952DF140D:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F31DA80D-5F19-4969-9F65-323952DF140D:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:55 [6, 26, 32, 33, 34, 35, 36, 37, 40, 41, 48, 49, 50, 55]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-14 12:45:21 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
,2017-07-14 12:45:21 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:33
,[ThaliCore] VirtualSocket.closeStreams() vsID:33
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:33
[ThaliCore] VirtualSocket.deinit vsID:33 [6, 26, 32, 34, 35, 36, 37, 40, 41, 48, 49, 50, 55]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPCli,ent.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:35
,[ThaliCore] VirtualSocket.closeStreams() vsID:35
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:36
[ThaliCore] VirtualSocket.closeStreams() vsID:36
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:35
,[ThaliCore] VirtualSocket.deinit vsID:35 [6, 26, 32, 34, 36, 37, 40, 41, 48, 49, 50, 55]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:36
,[ThaliCore] VirtualSocket.deinit vsID:36 [6, 26, 32, 34, 37, 40, 41, 48, 49, 50, 55]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:40
[ThaliCore] VirtualSocket.closeStreams() vsID:40
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:40
[ThaliCore] VirtualSocket.deinit vsID:40 [6, 26, 32, 34, 37, 41, 48, 49, 50, 55]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:32
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:32
,[ThaliCore] VirtualSocket.deinit vsID:32 [6, 26, 34, 37, 41, 48, 49, 50, 55]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:34
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:34
,[ThaliCore] VirtualSocket.deinit vsID:34 [6, 26, 37, 41, 48, 49, 50, 55]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:37
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:37
,[ThaliCore] VirtualSocket.deinit vsID:37 [6, 26, 41, 48, 49, 50, 55]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:41
[ThaliCore] Browse,rRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:41
[ThaliCore] VirtualSocket.deinit vsID:41 [6, 26, 48, 49, 50, 55]
,2017-07-14 12:45:22 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:F31DA80D-5F19-4969-9F65-323952DF140D:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F31DA80D-5F19-4969-9F65-323952DF140D:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:56 [6, 26, 48, 49, 50, 55, 56]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:F31DA80D-5F19-4969-9F65-323952DF140D:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F31DA80D-5F19-4969-9F65-323952DF140D:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:57 [6, 26, 48, 49, 50, 55, 56, 57]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStream,sHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:10B0CD6D-69F3-4A6F-93D9-C349008463B8
[ThaliCore] Session.startOutputStream(with:) peer:10B0CD6D-69F3-4A6F-93D9-C349008463B8
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5,8 [6, 26, 48, 49, 50, 55, 56, 57, 58]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:F31DA80D-5F19-4969-9F65-323952DF140D:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F31DA80D-5F19-4969-9F65-323952DF140D:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:59 [6, 26, 48, 49, 50, 55, 56, 57, 58, 59]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vs,ID:55
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:55
,[ThaliCore] VirtualSocket.deinit vsID:55 [6, 26, 48, 49, 50, 56, 57, 58, 59]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:56
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:56
[ThaliCore] VirtualSocket.deinit vsID:56 [6, 26, 48, 49, 50, 57, 58, 59]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vs,ID:57
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:57
,[ThaliCore] VirtualSocket.deinit vsID:57 [6, 26, 48, 49, 50, 58, 59]
,2017-07-14 12:45:23 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNRESET","status":500}'
,2017-07-14 12:45:23 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 socket hang up -1'
,2017-07-14 12:45:23 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: socket hang up -1  but we are already killed and so we ignored it'
,2017-07-14 12:45:23 - DEBUG thaliReplicationPeerAction: 'Got error in update: 500 socket hang up -1, but we are already killed and so we ignored it'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vs,ID:59
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:59
[ThaliCore] VirtualSocket.deinit vsID:59 [6, 26, 48, 49, 50, 58]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:48
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:49
[ThaliCore] VirtualSocket.closeStreams() vsID:48
[ThaliCore] VirtualSocket.closeStreams() vsID:49
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:48
[ThaliCore] VirtualSocket.deinit vsID:48 [6, 26, 49, 50, 58]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:49
,[ThaliCore] VirtualSocket.deinit vsID:49 [6, 26, 50, 58]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay,.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:50
[ThaliCore] VirtualSocket.closeStreams() vsID:50
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:50
[ThaliCore] VirtualSocket.deinit vsID:50 [6, 26, 58]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:58
[ThaliCore] VirtualSocket.closeStreams() vsID:58
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:58
[ThaliCore] VirtualSocket.deinit vsID:58 [6, 26]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
,2017-07-14 12:45:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 12:45:23 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"9AD30652-AF46-462F-A2F8-6E33AB8997AB","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-14 12:45:23 - WARN thaliNotificationClient: 'peer is not available'
,2017-07-14 12:45:23 - WARN thaliNotificationClient: 'peer is not available'
,2017-07-14 12:45:23 - WARN thaliNotificationClient: 'peer is not available'
,2017-07-14 12:45:23 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"F31DA80D-5F19-4969-9F65-323952DF140D","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-14 12:45:23 - WARN thaliNotificationClient: 'peer is not available'
,2017-07-14 12:45:23 - WARN thaliNotificationClient: 'peer is not available'
,2017-07-14 12:45:23 - WARN thaliNotificationClient: 'peer is not available'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 12:45:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 12:45:23 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
,2017-07-14 12:45:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,[ThaliCore] VirtualSocket exited RunLoop vsID:26
[ThaliCore] VirtualSocket.deinit vsID:26 [6]
,2017-07-14 12:45:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:45:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 12:45:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 909 passed
,# teardown
,# setup
,# Coordinated replication action test - should throw error when wrong remote db name is provided
,2017-07-14 12:45:24 - DEBUG thaliMobileNativeWrapper: 'listening 50818'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:648234A4-5567-4B77-AEDF-D1DCB6E0B4B6
,[ThaliCore] Browser.startListening
,2017-07-14 12:45:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "91E9A4F1-A2DD-4788-9B80-C8052C530F87", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:91E9A4F1-A2DD-4788-9B80-C8052C530F87
,2017-07-14 12:45:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
[ThaliCore] Session.startOutputStream(with:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:60 [6, 60]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=1 "Operation not permitted" UserInfo={NSLocalizedDescription=Operation not permitted, NSLocalizedFailureReason=Error in connect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:60
[ThaliCore] VirtualSocket.closeStreams() vsID:60
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:60
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
[ThaliCore] Session.startOutputStream(with:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
[ThaliCore] Vi,rtualSocket.deinit vsID:60 [6]
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:61 [6, 61]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=2 "No such file or directory" UserInfo={NSLocalizedDescription=No such file or directory, NSLocalizedFailureReason=Error ,in connect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
[ThaliCore] Session.startOutputStream(with:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6,2 [6, 61, 62]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:61
[ThaliCore] VirtualSocket.closeStreams() vsID:61
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:61
[ThaliCore] VirtualSocket.deinit vsID:61 [6, 62]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=2 "No such file or directory" UserInfo={NSLocalizedDescription=No such file or directory, NSLocalizedFailureReason=Error in connect() function})
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:62
[ThaliCore] VirtualSocket.closeStreams() vsID:62
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:62
,[ThaliCore] VirtualSocket.deinit vsID:62 [6]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
,[ThaliCore] Session.startOutputStream(with:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:63 [6, 63]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedDescription=Connection refused, NSLocalizedFailureReason=Error in connect() ,function})
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:63
[ThaliCore] VirtualSocket.closeStreams() vsID:63
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
[ThaliCore] Session.startOutputStream(with:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6,4 [6, 63, 64]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=70 "Stale NFS file handle" UserInfo={NSLocalizedDescription=Stale NFS file handle, NSLocalizedFailureReason=Error in connect() function})
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:64
[ThaliCore] VirtualSocket.closeStreams() vsID:64
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:64
,[ThaliCore] VirtualSocket.deinit vsID:64 [6, 63]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
[ThaliCore] Session.startOutputStream(with:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:65 [6, 63, 65]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedDescription=Connection refused, NSLocalizedFailureReason=Error in connect() ,function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:65
[ThaliCore] VirtualSocket.closeStreams() vsID:65
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:65
[ThaliCore] VirtualSocket.deinit vsID:65 [6, 63]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
[ThaliCore] Session.startOutputStream(with:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6,6 [6, 63, 66]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedDescription=Connection refused, NSLocalizedFailureReason=Error in connect() ,function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:66
[ThaliCore] VirtualSocket.closeStreams() vsID:66
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:66
[ThaliCore] VirtualSocket.deinit vsID:66 [6, 63]
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9AD30652-AF46-462F-A2F8-6E33AB8997AB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9AD30652-AF46-462F-A2F8-6E33AB8997AB", generation: 0)
,2017-07-14 12:45:25 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"9AD30652-AF46-462F-A2F8-6E33AB8997AB","generation":0}]'
,2017-07-14 12:45:25 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"9AD30652-AF46-462F-A2F8-6E33AB8997AB","generation":0}'
,2017-07-14 12:45:25 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"9AD30652-AF46-462F-A2F8-6E33AB8997AB","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 12:45:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9AD30652-AF46-462F-A2F8-6E33AB8997AB","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-14 12:45:25 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 9AD30652-AF46-462F-A2F8-6E33AB8997AB (syncValue: 15)'
,2017-07-14 12:45:25 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "9AD30652-AF46-462F-A2F8-6E33AB8997AB", generation: 0) found active relay
,2017-07-14 12:45:25 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"15","error":null,"portNumber":50778}'
,2017-07-14 12:45:25 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 9AD30652-AF46-462F-A2F8-6E33AB8997AB (syncValue: 16)'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
,[ThaliCore] Session.startOutputStream(with:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:67 [6, 63, 67]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedDescription=Connection refused, NSLocalizedFailureReason=Error in connect() ,function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:67
,[ThaliCore] VirtualSocket.closeStreams() vsID:67
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:67
,[ThaliCore] VirtualSocket.deinit vsID:67 [6, 63]
,2017-07-14 12:45:25 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "9AD30652-AF46-462F-A2F8-6E33AB8997AB", generation: 0) found active relay
,2017-07-14 12:45:25 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"16","error":null,"portNumber":50778}'
,2017-07-14 12:45:25 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 9AD30652-AF46-462F-A2F8-6E33AB8997AB (syncValue: 17)'
,2017-07-14 12:45:25 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "9AD30652-AF46-462F-A2F8-6E33AB8997AB", generation: 0) found active relay
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DD9A9580-4877-495F-9C40-3FEB21F0DA73:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DD9A9580-4877-495F-9C40-3FEB21F0DA73", generation: 0)
2017-07-14 12:45:25 - DEBUG t,haliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"17","error":null,"portNumber":50778}'
,2017-07-14 12:45:25 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 9AD30652-AF46-462F-A2F8-6E33AB8997AB (syncValue: 18)'
,2017-07-14 12:45:25 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "9AD30652-AF46-462F-A2F8-6E33AB8997AB", generation: 0) found active relay
,2017-07-14 12:45:25 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"18","error":null,"portNumber":50778}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:9AD30652-AF46-462F-A2F8-6E33AB8997AB:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:10B0CD6D-69F3-4A6F-93D9-C349008463B8
,[ThaliCore] Session.startOutputStream(with:) peer:10B0CD6D-69F3-4A6F-93D9-C349008463B8
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:68 [6, 63, 68]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9AD30652-AF46-462F-A2F8-6E33AB8997AB:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:10B0CD6D-69F3-4A6F-93D9-C349008463B8
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:69 [6, 63, 68, 69]
,[ThaliCore] Session.startOutputStream(with:) peer:10B0CD6D-69F3-4A6F-93D9-C349008463B8
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:70 [6, 63, 68, 69, 70]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:10B0CD6D-69F3-4A6F-93D9-C349008463B8
[ThaliCore] Session.startOutputStream(with:) peer:10B0CD6D-69F3-4A6F-93D9-C349008463B8
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:71 [6, 63, 68, 69, 70, 71]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:10B0CD6D-69F3-4A6F-93D9-C349008463B8
[ThaliCore] Session.startOutputStream(with:) peer:10B0CD6D-69F3-4A6F-93D9-C349008463B8
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7,2 [6, 63, 68, 69, 70, 71, 72]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
[ThaliCore] Session.startOutputStream(with:) peer:9AD30652-AF46-462F-A2F8-6E33AB8997AB:,0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:9AD30652-AF46-462F-A2F8-6E33AB8997AB:0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:69
[ThaliCore] VirtualSocket.closeStreams() vsID:69
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:69
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:9AD30652-AF46-462F-A2F8-6E33AB8997AB:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] VirtualSocket.deinit vsID:69 [6, 63, 68, 70, 71, 72]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=0 "Undefined error: 0" UserInfo={NSLocalizedDescription=Undefined error: 0, NSLocalizedFailureReason=Error in connect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:70
[ThaliCore] VirtualSocket.closeStreams() vsID:70
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedDescription=Connection refused, NSLocalizedFailureReason=Error in connect() ,function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:71
[ThaliCore] VirtualSocket.closeStreams() vsID:71
[ThaliCore] VirtualSocket exited RunLoop vsID:70
[ThaliCore] VirtualSocket.deinit vsID:70 [6, 63, 68, 71, 72]
[ThaliC,ore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedDescription=Connection refused, NSLocalizedFailureReason=Error in connect() functio,n})
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:72
[ThaliCore] VirtualSocket.closeStreams() vsID:72
[ThaliCore] AdvertiserRelay.didCloseVirtual,SocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:71
[ThaliCore] VirtualSocket.deinit vsID:71 [6, 63, 68, 72]
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:72
,[ThaliCore] VirtualSocket.deinit vsID:72 [6, 63, 68]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=0 "Undefined error: 0" UserInfo={NSLocalizedDescription=Undefined error: 0, NSLocalizedFailureReason=Error in connect() f,unction})
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:68
,[ThaliCore] VirtualSocket.closeStreams() vsID:68
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:68
[ThaliCore] VirtualSocket.deinit vsID:68 [6, 63]
,2017-07-14 12:45:25 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9AD30652-AF46-462F-A2F8-6E33AB8997AB:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:73 [6, 63, 73]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9AD30652-AF46-462F-A2F8-6E33AB8997AB:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:74 [6, 63, 73, 74]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-14 12:45:25 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"DD9A9580-4877-495F-9C40-3FEB21F0DA73","generation":0}]'
,2017-07-14 12:45:25 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"DD9A9580-4877-495F-9C40-3FEB21F0DA73","generation":0}'
,2017-07-14 12:45:25 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"DD9A9580-4877-495F-9C40-3FEB21F0DA73","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 12:45:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"DD9A9580-4877-495F-9C40-3FEB21F0DA73","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9AD30652-AF46-462F-A2F8-6E33AB8997AB:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:75 [6, 63, 73, 74, 75]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-14 12:45:25 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for DD9A9580-4877-495F-9C40-3FEB21F0DA73 (syncValue: 19)'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:73
[ThaliCore] VirtualSocket.closeStreams() vsID:73
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:73
,[ThaliCore] VirtualSocket.deinit vsID:73 [6, 63, 74, 75]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:74
[ThaliCore] VirtualSocket.closeStreams() vsID:74
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:74
,[ThaliCore] VirtualSocket.deinit vsID:74 [6, 63, 75]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocket,DisconnectHandler
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:75
[ThaliCore] VirtualSocket.closeStreams() vsID:75
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] VirtualSocket exited RunLoop vsID:75
,[ThaliCore] VirtualSocket.deinit vsID:75 [6, 63]
,2017-07-14 12:45:25 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "DD9A9580-4877-495F-9C40-3FEB21F0DA73", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "DD9A9580-4877-495F-9C40-3FEB21F0DA73", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:DD9A9580-4877-495F-9C40-3FEB21F0DA73:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-14 12:45:25 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CBBF1823-F1CD-4A02-99F5-32B700AE83E7:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CBBF1823-F1CD-4A02-99F5-32B700AE83E7", generation: 0)
,2017-07-14 12:45:25 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,2017-07-14 12:45:25 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,2017-07-14 12:45:25 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"CBBF1823-F1CD-4A02-99F5-32B700AE83E7","generation":0}]'
,2017-07-14 12:45:25 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"CBBF1823-F1CD-4A02-99F5-32B700AE83E7","generation":0}'
,2017-07-14 12:45:25 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"CBBF1823-F1CD-4A02-99F5-32B700AE83E7","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 12:45:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"CBBF1823-F1CD-4A02-99F5-32B700AE83E7","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
[ThaliCore] Session.startOutputStream(with:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:76 [6, 63, 76]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
[ThaliCore] Session.st,artOutputStream(with:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:77 [6, 63, 76, 77]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:F31DA80D-5F19-4969-9F65-323952DF140D:0 state: connected -> notConnected
,[ThaliCore] Browser: session notConnected Peer(uuid: "F31DA80D-5F19-4969-9F65-323952DF140D", generation: 0)
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50808
[T,haliCore] Session.disconnect() peer:F31DA80D-5F19-4969-9F65-323952DF140D:0
,[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "F31DA80D-5F19-4969-9F65-323952DF140D", generation: 0)
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=70 "Stale NFS file handle" UserInfo={NSLocalizedDescription=Stale NFS file handle, NSLocalizedFailureReason=Error in conn,ect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:76
[ThaliCore] VirtualSocket.closeStreams() vsID:76
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:76
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=70 "Stale NFS file handle" UserInfo={NSLocalizedDescription=Stale NFS file handle, NSLocalizedFailureReason=Error in conn,ect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:77
[ThaliCore] VirtualSocket.closeStreams() vsID:77
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket.deinit vsID:76 [6, 63, 77]
,[ThaliCore] VirtualSocket exited RunLoop vsID:77
,[ThaliCore] VirtualSocket.deinit vsID:77 [6, 63]
,[ThaliCore] Session.session(_:peer:didChange:) peer:DD9A9580-4877-495F-9C40-3FEB21F0DA73:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:91E9A4F1-A2DD-4788-9B80-C8052C530F87:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "91E9A4F1-A2DD-4788-9B80-C8052C530F87", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:DD9A9580-4877-495F-9C40-3FEB21F0DA73:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:DD9A9580-4877-495F-9C40-3FEB21F0DA73:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "DD9A9580-4877-495F-9C40-3FEB21F0DA73", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50839
,2017-07-14 12:45:28 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"19","error":null,"portNumber":50839}'
,2017-07-14 12:45:28 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for DD9A9580-4877-495F-9C40-3FEB21F0DA73 (syncValue: 20)'
,2017-07-14 12:45:28 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "DD9A9580-4877-495F-9C40-3FEB21F0DA73", generation: 0) found active relay
,2017-07-14 12:45:28 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"20","error":null,"portNumber":50839}'
,2017-07-14 12:45:28 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for DD9A9580-4877-495F-9C40-3FEB21F0DA73 (syncValue: 21)'
,2017-07-14 12:45:28 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "DD9A9580-4877-495F-9C40-3FEB21F0DA73", generation: 0) found active relay
,2017-07-14 12:45:28 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"21","error":null,"portNumber":50839}'
,2017-07-14 12:45:28 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for DD9A9580-4877-495F-9C40-3FEB21F0DA73 (syncValue: 22)'
,2017-07-14 12:45:28 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "DD9A9580-4877-495F-9C40-3FEB21F0DA73", generation: 0) found active relay
,2017-07-14 12:45:28 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"22","error":null,"portNumber":50839}'
,2017-07-14 12:45:28 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for CBBF1823-F1CD-4A02-99F5-32B700AE83E7 (syncValue: 23)'
,2017-07-14 12:45:28 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "CBBF1823-F1CD-4A02-99F5-32B700AE83E7", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CBBF1823-F1CD-4A02-99F5-32B700AE83E7", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:CBBF1823-F1CD-4A02-99F5-32B700AE83E7:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:DD9A9580-4877-495F-9C40-3FEB21F0DA73:0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[Th,aliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:DD9A9580-4877-495F-9C40-3FEB21F0DA73:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:DD9A9580-4877-495F-9C40-3FEB21F0DA73:0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[Th,aliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:DD9A9580-4877-495F-9C40-3FEB21F0DA73:0
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:430827BD-0DE6-4A3A-9F93-6F3DF46D2E1C
[ThaliCore] Advertiser: session connected Peer(uuid: "91E9A4F1-A2DD-4788-9B80-C8052C530F87", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:430827BD-0DE6-4A3A-9F93-6F3DF46D2E1C state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:DD9A9580-4877-495F-9C40-3FEB21F0DA73:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:78 [6, 63, 78]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:DD9A9580-4877-495F-9C40-3FEB21F0DA73:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:79 [6, 63, 78, 79]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:DD9A9580-4877-495F-9C40-3FEB21F0DA73:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:80 [6, 63, 78, 79, 80]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
[T,haliCore] Session.session(_:didReceive:withName:fromPeer:) peer:DD9A9580-4877-495F-9C40-3FEB21F0DA73:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:81 [6, 63, 78, 79, 80, 81]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:10B0CD6D-69F3-4A6F-93D9-C349008463B8
[ThaliCore] Session.startOutputStream(with:) peer:10B0CD6D-69F3-4A6F-93D9-C349008463B8
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8,2 [6, 63, 78, 79, 80, 81, 82]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=0 "Undefined error: 0" UserInfo={NSLocalizedDescription=Undefined error: 0, NSLocalizedFailureReason=Error in connect() f,unction})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:82
[ThaliCore] VirtualSocket.closeStreams() vsID:82
[ThaliCore] AdvertiserRelay.didC,loseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:82
[ThaliCore] VirtualSocket.deinit vsID:82 [6, 63, 78, 79, 80, 81]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:10B0CD6D-69F3-4A6F-93D9-C349008463B8
,[ThaliCore] Session.startOutputStream(with:) peer:10B0CD6D-69F3-4A6F-93D9-C349008463B8
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:83 [6, 63, 78, 79, 80, 81, 83]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=0 "Undefined error: 0" UserInfo={NSLocalizedDescription=Undefined error: 0, NSLocalizedFailureReason=Error in connect() f,unction})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:83
,[ThaliCore] VirtualSocket.closeStreams() vsID:83
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:10B0CD6D-69F3-4A6F-93D9-C349008463B8
[ThaliCore] Session.startOutputStream(with:) peer:10B0CD6D-69F3-4A6F-93D9-C349008463B8
,[ThaliCore] VirtualSocket exited RunLoop vsID:83
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:84 [6, 63, 78, 79, 80, 81, 83, 84]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] VirtualSocket.deinit vsID:83 [6, 63, 78, 79, 80, 81, 84]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedDescription=Connection refused, NSLocalizedFailureReason=Error in connect() ,function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:84
,[ThaliCore] VirtualSocket.closeStreams() vsID:84
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:84
,[ThaliCore] VirtualSocket.deinit vsID:84 [6, 63, 78, 79, 80, 81]
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D04E2705-213F-47BC-B6DE-BDE92F4BFA0D
[ThaliCore] Advertiser: session connected Peer(uuid: "91E9A4F1-A2DD-4788-9B80-C8052C530F87", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:D04E2705-213F-47BC-B6DE-BDE92F4BFA0D state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:CBBF1823-F1CD-4A02-99F5-32B700AE83E7:0 state: notConnected -> connecting
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:78
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:78
,[ThaliCore] VirtualSocket.deinit vsID:78 [6, 63, 79, 80, 81]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
,[ThaliCore] VirtualSocket.closeStreams() vsID:80
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:80
,[ThaliCore] VirtualSocket.deinit vsID:80 [6, 63, 79, 81]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
,[ThaliCore] VirtualSocket.closeStreams() vsID:81
,[ThaliCore] VirtualSocket exited RunLoop vsID:81
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:79
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] VirtualSocket exited RunLoop vsID:79
,[ThaliCore] VirtualSocket.deinit vsID:79 [6, 63, 81]
,[ThaliCore] Session.startOutputStream(with:) peer:DD9A9580-4877-495F-9C40-3FEB21F0DA73:0
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket.deinit vsID:81 [6, 63]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:DD9A9580-4877-495F-9C40-3FEB21F0DA73:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:85 [6, 63, 85]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-14 12:45:28 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  404 no_db_file'
,2017-07-14 12:45:28 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: no_db_file  and it caused us to complete'
,ok 910 error should be 'no_db_file'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
,[ThaliCore] VirtualSocket.closeStreams() vsID:85
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:85
,[ThaliCore] VirtualSocket.deinit vsID:85 [6, 63]
,[ThaliCore] Session.session(_:peer:didChange:) peer:10B0CD6D-69F3-4A6F-93D9-C349008463B8 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "E2889C1F-9781-47EB-A87E-5FA42585CC92", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:10B0CD6D-69F3-4A6F-93D9-C349008463B8
,[ThaliCore] AdvertiserRelay.deinit
[ThaliCore] Session.deinit peer:10B0CD6D-69F3-4A6F-93D9-C349008463B8
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:CBBF1823-F1CD-4A02-99F5-32B700AE83E7:0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D04E2705-213F-47BC-B6DE-BDE92F4BFA0D
,[ThaliCore] Session.session(_:peer:didChange:) peer:CBBF1823-F1CD-4A02-99F5-32B700AE83E7:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "CBBF1823-F1CD-4A02-99F5-32B700AE83E7", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50849
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"23","error":null,"portNumber":50849}'
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for CBBF1823-F1CD-4A02-99F5-32B700AE83E7 (syncValue: 24)'
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "CBBF1823-F1CD-4A02-99F5-32B700AE83E7", generation: 0) found active relay
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"24","error":null,"portNumber":50849}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:D04E2705-213F-47BC-B6DE-BDE92F4BFA0D state: connecting -> connected
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for CBBF1823-F1CD-4A02-99F5-32B700AE83E7 (syncValue: 25)'
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "CBBF1823-F1CD-4A02-99F5-32B700AE83E7", generation: 0) found active relay
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"25","error":null,"portNumber":50849}'
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for CBBF1823-F1CD-4A02-99F5-32B700AE83E7 (syncValue: 26)'
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "CBBF1823-F1CD-4A02-99F5-32B700AE83E7", generation: 0) found active relay
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"26","error":null,"portNumber":50849}'
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 9AD30652-AF46-462F-A2F8-6E33AB8997AB (syncValue: 27)'
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "9AD30652-AF46-462F-A2F8-6E33AB8997AB", generation: 0) found active relay
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"27","error":null,"portNumber":50778}'
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 9AD30652-AF46-462F-A2F8-6E33AB8997AB (syncValue: 28)'
2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "9AD30652-AF46-462F-A2F8-6E33AB8997AB", generation: 0) found active relay
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"28","error":null,"portNumber":50778}'
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 9AD30652-AF46-462F-A2F8-6E33AB8997AB (syncValue: 29)'
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "9AD30652-AF46-462F-A2F8-6E33AB8997AB", generation: 0) found active relay
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"29","error":null,"portNumber":50778}'
[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:430827BD-0DE6-4A3A-9F93-6F3DF46D2E1C
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 9AD30652-AF46-462F-A2F8-6E33AB8997AB (syncValue: 30)'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D04E2705-213F-47BC-B6DE-BDE92F4BFA0D
[ThaliCore] Session.startOutputStream(with:) peer:D04E2705-213F-47BC-B6DE-BDE92F4BFA0D
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:86 [6, 63, 86]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D04E2705-213F-47BC-B6DE-BDE92F4BFA0D
[ThaliCore] Session.startOutputStream(with:) peer:D04E2705-213F-47BC-B6DE-BDE92F4BFA0D
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:87 [6, 63, 86, 87]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D04E2705-213F-47BC-B6DE-BDE92F4BFA0D
[ThaliCore] Session.startOutputStream(with:) peer:D04E2705-213F-47BC-B6DE-BDE92F4BFA0D
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:88 [6, 63, 86, 87, 88]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
[ThaliCore] Session.startOutputStream(with:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8,9 [6, 63, 86, 87, 88, 89]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
[ThaliCore] Session.startOutputStream(with:) peer:722F6A08-FE12-4728-9A39-9E5301A5,35C8
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:90 [6, 63, 86, 87, 88, 89, 90]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
[ThaliCore] Session.startOutputStream(with:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=1 "Operation not permitted" UserInfo={NSLocalizedDescription=Operation not permitted, NSLocalizedFailureReason=Error in c,onnect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" ,UserInfo={NSLocalizedDescription=Connection refused, NSLocalizedFailureReason=Error in connect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual ,socket vsID:89
[ThaliCore] VirtualSocket.closeStreams() vsID:89
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:90
[ThaliCore] VirtualSocket.closeStreams() vsID:90
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:89
[ThaliCore] VirtualSocket.deinit vsID:89 [6, 63, 86, 87, 88, 90]
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStream,sHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:90
[ThaliCore] VirtualSocket.deinit vsID:90 [6, 63, 86, 87, 88]
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:91 [6, 63, 86, 87, 88, 91]
[ThaliCore] TCPClient.c,onnectToLocalhost(onPort:)
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
[ThaliCore] Session.startOutputStream(with:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedDescription=Connection refused, NSLocalizedFailureReason=Error in connect() ,function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:91
[ThaliCore] VirtualSocket.closeStreams() vsID:91
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:92 [6, 63, 86, 87, 88, 91, 92]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] VirtualSocket exited RunLoop vsID:91
[ThaliCore] VirtualSocket.deinit vsID:91 [6, 63, 86, 87, 88, 92]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=35 "Resource temporarily unavailable" UserInfo={NSLocalizedDescription=Resource temporarily unavailable, NSLocalizedFailu,reReason=Error in connect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:92
[ThaliCore] VirtualSocket.closeStreams() vsID:92
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:92
,[ThaliCore] VirtualSocket.deinit vsID:92 [6, 63, 86, 87, 88]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D04E2705-213F-47BC-B6DE-BDE92F4BFA0D
,[ThaliCore] Session.startOutputStream(with:) peer:D04E2705-213F-47BC-B6DE-BDE92F4BFA0D
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:93 [6, 63, 86, 87, 88, 93]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "9AD30652-AF46-462F-A2F8-6E33AB8997AB", generation: 0) found active relay
,[ThaliCore] Session.session(_:peer:didChange:) peer:430827BD-0DE6-4A3A-9F93-6F3DF46D2E1C state: connecting -> connected
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"30","error":null,"portNumber":50778}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:CBBF1823-F1CD-4A02-99F5-32B700AE83E7:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:CBBF1823-F1CD-4A02-99F5-32B700AE83E7:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:CBBF1823-F1CD-4A02-99F5-32B700AE83E7:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:CBBF1823-F1CD-4A02-99F5-32B700AE83E7:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:94 [6, 63, 86, 87, 88, 93, 94]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:CBBF1823-F1CD-4A02-99F5-32B700AE83E7:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:9AD30652-AF46-462F-A2F8-6E33AB8997AB:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:CBBF1823-F1CD-4A02-99F5-32B700AE83E7:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:95 [6, 63, 86, 87, 88, 93, 94, 95]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9AD30652-AF46-462F-A2F8-6E33AB8997AB:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:96 [6, 63, 86, 87, 88, 93, 94, 95, 96]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:96
[ThaliCore] VirtualSocket.closeStreams() vsID:96
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:9AD30652-AF46-46,2F-A2F8-6E33AB8997AB:0
[ThaliCore] VirtualSocket exited RunLoop vsID:96
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] Br,owserRelay.didSocketDisconnectHandler
[ThaliCore] VirtualSocket.deinit vsID:96 [6, 63, 86, 87, 88, 93, 94, 95]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:CBBF1823-F1CD-4A02-99F5-32B700AE83E7:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:97 [6, 63, 86, 87, 88, 93, 94, 95, 97]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9AD30652-AF46-462F-A2F8-6E33AB8997AB:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:98 [6, 63, 86, 87, 88, 93, 94, 95, 97, 98]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:98
[ThaliCore] VirtualSocket.closeStreams() vsID:98
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:98
,[ThaliCore] VirtualSocket.deinit vsID:98 [6, 63, 86, 87, 88, 93, 94, 95, 97]
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] Session.startOutputStream(with:) peer:9AD30652-AF46-462F-A2F8-6E33AB8997AB:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9AD30652-AF46-462F-A2F8-6E33AB8997AB:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:99 [6, 63, 86, 87, 88, 93, 94, 95, 97, 99]
[ThaliCore] BrowserRelay.didOpenVirtualSock,etStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:9AD30652-AF46-462F-A2F8-6E33AB8997AB:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:CBBF1823-F1CD-4A02-99F5-32B700AE83E7:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:100 [6, 63, 86, 87, 88, 93, 94, 95, 97, 99, 100]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:99
[ThaliCore] VirtualSocket.closeStreams() vsID:99
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9AD30652-AF46-462F-A2F8-6E33AB8997AB:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:101 [6, 63, 86, 87, 88, 93, 94, 95, 97, 99, 100, 101]
[ThaliCore] BrowserRelay.didClos,eVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket exited RunLoop vsID:99
[ThaliCore] VirtualSocket.deinit vsID:99 [6, 63, 86, 87, 88, 93, 94, 95, 97, 100, 101]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:101
[ThaliCore] VirtualSocket.closeStreams() vsID:101
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] VirtualSocket exited RunLoop vsID:101
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDis,connectHandler
[ThaliCore] VirtualSocket.deinit vsID:101 [6, 63, 86, 87, 88, 93, 94, 95, 97, 100]
,2017-07-14 12:45:31 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,2017-07-14 12:45:31 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,2017-07-14 12:45:31 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,2017-07-14 12:45:31 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:86
[ThaliCore] VirtualSocket.closeStreams() vsID:86
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:86
[ThaliCore] VirtualSocket.deinit vsID:86 [6, 63, 87, 88, 93, 94, 95, 97, 100]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:87
[ThaliCore] VirtualSocket.closeStreams() vsID:87
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:87
[ThaliCore] VirtualSocket.deinit vsID:87 [6, 63, 88, 93, 94, 95, 97, 100]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:88
[ThaliCore] VirtualSocket.closeStreams() vsID:88
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:88
,[ThaliCore] VirtualSocket.deinit vsID:88 [6, 63, 93, 94, 95, 97, 100]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:93
[ThaliCore] VirtualSocket.closeStreams() vsID:93
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:93
,[ThaliCore] VirtualSocket.deinit vsID:93 [6, 63, 94, 95, 97, 100]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D04E2705-213F-47BC-B6DE-BDE92F4BFA0D
[ThaliCore] Session.startOutputStream(with:) peer:D04E2705-213F-47BC-B6DE-BDE92F4BFA0D
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,02 [6, 63, 94, 95, 97, 100, 102]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:430827BD-0DE6-4A3A-9F93-6F3DF46D2E1C
[ThaliCore] Session.startOutputStream(with:) peer:430827BD-0DE6-4A3A-9F93-6F3DF46D2E1C
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:103 [6, 63, 94, 95, 97, 100, 102, 103]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:430827BD-0DE6-4A3A-9F93-6F3DF46D2E1C
,[ThaliCore] Session.startOutputStream(with:) peer:430827BD-0DE6-4A3A-9F93-6F3DF46D2E1C
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:104 [6, 63, 94, 95, 97, 100, 102, 103, 104]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:430827BD-0DE6-4A3A-9F93-6F3DF46D2E1C
[ThaliCore] Session.startOutputStream(with:) peer:430827BD-0DE6-4A3A-9F93-6F3DF46D2E1C
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:105 [6, 63, 94, 95, 97, 100, 102, 103, 104, 105]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:430827BD-0DE6-4A3A-9F93-6F3DF46D2E1C
[ThaliCore] Session.startOutputStream(with:) peer:430827BD-0DE6-4A3A-9F93-6F3DF46D2E1C
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:106 [6, 63, 94, 95, 97, 100, 102, 103, 104, 105, 106]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:102
,[ThaliCore] VirtualSocket.closeStreams() vsID:102
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:102
,[ThaliCore] VirtualSocket.deinit vsID:102 [6, 63, 94, 95, 97, 100, 103, 104, 105, 106]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 9AD30652-AF46-462F-A2F8-6E33AB8997AB (syncValue: 31)'
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "9AD30652-AF46-462F-A2F8-6E33AB8997AB", generation: 0) found active relay
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"31","error":null,"portNumber":50778}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:9AD30652-AF46-462F-A2F8-6E33AB8997AB:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9AD30652-AF46-462F-A2F8-6E33AB8997AB:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:107 [6, 63, 94, 95, 97, 100, 103, 104, 105, 106, 107]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:107
,[ThaliCore] VirtualSocket.closeStreams() vsID:107
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:107
,[ThaliCore] VirtualSocket.deinit vsID:107 [6, 63, 94, 95, 97, 100, 103, 104, 105, 106]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 9AD30652-AF46-462F-A2F8-6E33AB8997AB (syncValue: 32)'
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "9AD30652-AF46-462F-A2F8-6E33AB8997AB", generation: 0) found active relay
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"32","error":null,"portNumber":50778}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:103
,[ThaliCore] VirtualSocket.closeStreams() vsID:103
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:103
[ThaliCore] VirtualSocket.deinit vsID:103 [6, 63, 94, 95, 97, 100, 104, 105, 106]
[ThaliCore] Session.startOutputStream(with:) peer:9AD30652-AF46-462F-A2F8-6E33AB8997AB:0
[ThaliCore] TCPClient.socketDidD,isconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 9AD30652-AF46-462F-A2F8-6E33AB8997AB (syncValue: 33)'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9AD30652-AF46-462F-A2F8-6E33AB8997AB:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:108 [6, 63, 94, 95, 97, 100, 104, 105, 106, 108]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:108
[ThaliCore] VirtualSocket.closeStreams() vsID:108
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] VirtualSocket exited RunLoop vsID:108
,[ThaliCore] VirtualSocket.deinit vsID:108 [6, 63, 94, 95, 97, 100, 104, 105, 106]
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "9AD30652-AF46-462F-A2F8-6E33AB8997AB", generation: 0) found active relay
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"33","error":null,"portNumber":50778}'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:104
[ThaliCore] VirtualSocket.closeStreams() vsID:104
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:104
,[ThaliCore] VirtualSocket.deinit vsID:104 [6, 63, 94, 95, 97, 100, 105, 106]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:9AD30652-AF46-462F-A2F8-6E33AB8997AB:0
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 9AD30652-AF46-462F-A2F8-6E33AB8997AB (syncValue: 34)'
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "9AD30652-AF46-462F-A2F8-6E33AB8997AB", generation: 0) found active relay
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9AD30652-AF46-462F-A2F8-6E33AB8997AB:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:109 [6, 63, 94, 95, 97, 100, 105, 106, 109]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:109
[ThaliCore] VirtualSocket.closeStreams() vsID:109
2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"34","error":null,"portNumber":50778}'
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] VirtualSocket exited RunLoop vsID:109
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] VirtualSocket.deinit vsID:109 [6, 63, 94, 95, 97, 100, 105, 106]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:9AD30652-AF46-462F-A2F8-6E33AB8997AB:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9AD30652-AF46-462F-A2F8-6E33AB8997AB:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:110 [6, 63, 94, 95, 97, 100, 105, 106, 110]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:110
,[ThaliCore] VirtualSocket.closeStreams() vsID:110
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
[ThaliCore] Session.startOutputStream(with:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:111 [6, 63, 94, 95, 97, 100, 105, 106, 110, 111]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:110
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=70 "Stale NFS file handle" UserInfo={NSLocalizedDescription=Stale NFS file handle, NSLocalizedFailureReason=Error in connect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:111
[ThaliCore] VirtualSocket.closeStreams() vsID:111
,[ThaliCore] VirtualSocket.deinit vsID:110 [6, 63, 94, 95, 97, 100, 105, 106, 111]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:111
,[ThaliCore] VirtualSocket.deinit vsID:111 [6, 63, 94, 95, 97, 100, 105, 106]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:95
,[ThaliCore] VirtualSocket exited RunLoop vsID:95
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket.deinit vsID:95 [6, 63, 94, 97, 100, 105, 106]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:97
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:97
,[ThaliCore] VirtualSocket.deinit vsID:97 [6, 63, 94, 100, 105, 106]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:1
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
[ThaliCore] Session.startOutputStream(with:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:112 [6, 63, 94, 100, 105, 106, 112]
[ThaliCore] VirtualSocket.closeStreams() vsID:100
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:100
[ThaliCore] VirtualSocket.deinit vsID:100 [6, 63, 94, 105, 106, 112]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=70 "Stale NFS file handle" UserInfo={NSLocalizedDescription=Stale NFS file handle, NSLocalizedFailureReason=Error in conn,ect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:112
[ThaliCore] VirtualSocket.closeStreams() vsID:112
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:112
,[ThaliCore] VirtualSocket.deinit vsID:112 [6, 63, 94, 105, 106]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:94
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:94
[ThaliCore] VirtualSocket.deinit vsID:94 [6, 63, 105, 106]
,2017-07-14 12:45:32 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:CBBF1823-F1CD-4A02-99F5-32B700AE83E7:0
,2017-07-14 12:45:32 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,2017-07-14 12:45:32 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,2017-07-14 12:45:32 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:CBBF1823-F1CD-4A02-99F5-32B700AE83E7:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:113 [6, 63, 105, 106, 113]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:105
[ThaliCore] VirtualSocket.closeStreams() vsID:105
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:105
[ThaliCore] VirtualSocket.deinit vsID:105 [6, 63, 106, 113]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:106
[ThaliCore] VirtualSocket.closeStreams() vsID:106
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:106
[ThaliCore] VirtualSocket.deinit vsID:106 [6, 63, 113]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:430827BD-0DE6-4A3A-9F93-6F3DF46D2E1C
[ThaliCore] Session.startOutputStream(with:) peer:430827BD-0DE6-4A3A-9F93-6F3DF46D2E1C
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:114 [6, 63, 113, 114]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-14 12:45:32 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  404 no_db_file'
,2017-07-14 12:45:32 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: no_db_file  and it caused us to complete'
,ok 911 error should be 'no_db_file'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vs,ID:113
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:113
,[ThaliCore] VirtualSocket.deinit vsID:113 [6, 63, 114]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:114
[ThaliCore] VirtualSocket.closeStreams() vsID:114
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:114
[ThaliCore] VirtualSocket.deinit vsID:114 [6, 63]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
[ThaliCore] Session.startOutputStream(with:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:115 [6, 63, 115]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=35 "Resource temporarily unavailable" UserInfo={NSLocalizedDescription=Resource temporarily unavailable, NSLocalizedFailu,reReason=Error in connect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:115
[ThaliCore] VirtualSocket.closeStreams() vsID:115
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:115
[ThaliCore] VirtualSocket.deinit vsID:115 [6, 63]
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertis,er.stopAdvertising()
2017-07-14 12:45:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 12:45:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"9AD30652-AF46-462F-A2F8-6E33AB8997AB","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-14, 12:45:32 - WARN thaliNotificationClient: 'peer is not available'
,2017-07-14 12:45:32 - WARN thaliNotificationClient: 'peer is not available'
,2017-07-14 12:45:32 - WARN thaliNotificationClient: 'peer is not available'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
,[ThaliCore] Session.startOutputStream(with:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:116 [6, 63, 116]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedDescription=Connection refused, NSLocalizedFailureReason=Error in connect() ,function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:116
[ThaliCore] VirtualSocket.closeStreams() vsID:116
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:116
,[ThaliCore] VirtualSocket.deinit vsID:116 [6, 63]
,2017-07-14 12:45:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"DD9A9580-4877-495F-9C40-3FEB21F0DA73","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-14 12:45:32 - WARN thaliNotificationClient: 'peer is not available'
,2017-07-14 12:45:32 - WARN thaliNotificationClient: 'peer is not available'
,2017-07-14 12:45:32 - WARN thaliNotificationClient: 'peer is not available'
,2017-07-14 12:45:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"CBBF1823-F1CD-4A02-99F5-32B700AE83E7","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-14 12:45:32 - WARN thaliNotificationClient: 'peer is not available'
,2017-07-14 12:45:32 - WARN thaliNotificationClient: 'peer is not available'
,2017-07-14 12:45:32 - WARN thaliNotificationClient: 'peer is not available'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 12:45:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 12:45:32 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
,2017-07-14 12:45:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,[ThaliCore] VirtualSocket exited RunLoop vsID:63
[ThaliCore] VirtualSocket.deinit vsID:63 [6]
,2017-07-14 12:45:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:45:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 12:45:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 912 passed
,# teardown
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
[ThaliCore] Session.startOutputStream(with:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,17 [6, 117]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=70 "Stale NFS file handle" UserInfo={NSLocalizedDescripti,on=Stale NFS file handle, NSLocalizedFailureReason=Error in connect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:117
[ThaliCore,] VirtualSocket.closeStreams() vsID:117
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:117
[ThaliCore] VirtualSocket.deinit vsID:117 [6]
,# setup
,# compareBufferArrays
,ok 913 should throw
,ok 914 should throw
,ok 915 (unnamed assert)
,ok 916 (unnamed assert)
ok 917 (unnamed assert)
,ok 918 (unnamed assert)
,ok 919 (unnamed assert)
,# teardown
,# setup
,# Call start twice and get error
,ok 920 should throw
,# teardown
,# setup
,# Start and make sure it runs
,# teardown
,# setup
,# Make sure getTimeWhenRun is right after start
,ok 921 (unnamed assert)
,# teardown
,# setup
,# Make sure getTimeWhenRun is -1 after function is called
,ok 922 should be equal
,# teardown
,# setup
,# Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running
,ok 923 should be equal
ok 924 should be equal
ok 925 should throw
,# teardown
,# setup
,# Test TransientState
,ok 926 should throw
,ok 927 should throw
,ok 928 should be equal
,ok 929 should be equal
,ok 930 should be equal
,ok 931 should be equal
,ok 932 (unnamed assert)
,ok 933 (unnamed assert)
,# teardown
,# setup
,# No peers and empty database
,ok 934 verify failed
,ok 935 constructor called once
,ok 936 constructor called with right args
,ok 937 match start arg
,ok 938 start called once
,ok 939 stop called once
,ok 940 stop after start
,# teardown
,# setup
,# One peer and empty DB
,2017-07-14 12:45:37 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 941 verify failed
,ok 942 constructor called once
,ok 943 constructor called with right args
,ok 944 match start arg
,ok 945 start called once
,ok 946 stop called once
,ok 947 stop after start
,# teardown
,# setup
,# One peer with _Local set behind current seq
,2017-07-14 12:45:40 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 948 verify failed
,ok 949 constructor called once
,ok 950 constructor called with right args
,ok 951 match start arg
,ok 952 start called once
,ok 953 stop called once
,ok 954 stop after start
,# teardown
,# setup
,# One peer with _Local set equal to current seq
,2017-07-14 12:45:41 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 955 verify failed
,ok 956 constructor called once
,ok 957 constructor called with right args
,ok 958 match start arg
,ok 959 start called once
,ok 960 stop called once
,ok 961 stop after start
,# teardown
,# setup
,# One peer with _Local set ahead of current seq (and no this should not happen)
,2017-07-14 12:45:42 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 962 verify failed
,ok 963 constructor called once
,ok 964 constructor called with right args
,ok 965 match start arg
,ok 966 start called once
,ok 967 stop called once
,ok 968 stop after start
,# teardown
,# setup
,# Three peers, one not in DB, one behind and one ahead
,2017-07-14 12:45:42 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 969 verify failed
,ok 970 constructor called once
,ok 971 constructor called with right args
,ok 972 match start arg
,ok 973 start called once
,ok 974 stop called once
,ok 975 stop after start
,# teardown
,# setup
,# More than maximum peers, make sure we only send maximum allowed
,2017-07-14 12:45:43 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 976 verify failed
,ok 977 constructor called once
,ok 978 constructor called with right args
,ok 979 match start arg
,ok 980 start called once
,ok 981 stop called once
,ok 982 stop after start
,# teardown
,# setup
,# two peers with empty DB, update the doc
,2017-07-14 12:45:43 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,2017-07-14 12:45:43 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 983 verify failed
,ok 984 constructor called once
,ok 985 constructor called with right args
,ok 986 last start before stop
,ok 987 empty first start
,ok 988 full second start
,ok 989 only 2 timers
,# teardown
,# setup
,# add doc and make sure tokens refresh when they expire
,2017-07-14 12:45:44 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,2017-07-14 12:45:44 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,2017-07-14 12:45:44 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
ok 990 verify failed
ok 991 constructor called once
,ok 992 constructor called with right args
ok 993 start before stop
ok 994 We got at least 3 calls to start
ok 995 at least 3
ok 996 default 1
ok 997 1 run
ok 998 default 2
ok 999 2 run
ok 1000 default 3
,# teardown
,# setup
,# start and stop and start and stop
,ok 1001 start out null
,2017-07-14 12:45:45 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 1002 back to null
,2017-07-14 12:45:45 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 1003 still null
,ok 1004 verify failed
,ok 1005 constructor called once
,ok 1006 constructor called with right args
,ok 1007 first start before first stop
,ok 1008 first stop before second start
,ok 1009 second start before second stop
,# teardown
,# setup
,# two identical starts in a row
,2017-07-14 12:45:46 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 1010 verify failed
,ok 1011 constructor called once
,ok 1012 constructor called with right args
,ok 1013 (unnamed assert)
,# teardown
,# setup
,# two different starts in a row
,2017-07-14 12:45:47 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 1014 verify failed
,ok 1015 constructor called once
,ok 1016 constructor called with right args
,ok 1017 (unnamed assert)
,ok 1018 (unnamed assert)
,# teardown
,# setup
,# two stops and a start and two stops
,2017-07-14 12:45:49 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 1019 verify failed
,ok 1020 constructor called once
,ok 1021 constructor called with right args
,ok 1022 start before stop
,# teardown
,# setup
,# we properly enqueue requests so no then needed
,2017-07-14 12:45:50 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 1023 verify failed
,ok 1024 constructor called once
,ok 1025 constructor called with right args
,ok 1026 start before stop
,# teardown
,# setup
,# test calculateSeqPointKeyId
,ok 1027 should be equal
,ok 1028 should be equal
,# teardown
,# setup
,# #_doImmediateSeqUpdate - server is not there
,2017-07-14 12:45:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 12:45:51 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}'
,ok 1029 Got right error
,# teardown
,2017-07-14 12:45:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - server accepts & closes connection
,2017-07-14 12:45:52 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNRESET","status":500}'
,ok 1030 Got socket hang up
,# teardown
,2017-07-14 12:45:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - server always returns 500
,2017-07-14 12:45:53 - DEBUG localSeqManager: 'Got an error trying to update seq []'
,ok 1031 Got 500 as expected
,# teardown
,2017-07-14 12:45:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - create new seq doc
,ok 1032 should be equal
,ok 1033 revs are equal
,# teardown
,2017-07-14 12:45:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - doc exists, need to get rev and update
,ok 1034 should be equal
,ok 1035 revs are equal
,# teardown
,2017-07-14 12:45:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - update seq three times
,ok 1036 should be equal
,ok 1037 revs are equal
,ok 1038 should be equal
,ok 1039 revs are equal
,ok 1040 should be equal
,ok 1041 revs are equal
,# teardown
,2017-07-14 12:45:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - rev got changed under us
,(node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
,Trace: 
    at $3.prototype.trace@console.js:139:8
    at addListener@events.js:140:1
    at module.exports@/private/var/containers/Bundle/Application/C8C91A98-AF9F-4F81-8796-8AAA5FDEE39E/ThaliTest.app/www/jxcore/node_modules/pouchdb-all-dbs/lib/index.j,s:82:3
    at module.exports/<.start/<@/private/var/containers/Bundle/Application/C8C91A98-AF9F-4F81-8796-8AAA5FDEE39E/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/lib/index.js:143:9
    at tryCatcher@/private/var/containers/Bundle/Application/C,8C91A98-AF9F-4F81-8796-8AAA5FDEE39E/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/util.js:16:16
    at module.exports/Promise.prototype._settlePromiseFromHandler@/private/var/containers/Bundle/Application/C8C91A98-,AF9F-4F81-8796-8AAA5FDEE39E/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:504:13
,2017-07-14 12:46:01 - DEBUG localSeqManager: 'Got an error trying to update seq {"error":"conflict","reason":"Document update conflict","name":"conflict","status":409,"message":"Document update conflict"}'
,ok 1042 Our rev is old so we should fail
,# teardown
,2017-07-14 12:46:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - fail if stop is called
,ok 1043 confirm stop caused failure
,(node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
,Trace: 
    at $3.prototype.trace@console.js:139:8
    at addListener@events.js:140:1
    at module.exports@/private/var/containers/Bundle/Application/C8C91A98-AF9F-4F81-8796-8AAA5FDEE39E/ThaliTest.app/www/jxcore/node_modules/pouchdb-all-dbs/lib/index.j,s:57:3
    at module.exports/<.start/<@/private/var/containers/Bundle/Application/C8C91A98-AF9F-4F81-8796-8AAA5FDEE39E/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/lib/index.js:143:9
    at tryCatcher@/private/var/containers/Bundle/Application/C,8C91A98-AF9F-4F81-8796-8AAA5FDEE39E/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/util.js:16:16
    at module.exports/Promise.prototype._settlePromiseFromHandler@/private/var/containers/Bundle/Application/C8C91A98-,AF9F-4F81-8796-8AAA5FDEE39E/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:504:13
,# teardown
,2017-07-14 12:46:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - stop after get but before put fails right
,2017-07-14 12:46:03 - DEBUG localSeqManager: 'Got an error trying to update seq {"onPut":true}'
,ok 1044 stop caused us to fail
,ok 1045 We specifically failed on a stop before put
,# teardown
,2017-07-14 12:46:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - fail if stop is called
,ok 1046 failed due to stop
,ok 1047 failed due to stop
,# teardown
,2017-07-14 12:46:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - set seq for first time
,ok 1048 should be equal
,# teardown
,2017-07-14 12:46:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - Fail on bad seq value
,2017-07-14 12:46:06 - DEBUG localSeqManager: 'Got a bad seq, submitted seq 9, _nextSeqValueToSend: 10'
,ok 1049 Expected bad seq error
,# teardown
,2017-07-14 12:46:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - do we cancel timer properly on an immediate?
,ok 1050 Different promises
,ok 1051 Timer was cancelled
,ok 1052 should be equal
,# teardown
,2017-07-14 12:46:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - do we wait for blocked update
,ok 1053 One go and one blocked
,ok 1054 All blocked
,ok 1055 Still blocked
,ok 1056 should be equal
,# teardown
,2017-07-14 12:46:11 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - test that we wait long enough
,ok 1057 We waited long enough
,ok 1058 should be equal
,# teardown
,2017-07-14 12:46:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - test that we pick up new sequences while we wait
,ok 1059 Should have gotten same timer promise
,ok 1060 Still same timer promise
,ok 1061 We waited long enough
,ok 1062 should be equal
,# teardown
,2017-07-14 12:46:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
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
2017-07-14 12:46:17 - DEBUG thaliManager: 'creating express pouchdb instance'
,ok 1063 expressPouchDB was called once
,ok 1064 expressPouchDB was called with 2 arguments
,ok 1065 expressPouchDB was called with 'PouchDB' as 1-st argument
,ok 1066 expressPouchDB was called with 'expressPouchDB options' as 2-st argument
,ok 1067 PouchDB was called once
,ok 1068 PouchDB was called with 1 arguments
,ok 1069 PouchDB was called with 'dbName' as 1-st argument
,ok 1070 ThaliSendNotificationBasedOnReplication was called once
ok 1071 ThaliSendNotificationBasedOnReplication was called with 4 arguments
ok 1072 ThaliSendNotificationBasedOnReplication was called with 'express.Router instance' as 1-st argument
ok 107,3 ThaliSendNotificationBasedOnReplication was called with 'ecdhForLocalDevice' as 2-st argument
ok 1074 ThaliSendNotificationBasedOnReplication was called with 'thaliConfig.BEACON_MILLISECONDS_TO_EXPIRE' as 3-st argument
ok 1075 ThaliSendNotificationBase,dOnReplication was called with 'PouchDB instance' as 4-st argument
,ok 1076 ThaliPullReplicationFromNotification was called once
ok 1077 ThaliPullReplicationFromNotification was called with 4 arguments
ok 1078 ThaliPullReplicationFromNotification was called with 'PouchDB' as 1-st argument
ok 1079 ThaliPullReplicationFro,mNotification was called with 'dbName' as 2-st argument
ok 1080 ThaliPullReplicationFromNotification was called with 'ThaliPeerPoolInterface instance' as 3-st argument
ok 1081 ThaliPullReplicationFromNotification was called with 'ecdhForLocalDevice' as 4,-st argument
ok 1082 Salti was called once
ok 1083 Salti was called with 4 arguments
ok 1084 Salti was called with 'dbName' as 1-st argument
ok 1085 Salti was called with 'acl' as 2-st argument
ok 1086 Salti was called with 'thaliIdCallback' as 3-st a,rgument
ok 1087 Salti was called with 'options' as 4-st argument
2017-07-14 12:46:17 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
,2017-07-14 12:46:17 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-07-14 12:46:17 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-07-14 12:46:17 - DEBUG thaliMobileNativeWrapper: 'listening 50951'
,2017-07-14 12:46:17 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:6865CB67-151E-481B-BB4B-6F5FC137F162
,[ThaliCore] Browser.startListening
,2017-07-14 12:46:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 12:46:17 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "7DF690FF-D27D-4CC3-8D08-116A1F6891DE", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:7DF690FF-D27D-4CC3-8D08-116A1F6891DE
,2017-07-14 12:46:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-14 12:46:17 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
,ok 1088 ThaliMobile.start was called once
,ok 1089 ThaliMobile.start was called with 3 arguments
,ok 1090 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
,ok 1091 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
,ok 1092 ThaliMobile.start was called with 'networkType' as 3-st argument
,ok 1093 ThaliMobile.startListeningForAdvertisements was called once
ok 1094 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
ok 1095 ThaliMobile.startUpdateAdvertisingAndListening was called once
ok 1096 ThaliMobile.startUpdateAdv,ertisingAndListening was called with 0 arguments
ok 1097 ThaliSendNotificationBasedOnReplication.prototype.start was called once
ok 1098 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
ok 1099 ThaliSendNotificationBas,edOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
ok 1100 ThaliPullReplicationFromNotification.prototype.start was called once
ok 1101 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
ok 1102 T,haliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
2017-07-14 12:46:17 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,2017-07-14 12:46:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-14 12:46:17 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})'
2017-07-14 12:46:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state,).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-14 12:46:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14, 12:46:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 12:46:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 1103 ThaliMobile.stop was called once
,ok 1104 ThaliMobile.stop was called with 0 arguments
,ok 1105 ThaliSendNotificationBasedOnReplication.prototype.stop was called once
,ok 1106 ThaliSendNotificationBasedOnReplication.prototype.stop was called with 0 arguments
,ok 1107 ThaliPullReplicationFromNotification.prototype.stop was called once
,ok 1108 ThaliPullReplicationFromNotification.prototype.stop was called with 0 arguments
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 12:46:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:46:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,# teardown
,# setup
,# test thali manager multiple starts and stops
,2017-07-14 12:46:18 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
,2017-07-14 12:46:18 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
,2017-07-14 12:46:18 - DEBUG thaliManager: 'creating express pouchdb instance'
,ok 1109 expressPouchDB was called once
,ok 1110 expressPouchDB was called with 2 arguments
,ok 1111 expressPouchDB was called with 'PouchDB' as 1-st argument
,ok 1112 expressPouchDB was called with 'expressPouchDB options' as 2-st argument
,ok 1113 PouchDB was called once
,ok 1114 PouchDB was called with 1 arguments
,ok 1115 PouchDB was called with 'dbName' as 1-st argument
,ok 1116 ThaliSendNotificationBasedOnReplication was called once
,ok 1117 ThaliSendNotificationBasedOnReplication was called with 4 arguments
,ok 1118 ThaliSendNotificationBasedOnReplication was called with 'express.Router instance' as 1-st argument
,ok 1119 ThaliSendNotificationBasedOnReplication was called with 'ecdhForLocalDevice' as 2-st argument
,ok 1120 ThaliSendNotificationBasedOnReplication was called with 'thaliConfig.BEACON_MILLISECONDS_TO_EXPIRE' as 3-st argument
,ok 1121 ThaliSendNotificationBasedOnReplication was called with 'PouchDB instance' as 4-st argument
,ok 1122 ThaliPullReplicationFromNotification was called once
,ok 1123 ThaliPullReplicationFromNotification was called with 4 arguments
,ok 1124 ThaliPullReplicationFromNotification was called with 'PouchDB' as 1-st argument
,ok 1125 ThaliPullReplicationFromNotification was called with 'dbName' as 2-st argument
,ok 1126 ThaliPullReplicationFromNotification was called with 'ThaliPeerPoolInterface instance' as 3-st argument
,ok 1127 ThaliPullReplicationFromNotification was called with 'ecdhForLocalDevice' as 4-st argument
,ok 1128 Salti was called once
,ok 1129 Salti was called with 4 arguments
,ok 1130 Salti was called with 'dbName' as 1-st argument
,ok 1131 Salti was called with 'acl' as 2-st argument
,ok 1132 Salti was called with 'thaliIdCallback' as 3-st argument
,ok 1133 Salti was called with 'options' as 4-st argument
,2017-07-14 12:46:18 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
,2017-07-14 12:46:18 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-07-14 12:46:18 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-07-14 12:46:18 - DEBUG thaliMobileNativeWrapper: 'listening 50953'
,2017-07-14 12:46:18 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:66CCC07A-5E10-4A16-B5FB-A5ED89575EFA
,[ThaliCore] Browser.startListening
,2017-07-14 12:46:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 12:46:18 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "9DD24CEC-B51A-4AC8-B274-B997B9D3FC86", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:9DD24CEC-B51A-4AC8-B274-B997B9D3FC86
,2017-07-14 12:46:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-14 12:46:18 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
,ok 1134 ThaliMobile.start was called once
,ok 1135 ThaliMobile.start was called with 3 arguments
,ok 1136 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
,ok 1137 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
,ok 1138 ThaliMobile.start was called with 'networkType' as 3-st argument
,ok 1139 ThaliMobile.startListeningForAdvertisements was called once
,ok 1140 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
,ok 1141 ThaliMobile.startUpdateAdvertisingAndListening was called once
,ok 1142 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
,ok 1143 ThaliSendNotificationBasedOnReplication.prototype.start was called once
,ok 1144 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
,ok 1145 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
,ok 1146 ThaliPullReplicationFromNotification.prototype.start was called once
,ok 1147 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
,ok 1148 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
,2017-07-14 12:46:18 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
,2017-07-14 12:46:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 12:46:18 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})'
,2017-07-14 12:46:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-14 12:46:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:46:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 12:46:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 12:46:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:46:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 1149 ThaliMobile.stop was called once
,ok 1150 ThaliMobile.stop was called with 0 arguments
,ok 1151 ThaliSendNotificationBasedOnReplication.prototype.stop was called once
,ok 1152 ThaliSendNotificationBasedOnReplication.prototype.stop was called with 0 arguments
,ok 1153 ThaliPullReplicationFromNotification.prototype.stop was called once
,ok 1154 ThaliPullReplicationFromNotification.prototype.stop was called with 0 arguments
,2017-07-14 12:46:18 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
,2017-07-14 12:46:18 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-07-14 12:46:18 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-07-14 12:46:18 - DEBUG thaliMobileNativeWrapper: 'listening 50955'
,2017-07-14 12:46:18 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:29F48DF5-4246-43DC-BD7B-2D29FE4948BD
,[ThaliCore] Browser.startListening
,2017-07-14 12:46:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 12:46:18 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "525B1175-A7EB-4CEE-8802-812F54AD7F25", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:525B1175-A7EB-4CEE-8802-812F54AD7F25
,2017-07-14 12:46:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-14 12:46:18 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
,2017-07-14 12:46:18 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,2017-07-14 12:46:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 12:46:18 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})',
,2017-07-14 12:46:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-14 12:46:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:46:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 12:46:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 12:46:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:46:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 12:46:18 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
,2017-07-14 12:46:18 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-07-14 12:46:18 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-07-14 12:46:18 - DEBUG thaliMobileNativeWrapper: 'listening 50957'
,2017-07-14 12:46:18 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C809EA18-5B92-49A9-B228-C8ED64A01650
,[ThaliCore] Browser.startListening
,2017-07-14 12:46:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 12:46:18 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C32D0CBC-9800-4CD5-B997-B4FFEC38C906", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:C32D0CBC-9800-4CD5-B997-B4FFEC38C906
,2017-07-14 12:46:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-14 12:46:18 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
,2017-07-14 12:46:18 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,2017-07-14 12:46:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 12:46:18 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})'
,2017-07-14 12:46:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-14 12:46:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:46:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 12:46:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 12:46:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:46:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 12:46:18 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
,2017-07-14 12:46:18 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-07-14 12:46:18 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-07-14 12:46:18 - DEBUG thaliMobileNativeWrapper: 'listening 50959'
,2017-07-14 12:46:18 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:B00EF43F-9091-4527-AF6B-913170E68958
,[ThaliCore] Browser.startListening
,2017-07-14 12:46:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 12:46:18 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "9A302359-B43C-4643-89F1-2A900EB58E42", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:9A302359-B43C-4643-89F1-2A900EB58E42
,2017-07-14 12:46:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-14 12:46:18 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
,ok 1155 ThaliMobile.start was called once
,ok 1156 ThaliMobile.start was called with 3 arguments
,ok 1157 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
,ok 1158 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
,ok 1159 ThaliMobile.start was called with 'networkType' as 3-st argument
,ok 1160 ThaliMobile.startListeningForAdvertisements was called once
,ok 1161 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
,ok 1162 ThaliMobile.startUpdateAdvertisingAndListening was called once
,ok 1163 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
,ok 1164 ThaliSendNotificationBasedOnReplication.prototype.start was called once
,ok 1165 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
,ok 1166 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
,ok 1167 ThaliPullReplicationFromNotification.prototype.start was called once
,ok 1168 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
,ok 1169 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
,2017-07-14 12:46:19 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,2017-07-14 12:46:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 12:46:19 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})',
,2017-07-14 12:46:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-14 12:46:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:46:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 12:46:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 12:46:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:46:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,# teardown
,# setup
,# test write
,2017-07-14 12:46:19 - DEBUG CoordinatedClient: 'test was skipped, name: 'test write''
,# teardown
,# setup
,# test repeat write 1
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll can close even when connections open'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll with promise'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning set to false'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll works even with a server that is not listening yet witheatNotRunning set to true'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on a single db change'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of multiple onCheckpointReached handlers on a single db change'
2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReache,d handler on multiple db changes that are in the checkpoints plugin delay interval'
2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints ,plugin delay interval'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultDirectory'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultAdapter'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueue and run in order'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueueAtTop and run backwards'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - mix enqueue and enqueueAtTop'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - queues handled independently'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueued function are always executed asynchronously'
2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - exceptions in the executor are properly han,dled'
2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - basic'
2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - another'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - skip'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - another skip'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox spy'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub'
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
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: failed - test repeat write 1, error: 'TypeError: thaliManager is undefined', stack: 'testRepeatWrite/<@/private/var/containers/Bundle/Application/C8C91A98-AF9F-4F81-8796-8AAA5FDEE39E/Tha,liTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js:279:7
CoordinatedClient.prototype._processEvent/</<@/private/var/containers/Bundle/Application/C8C91A98-AF9F-4F81-8796-8AAA5FDEE39E/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:471:9
canc,ellationExecute@/private/var/containers/Bundle/Application/C8C91A98-AF9F-4F81-8796-8AAA5FDEE39E/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/debuggability.js:320:9
module.exports/Promise.prototype._resolveFromExecutor@/private/var/containers/,Bundle/Application/C8C91A98-AF9F-4F81-8796-8AAA5FDEE39E/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:481:13
Promise@/private/var/containers/Bundle/Application/C8C91A98-AF9F-4F81-8796-8AAA5FDEE39E/ThaliTest.app/www/jxcore/node_modul,es/bluebird/js/release/promise.js:77:9
CoordinatedClient.prototype._processEvent/<@/private/var/containers/Bundle/Application/C8C91A98-AF9F-4F81-8796-8AAA5FDEE39E/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:428:14
tryCatcher@/private/var/containers,/Bundle/Application/C8C91A98-AF9F-4F81-8796-8AAA5FDEE39E/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/util.js:16:16
module.exports/Promise.prototype._settlePromiseFromHandler@/private/var/containers/Bundle/Application/C8C91A98-AF9F-4F81-8796-,8AAA5FDEE39E/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:510:13
module.exports/Promise.prototype._settlePromise@/private/var/containers/Bundle/Application/C8C91A98-AF9F-4F81-8796-8AAA5FDEE39E/ThaliTest.app/www/jxcore/node_modules/,bluebird/js/release/promise.js:567:13
module.exports/Promise.prototype._settlePromise0@/private/var/containers/Bundle/Application/C8C91A98-AF9F-4F81-8796-8AAA5FDEE39E/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:612:5
module.exp,orts/Promise.prototype._settlePromises@/private/var/containers/Bundle/Application/C8C91A98-AF9F-4F81-8796-8AAA5FDEE39E/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:691:13
Async.prototype._drainQueue@/private/var/containers/Bundle/A,pplication/C8C91A98-AF9F-4F81-8796-8AAA5FDEE39E/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/async.js:138:13
Async.prototype._drainQueues@/private/var/containers/Bundle/Application/C8C91A98-AF9F-4F81-8796-8AAA5FDEE39E/ThaliTest.app/www/jxcore,/node_modules/bluebird/js/release/async.js:148:5
Async/this.drainQueues@/private/var/containers/Bundle/Application/C8C91A98-AF9F-4F81-8796-8AAA5FDEE39E/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/async.js:17:9
$v@timers.js:364:1
''
2017-0,7-14 12:46:20 - ERROR CoordinatedClient: 'failed to run unit tests, platformName: 'ios''
,2017-07-14 12:49:21 - DEBUG CoordinatedClient: 'all tests completed'
,2017-07-14 12:49:21 - DEBUG CoordinatedClient: 'test client disconnected'
2017-07-14 12:49:21 - DEBUG CoordinatedClient: 'test client failed'
,2017-07-14 12:49:21 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: TimeoutError: timeout exceeded, event: 'run_test repeat write 1_finished', test: 'test repeat write 1'', stack: 'CoordinatedClient.prototype._customError@/private/var/container,s/Bundle/Application/C8C91A98-AF9F-4F81-8796-8AAA5FDEE39E/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:292:27
Emitter.prototype.emit@/private/var/containers/Bundle/Application/C8C91A98-AF9F-4F81-8796-8AAA5FDEE39E/ThaliTest.app/www/jxcore/node_modules,/component-emitter/index.js:131:7
Socket.prototype.onevent@/private/var/containers/Bundle/Application/C8C91A98-AF9F-4F81-8796-8AAA5FDEE39E/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:263:5
Socket.prototype.onpacket@/private/var/c,ontainers/Bundle/Application/C8C91A98-AF9F-4F81-8796-8AAA5FDEE39E/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:221:7
module.exports/<@/private/var/containers/Bundle/Application/C8C91A98-AF9F-4F81-8796-8AAA5FDEE39E/ThaliTest.app/ww,w/jxcore/node_modules/component-bind/index.js:21:12
Emitter.prototype.emit@/private/var/containers/Bundle/Application/C8C91A98-AF9F-4F81-8796-8AAA5FDEE39E/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7''
2017-07-14 12:49:21 - DEBU,G CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'

```
