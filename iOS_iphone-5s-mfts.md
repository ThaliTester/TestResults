#### Test 113351851d000154_iOS_iphone-5s-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/113351851d000154/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/9AE9D52A-DE5D-43CC-967B-B15411968F73/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'
,Executing commands in '/tmp/9AE9D52A-DE5D-43CC-967B-B15411968F73/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/113351851d000154/build_ios/ThaliTest.app"
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6s Plus 'Iphone6sPlus-1' (f70cda60583ea0f895d05ea355cd125983c27594).
,Current executable set to '/Users/thali/Github/CI/builder/builds/113351851d000154/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/1F438D99-FC6B-4E94-B928-15DE93A9EB98/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57398"
,(lldb)     command script import "/tmp/9AE9D52A-DE5D-43CC-967B-B15411968F73/fruitstrap_bffa901fefdea07f59339a6737776943349f5077.py"
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
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-07-21 07:55:53 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 07:55:53 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 07:55:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:55:53 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:55:53 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:55:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:55:53 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
,AppContextTests.test_didEnterForeground finished
,AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
AppContextTests.test_esonValue finished
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "264B5C56-33A5-428F-AE41-E7B29CB8D254", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:264B5C56-33A5-428F-AE41-E7B29CB8D254
Optional(true)
Optional(false)
App,ContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:364225E2-53E8-42A2-87C2-9B71D5F0508B
[ThaliCore] Browser.st,artListening
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D93001D4-43,36-4D37-BD33-B55758677DA3
[ThaliCore] Browser.startListening
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "56B15A36-621E-45BA-A4C1-9BEC510D5A73", generation: 0)
[ThaliCore] Advertiser.startAdvertising, with peerID:56B15A36-621E-45BA-A4C1-9BEC510D5A73
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:56B15A36-621E-45BA-A4C1-9BEC510D5A73:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "56B15A36-621E-45BA-A4C1-9BEC510D5A73", generation: 0)
,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
,AppContextTests.test_connectReturnValueCorrect finished
AppContextTests finished
All tests finished
All tests finished
,2017-07-21 07:55:55 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
Number of passed tests:  13
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  1.699497163295746
,2017-07-21 07:55:55 - DEBUG UnitTest_app: 'My device name is: 'Apple-iphone-5s-mfts''
,2017-07-21 07:55:55 - WARN testUtils: 'myNameCallback not set!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:56B15A36-621E-45BA-A4C1-9BEC510D5A73:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "56B15A36-621E-45BA-A4C1-9BEC510D5A73", generation: 0)
,2017-07-21 07:55:59 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-07-21 07:55:59 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1F438D99-FC6B-4E94-B928-15DE93A9EB98/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-07-21 07:55:59 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1F438D99-FC6B-4E94-B928-15DE93A9EB98/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-07-21 07:55:59 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1F438D99-FC6B-4E94-B928-15DE93A9EB98/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-07-21 07:55:59 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1F438D99-FC6B-4E94-B928-15DE93A9EB98/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-07-21 07:55:59 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1F438D99-FC6B-4E94-B928-15DE93A9EB98/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-07-21 07:55:59 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1F438D99-FC6B-4E94-B928-15DE93A9EB98/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-07-21 07:55:59 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1F438D99-FC6B-4E94-B928-15DE93A9EB98/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-07-21 07:55:59 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1F438D99-FC6B-4E94-B928-15DE93A9EB98/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-07-21 07:55:59 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1F438D99-FC6B-4E94-B928-15DE93A9EB98/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-07-21 07:55:59 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1F438D99-FC6B-4E94-B928-15DE93A9EB98/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-07-21 07:55:59 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1F438D99-FC6B-4E94-B928-15DE93A9EB98/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-07-21 07:55:59 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1F438D99-FC6B-4E94-B928-15DE93A9EB98/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-07-21 07:56:00 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1F438D99-FC6B-4E94-B928-15DE93A9EB98/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-07-21 07:56:00 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1F438D99-FC6B-4E94-B928-15DE93A9EB98/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-07-21 07:56:00 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1F438D99-FC6B-4E94-B928-15DE93A9EB98/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-07-21 07:56:00 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1F438D99-FC6B-4E94-B928-15DE93A9EB98/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-07-21 07:56:00 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1F438D99-FC6B-4E94-B928-15DE93A9EB98/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-07-21 07:56:00 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1F438D99-FC6B-4E94-B928-15DE93A9EB98/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-07-21 07:56:00 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1F438D99-FC6B-4E94-B928-15DE93A9EB98/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-07-21 07:56:00 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1F438D99-FC6B-4E94-B928-15DE93A9EB98/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-07-21 07:56:00 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1F438D99-FC6B-4E94-B928-15DE93A9EB98/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-07-21 07:56:00 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1F438D99-FC6B-4E94-B928-15DE93A9EB98/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-07-21 07:56:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1F438D99-FC6B-4E94-B928-15DE93A9EB98/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-07-21 07:56:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1F438D99-FC6B-4E94-B928-15DE93A9EB98/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-07-21 07:56:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1F438D99-FC6B-4E94-B928-15DE93A9EB98/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-07-21 07:56:02 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1F438D99-FC6B-4E94-B928-15DE93A9EB98/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-07-21 07:56:02 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1F438D99-FC6B-4E94-B928-15DE93A9EB98/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-07-21 07:56:02 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1F438D99-FC6B-4E94-B928-15DE93A9EB98/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-07-21 07:56:02 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1F438D99-FC6B-4E94-B928-15DE93A9EB98/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-07-21 07:56:02 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1F438D99-FC6B-4E94-B928-15DE93A9EB98/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-07-21 07:56:02 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1F438D99-FC6B-4E94-B928-15DE93A9EB98/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-07-21 07:56:02 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1F438D99-FC6B-4E94-B928-15DE93A9EB98/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-07-21 07:56:02 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1F438D99-FC6B-4E94-B928-15DE93A9EB98/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-07-21 07:56:02 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1F438D99-FC6B-4E94-B928-15DE93A9EB98/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-07-21 07:56:02 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1F438D99-FC6B-4E94-B928-15DE93A9EB98/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-07-21 07:56:02 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1F438D99-FC6B-4E94-B928-15DE93A9EB98/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-07-21 07:56:02 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1F438D99-FC6B-4E94-B928-15DE93A9EB98/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-07-21 07:56:02 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1F438D99-FC6B-4E94-B928-15DE93A9EB98/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-07-21 07:56:02 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1F438D99-FC6B-4E94-B928-15DE93A9EB98/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-07-21 07:56:02 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1F438D99-FC6B-4E94-B928-15DE93A9EB98/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-07-21 07:56:03 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-07-21 07:56:03 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
,2017-07-21 07:56:03 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
,# setup
,# closeAll can close even when connections open
,2017-07-21 07:56:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 1 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll with promise
,2017-07-21 07:56:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 2 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll properly throws when closing a non open server with eatNotRunning set to false
,2017-07-21 07:56:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
,# teardown
,# setup
,# closeAll works even with a server that is not listening yet witheatNotRunning set to true
,2017-07-21 07:56:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
,# setup
,# Call of onCheckpointReached handler on a single db change
,2017-07-21 07:56:19 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on a single db change''
,# teardown
,# setup
,# Call of multiple onCheckpointReached handlers on a single db change
,2017-07-21 07:56:20 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of multiple onCheckpointReached handlers on a single db change''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
,2017-07-21 07:56:20 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
,2017-07-21 07:56:21 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''
,# teardown
,# setup
,# test defaultDirectory
,ok 4 should be equal
,ok 5 should be equal
ok 6 should be equal
,# teardown
,# setup
,# test defaultAdapter
,ok 7 should be equal
,ok 8 should be equal
,ok 9 should be equal
ok 10 should be equal
,ok 11 should be equal
,ok 12 should be equal
,ok 13 should be equal
,ok 14 should be equal
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
,# teardown
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
,2017-07-21 07:56:37 - DEBUG CoordinatedClient: 'test was skipped, name: 'skip''
,# teardown
,# setup
,# another skip
,2017-07-21 07:56:38 - DEBUG CoordinatedClient: 'test was skipped, name: 'another skip''
,# teardown
,# setup
,# test sinon sansbox spy
,2017-07-21 07:56:39 - DEBUG testTests: 'test spy method for global sinon sansbox'
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
ok 53 participant data matches
ok 54 test participant has uuid
ok 55 participant data matches
ok 56 own UUID is found from the participants list
,# teardown
,# setup
,# Correctly parses/stringifies USN
,ok 57 correctly parses USN string
,ok 58 throws if usn has invalid prefix
,ok 59 throws if usn has invalid identifier format
,ok 60 throws if usn has invalid generation
,ok 61 correctly stringifies peer
,# teardown
,# setup
,# onPeerLost calls jxcore
,2017-07-21 07:56:42 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
,# teardown
,2017-07-21 07:56:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 07:56:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 07:56:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:56:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:56:42 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:56:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:56:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:56:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# onPeerDiscovered calls jxcore
,2017-07-21 07:56:42 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
,# teardown
,2017-07-21 07:56:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 07:56:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 07:56:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:56:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 07:56:42 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 07:56:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 07:56:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:56:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopListeningForAdvertisements
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:3AB66B00-5D25-443F-835C-37FC0E66DC9C
[ThaliCore] Browser.startListening
2017-07-21 07:56:43 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 07:56:43 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 07:56:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 62 Can call startLis,teningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 07:56:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 07:56:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 63 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 07:56:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:56:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 07:56:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:56:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 07:56:43 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 07:56:43 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 07:56:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:56:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:56:43 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:56:43 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:56:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:56:43 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startListeningForAdvertisements twice is NOT an error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:7B61E842-5EC2-48E9-A5B9-682CE3134255
[ThaliCore] Browser.startListening
2017-07-21 07:56:44 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 07:56:44 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 07:56:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 64 Can call startLis,teningForAdvertisements without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
2017-07-21 07:56:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 07:56:44 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 07:56:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 65 Can call startListeningForAdvertisements twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 07:56:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:56:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 07:56:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:56:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 07:56:44 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 07:56:44 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 07:56:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:56:44 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:56:44 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:56:44 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:56:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:56:44 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling stopListeningForAdvertisements without calling start is NOT an error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 07:56:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:56:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 66 Can call stopListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 07:56:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisin,gActive":false}'
2017-07-21 07:56:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 67 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 07:56:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:56:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 07:56:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:56:46 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 07:56:46 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 07:56:46 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-07-21 07:56:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:56:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:56:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:56:46 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:56:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:56:46 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopUpdateAdvertisingAndListening
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "97866DE3-8FF5-4ADA-B58B-AC3D0B986D3B", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:97866DE3-8FF5-4ADA-B58B-AC3D0B986D3B
2017-07-21 0,7:56:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 07:56:46 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 07:56:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 68 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:97866DE3-8FF5-4ADA-B58B-AC3D0B986D3B
,2017-07-21 07:56:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:56:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 69 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 07:56:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:56:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 07:56:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:56:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 07:56:47 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 07:56:47 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 07:56:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:56:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:56:47 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:56:47 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:56:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:56:47 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startUpdateAdvertisingAndListening twice is NOT an error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "DC1A820E-1038-4199-B7C0-8627A620DB17", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:DC1A820E-1038-4199-B7C0-8627A620DB17
,2017-07-21 07:56:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 07:56:47 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 07:56:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 70 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHa,ndler:) Peer(uuid: "DC1A820E-1038-4199-B7C0-8627A620DB17", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:DC1A820E-1038-4199-B7C0-8627A620DB17
,2017-07-21 07:56:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-21 07:56:47 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-21 07:56:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 71 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 07:56:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 07:56:47 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 07:56:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:DC1A820E-1038-4199-B7C0-8627A620DB17
[ThaliCore] Advertiser.stopAdvertising() peerID:DC1A820E-1038-4199-B7C0-8627A620DB17,
2017-07-21 07:56:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:56:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped stat,e).'
,2017-07-21 07:56:47 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 07:56:47 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 07:56:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:56:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:56:47 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:56:47 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:56:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:56:47 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 07:56:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:56:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 72 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 07:56:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:56:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 73 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 07:56:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:56:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 07:56:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:56:48 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 07:56:48 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 07:56:48 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-07-21 07:56:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:56:48 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:56:48 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:56:48 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:56:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:56:48 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peerAvailabilityChange is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C21BA560-FF4E-445D-9B31-8D16DD9BA945", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:C21BA560-FF4E-445D-9B31-8D16DD9BA945
2017-07-21 07:56:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 07:56:48, - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkTy,pe":null}})'
2017-07-21 07:56:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 74 Can call startUpdateAdvertisingAndListeningwithout error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[Thali,Core] Browser.init(serviceType:foundPeer:lostPeer:) peer:39979313-D2D2-4363-9EE4-911DBAD05A4F
[ThaliCore] Browser.startListening
2017-07-21 07:56:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"adver,tisingActive":true}'
,2017-07-21 07:56:48 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-21 07:56:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 75 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CD6697C3-80A5-4BF6-8ACF-DDFD13E1FBCF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CD6697C3-80A5-4BF6-8ACF-DDFD13E1FBCF", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6F4D58C6-50EC-4889-A6E2-79C7E140AF34:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6F4D58C6-50EC-4889-A6E2-79C7E140AF34", generation: 0)
ok 76 peers must be an array,
ok 77 peers must not be zero-length
,ok 78 peer must have only peerIdentifier, peerAvailable and generation properties
ok 79 peerIdentifier must be a string
,ok 80 generation must be a number
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C21BA560-FF4E-445D-9B31-8D16DD9BA945:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C21BA560-FF4E-445D-9B31-8D16DD9BA945", generation: 0)
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 07:56:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 07:56:49 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 07:56:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:C21BA560-FF4E-445D-9B31-8D16DD9BA945
2017-07-21 07:56:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdat,eNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:56:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 07:56:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 07:56:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 07:56:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:56:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:56:49 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:56:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:56:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:56:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can connect to a remote peer
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "1DB06BF0-3361-4720-9B4B-E8F6A5B37989", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:1DB06BF0-3361-4720-9B4B-E8F6A5B37989
2017-07-21 0,7:56:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 07:56:50 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 07:56:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 81 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:F8527CE8-7E0E-46C7-8476-2D0D47B99EA4
[Thal,i,Core] Browser.startListening
2017-07-21 07:56:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 07:56:50 - INFO thaliMobile: 'Received state ({"discoveryActive":true,,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 07:56:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 82 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CD6697C3-80A5-4BF6-8ACF-DDFD13E1FBCF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CD6697C3-80A5-4BF6-8ACF-DDFD13E1FBCF", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6F4D58C6-50EC-4889-A6E2-79C7E140AF34:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6F4D58C6-50EC-4889-A6E2-79C7E140AF34", generation: 0)
,2017-07-21 07:56:50 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"CD6697C3-80A5-4BF6-8ACF-DDFD13E1FBCF","generation":0}'
,2017-07-21 07:56:50 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for CD6697C3-80A5-4BF6-8ACF-DDFD13E1FBCF (syncValue: QgjUxLVFNFCdWPb4tBIDUjueD0KliFKy)'
,2017-07-21 07:56:50 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "CD6697C3-80A5-4BF6-8ACF-DDFD13E1FBCF", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CD6697C3-80A5-4BF6-8ACF-DDFD13E1FBCF", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:CD6697C3-80A5-4BF6-8ACF-DDFD13E1FBCF:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 07:56:50 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"6F4D58C6-50EC-4889-A6E2-79C7E140AF34","generation":0}'
2017-07-21 07:56:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 07:56:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:22B764CD-1CCE-4DBA-91F5-A067A3B0164D:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "22B764CD-1CCE-4DBA-91F5-A067A3B0164D", generation: 0)
,2017-07-21 07:56:50 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"22B764CD-1CCE-4DBA-91F5-A067A3B0164D","generation":0}'
2017-07-21 07:56:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 07:56:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 07:56:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:26D99AE4-FD01-4D89-8824-8246C4432DC5:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "26D99AE4-FD01-4D89-8824-8246C4432DC5", generation: 0)
,2017-07-21 07:56:50 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"26D99AE4-FD01-4D89-8824-8246C4432DC5","generation":0}'
,2017-07-21 07:56:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 07:56:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 07:56:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 07:56:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1DB06BF0-3361-4720-9B4B-E8F6A5B37989:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1DB06BF0-3361-4720-9B4B-E8F6A5B37989", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:CD6697C3-80A5-4BF6-8ACF-DDFD13E1FBCF:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:CD,6697C3-80A5-4BF6-8ACF-DDFD13E1FBCF:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "CD6697C3-80A5-4BF6-8ACF-DDFD13E1FBCF", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C,D6697C3-80A5-4BF6-8ACF-DDFD13E1FBCF", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CD6697C3-80A5-4BF6-8ACF-DDFD13E1FBCF", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:CD6697C3-80A5-4BF6-8ACF-DDFD13E1FBCF:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
[ThaliCore] Session.deinit, ,peer:CD6697C3-80A5-4BF6-8ACF-DDFD13E1FBCF:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:CD6697C3-80A5-4BF6-8ACF-DDFD13E1FBCF:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:CD,6697C3-80A5-4BF6-8ACF-DDFD13E1FBCF:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "CD6697C3-80A5-4BF6-8ACF-DDFD13E1FBCF", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C,D6697C3-80A5-4BF6-8ACF-DDFD13E1FBCF", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CD6697C3-80A5-4BF6-8ACF-DDFD13E1FBCF", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:CD6697C3-80A5-4BF6-8ACF-DDFD13E1FBCF:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:CD6697C3-80A5-4BF6-8ACF-DDFD13E1FBCF:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:6F4D58C6-50EC-4889-A6E2-79C7E140AF34:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "6F4D58C6-50EC-4889-A6E2-79C7E140AF34", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:CD6697C3-80A5-4BF6-8ACF-DDFD13E1FBCF:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "CD6697C3-80A5-4BF6-8ACF-DDFD13E1FBCF", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:862E2617-8FB6-4A3C-A4F3-3A422747726D
[ThaliCore] Advertiser: session connected Peer(uuid: "1DB06BF0-3361-4720-9B4B-E8F6A5B37989", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:862E2617-8FB6-4A3C-A4F3-3A422747726D state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:CD6697C3-80A5-4BF6-8ACF-DDFD13E1FBCF:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:CD,6697C3-80A5-4BF6-8ACF-DDFD13E1FBCF:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "CD6697C3-80A5-4BF6-8ACF-DDFD13E1FBCF", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C,D6697C3-80A5-4BF6-8ACF-DDFD13E1FBCF", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CD6697C3-80A5-4BF6-8ACF-DDFD13E1FBCF", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 07:56:59 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"QgjUxLVFNFCdWPb4tBIDUjueD0KliFKy","error":"Peer is unavailable","portNumber":null}'
2017-07-21 07:56:59 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'QgjUxLVFNFCdWPb4tBIDUjueD0KliFKy', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-21 07:56:59 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"CD6697C3-80A5-4BF6-8ACF-DDFD13E1FBCF","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 07:56:59 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-21 07:56:59 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"CD6697C3-80A5-4BF6-8ACF-DDFD13E1FBCF","peerAvailable":true,"portNumber":null,"recreated,":true}'
,2017-07-21 07:56:59 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 07:56:59 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-21 07:56:59 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 22B764CD-1CCE-4DBA-91F5-A067A3B0164D (syncValue: zI9AfwfWMDuTkNmnD4h3l9S,lK7wyR2K9)'
2017-07-21 07:56:59 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "22B764CD-1CCE-4DBA-91F5-A067A3B0164D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "22B764CD-1CCE-4DBA-91F5-A067A3B0164D", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:22B764CD-1CCE-4DBA-91F5-A067A3B0164D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-21 07:56:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:CD6697C3-80A5-4BF6-8ACF-DDFD13E1FBCF:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:16864A41-D630-45C1-B0AF-4E67A4AC8C31
[ThaliCore] Advertiser: session connected Peer(uuid: "1DB06BF0-3361-4720-9B4B-E8F6A5B37989", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:16864A41-D630-45C1-B0AF-4E67A4AC8C31 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:22B764CD-1CCE-4DBA-91F5-A067A3B0164D:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:862E2617-8FB6-4A3C-A4F3-3A422747726D
,[ThaliCore] Session.session(_:peer:didChange:) peer:862E2617-8FB6-4A3C-A4F3-3A422747726D state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:16864A41-D630-45C1-B0AF-4E67A4AC8C31
,[ThaliCore] Session.session(_:peer:didChange:) peer:16864A41-D630-45C1-B0AF-4E67A4AC8C31 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:22B764CD-1CCE-4DBA-91F5-A067A3B0164D:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:22B764CD-1CCE-4DBA-91F5-A067A3B0164D:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "22B764CD-1CCE-4DBA-91F5-A067A3B0164D", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:56942
,2017-07-21 07:57:02 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"zI9AfwfWMDuTkNmnD4h3l9SlK7wyR2K9","error":null,"portNumber":56942}'
2017-07-21 07:57:02 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'zI9AfwfWMDuTkNmnD4h3l9SlK7wyR2K9', error: 'null', listeningPort: '56942''
,2017-07-21 07:57:02 - INFO testThaliMobileNative: ''
,ok 83 Must have listeningPort
,ok 84 listeningPort must be a number
,ok 85 listening port should not be 0
,# teardown
,2017-07-21 07:57:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 07:57:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 ,07:57:04 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-21 07:57:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:1DB06BF0-3361-4720-9B4B-E,8F6A5B37989
2017-07-21 07:57:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:57:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
,[ThaliCore] BrowserManager.disconnect peer:22B764CD-1CCE-4DBA-91F5-A067A3B0164D
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:56942
[ThaliCore] Session.disconnect() p,eer:22B764CD-1CCE-4DBA-91F5-A067A3B0164D:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:22B764CD-1CCE-4DBA-91F5-A067A3B0164D:0
[ThaliCore] BrowserRelay.deinit
,2017-07-21 07:57:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 07:57:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 07:57:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:57:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:57:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:57:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:57:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:57:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data
,[ThaliCore] Session.session(_:peer:didChange:) peer:862E2617-8FB6-4A3C-A4F3-3A422747726D state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "1DB06BF0-3361-4720-9B4B-E8F6A5B37989", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
,[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
,[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
,[ThaliCore] Session.disconnect() peer:16864A41-D630-45C1-B0AF-4E67A4AC8C31
,[ThaliCore] Session.session(_:peer:didChange:) peer:16864A41-D630-45C1-B0AF-4E67A4AC8C31 state: connected -> notConnected
[ThaliCore] AdvertiserRelay.deinit
[ThaliCore] Advertiser: session notConnected Peer(uuid: "1DB06BF0-3361-4720-9B4B-E8F6A5B37989", g,eneration: 0)
[ThaliCore] Session.deinit peer:16864A41-D630-45C1-B0AF-4E67A4AC8C31
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "387EC95F-5F42-4F46-A25B-FFFA6275C91A", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:387EC95F-5F42-4F46-A25B-FFFA6275C91A
2017-07-21 0,7:57:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 07:57:05 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 07:57:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 86 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:6B1FA896-089E-47F1-A059-7B78FA7385CA
[ThaliCore] Browser.startListening
,2017-07-21 07:57:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 07:57:05 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-21 07:57:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 87 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:22B764CD-1CCE-4DBA-91F5-A067A3B0164D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "22B764CD-1CCE-4DBA-91F5-A067A3B0164D", generation: 0)
2017-07-21 07:57:06 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"22B764CD-1CCE-4DBA-91F5-A067A3B0164D","generation":0}'
,2017-07-21 07:57:06 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 22B764CD-1CCE-4DBA-91F5-A067A3B0164D (syncValue: rWvEd1ELnt7n9inYNVqZ6ua3YkBNerQC)'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:26D99AE4-FD01-4D89,-8824-8246C4432DC5:0
2017-07-21 07:57:06 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "26D99AE4-FD01-4D89-8824-8246C4432DC5", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "22B764CD-1CCE-4DBA-91F5-A067A3B0164D", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "22B764CD-1CCE-4DBA-91F5-A067A3B0164D", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:22B764CD-1CCE-4DBA-91F5-A067A3B0164D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
2017-07-21 07:57:06 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"26D99AE4-FD01-4D89-8824-8246C4432DC5","generation":0}'
,2017-07-21 07:57:06 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 07:57:06 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3297E131-DDDB-48D9-8747-F6AA1CD08F8F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3297E131-DDDB-48D9-8747-F6AA1CD08F8F", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:44B8682C-03C2-4208-8FBD-AE9D3CBB179E:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "44B8682C-03C2-4208-8FBD-AE9D3CBB179E", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:387EC95F-5F42-4F46-A25B-FFFA6275C91A:0
[ThaliCore] BrowserManager.fo,undPeerHandler peer:Peer(uuid: "387EC95F-5F42-4F46-A25B-FFFA6275C91A", generation: 0)
2017-07-21 07:57:06 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"3297E131-DDDB-48D9-8747-F6AA1CD08F8F","generation":0}'
,2017-07-21 07:57:06 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 07:57:06 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 07:57:06 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 07:57:06 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,",peerIdentifier":"44B8682C-03C2-4208-8FBD-AE9D3CBB179E","generation":0}'
,2017-07-21 07:57:06 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 07:57:06 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 07:57:06 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 07:57:06 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:22B764CD-1CCE-4DBA-91F5-A067A3B0164D:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:22,B764CD-1CCE-4DBA-91F5-A067A3B0164D:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "22B764CD-1CCE-4DBA-91F5-A067A3B0164D", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2,2B764CD-1CCE-4DBA-91F5-A067A3B0164D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "22B764CD-1CCE-4DBA-91F5-A067A3B0164D", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:22B764CD-1CCE-4DBA-91F5-A067A3B0164D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:22B764CD-1CCE-4DBA-91F5-A067A3B0164D:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:26D99AE4-FD01-4D89-8824-8246C4432DC5:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "26D99AE4-FD01-4D89-8824-8246C4432DC5", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:22B764CD-1CCE-4DBA-91F5-A067A3B0164D:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:22,B764CD-1CCE-4DBA-91F5-A067A3B0164D:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "22B764CD-1CCE-4DBA-91F5-A067A3B0164D", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2,2B764CD-1CCE-4DBA-91F5-A067A3B0164D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "22B764CD-1CCE-4DBA-91F5-A067A3B0164D", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:22B764CD-1CCE-4DBA-91F5-A067A3B0164D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:22B764CD-1CCE-4DBA-91F5-A067A3B0164D:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:22B764CD-1CCE-4DBA-91F5-A067A3B0164D:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:22,B764CD-1CCE-4DBA-91F5-A067A3B0164D:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "22B764CD-1CCE-4DBA-91F5-A067A3B0164D", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2,2B764CD-1CCE-4DBA-91F5-A067A3B0164D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "22B764CD-1CCE-4DBA-91F5-A067A3B0164D", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:22B764CD-1CCE-4DBA-91F5-A067A3B0164D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:22B764CD-1CCE-4DBA-91F5-A067A3B0164D:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:22B764CD-1CCE-4DBA-91F5-A067A3B0164D:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:22,B764CD-1CCE-4DBA-91F5-A067A3B0164D:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "22B764CD-1CCE-4DBA-91F5-A067A3B0164D", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:22B764CD,-1CCE-4DBA-91F5-A067A3B0164D error: max retries exceeded
2017-07-21 07:57:17 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"rWvEd1ELnt7n9inYNVqZ6ua3YkBNerQC","error":"Connection could not be established","portNumber":null}'
2017-0,7-21 07:57:17 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'rWvEd1ELnt7n9inYNVqZ6ua3YkBNerQC', error: 'Connection could not be established', listeningPort: '%s''
2017-07-21 07:57:17 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"22B764CD-1CCE-4DBA-91F5-A067A3B0164D","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 07:57:17 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent, due to not being in started state'
2017-07-21 07:57:17 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"22B764CD-1CCE-4DBA-91F5-A067A3B0164D","peerAvailable":true,"portNumber":null,"recreated":true}'
20,17-07-21 07:57:17 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 07:57:17 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-21 07:57:17 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 3297E131-DDDB-48D9-8747-F6AA1CD08F8F (syncValue: qLRHpQ6,Ez5fm73YSS4pIPM0F0pEu7eSU)'
2017-07-21 07:57:17 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3297E131-DDDB-48D9-8747-F6AA1CD08F8F", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3297E131-DDDB-48D9-8747-F6AA1CD08F8F", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3297E131-DDDB,-48D9-8747-F6AA1CD08F8F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 07:57:17 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 07:57:17 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:22B764CD-1CCE-4DBA-91F5-A067A3B0164D:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:3297E131-DDDB-48D9-8747-F6AA1CD08F8F:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:3297E131-DDDB-48D9-8747-F6AA1CD08F8F:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:3297E131-DDDB-48D9-8747-F6AA1CD08F8F:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "3297E131-DDDB-48D9-8747-F6AA1CD08F8F", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:56958
2017-07-21 07:57:20 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"qLRHpQ6Ez5fm73YSS4pIPM0F0pEu7eSU",,"error":null,"portNumber":56958}'
2017-07-21 07:57:20 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'qLRHpQ6Ez5fm73YSS4pIPM0F0pEu7eSU', error: 'null', listeningPort: '56958''
,Connecting to the localhost:56958
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:3297E131-DDDB-48D9-8747-F6AA1CD08F8F:0
Connected to the localhost:56958
,2017-07-21 07:57:20 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-21 07:57:20 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3297E131-DDDB-48D9-8747-F6AA1CD08F8F:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1 [1]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 88 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pee,r})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams,() vsID:1
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:1
[ThaliCore] VirtualSocket.deinit vsID:1 []
,# teardown
,2017-07-21 07:57:27 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 07:57:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 ,07:57:27 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-21 07:57:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:387EC95F-5F42-4F46-A25B-F,FFA6275C91A
2017-07-21 07:57:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:57:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
,[ThaliCore] BrowserManager.disconnect peer:3297E131-DDDB-48D9-8747-F6AA1CD08F8F
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:56958
[ThaliCore] Session.disconnect() p,eer:3297E131-DDDB-48D9-8747-F6AA1CD08F8F:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:3297E131-DDDB-48D9-8747-F6AA1CD08F8F:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-21 07:57:27 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 07:57:27 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 07:57:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:57:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:57:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:57:27 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:57:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:57:27 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data via parallel connections
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C67E6215-DEE9-4444-A445-F329D8DE911F", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:C67E6215-DEE9-4444-A445-F329D8DE911F
2017-07-21 0,7:57:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 07:57:28 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 07:57:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 89 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:8E00E207-5950-4376-909C-85C20E020EAA
[ThaliCore] Browser.startListening
2017-07-21 07:57:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 07:57:28 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-21 07:57:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 90 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:22B764CD-1CCE-4DBA-91F5-A067A3B0164D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "22B764CD-1CCE-4DBA-91F5-A067A3B0164D", generation: 0)
2017-07-21 07:57:28 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"22B764CD-1CCE-4DBA-91F5-A067A3B0164D","generation":0}'
2017-07-21 07:57:28 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 22B764CD-1CCE-4DBA-91F5-A067A3B0164D, (syncValue: nxnF4E28CSQYfCZP1M2eWHujaKHho5FS)'
2017-07-21 07:57:28 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "22B764CD-1CCE-4DBA-91F5-A067A3B,0164D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "22B764CD-1CCE-4DBA-91F5-A067A3B0164D", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found ,peer:44B8682C-03C2-4208-8FBD-AE9D3CBB179E:0
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:22B764CD-1CCE-4DBA-91F5-A067A3B0164D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "44B8682C-03C2-4208-8FBD-AE9D3CBB179E,", generation: 0)
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-21 07:57:28 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailabl,e":true,"peerIdentifier":"44B8682C-03C2-4208-8FBD-AE9D3CBB179E","generation":0}'
2017-07-21 07:57:28 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 07:57:28 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:18629558-6C03-4C79-916D-F3DF313B891E:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "18629558-6C03-4C79-916D-F3DF313B891E", generation: 0)
,2017-07-21 07:57:29 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"18629558-6C03-4C79-916D-F3DF313B891E","generation":0}'
,2017-07-21 07:57:29 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 07:57:29 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 07:57:29 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:950874DD-50F5-4754-B6B8-316A63E92A54:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "950874DD-50F5-4754-B6B8-316A63E92A54", generation: 0)
,2017-07-21 07:57:29 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"950874DD-50F5-4754-B6B8-316A63E92A54","generation":0}'
,2017-07-21 07:57:29 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 07:57:29 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 07:57:29 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 07:57:29 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C67E6215-DEE9-4444-A445-F329D8DE911F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C67E6215-DEE9-4444-A445-F329D8DE911F", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:22B764CD-1CCE-4DBA-91F5-A067A3B0164D:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:22,B764CD-1CCE-4DBA-91F5-A067A3B0164D:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "22B764CD-1CCE-4DBA-91F5-A067A3B0164D", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2,2B764CD-1CCE-4DBA-91F5-A067A3B0164D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "22B764CD-1CCE-4DBA-91F5-A067A3B0164D", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:22B764CD-1CCE-4DBA-91F5-A067A3B0164D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:22B764CD-1CCE-4DBA-91F5-A067A3B0164D:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:22B764CD-1CCE-4DBA-91F5-A067A3B0164D:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:22,B764CD-1CCE-4DBA-91F5-A067A3B0164D:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "22B764CD-1CCE-4DBA-91F5-A067A3B0164D", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2,2B764CD-1CCE-4DBA-91F5-A067A3B0164D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "22B764CD-1CCE-4DBA-91F5-A067A3B0164D", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:22B764CD-1CCE-4DBA-91F5-A067A3B0164D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:22B764CD-1CCE-4DBA-91F5-A067A3B0164D:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:22B764CD-1CCE-4DBA-91F5-A067A3B0164D:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "22B764CD-1CCE-4DBA-91F5-A067A3B0164D", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:22B764CD-1CCE-4DBA-91F5-A067A3B0164D:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:22,B764CD-1CCE-4DBA-91F5-A067A3B0164D:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "22B764CD-1CCE-4DBA-91F5-A067A3B0164D", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2,2B764CD-1CCE-4DBA-91F5-A067A3B0164D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "22B764CD-1CCE-4DBA-91F5-A067A3B0164D", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 07:57:36 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"nxnF4E28CSQYfCZP1M2eWHujaKHho5FS","error":"Peer is unavailable",,"portNumber":null}'
2017-07-21 07:57:36 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'nxnF4E28CSQYfCZP1M2eWHujaKHho5FS', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-21 07:57:36 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"22B764CD-1CCE-4DBA-91F5-A067A3B0164D","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 07:57:36 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-21 07:57:36 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"22B764CD-1CCE-4DBA-91F5-A067A3B0164D","peerAvailable":true,"portNumber":null,"recreate,d,":true}'
,2017-07-21 07:57:36 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 07:57:36 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,2017-07-21 07:57:36 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 44B8682C-03C2-4208-8FBD-AE9D3CBB179E (syncValue: Bx5y4Minu9cEtzyirb0mSHeFGaPjUCtk)'
,2017-07-21 07:57:36 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "44B8682C-03C2-4208-8FBD-AE9D3CBB179E", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "44B8682C-03C2-4208-8FBD-AE9D3CBB179E", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:44B8682C-03C2-4208-8FBD-AE9D3CBB179E:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 07:57:36 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:22B764CD-1CCE-4DBA-91F5-A067A3B0164D:0
[ThaliCore] BrowserRelay.deinit
,2017-07-21 07:57:36 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:44B8682C-03C2-4208-8FBD-AE9D3CBB179E:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:44,B8682C-03C2-4208-8FBD-AE9D3CBB179E:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "44B8682C-03C2-4208-8FBD-AE9D3CBB179E", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,4B8682C-03C2-4208-8FBD-AE9D3CBB179E", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "44B8682C-03C2-4208-8FBD-AE9D3CBB179E", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:44B8682C-03C2-4208-8FBD-AE9D3CBB179E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:44B8682C-03C2-4208-8FBD-AE9D3CBB179E:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:44B8682C-03C2-4208-8FBD-AE9D3CBB179E:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:44,B8682C-03C2-4208-8FBD-AE9D3CBB179E:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "44B8682C-03C2-4208-8FBD-AE9D3CBB179E", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,4B8682C-03C2-4208-8FBD-AE9D3CBB179E", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "44B8682C-03C2-4208-8FBD-AE9D3CBB179E", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:44B8682C-03C2-4208-8FBD-AE9D3CBB179E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:44B8682C-03C2-4208-8FBD-AE9D3CBB179E:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:17A86F4E-6594-45A6-B9F9-195D16166C20
[ThaliCore] Advertiser: session connected Peer(uuid: "C67E6215-DEE9-4444-A445-F329D8DE911F", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:17A86F4E-6594-45A6-B9F9-195D16166C20 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:17A86F4E-6594-45A6-B9F9-195D16166C20
,[ThaliCore] Session.session(_:peer:didChange:) peer:17A86F4E-6594-45A6-B9F9-195D16166C20 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:17A86F4E-6594-45A6-B9F9-195D16166C20
[ThaliCore] Session.startOutputStream(with:) peer:17A86F4E-6594-45A6-B9F9-195D16166C20
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2 [2]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:44B8682C-03C2-4208-8FBD-AE9D3CBB179E:0 state: notConnected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:44B8682C-03C2-4208-8FBD-AE9D3CBB179E:0
,[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "44B8682C-03C2-4208-8FBD-AE9D3CBB179E", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "44B8682C-03C2-4208-8FBD-AE9D3CBB179E", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "44B8682C-03C2-4208-8FBD-AE9D3CBB179E", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:44B8682C-03C2-4208-8FBD-AE9D3CBB179E:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:17A86F4E-6594-45A6-B9F9-195D16166C20
,[ThaliCore] Session.startOutputStream(with:) peer:17A86F4E-6594-45A6-B9F9-195D16166C20
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3 [2, 3]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:17A86F4E-6594-45A6-B9F9-195D16166C20
[ThaliCore] Session.startOutputStream(with:) peer:17A86F4E-6594-45A6-B9F9-195D16166C20
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4, [2, 3, 4]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] Session.deinit peer:44B8682C-03C2-4208-8FBD-AE9D3CBB179E:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,2017-07-21 07:57:45 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:57:45 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:57:46 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:57:46 - DEBUG testThaliMobileNative: 'Server received (1024 bytes):'
,2017-07-21 07:57:46 - DEBUG testThaliMobileNative: 'Server received (71 bytes):'
,2017-07-21 07:57:46 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:57:46 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:57:46 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:57:46 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:57:47 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:57:47 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:44B8682C-03C2-4208-8FBD-AE9D3CBB179E:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "44B8682C-03C2-4208-8FBD-AE9D3CBB179E", generation: 0)
,2017-07-21 07:57:47 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:57:47 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:57:47 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:57:47 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:57:47 - DEBUG testThaliMobileNative: 'Server received (1054 bytes):'
2017-07-21 07:57:47 - DEBUG testThaliMobileNative: 'Server received all data: 71oCwCsvVrMtu371qkiY7xN52yyF8uNme6W0Ij5mAsHskXYo9pqwAbyFSLtqVMDnnRMvpqzUyE3SksuzbaiY4nyZtQWTDI,O5dZabVRX2OSLnBBLLgLs5cLwG9xawBlN2Tw0ebwR39bl8G59w9SpQ1Ys8EpC3qia9avw4IgQf6YX1jaxzFOASmSgvRIbNQgrQgPlJBIEG07wNenTKapYxy47MliSGGFEQfVCs1kDbZgTkUMBNp4n07mJ5I91QC16nFYTH6d3yBMFFFe3lpwUAUPu4DyOJM0ODFGm9DraIZhQlEESIFHmRcoHSH1eCFyoEZGuAxUleHQa2T5hN9wc8OOTkHZX8Jz,JSSTgEYemReixYJ0PIUfKYhavdHKLCx5MQ1wxOhuxFFAhvh5RJWEQvlij3yQwQN3PHX3iNJweP0X8aTtBKhsnbvr8gK4AoVyicnRV3Ao7JV4km7D8Hny5gsdmarDn3AKJIm5vJOry8vNg9lwUbMa2JzbjjZHC0tAGJcb2fH6asJBtiif7XW0Gy1b0CLlIgweNfvpiOb6yDO3OtTBpQPavieG6RV3uoRInDcrd1dLFOyYTxetrBMD2v8DdQeZ5lNT,WF80YP4Fnaq5vfli5l0cKFb0gzwB9r6V9tZc7XwxixxB6At8WEoRWAfnyrkf0IjglLxaaYXyyI9XzHeJCiI74KCqsbA8Sv4FYQzw70XcMGeJWIX0NREjHA0iD5j3Tg7Nx6JxEjFt6WiMZRTNBpK2t5VqgQsuyoa1FIePVtTVTThhxFrnk4VC1sJRFRE2HRiqExPMuLjxnBdi72j6ihQfZYki240qsrBpryB3rhhbYYuKvcm5kRABM7gpcv75hvT,7,78wcze54jJWl6cQM9mTr1EnSFC7sqXx7Fgisdwb2W6pygpskL8w2GUYQZbnQJY0cZD4vEbpluXI1JK3jCoOGRw7pxRXmwQPMN8vk5DEKkIjl4UDWSdC3ymfrH9kpTlEZ04TEsB4pVjt0aSuwoJ4s6OjnTvytwJzeV5BzAogt1ICA5nBUrUFtFjUyqeyZlYPnH8FpNp5Gl54q4pUmt8YDABrD4Rk2YUGruvc5xQmOPHqdqmFRpIWy714gKsJ7ggzX,JyvU66H4r58shFtefuwMe5awpA37p4OPlUj3uLccc8SusAG6mccs9oNj93pjcyOSoQgsvLj4fERT5wduqIZW3NEcvXMzYvOcvnY3lS6U81HRAMOJYKLQpRsImLBb96eQE6qknQsziT20MhR7lm6FN24gDVs8FtCxSQO3iT86NKFZwWsuXkUApk8qzrOeYnSMdmdWLCWYuecLFJvuniibkf1wpDymw1LTInpCblMhWaRgTPZNoXpsU4du5gWMl1kp,dHWneiplzwN38MUdMBrMGUFUAFMIBCq8BlsylpHtTFTSCy4IvJ1FeM4bjixmoRDbMNb0zZ0GILAQjlwjQZW7E0rC3x1BB3W46hbVDqdBtpsTg6mhySPMtD7HPtTQxcC0UT2EvZhz4ssIcjxXPiUJ6QoExnb9K9jl8KE1V1JpqAHzkWDsvmlEJZr591Ia8glaG5Qad3BQPi39ynt9lhKRN0q1pN14W1UNEYh7yz9Hw3zGNvPb2ipA378OB45TOSv7,ztzeNAqB22biWPmZUyZMHghRcZnjqqjnoKkxkV5G8qmNhdUm5sjdzOTrJ0EP6Mxr6QQ04CjBKaMgFoIoX4LrW8vSuE9JrOtuksm3bH3VLyo8mEEAFvNWONh2StKXIYKTfPwqtOWSb9Z41qgvVd4LAbIMIeaHx5a66v4sLrM1PvZ9vXB0tfaB8A06IzGF8zueHTuiYjbL1O3mqAUuWczK4HtCEtpfTZL9H4oTKK5y2cI9hFhRNaMblHGdykIeBoL,fGJRKIPTYxC3nZQZ4CdGaKj2DfqXZmpTJDUYRPDw5qsTyF0RwZAqSkPj3dl1qu8XYKsd9XbihYY0pKoVK0GSWlRmimp3HIlQDLmQVyOW9eKdWnlUSX17KMoUUX2hmvmGnREkPiVy2QmPk2PsSgLHJnwfzqnV9Rry39vaJZFGRgrQPEx2pO2RbKMGS4twG4zJH4IqynUWjxIQeXAucevZGEWoi30N05EQwLcjrRLovO5j4q31vr1VmDmKpnArMflp,hwm2NRTrMfzGi1eKyjpquFzFGfGGPnuX2KngxCveclrH8T1Pq7aNXhdQryHLEL21wqHSgA3uJQIh5s6hYbAtuWFwi38xVKFLvZ17OYC9oSvUB51yqyTcfR6vulxYfj3kCrlmFjrVtVn0iJAIn34vrljgIHOj9VR4FS2g0o1SAu0GqmE3xgn4ySuTlvopINYaAvevcLksAEGagKs46ZY985ID8m73XpKtrmEwIv8llOQYoGYCsWFM9sv7FKuMQ0IU,tq1SINUgfjRgIlQzLEG8qXMfTkybL54AEZJQe7ku07N6VUJND8SCGz9KjvtMCAH4NlVEUMrDVZP1xyJZplzvq0TSItYyfKjroFVXnpJoqZ3BmA8PZp4q5PK5F7559abAUiOgp02hgTw5DbffJ0E7L1aLUMyXXWdemCq3vK2OJAoUsDdf36QPrBJeDMz7b5sjqPiq5WHLNyl0hMpFjE2wqEOqrrXZshMBQa5HfNvrrgogjaP0nUdeMJVhkolnkxEU,EP0f4aL6xHoXmL8PczdRumkxgAGtztwWRP7BTOS8NEsZA8jXety9ay4haieLk4lyJaBjLBXwOBB8JjXoo6a7IyXyfedbslASarljpqhiPlcfYKQWIgeflxXYW5EfDRHwt7kk6VFCVNO0sRkByVvUDyfrcFU8T6Ezpo8zCfTVulWcZz7aBhNz5dBMhZmaiya0zTvXGhymg044ezNHfU9ebtO60Y3TiNNGlnYpKBOMM5vqmbpZCT01TEuqIpDIJ17,2,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,b,IYRIRH2qvFRKIKHASC4kmlM5HznwVbWfRx9sz2wt0s1efkcYipIex2vQNYBzIgvYFktwVHdXWSqc6HW1gOGkgpr4ofoWkxApQFTs6l1Lu2ARKjFBShjXBrGplp4E3w30KKVl0kOYBzlTnnIRFkDlXM7NiKfCB4IoHcI4qzYkJnvn24YYcYds3OGat9jqWv66VYc6lHTwdzUN6O5OPBc21uuqBeyhh0Idqee4zAlUHCnsRG19pqYQUlbAo19myJPo,lWsYr8jtiDvZC3p7dxDBdkOXJs6IZJcczVFxdXd4X3oCok3TqxsuTswsC3e2ESpxzsqgmzEjjErb3msWWTMvYnI96kCLfpl37A4ywn46ECuyVmhlW45D1o7vO0mVFnnF0dF1uB50LFGHxFygphtYbVQjGey8nSgI621l7e69rCaWiGChkfDLGHpsRoPoF6AOJtEXk5UIf6qEGk7OVBQ62CMRDeZzr23BoLqxLBatmUcfV1UP4aEVtayQa6AE6afF,5A1XGBMcmnyJnnmGZUCeMY75WX0aBMic9mpJ4r80qLf2Bt63NenT19El69PqbcaXAefIJiXlHcg6YJHSsNyrPiKiJuTe9CZ0u6ti8Q4359T8cmE1AgFfPP2tRk8Nlo5kglv1JYwzEPkyv9pFNZ0zilTTl20qeCqwH9rR5eMfVRqLXpAybqFFtmwaDfQVBFMmRKn5d0pTBH945sm3z80XL8QINUdbvTZFYtAnDbwxUXRHlJ2k7QodzdppsIVyXqFw,ZBAoiMWd2v5vezTYLUBrYthdnRe6TL6o0LIHq0inFr8W8cRvSSIq2IT9g5hHOxjBpwj8JCmVKOdh442t6TUnloG68Kuw43U5RHgcIj7rqp9fMo9fq4g8m1BQUCBWnJpy9EdC5jjdqIE73yUFEc9TiU47kFrxxoZ58Rsb4r38pPXmvjyO3j3cWyJvNWWgfKWUgPO2yaZ7l3RwwmdrDBptooqXWFM0BhADRKs2B7WXlCEjgWJfUsmezzEf3ObAKP0,c[ThaliCore] Session.session(_:peer:didChange:) peer:44B8682C-03C2-4208-8FBD-AE9D3CBB179E:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:44B8682C-03C2-4208-8FBD-AE9D3CBB179E:0
,[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "44B8682C-03C2-4208-8FBD-AE9D3CBB179E", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:44B8682C-03C2-4208-8FBD-AE9D3CBB179E error: ma,x retries exceeded
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'
2017-07-21 07:57:47 - DEBUG testThaliMobileNative: 'Server sends data, back to client (16384 bytes):'
2017-07-21 07:57:47 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-21 07:57:47 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Bx5y4Minu9cEtzyirb0mSHeFGaPjUCtk","error":"Connection could not be established","portNumber":null}'
2017-07-21 07:57:47 - DEBUG thaliMobileNativeTestUtils: 'Got mul,tiConnectResolved -syncValue: 'Bx5y4Minu9cEtzyirb0mSHeFGaPjUCtk', error: 'Connection could not be established', listeningPort: '%s''
2017-07-21 07:57:47 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"44,B8682C-03C2-4208-8FBD-AE9D3CBB179E","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 07:57:47 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 07:57:47 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"44B8682C-03C2-4208-8FBD-AE9D3CBB179E","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-21 07:57:47 - DEBUG thaliMobile,NativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 07:57:47 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-21 07:57:47 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 18629558-6C03-4C79-916D-F3DF313B891E (syncValue: gu7LIKMyNZkqgbwKo5kJQd6fkIGosHIl)'
,2017-07-21 07:57:47 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "18629558-6C03-4C79-916D-F3DF313B891E", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "18,629558-6C03-4C79-916D-F3DF313B891E", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:18629558-6C03-4C79-916D-F3DF313B891E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
2017-07-21 07:57:47 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 07:57:47 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:44B8682C-03C2-4208-8FBD-AE9D3CBB179E:0
[ThaliCore] BrowserRelay.deinit
,2017-07-21 07:57:48 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,[ThaliCore] Session.session(_:peer:didChange:) peer:18629558-6C03-4C79-916D-F3DF313B891E:0 state: notConnected -> connecting
,2017-07-21 07:57:48 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:57:48 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:57:48 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:57:48 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:57:49 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:57:49 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:57:49 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:57:49 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:57:49 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:57:49 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:57:50 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:57:50 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:57:50 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:57:50 - DEBUG testThaliMobileNative: 'Server received (1054 bytes):'
,2017-07-21 07:57:50 - DEBUG testThaliMobileNative: 'Server received all data: rKAHx4CHb1ZsWckdRUUWVAqbbxvOS26UaEUFLxLQiGJ8qfpAaVk2YRq6ZRccM6neBtPbaBbW02sIhOktZ2JR93r6sMKvisbl6vV47oVVQFs6IW4AueVt3vNLIMrsevXbOQatOre3p6SS81M6BhRJGnpz0WjaZ140901A7VWLr9KcyUHi5G,ZmWQNYjIWcGnmNjDWQVUBrWfDiVcCsSrGezVPn3hbst3KtR8WJVeAAFxDkZkl1Kv3VsomkLcihVP8pA6xht5fIc7gIrB1FJ9wUHJ8hVZb0YUtoiATis88slIHvYcZOgJRHdD8ZjXyKUydyWs70Bwxr4O1wcYdh1aYCM8RlOHhCVINNG1LECKB2tAHbqowFqezUncD6Nztu4Bez1h2oB8nbeXJpF41uVSkqyaLOEV7wNEwiFQuuBABYjzpGXWlBhs,eiZ9gHcCBKVvkbZrLLhsn7Ex3JmP2U2jwVv2dQep5Oqxtu9hO0kSMhoWbbQFfalCBFchoH3uLpcPxwMqPk8gMFrv7Av8PgnFsKRnCASMKoXKPRR5gbMMMzelPvbbFMqnomHIZUo0A4yI1Cw6LGA6DAfkv5kVlQqz93yYTuxtd6WOTXwIN3PiCFyTziXPccFuZJ6AI2xbntqFxMSAJctT2kUQOlN6hBCOnctScWvHC1N2JabAbB0ZhmpvN7PnrThG,eixznO7eAGPLRZEFeMoCBAdSPhacur8IBhRN0kRJ2hAtIATHLI61JOTbDqd1NVHwPbUMhYaSXloNv3nNj987O704nNAKl91OfdIvUQKgpyO9keYzSRe5SaNsqU8wjkgQOvCh9wPcxv5i1HuwePF9KvWzmJENculLs6kik24yQpH4efmo7aRr7xvkf8EA6y0Bost1q4ig8ioJbhe5vTEW40txBGBEvNAgAUHkKNauyWkf3r54bK4F02NOMPpITbM,t,XwTDtI4ewkIj9nIr9h0fcwmxElM9zfkYdWmwbaxusEB1YsJhto1hepRWyfmeyNvFdA4sylToUKZgbmt934eCiPXADbZjIS9scz6fKvb9UKNh8xpFhHkCvO4ZlesBdHBKugyWOgyMVslCnZXpjdzXKqmJKenSGmwXkQbJVCodRSbOGrCaCgRnTKF6b0HoWtP71DNJvgP3OsQJ1b1blr2WcjkC2CFMR8cPCaav43bY9Z7wAqMLTzqkf8LjdJKEcx0B,Ev2nL87jihJiLYuHJNYz1Ay1Q4MqPDxmec1kCuA99VTThw1MUmIMhLheO6uHZpgOuy3kUF3MotiJRwcnhsxIVQzmnXRhcSoyDn3ABHd8rQ9GphHwsz5RnqJUc66wum72VwGcuAUrSMRrFBZXdDQ2BkrlMindqs139GaM0FPxxo8q2KdmlNv26POLmM807UmGzVqfqRK7cEQHjibsigYVoM8f9Zeok8Lf1NysbR1UzPOxMyS7upnD2xJUxHmLQPew,OKoeyZFwlzd1x41fQsDA8K5yhiKD58GqrTQCsTnqfHu0xuyE31skOlQhnig63r8J8L3jU8uadw7Cmtw95Gj5DvfU2fg2dYVCKQhp115AeCk0D4FLOCICDQdgmTKPs3xl1He1d8eKzYjtXvpZXx9MJF96lADhXWj1Q3fdB2YZgLbVkiDArqmISWxd5NSvoeV82vzVvTy7EYtKawwWUiZJOm4CeXqAmkSbSN4a6uMtdBwsEfFwS35UnAGsibf0QPFZ,u03qa0eueNH7K5NTbC3UmvN01DblJdg2jFwAMPJWf1v5cIpl53qNqr7AKPtqD2V03CZiKFZalwVbjvnquNpEuC8PZ30arYAezwMLg3gCa8LZV0J0F7EObaB3ABcTLIjDf3Bhb1e08zt8OwV4HjvYsNj2MwTziu8I1roFdazXITGRi3OdaMDGb0jPA3Ajir0Oz5YTUUckjEPvpOv1JE5NriJJPAyyu8fCrf5pdhe36xpQz4NTjfJQY6Wf1IiojzG,8,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,b,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'
2017-07-21 07:57:50 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-21 07:57:50 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-21 07:57:50 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:57:50 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:57:51 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:18629558-6C03-4C79-916D-F3DF313B891E:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:18629558-6C03-4C79-916D-F3DF313B891E:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "18629558-6C03-4C79-916D-F3DF313B891E", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:56981
2017-07-21 07:57:51 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"gu7LIKMyNZkqgbwKo5kJQd6fkIGosHIl",,"error":null,"portNumber":56981}'
2017-07-21 07:57:51 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'gu7LIKMyNZkqgbwKo5kJQd6fkIGosHIl', error: 'null', listeningPort: '56981''
,Connecting to the localhost:56981
Connecting to the localhost:56981
Connecting to the localhost:56981
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:,) peer:18629558-6C03-4C79-916D-F3DF313B891E:0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:18629558-6C03-4C79-916D-F3DF313B891E:0
[ThaliCore], TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:18629558-6C03-4C79-916D-F3DF313B891E:0
,Connected to the localhost:56981
,Connected to the localhost:56981
Connected to the localhost:56981
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:18629558-6C03-4C79-916D-F3DF313B891E:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5 [2, 3, 4, 5]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:18629558-6C03-4C79-916D-F3DF313B891E:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6 [2, 3, 4, 5, 6]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:18629558-6C03-4C79-916D-F3DF313B891E:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7 [2, 3, 4, 5, 6, 7]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 91 correct string length
,2017-07-21 07:57:51 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 92 correct string length
,2017-07-21 07:57:51 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 93 correct string length
,2017-07-21 07:57:51 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,2017-07-21 07:57:51 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-21 07:57:51 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-21 07:57:51 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-21 07:57:51 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:5
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:5
[ThaliCore] VirtualSocket.deinit vsID:5 [2, 3, 4, 6, 7]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vs,ID:6
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:6
[ThaliCore] VirtualSocket.deinit vsID:6 [2, 3, 4, 7]
,ok 94 got the same data back
,ok 95 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vs,ID:7
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:7
[ThaliCore] VirtualSocket.deinit vsID:7 [2, 3, 4]
,ok 96 got the same data back
,# teardown
,2017-07-21 07:57:51 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:57:51 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:57:52 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:57:52 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:57:52 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:57:52 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:57:53 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:57:53 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:57:53 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:2
[ThaliCore] VirtualSocket.closeStreams() vsID:2
2017-07-21 07:57:54 - DEBUG testThaliMobileNative: 'Server received (1024 bytes):'
[ThaliCore] AdvertiserRelay.didCloseVirtualSocket,StreamsHandler disconnecting:false
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:3
[ThaliCore] VirtualSocket.closeStreams() vsID:3
[ThaliCore] VirtualSocket exited RunLoop vsID:2
[ThaliCore] VirtualSocket.deinit vsID:2 [3, 4]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-21 07:57:54 - DEBUG testThaliMobileNative: 'Server received (30 bytes):'
2017-07-21 07:57:54 - DEBUG testThaliMobileNative: 'Server received all data: t7X884RdKC0wZtZbpzOuzWrLakKaGNlHoubZNSDQMB28d3xC3iOZTsnoWmej9zixjBcN0mOaMtGhLLukSuh9wjJ4CW6iUEYh,tgJJAN0yNuWn07rsDzQFiFvw6n3h7OLt5GZblGdsbljzamDTTSSyJm1s0LeavAnjJ4iypuA3BNKz9TjOo8NlK9bxUGqrf9kTIFbwXr4zxGnpo1NLuo3yjeX1Zsv49Ld1LTv6JvNNutqUsFhqx0lKNCwL9Pjia4X71hjhdfptAZXBcoYKB6zxD5FmHjy3eGyowzCkPSFPbnXUZf56H9eX02NpS3bONugHeKKvoqoReIh67UbJG5sttnaSHqJZM6tQ,zatcoCRG8p8pD1BqPJTFsJyUiLIF6qjw7neK7gxMUOyCGyS46JcK2shUV1564ogHLw5ouh2XfMrJSBkQWPZWFYafJEMEZZVQ0oQthiTAgryvla4eQ6ney9TU7vM3n4Mwsjz4YFF3QVGFzZodBzrgI9eQibZmyh0okZf470D9sv7KyWngwcOdCodI2pppPPLzQpFuXuE03xX92YsDnamfTSrUvqosaanzLQUBOcpL0L5lB2EbKNzkzQv5AhXXRmUN,XmHK9qb9P5PjDeGK5uI7C9Z1XtnPzHYslzwwgcKf8pV8YupCAPy0ferftgBUy68vIQwpteQMZtjv3QRM9zoqax7T8FO6r90uQ7BLwobz9j5BCLvkrI5Nsm2dKKxcPCnqMr0zqSqy9hGlkVb3YtKMhkEvE9iBz2bLHBNcusXol45zZSygSnfOh4Jl9YYX8hWU0tuejs85yMSbNn99fMD1gEXmVZXbeyxZM6bYFbhklK6AUzQrqHzJKF13YUa0pOdY,ZJLL3XqIUnmCDyVqgKUTkKqKDbiVyRRcbjblSLa4zl0wkLc6BQ6HoAZQNYYVbo4TceJaHuHK5tXqt3yMgK5aZwHsx4AmTiLpIMsAuOaUSXWoWENh4Gk0kKnCiNvFDlozKIfeWQPsoFt6UKZcFDy4mbmPOQfVBonmpOwxI77gAIRyTuLea1iz8iXqPorlDLoCbTxh1CESJrMvatbXkHz8qJE0pjIxtwloc3nTWgi22ThLG9f8nGbq3ukptHdB1yoj,UxEEGryHZuLITt91RBiZoYR7I3XDyVahPss12hOGP1UBTd7n5jzkKvPfqZf0P5Mw1ubna6Z0Y7rmY9mzmkjLNmdY2256wBQLgh33fIWSOsyjFtRU8rSl6FEObDCXXjRmU1mxye5WrWapkrhcUXJm53HImukkCWQNgWxKDduTajcICnCHXuc5Sz99OHU5NFyzxTUUmqg4Xq9u2SsDEYBqRCWPn5OrSGbyBAsKzln2znKAxM7lq3dHBGpzFSEZlPc5,ym30OkXmP9IvBvFVc6bhIjXqvJpxVHzc0OZm20912KjmhQerh9m16IWUSxCxS2T2q4RYaQpDmODdnhzmTwue8DEblkTBTGaxPzGXhH03TQ4bWzCsIdgifYGhm8zWSjIxg6HPlVjvyxeomSJcgOsUVObaOSA2EHEiLvwzRlnTfjktABfWPuVhcR1hfAftyT9hsrNTV8MjzRW4LSW8xeJpZHUYMF6JCCgXLhn9lFne7NUQF70shB6NY6HmZ0j7o6qE,EJZGvpYHQdGfllCWOEyFptzHpJTktwRIgiHra9O4n7Ilg7PebBJHSTBMEQWkM4vop3uhWDOIQFS4sPiAiBhkGcWQTv6d5CGIh6TmLBmPoUoLs2bPSiGzTglqaY8QMo1ucNAYJtfaqnm8eCQntmcsUvdldu5xsEaWEDV8brADcRZF6DHlX5fIsOK5At9y0IhNbrzA9UWHcWvmajf2oFAxCdY9z3ydIdzWHGK76Q8nRpwAmFusF4gXHJzygNggMhj[,ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
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'
2017-07-,21 07:57:54 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-07-21 07:57:54 - DEBUG testThaliMobileNative: 'Server data flushed'
[ThaliCore] VirtualSocket exited RunLoop vsID:3
[ThaliCore] TCPClient.socketDidDisconne,ct(_:withError:) disconnecting:false socket error:nil
[ThaliCore] VirtualSocket.deinit vsID:3 [4]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:4
,[ThaliCore] VirtualSocket.closeStreams() vsID:4
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:4
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] VirtualSocket.deinit vsID:4 []
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-21 07:57:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 07:57:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 07:57:54 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 07:57:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:C67E6215-DEE9-4444-A445-F329D8DE911F
2017-07-2,1 07:57:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:57:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:18629558-6C03-4C79-916D-F3DF313B891E
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:56981
[ThaliCore] Session.disconnect() p,eer:18629558-6C03-4C79-916D-F3DF313B891E:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:17A86F4E-6594-45A6-B9F9-195D16166C20 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "C67E6215-DEE9-4444-A445-F329D8DE911F", generation: 0)
,[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:17A86F4E-6594-45A6-B9F9-195D16166C2,0
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:18629558-6C03-4C79-916D-F3DF313B891E:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-21 07:57:54 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 07:57:54 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 07:57:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:57:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:57:54 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:57:54 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
[ThaliCore] Session.deinit peer:17A86F4E-6594-45A6-B9F9-195D16166C20
,2017-07-21 07:57:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:57:54 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data securely
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "9DB02CB4-9A8D-4C90-9B9F-22F0835DE8FB", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:9DB02CB4-9A8D-4C90-9B9F-22F0835DE8FB
,2017-07-21 07:57:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 07:57:56 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 07:57:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 97 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:9E590909-86C7-473F-832E-5B73F900B018
[ThaliCore] Browser.startListening
,2017-07-21 07:57:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 07:57:56 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 07:57:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 98 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:18629558-6C03-4C79-916D-F3DF313B891E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "18629558-6C03-4C79-916D-F3DF313B891E", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:950874DD-50F5-4754-B6B8-316A63E92A54:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "950874DD-50F5-4754-B6B8-316A63E92A54", generation: 0)
2017-07-21 07:57:56 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"18629558-6C03-4C79-916D-F3DF313B891E","generation":0}'
2017-07-21 07:57:56 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 18629558-6C03-4C79-916D-F3DF313B891E (syncValue: HaDZldDhH73bfrUDhYfLxycYy4m3EGVk)'
,2017-07-21 07:57:56 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "18629558-6C03-4C79-916D-F3DF313B891E", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "18629558-6C03-4C79-916D-F3DF313B891E", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:18629558-6C03-4C79-916D-F3DF313B891E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,2017-07-21 07:57:56 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"950874DD-50F5-4754-B6B8-316A63E92A54","generation":0}'
,2017-07-21 07:57:56 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 07:57:56 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B84EE5A7-220B-4B6A-9E36-00A6615627EF:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B84EE5A7-220B-4B6A-9E36-00A6615627EF", generation: 0)
,2017-07-21 07:57:57 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B84EE5A7-220B-4B6A-9E36-00A6615627EF","generation":0}'
,2017-07-21 07:57:57 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 07:57:57 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 07:57:57 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9DB02CB4-9A8D-4C90-9B9F-22F0835DE8FB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9DB02CB4-9A8D-4C90-9B9F-22F0835DE8FB", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:25BA6BBB-1122-4518-BE28-A26BE6496CE8:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "25BA6BBB-1122-4518-BE28-A26BE6496CE8", generation: 0)
2017-07-21 07:57:57 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"25BA6BBB-1122-4518-BE28-A26BE6496CE8","generation":0}'
2017-07-21 07:57:57 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 07:57:57 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-21 07:57:57 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 07:57:57 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:18629558-6C03-4C79-916D-F3DF313B891E:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:18,629558-6C03-4C79-916D-F3DF313B891E:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "18629558-6C03-4C79-916D-F3DF313B891E", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1,8629558-6C03-4C79-916D-F3DF313B891E", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "18629558-6C03-4C79-916D-F3DF313B891E", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:18629558-6C03-4C79-916D-F3DF313B891E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:18629558-6C03-4C79-916D-F3DF313B891E:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:18629558-6C03-4C79-916D-F3DF313B891E:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:18,629558-6C03-4C79-916D-F3DF313B891E:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "18629558-6C03-4C79-916D-F3DF313B891E", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1,8629558-6C03-4C79-916D-F3DF313B891E", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "18629558-6C03-4C79-916D-F3DF313B891E", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:18629558-6C03-4C79-916D-F3DF313B891E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:18629558-6C03-4C79-916D-F3DF313B891E:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:950874DD-50F5-4754-B6B8-316A63E92A54:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "950874DD-50F5-4754-B6B8-316A63E92A54", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:18629558-6C03-4C79-916D-F3DF313B891E:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:18,629558-6C03-4C79-916D-F3DF313B891E:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "18629558-6C03-4C79-916D-F3DF313B891E", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1,8629558-6C03-4C79-916D-F3DF313B891E", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "18629558-6C03-4C79-916D-F3DF313B891E", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:18629558-6C03-4C79-916D-F3DF313B891E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:18629558-6C03-4C79-916D-F3DF313B891E:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:18629558-6C03-4C79-916D-F3DF313B891E:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:18,629558-6C03-4C79-916D-F3DF313B891E:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "18629558-6C03-4C79-916D-F3DF313B891E", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:18629558,-6C03-4C79-916D-F3DF313B891E error: max retries exceeded
2017-07-21 07:58:07 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"HaDZldDhH73bfrUDhYfLxycYy4m3EGVk","error":"Connection could not be established","portNumber":null}'
2017-0,7-21 07:58:07 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'HaDZldDhH73bfrUDhYfLxycYy4m3EGVk', error: 'Connection could not be established', listeningPort: '%s''
2017-07-21 07:58:07 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"18629558-6C03-4C79-916D-F3DF313B891E","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 07:58:07 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent, due to not being in started state'
2017-07-21 07:58:07 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"18629558-6C03-4C79-916D-F3DF313B891E","peerAvailable":true,"portNumber":null,"recreated":true}'
20,17-07-21 07:58:07 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 07:58:07 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-21 07:58:07 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B84EE5A7-220B-4B6A-9E36-00A6615627EF (syncValue: KwsH0JV,F04pWs3v3K3GhepoU0IMpAE9T)'
2017-07-21 07:58:07 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B84EE5A7-220B-4B6A-9E36-00A6615627EF", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B84EE5A7-220B-4B6A-9E36-00A6615627EF", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B84EE5A7-220B,-4B6A-9E36-00A6615627EF:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 07:58:07 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 07:58:07 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:18629558-6C03-4C79-916D-F3DF313B891E:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:57A5A079-6D1E-476E-9F1D-C726B6B16C4F
[ThaliCore] Advertiser: session connected Peer(uuid: "9DB02CB4-9A8D-4C90-9B9F-22F0835DE8FB", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:57A5A079-6D1E-476E-9F1D-C726B6B16C4F state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:B84EE5A7-220B-4B6A-9E36-00A6615627EF:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B84EE5A7-220B-4B6A-9E36-00A6615627EF:0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:57A5A079-6D1E-476E-9F1D-C726B6B16C4F
,[ThaliCore] Session.session(_:peer:didChange:) peer:B84EE5A7-220B-4B6A-9E36-00A6615627EF:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "B84EE5A7-220B-4B6A-9E36-00A6615627EF", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:56998
,2017-07-21 07:58:10 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"KwsH0JVF04pWs3v3K3GhepoU0IMpAE9T","error":null,"portNumber":56998}'
2017-07-21 07:58:10 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'KwsH0JVF04pWs3v3K3GhepoU0IMpAE9T', error: 'null', listeningPort: '56998''
,Connecting to the localhost:56998
,[ThaliCore] Session.session(_:peer:didChange:) peer:57A5A079-6D1E-476E-9F1D-C726B6B16C4F state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:57A5A079-6D1E-476E-9F1D-C726B6B16C4F
[ThaliCore] Session.startOutputStream(with:) peer:57A5A079-6D1E-476E-9F1D-C726B6B16C4F
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8 [8]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B84EE5A7-220B-4B6A-9E36-00A6615627EF:0
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B84EE5A7-220B-4B6A-9E36-00A6615627EF:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9 [8, 9]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,Server received psk id: psk-id
,Connected to the localhost:56998
,2017-07-21 07:58:10 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-21 07:58:10 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-21 07:58:10 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-07-21 07:58:10 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-21 07:58:10 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes): '
,2017-07-21 07:58:10 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-21 07:58:10 - DEBUG testThaliMobileNative: 'Server's socket stream finished'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:9
[ThaliCore] VirtualSocket.closeStreams() vsID:9
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" Use,rInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:8
[ThaliCore] VirtualSocket.closeStreams() vsID:8
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] VirtualSocket exited RunLoop vsID:9
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisco,nnectHandler
[ThaliCore] VirtualSocket.deinit vsID:9 [8]
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:8
[ThaliCore] VirtualSocket.deinit vsID:8 []
,ok 99 got the same data back
,# teardown
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:18629558-6C03-4C79-916D-F3DF313B891E:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "18629558-6C03-4C79-916D-F3DF313B891E", generation: 0)
,2017-07-21 07:58:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 07:58:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 07:58:16 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 07:58:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:9DB02CB4-9A8D-4C90-9B9F-22F0835DE8FB
2017-07-21 07:58:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07,:58:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:B84EE5A7-220B-4B6A-9E36-00A6615627EF
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:56998
[ThaliCore] Session.disconnect() p,eer:B84EE5A7-220B-4B6A-9E36-00A6615627EF:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:57A5A079-6D1E-476E-9F1D-C726B6B16C4F state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "9DB02CB4-9A8D-4C90-9B9F-22F0835DE8FB", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:57A5A079-6D1E-476E-9F1D-C726B6B16C4F
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:B84EE5A7-220B-4B6A-9E36-00A6615627EF:0
[ThaliCore] BrowserRelay.deinit
,2017-07-21 07:58:16 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 07:58:16 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 07:58:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:58:16 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:58:16 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:58:16 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:58:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:58:16 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.deinit peer:57A5A079-6D1E-476E-9F1D-C726B6B16C4F
,# Can shift large amounts of data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "68CF2D20-4470-42C1-86DD-5C4B66AE0A9A", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:68CF2D20-4470-42C1-86DD-5C4B66AE0A9A
,2017-07-21 07:58:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-21 07:58:18 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 07:58:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 100 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:40106DE9-C5FF-46AB-9B53-46CA9B93576D
,[ThaliCore] Browser.startListening
,2017-07-21 07:58:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 07:58:18 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:25BA6BBB-1122-4518-BE28-A26BE6496CE8:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "25BA6BBB-1122-4518-BE28-A26BE6496CE8", generation: 0)
,2017-07-21 07:58:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 101 Can call startListeningForAdvertisements without error
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B84EE5A7-220B-4B6A-9E36-00A6615627EF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B84EE5A7-220B-4B6A-9E,36-00A6615627EF", generation: 0)
2017-07-21 07:58:18 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"25BA6BBB-1122-4518-BE28-A26BE6496CE8","generation":0}'
,2017-07-21 07:58:18 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 25BA6BBB-1122-4518-BE28-A26BE6496CE8 (syncValue: 174jxmkxTaEffdz6kOzgu9HhX2f40wVX)'
,2017-07-21 07:58:18 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "25BA6BBB-1122-4518-BE28-A26BE6496CE8", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "25BA6BBB-1122-4518-BE28-A26BE6496CE8", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:25BA6BBB-1122-4518-BE28-A26BE6496CE8:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 07:58:18 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B84EE5A7-220B-4B6A-9E36-00A6615627EF","generation":0}'
,2017-07-21 07:58:18 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 07:58:18 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0484139D-6BA0-4F9E-B15D-5ACBCFFF6C4C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0484139D-6BA0-4F9E-B15D-5ACBCFFF6C4C", generation: 0)
2017-07-21 07:58:18 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"0484139D-6BA0-4F9E-B15D-5ACBCFFF6C4C","generation":0}'
2017-07-21 07:58:18 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 07:58:18 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-21 07:58:18 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:68CF2D20-4470-42C1-86DD-5C4B66AE0A9A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "68CF2D20-4470-42C1-86DD-5C4B66AE0A9A", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:45972DD7-E306-4909-AA0D-0C667C726D62:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "45972DD7-E306-4909-AA0D-0C667C726D62", generation: 0)
2017-07-21 07:58:19 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"45972DD7-E306-4909-AA0D-0C667C726D62","generation":0}'
2017-07-21 07:58:19 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 07:58:19 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 07:58:19 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 07:58:19 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:B84EE5A7-220B-4B6A-9E36-00A6615627EF:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "B84EE5A7-220B-4B6A-9E36-00A6615627EF", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:25BA6BBB-1122-4518-BE28-A26BE6496CE8:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:25,BA6BBB-1122-4518-BE28-A26BE6496CE8:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "25BA6BBB-1122-4518-BE28-A26BE6496CE8", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2,5BA6BBB-1122-4518-BE28-A26BE6496CE8", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "25BA6BBB-1122-4518-BE28-A26BE6496CE8", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:25BA6BBB-1122-4518-BE28-A26BE6496CE8:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:25BA6BBB-1122-4518-BE28-A26BE6496CE8:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:25BA6BBB-1122-4518-BE28-A26BE6496CE8:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:25,BA6BBB-1122-4518-BE28-A26BE6496CE8:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "25BA6BBB-1122-4518-BE28-A26BE6496CE8", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2,5BA6BBB-1122-4518-BE28-A26BE6496CE8", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "25BA6BBB-1122-4518-BE28-A26BE6496CE8", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:25BA6BBB-1122-4518-BE28-A26BE6496CE8:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:25BA6BBB-1122-4518-BE28-A26BE6496CE8:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:25BA6BBB-1122-4518-BE28-A26BE6496CE8:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:25,BA6BBB-1122-4518-BE28-A26BE6496CE8:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "25BA6BBB-1122-4518-BE28-A26BE6496CE8", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2,5BA6BBB-1122-4518-BE28-A26BE6496CE8", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "25BA6BBB-1122-4518-BE28-A26BE6496CE8", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:25BA6BBB-1122-4518-BE28-A26BE6496CE8:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:25BA6BBB-1122-4518-BE28-A26BE6496CE8:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:25BA6BBB-1122-4518-BE28-A26BE6496CE8:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:25,BA6BBB-1122-4518-BE28-A26BE6496CE8:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "25BA6BBB-1122-4518-BE28-A26BE6496CE8", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:25BA6BBB,-1122-4518-BE28-A26BE6496CE8 error: max retries exceeded
2017-07-21 07:58:29 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"174jxmkxTaEffdz6kOzgu9HhX2f40wVX","error":"Connection could not be established","portNumber":null}'
2017-0,7-21 07:58:29 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '174jxmkxTaEffdz6kOzgu9HhX2f40wVX', error: 'Connection could not be established', listeningPort: '%s''
2017-07-21 07:58:29 - DEBUG thaliMobileNativeWrapper: 'Received, peer availability changed event with {"peerIdentifier":"25BA6BBB-1122-4518-BE28-A26BE6496CE8","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 07:58:29 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEven,t due to not being in started state'
2017-07-21 07:58:29 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"25BA6BBB-1122-4518-BE28-A26BE6496CE8","peerAvailable":true,"portNumber":null,"recreated":true}'
2,017-07-21 07:58:29 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 07:58:29 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-21 07:58:29 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 0484139D-6BA0-4F9E-B15D-5ACBCFFF6C4C (syncValue: obueRwC,umY3TjqgkjJ3ffYr2tx0KRaYh)'
2017-07-21 07:58:29 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0484139D-6BA0-4F9E-B15D-5ACBCFFF6C4C", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "0484139D-6BA0-4F9E-B15D-5ACBCFFF6C4C", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:0484139D-6BA0-4F9E-B15D-5ACBCFFF6C4C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 07:58:29 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 07:58:29 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:25BA6BBB-1122-4518-BE28-A26BE6496CE8:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:25BA6BBB-1122-4518-BE28-A26BE6496CE8:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "25BA6BBB-1122-4518-BE28-A26BE6496CE8", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:0484139D-6BA0-4F9E-B15D-5ACBCFFF6C4C:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:0484139D-6BA0-4F9E-B15D-5ACBCFFF6C4C:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:0484139D-6BA0-4F9E-B15D-5ACBCFFF6C4C:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "0484139D-6BA0-4F9E-B15D-5ACBCFFF6C4C", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57015
2017-07-21 07:58:32 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"obueRwCumY3TjqgkjJ3ffYr2tx0KRaYh",,"error":null,"portNumber":57015}'
2017-07-21 07:58:32 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'obueRwCumY3TjqgkjJ3ffYr2tx0KRaYh', error: 'null', listeningPort: '57015''
,Connecting to the localhost:57015
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:0484139D-6BA0-4F9E-B15D-5ACBCFFF6C4C:0
Connected to the localhost:57015
,2017-07-21 07:58:32 - DEBUG testThaliMobileNative: 'Client sends data (65536 bytes):'
,2017-07-21 07:58:32 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0484139D-6BA0-4F9E-B15D-5ACBCFFF6C4C:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:10 [10]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
ok 102 got the same data ,back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStream,s() vsID:10
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:10
[ThaliCore] VirtualSocket.deinit vsID:10 []
,# teardown
,2017-07-21 07:58:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 07:58:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-21 07:58:40 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-21 07:58:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:68CF2D20-4470-,42C1-86DD-5C4B66AE0A9A
,2017-07-21 07:58:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:58:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:0484139D-6BA0-4F9E-B15D-5ACBCFFF6C4C
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:57015
[ThaliCore] Session.disconnect() p,eer:0484139D-6BA0-4F9E-B15D-5ACBCFFF6C4C:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:0484139D-6BA0-4F9E-B15D-5ACBCFFF6C4C:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-21 07:58:40 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 07:58:40 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 07:58:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:58:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:58:40 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:58:40 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:58:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:58:40 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We do not emit peerAvailabilityChanged events until one of the start methods is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "08FD39BA-1AD7-479D-A6F5-B6F2E5D20755", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:08FD39BA-1AD7-479D-A6F5-B6F2E5D20755
2017-07-21 0,7:58:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 07:58:42 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 07:58:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 103 Ready to advertise
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:7FD5C170-E010-478F-836A-34AE3A07912A
[ThaliCore] Browser.startListening
2017-07,-21 07:58:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 07:58:42 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not m,atch with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 07:58:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate, (was in stopped state).'
ok 104 Ready to listen
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9B670379-F421-4B0E-9E50-7194D7F30765:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9B670379-F421-4B0E-9E50-7194D7F30765", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8A567840-BD3A-492A-B7C1-9FDC148793B0:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8A567840-BD3A-492A-B7C1-9FDC148793B0", generation: 0)
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:08FD39BA-1AD7-479D-A6F5-B6F2E5D20755
,2017-07-21 07:58:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 07:58:42 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 07:58:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0484139D-6BA0-4F9E-B15D-5ACBCFFF6C4C:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0484139D-6BA0-4F9E-B15D-5ACBCFFF6C4C", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:45972DD7-E306-4909-AA0D-0C667C726D62:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "45972DD7-E306-4909-AA0D-0C667C726D62", generation: 0)
,ok 105 stop ads worked
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 07:58:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:58:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 106 test stop worked
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 07:58:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:58:46 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 07:58:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 07:58:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 07:58:46 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 07:58:46 - DEBUG t,haliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 07:58:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:58:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:58:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:58:46 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:58:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:58:46 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Test updating advertising and parallel data transfer
,2017-07-21 07:58:46 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test updating advertising and parallel data transfer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 07:58:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:58:46 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 07:58:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 07:58:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 07:58:46 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 07:58:46 - DEBUG t,haliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 07:58:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:58:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:58:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:58:46 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:58:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:58:46 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# discoveryAdvertisingStateUpdateNonTCP is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:85C82BE0-062A-4FF2-8C37-71AEE1744760
[ThaliCore] Browser.startListening
ok 107 discoveryActive should be false
ok 108 advertisingA,ctive should be true
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C841736D-A769-44F2-85EF-CDFAAA3D809E", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:C841736D-A769-44F2-85EF-CDFAAA3D809E
,ok 109 discoveryActive should be false
ok 110 advertisingActive should be true
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,ok 111 discoveryActive should be false
,ok 112 advertisingActive should be true
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:C841736D-A769-44F2-85EF-CDFAAA3D809E
,ok 113 discoveryActive should be false
,ok 114 advertisingActive should be true
,ok 115 Can call startListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 07:58:47 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 07:58:47 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 07:58:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:58:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:58:47 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:58:47 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:58:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:58:47 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call connect when start listening for advertisements is not active
,2017-07-21 07:58:47 - DEBUG CoordinatedClient: 'test was skipped, name: 'cannot call connect when start listening for advertisements is not active''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 07:58:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:58:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 116 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 07:58:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-07-21 07:58:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 117 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# Get error when trying to double connect to a peer on Android
,2017-07-21 07:58:48 - DEBUG CoordinatedClient: 'test was skipped, name: 'Get error when trying to double connect to a peer on Android''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 07:58:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:58:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 118 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 07:58:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-07-21 07:58:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 119 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection
,2017-07-21 07:58:48 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 07:58:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:58:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 120 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 07:58:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-07-21 07:58:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 121 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection
,2017-07-21 07:58:48 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 07:58:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:58:49 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 122 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 07:58:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:58:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 123 Should be able to call stopAdvertisingAndListening in tea,rdown
,# setup
,# #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer
,2017-07-21 07:58:49 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 07:58:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:58:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 124 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 07:58:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-07-21 07:58:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 125 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer
,2017-07-21 07:58:49 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 07:58:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:58:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 126 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 07:58:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:58:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 127 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# cannot call multiConnect when start listening for advertisements is not active
,ok 128 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:da50a176-686e-4d4c-83c2-ba2862d9ffdd error: startListeningNotActive
,2017-07-21 07:58:49 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"ZCNLqeb5eiGgMLSzK6Td0hybP7B2IgnC","error":"startListeningForAdvertisements is not active","portNumber":null}'
,ok 129 Should only get called after multiConnect returned
,ok 130 SyncValue matches
,ok 131 Got right error
,ok 132 listeningPort is null
,2017-07-21 07:58:49 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"da50a176-686e-4d4c-83c2-ba2862d9ffdd","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-21 07:58:49 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 07:58:49 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"da50a176-686e-4d4c-83c2-ba2862d9ffdd","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 07:58:49 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 07:58:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:58:50 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 07:58:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 07:58:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 07:58:50 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 07:58:50 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 07:58:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:58:50 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:58:50 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:58:50 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:58:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:58:50 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with illegal peerID
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:83F9CFF3-CEF1-411D-9553-F4B200AF0536
,[ThaliCore] Browser.startListening
,2017-07-21 07:58:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 07:58:50 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 07:58:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 133 No error on starting
,ok 134 Got null as expected
,2017-07-21 07:58:50 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"XnPkuiige6x65EUh8S4rn9X8O0VcCYaN","error":"Illegal peerID","portNumber":null}'
,ok 135 Should only get called after multiConnect returned
ok 136 SyncValue matches
,ok 137 Got right error
ok 138 listeningPort is null
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9B670379-F421-4B0E-9E50-7194D7F30765:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9B670379-F421-4B0E-9E50-7194D7F30765", generation: 0)
# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:45972DD7-E306-4909-AA0D-0C667C726D62:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "45972DD7-E306-4909-AA0D-0C667C726D62", generation: 0)
,2017-07-21 07:58:50 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"9B670379-F421-4B0E-9E50-7194D7F30765","generation":0}]'
2017-07-21 07:58:50 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"9B670379-F421-4B0E-9E50-7194D7F30765","generation":0}'
,2017-07-21 07:58:50 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 07:58:50 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"45972DD7-E306-4909-AA0D-0C667C726D62","generation":0}]'
,2017-07-21 07:58:50 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"45972DD7-E306-4909-AA0D-0C667C726D62","generation":0}'
,2017-07-21 07:58:50 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 07:58:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:58:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 07:58:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:58:50 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 07:58:50 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 07:58:50 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-07-21 07:58:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:58:50 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:58:50 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:58:50 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:58:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:58:50 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# multiConnect properly fails on legal but non-existent peerID
,2017-07-21 07:58:50 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiConnect properly fails on legal but non-existent peerID''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 07:58:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:58:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 07:58:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:58:51 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 07:58:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 07:58:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
2017-07-21 07:58:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:58:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:58:51 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:58:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:58:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:58:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with invalid syncValue
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:10B1DA38-4DAF-48FF-B2D8-D1B5DD3C8852
[ThaliCore] Browser.startListening
2017-07-21 07:58:51 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 07:58:51 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 07:58:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 139 No error on star,ting
,ok 140 Got right error
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:45972DD7-E306-4909-AA0D-0C667C726D62:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "45972DD7-E306-4909-AA0D-0C667C726D62", generation: 0)
,2017-07-21 07:58:51 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"45972DD7-E306-4909-AA0D-0C667C726D62","generation":0}]'
2017-07-21 07:58:51 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"45972DD7-E306-4909-AA0D-0C667C726D62","generation":0}'
2017-07-21 07:58:51 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent du,e to not being in started state'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 07:58:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:58:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 07:58:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:58:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 07:58:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 07:58:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 07:58:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:58:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:58:51 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:58:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:58:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:58:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call disconnect with invalid peer id
,ok 141 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 07:58:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:58:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 07:58:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:58:52 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 07:58:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 07:58:52 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
2017-07-21 07:58:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:58:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:58:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:58:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:58:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:58:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# disconnect doesn't fail on plausible but bogus peer ID
,[ThaliCore] BrowserManager.disconnect peer:e4c6a860-760a-4283-bf91-7a8985c51c7c
ok 142 No error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 07:58:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:58:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 07:58:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:58:53 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 07:58:53 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 07:58:53 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
2017-07-21 07:58:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:58:53 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:58:53 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:58:53 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:58:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:58:53 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Get same port when trying to connect multiple times on iOS
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "84BF45AB-2C17-4C8C-9041-D9E809F54A9C", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:84BF45AB-2C17-4C8C-9041-D9E809F54A9C
2017-07-21 0,7:58:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 07:58:53 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 07:58:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 143 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:AB22B73A-1A68-45CF-A1E7-0BF6FBE95420
[Tha,liCore] Browser.startListening
,2017-07-21 07:58:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 07:58:53 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 07:58:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 144 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:45972DD7-E306-4909-AA0D-0C667C726D62:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "45972DD7-E306-4909-AA0D-0C667C726D62", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:9B670379-F421-4B0E-9E50-7194D7F30765:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9B670379-F421-4B0E-9E50-7194D7F30765", generation: 0)
2017-07-21 07:58:53 - DEBUG thaliMobileNativeTestUtils: 'W,e got a peer {"peerAvailable":true,"peerIdentifier":"45972DD7-E306-4909-AA0D-0C667C726D62","generation":0}'
,2017-07-21 07:58:53 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 45972DD7-E306-4909-AA0D-0C667C726D62 (syncValue: JFHllyqwnb6oWHn4a065kcaKJMXgLzmj)'
2017-07-21 07:58:53 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "45972DD7-E306-4909-AA0D-0C667C726D62", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "45,972DD7-E306-4909-AA0D-0C667C726D62", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:45972DD7-E306-4909-AA0D-0C667C726D62:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,2017-07-21 07:58:53 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"9B670379-F421-4B0E-9E50-7194D7F30765","generation":0}'
,2017-07-21 07:58:53 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 07:58:53 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:81FF9BC4-DDD6-493F-9C81-AB9AE97C1F0E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "81FF9BC4-DDD6-493F-9C81-AB9AE97C1F0E", generation: 0)
2017-07-21 07:58:54 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"81FF9BC4-DDD6-493F-9C81-AB9AE97C1F0E","generation":0}'
2017-07-21 07:58:54 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 07:58:54 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-21 07:58:54 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:45972DD7-E306-4909-AA0D-0C667C726D62:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "45972DD7-E306-4909-AA0D-0C667C726D62", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6197B4A3-B151-412A-B001-2B3152ED3D6D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6197B4A3-B151-412A-B001-2B3152ED3D6D", generation: 0)
,2017-07-21 07:58:55 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"6197B4A3-B151-412A-B001-2B3152ED3D6D","generation":0}'
2017-07-21 07:58:55 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 07:58:55 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 07:58:55 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:84BF45AB-2C17-4C8C-9041-D9E809F54A9C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "84BF45AB-2C17-4C8C-9041-D9E809F54A9C", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:45972DD7-E306-4909-AA0D-0C667C726D62:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:45,972DD7-E306-4909-AA0D-0C667C726D62:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "45972DD7-E306-4909-AA0D-0C667C726D62", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,5972DD7-E306-4909-AA0D-0C667C726D62", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "45972DD7-E306-4909-AA0D-0C667C726D62", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 07:58:56 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"JFHllyqwnb6oWHn4a065kcaKJMXgLzmj","error":"Peer is unavailable",,"portNumber":null}'
2017-07-21 07:58:56 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'JFHllyqwnb6oWHn4a065kcaKJMXgLzmj', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-21 07:58:56 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"45972DD7-E306-4909-AA0D-0C667C726D62","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 07:58:56 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-21 07:58:56 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"45972DD7-E306-4909-AA0D-0C667C726D62","peerAvailable":true,"portNumber":null,"recreate,d":true}'
2017-07-21 07:58:56 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 07:58:56 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-21 07:58:56 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 9B670379-F421-4B0E-9E50-7194D7F30765 (syncValue: lK6uCDUTLUdON95bl79rIiX,ZZ0V0qv2b)'
2017-07-21 07:58:56 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9B670379-F421-4B0E-9E50-7194D7F30765", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9B670379-F421-4B0E-9E50-7194D7F30765", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9B670379-F421-4B0E-9E50-7194D,7F30765:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 07:58:56 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 07:58:56 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:45972DD7-E306-4909-AA0D-0C667C726D62:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:9B670379-F421-4B0E-9E50-7194D7F30765:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:9B,670379-F421-4B0E-9E50-7194D7F30765:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "9B670379-F421-4B0E-9E50-7194D7F30765", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,B670379-F421-4B0E-9E50-7194D7F30765", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9B670379-F421-4B0E-9E50-7194D7F30765", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:9B670379-F421-4B0E-9E50-7194D7F30765:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:9B670379-F421-4B0E-9E50-7194D7F30765:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:9B670379-F421-4B0E-9E50-7194D7F30765:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:9B,670379-F421-4B0E-9E50-7194D7F30765:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "9B670379-F421-4B0E-9E50-7194D7F30765", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,B670379-F421-4B0E-9E50-7194D7F30765", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9B670379-F421-4B0E-9E50-7194D7F30765", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:9B670379-F421-4B0E-9E50-7194D7F30765:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:9B670379-F421-4B0E-9E50-7194D7F30765:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:45972DD7-E306-4909-AA0D-0C667C726D62:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "45972DD7-E306-4909-AA0D-0C667C726D62", generation: 0)
,2017-07-21 07:59:02 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"45972DD7-E306-4909-AA0D-0C667C726D62","generation":0}'
,2017-07-21 07:59:02 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 07:59:02 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 07:59:02 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 07:59:02 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:9B670379-F421-4B0E-9E50-7194D7F30765:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "9B670379-F421-4B0E-9E50-7194D7F30765", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:9B670379-F421-4B0E-9E50-7194D7F30765:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:9B,670379-F421-4B0E-9E50-7194D7F30765:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "9B670379-F421-4B0E-9E50-7194D7F30765", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,B670379-F421-4B0E-9E50-7194D7F30765", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9B670379-F421-4B0E-9E50-7194D7F30765", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
,2017-07-21 07:59:04 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"lK6uCDUTLUdON95bl79rIiXZZ0V0qv2b","error":"Peer is unavailable","portNumber":null}'
,2017-07-21 07:59:04 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'lK6uCDUTLUdON95bl79rIiXZZ0V0qv2b', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-21 07:59:04 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"9B670379-F421-4B0E-9E50-7194D7F30765","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-21 07:59:04 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 07:59:04 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"9B670379-F421-4B0E-9E50-7194D7F30765","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 07:59:04 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 07:59:04 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,2017-07-21 07:59:04 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 81FF9BC4-DDD6-493F-9C81-AB9AE97C1F0E (syncValue: ZQJbb7fZ36cKABXNYkqNIdYgHzzLXFI7)'
,2017-07-21 07:59:04 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "81FF9BC4-DDD6-493F-9C81-AB9AE97C1F0E", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "81FF9BC4-DDD6-493F-9C81-AB9AE97C1F0E", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:81FF9BC4-DDD6-493F-9C81-AB9AE97C1F0E:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:9B670379-F421-4B0E-9E50-7194D7F30765:0
[ThaliCore] BrowserRelay.deinit
,2017-07-21 07:59:05 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 07:59:05 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:81FF9BC4-DDD6-493F-9C81-AB9AE97C1F0E:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:81FF9BC4-DDD6-493F-9C81-AB9AE97C1F0E:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:81FF9BC4-DDD6-493F-9C81-AB9AE97C1F0E:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "81FF9BC4-DDD6-493F-9C81-AB9AE97C1F0E", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57031
2017-07-21 07:59:07 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"ZQJbb7fZ36cKABXNYkqNIdYgHzzLXFI7",,"error":null,"portNumber":57031}'
2017-07-21 07:59:07 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'ZQJbb7fZ36cKABXNYkqNIdYgHzzLXFI7', error: 'null', listeningPort: '57031''
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:81FF9BC4-DDD6-493F-9C81-AB9AE97C1F0E:0
,ok 145 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "81FF9BC4-DDD6-493F-9C81-AB9AE97C1F0E", generation: 0) found active relay
,2017-07-21 07:59:07 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"0qwYi3FYmScu1doe1Gitqo1Rok1TLtXN","error":null,"portNumber":57031}'
,ok 146 No error
,ok 147 Ports equal
,ok 148 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "81FF9BC4-DDD6-493F-9C81-AB9AE97C1F0E", generation: 0) found active relay
,2017-07-21 07:59:07 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"ptcAntvNYkRfHlg8jSctp41adHUucVpb","error":null,"portNumber":57031}'
,ok 149 No error
,ok 150 Ports equal
,# teardown
,2017-07-21 07:59:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 07:59:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 07:59:07 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 07:59:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:84BF45AB-2C17-4C8C-9041-D9E809F54A9C
2017-07-21 07:59:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:59:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:81FF9BC4-DDD6-493F-9C81-AB9AE97C1F0E
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:57031
[ThaliCore] Session.disconnect() p,eer:81FF9BC4-DDD6-493F-9C81-AB9AE97C1F0E:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:81FF9BC4-DDD6-493F-9C81-AB9AE97C1F0E:0
[ThaliCore] BrowserRelay.deinit
,2017-07-21 07:59:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 07:59:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 07:59:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:59:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:59:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:59:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:59:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:59:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# initial peer discovery
,2017-07-21 07:59:07 - DEBUG CoordinatedClient: 'test was skipped, name: 'initial peer discovery''
,# teardown
,2017-07-21 07:59:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 07:59:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 07:59:08 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:59:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:59:08 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:59:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:59:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:59:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 1
,2017-07-21 07:59:08 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 1''
,# teardown
,2017-07-21 07:59:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 07:59:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 07:59:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:59:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:59:08 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:59:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:59:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:59:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 2
,2017-07-21 07:59:08 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 2''
,# teardown
,2017-07-21 07:59:09 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 07:59:09 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 07:59:09 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:59:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:59:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:59:09 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:59:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:59:09 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# check latest peer discovery
,2017-07-21 07:59:09 - DEBUG CoordinatedClient: 'test was skipped, name: 'check latest peer discovery''
,# teardown
,2017-07-21 07:59:09 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 07:59:09 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 07:59:09 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:59:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:59:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:59:09 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:59:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:59:09 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Set up for no peer discovery test
,2017-07-21 07:59:09 - DEBUG CoordinatedClient: 'test was skipped, name: 'Set up for no peer discovery test''
,# teardown
,2017-07-21 07:59:10 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 07:59:10 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 07:59:10 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:59:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:59:10 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:59:10 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:59:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:59:10 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# no peer discovery
,2017-07-21 07:59:10 - DEBUG CoordinatedClient: 'test was skipped, name: 'no peer discovery''
,# teardown
,2017-07-21 07:59:10 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 07:59:10 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 07:59:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:59:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:59:10 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:59:10 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:59:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:59:10 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calling createNativeListener directly rejects
,2017-07-21 07:59:10 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 07:59:10 - DEBUG createNativeListener: 'listening 57034'
,ok 151 Should throw
,# teardown
,2017-07-21 07:59:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 07:59:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 07:59:10 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits incomingConnectionState
,2017-07-21 07:59:11 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-21 07:59:11 - DEBUG createNativeListener: 'listening 57036'
,2017-07-21 07:59:11 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-21 07:59:11 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 152 initial connection state should be CONNECTED
,2017-07-21 07:59:11 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 153 final connection state should be DISCONNECTED
,# teardown
,2017-07-21 07:59:11 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 07:59:11 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 07:59:11 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits routerPortConnectionFailed
,2017-07-21 07:59:11 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 07:59:11 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 07:59:11 - DEBUG createNativeListener: 'listening 57039'
,2017-07-21 07:59:11 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-21 07:59:11 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 07:59:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-21 07:59:11 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - error Error: connect ECONNREFUSED'
,ok 154 tried to connect to right port
,ok 155 failed due to refused connection
,ok 156 routerPortConnectionFailed is emitted
,# teardown
,2017-07-21 07:59:11 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-21 07:59:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-21 07:59:11 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 07:59:11 - DEBUG createNativeListener: 'Native Server - close'
2017-07-21 07:59:11 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2017-07-21 07:59:11 - DEBUG createNativeListener: 'incoming ,- incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server connections all up
,2017-07-21 07:59:11 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 07:59:11 - DEBUG createNativeListener: 'listening 57043'
,2017-07-21 07:59:11 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-21 07:59:11 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 07:59:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-21 07:59:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,ok 157 Send/recvd #1 should be equal length
,ok 158 Send/recvd #1 should be same
,ok 159 Send/recvd #2 should be equal length
,ok 160 Send/recvd #2 should be same
,ok 161 Should be exactly 2 client sockets
,# teardown
,2017-07-21 07:59:11 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 07:59:11 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 07:59:11 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-21 07:59:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-21 07:59:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
,2017-07-21 07:59:11 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-21 07:59:11 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,2017-07-21 07:59:11 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-07-21 07:59:11 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# native server - closing incoming stream cleans outgoing socket
,2017-07-21 07:59:12 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-21 07:59:12 - DEBUG createNativeListener: 'listening 57048'
,2017-07-21 07:59:12 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-21 07:59:12 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 07:59:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-21 07:59:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-07-21 07:59:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,ok 162 socket shouldn't close until after stream
,ok 163 incoming remains open
,# teardown
,2017-07-21 07:59:12 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-21 07:59:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 07:59:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 07:59:13 - DEBUG createNativeListener: 'Native Server - close'
2017-07-21 07:59:13, - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2017-07-21 07:59:13 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing incoming connection cleans outgoing socket
,2017-07-21 07:59:13 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 07:59:13 - DEBUG createNativeListener: 'listening 57052'
,2017-07-21 07:59:13 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-21 07:59:13 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 164 we should not have gotten an error
,2017-07-21 07:59:13 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-21 07:59:13 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-21 07:59:13 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 165 socket shouldn't close until after incoming
,ok 166 incoming is cleaned up
,# teardown
,2017-07-21 07:59:13 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-21 07:59:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 07:59:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 07:59:13 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - closing outgoing socket cleans associated mux stream
,2017-07-21 07:59:13 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-21 07:59:13 - DEBUG createNativeListener: 'listening 57056'
,2017-07-21 07:59:13 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-21 07:59:13 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 07:59:13 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-21 07:59:13 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-07-21 07:59:13 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-21 07:59:13 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,ok 167 stream was closed
,ok 168 incoming should survive
,ok 169 mux should have no streams
,# teardown
,2017-07-21 07:59:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 07:59:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 07:59:14 - DEBUG createNativeListener: 'Native Server - close'
2017-07-21 07:59:14, - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2017-07-21 07:59:14 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing the whole server cleans everything up
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'listening 57060'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 170 we should not have gotten an error
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 171 Buffers are identical
,2017-07-21 07:59:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 172 native server is nulled out
,ok 173 native server should be closed
,ok 174 incoming has been removed
,ok 175 Incoming should be done
,ok 176 The mux object should be closed
,ok 177 The mux stream should be closed
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# teardown
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-21 07:59:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - we can get a ton of connections and data through and still clean up the server completely
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-21 07:59:14 - DEBUG createNativeListener: 'listening 57064'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - created'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - created'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - created'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - created'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - created'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - created'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - created'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - created'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - created'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - created'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - created'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - created'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - created'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - created'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - created'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - created'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - created'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - created'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - created'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - created'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - created'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - created'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - created'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - created'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - created'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - created'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - created'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - created'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - created'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - created'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - created'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - created'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - created'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - created'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - created'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - created'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - created'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - created'
,2017-07-21 07:59:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - closed'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - closed'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - closed'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - closed'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - closed'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - closed'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - closed'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - closed'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - closed'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - closed'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - closed'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - closed'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - closed'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - closed'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - closed'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - closed'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - closed'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - closed'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - closed'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - closed'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - closed'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - closed'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - closed'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - closed'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - closed'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - closed'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - closed'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - closed'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - closed'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - closed'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - closed'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - closed'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - closed'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - closed'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - closed'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - closed'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - closed'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - closed'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,ok 178 native server is nulled out
,ok 179 native server should be closed
,ok 180 incoming has been removed
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - close'
2017-07-21 07:59:15 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - close'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - close'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - close'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - close'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - close'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - close'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - close'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - close'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - close'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - close'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - close'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - close'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - close'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - close'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - close'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - close'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - close'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - close'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - close'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - close'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - close'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - close'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - close'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - close'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - close'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - close'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - close'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - close'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - close'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - close'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - close'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - close'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - close'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - close'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - close'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - close'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - close'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-21 07:59:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - simulate mux failure, make sure everything is cleaned up
,2017-07-21 07:59:16 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-21 07:59:16 - DEBUG createNativeListener: 'listening 57116'
,2017-07-21 07:59:16 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-21 07:59:16 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 181 we should not have gotten an error
,2017-07-21 07:59:16 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 182 Buffers are identical
,2017-07-21 07:59:16 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-21 07:59:16 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-21 07:59:16 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 183 server should be fine
,ok 184 server should be open
,ok 185 incoming has been removed
,ok 186 The mux object should be closed
,ok 187 The mux stream should be closed
,2017-07-21 07:59:16 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-21 07:59:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 07:59:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 07:59:16 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - timing out the incoming connection cleans everything up
,2017-07-21 07:59:16 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 07:59:16 - DEBUG createNativeListener: 'listening 57120'
,2017-07-21 07:59:16 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-21 07:59:16 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 188 we should not have gotten an error
,2017-07-21 07:59:16 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 189 Buffers are identical
,2017-07-21 07:59:16 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - incoming socket timeout'
,2017-07-21 07:59:16 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-21 07:59:16 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-21 07:59:16 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 190 server should be fine
,ok 191 server should be open
,ok 192 incoming has been removed
,ok 193 The mux object should be closed
,ok 194 The mux stream should be closed
,# teardown
,2017-07-21 07:59:16 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-21 07:59:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 07:59:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 07:59:16 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# can create servers manager
,ok 195 serversManager must not be null
ok 196 serversManager must be an object
,# teardown
,# setup
,# calling stop without start causes error
,ok 197 We need to call start first
,# teardown
,# setup
,# can start/stop servers manager
,2017-07-21 07:59:17 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-21 07:59:17 - DEBUG createNativeListener: 'listening 57123'
ok 198 port must be in range
,# teardown
,2017-07-21 07:59:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 07:59:17 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# starting twice resolves with listening port
,2017-07-21 07:59:17 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 07:59:17 - DEBUG createNativeListener: 'listening 57124'
,ok 199 second start should return same port
,# teardown
,2017-07-21 07:59:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 07:59:18 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminateIncomingConnection will terminate a connection
,2017-07-21 07:59:18 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 07:59:18 - DEBUG createNativeListener: 'listening 57126'
,2017-07-21 07:59:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-21 07:59:18 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 200 we should be connected
,2017-07-21 07:59:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 201 now we are disconnected
,2017-07-21 07:59:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# teardown
,2017-07-21 07:59:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 07:59:18 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminate an Outgoing connection
,2017-07-21 07:59:18 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 32'
,ok 202 Passed bogus id
,2017-07-21 07:59:18 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 901'
,ok 203 Passed good id but bogus port
,2017-07-21 07:59:18 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 900'
,ok 204 Passed right context
,ok 205 Right server
,ok 206 No error should be set
,ok 207 Retry should be false
,ok 208 We called close server
,# teardown
,# setup
,# Single local http request
,listening on 57128
,ok 209 should be equal
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 07:59:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:59:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 07:59:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {,"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:59:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 07:59:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21, 07:59:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 07:59:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 07:59:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:59:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:59:19 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:59:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:59:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:59:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Single coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "BF4A1875-D77B-4930-8496-4BFA2D99D970", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:BF4A1875-D77B-4930-8496-4BFA2D99D970
2017-07-21 0,7:59:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 07:59:19 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 07:59:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
,ok 210 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:3B7311B4-200D-479D-8F41-D0B8ECD9B748
,[ThaliCore] Browser.startListening
,2017-07-21 07:59:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 07:59:19 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-21 07:59:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 211 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6197B4A3-B151-412A-B001-2B3152ED3D6D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6197B4A3-B151-412A-B001-2B3152ED3D6D", generation: 0)
,2017-07-21 07:59:20 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"6197B4A3-B151-412A-B001-2B3152ED3D6D","generation":0}'
,2017-07-21 07:59:20 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 6197B4A3-B151-412A-B001-2B3152ED3D6D (syncValue: aeFL0BPqF0YX4mHeu7c7uI0j6bPQATu3)'
,2017-07-21 07:59:20 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6197B4A3-B151-412A-B001-2B3152ED3D6D", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "6197B4A3-B151-412A-B001-2B3152ED3D6D", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:6197B4A3-B151-412A-B001-2B3152ED3D6D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9A958306-EC3D-44EB-89A8-EA859D70CC56:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9A958306-EC3D-44EB-89A8-EA859D70CC56", generation: 0)
,2017-07-21 07:59:20 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"9A958306-EC3D-44EB-89A8-EA859D70CC56","generation":0}'
,2017-07-21 07:59:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 07:59:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BF4A1875-D77B-4930-8496-4BFA2D99D970:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BF4A1875-D77B-4930-8496-4BFA2D99D970", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BE7D46BF-E36C-4CFC-8F1B-0419EE18E394:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BE7D46BF-E36C-4CFC-8F1B-0419EE18E394", generation: 0)
,2017-07-21 07:59:20 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"BE7D46BF-E36C-4CFC-8F1B-0419EE18E394","generation":0}'
,2017-07-21 07:59:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 07:59:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 07:59:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:6197B4A3-B151-412A-B001-2B3152ED3D6D:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "6197B4A3-B151-412A-B001-2B3152ED3D6D", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:6197B4A3-B151-412A-B001-2B3152ED3D6D:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:61,97B4A3-B151-412A-B001-2B3152ED3D6D:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "6197B4A3-B151-412A-B001-2B3152ED3D6D", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,197B4A3-B151-412A-B001-2B3152ED3D6D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "6197B4A3-B151-412A-B001-2B3152ED3D6D", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 07:59:23 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"aeFL0BPqF0YX4mHeu7c7uI0j6bPQATu3","error":"Peer is unavailable",,"portNumber":null}'
2017-07-21 07:59:23 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'aeFL0BPqF0YX4mHeu7c7uI0j6bPQATu3', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-21 07:59:23 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"6197B4A3-B151-412A-B001-2B3152ED3D6D","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 07:59:23 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-21 07:59:23 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"6197B4A3-B151-412A-B001-2B3152ED3D6D","peerAvailable":true,"portNumber":null,"recreate,d,":true}'
,2017-07-21 07:59:23 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 07:59:23 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,2017-07-21 07:59:23 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 9A958306-EC3D-44EB-89A8-EA859D70CC56 (syncValue: NyHIz6ZS17gbopUJ5CqSaNxCJTcOWtvD)'
,2017-07-21 07:59:23 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9A958306-EC3D-44EB-89A8-EA859D70CC56", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9A958306-EC3D-44EB-89A8-EA859D70CC56", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9A958306-EC3D-44EB-89A8-EA859D70CC56:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 07:59:23 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:6197B4A3-B151-412A-B001-2B3152ED3D6D:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:9A958306-EC3D-44EB-89A8-EA859D70CC56:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:468EE149-B728-47C9-B180-34D960C0F8FA
[ThaliCore] Advertiser: session connected Peer(uuid: "BF4A1875-D77B-4930-8496-4BFA2D99D970", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:468EE149-B728-47C9-B180-34D960C0F8FA state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:9A958306-EC3D-44EB-89A8-EA859D70CC56:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:9A958306-EC3D-44EB-89A8-EA859D70CC56:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "9A958306-EC3D-44EB-89A8-EA859D70CC56", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57136
2017-07-21 07:59:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"NyHIz6ZS17gbopUJ5CqSaNxCJTcOWtvD",,"error":null,"portNumber":57136}'
2017-07-21 07:59:26 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'NyHIz6ZS17gbopUJ5CqSaNxCJTcOWtvD', error: 'null', listeningPort: '57136''
,ok 212 should be equal
,2017-07-21 07:59:26 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for BE7D46BF-E36C-4CFC-8F1B-0419EE18E394 (syncValue: rzwx2PD793VRduYy3n7l7h5tZpzBOl9s)'
,2017-07-21 07:59:26 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "BE7D46BF-E36C-4CFC-8F1B-0419EE18E394", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BE7D46BF-E36C-4CFC-8F1B-0419EE18E394", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:BE7D46BF-E36C-4CFC-8F1B-0419EE18E394:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:BE7D46BF-E36C-4CFC-8F1B-0419EE18E394:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1015D93F-E501-4227-8F24-53E16A8BE897
[ThaliCore] Advertiser: session connected Peer(uuid: "BF4A1875-D77B-4930-8496-4BFA2D99D970", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:1015D93F-E501-4227-8F24-53E16A8BE897 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:468EE149-B728-47C9-B180-34D960C0F8FA
,[ThaliCore] Session.session(_:peer:didChange:) peer:468EE149-B728-47C9-B180-34D960C0F8FA state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:BE7D46BF-E36C-4CFC-8F1B-0419EE18E394:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:BE7D46BF-E36C-4CFC-8F1B-0419EE18E394:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "BE7D46BF-E36C-4CFC-8F1B-0419EE18E394", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57140
,2017-07-21 07:59:29 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"rzwx2PD793VRduYy3n7l7h5tZpzBOl9s","error":null,"portNumber":57140}'
,2017-07-21 07:59:29 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'rzwx2PD793VRduYy3n7l7h5tZpzBOl9s', error: 'null', listeningPort: '57140''
,ok 213 should be equal
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:1015D93F-E501-4227-8F24-53E16A8BE897
,[ThaliCore] Session.session(_:peer:didChange:) peer:1015D93F-E501-4227-8F24-53E16A8BE897 state: connecting -> connected
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 07:59:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 ,07:59:30 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-21 07:59:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:BF4A1875-D77B-4930-8496-4,BFA2D99D970
2017-07-21 07:59:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:59:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in s,[ThaliCore] Session.session(_:peer:didChange:) peer:468EE149-B728-47C9-B180-34D960C0F8FA state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "BF4A1875-D77B-4930-8496-4BFA2D99D970", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:1015D93F-E501-4227-8F24-53E16A8BE897
,topped state).'
,[ThaliCore] BrowserManager.disconnect peer:9A958306-EC3D-44EB-89A8-EA859D70CC56
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:57136
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:9A958306-EC3D-44EB-89A8-EA859D70CC56:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:9A958306-EC3D-44EB-89A8-EA859D70CC56:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uui,d: "9A958306-EC3D-44EB-89A8-EA859D70CC56", generation: 0)
,[ThaliCore] Session.deinit peer:1015D93F-E501-4227-8F24-53E16A8BE897
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] BrowserManager.disconnect peer:BE7D46BF-E36C-4CFC-8F1B-0419EE18E394
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:57140
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:BE7D46BF-E36C-4CFC-8F1B-0419EE18E394:0
,[ThaliCore] Session.deinit peer:BE7D46BF-E36C-4CFC-8F1B-0419EE18E394:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-21 07:59:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 07:59:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 07:59:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 07:59:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:59:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:59:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:59:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:59:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:59:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-21 07:59:30 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"NyHIz6ZS17gbopUJ5CqSaNxCJTcOWtvD","error":"Session disconnected","portNumber":null}'
,2017-07-21 07:59:30 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"9A958306-EC3D-44EB-89A8-EA859D70CC56","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-21 07:59:30 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 07:59:30 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"9A958306-EC3D-44EB-89A8-EA859D70CC56","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 07:59:30 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Session.deinit peer:9A958306-EC3D-44EB-89A8-EA859D70CC56:0
,[ThaliCore] BrowserRelay.deinit
,# Multiple local http requests
,listening on 57142
,ok 214 should be equal
,ok 215 should be equal
,ok 216 should be equal
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 07:59:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:59:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 07:59:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {,"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:59:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 07:59:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21, 07:59:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 07:59:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 07:59:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:59:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:59:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:59:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:59:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:59:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Multiple coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "98432C64-BBE6-47D0-8F65-58905E66E920", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:98432C64-BBE6-47D0-8F65-58905E66E920
2017-07-21 0,7:59:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 07:59:32 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 07:59:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 217 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:419DC82A-44BA-4B39-B3B6-93BAD8E5056D
[Tha,liCore] Browser.startListening
2017-07-21 07:59:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 07:59:32 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-21 07:59:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 218 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BE7D46BF-E36C-4CFC-8F1B-0419EE18E394:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BE7D46BF-E36C-4CFC-8F1B-0419EE18E394", generation: 0)
2017-07-21 07:59:32 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"BE7D46BF-E36C-4CFC-8F1B-0419EE18E394","generation":0}'
2017-07-21 07:59:32 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for BE7D46BF-E36C-4CFC-8F1B-0419EE18E394, (syncValue: SqerB6sO5eSFuMXzwyRQeaKmla7dMwK2)'
2017-07-21 07:59:32 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "BE7D46BF-E36C-4CFC-8F1B-0419EE1,8E394", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BE7D46BF-E36C-4CFC-8F1B-0419EE18E394", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected,:,) peer:BE7D46BF-E36C-4CFC-8F1B-0419EE18E394:0
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9A958306-EC3D-44EB-89A8-EA859D70CC56:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPList,ener.init(with:socketDisconnected:stoppedListening:)
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9A958306-EC3D-44EB-89A8-EA859D70CC56", generation: 0)
2017-07-21 07:59:32 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable,":true,"peerIdentifier":"9A958306-EC3D-44EB-89A8-EA859D70CC56","generation":0}'
2017-07-21 07:59:32 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 07:59:32 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BFCB2BCD-C807-439B-8959-5A1DEF10A145:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BFCB2BCD-C807-439B-8959-5A1DEF10A145", generation: 0)
2017-07-21 07:59:33 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"BFCB2BCD-C807-439B-8959-5A1DEF10A145","generation":0}'
2017-07-21 07:59:33 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 07:59:33 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-21 07:59:33 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C7BBE235-3DD4-43E3-BA80-A3BA3281F60E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C7BBE235-3DD4-43E3-BA80-A3BA3281F60E", generation: 0)
2017-07-21 07:59:33 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"C7BBE235-3DD4-43E3-BA80-A3BA3281F60E","generation":0}'
2017-07-21 07:59:33 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 07:59:33 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
,2017-07-21 07:59:33 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 07:59:33 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:98432C64-BBE6-47D0-8F65-58905E66E920:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "98432C64-BBE6-47D0-8F65-58905E66E920", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:BE7D46BF-E36C-4CFC-8F1B-0419EE18E394:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:BE,7D46BF-E36C-4CFC-8F1B-0419EE18E394:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "BE7D46BF-E36C-4CFC-8F1B-0419EE18E394", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,E7D46BF-E36C-4CFC-8F1B-0419EE18E394", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BE7D46BF-E36C-4CFC-8F1B-0419EE18E394", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:BE7D46BF-E36C-4CFC-8F1B-0419EE18E394:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:BE7D46BF-E36C-4CFC-8F1B-0419EE18E394:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:BE7D46BF-E36C-4CFC-8F1B-0419EE18E394:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:BE,7D46BF-E36C-4CFC-8F1B-0419EE18E394:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "BE7D46BF-E36C-4CFC-8F1B-0419EE18E394", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,E7D46BF-E36C-4CFC-8F1B-0419EE18E394", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BE7D46BF-E36C-4CFC-8F1B-0419EE18E394", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:BE7D46BF-E36C-4CFC-8F1B-0419EE18E394:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:BE7D46BF-E36C-4CFC-8F1B-0419EE18E394:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:BE7D46BF-E36C-4CFC-8F1B-0419EE18E394:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:BE,7D46BF-E36C-4CFC-8F1B-0419EE18E394:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "BE7D46BF-E36C-4CFC-8F1B-0419EE18E394", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,E7D46BF-E36C-4CFC-8F1B-0419EE18E394", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BE7D46BF-E36C-4CFC-8F1B-0419EE18E394", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:BE7D46BF-E36C-4CFC-8F1B-0419EE18E394:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:BE7D46BF-E36C-4CFC-8F1B-0419EE18E394:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:9A958306-EC3D-44EB-89A8-EA859D70CC56:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "9A958306-EC3D-44EB-89A8-EA859D70CC56", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:BE7D46BF-E36C-4CFC-8F1B-0419EE18E394:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:BE,7D46BF-E36C-4CFC-8F1B-0419EE18E394:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "BE7D46BF-E36C-4CFC-8F1B-0419EE18E394", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:BE7D46BF,-E36C-4CFC-8F1B-0419EE18E394 error: max retries exceeded
2017-07-21 07:59:43 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"SqerB6sO5eSFuMXzwyRQeaKmla7dMwK2","error":"Connection could not be established","portNumber":null}'
2017-0,7-21 07:59:43 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'SqerB6sO5eSFuMXzwyRQeaKmla7dMwK2', error: 'Connection could not be established', listeningPort: '%s''
2017-07-21 07:59:43 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"BE7D46BF-E36C-4CFC-8F1B-0419EE18E394","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 07:59:43 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent, due to not being in started state'
2017-07-21 07:59:43 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"BE7D46BF-E36C-4CFC-8F1B-0419EE18E394","peerAvailable":true,"portNumber":null,"recreated":true}'
20,17-07-21 07:59:43 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 07:59:43 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-21 07:59:43 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for BFCB2BCD-C807-439B-8959-5A1DEF10A145 (syncValue: CNJMdRn,i0w5AMtBS2VVsU6IxgmTM4VZP)'
2017-07-21 07:59:43 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "BFCB2BCD-C807-439B-8959-5A1DEF10A145", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BFCB2BCD-C807-439B-8959-5A1DEF10A145", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:BFCB2BCD-C807,-439B-8959-5A1DEF10A145:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 07:59:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 07:59:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:BE7D46BF-E36C-4CFC-8F1B-0419EE18E394:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:BFCB2BCD-C807-439B-8959-5A1DEF10A145:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:BFCB2BCD-C807-439B-8959-5A1DEF10A145:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:BFCB2BCD-C807-439B-8959-5A1DEF10A145:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "BFCB2BCD-C807-439B-8959-5A1DEF10A145", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57161
2017-07-21 07:59:46 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"CNJMdRni0w5AMtBS2VVsU6IxgmTM4VZP",,"error":null,"portNumber":57161}'
2017-07-21 07:59:46 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'CNJMdRni0w5AMtBS2VVsU6IxgmTM4VZP', error: 'null', listeningPort: '57161''
,ok 219 should be equal
,ok 220 should be equal
,ok 221 should be equal
,2017-07-21 07:59:46 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for C7BBE235-3DD4-43E3-BA80-A3BA3281F60E (syncValue: 9t4LjvJdEnxFo8CeSQjgXhsbn9kh7els)'
,2017-07-21 07:59:46 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C7BBE235-3DD4-43E3-BA80-A3BA3281F60E", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C7BBE235-3DD4-43E3-BA80-A3BA3281F60E", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C7BBE235-3DD4-43E3-BA80-A3BA3281F60E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
2017-07-21 07:59:46 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3E17DEE8-7F8E-4431-9B40-F19C919BA109
[ThaliCore] Advertiser: session connected Peer(uuid: "98432C64-BBE6-47D0-8F65-58905E66E920", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:3E17DEE8-7F8E-4431-9B40-F19C919BA109 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:C7BBE235-3DD4-43E3-BA80-A3BA3281F60E:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:BE7D46BF-E36C-4CFC-8F1B-0419EE18E394:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "BE7D46BF-E36C-4CFC-8F1B-0419EE18E394", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:7856DD58-C61B-439F-B37F-134F59E2FFBD
[ThaliCore] Advertiser: session connected Peer(uuid: "98432C64-BBE6-47D0-8F65-58905E66E920", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:7856DD58-C61B-439F-B37F-134F59E2FFBD state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:C7BBE235-3DD4-43E3-BA80-A3BA3281F60E:0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:3E17DEE8-7F8E-4431-9B40-F19C919BA109
,[ThaliCore] Session.session(_:peer:didChange:) peer:C7BBE235-3DD4-43E3-BA80-A3BA3281F60E:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "C7BBE235-3DD4-43E3-BA80-A3BA3281F60E", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57167
,2017-07-21 07:59:49 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"9t4LjvJdEnxFo8CeSQjgXhsbn9kh7els","error":null,"portNumber":57167}'
,2017-07-21 07:59:49 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '9t4LjvJdEnxFo8CeSQjgXhsbn9kh7els', error: 'null', listeningPort: '57167''
,ok 222 should be equal
,ok 223 should be equal
,ok 224 should be equal
,# teardown
,[ThaliCore] Session.session(_:peer:didChange:) peer:3E17DEE8-7F8E-4431-9B40-F19C919BA109 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:7856DD58-C61B-439F-B37F-134F59E2FFBD
,[ThaliCore] Session.session(_:peer:didChange:) peer:7856DD58-C61B-439F-B37F-134F59E2FFBD state: connecting -> connected
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 07:59:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 ,07:59:50 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-21 07:59:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:98432C64-BBE6-47D0-8F65-5,8905E66E920
2017-07-21 07:59:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:59:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,stopped state).'
[ThaliCore] BrowserManager.disconnect peer:BFCB2BCD-C807-439B-8959-5A1DEF10A145
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:57161
[ThaliCore] Sess,ion.disconnect() peer:BFCB2BCD-C807-439B-8959-5A1DEF10A145:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:BFCB2BCD-C807-439B-8959-5A1DEF10A145:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] BrowserManager.disconnect peer:C7BBE235-3DD4-43E3-BA80-A3BA3281F60E
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:57167
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:C7BBE235-3DD4-43E3-BA80-A3BA3281F60E:0
,[ThaliCore] Session.deinit peer:C7BBE235-3DD4-43E3-BA80-A3BA3281F60E:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-21 07:59:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 07:59:50 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 07:59:50 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 07:59:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,[ThaliCore] Session.session(_:peer:didChange:) peer:3E17DEE8-7F8E-4431-9B40-F19C919BA109 state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "98432C64-BBE6-47D0-8F65-58905E66E920", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:7856DD58-C61B-439F-B37F-134F59E2FFBD
,2017-07-21 07:59:50 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:59:50 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:59:50 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:59:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:59:50 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.deinit peer:7856DD58-C61B-439F-B37F-134F59E2FFBD
,[ThaliCore] AdvertiserRelay.deinit
,# #startListeningForAdvertisements should fail if start not called
,ok 225 specific error should be returned
,# teardown
,ok 226 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 07:59:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:59:51 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 07:59:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 07:59:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 07:59:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 07:59:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 07:59:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:59:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:59:51 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:59:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:59:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:59:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# #startUpdateAdvertisingAndListening should fail if start not called
,ok 227 specific error should be returned
,# teardown
,ok 228 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 07:59:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:59:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 07:59:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:59:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 07:59:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 07:59:52 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 07:59:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:59:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:59:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:59:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:59:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:59:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #stopListeningForAdvertisements many times
,2017-07-21 07:59:52 - DEBUG thaliMobileNativeWrapper: 'listening 57171'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 07:59:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:59:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 229 no errors
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 07:59:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:59:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 230 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 07:59:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:59:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 07:59:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:59:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 07:59:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 231 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 07:59:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:59:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 07:59:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:59:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 07:59:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 07:59:52 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 07:59:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:59:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:59:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:59:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:59:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:59:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #startListeningForAdvertisements many times
,2017-07-21 07:59:52 - DEBUG thaliMobileNativeWrapper: 'listening 57172'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:8C97FC3C-00F6-479D-9553-691287D088BF
,[ThaliCore] Browser.startListening
,2017-07-21 07:59:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 07:59:52 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 07:59:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 232 no errors
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-07-21 07:59:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 07:59:52 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 07:59:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 233 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 07:59:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 07:59:52 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 07:59:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-21 07:59:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:59:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 07:59:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 234 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 07:59:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:59:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 07:59:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:59:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 07:59:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 07:59:52 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 07:59:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:59:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:59:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:59:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:59:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:59:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-07-21 07:59:53 - DEBUG thaliMobileNativeWrapper: 'listening 57173'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "DD3A6C10-2292-41EE-9020-A502CC343C9E", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:DD3A6C10-2292-41EE-9020-A502CC343C9E
,2017-07-21 07:59:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-21 07:59:53 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 07:59:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 235 no errors
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "DD3A6C10-2292-41EE-9020-A502CC343C9E", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:DD3A6C10-2292-41EE-9020-A502CC343C9E
,2017-07-21 07:59:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-21 07:59:53 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 07:59:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 236 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:DD3A6C10-2292-41EE-9020-A502CC343C9E
,[ThaliCore] Advertiser.stopAdvertising() peerID:DD3A6C10-2292-41EE-9020-A502CC343C9E
2017-07-21 07:59:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:59:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 07:59:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:59:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 07:59:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 237 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 07:59:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:59:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 07:59:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:59:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 07:59:53 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 07:59:53 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 07:59:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:59:53 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:59:53 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:59:53 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:59:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:59:53 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #stopAdvertisingAndListening many times
,2017-07-21 07:59:53 - DEBUG thaliMobileNativeWrapper: 'listening 57176'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 07:59:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingAct,ive":false}'
2017-07-21 07:59:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 238 no errors
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 07:59:53 - DEBUG thaliMobileNativeWrapper: 'discover,yAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:59:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 239 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 07:59:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:59:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 07:59:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:59:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 07:59:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 240 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 07:59:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:59:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 07:59:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:59:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 07:59:53 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 07:59:53 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 07:59:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:59:53 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:59:53 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:59:53 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:59:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:59:53 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can get the network status before starting
,ok 241 network status should have certain non-empty properties
,# teardown
,ok 242 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 07:59:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:59:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 07:59:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:59:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 07:59:54 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 07:59:54 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 07:59:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:59:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:59:54 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:59:54 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:59:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:59:54 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# error returned with bad router
,2017-07-21 07:59:54 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a string'
,ok 243 specific error expected
,# teardown
,ok 244 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 07:59:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:59:55 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 07:59:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 07:59:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 07:59:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 07:59:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 07:59:55 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:59:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:59:55 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:59:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:59:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:59:55 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# all services are started when we call start
,2017-07-21 07:59:55 - DEBUG thaliMobileNativeWrapper: 'listening 57177'
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:7EF4287B-F4D9-444D-A659-01C91E5C50FD
[ThaliCore] Browser.startListening
2017-07-21 07:59:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,",advertisingActive":false}'
2017-07-21 07:59:55 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments",:{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 07:59:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandle,r:) Peer(uuid: "5410763C-5DAC-4F0A-8AF7-F567603971EE", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:5410763C-5DAC-4F0A-8AF7-F567603971EE
2017-07-21 07:59:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {,"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 07:59:55 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 07:59:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 245 all connection succeed
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C7BBE235-3DD4-43E3-BA80-A3BA3281F60E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C7BBE235-3DD4-43E3-BA80-A3BA3281F60E", generation: 0)
# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BFCB2BCD-C807-439B-8959-5A1DEF10A145:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BFCB2BCD-C807-439B-8959-5A1DEF10A145", generation: 0)
,2017-07-21 07:59:55 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"C7BBE235-3DD4-43E3-BA80-A3BA3281F60E","generation":0}]'
,2017-07-21 07:59:55 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"C7BBE235-3DD4-43E3-BA80-A3BA3281F60E","generation":0}'
,2017-07-21 07:59:55 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"BFCB2BCD-C807-439B-8959-5A1DEF10A145","generation":0}]'
,2017-07-21 07:59:55 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"BFCB2BCD-C807-439B-8959-5A1DEF10A145","generation":0}'
,2017-07-21 07:59:55 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"C7BBE235-3DD4-43E3-BA80-A3BA3281F60E","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 07:59:55 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"C7BBE235-3DD4-43E3-BA80-A3BA3281F60E","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 07:59:55 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"BFCB2BCD-C807-439B-8959-5A1DEF10A145","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 07:59:55 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"BFCB2BCD-C807-439B-8959-5A1DEF10A145","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:5410763C-5DAC-4F0A-8AF7-F567603971EE
,2017-07-21 07:59:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 07:59:55 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 07:59:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 07:59:55 - DEBUG thaliMobileNativeW,rapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:59:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 07:59:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 246 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 07:59:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:59:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 07:59:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:59:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 07:59:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 07:59:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 07:59:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:59:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:59:55 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:59:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:59:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:59:55 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# TCP Servers Manager should be null when we call start on iOS
,2017-07-21 07:59:56 - DEBUG thaliMobileNativeWrapper: 'listening 57180'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:124601DE-116A-477D-9DE2-5ACEA1E6BDEB
[ThaliCore] Browser.st,artListening
2017-07-21 07:59:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 07:59:56 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 07:59:56 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "7F1D8E3C-7465-4B18-B43E-1B7B4CAEEA8B", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID,:,7F1D8E3C-7465-4B18-B43E-1B7B4CAEEA8B
,2017-07-21 07:59:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 07:59:56 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 07:59:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 247 TCP Servers Manager doesn't exists
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:7F1D8E3C-7465-4B18-B43E-1B7B4CAEEA8B
,2017-07-21 07:59:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 07:59:56 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 07:59:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 07:59:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:59:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 07:59:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 248 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 07:59:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:59:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 07:59:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:59:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 07:59:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 07:59:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 07:59:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:59:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:59:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:59:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:59:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:59:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# all services are stopped when we call stop
,2017-07-21 07:59:56 - DEBUG thaliMobileNativeWrapper: 'listening 57182'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:251CE882-BC52-46AB-838C-6FD6EAC1C31B
,[ThaliCore] Browser.startListening
,2017-07-21 07:59:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 07:59:56 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 07:59:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "DCA6851B-7099-4BA5-8379-964CB76D5F49", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:DCA6851B-7099-4BA5-8379-964CB76D5F49
,2017-07-21 07:59:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 07:59:56 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-21 07:59:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:DCA6851B-7099-4BA5-8379-964CB76D5F49
,2017-07-21 07:59:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 07:59:56 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 07:59:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 07:59:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:59:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 07:59:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 249 is stopped after calling stop
,ok 250 connection should fail after stopping
,# teardown
,ok 251 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 07:59:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:59:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 07:59:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:59:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 07:59:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 07:59:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 07:59:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:59:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:59:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:59:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:59:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:59:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateConnection is properly hooked up
,2017-07-21 07:59:57 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateConnection is properly hooked up''
,# teardown
,ok 252 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 07:59:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:59:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 07:59:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:59:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 07:59:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 07:59:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 07:59:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:59:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:59:57 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:59:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:59:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:59:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateConnection is return error if we get called on iOS
,ok 253 error description matches
,# teardown
,ok 254 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 07:59:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:59:57 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 07:59:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 07:59:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 07:59:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 07:59:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 07:59:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:59:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:59:57 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:59:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:59:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:59:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is properly hooked up
,2017-07-21 07:59:58 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateListener is properly hooked up''
,# teardown
,ok 255 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 07:59:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:59:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 07:59:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:59:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 07:59:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 07:59:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 07:59:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:59:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:59:58 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:59:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:59:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:59:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is return error if we get called on iOS
,ok 256 error description matches
,# teardown
,ok 257 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 07:59:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:59:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 07:59:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:59:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 07:59:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 07:59:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 07:59:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:59:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:59:58 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:59:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:59:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:59:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure we actually call kill connections properly
,ok 258 IMPLEMENT ME!!!!!!
,# teardown
,ok 259 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 07:59:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:59:59 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 07:59:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 07:59:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 07:59:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 07:59:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 07:59:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:59:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:59:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:59:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:59:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:59:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
,2017-07-21 07:59:59 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''
,# teardown
,ok 260 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 07:59:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:59:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 07:59:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:59:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 07:59:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 07:59:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 07:59:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:59:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:59:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:59:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:59:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:59:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager
,2017-07-21 07:59:59 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''
,# teardown
,ok 261 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 07:59:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:59:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 07:59:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:59:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 07:59:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 07:59:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 07:59:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:59:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:59:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:59:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:59:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:59:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from multiConnectConnection
,2017-07-21 08:00:00 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 262 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:00:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:00:00 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:00:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 08:00:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:00:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:00:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:00:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:00:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:00:00 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:00:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:00:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:00:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection
,2017-07-21 08:00:00 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 263 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:00:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:00:00 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:00:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 08:00:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:00:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:00:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:00:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:00:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:00:00 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:00:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:00:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:00:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved
,ok 264 NOT IMPLEMENTED # SKIP
,# teardown
,ok 265 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:00:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:00:01 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:00:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 08:00:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:00:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:00:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:00:01 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:00:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:00:01 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:00:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:00:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:00:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure bad PSK connections fail
,2017-07-21 08:00:01 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure bad PSK connections fail''
,# teardown
,ok 266 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:00:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:00:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:00:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:00:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:00:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:00:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:00:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:00:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:00:02 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:00:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:00:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:00:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peer changes handled from a queue
,2017-07-21 08:00:02 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer changes handled from a queue''
,# teardown
,ok 267 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:00:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:00:02 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:00:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 08:00:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:00:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:00:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:00:02 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:00:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:00:02 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:00:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:00:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:00:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# relaying discoveryAdvertisingStateUpdateNonTCP
,2017-07-21 08:00:02 - DEBUG CoordinatedClient: 'test was skipped, name: 'relaying discoveryAdvertisingStateUpdateNonTCP''
,# teardown
,ok 268 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:00:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:00:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:00:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:00:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:00:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:00:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:00:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:00:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:00:02 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:00:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:00:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:00:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received
,2017-07-21 08:00:03 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''
,# teardown
,ok 269 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:00:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:00:03 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:00:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 08:00:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:00:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:00:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:00:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:00:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:00:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:00:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:00:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:00:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# we successfully receive and replay discoveryAdvertisingStateUpdate
,2017-07-21 08:00:03 - DEBUG thaliMobileNativeWrapper: 'listening 57185'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:AD0268F5-CE16-4DB2-9015-D9583DB745B6
,[ThaliCore] Browser.startListening
,2017-07-21 08:00:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 08:00:03 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 08:00:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 270 discoveryActive matches
,ok 271 advertisingActive matches
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:00:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 08:00:03 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 08:00:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-21 08:00:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:00:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 272 discoveryActive matches
,ok 273 advertisingActive matches
,2017-07-21 08:00:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 08:00:03 - DEBUG thaliMobileNativeWrapper: 'listening 57186'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "E75B6F74-2BC6-4D81-9A53-15D3F3D0922E", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:E75B6F74-2BC6-4D81-9A53-15D3F3D0922E
,2017-07-21 08:00:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-21 08:00:03 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 08:00:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 274 discoveryActive matches
,ok 275 advertisingActive matches
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:E75B6F74-2BC6-4D81-9A53-15D3F3D0922E
,2017-07-21 08:00:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:00:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 276 discoveryActive matches
,ok 277 advertisingActive matches
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:00:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:00:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:00:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 08:00:03 - DEBUG thaliMobileNativeWrapper: 'listening 57188'
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:00:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:00:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:00:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:00:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:00:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 278 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:00:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:00:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:00:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:00:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:00:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:00:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:00:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:00:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:00:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:00:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:00:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:00:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS
,2017-07-21 08:00:04 - DEBUG thaliMobileNativeWrapper: 'listening 57189'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:39C1867F-0A2B-41B7-84AA-90202E42E1C1
[ThaliCore] Browser.startListening
2017-07-21 08:00:04 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 08:00:04 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:00:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserM,anager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "23DBF6D0-7004-462A-A8F2-AF058BA9B92F", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:23DBF6D0-7004-462A-A8F2-AF058BA9B92F
2017-07-21 08:00:04 - DEBUG thaliM,o,bileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 08:00:04 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started",:false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:00:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C7BBE235-3DD4-43E3-BA80-A3BA3281F60E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C7BBE235-3DD4-43E3-BA80-A3BA3281F60E", generation: 0)
,2017-07-21 08:00:05 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"C7BBE235-3DD4-43E3-BA80-A3BA3281F60E","generation":0}]'
[ThaliCore] Browser.browser(_:foundPeer:withDi,scoveryInfo:) found peer:BFCB2BCD-C807-439B-8959-5A1DEF10A145:0
2017-07-21 08:00:05 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"C7BBE235-3DD4-43E3-BA80-A3BA3281F60E","generation",:0}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BFCB2BCD-C807-439B-8959-5A1DEF10A145", generation: 0)
,2017-07-21 08:00:05 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"C7BBE235-3DD4-43E3-BA80-A3BA3281F60E","peerAvailable":true,"generation":0,"portNumber":null}'
ok 279 portNumber equal null
,# teardown
,2017-07-21 08:00:05 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"BFCB2BCD-C807-439B-8959-5A1DEF10A145","generation":0}]'
,2017-07-21 08:00:05 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"BFCB2BCD-C807-439B-8959-5A1DEF10A145","generation":0}'
,2017-07-21 08:00:05 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"BFCB2BCD-C807-439B-8959-5A1DEF10A145","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1A8CD3A1-17EC-4D75-ACC9-498530804876:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1A8CD3A1-17EC-4D75-ACC9-498530804876", generation: 0)
,2017-07-21 08:00:05 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"1A8CD3A1-17EC-4D75-ACC9-498530804876","generation":0}]'
2017-07-21 08:00:05 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"1A8CD3A1-17EC-4D75-ACC9-498530804876","generation":0}'
,2017-07-21 08:00:05 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"1A8CD3A1-17EC-4D75-ACC9-498530804876","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 08:00:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1A8CD3A1-17EC-4D75-ACC9-498530804876","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:23DBF6D0-7004-462A-A8F2-AF058BA9B92F
,2017-07-21 08:00:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 08:00:05 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 08:00:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-21 08:00:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:00:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:00:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 280 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:00:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:00:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:00:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:00:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:00:05 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:00:05 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:00:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:00:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:00:05 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:00:05 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:00:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:00:05 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can do HTTP requests between peers
,2017-07-21 08:00:06 - DEBUG CoordinatedClient: 'test was skipped, name: 'can do HTTP requests between peers''
,# teardown
,ok 281 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:00:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:00:10 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:00:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 08:00:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:00:10 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:00:10 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:00:10 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:00:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:00:10 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:00:10 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:00:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:00:10 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can still do HTTP requests between peers with coordinator
,2017-07-21 08:00:10 - DEBUG CoordinatedClient: 'test was skipped, name: 'can still do HTTP requests between peers with coordinator''
,# teardown
,ok 282 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:00:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:00:11 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:00:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 08:00:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:00:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:00:11 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:00:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:00:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:00:11 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:00:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:00:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:00:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calls correct starts when network changes
,2017-07-21 08:00:11 - DEBUG CoordinatedClient: 'test was skipped, name: 'calls correct starts when network changes''
,# teardown
,ok 283 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:00:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:00:12 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:00:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 08:00:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:00:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:00:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:00:12 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:00:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:00:12 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:00:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:00:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:00:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# test to coordinate connection cut
,# teardown
,ok 284 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:00:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:00:12 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:00:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 08:00:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:00:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:00:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:00:12 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:00:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:00:12 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:00:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:00:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:00:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can do HTTP requests after connections are cut
,2017-07-21 08:00:13 - DEBUG thaliMobileNativeWrapper: 'listening 57191'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:DABCA13C-E1C4-4520-9ABE-F4325694BB8C
,[ThaliCore] Browser.startListening
,2017-07-21 08:00:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 08:00:13 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-21 08:00:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "9476F58F-47F8-4A4C-A0A0-0319CEDF586F", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:9476F58F-47F8-4A4C-A0A0-0319CEDF586F
,2017-07-21 08:00:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 08:00:13 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:00:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C7BBE235-3DD4-43E3-BA80-A3BA3281F60E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C7BBE235-3DD4-43E3-BA80-A3BA3281F60E", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:BFCB2BCD-C807-439B-8959-5A1DEF10A145:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BFCB2BCD-C807-439B-8959-5A1DEF10A145", generation: 0)
,2017-07-21 08:00:13 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"C7BBE235-3DD4-43E3-BA80-A3BA3281F60E","generation":0}]'
,2017-07-21 08:00:13 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"C7BBE235-3DD4-43E3-BA80-A3BA3281F60E","generation":0}'
,2017-07-21 08:00:13 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"BFCB2BCD-C807-439B-8959-5A1DEF10A145","generation":0}]'
,2017-07-21 08:00:13 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"BFCB2BCD-C807-439B-8959-5A1DEF10A145","generation":0}'
,2017-07-21 08:00:13 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"C7BBE235-3DD4-43E3-BA80-A3BA3281F60E","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 08:00:13 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"C7BBE235-3DD4-43E3-BA80-A3BA3281F60E","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 08:00:13 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for C7BBE235-3DD4-43E3-BA80-A3BA3281F60E (syncValue: vvX5IoIJwkiy9aDVnuQbVAcE2fvWpGsx)'
,2017-07-21 08:00:13 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C7BBE235-3DD4-43E3-BA80-A3BA3281F60E", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C7BBE235-3DD4-43E3-BA80-A3BA3281F60E", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C7BBE235-3DD4-43E3-BA80-A3BA3281F60E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,2017-07-21 08:00:13 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"BFCB2BCD-C807-439B-8959-5A1DEF10A145","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 08:00:13 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"BFCB2BCD-C807-439B-8959-5A1DEF10A145","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C09A6A8E-EFDE-48EC-84E1-789AFE3A33B1:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C09A6A8E-EFDE-48EC-84E1-789AFE3A33B1", generation: 0)
,2017-07-21 08:00:14 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"C09A6A8E-EFDE-48EC-84E1-789AFE3A33B1","generation":0}]'
2017-07-21 08:00:14 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"C09A6A8E-EFDE-48EC-84E1-789AFE3A33B1","generation":0}'
,2017-07-21 08:00:14 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"C09A6A8E-EFDE-48EC-84E1-789AFE3A33B1","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 08:00:14 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"C09A6A8E-EFDE-48EC-84E1-789AFE3A33B1","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 08:00:14 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"C09A6A8E-EFDE-48EC-84E1-789AFE3A33B1","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9476F58F-47F8-4A4C-A0A0-0319CEDF586F:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9476F58F-47F8-4A4C-A0A0-0319CEDF586F", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7ACAA28D-9E95-4685-A1D8-2D2948F6818A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7ACAA28D-9E95-4685-A1D8-2D2948F6818A", generation: 0)
2017-07-21 08:00:14 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"7ACAA28D-9E95-4685-A1D8-2D2948F6818A","generation":0}]'
2017-07-21 08:00:14 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"7ACAA28D-9E95-4685-A1D8-2D2948F6818A","generation":0}'
,2017-07-21 08:00:14 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"7ACAA28D-9E95-4685-A1D8-2D2948F6818A","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 08:00:14 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7ACAA28D-9E95-4685-A1D8-2D2948F6818A","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 08:00:14 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"7ACAA28D-9E95-4685-A1D8-2D2948F6818A","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:C7BBE235-3DD4-43E3-BA80-A3BA3281F60E:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:C7,BBE235-3DD4-43E3-BA80-A3BA3281F60E:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "C7BBE235-3DD4-43E3-BA80-A3BA3281F60E", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C,7BBE235-3DD4-43E3-BA80-A3BA3281F60E", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C7BBE235-3DD4-43E3-BA80-A3BA3281F60E", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:C7BBE235-3DD4-43E3-BA80-A3BA3281F60E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:C7BBE235-3DD4-43E3-BA80-A3BA3281F60E:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:C7BBE235-3DD4-43E3-BA80-A3BA3281F60E:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:C7,BBE235-3DD4-43E3-BA80-A3BA3281F60E:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "C7BBE235-3DD4-43E3-BA80-A3BA3281F60E", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C,7BBE235-3DD4-43E3-BA80-A3BA3281F60E", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C7BBE235-3DD4-43E3-BA80-A3BA3281F60E", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:C7BBE235-3DD4-43E3-BA80-A3BA3281F60E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:C7BBE235-3DD4-43E3-BA80-A3BA3281F60E:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:BFCB2BCD-C807-439B-8959-5A1DEF10A145:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "BFCB2BCD-C807-439B-8959-5A1DEF10A145", generation: 0)
2017-07-21 08:00:20 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"BFCB2BCD-C807-439B-8959-5A1DEF10A145","generation":0}]'
2017-07-21 08:00:20 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"BFCB2BCD-C807-439B-8959-5A1DEF10A145","generation":0}'
,2017-07-21 08:00:20 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"BFCB2BCD-C807-439B-8959-5A1DEF10A145","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-21 08:00:20 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"BFCB2BCD-C807-439B-8959-5A1DEF10A145","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:C7BBE235-3DD4-43E3-BA80-A3BA3281F60E:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:C7,BBE235-3DD4-43E3-BA80-A3BA3281F60E:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "C7BBE235-3DD4-43E3-BA80-A3BA3281F60E", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C,7BBE235-3DD4-43E3-BA80-A3BA3281F60E", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C7BBE235-3DD4-43E3-BA80-A3BA3281F60E", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:C7BBE235-3DD4-43E3-BA80-A3BA3281F60E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:C7BBE235-3DD4-43E3-BA80-A3BA3281F60E:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:BCE26EE8-3CFC-48D6-AB96-3A21F7FD9086
[ThaliCore] Advertiser: session connected Peer(uuid: "9476F58F-47F8-4A4C-A0A0-0319CEDF586F", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:BCE26EE8-3CFC-48D6-AB96-3A21F7FD9086 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:C7BBE235-3DD4-43E3-BA80-A3BA3281F60E:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:C7,BBE235-3DD4-43E3-BA80-A3BA3281F60E:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "C7BBE235-3DD4-43E3-BA80-A3BA3281F60E", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:C7BBE235,-3DD4-43E3-BA80-A3BA3281F60E error: max retries exceeded
2017-07-21 08:00:24 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"vvX5IoIJwkiy9aDVnuQbVAcE2fvWpGsx","error":"Connection could not be established","portNumber":null}'
2017-0,7-21 08:00:24 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'vvX5IoIJwkiy9aDVnuQbVAcE2fvWpGsx', error: 'Connection could not be established', listeningPort: '%s''
,2017-07-21 08:00:24 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"C7BBE235-3DD4-43E3-BA80-A3BA3281F60E","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-21 08:00:24 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"C7BBE235-3DD4-43E3-BA80-A3BA3281F60E","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-21 08:00:24 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"C7BBE235-3DD4-43E3-BA80-A3BA3281F60E","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-21 08:00:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"C7BBE235-3DD4-43E3-BA80-A3BA3281F60E","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-21 08:00:24 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"C7BBE235-3DD4-43E3-BA80-A3BA3281F60E","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-21 08:00:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"C7BBE235-3DD4-43E3-BA80-A3BA3281F60E","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 08:00:24 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"C7BBE235-3DD4-43E3-BA80-A3BA3281F60E","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-21 08:00:24 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-21 08:00:24 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for C09A6A8E-EFDE-48EC-84E1-789AFE3A33B1 (syncValue: oEZs3Nk87xCJTqRdesHyRk2G5FoYygSG)'
,2017-07-21 08:00:24 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C09A6A8E-EFDE-48EC-84E1-789AFE3A33B1", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C09A6A8E-EFDE-48EC-84E1-789AFE3A33B1", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C09A6A8E-EFDE-48EC-84E1-789AFE3A33B1:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:C7BBE235-3DD4-43E3-BA80-A3BA3281F60E:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:C09A6A8E-EFDE-48EC-84E1-789AFE3A33B1:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:BCE26EE8-3CFC-48D6-AB96-3A21F7FD9086
,[ThaliCore] Session.session(_:peer:didChange:) peer:BCE26EE8-3CFC-48D6-AB96-3A21F7FD9086 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:BCE26EE8-3CFC-48D6-AB96-3A21F7FD9086
,[ThaliCore] Session.startOutputStream(with:) peer:BCE26EE8-3CFC-48D6-AB96-3A21F7FD9086
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:11 [11]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:C09A6A8E-EFDE-48EC-84E1-789AFE3A33B1:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:C09A6A8E-EFDE-48EC-84E1-789AFE3A33B1:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "C09A6A8E-EFDE-48EC-84E1-789AFE3A33B1", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57203
,2017-07-21 08:00:27 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"oEZs3Nk87xCJTqRdesHyRk2G5FoYygSG","error":null,"portNumber":57203}'
,2017-07-21 08:00:27 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'oEZs3Nk87xCJTqRdesHyRk2G5FoYygSG', error: 'null', listeningPort: '57203''
,2017-07-21 08:00:27 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:C09A6A8E-EFDE-48EC-84E1-789AFE3A33B1:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C09A6A8E-EFDE-48EC-84E1-789AFE3A33B1:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:12 [11, 12]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-21 08:00:27 - DEBUG testUtils: 'Got response data'
,2017-07-21 08:00:27 - DEBUG testUtils: 'Got end'
,ok 285 response body should match testData
,ok 286 must be started
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:9476F58F-47F8-4A4C-A0A0-0319CEDF586F
2017-07-21 08:00:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-07-21 08:00:27 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:00:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stop,Listening()
2017-07-21 08:00:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:00:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,stopped state).'
2017-07-21 08:00:27 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 287 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:00:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:00:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:00:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:00:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:11
[ThaliCore] VirtualSocket.closeStreams() vsID:11
[ThaliCore] BrowserManager.disconnect peer:C09A6A8E-EFDE-48EC-84E1-789AFE3A33B1
[ThaliCore] Session.session(_:peer:didChange:) pee,r:BCE26EE8-3CFC-48D6-AB96-3A21F7FD9086 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:57203
[ThaliCore] VirtualSocket.closeStreams() v,sID:12
[ThaliCore] Advertiser: session notConnected Peer(uuid: "9476F58F-47F8-4A4C-A0A0-0319CEDF586F", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] VirtualSocket.handleEventO,nInputStream streams are closed
[ThaliCore] VirtualSocket.closeStreams() vsID:11
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:true socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPCl,ient.deinit
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed,, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:true
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:BCE26EE8-3CFC-4,8D6-AB96-3A21F7FD9086
[ThaliCore] AdvertiserRelay.deinit
[ThaliCore] VirtualSocket exited RunLoop vsID:11
[ThaliCore] VirtualSocket.deinit vsID:11 [12]
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] Virtua,lSocket exited RunLoop vsID:12
[ThaliCore] Session.disconnect() peer:C09A6A8E-EFDE-48EC-84E1-789AFE3A33B1:0
[ThaliCore] VirtualSocket.closeStreams() vsID:12
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] Vi,rtualSocket.deinit vsID:12 []
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:BCE26EE8-3CFC-48D6-AB96-3A21F7FD9086
[ThaliCore] Session.deinit peer:C09A6A8E-EFDE-48EC-84E1-789AFE3A33B1:0
[ThaliCore] BrowserRelay.deinit
2017-07-21 08:00:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityCha,nged registered to native'
2017-07-21 08:00:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:00:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native',
,2017-07-21 08:00:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 08:00:28 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 08:00:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 08:00:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 08:00:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# will fail bad PSK connection between peers
,ok 288 FIX ME, PLEASE!!!
,# teardown
,ok 289 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:00:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:00:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:00:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:00:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:00:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:00:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:00:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:00:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:00:28 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:00:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:00:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:00:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We provide notification when a listener dies and we recreate it
,2017-07-21 08:00:29 - DEBUG CoordinatedClient: 'test was skipped, name: 'We provide notification when a listener dies and we recreate it''
,# teardown
,ok 290 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:00:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:00:29 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:00:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 08:00:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:00:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:00:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:00:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:00:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:00:29 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:00:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:00:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:00:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated
,2017-07-21 08:00:29 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated''
,# teardown
,ok 291 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:00:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:00:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:00:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:00:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:00:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:00:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:00:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:00:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:00:29 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:00:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:00:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:00:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,ok 292 ThaliMobile should be stopped
,# #startListeningForAdvertisements should fail if start not called
,ok 293 specific error should be returned
,# teardown
,2017-07-21 08:00:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"C7BBE235-3DD4-43E3-BA80-A3BA3281F60E","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-21 08:00:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"1A8CD3A1-17EC-4D75-ACC9-498530804876","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-21 08:00:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"C09A6A8E-EFDE-48EC-84E1-789AFE3A33B1","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-21 08:00:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"7ACAA28D-9E95-4685-A1D8-2D2948F6818A","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 294 error should be null
,ok 295 error should be null
,# setup
,ok 296 ThaliMobile should be stopped
,# #startUpdateAdvertisingAndListening should fail if start not called
,ok 297 specific error should be returned
,# teardown
,ok 298 error should be null
,ok 299 error should be null
,# setup
,ok 300 ThaliMobile should be stopped
,# should be able to call #stopListeningForAdvertisements many times
,2017-07-21 08:00:30 - DEBUG thaliMobileNativeWrapper: 'listening 57205'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:00:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 301 error should be null
,ok 302 error should be null
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:00:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 303 error should be null
,ok 304 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:00:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:00:30 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:00:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 08:00:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 08:00:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 305 error should be null
ok 306 error should be null
,# setup
,ok 307 ThaliMobile should be stopped
,# should be able to call #startListeningForAdvertisements many times
,2017-07-21 08:00:31 - DEBUG thaliMobileNativeWrapper: 'listening 57206'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:FA170C96-1368-4C42-82C2-E116E2BFD230
,[ThaliCore] Browser.startListening
,2017-07-21 08:00:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,ok 308 error should be null
ok 309 error should be null
,[ThaliCore] BrowserManager.startListeningForAdvertisements
2017-07-21 08:00:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,ok 310 error should be null
,ok 311 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:00:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 08:00:31 - INFO thaliMobile: 'Received state ({"d,iscoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
2017-07-21 08:00:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateU,pdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 08:00:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advert,isingActive":false}'
2017-07-21 08:00:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:00:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 312 error should be null
,ok 313 error should be null
,# setup
,ok 314 ThaliMobile should be stopped
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-07-21 08:00:31 - DEBUG thaliMobileNativeWrapper: 'listening 57207'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "78ADC02D-4229-4565-9B51-3F2C9371FF9A", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:78ADC02D-4229-4565-9B51-3F2C9371FF9A
,2017-07-21 08:00:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,ok 315 error should be null
,ok 316 error should be null
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "78ADC02D-4229-4565-9B51-3F2C9371FF9A", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:78ADC02D-4229-4565-9B51-3F2C9371FF9A
,2017-07-21 08:00:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,ok 317 error should be null
,ok 318 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:78ADC02D-4229-4565-9B51-3F2C9371FF9A
,[ThaliCore] Advertiser.stopAdvertising() peerID:78ADC02D-4229-4565-9B51-3F2C9371FF9A
,2017-07-21 08:00:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:00:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:00:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:00:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:00:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 319 error should be null
,ok 320 error should be null
,# setup
,ok 321 ThaliMobile should be stopped
,# should be able to call #stopAdvertisingAndListening many times
,2017-07-21 08:00:32 - DEBUG thaliMobileNativeWrapper: 'listening 57210'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:00:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 322 error should be null
,ok 323 error should be null
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:00:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 324 error should be null
,ok 325 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:00:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:00:32 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:00:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 08:00:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 08:00:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 326 error should be null
ok 327 error should be null
,# setup
,ok 328 ThaliMobile should be stopped
,# #start - Causing native or wifi to fail will cause a promise reject 
,2017-07-21 08:00:32 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a Null'
,ok 329 This should not cause wifi to fail
,ok 330 native router should be bad
,# teardown
,ok 331 error should be null
,ok 332 error should be null
,# setup
,ok 333 ThaliMobile should be stopped
,# #start should fail if called twice in a row
,2017-07-21 08:00:33 - DEBUG thaliMobileNativeWrapper: 'listening 57211'
,ok 334 first call should succeed
,ok 335 first call should succeed
,ok 336 specific error should be returned
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:00:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:00:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:00:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:00:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:00:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 337 error should be null
,ok 338 error should be null
,# setup
,ok 339 ThaliMobile should be stopped
,# #start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)
,2017-07-21 08:00:33 - DEBUG CoordinatedClient: 'test was skipped, name: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''
,# teardown
,ok 340 error should be null
ok 341 error should be null
,# setup
,ok 342 ThaliMobile should be stopped
,# does not emit duplicate discoveryAdvertisingStateUpdate
,2017-07-21 08:00:33 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not emit duplicate discoveryAdvertisingStateUpdate''
,# teardown
,ok 343 error should be null
,ok 344 error should be null
,# setup
,ok 345 ThaliMobile should be stopped
,# does not send duplicate availability changes
,2017-07-21 08:00:34 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5f3e1d1b-3465-43ac-a5ea-c541c569942b","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 346 should be called once
,ok 347 should not have been called more than once
,# teardown
,2017-07-21 08:00:34 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"5f3e1d1b-3465-43ac-a5ea-c541c569942b","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 348 error should be null
,ok 349 error should be null
,# setup
,ok 350 ThaliMobile should be stopped
,# can get the network status
,ok 351 network status should have certain non-empty properties
,# teardown
,ok 352 error should be null
ok 353 error should be null
,# setup
,ok 354 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer added/removed to/from cache (native)
,ok 355 we have not added peer to the cache yet
2017-07-21 08:00:34 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"fbb902c6-86e0-4f89-88e6-b7d2d505f954","connectionType":"MPCF","peerAvailable":true,"generation":0,,"newAddressPort":false}'
ok 356 peer should be available
ok 357 cache contains native peer
2017-07-21 08:00:34 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"fbb902c6-86e0-4f89-88e6-b7d2d505f954","connectionTyp,e":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
ok 358 peer should be unavailable
ok 359 peer has been removed from cache
,# teardown
,ok 360 error should be null
,ok 361 error should be null
,# setup
,ok 362 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer added/removed to/from cache (wifi)
,ok 363 we have not added peer to the cache yet
,2017-07-21 08:00:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9de9f998-5c02-4c6b-abfb-19f98f9845f2","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 364 peer should be available
,ok 365 cache contains wifi peer
,2017-07-21 08:00:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9de9f998-5c02-4c6b-abfb-19f98f9845f2","connectionType":"tcp","peerAvailable":false,"generation":0,"newAddressPort":null}'
,ok 366 peer should be unavailable
,ok 367 peer has been removed from cache
,# teardown
,ok 368 error should be null
,ok 369 error should be null
,# setup
,ok 370 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored
,2017-07-21 08:00:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"00c9aa4e-5a1e-435c-8222-5e473530f193","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 371 first peer is available
,2017-07-21 08:00:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"bb0a5870-a117-4c4e-81ec-4e469acf05ed","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 372 second peer is available
,ok 373 first and second peers are different
,# teardown
,2017-07-21 08:00:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"00c9aa4e-5a1e-435c-8222-5e473530f193","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-21 08:00:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"bb0a5870-a117-4c4e-81ec-4e469acf05ed","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 374 error should be null
,ok 375 error should be null
,# setup
,ok 376 ThaliMobile should be stopped
,# native available - new peer is cached
,ok 377 should not be in cache at start
2017-07-21 08:00:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"55510a49-a570-4453-b825-33562241f63b","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 378 peer is available
,# teardown
,2017-07-21 08:00:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"55510a49-a570-4453-b825-33562241f63b","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 379 error should be null
,ok 380 error should be null
,# setup
,ok 381 ThaliMobile should be stopped
,# native available - peer with same port and different generation is cached (BLUETOOTH)
,2017-07-21 08:00:35 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with same port and different generation is cached (BLUETOOTH)''
,# teardown
,ok 382 error should be null
ok 383 error should be null
,# setup
,ok 384 ThaliMobile should be stopped
,# native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)
,2017-07-21 08:00:36 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)''
,# teardown
,ok 385 error should be null
,ok 386 error should be null
,# setup
,ok 387 ThaliMobile should be stopped
,# native available - peer with greater generation is cached (MPCF)
,2017-07-21 08:00:36 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"8818fd5f-6d34-4144-95c9-03e554b9f640","connectionType":"MPCF","peerAvailable":true,"generation":2,"newAddressPort":false}'
ok 388 peer should be available
,2017-07-21 08:00:36 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"8818fd5f-6d34-4144-95c9-03e554b9f640","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
ok 389 peer should be ,available
ok 390 should store correct generation
,# teardown
,2017-07-21 08:00:36 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"8818fd5f-6d34-4144-95c9-03e554b9f640","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 391 error should be null
ok 392 error should be null
,# setup
,ok 393 ThaliMobile should be stopped
,# native available - peer with same or older generation is ignored (MPCF)
,2017-07-21 08:00:37 - DEBUG thaliMobileNativeWrapper: 'listening 57212'
2017-07-21 08:00:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"72a16753-ed08-44ef-9d7f-a6b8b37710cc","connectionType":"MPCF","peerAvaila,ble":true,"generation":2,"newAddressPort":false}'
ok 394 discovered correct peer
ok 395 got correct generation
,2017-07-21 08:00:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"72a16753-ed08-44ef-9d7f-a6b8b37710cc","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
ok 396 discovered corr,ect peer
ok 397 got correct generation
,# teardown
,2017-07-21 08:00:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"72a16753-ed08-44ef-9d7f-a6b8b37710cc","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:00:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:00:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:00:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:00:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:00:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 398 error should be null
,ok 399 error should be null
,# setup
,ok 400 ThaliMobile should be stopped
,# native unavailable - new peer is ignored
,2017-07-21 08:00:37 - DEBUG thaliMobileNativeWrapper: 'listening 57213'
,2017-07-21 08:00:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"26f5f233-5d57-48f1-bf74-3827b6bd8fba","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 401 discovered available peer
,ok 402 peer is available
,# teardown
,2017-07-21 08:00:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"26f5f233-5d57-48f1-bf74-3827b6bd8fba","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:00:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:00:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:00:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:00:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:00:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 403 error should be null
,ok 404 error should be null
,# setup
,ok 405 ThaliMobile should be stopped
,# native unavailable - cached peer is removed
,2017-07-21 08:00:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"d5e314b3-aba9-439f-9020-218dd1371078","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 406 peer should be ,available
2017-07-21 08:00:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"d5e314b3-aba9-439f-9020-218dd1371078","connectionType":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
ok 407 peer, should be unavailable
ok 408 should be removed from cache
,# teardown
,ok 409 error should be null
,ok 410 error should be null
,# setup
,ok 411 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for wifi peers
,2017-07-21 08:00:38 - DEBUG thaliMobileNativeWrapper: 'listening 57214'
2017-07-21 08:00:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"c4ccbad2-3608-4af1-8ee7-7efc5ea29430","connectionType":"MPCF","peerAvaila,ble":true,"generation":0,"newAddressPort":false}'
ok 412 first peer is expected to be available
2017-07-21 08:00:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"d734d896-fa24-4af4-afbf-48d8a0250888","connectio,nType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 413 second peer is expected to be available
2017-07-21 08:00:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"d734d896-fa24-,4af4-afbf-48d8a0250888","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 414 peer became unavailable
ok 415 it was wifi peer
,2017-07-21 08:00:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"d734d896-fa24-4af4-afbf-48d8a0250888","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 416 we found peer again
,ok 417 it was wifi peer
,2017-07-21 08:00:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"d734d896-fa24-4af4-afbf-48d8a0250888","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 418 peer became unavailable
,ok 419 it was wifi peer
,# teardown
,2017-07-21 08:00:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"c4ccbad2-3608-4af1-8ee7-7efc5ea29430","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:00:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:00:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:00:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:00:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:00:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 420 error should be null
,ok 421 error should be null
,# setup
,ok 422 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)
,2017-07-21 08:00:38 - DEBUG CoordinatedClient: 'test was skipped, name: 'networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)''
,# teardown
,ok 423 error should be null
ok 424 error should be null
,# setup
,ok 425 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)
,2017-07-21 08:00:39 - DEBUG thaliMobileNativeWrapper: 'listening 57215'
2017-07-21 08:00:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"be53d101-d63b-4b5e-9835-63364603f7c5","connectionType":"MPCF","peerAvaila,ble":true,"generation":0,"newAddressPort":false}'
ok 426 first peer is expected to be available
2017-07-21 08:00:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"3015d619-c91a-43be-977b-a0c457b94f42","connectio,nType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 427 second peer is expected to be available
,2017-07-21 08:00:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"be53d101-d63b-4b5e-9835-63364603f7c5","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 428 peer became unavailable
,2017-07-21 08:00:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"3015d619-c91a-43be-977b-a0c457b94f42","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 429 peer became unavailable
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:00:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:00:39 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:00:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:00:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:00:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 430 error should be null
,ok 431 error should be null
,# setup
,ok 432 ThaliMobile should be stopped
,# multiconnect failure - new peer is ignored (MPCF)
,2017-07-21 08:00:39 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - new peer is ignored (MPCF)''
,# teardown
,ok 433 error should be null
,ok 434 error should be null
,# setup
,ok 435 ThaliMobile should be stopped
,# multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)
,2017-07-21 08:00:39 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''
,# teardown
,ok 436 error should be null
,ok 437 error should be null
,# setup
,ok 438 ThaliMobile should be stopped
,# newAddressPort field (TCP_NATIVE)
,2017-07-21 08:00:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5aa43a04-1031-4114-aead-3ddf281daafa","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 439 peer discovered first time does not have new address
,2017-07-21 08:00:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5aa43a04-1031-4114-aead-3ddf281daafa","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddressPort":false}'
,ok 440 address has not been changed
,2017-07-21 08:00:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5aa43a04-1031-4114-aead-3ddf281daafa","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddressPort":true}'
,ok 441 new port handled correctly
,2017-07-21 08:00:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5aa43a04-1031-4114-aead-3ddf281daafa","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddressPort":true}'
,ok 442 new host handled correctly
,2017-07-21 08:00:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5aa43a04-1031-4114-aead-3ddf281daafa","connectionType":"tcp","peerAvailable":false,"generation":20,"newAddressPort":null}'
,ok 443 newAddressPort is null for unavailable peers
,# teardown
,ok 444 error should be null
,ok 445 error should be null
,# setup
,ok 446 ThaliMobile should be stopped
,# newAddressPort field (BLUETOOTH)
,2017-07-21 08:00:40 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort field (BLUETOOTH)''
,# teardown
,ok 447 error should be null
,ok 448 error should be null
,# setup
,ok 449 ThaliMobile should be stopped
,# newAddressPort field (MPCF)
,ok 450 NOT IMPLEMENTED # SKIP
,# teardown
,ok 451 error should be null
ok 452 error should be null
,# setup
,ok 453 ThaliMobile should be stopped
,# newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)
,2017-07-21 08:00:40 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)''
,# teardown
,ok 454 error should be null
ok 455 error should be null
,# setup
,ok 456 ThaliMobile should be stopped
,# #getPeerHostInfo - error when peer has not been discovered yet
,ok 457 should be equal
,# teardown
,ok 458 error should be null
ok 459 error should be null
,# setup
,ok 460 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)
,2017-07-21 08:00:40 - DEBUG CoordinatedClient: 'test was skipped, name: '#getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)''
,# teardown
,ok 461 error should be null
ok 462 error should be null
,# setup
,ok 463 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)
,2017-07-21 08:00:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 464 contains expected properties
ok 465 the same hostAddress
ok 466 the same portNumber
,# teardown
,2017-07-21 08:00:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 467 error should be null
,ok 468 error should be null
,# setup
,ok 469 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached wifi peer
,2017-07-21 08:00:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 470 contains expected properties
,ok 471 the same hostAddress
,ok 472 the same portNumber
,# teardown
,2017-07-21 08:00:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 473 error should be null
,ok 474 error should be null
,# setup
,ok 475 ThaliMobile should be stopped
,# #disconnect fails on wifi peers
,2017-07-21 08:00:41 - DEBUG thaliMobileNativeWrapper: 'listening 57216'
,2017-07-21 08:00:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"dfc8639e-cf14-4b40-b8ce-1876b1e84d34","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 476 Got specific error message
,# teardown
,2017-07-21 08:00:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"dfc8639e-cf14-4b40-b8ce-1876b1e84d34","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:00:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:00:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:00:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:00:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:00:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 477 error should be null
,ok 478 error should be null
,# setup
,ok 479 ThaliMobile should be stopped
,# #disconnect delegates native peers to the native wrapper
,2017-07-21 08:00:41 - DEBUG thaliMobileNativeWrapper: 'listening 57217'
,2017-07-21 08:00:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"cc0532c8-4e8e-4782-aed2-82905ebaa1c6","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] BrowserManager.disconnect peer:cc0532c8-4e8e-4782-aed2-82905ebaa1c6
,ok 480 native wrapper `disconnect` called once
,ok 481 native wrapper `disconnect` called with peer data
,# teardown
,2017-07-21 08:00:42 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"cc0532c8-4e8e-4782-aed2-82905ebaa1c6","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:00:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:00:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:00:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:00:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:00:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 482 error should be null
,ok 483 error should be null
,# setup
,ok 484 ThaliMobile should be stopped
,# network changes emitted correctly
,2017-07-21 08:00:42 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes emitted correctly''
,# teardown
,ok 485 error should be null
ok 486 error should be null
,# setup
,ok 487 ThaliMobile should be stopped
,# network changes not emitted in started state
,2017-07-21 08:00:42 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes not emitted in started state''
,# teardown
,ok 488 error should be null
,ok 489 error should be null
,# setup
,ok 490 ThaliMobile should be stopped
,# network changes not emitted in stopped state
,2017-07-21 08:00:43 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes not emitted in stopped state''
,# teardown
,ok 491 error should be null
,ok 492 error should be null
,# setup
,ok 493 ThaliMobile should be stopped
,# We properly fire peer unavailable and then available when connection fails on Android
,2017-07-21 08:00:43 - DEBUG CoordinatedClient: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on Android''
,# teardown
,ok 494 error should be null
ok 495 error should be null
,# setup
,ok 496 ThaliMobile should be stopped
,# We properly fire peer unavailable and then available when connection fails on iOS
,2017-07-21 08:00:43 - DEBUG CoordinatedClient: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on iOS''
,# teardown
,ok 497 error should be null
,ok 498 error should be null
,# setup
,ok 499 ThaliMobile should be stopped
,# If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen
,2017-07-21 08:00:44 - DEBUG CoordinatedClient: 'test was skipped, name: 'If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen''
,# teardown
,ok 500 error should be null
ok 501 error should be null
,# setup
,ok 502 ThaliMobile should be stopped
,# does not fire duplicate events after peer listener recreation
,2017-07-21 08:00:44 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not fire duplicate events after peer listener recreation''
,# teardown
,ok 503 error should be null
,ok 504 error should be null
,# setup
,ok 505 ThaliMobile should be stopped
,# #stop should change peers
,2017-07-21 08:00:44 - DEBUG thaliMobileNativeWrapper: 'listening 57218'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:82E0433D-FAE8-43BC-A4D5-19D4C34FAA9B
,[ThaliCore] Browser.startListening
,2017-07-21 08:00:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 08:00:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"71704f92-5ef9-40aa-a5e1-019875802ac5","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 506 Peer availabilities has one entry for our connection type
,2017-07-21 08:00:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"0aea7ede-cf7d-494e-b8ef-0290885ec1f1","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 507 Peer availabilities has one entry for our connection type
,2017-07-21 08:00:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"71704f92-5ef9-40aa-a5e1-019875802ac5","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-21 08:00:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"0aea7ede-cf7d-494e-b8ef-0290885ec1f1","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:00:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 08:00:44 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"pskIdToSecret":[102,111,111],"networkType":"BOTH"}})'
,2017-07-21 08:00:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 08:00:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:00:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:00:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 08:00:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 508 No peers
,ok 509 No peers
,ok 510 No peers
,# teardown
,ok 511 error should be null
,ok 512 error should be null
,# setup
,ok 513 ThaliMobile should be stopped
,# If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted
,2017-07-21 08:00:45 - DEBUG thaliMobileNativeWrapper: 'listening 57219'
,2017-07-21 08:00:45 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1e5148cd-60ca-42af-8d70-29049e68b4b1","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 514 1
,ok 515 2
,2017-07-21 08:00:45 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"27d4b279-60c2-4067-ae2a-b8b3c0456f50","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,# teardown
,2017-07-21 08:00:45 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"1e5148cd-60ca-42af-8d70-29049e68b4b1","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-21, 08:00:45 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"27d4b279-60c2-4067-ae2a-b8b3c0456f50","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore] Advertis,erManager.stopAdvertising()
2017-07-21 08:00:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:00:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingState,Update (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:00:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:00:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 08:00:45 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 516 error should be null
,ok 517 error should be null
,# setup
,ok 518 ThaliMobile should be stopped
,# peer should be found once after listening and discovery started
,2017-07-21 08:00:45 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer should be found once after listening and discovery started''
,# teardown
,ok 519 error should be null
,ok 520 error should be null
,# setup
,ok 521 ThaliMobile should be stopped
,# can get data from all participants
,2017-07-21 08:00:45 - DEBUG thaliMobileNativeWrapper: 'listening 57220'
ok 522 error should be null
,ok 523 error should be null
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C39D4A68-9FE6-420E-91C5-1FF6CE30E22A", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:C39D4A68-9FE6-420E-91,C5-1FF6CE30E22A
2017-07-21 08:00:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,ok 524 error should be null
ok 525 error should be null
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:B17D840B-525A-43E7-8097-00BD8B450B10
[ThaliCore] Browser.startListening
,2017-07-21 08:00:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,ok 526 error should be null
,ok 527 error should be null
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C7BBE235-3DD4-43E3-BA80-A3BA3281F60E:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C7BBE235-3DD4-43E3-BA80-A3BA3281F60E", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1AEB318D-F436-4ED2-92B3-8595DFA2FFED:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1AEB318D-F436-4ED2-92B3-8595DFA2FFED", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:CE14C433-882F-4790-BE2A-EEC0450765EB:0
2017-07-21 08:00:47 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"C7BBE235-3DD4-43E3-BA,80-A3BA3281F60E","generation":0}]'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CE14C433-882F-4790-BE2A-EEC0450765EB", generation: 0)
,2017-07-21 08:00:47 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"C7BBE235-3DD4-43E3-BA80-A3BA3281F60E","generation":0}'
,2017-07-21 08:00:47 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"1AEB318D-F436-4ED2-92B3-8595DFA2FFED","generation":0}]'
2017-07-21 08:00:47 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"1AEB318D-F436-4ED2-92B3-8595DFA2FFED","generation":0}'
,2017-07-21 08:00:47 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"CE14C433-882F-4790-BE2A-EEC0450765EB","generation":0}]'
,2017-07-21 08:00:47 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"CE14C433-882F-4790-BE2A-EEC0450765EB","generation":0}'
,2017-07-21 08:00:47 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"C7BBE235-3DD4-43E3-BA80-A3BA3281F60E","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 08:00:47 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"C7BBE235-3DD4-43E3-BA80-A3BA3281F60E","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 08:00:47 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"1AEB318D-F436-4ED2-92B3-8595DFA2FFED","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 08:00:47 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1AEB318D-F436-4ED2-92B3-8595DFA2FFED","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 08:00:47 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"CE14C433-882F-4790-BE2A-EEC0450765EB","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 08:00:47 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"CE14C433-882F-4790-BE2A-EEC0450765EB","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 08:00:47 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for C7BBE235-3DD4-43E3-BA80-A3BA3281F60E (syncValue: 0)'
,2017-07-21 08:00:47 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C7BBE235-3DD4-43E3-BA80-A3BA3281F60E", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C7BBE235-3DD4-43E3-BA80-A3BA3281F60E", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C7BBE235-3DD4-43E3-BA80-A3BA3281F60E:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C39D4A68-9FE6-420E-91C5-1FF6CE30E22A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C39D4A68-9FE6-420E-91C5-1FF6CE30E22A", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:C7BBE235-3DD4-43E3-BA80-A3BA3281F60E:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:C7,BBE235-3DD4-43E3-BA80-A3BA3281F60E:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "C7BBE235-3DD4-43E3-BA80-A3BA3281F60E", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C,7BBE235-3DD4-43E3-BA80-A3BA3281F60E", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C7BBE235-3DD4-43E3-BA80-A3BA3281F60E", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:C7BBE235-3DD4-43E3-BA80-A3BA3281F60E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:C7BBE235-3DD4-43E3-BA80-A3BA3281F60E:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:C7BBE235-3DD4-43E3-BA80-A3BA3281F60E:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:C7,BBE235-3DD4-43E3-BA80-A3BA3281F60E:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "C7BBE235-3DD4-43E3-BA80-A3BA3281F60E", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C,7BBE235-3DD4-43E3-BA80-A3BA3281F60E", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C7BBE235-3DD4-43E3-BA80-A3BA3281F60E", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:C7BBE235-3DD4-43E3-BA80-A3BA3281F60E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:C7BBE235-3DD4-43E3-BA80-A3BA3281F60E:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:7DD5AEE7-8E99-4B80-925A-2130205EC73D
[ThaliCore] Advertiser: session connected Peer(uuid: "C39D4A68-9FE6-420E-91C5-1FF6CE30E22A", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:7DD5AEE7-8E99-4B80-925A-2130205EC73D state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:C7BBE235-3DD4-43E3-BA80-A3BA3281F60E:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "C7BBE235-3DD4-43E3-BA80-A3BA3281F60E", generation: 0)
2017-07-21 08:00:55 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"C7BBE235-3DD4-43E3-BA80-A3BA3281F60E","generation":0}]'
2017-07-21 08:00:55 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"C7BBE235-3DD4-43E3-BA80-A3BA3281F60E","generation":0}'
,2017-07-21 08:00:55 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"C7BBE235-3DD4-43E3-BA80-A3BA3281F60E","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-21 08:00:55 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"C7BBE235-3DD4-43E3-BA80-A3BA3281F60E","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:C7BBE235-3DD4-43E3-BA80-A3BA3281F60E:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:C7,BBE235-3DD4-43E3-BA80-A3BA3281F60E:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "C7BBE235-3DD4-43E3-BA80-A3BA3281F60E", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C,7BBE235-3DD4-43E3-BA80-A3BA3281F60E", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C7BBE235-3DD4-43E3-BA80-A3BA3281F60E", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
,2017-07-21 08:00:56 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"0","error":"Peer is unavailable","portNumber":null}'
,2017-07-21 08:00:56 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"C7BBE235-3DD4-43E3-BA80-A3BA3281F60E","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-21 08:00:56 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"C7BBE235-3DD4-43E3-BA80-A3BA3281F60E","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 08:00:56 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 1AEB318D-F436-4ED2-92B3-8595DFA2FFED (syncValue: 1)'
,2017-07-21 08:00:56 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1AEB318D-F436-4ED2-92B3-8595DFA2FFED", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1AEB318D-F436-4ED2-92B3-8595DFA2FFED", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1AEB318D-F436-4ED2-92B3-8595DFA2FFED:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 08:00:56 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"C7BBE235-3DD4-43E3-BA80-A3BA3281F60E","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,[ThaliCore] Session.deinit peer:C7BBE235-3DD4-43E3-BA80-A3BA3281F60E:0
[ThaliCore] BrowserRelay.deinit
,2017-07-21 08:00:56 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"C7BBE235-3DD4-43E3-BA80-A3BA3281F60E","peerAvailable":true,"portNumber":null,"recreated":true}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:1AEB318D-F436-4ED2-92B3-8595DFA2FFED:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F5E784E7-3593-443A-B503-E8844F0337E9
[ThaliCore] Advertiser: session connected Peer(uuid: "C39D4A68-9FE6-420E-91C5-1FF6CE30E22A", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:F5E784E7-3593-443A-B503-E8844F0337E9 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:7DD5AEE7-8E99-4B80-925A-2130205EC73D
,[ThaliCore] Session.session(_:peer:didChange:) peer:7DD5AEE7-8E99-4B80-925A-2130205EC73D state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7DD5AEE7-8E99-4B80-925A-2130205EC73D
,[ThaliCore] Session.startOutputStream(with:) peer:7DD5AEE7-8E99-4B80-925A-2130205EC73D
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:13 [13]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:1AEB318D-F436-4ED2-92B3-8595DFA2FFED:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:1AEB318D-F436-4ED2-92B3-8595DFA2FFED:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "1AEB318D-F436-4ED2-92B3-8595DFA2FFED", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57231
2017-07-21 08:00:58 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"1","error":null,"portNumber":57231,}'
,2017-07-21 08:00:58 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for CE14C433-882F-4790-BE2A-EEC0450765EB (syncValue: 2)'
,2017-07-21 08:00:58 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "CE14C433-882F-4790-BE2A-EEC0450765EB", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CE14C433-882F-4790-BE2A-EEC0450765EB", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:CE14C433-882F-4790-BE2A-EEC0450765EB:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:1AEB318D-F436-4ED2-92B3-8595DFA2FFED:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:1AEB318D-F436-4ED2-92B3-8595DFA2FFED:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:14 [13, 14]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-21 08:00:59 - DEBUG testUtils: 'Got response data'
,2017-07-21 08:00:59 - DEBUG testUtils: 'Got end'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:F5E784E7-3593-443A-B503-E8844F0337E9
,[ThaliCore] Session.session(_:peer:didChange:) peer:F5E784E7-3593-443A-B503-E8844F0337E9 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F5E784E7-3593-443A-B503-E8844F0337E9
[ThaliCore] Session.startOutputStream(with:) peer:F5E784E7-3593-443A-B503-E8844F0337E9
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:15 [13, 14, 15]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:CE14C433-882F-4790-BE2A-EEC0450765EB:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:CE14C433-882F-4790-BE2A-EEC0450765EB:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:CE14C433-882F-4790-BE2A-EEC0450765EB:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "CE14C433-882F-4790-BE2A-EEC0450765EB", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57236
,2017-07-21 08:01:02 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"2","error":null,"portNumber":57236}'
,[ThaliCore] BrowserManager.disconnect peer:C7BBE235-3DD4-43E3-BA80-A3BA3281F60E
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:CE14C433-882F-4790-BE2A-EEC0450765EB:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:CE14C433-882F-4790-BE2A-EEC0450765EB:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:16 [13, 14, 15, 16]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-21 08:01:02 - DEBUG testUtils: 'Got response data'
,2017-07-21 08:01:02 - DEBUG testUtils: 'Got end'
,ok 528 received all uuids
,# teardown
,2017-07-21 08:01:02 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"1AEB318D-F436-4ED2-92B3-8595DFA2FFED","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-21 08:01:02 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"CE14C433-882F-4790-BE2A-EEC0450765EB","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:C39D4A68-9FE6-420E-91C5-1FF6CE30E22A
,2017-07-21 08:01:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 08:01:02 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
2017-07-21 08:01:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] Brows,erManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 08:01:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:01:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-07-21 08:01:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:15
[ThaliCore] VirtualSocket.closeS,treams() vsID:15
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:15
[ThaliCore] VirtualSocket.deinit vsID:15 [13, 14, 16]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:13
[ThaliCore] VirtualSocket.closeS,treams() vsID:13
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:13
,[ThaliCore] VirtualSocket.deinit vsID:13 [14, 16]
,ok 529 error should be null
,ok 530 error should be null
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:16
,[ThaliCore] VirtualSocket.closeStreams() vsID:16
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:16
[ThaliCore] VirtualSocket.deinit vsID:16 [14]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:n,il
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,# setup
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:14
[ThaliCore] VirtualSocket.closeStreams() vsID:14
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:14
,[ThaliCore] VirtualSocket.deinit vsID:14 []
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,ok 531 ThaliMobile should be stopped
,# test for data corruption
,2017-07-21 08:01:03 - DEBUG CoordinatedClient: 'test was skipped, name: 'test for data corruption''
,# teardown
,ok 532 error should be null
,ok 533 error should be null
,# setup
,# #testThaliPeerAction - test getters
,ok 534 getPeerIdentifier
,ok 535 getConnectionType
ok 536 getActionType
ok 537 getActionState
ok 538 getPskIdentity
,ok 539 getPskKey
,# teardown
,# setup
,# #testThaliPeerAction - start and kill
,ok 540 initial state
ok 541 after start
2017-07-21 08:01:04 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 542 after kill
,# teardown
,# setup
,# #testThaliPeerAction - double start
,ok 543 should be equal
,# teardown
,# setup
,# #testThaliPeerAction - start after kill
,2017-07-21 08:01:04 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 544 clean kill
,ok 545 should be equal
,# teardown
,# setup
,# #testThaliPeerAction - make sure ids are unique
,ok 546 should not be equal
,# teardown
,# setup
,# #testThaliPeerAction - check that forever agent can be destroyed
,ok 547 forever agent should have it's own destroy method
,ok 548 agent's destroy should be called
ok 549 agent's destroy should not be called again
ok 550 agent is destroyed
,# teardown
,# setup
,# Test PeerDictionary basic functionality
,ok 551 Entry counter must be 1
,ok 552 Entry exists
,ok 553 Size must be 1
,ok 554 Entry counter must be 2
,ok 555 Entry exists
,ok 556 Size must be 2
,ok 557 Entry counter must be 1
,ok 558 Entry exists
,ok 559 Size must be 3
,ok 560 Entry counter must be 2
,ok 561 Entry exists
,ok 562 Size must be 4
,ok 563 Entry 1_1 should not be found
,ok 564 Entry 1_1 does not exist
,ok 565 Size must be 3
,ok 566 Entry 1_2 should not be found
,ok 567 Entry 1_2 does not exist
,ok 568 Size must be 2
,ok 569 should be equal
,ok 570 Entry 2_1 should not be found
,ok 571 Entry 2_2 should not be found
,ok 572 Entry 2_1 does not exist
,ok 573 Entry 2_2 does not exist
,ok 574 Size must be 0
,# teardown
,# setup
,# Test PeerDictionary with multiple entries.
,ok 575 Size must be100
,ok 576 Entries between 20 and MAXSIZE + 20 should exist
,ok 577 WAITING state entry should not be removed
,# teardown
,# setup
,# RESOLVED entries are removed before WAITING state entry.
,ok 578 Entries between 6 and MAXSIZE + 4 should exist
,ok 579 Size should be MAXSIZE
,ok 580 Size should be MAXSIZE+6
,# teardown
,# setup
,# WAITING entries are removed before CONTROLLED_BY_POOL state entry.
,ok 581 WAITING state entry should not be removed
,ok 582 Waiting entries between 6 and MAXSIZE + 4 should exist
,ok 583 Size should be MAXSIZE
,ok 584 entryCounter should be MAXSIZE+6
,# teardown
,# setup
,# When CONTROLLED_BY_POOL entry is removed and kill is called.
,ok 585 Kill should be called once
,ok 586 Size should be MAXSIZE
,# teardown
,# setup
,# #ThaliPeerPoolDefault - single action
,ok 587 is an agent
ok 588 enqueue is fine
ok 589 Everything should be off the queue
,# teardown
,# setup
,# #ThaliPeerPoolDefault - multiple actions
,ok 590 is an agent
ok 591 first enqueue is fine
ok 592 is an agent
ok 593 second enqueue is fine
ok 594 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
ok 595 Queue is empty
,# teardown
,# setup
,# #ThaliPeerPoolDefault - PSK Pool works
,ok 596 is an agent
ok 597 good enqueue
,ok 598 Identity should match
,2017-07-21 08:01:08 - DEBUG testUtils: 'Got response data'
,2017-07-21 08:01:08 - DEBUG testUtils: 'Got end'
,ok 599 Got expected response
,ok 600 Got psk call back
,# teardown
,2017-07-21 08:01:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #ThaliPeerPoolDefault - stop
,ok 601 is an agent
,ok 602 enqueue worked
,ok 603 is an agent
,ok 604 enqueue 2 worked
,ok 605 enqueue is not available when stopped
,ok 606 start action is killed
,ok 607 killed action is still killed
,ok 608 enqueued action when stopped is killed
,ok 609 inQueue is empty
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure that start verifies queue length
,ok 610 good start
ok 611 good enqueue
ok 612 queue is not empty
,# teardown
,# setup
,# #ThaliPeerPoolInterface - bad enqueues
,ok 613 null arg
ok 614 wrong arg type
,ok 615 wrong arg type
,# teardown
,# setup
,# #ThaliPeerPoolInterface - do not allow same object type
,ok 616 good enqueue
,ok 617 already enqueued
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure we catch kill and dequeue
,ok 618 good enqueue
ok 619 2nd good enqueue
ok 620 we are in the pool
ok 621 We are out of the pool
,ok 622 Action was killed
ok 623 The original kill was called too
ok 624 second item is still in queue
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent
,ok 625 good enqueue
,ok 626 first kill
,ok 627 second NOOP kill
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure that stop removes all actions
,ok 628 1st good enqueue
,ok 629 2nd good enqueue
,ok 630 1st action is in the pool
,ok 631 2nd action is in the pool
,ok 632 1st action is out of the pool
,ok 633 2st action is out of the pool
,ok 634 pool is empty
,# teardown
,# setup
,# We reject unrecognized connection type
,2017-07-21 08:01:12 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 635 Got right error
,ok 636 Start should not be called
,ok 637 Kill should have been called at least once
,# teardown
,# setup
,# We reject unrecognized action type
,2017-07-21 08:01:12 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-21 08:01:12 - ERROR thaliPeerPoolOneAtATime: 'Got unsupported action type: blah'
ok 638 Got right error
ok 639 Start should not be called
ok 640 Kill should have been called at least once
,# teardown
,# setup
,# One action on bluetooth
,2017-07-21 08:01:12 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 641 Got null
,2017-07-21 08:01:12 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerID'
,ok 642 is an agent
,2017-07-21 08:01:12 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerID'
,ok 643 Got killed at least once
,# teardown
,# setup
,# Two notification actions
,2017-07-21 08:01:13 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 644 Got Null
,ok 645 Got another null
,2017-07-21 08:01:13 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId1'
,ok 646 is an agent
,2017-07-21 08:01:13 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId1'
,2017-07-21 08:01:13 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
,ok 647 is an agent
,2017-07-21 08:01:13 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
,ok 648 Action 1 killed at least once
,ok 649 Action 1 went first
,ok 650 Action 2 killed at least once
,# teardown
,# setup
,# replicateThroughProblems
,2017-07-21 08:01:13 - DEBUG thaliPeerPoolOneAtATime: 'Action Started success'
,2017-07-21 08:01:13 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - success'
,2017-07-21 08:01:13 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,ok 651 should have gotten null
,2017-07-21 08:01:13 - DEBUG thaliPeerPoolOneAtATime: 'Action Started noActivityTimeOut'
,2017-07-21 08:01:13 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: No activity time out - noActivityTimeOut'
,ok 652 Should have stopped nicely
,2017-07-21 08:01:13 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButNotAvailable'
,2017-07-21 08:01:13 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButNotAvailable'
,ok 653 Still looking for null
,2017-07-21 08:01:13 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButAvailable'
,2017-07-21 08:01:13 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButAvailable'
,2017-07-21 08:01:13 - DEBUG thaliPeerPoolOneAtATime: 'Replication action failed badly so we are going to retry'
,2017-07-21 08:01:13 - DEBUG thaliPeerPoolOneAtATime: 'Action Started clone!'
,2017-07-21 08:01:13 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - clone!'
,2017-07-21 08:01:13 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,ok 654 Yup, another null
,ok 655 We cloned!
,# teardown
,# setup
,# Replication goes first
,2017-07-21 08:01:13 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 656 Null 1
,ok 657 (unnamed assert)
,2017-07-21 08:01:13 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,ok 658 is an agent
,ok 659 Null 3
,ok 660 Replication not yet called
,ok 661 Notification 2 not yet called
,2017-07-21 08:01:13 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,2017-07-21 08:01:13 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
,ok 662 is an agent
,ok 663 Notification went first
,ok 664 Notification 2 not called yet
,2017-07-21 08:01:14 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
,2017-07-21 08:01:14 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,2017-07-21 08:01:14 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,ok 665 is an agent
,ok 666 Notification finished
,ok 667 Replication finished
,2017-07-21 08:01:14 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,# teardown
,# setup
,# wifi allows many parallel non-replication actions
,2017-07-21 08:01:15 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
2017-07-21 08:01:15 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
ok 668 is an agent
ok 669 First does, not throw
2017-07-21 08:01:15 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
,ok 670 is an agent
ok 671 Second does not throw
2017-07-21 08:01:15 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
truetruefalsetrue
,2017-07-21 08:01:15 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
truetruetruetrue
# teardown
,# setup
,# wifi allows no more than 2 simultaneous replication actions for same peerID
,2017-07-21 08:01:15 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-21 08:01:15 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 595, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,ok 672 is an agent
,ok 673 first ok
,2017-07-21 08:01:15 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 596, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,ok 674 is an agent
,ok 675 second ok
,ok 676 third ok
,2017-07-21 08:01:16 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 595, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,2017-07-21 08:01:16 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 596, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,2017-07-21 08:01:16 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,2017-07-21 08:01:16 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,# teardown
,# setup
,# Client to server request coordinated
,2017-07-21 08:01:16 - DEBUG CoordinatedClient: 'test was skipped, name: 'Client to server request coordinated''
,# teardown
,2017-07-21 08:01:17 - INFO testThaliNotification: 'Participants:0 Peers Replied to us:0 Peers requested to:0'
,# setup
,# Test BEACONS_RETRIEVED_AND_PARSED locally
,ok 677 peerIdentifier should match
ok 678 generation should match
,ok 679 Response should be BEACONS_RETRIEVED_AND_PARSED
,ok 680 good beacon
,ok 681 good preAmble
,ok 682 public keys match!
,ok 683 must return null after successful call
,ok 684 Once start returns the action should be in KILLED state
,# teardown
,2017-07-21 08:01:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test HTTP_BAD_RESPONSE locally
,2017-07-21 08:01:18 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test HTTP_BAD_RESPONSE locally''
,# teardown
,2017-07-21 08:01:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test NETWORK_PROBLEM locally
,ok 685 Response should be NETWORK_PROBLEM
,ok 686 reject reason should be: Could not establish TCP connection
,# teardown
,2017-07-21 08:01:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Action fails when getPeerHostInfo fails
,ok 687 Resolution should be BAD_PEER
,ok 688 correct error message
,# teardown
,2017-07-21 08:01:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the start two times
,ok 689 Call start once
,ok 690 Response should be BEACONS_RETRIEVED_AND_PARSED
,ok 691 must return null after successful call.
,# teardown
,2017-07-21 08:01:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill before calling the start
,ok 692 Should be Killed
,ok 693 Start after killed
,# teardown
,2017-07-21 08:01:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill immediately after the start
,ok 694 Should be KILLED
,ok 695 must return null after successful kill
,# teardown
,2017-07-21 08:01:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill while waiting a response from the server
,ok 696 Should be KILLED
ok 697 must return null after successful kill
,# teardown
,2017-07-21 08:01:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test to exceed the max content size locally
,ok 698 HTTP_BAD_RESPONSE should be response when content size is exceeded
,ok 699 must return null after successful call
,# teardown
,2017-07-21 08:01:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Close the server socket while the client is waiting a response from the server. Local test.
,2017-07-21 08:01:25 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 700 Should be NETWORK_PROBLEM caused closing server socket
,ok 701 Should be Could not establish TCP connection
,# teardown
,# setup
,# Close the client socket while the client is waiting a response from the server. Local test.
,ok 702 Should be NETWORK_PROBLEM caused closing client socket
ok 703 Should be Could not establish TCP connection
,# teardown
,2017-07-21 08:01:27 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #generatePreambleAndBeacons bad args
,ok 704 publicKeysToNotify cannot be null
ok 705 ecdh for local device cannot be null
,ok 706 milliseconds cannot be less than 0
,ok 707 milliseconds cannot be 0
,ok 708 milliseconds cannot be greater than one_day
,# teardown
,# setup
,# #generatePreambleAndBeacons empty keys to notify
,ok 709 should be equal
,# teardown
,# setup
,# #generatePreambleAndBeacons multiple keys to notify
,ok 710 should be equal
ok 711 should be equal
,ok 712 (unnamed assert)
,ok 713 should be equal
,# teardown
,# setup
,# #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
,ok 714 should throw
,# teardown
,# setup
,# #parseBeacons invalid expiration in beaconStreamWithPreAmble
,ok 715 Preamble expiration must be a 64 bit integer
,# teardown
,# setup
,# #parseBeacons expiration out of range lower
,ok 716 Expiration out of range
,# teardown
,# setup
,# #parseBeacons expiration out of range lower
,ok 717 Expiration out of range
,# teardown
,# setup
,# #parseBeacons no beacons returns null
,ok 718 should be equal
,# teardown
,# setup
,# #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
,ok 719 Malformed encrypted beacon key ID
,# teardown
,# setup
,# #parseBeacons addressBookCallback fails decrypt
,ok 720 should be equal
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns no matches
,2017-07-21 08:01:30 - DEBUG CoordinatedClient: 'test was skipped, name: '#parseBeacons addressBookCallback returns no matches''
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns spurious match
,ok 721 should be equal
,ok 722 should be equal
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns public key
,ok 723 right number of calls to address book
ok 724 good preAmble
,ok 725 good unencryptedKeyId
,ok 726 good beacon
,# teardown
,# setup
,# validate generatePskIdentityField
,ok 727 decoded buffers match
,# teardown
,# setup
,# validate generatePskSecret
,ok 728 secrets match
,# teardown
,# setup
,# validate generatePskSecrets
,ok 729 Matching numbers
,ok 730 We have an entry!
,ok 731 keys match
,ok 732 secrets match
,ok 733 We have an entry!
,ok 734 keys match
,ok 735 secrets match
,ok 736 We have an entry!
,ok 737 keys match
,ok 738 secrets match
,# teardown
,# setup
,# validate generateBeaconStreamAndSecrets
,ok 739 Streams have same length
,ok 740 matching size
,ok 741 keys match
,ok 742 secrets match
,# teardown
,# setup
,# Add two Peers.
,ok 743 should be equal
,ok 744 peerDictionalty contains 2 peers
,ok 745 bluetooth peer's notification has correct connection type
,ok 746 tcp peer's notification has correct connection type
,2017-07-21 08:01:33 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,2017-07-21 08:01:33 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-07-21 08:01:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# TCP_NATIVE peer loses DNS
,ok 747 notification peer dictionary contains exactly 1 peer
2017-07-21 08:01:34 - WARN thaliNotificationClient: 'peer is not available'
,ok 748 notification peer dictionary does not contain any peers
2017-07-21 08:01:34 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-07-21 08:01:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Received beacons with no values for us
,ok 749 entry exists
,ok 750 entry is resolved
,# teardown
,2017-07-21 08:01:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Notification action killed with a superseded
,ok 751 Action should be KILLED
,ok 752 Peer state should be RESOLVED
,# teardown
,2017-07-21 08:01:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally
,ok 753 hostAddress must match
,ok 754 portNumber must match
,ok 755 suggestedTCPTimeout must match
,ok 756 connectionType must match
,ok 757 peerIDs must match
,# teardown
,2017-07-21 08:01:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Emits error event when peerPool.enqueue throws
,ok 758 Correct error
,# teardown
,2017-07-21 08:01:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally using ThaliPeerPoolDefault
,ok 759 hostAddress must match
,ok 760 portNumber must match
,ok 761 suggestedTCPTimeout must match
,ok 762 connectionType must match
,ok 763 peerIds must match
,# teardown
,2017-07-21 08:01:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Action fails because of a bad hostname.
,2017-07-21 08:01:36 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 764 action should be resolved with NETWORK_PROBLEM error
,2017-07-21 08:01:36 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 765 action should be resolved with NETWORK_PROBLEM error
,2017-07-21 08:01:37 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 766 action should be resolved with NETWORK_PROBLEM error
,2017-07-21 08:01:38 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 767 action should be resolved with NETWORK_PROBLEM error
ok 768 correct number of requests
ok 769 correct number of failures
ok 770 correct final peer state
,# teardown
,2017-07-21 08:01:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# hostaddress is removed when the action is running. 
,2017-07-21 08:01:40 - WARN thaliNotificationClient: 'peer is not available'
2017-07-21 08:01:40 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 771 peerDictionary should become empty
,# teardown
,2017-07-21 08:01:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notificationClient does not retry action with BAD_PEER resolution
,2017-07-21 08:01:41 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 772 failed with expected error
,ok 773 peer state should be RESOLVED
,# teardown
,2017-07-21 08:01:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notification client correctly handles peer availability changes of the same peer
,2017-07-21 08:01:41 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 774 First action failed
,ok 775 second action killed
# teardown
,2017-07-21 08:01:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Client to server request locally
,ok 776 secrets are equal
,ok 777 Public key matches with the server key
,ok 778 hostAddress must match
,ok 779 portNumber must match
,ok 780 suggestedTCPTimeout must match
,ok 781 connectionType must match
,# teardown
,2017-07-21 08:01:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache clean and expiration
,ok 782 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE
,ok 783 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE-1
,ok 784 All entries should be expired after 1 second
# teardown
,2017-07-21 08:01:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache getSecret and getPublic
,ok 785 All keys need to be available in the cache
,ok 786 All entries should be expired after 1 second
# teardown
,2017-07-21 08:01:45 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache multiple entries
,ok 787 Size of the cache should be 2
ok 788 Cache doesn't contain dictionary1
,ok 789 Size of the cache should be 1
ok 790 Cache doesn't contain beaconStreamAndSecretDictionary2
# teardown
,2017-07-21 08:01:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Start and stop ThaliNotificationServer
,ok 791 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
,ok 792 ThaliMobile.StopAdvertisingAndListeningshould be called once
,# teardown
,2017-07-21 08:01:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass an empty array to ThaliNotificationServer.start
,ok 793 StartUpdateAdvertisingAndListening should not be called
,ok 794 ThaliMobile.StopAdvertisingAndListening should be called once
,ok 795 no error
,ok 796 should be 204
,# teardown
,2017-07-21 08:01:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass a string to ThaliNotificationServer.start
,ok 797 StartUpdateAdvertisingAndListening should not be called
,# teardown
,2017-07-21 08:01:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass an empty parameter to ThaliNotificationServer.start
,ok 798 StartUpdateAdvertisingAndListening should not be called
,# teardown
,2017-07-21 08:01:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeacons
,ok 799 no error
,ok 800 should be 200
,ok 801 should be equal
,ok 802 should be equal
,ok 803 (unnamed assert)
,ok 804 no error
ok 805 should be 204
,# teardown
,2017-07-21 08:01:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeacons (no keys)
,ok 806 error should be null
,ok 807 should be 204
,# teardown
,2017-07-21 08:01:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeaconsbefore calling start
,ok 808 should be 404
,# teardown
,2017-07-21 08:01:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure peerDictionaryKey is reasonable
,ok 809 equal keys
ok 810 not equal connection type
ok 811 same connection type, different buffer
,# teardown
,# setup
,# Make sure start works
,2017-07-21 08:01:53 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,ok 812 First start and on called correctly
,# teardown
,# setup
,# Make sure stop works
,ok 813 second cleared dictionary
,2017-07-21 08:01:54 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,ok 814 First start and on called correctly
,ok 815 First stop and removeListener called correctly
,ok 816 first action kill called
,ok 817 second action kill called
,ok 818 first cleared dictionary
,ok 819 first cleared pool
,ok 820 second cleared dictionary
,ok 821 second cleared pool
,# teardown
,# setup
,# Emits error event when peerPool.enqueue throws
,ok 822 Correct error
,# teardown
,# setup
,# Simple peer event
,2017-07-21 08:01:55 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,ok 823 listener has been set
,ok 824 peer dictionary has expected number of entries
,ok 825 Dictionary and pool have same action
ok 826 ads match
,ok 827 PouchDB matches
,ok 828 DB Names match
,ok 829 public keys match
,ok 830 peer dictionary has expected number of entries
,ok 831 Dictionary and pool have same action
,ok 832 ads match
,ok 833 PouchDB matches
,ok 834 DB Names match
,ok 835 public keys match
,2017-07-21 08:01:55 - DEBUG thaliReplicationPeerAction: 'We called _complete with  and it caused us to complete'
,ok 836 start called once
,ok 837 One entry left
,ok 838 Dictionary and pool have same action
,ok 839 Start never called
,ok 840 Kill called once
,ok 841 no entries left
,ok 842 Third action is dead
,ok 843 peer dictionary has expected number of entries
,ok 844 Dictionary and pool have same action
,ok 845 ads match
,ok 846 PouchDB matches
,ok 847 DB Names match
,ok 848 public keys match
,# teardown
,# setup
,# Coordinated pull replication from notification test
,2017-07-21 08:01:55 - DEBUG CoordinatedClient: 'test was skipped, name: 'Coordinated pull replication from notification test''
,# teardown
,# setup
,# Server is not there
,2017-07-21 08:01:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 08:01:56 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 connect ECONNREFUSED'
,2017-07-21 08:01:56 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: connect ECONNREFUSED  and it caused us to complete'
,ok 849 right error
,# teardown
,2017-07-21 08:01:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server accepts & closes connection
,2017-07-21 08:01:56 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 socket hang up'
,2017-07-21 08:01:56 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: socket hang up  and it caused us to complete'
,ok 850 right error
,# teardown
,2017-07-21 08:01:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 500
,2017-07-21 08:01:57 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 changes rejected'
,2017-07-21 08:01:57 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 851 Got error as expected
,# teardown
,2017-07-21 08:01:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 401
,2017-07-21 08:01:57 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  401 changes rejected'
,2017-07-21 08:01:57 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 852 Got error as expected
,# teardown
,2017-07-21 08:01:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 403
,2017-07-21 08:01:58 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  403 changes rejected'
,2017-07-21 08:01:58 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 853 Got error as expected
,# teardown
,2017-07-21 08:01:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure docs replicate with remote db with same name as local db
,2017-07-21 08:02:01 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-21 08:02:01 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-21 08:02:03 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
,ok 854 should be equal
ok 855 All tests passed!
,# teardown
,2017-07-21 08:02:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure docs replicate with remote db with different name than local db
,2017-07-21 08:02:06 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-21 08:02:06 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-21 08:02:08 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
,ok 856 should be equal
,ok 857 All tests passed!
,# teardown
,2017-07-21 08:02:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Do nothing and make sure we time out
,2017-07-21 08:02:09 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-21 08:02:11 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2017-07-21 08:02:11 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and s,o we ignored it'
ok 858 action should be killed
ok 859 Error should be timed out
,ok 860 No doc found
,# teardown
,2017-07-21 08:02:11 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Do something and make sure we time out
,2017-07-21 08:02:13 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-21 08:02:14 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,ok 861 should be equal
,2017-07-21 08:02:15 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2017-07-21 08:02:15 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and s,o we ignored it'
,ok 862 action should be killed
ok 863 Error should be timed out
,# teardown
,2017-07-21 08:02:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Start replicating and then catch error when server goes
,ok 864 socket hung up
,# teardown
,2017-07-21 08:02:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure clone works
,ok 865 same getPeerAdvertisesDataForUs
ok 866 Same pouchdB
ok 867 same localDbName
ok 868 Same public key
,# teardown
,# setup
,# Coordinated replication action test - each device has the same local db name
,2017-07-21 08:02:21 - DEBUG CoordinatedClient: 'test was skipped, name: 'Coordinated replication action test - each device has the same local db name''
,# teardown
,# setup
,# Coordinated replication action test - each device has different local db name
,2017-07-21 08:02:22 - DEBUG thaliMobileNativeWrapper: 'listening 57363'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C4E2EC99-3E16-40AE-8DE9-96503462B65F
[ThaliCore] Browser.startListening
,2017-07-21 08:02:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "72759949-905B-4F26-99D5-EC97C00BEAC3", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:72759949-905B-4F26-99D5-EC97C00BEAC3
,2017-07-21 08:02:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FA1EB5BA-D365-4DBE-9591-19F3D61E10A8:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FA1EB5BA-D365-4DBE-9591-19F3D61E10A8", generation: 0)
,2017-07-21 08:02:23 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"FA1EB5BA-D365-4DBE-9591-19F3D61E10A8","generation":0}]'
2017-07-21 08:02:23 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"FA1EB5BA-D365-4DBE-9591-19F3D61E10A8","generation":0}'
,2017-07-21 08:02:23 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"FA1EB5BA-D365-4DBE-9591-19F3D61E10A8","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 08:02:23 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"FA1EB5BA-D365-4DBE-9591-19F3D61E10A8","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 08:02:23 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for FA1EB5BA-D365-4DBE-9591-19F3D61E10A8 (syncValue: 3)'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:798FE329-CA2C-48EB-8C64-3BEA2692A145:0
2017-07-21 ,08:02:23 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "798FE329-CA2C-48EB-8C64-3BEA2692A145", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "FA1EB5BA-D365-4DBE-9591-19F3D61E10A8", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FA1EB5BA-D365-4DBE-9591-19F3D61E10A8", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FA1EB5BA-D365-4DBE-9591-19F3D61E10A8:0,
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 08:02:23 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"798FE329-CA2C-48EB-8C64-3BEA2692A145","generation":0}]'
2017-07-21 08:02:23 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"798FE329-CA2C-48EB-8C64-3BEA2692A145","generation":0}'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D48E2020-BCEB-46C0-9637-2F5F95561B8D
,[ThaliCore] Advertiser: session connected Peer(uuid: "72759949-905B-4F26-99D5-EC97C00BEAC3", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:D48E2020-BCEB-46C0-9637-2F5F95561B8D state: notConnected -> connecting
,2017-07-21 08:02:23 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"798FE329-CA2C-48EB-8C64-3BEA2692A145","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3BC99E38-DFA3-444D-847D-934C08CEAD4F
[ThaliCore] Advertiser: session connected Peer(uuid: "72759949-905B-4F26-99D5-EC97C00BEAC3", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:3BC99E38-DFA3-444D-847D-934C08CEAD4F state: notConnected -> connecting
2017-07-21 08:02:23 - DEBUG thaliMobile: 'Emitting peerAvailability,Changed from handlePeer {"peerIdentifier":"798FE329-CA2C-48EB-8C64-3BEA2692A145","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "72759949-905B-4F26-99D5-EC97C00BEAC3", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:FA1EB5BA-D365-4DBE-9591-19F3D61E10A8:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:FA1EB5BA-D365-4DBE-9591-19F3D61E10A8:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:FA1EB5BA-D365-4DBE-9591-19F3D61E10A8:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "FA1EB5BA-D365-4DBE-9591-19F3D61E10A8", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57366
,2017-07-21 08:02:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"3","error":null,"portNumber":57366}'
,2017-07-21 08:02:26 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 798FE329-CA2C-48EB-8C64-3BEA2692A145 (syncValue: 4)'
,2017-07-21 08:02:26 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:3BC99E38-DFA3-444D-847D-934C08CEAD4F
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "798FE329-CA2C-48EB-8C64-3BEA2692A145", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "798FE329-CA2C-48EB-8C64-3BEA2692A145", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:3BC99E38-DFA3-444D-847D-934C08CEAD4F state: connecting -> connected
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:798FE329-CA2C-48EB-8C64-3BEA2692A145:0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D48E2020-BCEB-46C0-9637-2F5F95561B8D
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3BC99E38-DFA3-444D-847D-934C08CEAD4F
[ThaliCore] Session.startOutputStream(with:) peer:3BC99E38-DFA3-444D-847D-934C08CEAD4F
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:17 [17]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:D48E2020-BCEB-46C0-9637-2F5F95561B8D state: connecting -> connected
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:FA1EB5BA-D365-4DBE-9591-19F3D61E10A8:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FA1EB5BA-D365-4DBE-9591-19F3D61E10A8:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:18 [17, 18]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D48E2020-BCEB-46C0-9637-2F5F95561B8D
[ThaliCore] Session.startOutputStream(with:) peer:D48E2020-BCEB-46C0-9637-2F5F95561B8D
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:19 [17, 18, 19]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:18
[ThaliCore] Browse,rRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:18
[ThaliCore] VirtualSocket.deinit vsID:18 [17, 19]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:FA1EB5BA-D365-4DBE-9591-19F3D61E10A8:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3BC99E38-DFA3-444D-847D-934C08CEAD4F
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FA1EB5BA-D365-4DBE-9591-19F3D61E10A8:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:20 [17, 19, 20]
[ThaliCore] Session.startOutputStream(with:) peer:3BC99E38-DFA3-444D-847D-934C08CEAD4F
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:21 [17, 19, 20, 21]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:17
[ThaliCore] VirtualSocket.closeStreams() vsID:17
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D48E2020-BCEB-46C0-9637-2F5F95561B8D
[ThaliCore] Session.startOutputStream(with:) peer:D48E2020-BCEB-46C0-9637-2F5F95561B8D
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:22 [17, 19, 20, 21, 22]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
[ThaliCore] VirtualSocket exited RunLoop vsID:17
[ThaliCore] VirtualSocket.deinit vsID:17 [19, 20, 21, 22]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:19
[ThaliCore] VirtualSocket.closeStreams() vsID:19
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:peer:didChange:) peer:798FE329-CA2C-48EB-8C64-3BEA2692A145:0 state: notConnected -> connecting
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:19
[ThaliCore] VirtualSocket.deinit vsID:19 [20, 21, 22]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D48E2020-BCEB-46C0-9637-2F5F95561B8D
,[ThaliCore] Session.startOutputStream(with:) peer:D48E2020-BCEB-46C0-9637-2F5F95561B8D
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:23 [20, 21, 22, 23]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,2017-07-21 08:02:26 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:FA1EB5BA-D365-4DBE-9591-19F3D61E10A8:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FA1EB5BA-D365-4DBE-9591-19F3D61E10A8:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:24 [20, 21, 22, 23, 24]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3BC99E38-DFA3-444D-847D-934C08CEAD4F
[ThaliCore] Session.startOutputStream(with:) peer:3BC99E38-DFA3-444D-847D-934C08CEAD4F
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:25 [20, 21, 22, 23, 24, 25]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D48E2020-BCEB-46C0-9637-2F5F95561B8D
[ThaliCore] Session.startOutputStream(with:) peer:D48E2020-BCEB-46C0-9637-2F5F95561B8D
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:26 [20, 21, 22, 23, 24, 25, 26]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:FA1EB5BA-D365-4DBE-9591-19F3D61E10A8:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FA1EB5BA-D365-4DBE-9591-19F3D61E10A8:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:27 [20, 21, 22, 23, 24, 25, 26, 27]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:FA1EB5BA-D365-4DBE-9591-19F3D61E10A8:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FA1EB5BA-D365-4DBE-9591-19F3D61E10A8:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D48E2020-BCEB-46C0-9637-2F5F95561B8D
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:28 [20, 21, 22, 23, 24, 25, 26, 27, 28]
,[ThaliCore] Session.startOutputStream(with:) peer:D48E2020-BCEB-46C0-9637-2F5F95561B8D
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:29 [20, 21, 22, 23, 24, 25, 26, 27, 28, 29]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:FA1EB5BA-D365-4DBE-9591-19F3D61E10A8:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FA1EB5BA-D365-4DBE-9591-19F3D61E10A8:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:30 [20, 21, 22, 23, 24, 25, 26, 27, 28, 29, 30]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D48E2020-BCEB-46C0-9637-2F5F95561B8D
[ThaliCore] Session.startOutputStream(with:) peer:D48E2020-BCEB-46C0-9637-2F5F95561B8D
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:31 [20, 21, 22, 23, 24, 25, 26, 27, 28, 29, 30, 31]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:28
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:28
[ThaliCore] VirtualSocket.deinit vsID:28 [20, 21, 22, 23, 24, 25, 26, 27, 29, 30, 31]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3BC99E38-DFA3-444D-847D-934C08CEAD4F
[ThaliCore] Session.startOutputStream(with:) peer:3BC99E38-DFA3-444D-847D-934C08CEAD4F
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3,2 [20, 21, 22, 23, 24, 25, 26, 27, 29, 30, 31, 32]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:29
[ThaliCore] VirtualSocket.closeStreams() vsID:29
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:29
[ThaliCore] VirtualSocket.deinit vsID:29 [20, 21, 22, 23, 24, 25, 26, 27, 30, 31, 32]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D48E2020-BCEB-46C0-9637-2F5F95561B8D
[ThaliCore] Session.startOutputStream(with:) peer:D48E2020-BCEB-46C0-9637-2F5F95561B8D
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:33 [20, 21, 22, 23, 24, 25, 26, 27, 30, 31, 32, 33]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:FA1EB5BA-D365-4DBE-9591-19F3D61E10A8:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FA1EB5BA-D365-4DBE-9591-19F3D61E10A8:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:34 [20, 21, 22, 23, 24, 25, 26, 27, 30, 31, 32, 33, 34]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3BC99E38-DFA3-444D-847D-934C08CEAD4F
,[ThaliCore] Session.startOutputStream(with:) peer:3BC99E38-DFA3-444D-847D-934C08CEAD4F
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:35 [20, 21, 22, 23, 24, 25, 26, 27, 30, 31, 32, 33, 34, 35]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,2017-07-21 08:02:27 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:34
,[ThaliCore] VirtualSocket exited RunLoop vsID:34
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:34 [20, 21, 22, 23, 24, 25, 26, 27, 30, 31, 32, 33, 35]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3BC99E38-DFA3-444D-847D-934C08CEAD4F
[ThaliCore] Session.startOutputStream(with:) peer:3BC99E38-DFA3-444D-847D-934C08CEAD4F
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:36 [20, 21, 22, 23, 24, 25, 26, 27, 30, 31, 32, 33, 35, 36]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:33
[ThaliCore] VirtualSocket.closeStreams() vsID:33
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:33
[ThaliCore] VirtualSocket.deinit vsID:33 [20, 21, 22, 23, 24, 25, 26, 27, 30, 31, 32, 35, 36]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D48E2020-BCEB-46C0-9637-2F5F95561B8D
[ThaliCore] Session.startOutputStream(with:) peer:D48E2020-BCEB-46C0-9637-2F5F95561B8D
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:37 [20, 21, 22, 23, 24, 25, 26, 27, 30, 31, 32, 35, 36, 37]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:35
[ThaliCore] VirtualSocket.closeStreams() vsID:35
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:35
,[ThaliCore] VirtualSocket.deinit vsID:35 [20, 21, 22, 23, 24, 25, 26, 27, 30, 31, 32, 36, 37]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D48E2020-BCEB-46C0-9637-2F5F95561B8D
[ThaliCore] Session.startOutputStream(with:) peer:D48E2020-BCEB-46C0-9637-2F5F95561B8D
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:38 [20, 21, 22, 23, 24, 25, 26, 27, 30, 31, 32, 36, 37, 38]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:31
[ThaliCore] VirtualSocket.closeStreams() vsID:31
[ThaliCore] TCPClient: didConnectToHost, active connections count: 5
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:31
,[ThaliCore] VirtualSocket.deinit vsID:31 [20, 21, 22, 23, 24, 25, 26, 27, 30, 32, 36, 37, 38]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:37
[ThaliCore] VirtualSocket.closeStreams() vsID:37
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:37
[ThaliCore] VirtualSocket.deinit vsID:37 [20, 21, 22, 23, 24, 25, 26, 27, 30, 32, 36, 38]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient,.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3BC99E38-DFA3-444D-847D-934C08CEAD4F
[ThaliCore] Session.startOutputStream(with:) peer:3BC99E38-DFA3-444D-847D-934C08CEAD4F
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3,9 [20, 21, 22, 23, 24, 25, 26, 27, 30, 32, 36, 38, 39]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:39
[ThaliCore] VirtualSocket.closeStreams() vsID:39
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:39
[ThaliCore] VirtualSocket.deinit vsID:39 [20, 21, 22, 23, 24, 25, 26, 27, 30, 32, 36, 38]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient,.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:798FE329-CA2C-48EB-8C64-3BEA2692A145:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:798FE329-CA2C-48EB-8C64-3BEA2692A145:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "798FE329-CA2C-48EB-8C64-3BEA2692A145", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57392
,2017-07-21 08:02:29 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"4","error":null,"portNumber":57392}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:798FE329-CA2C-48EB-8C64-3BEA2692A145:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:798FE329-CA2C-48EB-8C64-3BEA2692A145:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:40 [20, 21, 22, 23, 24, 25, 26, 27, 30, 32, 36, 38, 40]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vs,ID:40
,[ThaliCore] VirtualSocket exited RunLoop vsID:40
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:40 [20, 21, 22, 23, 24, 25, 26, 27, 30, 32, 36, 38]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:798FE329-CA2C-48EB-8C64-3BEA2692A145:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:798FE329-CA2C-48EB-8C64-3BEA2692A145:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:41 [20, 21, 22, 23, 24, 25, 26, 27, 30, 32, 36, 38, 41]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-21 08:02:29 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:798FE329-CA2C-48EB-8C64-3BEA2692A145:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:798FE329-CA2C-48EB-8C64-3BEA2692A145:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:42 [20, 21, 22, 23, 24, 25, 26, 27, 30, 32, 36, 38, 41, 42]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-21 08:02:30 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-21 08:02:30 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
,2017-07-21 08:02:30 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:20
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:20
,[ThaliCore] VirtualSocket.deinit vsID:20 [21, 22, 23, 24, 25, 26, 27, 30, 32, 36, 38, 41, 42]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:24
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:24
[ThaliCore] VirtualSocket.deinit vsID:24 [21, 22, 23, 25, 26, 27, 30, 32, 36, 38, 41, 42]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:27
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:27
,[ThaliCore] VirtualSocket.deinit vsID:27 [21, 22, 23, 25, 26, 30, 32, 36, 38, 41, 42]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:30
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:30
,[ThaliCore] VirtualSocket.deinit vsID:30 [21, 22, 23, 25, 26, 32, 36, 38, 41, 42]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:798FE329-CA2C-48EB-8C64-3BEA2692A145:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:798FE329-CA2C-48EB-8C64-3BEA2692A145:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:43 [21, 22, 23, 25, 26, 32, 36, 38, 41, 42, 43]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3BC99E38-DFA3-444D-847D-934C08CEAD4F
[ThaliCore] Session.startOutputStream(with:) peer:3BC99E38-DFA3-444D-847D-934C08CEAD4F
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:44 [21, 22, 23, 25, 26, 32, 36, 38, 41, 42, 43, 44]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:22
[ThaliCore] VirtualSocket.closeStreams() vsID:22
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:25
[ThaliCore] VirtualSocket.closeStreams() vsID:25
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:22
,[ThaliCore] VirtualSocket.deinit vsID:22 [21, 23, 25, 26, 32, 36, 38, 41, 42, 43, 44]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected,
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D48E2020-BCEB-46C0-9637-2F5F95561B8D
[ThaliCore] Session.startOutputStream(with:) peer:D48E2020-BCEB-46C0-9637-2F5F95561B8D
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4,5 [21, 23, 25, 26, 32, 36, 38, 41, 42, 43, 44, 45]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] VirtualSocket exited RunLoop vsID:25
[ThaliCore] VirtualSocket.deinit vsID:25 [21, 23, 26, 32, 36, 38, 41, 42, 43, 44, 45]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.soc,ketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:23
[ThaliCore] VirtualSocket.closeStreams() vsID:23
[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncount,ered vsID:26
[ThaliCore] VirtualSocket.closeStreams() vsID:26
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:32
[ThaliCore] VirtualSocket.closeStreams() vsID:32
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:36
[ThaliCore] VirtualSocket.closeStreams() vsID:36
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:44
,[ThaliCore] VirtualSocket.closeStreams() vsID:44
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:21
[ThaliCore] VirtualSocket.closeStreams() vsID:21
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:38
[Thali,Core] VirtualSocket.closeStreams() vsID:38
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:32
[ThaliCore] VirtualSocket.deinit vsID:32 [21, 23, 26, 36, 38, 41, 42, 43, 44, 45]
[ThaliCore] TCPClient.socketDidDisconn,ect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:26
[ThaliCore] VirtualSocket.deinit vsID:26 [21, 23, 36, 38, 41, 42, 43, 44, 45]
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:36
,[ThaliCore] VirtualSocket.deinit vsID:36 [21, 23, 38, 41, 42, 43, 44, 45]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:38
[ThaliCore] VirtualSocket.deinit vsID:38 [21, 23, 41, 42, 43, 44, 45]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect,(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withEr,ror:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:21
,[ThaliCore] VirtualSocket.deinit vsID:21 [23, 41, 42, 43, 44, 45]
,[ThaliCore] VirtualSocket exited RunLoop vsID:44
,[ThaliCore] VirtualSocket.deinit vsID:44 [23, 41, 42, 43, 45]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:798FE329-CA2C-48EB-8C64-3BEA2692A145:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:798FE329-CA2C-48EB-8C64-3BEA2692A145:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:46 [23, 41, 42, 43, 45, 46]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:41
,[ThaliCore] VirtualSocket exited RunLoop vsID:41
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:41 [23, 42, 43, 45, 46]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
,[ThaliCore] VirtualSocket.closeStreams() vsID:42
,[ThaliCore] VirtualSocket exited RunLoop vsID:42
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:42 [23, 43, 45, 46]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:43
,[ThaliCore] VirtualSocket exited RunLoop vsID:43
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:43 [23, 45, 46]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:46
,[ThaliCore] VirtualSocket exited RunLoop vsID:46
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:46 [23, 45]
,2017-07-21 08:02:30 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNRESET","status":500}'
,2017-07-21 08:02:30 - DEBUG thaliReplicationPeerAction: 'Got error in update: 500 socket hang up -1, but we are already killed and so we ignored it'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:798FE329-CA2C-48EB-8C64-3BEA2692A145:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:798FE329-CA2C-48EB-8C64-3BEA2692A145:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:47 [23, 45, 47]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-21 08:02:30 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:72759949-905B-4F26-99D5-EC97C00BEAC3
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:47
[ThaliCore] VirtualSocket.closeStreams() vsID:47
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:47
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] VirtualSocket.deinit vsID:47 [23, 45]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-21 08:02:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 08:02:30 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"FA1EB5BA-D365-4DBE-9591-19F3D61E10A8","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-21 08:02:30 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"798FE329-CA2C-48EB-8C64-3BEA2692A145","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:02:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 08:02:30 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
,2017-07-21 08:02:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,[ThaliCore] VirtualSocket exited RunLoop vsID:23
[ThaliCore] VirtualSocket.deinit vsID:23 [45]
,2017-07-21 08:02:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:02:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:02:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:45
[ThaliCore] VirtualSocket.closeS,treams() vsID:45
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:45
,[ThaliCore] VirtualSocket.deinit vsID:45 []
,ok 869 passed
,# teardown
,# setup
,# Coordinated replication action test - should throw error when wrong remote db name is provided
,2017-07-21 08:02:31 - DEBUG thaliMobileNativeWrapper: 'listening 57401'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:07228FCA-DEF9-4E7F-95C3-638A9B94BF6A
,[ThaliCore] Browser.startListening
,2017-07-21 08:02:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "7FE17ECE-9559-451B-8C09-89E0B0DFA7BF", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:7FE17ECE-9559-451B-8C09-89E0B0DFA7BF
,2017-07-21 08:02:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D48E2020-BCEB-46C0-9637-2F5F95561B8D
[ThaliCore] Session.startOutputStream(with:) peer:D48E2020-BCEB-46C0-9637-2F5F95561B8D
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4,8 [48]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=0 "Undefined error: 0" UserInfo={NSLocalizedDescription=Undefi,ned error: 0, NSLocalizedFailureReason=Error in connect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:48
[ThaliCore] VirtualSock,et.closeStreams() vsID:48
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D48E2020-BCEB-46C0-9637-2F5F95561B8D
[ThaliCore] Session.startOutputStream(with:) peer:D48E2020-BCEB-46C0-9637-2F5F95561B8D
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4,9 [48, 49]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedDescription=Connection refused, NSLocalizedFailureReason=Error in connect() ,function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:49
[ThaliCore] VirtualSocket.closeStreams() vsID:49
[ThaliCore] AdvertiserRelay.did,CloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:49
[ThaliCore] VirtualSocket.deinit vsID:49 [48]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3BC99E38-DFA3-444D-847D-934C08CEAD4F
[ThaliCore] Session.startOutputStream(with:) peer:3BC99E38-DFA3-444D-847D-934C08CEAD4F
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:50 [48, 50]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=1 "Operation not permitted" UserInfo={NSLocalizedDescription=Operation not permitted, NSLocalizedFailureReason=Error in c,onnect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:50
[ThaliCore] VirtualSocket.closeStreams() vsID:50
[ThaliCore] Advertiser,Relay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:798FE329-CA2C-48EB-8C64-3BEA2692A145:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "798FE329-CA2C-48EB-8C64-3BEA2692A145", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FA1EB5BA-D365-4DBE-9591-19F3D61E10A8:0
2017-07-21 08:02:32 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdent,ifier":"798FE329-CA2C-48EB-8C64-3BEA2692A145","generation":0}]'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FA1EB5BA-D365-4DBE-9591-19F3D61E10A8", generation: 0)
2017-07-21 08:02:32 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"798FE329-CA2C-48EB-8C64-3BEA2692A145","generation":0}'
2017-07-21 08:02:32 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,,"peerIdentifier":"FA1EB5BA-D365-4DBE-9591-19F3D61E10A8","generation":0}]'
,2017-07-21 08:02:32 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"FA1EB5BA-D365-4DBE-9591-19F3D61E10A8","generation":0}'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3BC99E38-DFA3-444D-847D-934C08CEAD4F
[ThaliCore] Session.startOutputStream(with:) peer:3BC99E38-DFA3-444D-847D-934C08CEAD4F
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:51 [48, 50, 51]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=0 "Undefined error: 0" UserInfo={NSLocalizedDescription=Undefined error: 0, NSLocalizedFailureReason=Error in connect() f,unction})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:51
[ThaliCore] VirtualSocket.closeStreams() vsID:51
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:51
,[ThaliCore] VirtualSocket.deinit vsID:51 [48, 50]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D48E2020-BCEB-46C0-9637-2F5F95561B8D
[ThaliCore] Session.startOutputStream(with:) peer:D48E2020-BCEB-46C0-9637-2F5F95561B8D
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5,2 [48, 50, 52]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=0 "Undefined error: 0" UserInfo={NSLocalizedDescription=Undefined error: 0, NSLocalizedFailureReason=Error in connect() f,unction})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:52
[ThaliCore] VirtualSocket.closeStreams() vsID:52
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:52
,[ThaliCore] VirtualSocket.deinit vsID:52 [48, 50]
,2017-07-21 08:02:32 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"798FE329-CA2C-48EB-8C64-3BEA2692A145","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 08:02:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"798FE329-CA2C-48EB-8C64-3BEA2692A145","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 08:02:32 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"FA1EB5BA-D365-4DBE-9591-19F3D61E10A8","peerAvailable":true,"generation":0,"portNumber":null}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:713A7165-53BE-4979-B6FF-1B1C4676AEBF:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "713A7165-53BE-4979-B6FF-1B1C4676AEBF", generation: 0)
,2017-07-21 08:02:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"FA1EB5BA-D365-4DBE-9591-19F3D61E10A8","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 08:02:32 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 798FE329-CA2C-48EB-8C64-3BEA2692A145 (syncValue: 5)'
,2017-07-21 08:02:32 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "798FE329-CA2C-48EB-8C64-3BEA2692A145", generation: 0) found active relay
,2017-07-21 08:02:32 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"5","error":null,"portNumber":57392}'
,2017-07-21 08:02:32 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for FA1EB5BA-D365-4DBE-9591-19F3D61E10A8 (syncValue: 6)'
,2017-07-21 08:02:32 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "FA1EB5BA-D365-4DBE-9591-19F3D61E10A8", generation: 0) found active relay
,2017-07-21 08:02:32 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"6","error":null,"portNumber":57366}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:798FE329-CA2C-48EB-8C64-3BEA2692A145:0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[Th,aliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:FA1EB5BA-D365-4DBE-9591-19F3D61E10A8:0
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A74787B1-5250-4D60-858F-332648519D4E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A74787B1-5250-4D60-858F-332648519D4E", generation: 0)
[ThaliCore] Session.session(_,:didReceive:withName:fromPeer:) peer:FA1EB5BA-D365-4DBE-9591-19F3D61E10A8:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:53 [48, 50, 53]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:798FE329-CA2C-48EB-8C64-3BEA2692A145:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:54 [48, 50, 53, 54]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:54
[ThaliCore] VirtualSocket.closeStreams() vsID:54
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:54
[ThaliCore] VirtualSocket.deinit vsID:54 [48, 50, 53]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket r,emoved, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:53
[ThaliCore] VirtualSocket.closeStreams() vsID:53
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] VirtualSocket exited RunLoop vsID:53
[ThaliCore] VirtualSocket.deinit vsID:53 [48, 50]
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E2806D10-630D-4F19-A090-FDA0F3CE6A37
[ThaliCore] Session.session(_:peer:didChange:) peer:E2806D10-630D-4F19-A090-FDA0F3CE6A37 state: notConnected -> connecting
[ThaliCore] Advertis,er: session connected Peer(uuid: "7FE17ECE-9559-451B-8C09-89E0B0DFA7BF", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
,2017-07-21 08:02:32 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,2017-07-21 08:02:32 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,2017-07-21 08:02:32 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"713A7165-53BE-4979-B6FF-1B1C4676AEBF","generation":0}]'
2017-07-21 08:02:32 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"713A7165-53BE-4979-B6FF-1B1C4676AEBF","generation":0}'
2017-07-21 08:02:32 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native, layer [{"peerAvailable":true,"peerIdentifier":"A74787B1-5250-4D60-858F-332648519D4E","generation":0}]'
2017-07-21 08:02:32 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"A74787B1-5,250-4D60-858F-332648519D4E","generation":0}'
,2017-07-21 08:02:32 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"713A7165-53BE-4979-B6FF-1B1C4676AEBF","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 08:02:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"713A7165-53BE-4979-B6FF-1B1C4676AEBF","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 08:02:32 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"A74787B1-5250-4D60-858F-332648519D4E","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 08:02:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"A74787B1-5250-4D60-858F-332648519D4E","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 08:02:32 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 713A7165-53BE-4979-B6FF-1B1C4676AEBF (syncValue: 7)'
,2017-07-21 08:02:32 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "713A7165-53BE-4979-B6FF-1B1C4676AEBF", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "713A7165-53BE-4979-B6FF-1B1C4676AEBF", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:713A7165-53BE-4979-B6FF-1B1C4676AEBF:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7FE17ECE-9559-451B-8C09-89E0B0DFA7BF:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7FE17ECE-9559-451B-8C09-89E0B0DFA7BF", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:713A7165-53BE-4979-B6FF-1B1C4676AEBF:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:FA1EB5BA-D365-4DBE-9591-19F3D61E10A8:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "FA1EB5BA-D365-4DBE-9591-19F3D61E10A8", generation: 0)
[ThaliCore] BrowserRelay.closeRelay() state:connec,ted
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:57366
[ThaliCore] Session.disconnect() peer:FA1EB5BA-D365-4DBE-9591-19F3D61E10A8:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[,ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:FA1EB5BA-D365-4DBE-9591-19F3D61E10A8:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "FA1EB5BA-D365-4DBE-9591-19F3D61E10A8", generation: 0) relay removed
[ThaliCore] BrowserRelay.deinit
,2017-07-21 08:02:34 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"FA1EB5BA-D365-4DBE-9591-19F3D61E10A8","generation":0}]'
,2017-07-21 08:02:34 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"FA1EB5BA-D365-4DBE-9591-19F3D61E10A8","generation":0}'
,2017-07-21 08:02:34 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"FA1EB5BA-D365-4DBE-9591-19F3D61E10A8","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-21 08:02:34 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"FA1EB5BA-D365-4DBE-9591-19F3D61E10A8","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-21 08:02:34 - WARN thaliNotificationClient: 'peer is not available'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:E2806D10-630D-4F19-A090-FDA0F3CE6A37
,[ThaliCore] Session.session(_:peer:didChange:) peer:E2806D10-630D-4F19-A090-FDA0F3CE6A37 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:713A7165-53BE-4979-B6FF-1B1C4676AEBF:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:713A7165-53BE-4979-B6FF-1B1C4676AEBF:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "713A7165-53BE-4979-B6FF-1B1C4676AEBF", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57411
,2017-07-21 08:02:35 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"7","error":null,"portNumber":57411}'
,2017-07-21 08:02:35 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for A74787B1-5250-4D60-858F-332648519D4E (syncValue: 8)'
,2017-07-21 08:02:35 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A74787B1-5250-4D60-858F-332648519D4E", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A74787B1-5250-4D60-858F-332648519D4E", generation: 0)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E2806D10-630D-4F19-A090-FDA0F3CE6A37
[ThaliCore] Session.startOutputStream(with:) peer:E2806D10-630D-4F19-A090-FDA0F3CE6A37
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5,5 [48, 50, 55]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:A74787B1-5250-4D60-858F-332648519D4E:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FF3F4E8E-43EA-4E8A-B997-DA2DB9722F24
[ThaliCore] Advertiser: session connected Peer(uuid: "7FE17ECE-9559-451B-8C09-89E0B0DFA7BF", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:FF3F4E8E-43EA-4E8A-B997-DA2DB9722F24 state: notConnected -> connecting
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:713A7165-53BE-4979-B6FF-1B1C4676AEBF:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:713A7165-53BE-4979-B6FF-1B1C4676AEBF:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:56 [48, 50, 55, 56]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:56
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:56
,[ThaliCore] VirtualSocket.deinit vsID:56 [48, 50, 55]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:713A7165-53BE-4979-B6FF-1B1C4676AEBF:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:713A7165-53BE-4979-B6FF-1B1C4676AEBF:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:57 [48, 50, 55, 57]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:55
[ThaliCore] VirtualSocket.closeStreams() vsID:55
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:,55
[ThaliCore] VirtualSocket.deinit vsID:55 [48, 50, 57]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E2806D10-630D-4F19-A090-FDA0F3CE6A37
[ThaliCore] Session.startOutputStream(with:) peer:E2806D10-630D-4F19-A090-FDA0F3CE6A37
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5,8 [48, 50, 57, 58]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:A74787B1-5250-4D60-858F-332648519D4E:0 state: notConnected -> connecting
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:58
[ThaliCore] VirtualSocket.closeStreams() vsID:58
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:58
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] VirtualSocket.deinit vsID:58 [48, 50, 57]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-21 08:02:36 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  404 no_db_file'
,2017-07-21 08:02:36 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: no_db_file  and it caused us to complete'
,ok 870 error should be 'no_db_file'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:57
[ThaliCore] VirtualSocket exited RunLoop vsID:57
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:57 [48, 50]
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:798FE329-CA2C-48EB-8C64-3BEA2692A145:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "798FE329-CA2C-48EB-8C64-3BEA2692A145", generation: 0)
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:57392
[ThaliCore] Session.disconnect() peer:798FE329-CA2C-48EB-8C64-3BEA2692A145:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[Thali,Core] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:D48E2020-BCEB-46C0-9637-2F5F95561B8D state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "72759949-905B-4F26-99D5-EC97C00BEAC3", generation: 0)
,[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:3BC99E38-DFA3-444D-847D-934C08CEAD4,F
,[ThaliCore] Session.deinit peer:3BC99E38-DFA3-444D-847D-934C08CEAD4F
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:798FE329-CA2C-48EB-8C64-3BEA2692A145:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "798FE329-CA2C-48EB-8C64-3BEA2692A145", generation: 0) relay removed
,[ThaliCore] BrowserRelay.deinit
,2017-07-21 08:02:36 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"798FE329-CA2C-48EB-8C64-3BEA2692A145","generation":0}]'
,2017-07-21 08:02:36 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"798FE329-CA2C-48EB-8C64-3BEA2692A145","generation":0}'
,2017-07-21 08:02:36 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"798FE329-CA2C-48EB-8C64-3BEA2692A145","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-21 08:02:36 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"798FE329-CA2C-48EB-8C64-3BEA2692A145","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-21 08:02:36 - WARN thaliNotificationClient: 'peer is not available'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:A74787B1-5250-4D60-858F-332648519D4E:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:A74787B1-5250-4D60-858F-332648519D4E:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "A74787B1-5250-4D60-858F-332648519D4E", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57417
2017-07-21 08:02:38 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"8","error":null,"portNumber":57417}'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:FF3F4E8E-43EA-4E8A-B997-DA2DB9722F24
2017-07-21 08:02:38 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for FA1EB5BA-D365-4DBE-9591-19F3D61E10A8 (syncValue: 9),'
2017-07-21 08:02:38 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "FA1EB5BA-D365-4DBE-9591-19F3D61E10A8", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FA1EB5BA-D365-4DBE-9591-19F3D61E10A8", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:FF3F4E8E-43EA-4E8A-B997-DA2DB9722F24 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FF3F4E8E-43EA-4E8A-B997-DA2DB9722F24
,[ThaliCore] Session.startOutputStream(with:) peer:FF3F4E8E-43EA-4E8A-B997-DA2DB9722F24
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:59 [48, 50, 59]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 08:02:39 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"9","error":"Peer is unavailable","portNumber":null}'
,2017-07-21 08:02:39 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"FA1EB5BA-D365-4DBE-9591-19F3D61E10A8","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-21 08:02:39 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"FA1EB5BA-D365-4DBE-9591-19F3D61E10A8","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 08:02:39 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 798FE329-CA2C-48EB-8C64-3BEA2692A145 (syncValue: 10)'
,2017-07-21 08:02:39 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "798FE329-CA2C-48EB-8C64-3BEA2692A145", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "798FE329-CA2C-48EB-8C64-3BEA2692A145", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
,2017-07-21 08:02:39 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"10","error":"Peer is unavailable","portNumber":null}'
,2017-07-21 08:02:39 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"798FE329-CA2C-48EB-8C64-3BEA2692A145","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-21 08:02:39 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"798FE329-CA2C-48EB-8C64-3BEA2692A145","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 08:02:39 - DEBUG thaliPeerPoolDefault: 'Got err   Peer is unavailable'
,2017-07-21 08:02:39 - DEBUG thaliPeerPoolDefault: 'Got err   Peer is unavailable'
,2017-07-21 08:02:39 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"FA1EB5BA-D365-4DBE-9591-19F3D61E10A8","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:A74787B1-5250-4D60-858F-332648519D4E:0
,2017-07-21 08:02:39 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"FA1EB5BA-D365-4DBE-9591-19F3D61E10A8","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 08:02:39 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"798FE329-CA2C-48EB-8C64-3BEA2692A145","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-21 08:02:39 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"798FE329-CA2C-48EB-8C64-3BEA2692A145","peerAvailable":true,"portNumber":null,"recreated":true}'
,[ThaliCore] BrowserManager.disconnect peer:FA1EB5BA-D365-4DBE-9591-19F3D61E10A8
,[ThaliCore] BrowserManager.disconnect peer:798FE329-CA2C-48EB-8C64-3BEA2692A145
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A74787B1-5250-4D60-858F-332648519D4E:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:60 [48, 50, 59, 60]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:59
[ThaliCore] VirtualSocket.closeStreams() vsID:59
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:59
[ThaliCore] VirtualSocket.deinit vsID:59 [48, 50, 60]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) c,lient disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FF3F4E8E-43EA-4E8A-B997-DA2DB9722F24
[ThaliCore] Session.startOutputStream(with:) peer:FF3F4E8E-43EA-4E8A-B997-DA2DB9722F24
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6,1 [48, 50, 60, 61]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:60
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:60
[ThaliCore] VirtualSocket.deinit vsID:60 [48, 50, 61]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:A74787B1-5250-4D60-858F-332648519D4E:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A74787B1-5250-4D60-858F-332648519D4E:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:62 [48, 50, 61, 62]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-21 08:02:39 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  404 no_db_file'
,2017-07-21 08:02:39 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: no_db_file  and it caused us to complete'
,ok 871 error should be 'no_db_file'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:62
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:62
[ThaliCore] VirtualSocket.deinit vsID:62 [48, 50, 61]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:61
[ThaliCore] VirtualSocket.closeStreams() vsID:61
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:61
,[ThaliCore] VirtualSocket.deinit vsID:61 [48, 50]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSoc,ketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:7FE17ECE-9559-451B-8C09-89E0B0DFA7BF
,2017-07-21 08:02:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 08:02:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"713A7165-53BE-4979-B6FF-1B1C4676AEBF","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-21 08:02:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"A74787B1-5250-4D60-858F-332648519D4E","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:02:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 08:02:39 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
,2017-07-21 08:02:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,[ThaliCore] VirtualSocket exited RunLoop vsID:48
[ThaliCore] VirtualSocket.deinit vsID:48 [50]
,2017-07-21 08:02:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:02:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:02:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 872 passed
,# teardown
,[ThaliCore] Session.session(_:peer:didChange:) peer:FF3F4E8E-43EA-4E8A-B997-DA2DB9722F24 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "7FE17ECE-9559-451B-8C09-89E0B0DFA7BF", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:FF3F4E8E-43EA-4E8A-B997-DA2DB9722F24
[ThaliCore] Advert,iserRelay.deinit
,[ThaliCore] Session.deinit peer:FF3F4E8E-43EA-4E8A-B997-DA2DB9722F24
,# setup
,# compareBufferArrays
,ok 873 should throw
ok 874 should throw
ok 875 (unnamed assert)
ok 876 (unnamed assert)
ok 877 (unnamed assert)
ok 878 (unnamed assert)
,ok 879 (unnamed assert)
,# teardown
,# setup
,# Call start twice and get error
,ok 880 should throw
,# teardown
,# setup
,# Start and make sure it runs
,# teardown
,# setup
,# Make sure getTimeWhenRun is right after start
,ok 881 (unnamed assert)
,# teardown
,# setup
,# Make sure getTimeWhenRun is -1 after function is called
,ok 882 should be equal
,# teardown
,# setup
,# Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running
,ok 883 should be equal
ok 884 should be equal
ok 885 should throw
,# teardown
,# setup
,# Test TransientState
,ok 886 should throw
,ok 887 should throw
,ok 888 should be equal
,ok 889 should be equal
,ok 890 should be equal
,ok 891 should be equal
,ok 892 (unnamed assert)
,ok 893 (unnamed assert)
,# teardown
,# setup
,# No peers and empty database
,ok 894 verify failed
,ok 895 constructor called once
,ok 896 constructor called with right args
,ok 897 match start arg
,ok 898 start called once
,ok 899 stop called once
,ok 900 stop after start
,# teardown
,# setup
,# One peer and empty DB
,2017-07-21 08:03:07 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 901 verify failed
,ok 902 constructor called once
,ok 903 constructor called with right args
,ok 904 match start arg
,ok 905 start called once
,ok 906 stop called once
,ok 907 stop after start
,# teardown
,# setup
,# One peer with _Local set behind current seq
,2017-07-21 08:03:08 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 908 verify failed
,ok 909 constructor called once
,ok 910 constructor called with right args
,ok 911 match start arg
,ok 912 start called once
,ok 913 stop called once
,ok 914 stop after start
,# teardown
,# setup
,# One peer with _Local set equal to current seq
,2017-07-21 08:03:08 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 915 verify failed
,ok 916 constructor called once
,ok 917 constructor called with right args
ok 918 match start arg
ok 919 start called once
ok 920 stop called once
ok 921 stop after start
,# teardown
,# setup
,# One peer with _Local set ahead of current seq (and no this should not happen)
,2017-07-21 08:03:09 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 922 verify failed
,ok 923 constructor called once
,ok 924 constructor called with right args
,ok 925 match start arg
,ok 926 start called once
,ok 927 stop called once
,ok 928 stop after start
,# teardown
,# setup
,# Three peers, one not in DB, one behind and one ahead
,2017-07-21 08:03:10 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 929 verify failed
,ok 930 constructor called once
,ok 931 constructor called with right args
,ok 932 match start arg
,ok 933 start called once
,ok 934 stop called once
,ok 935 stop after start
,# teardown
,# setup
,# More than maximum peers, make sure we only send maximum allowed
,2017-07-21 08:03:12 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 936 verify failed
,ok 937 constructor called once
,ok 938 constructor called with right args
,ok 939 match start arg
,ok 940 start called once
,ok 941 stop called once
,ok 942 stop after start
,# teardown
,# setup
,# two peers with empty DB, update the doc
,2017-07-21 08:03:12 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,2017-07-21 08:03:12 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 943 verify failed
,ok 944 constructor called once
,ok 945 constructor called with right args
,ok 946 last start before stop
,ok 947 empty first start
,ok 948 full second start
,ok 949 only 2 timers
,# teardown
,# setup
,# add doc and make sure tokens refresh when they expire
,2017-07-21 08:03:13 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,2017-07-21 08:03:13 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,2017-07-21 08:03:13 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
ok 950 verify failed
ok 951 constructor called once
ok 952 constructor called with right args
ok 953 start befor,e stop
ok 954 We got at least 3 calls to start
ok 955 at least 3
ok 956 default 1
ok 957 1 run
ok 958 default 2
ok 959 2 run
ok 960 default 3
,# teardown
,# setup
,# start and stop and start and stop
,ok 961 start out null
,2017-07-21 08:03:13 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 962 back to null
,2017-07-21 08:03:13 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
ok 963 still null
,ok 964 verify failed
,ok 965 constructor called once
,ok 966 constructor called with right args
,ok 967 first start before first stop
,ok 968 first stop before second start
,ok 969 second start before second stop
,# teardown
,# setup
,# two identical starts in a row
,2017-07-21 08:03:15 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 970 verify failed
,ok 971 constructor called once
,ok 972 constructor called with right args
,ok 973 (unnamed assert)
,# teardown
,# setup
,# two different starts in a row
,2017-07-21 08:03:15 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 974 verify failed
ok 975 constructor called once
,ok 976 constructor called with right args
,ok 977 (unnamed assert)
,ok 978 (unnamed assert)
,# teardown
,# setup
,# two stops and a start and two stops
,2017-07-21 08:03:16 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 979 verify failed
,ok 980 constructor called once
,ok 981 constructor called with right args
,ok 982 start before stop
,# teardown
,# setup
,# we properly enqueue requests so no then needed
,2017-07-21 08:03:16 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 983 verify failed
,ok 984 constructor called once
,ok 985 constructor called with right args
,ok 986 start before stop
,# teardown
,# setup
,# test calculateSeqPointKeyId
,ok 987 should be equal
ok 988 should be equal
,# teardown
,# setup
,# #_doImmediateSeqUpdate - server is not there
,2017-07-21 08:03:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 08:03:18 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}'
,ok 989 Got right error
,# teardown
,2017-07-21 08:03:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - server accepts & closes connection
,2017-07-21 08:03:19 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNRESET","status":500}'
,ok 990 Got socket hang up
,# teardown
,2017-07-21 08:03:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - server always returns 500
,2017-07-21 08:03:21 - DEBUG localSeqManager: 'Got an error trying to update seq []'
,ok 991 Got 500 as expected
,# teardown
,2017-07-21 08:03:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - create new seq doc
,ok 992 should be equal
,ok 993 revs are equal
,# teardown
,2017-07-21 08:03:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - doc exists, need to get rev and update
,ok 994 should be equal
,ok 995 revs are equal
,# teardown
,2017-07-21 08:03:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - update seq three times
,ok 996 should be equal
,ok 997 revs are equal
,ok 998 should be equal
,ok 999 revs are equal
,ok 1000 should be equal
,ok 1001 revs are equal
,# teardown
,2017-07-21 08:03:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - rev got changed under us
,(node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
,Trace: 
    at $3.prototype.trace@console.js:139:8
    at addListener@events.js:140:1
    at module.exports@/private/var/containers/Bundle/Application/1F438D99-FC6B-4E94-B928-15DE93A9EB98/ThaliTest.app/www/jxcore/node_modules/pouchdb-all-dbs/lib/index.j,s:82:3
    at module.exports/<.start/<@/private/var/containers/Bundle/Application/1F438D99-FC6B-4E94-B928-15DE93A9EB98/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/lib/index.js:143:9
    at tryCatcher@/private/var/containers/Bundle/Application/1,F438D99-FC6B-4E94-B928-15DE93A9EB98/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/util.js:16:16
    at module.exports/Promise.prototype._settlePromiseFromHandler@/private/var/containers/Bundle/Application/1F438D99-,FC6B-4E94-B928-15DE93A9EB98/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:504:13
,2017-07-21 08:03:30 - DEBUG localSeqManager: 'Got an error trying to update seq {"error":"conflict","reason":"Document update conflict","name":"conflict","status":409,"message":"Document update conflict"}'
,ok 1002 Our rev is old so we should fail
,# teardown
,2017-07-21 08:03:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - fail if stop is called
,ok 1003 confirm stop caused failure
,(node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
,Trace: 
    at $3.prototype.trace@console.js:139:8
    at addListener@events.js:140:1
    at module.exports@/private/var/containers/Bundle/Application/1F438D99-FC6B-4E94-B928-15DE93A9EB98/ThaliTest.app/www/jxcore/node_modules/pouchdb-all-dbs/lib/index.j,s:57:3
    at module.exports/<.start/<@/private/var/containers/Bundle/Application/1F438D99-FC6B-4E94-B928-15DE93A9EB98/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/lib/index.js:143:9
    at tryCatcher@/private/var/containers/Bundle/Application/1,F438D99-FC6B-4E94-B928-15DE93A9EB98/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/util.js:16:16
    at module.exports/Promise.prototype._settlePromiseFromHandler@/private/var/containers/Bundle/Application/1F438D99-,FC6B-4E94-B928-15DE93A9EB98/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:504:13
,# teardown
,2017-07-21 08:03:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - stop after get but before put fails right
,2017-07-21 08:03:31 - DEBUG localSeqManager: 'Got an error trying to update seq {"onPut":true}'
,ok 1004 stop caused us to fail
,ok 1005 We specifically failed on a stop before put
,# teardown
,2017-07-21 08:03:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - fail if stop is called
,ok 1006 failed due to stop
,ok 1007 failed due to stop
,# teardown
,2017-07-21 08:03:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - set seq for first time
,ok 1008 should be equal
,# teardown
,2017-07-21 08:03:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - Fail on bad seq value
,2017-07-21 08:03:35 - DEBUG localSeqManager: 'Got a bad seq, submitted seq 9, _nextSeqValueToSend: 10'
,ok 1009 Expected bad seq error
,# teardown
,2017-07-21 08:03:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - do we cancel timer properly on an immediate?
,ok 1010 Different promises
,ok 1011 Timer was cancelled
,ok 1012 should be equal
,# teardown
,2017-07-21 08:03:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - do we wait for blocked update
,ok 1013 One go and one blocked
,ok 1014 All blocked
,ok 1015 Still blocked
,ok 1016 should be equal
,# teardown
,2017-07-21 08:03:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - test that we wait long enough
,ok 1017 We waited long enough
,ok 1018 should be equal
,# teardown
,2017-07-21 08:03:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - test that we pick up new sequences while we wait
,ok 1019 Should have gotten same timer promise
,ok 1020 Still same timer promise
,ok 1021 We waited long enough
,ok 1022 should be equal
,# teardown
,2017-07-21 08:03:45 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Coordinated seq test
,2017-07-21 08:03:45 - DEBUG CoordinatedClient: 'test was skipped, name: 'Coordinated seq test''
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:03:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:03:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,# setup
,# test thali manager spies
,2017-07-21 08:03:46 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
,2017-07-21 08:03:46 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
,2017-07-21 08:03:46 - DEBUG thaliManager: 'creating express pouchdb instance'
,ok 1023 expressPouchDB was called once
,ok 1024 expressPouchDB was called with 2 arguments
,ok 1025 expressPouchDB was called with 'PouchDB' as 1-st argument
,ok 1026 expressPouchDB was called with 'expressPouchDB options' as 2-st argument
,ok 1027 PouchDB was called once
,ok 1028 PouchDB was called with 1 arguments
,ok 1029 PouchDB was called with 'dbName' as 1-st argument
,ok 1030 ThaliSendNotificationBasedOnReplication was called once
,ok 1031 ThaliSendNotificationBasedOnReplication was called with 4 arguments
,ok 1032 ThaliSendNotificationBasedOnReplication was called with 'express.Router instance' as 1-st argument
,ok 1033 ThaliSendNotificationBasedOnReplication was called with 'ecdhForLocalDevice' as 2-st argument
,ok 1034 ThaliSendNotificationBasedOnReplication was called with 'thaliConfig.BEACON_MILLISECONDS_TO_EXPIRE' as 3-st argument
,ok 1035 ThaliSendNotificationBasedOnReplication was called with 'PouchDB instance' as 4-st argument
,ok 1036 ThaliPullReplicationFromNotification was called once
,ok 1037 ThaliPullReplicationFromNotification was called with 4 arguments
,ok 1038 ThaliPullReplicationFromNotification was called with 'PouchDB' as 1-st argument
,ok 1039 ThaliPullReplicationFromNotification was called with 'dbName' as 2-st argument
,ok 1040 ThaliPullReplicationFromNotification was called with 'ThaliPeerPoolInterface instance' as 3-st argument
,ok 1041 ThaliPullReplicationFromNotification was called with 'ecdhForLocalDevice' as 4-st argument
,ok 1042 Salti was called once
,ok 1043 Salti was called with 4 arguments
,ok 1044 Salti was called with 'dbName' as 1-st argument
,ok 1045 Salti was called with 'acl' as 2-st argument
,ok 1046 Salti was called with 'thaliIdCallback' as 3-st argument
,ok 1047 Salti was called with 'options' as 4-st argument
,2017-07-21 08:03:46 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
,2017-07-21 08:03:46 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-07-21 08:03:46 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-07-21 08:03:46 - DEBUG thaliMobileNativeWrapper: 'listening 57491'
,2017-07-21 08:03:46 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:B98DB6A1-2487-4ACF-B42E-CCF8A66447A0
[ThaliCore] Browser.startListening
,2017-07-21 08:03:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 08:03:46 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "A5B4DACC-925B-4A41-9974-A096667B15DB", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:A5B4DACC-925B-4A41-9974-A096667B15DB
,2017-07-21 08:03:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 08:03:46 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
,ok 1048 ThaliMobile.start was called once
,ok 1049 ThaliMobile.start was called with 3 arguments
,ok 1050 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
,ok 1051 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
,ok 1052 ThaliMobile.start was called with 'networkType' as 3-st argument
,ok 1053 ThaliMobile.startListeningForAdvertisements was called once
,ok 1054 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
,ok 1055 ThaliMobile.startUpdateAdvertisingAndListening was called once
,ok 1056 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
,ok 1057 ThaliSendNotificationBasedOnReplication.prototype.start was called once
,ok 1058 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
,ok 1059 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
,ok 1060 ThaliPullReplicationFromNotification.prototype.start was called once
,ok 1061 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
,ok 1062 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
,2017-07-21 08:03:46 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:A5B4DACC-925B-4A41-9974-A096667B15DB
,2017-07-21 08:03:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 08:03:46 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})',
,2017-07-21 08:03:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 08:03:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:03:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:03:46 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 1063 ThaliMobile.stop was called once
,ok 1064 ThaliMobile.stop was called with 0 arguments
,ok 1065 ThaliSendNotificationBasedOnReplication.prototype.stop was called once
,ok 1066 ThaliSendNotificationBasedOnReplication.prototype.stop was called with 0 arguments
,ok 1067 ThaliPullReplicationFromNotification.prototype.stop was called once
,ok 1068 ThaliPullReplicationFromNotification.prototype.stop was called with 0 arguments
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:03:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:03:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,# teardown
,# setup
,# test thali manager multiple starts and stops
,2017-07-21 08:03:47 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
,2017-07-21 08:03:47 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
,2017-07-21 08:03:47 - DEBUG thaliManager: 'creating express pouchdb instance'
,ok 1069 expressPouchDB was called once
,ok 1070 expressPouchDB was called with 2 arguments
,ok 1071 expressPouchDB was called with 'PouchDB' as 1-st argument
,ok 1072 expressPouchDB was called with 'expressPouchDB options' as 2-st argument
,ok 1073 PouchDB was called once
,ok 1074 PouchDB was called with 1 arguments
,ok 1075 PouchDB was called with 'dbName' as 1-st argument
,ok 1076 ThaliSendNotificationBasedOnReplication was called once
,ok 1077 ThaliSendNotificationBasedOnReplication was called with 4 arguments
,ok 1078 ThaliSendNotificationBasedOnReplication was called with 'express.Router instance' as 1-st argument
,ok 1079 ThaliSendNotificationBasedOnReplication was called with 'ecdhForLocalDevice' as 2-st argument
,ok 1080 ThaliSendNotificationBasedOnReplication was called with 'thaliConfig.BEACON_MILLISECONDS_TO_EXPIRE' as 3-st argument
,ok 1081 ThaliSendNotificationBasedOnReplication was called with 'PouchDB instance' as 4-st argument
,ok 1082 ThaliPullReplicationFromNotification was called once
,ok 1083 ThaliPullReplicationFromNotification was called with 4 arguments
,ok 1084 ThaliPullReplicationFromNotification was called with 'PouchDB' as 1-st argument
,ok 1085 ThaliPullReplicationFromNotification was called with 'dbName' as 2-st argument
,ok 1086 ThaliPullReplicationFromNotification was called with 'ThaliPeerPoolInterface instance' as 3-st argument
,ok 1087 ThaliPullReplicationFromNotification was called with 'ecdhForLocalDevice' as 4-st argument
,ok 1088 Salti was called once
,ok 1089 Salti was called with 4 arguments
,ok 1090 Salti was called with 'dbName' as 1-st argument
,ok 1091 Salti was called with 'acl' as 2-st argument
,ok 1092 Salti was called with 'thaliIdCallback' as 3-st argument
,ok 1093 Salti was called with 'options' as 4-st argument
,2017-07-21 08:03:47 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
,2017-07-21 08:03:47 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-07-21 08:03:47 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-07-21 08:03:47 - DEBUG thaliMobileNativeWrapper: 'listening 57493'
,2017-07-21 08:03:47 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:0A030815-3329-4369-994E-3A77C075CC84
,[ThaliCore] Browser.startListening
,2017-07-21 08:03:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 08:03:47 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "575D74B0-F56B-4B93-A390-958991D8FA87", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:575D74B0-F56B-4B93-A390-958991D8FA87
,2017-07-21 08:03:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 08:03:47 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
,ok 1094 ThaliMobile.start was called once
,ok 1095 ThaliMobile.start was called with 3 arguments
,ok 1096 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
,ok 1097 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
,ok 1098 ThaliMobile.start was called with 'networkType' as 3-st argument
,ok 1099 ThaliMobile.startListeningForAdvertisements was called once
,ok 1100 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
,ok 1101 ThaliMobile.startUpdateAdvertisingAndListening was called once
,ok 1102 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
,ok 1103 ThaliSendNotificationBasedOnReplication.prototype.start was called once
,ok 1104 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
,ok 1105 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
,ok 1106 ThaliPullReplicationFromNotification.prototype.start was called once
,ok 1107 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
,ok 1108 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
,2017-07-21 08:03:48 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:575D74B0-F56B-4B93-A390-958991D8FA87
,2017-07-21 08:03:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 08:03:48 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})',
,2017-07-21 08:03:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 08:03:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:03:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:03:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:03:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:03:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 1109 ThaliMobile.stop was called once
,ok 1110 ThaliMobile.stop was called with 0 arguments
,ok 1111 ThaliSendNotificationBasedOnReplication.prototype.stop was called once
,ok 1112 ThaliSendNotificationBasedOnReplication.prototype.stop was called with 0 arguments
,ok 1113 ThaliPullReplicationFromNotification.prototype.stop was called once
,ok 1114 ThaliPullReplicationFromNotification.prototype.stop was called with 0 arguments
,2017-07-21 08:03:48 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
,2017-07-21 08:03:48 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-07-21 08:03:48 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-07-21 08:03:48 - DEBUG thaliMobileNativeWrapper: 'listening 57495'
,2017-07-21 08:03:48 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:F8669E6F-3C9A-44DE-BF9F-CFDE09823B35
,[ThaliCore] Browser.startListening
,2017-07-21 08:03:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 08:03:48 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "80E6C825-72F7-4B71-85F6-4C0573AB3FF4", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:80E6C825-72F7-4B71-85F6-4C0573AB3FF4
,2017-07-21 08:03:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 08:03:48 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
,2017-07-21 08:03:48 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:80E6C825-72F7-4B71-85F6-4C0573AB3FF4
,2017-07-21 08:03:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 08:03:48 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})',
,2017-07-21 08:03:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 08:03:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:03:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:03:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:03:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:03:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:03:48 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
,2017-07-21 08:03:48 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-07-21 08:03:48 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-07-21 08:03:48 - DEBUG thaliMobileNativeWrapper: 'listening 57497'
,2017-07-21 08:03:48 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:35AE9EF2-4BA0-4810-8684-0E622B35EE44
,[ThaliCore] Browser.startListening
,2017-07-21 08:03:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 08:03:48 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "6C24E95D-07D7-4DB4-9868-EB1143CBB5D9", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:6C24E95D-07D7-4DB4-9868-EB1143CBB5D9
,2017-07-21 08:03:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 08:03:48 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
,2017-07-21 08:03:48 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:6C24E95D-07D7-4DB4-9868-EB1143CBB5D9
,2017-07-21 08:03:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 08:03:48 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})'
,2017-07-21 08:03:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 08:03:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:03:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:03:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:03:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:03:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:03:48 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
,2017-07-21 08:03:48 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-07-21 08:03:48 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-07-21 08:03:48 - DEBUG thaliMobileNativeWrapper: 'listening 57499'
,2017-07-21 08:03:48 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:AC5C63CD-F7C4-4234-80B3-DDCA96F421FA
,[ThaliCore] Browser.startListening
,2017-07-21 08:03:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 08:03:48 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "5B2F51A5-45D5-4DBA-B2DD-A8AE2DB5346A", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:5B2F51A5-45D5-4DBA-B2DD-A8AE2DB5346A
,2017-07-21 08:03:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 08:03:48 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
,ok 1115 ThaliMobile.start was called once
,ok 1116 ThaliMobile.start was called with 3 arguments
,ok 1117 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
,ok 1118 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
,ok 1119 ThaliMobile.start was called with 'networkType' as 3-st argument
,ok 1120 ThaliMobile.startListeningForAdvertisements was called once
,ok 1121 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
,ok 1122 ThaliMobile.startUpdateAdvertisingAndListening was called once
,ok 1123 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
,ok 1124 ThaliSendNotificationBasedOnReplication.prototype.start was called once
,ok 1125 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
,ok 1126 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
,ok 1127 ThaliPullReplicationFromNotification.prototype.start was called once
,ok 1128 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
,ok 1129 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
,2017-07-21 08:03:48 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:5B2F51A5-45D5-4DBA-B2DD-A8AE2DB5346A
,2017-07-21 08:03:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 08:03:48 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})'
,2017-07-21 08:03:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 08:03:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:03:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:03:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:03:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:03:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,# teardown
,# setup
,# ssdp server and client should be restarted when wifi toggled
,2017-07-21 08:03:48 - DEBUG CoordinatedClient: 'test was skipped, name: 'ssdp server and client should be restarted when wifi toggled''
,# teardown
,# setup
,# ssdp server and client should be restarted when bssid changed
,2017-07-21 08:03:49 - DEBUG CoordinatedClient: 'test was skipped, name: 'ssdp server and client should be restarted when bssid changed''
,# teardown
,# setup
,# ssdp server and client should be restarted only when advertising/listening is active
,2017-07-21 08:03:49 - DEBUG CoordinatedClient: 'test was skipped, name: 'ssdp server and client should be restarted only when advertising/listening is active''
,# teardown
,2017-07-21 08:03:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll can close even when connections open'
,2017-07-21 08:03:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll with promise'
,2017-07-21 08:03:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning set to false'
,2017-07-21 08:03:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll works even with a server that is not listening yet witheatNotRunning set to true'
,2017-07-21 08:03:49 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on a single db change'
,2017-07-21 08:03:49 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of multiple onCheckpointReached handlers on a single db change'
,2017-07-21 08:03:49 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval'
,2017-07-21 08:03:49 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval'
,2017-07-21 08:03:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultDirectory'
,2017-07-21 08:03:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultAdapter'
,2017-07-21 08:03:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueue and run in order'
,2017-07-21 08:03:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueueAtTop and run backwards'
,2017-07-21 08:03:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - mix enqueue and enqueueAtTop'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - queues handled independently'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueued function are always executed asynchronously'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - exceptions in the executor are properly handled'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - basic'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - another'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - skip'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - another skip'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox spy'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub override'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox mock'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox restore after test end'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can pass data in setup'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Correctly parses/stringifies USN'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerLost calls jxcore'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerDiscovered calls jxcore'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopListeningForAdvertisements'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startListeningForAdvertisements twice is NOT an error'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling stopListeningForAdvertisements without calling start is NOT an error'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopUpdateAdvertisingAndListening'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startUpdateAdvertisingAndListening twice is NOT an error'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call stopUpdateAdvertisingAndListening twice without start and it is not an error'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChange is called'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can connect to a remote peer'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data via parallel connections'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data securely'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift large amounts of data'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We do not emit peerAvailabilityChanged events until one of the start methods is called'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Test updating advertising and parallel data transfer'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - discoveryAdvertisingStateUpdateNonTCP is called'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - cannot call connect when start listening for advertisements is not active'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Get error when trying to double connect to a peer on Android'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect when start listening for advertisements is not active'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with illegal peerID'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiConnect properly fails on legal but non-existent peerID'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with invalid syncValue'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call disconnect with invalid peer id'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - disconnect doesn't fail on plausible but bogus peer ID'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Get same port when trying to connect multiple times on iOS'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - initial peer discovery'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 1'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 2'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - check latest peer discovery'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Set up for no peer discovery test'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - no peer discovery'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling createNativeListener directly rejects'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits incomingConnectionState'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits routerPortConnectionFailed'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server connections all up'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming stream cleans outgoing socket'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming connection cleans outgoing socket'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing outgoing socket cleans associated mux stream'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing the whole server cleans everything up'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - we can get a ton of connections and data through and still clean up the server completely'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - simulate mux failure, make sure everything is cleaned up'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - timing out the incoming connection cleans everything up'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can create servers manager'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling stop without start causes error'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can start/stop servers manager'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - starting twice resolves with listening port'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminateIncomingConnection will terminate a connection'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminate an Outgoing connection'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single local http request'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single coordinated request ios native'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Multiple local http requests'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Multiple coordinated request ios native'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startListeningForAdvertisements should fail if start not called'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if start not called'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopListeningForAdvertisements many times'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startListeningForAdvertisements many times'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startUpdateAdvertisingAndListening many times'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopAdvertisingAndListening many times'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get the network status before starting'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - error returned with bad router'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - all services are started when we call start'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - TCP Servers Manager should be null when we call start on iOS'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - all services are stopped when we call stop'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure terminateConnection is properly hooked up'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure terminateConnection is return error if we get called on iOS'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure terminateListener is properly hooked up'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure terminateListener is return error if we get called on iOS'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure we actually call kill connections properly'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire failedNativeConnection event when we get failedConnection from multiConnectConnection'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure bad PSK connections fail'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - peer changes handled from a queue'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - relaying discoveryAdvertisingStateUpdateNonTCP'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - we successfully receive and replay discoveryAdvertisingStateUpdate'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - can do HTTP requests between peers'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - can still do HTTP requests between peers with coordinator'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - calls correct starts when network changes'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test to coordinate connection cut'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can do HTTP requests after connections are cut'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - will fail bad PSK connection between peers'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We provide notification when a listener dies and we recreate it'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startListeningForAdvertisements should fail if start not called'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if start not called'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopListeningForAdvertisements many times'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startListeningForAdvertisements many times'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startUpdateAdvertisingAndListening many times'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopAdvertisingAndListening many times'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #start - Causing native or wifi to fail will cause a promise reject '
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #start should fail if called twice in a row'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - does not emit duplicate discoveryAdvertisingStateUpdate'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - does not send duplicate availability changes'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get the network status'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer added/removed to/from cache (native)'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer added/removed to/from cache (wifi)'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - new peer is cached'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - native available - peer with same port and different generation is cached (BLUETOOTH)'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - peer with greater generation is cached (MPCF)'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - peer with same or older generation is ignored (MPCF)'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native unavailable - new peer is ignored'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native unavailable - cached peer is removed'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - networkChanged - fires peerAvailabilityChanged event for wifi peers'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiconnect failure - new peer is ignored (MPCF)'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - newAddressPort field (TCP_NATIVE)'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - newAddressPort field (BLUETOOTH)'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - newAddressPort field (MPCF)'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - error when peer has not been discovered yet'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - returns discovered cached wifi peer'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #disconnect fails on wifi peers'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #disconnect delegates native peers to the native wrapper'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes emitted correctly'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes not emitted in started state'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes not emitted in stopped state'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We properly fire peer unavailable and then available when connection fails on Android'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We properly fire peer unavailable and then available when connection fails on iOS'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - does not fire duplicate events after peer listener recreation'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #stop should change peers'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - peer should be found once after listening and discovery started'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get data from all participants'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - test for data corruption'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - test getters'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - start and kill'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - double start'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - start after kill'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - make sure ids are unique'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - check that forever agent can be destroyed'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test PeerDictionary basic functionality'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test PeerDictionary with multiple entries.'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - RESOLVED entries are removed before WAITING state entry.'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - WAITING entries are removed before CONTROLLED_BY_POOL state entry.'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - When CONTROLLED_BY_POOL entry is removed and kill is called.'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - single action'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - multiple actions'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - PSK Pool works'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - stop'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure that start verifies queue length'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - bad enqueues'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - do not allow same object type'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure we catch kill and dequeue'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure that stop removes all actions'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We reject unrecognized connection type'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We reject unrecognized action type'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - One action on bluetooth'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Two notification actions'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - replicateThroughProblems'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Replication goes first'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - wifi allows many parallel non-replication actions'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - wifi allows no more than 2 simultaneous replication actions for same peerID'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Client to server request coordinated'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test BEACONS_RETRIEVED_AND_PARSED locally'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Test HTTP_BAD_RESPONSE locally'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test NETWORK_PROBLEM locally'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Action fails when getPeerHostInfo fails'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the start two times'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill before calling the start'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill immediately after the start'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill while waiting a response from the server'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test to exceed the max content size locally'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Close the server socket while the client is waiting a response from the server. Local test.'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Close the client socket while the client is waiting a response from the server. Local test.'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons bad args'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons empty keys to notify'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons multiple keys to notify'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid expiration in beaconStreamWithPreAmble'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons expiration out of range lower'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons expiration out of range lower'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons no beacons returns null'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback fails decrypt'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #parseBeacons addressBookCallback returns no matches'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns spurious match'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns public key'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskIdentityField'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskSecret'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskSecrets'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generateBeaconStreamAndSecrets'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Add two Peers.'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - TCP_NATIVE peer loses DNS'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Received beacons with no values for us'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Notification action killed with a superseded'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Resolves an action locally'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Emits error event when peerPool.enqueue throws'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Resolves an action locally using ThaliPeerPoolDefault'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Action fails because of a bad hostname.'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - hostaddress is removed when the action is running. '
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - notificationClient does not retry action with BAD_PEER resolution'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - notification client correctly handles peer availability changes of the same peer'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Client to server request locally'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache clean and expiration'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache getSecret and getPublic'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache multiple entries'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Start and stop ThaliNotificationServer'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass an empty array to ThaliNotificationServer.start'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass a string to ThaliNotificationServer.start'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass an empty parameter to ThaliNotificationServer.start'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeacons'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeacons (no keys)'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeaconsbefore calling start'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure peerDictionaryKey is reasonable'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure start works'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure stop works'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Emits error event when peerPool.enqueue throws'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Simple peer event'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Coordinated pull replication from notification test'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server is not there'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server accepts & closes connection'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server always returns 500'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server always returns 401'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server always returns 403'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure docs replicate with remote db with same name as local db'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure docs replicate with remote db with different name than local db'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Do nothing and make sure we time out'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Do something and make sure we time out'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Start replicating and then catch error when server goes'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure clone works'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Coordinated replication action test - each device has the same local db name'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Coordinated replication action test - each device has different local db name'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Coordinated replication action test - should throw error when wrong remote db name is provided'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - compareBufferArrays'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call start twice and get error'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Start and make sure it runs'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure getTimeWhenRun is right after start'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure getTimeWhenRun is -1 after function is called'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test TransientState'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - No peers and empty database'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - One peer and empty DB'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - One peer with _Local set behind current seq'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - One peer with _Local set equal to current seq'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - One peer with _Local set ahead of current seq (and no this should not happen)'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Three peers, one not in DB, one behind and one ahead'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - More than maximum peers, make sure we only send maximum allowed'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - two peers with empty DB, update the doc'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - add doc and make sure tokens refresh when they expire'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - start and stop and start and stop'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - two identical starts in a row'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - two different starts in a row'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - two stops and a start and two stops'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - we properly enqueue requests so no then needed'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test calculateSeqPointKeyId'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - server is not there'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - server accepts & closes connection'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - server always returns 500'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - create new seq doc'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - doc exists, need to get rev and update'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - update seq three times'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - rev got changed under us'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - fail if stop is called'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - stop after get but before put fails right'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #update - fail if stop is called'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #update - set seq for first time'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #update - Fail on bad seq value'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #update - do we cancel timer properly on an immediate?'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #update - do we wait for blocked update'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #update - test that we wait long enough'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #update - test that we pick up new sequences while we wait'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Coordinated seq test'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test thali manager spies'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test thali manager multiple starts and stops'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - ssdp server and client should be restarted when wifi toggled'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - ssdp server and client should be restarted when bssid changed'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - ssdp server and client should be restarted only when advertising/listening is active'
,2017-07-21 08:03:50 - DEBUG CoordinatedClient: 'all unit tests succeeded, platformName: 'ios''
,2017-07-21 08:03:50 - DEBUG CoordinatedClient: 'all tests completed'
,2017-07-21 08:03:50 - DEBUG CoordinatedClient: 'test client disconnected'
,2017-07-21 08:03:50 - DEBUG CoordinatedClient: 'test client succeed'
,2017-07-21 08:03:50 - DEBUG CoordinatedThaliTape: 'all tests succeed'
,2017-07-21 08:03:50 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****'

```
