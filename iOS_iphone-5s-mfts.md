#### Test 113351851151165c_iOS_iphone-5s-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/113351851151165c/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6s Plus 'Iphone6sPlus-1' (f70cda60583ea0f895d05ea355cd125983c27594).
,(lldb) command source -s 0 '/tmp/171AD8AD-87C7-422C-BDB4-8F116634ED16/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'
,Executing commands in '/tmp/171AD8AD-87C7-422C-BDB4-8F116634ED16/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/113351851151165c/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/113351851151165c/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/16C0A5F0-CF84-4126-ACE0-BE4A6E75D474/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:65533"
,(lldb)     command script import "/tmp/171AD8AD-87C7-422C-BDB4-8F116634ED16/fruitstrap_bffa901fefdea07f59339a6737776943349f5077.py"
,(lldb)     command script add -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.safequit_command safequit
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
,2017-07-18 09:50:39 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:50:39 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:50:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:50:39 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:50:39 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:50:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:50:39 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
,AppContextTests.test_didEnterForeground finished
AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
,AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
AppContextTests.test_esonValue finished
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "B3985C51-DDBF-4ED6-91,E9-CD46E753E5DE", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:B3985C51-DDBF-4ED6-91E9-CD46E753E5DE
Optional(true)
Optional(false)
,AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:07A27D75-A774-42ED-9A82-323C300DBE69
[ThaliCore] Browser,.startListening
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:0C873694-,E7B7-4EDE-8858-5F6ACC2ADACB
[ThaliCore] Browser.startListening
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "90A6EF44-291D-45DD-8AD9-17807C18CA13", generation: 0)
[ThaliCore] Advertiser.startAdvertisi,ng with peerID:90A6EF44-291D-45DD-8AD9-17807C18CA13
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:90A6EF44-291D-45DD-8AD9-17807C18CA13:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "90A6EF44-291D-45DD-8AD9-17807C18CA13", generation: 0)
,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
AppContextTests.test_connectReturnValueCo,rrect finished
AppContextTests finished
All tests finished
All tests finished
,2017-07-18 09:50:41 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
Number of passed tests:  13
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  1.608029961585999
,2017-07-18 09:50:41 - DEBUG UnitTest_app: 'My device name is: 'Apple-iphone-5s-mfts''
,2017-07-18 09:50:41 - WARN testUtils: 'myNameCallback not set!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:90A6EF44-291D-45DD-8AD9-17807C18CA13:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "90A6EF44-291D-45DD-8AD9-17807C18CA13", generation: 0)
,2017-07-18 09:50:44 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-07-18 09:50:44 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/16C0A5F0-CF84-4126-ACE0-BE4A6E75D474/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-07-18 09:50:44 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/16C0A5F0-CF84-4126-ACE0-BE4A6E75D474/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-07-18 09:50:45 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/16C0A5F0-CF84-4126-ACE0-BE4A6E75D474/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-07-18 09:50:45 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/16C0A5F0-CF84-4126-ACE0-BE4A6E75D474/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-07-18 09:50:45 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/16C0A5F0-CF84-4126-ACE0-BE4A6E75D474/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-07-18 09:50:45 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/16C0A5F0-CF84-4126-ACE0-BE4A6E75D474/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-07-18 09:50:45 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/16C0A5F0-CF84-4126-ACE0-BE4A6E75D474/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-07-18 09:50:45 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/16C0A5F0-CF84-4126-ACE0-BE4A6E75D474/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-07-18 09:50:45 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/16C0A5F0-CF84-4126-ACE0-BE4A6E75D474/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-07-18 09:50:45 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/16C0A5F0-CF84-4126-ACE0-BE4A6E75D474/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-07-18 09:50:45 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/16C0A5F0-CF84-4126-ACE0-BE4A6E75D474/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-07-18 09:50:45 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/16C0A5F0-CF84-4126-ACE0-BE4A6E75D474/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-07-18 09:50:46 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/16C0A5F0-CF84-4126-ACE0-BE4A6E75D474/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-07-18 09:50:46 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/16C0A5F0-CF84-4126-ACE0-BE4A6E75D474/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-07-18 09:50:46 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/16C0A5F0-CF84-4126-ACE0-BE4A6E75D474/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-07-18 09:50:46 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/16C0A5F0-CF84-4126-ACE0-BE4A6E75D474/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-07-18 09:50:46 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/16C0A5F0-CF84-4126-ACE0-BE4A6E75D474/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-07-18 09:50:46 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/16C0A5F0-CF84-4126-ACE0-BE4A6E75D474/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-07-18 09:50:46 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/16C0A5F0-CF84-4126-ACE0-BE4A6E75D474/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-07-18 09:50:46 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/16C0A5F0-CF84-4126-ACE0-BE4A6E75D474/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-07-18 09:50:46 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/16C0A5F0-CF84-4126-ACE0-BE4A6E75D474/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-07-18 09:50:46 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/16C0A5F0-CF84-4126-ACE0-BE4A6E75D474/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-07-18 09:50:46 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/16C0A5F0-CF84-4126-ACE0-BE4A6E75D474/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-07-18 09:50:46 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/16C0A5F0-CF84-4126-ACE0-BE4A6E75D474/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-07-18 09:50:46 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/16C0A5F0-CF84-4126-ACE0-BE4A6E75D474/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-07-18 09:50:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/16C0A5F0-CF84-4126-ACE0-BE4A6E75D474/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-07-18 09:50:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/16C0A5F0-CF84-4126-ACE0-BE4A6E75D474/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-07-18 09:50:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/16C0A5F0-CF84-4126-ACE0-BE4A6E75D474/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-07-18 09:50:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/16C0A5F0-CF84-4126-ACE0-BE4A6E75D474/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-07-18 09:50:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/16C0A5F0-CF84-4126-ACE0-BE4A6E75D474/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-07-18 09:50:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/16C0A5F0-CF84-4126-ACE0-BE4A6E75D474/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-07-18 09:50:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/16C0A5F0-CF84-4126-ACE0-BE4A6E75D474/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-07-18 09:50:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/16C0A5F0-CF84-4126-ACE0-BE4A6E75D474/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-07-18 09:50:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/16C0A5F0-CF84-4126-ACE0-BE4A6E75D474/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-07-18 09:50:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/16C0A5F0-CF84-4126-ACE0-BE4A6E75D474/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-07-18 09:50:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/16C0A5F0-CF84-4126-ACE0-BE4A6E75D474/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-07-18 09:50:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/16C0A5F0-CF84-4126-ACE0-BE4A6E75D474/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-07-18 09:50:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/16C0A5F0-CF84-4126-ACE0-BE4A6E75D474/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-07-18 09:50:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/16C0A5F0-CF84-4126-ACE0-BE4A6E75D474/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-07-18 09:50:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/16C0A5F0-CF84-4126-ACE0-BE4A6E75D474/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-07-18 09:50:48 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-07-18 09:50:49 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
,2017-07-18 09:50:49 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
,# setup
,# closeAll can close even when connections open
,2017-07-18 09:50:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 1 not possible to connect to the server anymore
# teardown
,# setup
,# closeAll with promise
,2017-07-18 09:50:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 2 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll properly throws when closing a non open server with eatNotRunning set to false
,2017-07-18 09:50:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
,# teardown
,# setup
,# closeAll works even with a server that is not listening yet witheatNotRunning set to true
,2017-07-18 09:51:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
,# setup
,# Call of onCheckpointReached handler on a single db change
,2017-07-18 09:51:01 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on a single db change''
,# teardown
,# setup
,# Call of multiple onCheckpointReached handlers on a single db change
,2017-07-18 09:51:02 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of multiple onCheckpointReached handlers on a single db change''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
,2017-07-18 09:51:02 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
,2017-07-18 09:51:03 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''
,# teardown
,# setup
,# test defaultDirectory
,ok 4 should be equal
,ok 5 should be equal
,ok 6 should be equal
,# teardown
,# setup
,# test defaultAdapter
,ok 7 should be equal
,ok 8 should be equal
,ok 9 should be equal
,ok 10 should be equal
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
ok 25 thirdPromise - in resolve
ok 26 secondPromise - second to run
ok 27 secondPromise - in catch
,ok 28 firstPromise - third to run
ok 29 firstPromise - in then
ok 30 testing promises
,# teardown
,# setup
,# mix enqueue and enqueueAtTop
,ok 31 fourth
,ok 32 fourth
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
,2017-07-18 09:51:09 - DEBUG CoordinatedClient: 'test was skipped, name: 'skip''
,# teardown
,# setup
,# another skip
,2017-07-18 09:51:09 - DEBUG CoordinatedClient: 'test was skipped, name: 'another skip''
,# teardown
,# setup
,# test sinon sansbox spy
,2017-07-18 09:51:10 - DEBUG testTests: 'test spy method for global sinon sansbox'
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
ok 58 throws if usn has invalid prefix
ok 59 throws if usn has invalid identifier format
,ok 60 throws if usn has invalid generation
ok 61 correctly stringifies peer
,# teardown
,# setup
,# onPeerLost calls jxcore
,2017-07-18 09:51:14 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
,# teardown
,2017-07-18 09:51:15 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:51:15 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:51:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:51:15 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:51:15 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:51:15 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:51:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:51:15 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# onPeerDiscovered calls jxcore
,2017-07-18 09:51:15 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
,# teardown
,2017-07-18 09:51:15 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:51:15 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:51:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:51:15 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-18 09:51:15 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:51:15 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:51:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:51:15 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopListeningForAdvertisements
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:1A59F5AF-A501-4D56-ADD0-71115CB3A50A
[ThaliCore] Browser.startListening
2017-07-18 09:51:16 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-18 09:51:16 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:51:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 62 Can call startLis,teningForAdvertisements without error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-18 09:51:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:51:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 63 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-18 09:51:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:51:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 64 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-18 09:51:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisin,gActive":false}'
2017-07-18 09:51:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 65 Should be able to call stopAdvertisingAndListening in teardown
,2017-07-18 09:51:16 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:51:16 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:51:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:51:16 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:51:16 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:51:16 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:51:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:51:16 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startListeningForAdvertisements twice is NOT an error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C18A84FB-FD76-40DC-98D9-78A6C751FF26
[ThaliCore] Browser.startListening
2017-07-18 09:51:17 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-18 09:51:17 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:51:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 66 Can call startLis,teningForAdvertisements without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-07-18 09:51:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-18 09:51:17 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-18 09:51:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 67 Can call startListeningForAdvertisements twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-18 09:51:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:51:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 68 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-18 09:51:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:51:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 69 Should be able to call stopAdvertisingAndListening in teardown
,2017-07-18 09:51:17 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:51:17 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:51:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:51:17 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:51:17 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:51:17 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:51:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:51:17 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling stopListeningForAdvertisements without calling start is NOT an error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-18 09:51:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:51:18 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 70 Can call stopListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-18 09:51:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdver,tisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:51:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 71 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-18 09:51:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:51:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 72 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-18 09:51:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:51:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 73 Should be able to call stopAdvertisingAndListening in teardown
,2017-07-18 09:51:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:51:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:51:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:51:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:51:18 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:51:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:51:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:51:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopUpdateAdvertisingAndListening
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "236FE5CB-E285-4CA4-BECF-7641A6366EC4", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:236FE5CB-E285-4CA4-BECF-7641A6366EC4
2017-07-18 0,9:51:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-18 09:51:19 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:51:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 74 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:236FE5CB-E285-4CA4-BECF-7641A6366EC4
,2017-07-18 09:51:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:51:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 75 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-18 09:51:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:51:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 76 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-18 09:51:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:51:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 77 Should be able to call stopAdvertisingAndListening in teardown
,2017-07-18 09:51:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:51:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:51:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:51:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:51:19 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:51:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:51:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:51:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startUpdateAdvertisingAndListening twice is NOT an error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "DDAAFC3B-2A9A-4931-9F38-DD213668A5C5", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:DDAAFC3B-2A9A-4931-9F38-DD213668A5C5
2017-07-18 0,9:51:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-18 09:51:19 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:51:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 78 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "DDAAFC3B-2A9A-4931-9F38-DD213668A5C5", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:DDAAFC3B-2A9A-4931-9F38-DD213668A5C5
,2017-07-18 09:51:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-18 09:51:19 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-18 09:51:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 79 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-18 09:51:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-18 09:51:20 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-18 09:51:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 80 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:DDAAFC3B-2A9A-4931-9F38-DD213668A5C5
,[ThaliCore] Advertiser.stopAdvertising() peerID:DDAAFC3B-2A9A-4931-9F38-DD213668A5C5
,2017-07-18 09:51:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:51:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 81 Should be able to call stopAdvertisingAndListening in teardown
,2017-07-18 09:51:20 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:51:20 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:51:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:51:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:51:20 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:51:20 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:51:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:51:20 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-18 09:51:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:51:21 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
ok 82 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-18 09:51:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNon,TCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:51:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 83 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-18 09:51:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:51:21 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 84 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-18 09:51:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdver,tisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:51:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 85 Should be able to call stopAdvertisingAndListening in teard,own
,2017-07-18 09:51:21 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-18 09:51:21 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:51:21 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:51:21 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:51:21 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:51:21 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:51:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:51:21 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peerAvailabilityChange is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "80D74A42-61EC-45BE-AA90-5C1DF610E490", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:80D74A42-61EC-45BE-AA90-5C1DF610E490
2017-07-18 09:51:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-18 09:51:22, - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkTy,pe":null}})'
2017-07-18 09:51:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 86 Can call startUpdateAdvertisingAndListeningwithout error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[Thali,Core] Browser.init(serviceType:foundPeer:lostPeer:) peer:68D5BA2F-109F-412A-BCB1-4CDAAF111E8D
[ThaliCore] Browser.startListening
2017-07-18 09:51:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"adver,tisingActive":true}'
2017-07-18 09:51:22 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"rout,er":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:51:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 87 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:ADD621AC-46A0-4CE2-9B2B-724F599DC244:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "ADD621AC-46A0-4CE2-9B2B-724F599DC244", generation: 0)
,ok 88 peers must be an array
,ok 89 peers must not be zero-length
,ok 90 peer must have only peerIdentifier, peerAvailable and generation properties
,ok 91 peerIdentifier must be a string
ok 92 generation must be a number
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F2901452-AE22-4CB3-96E1-1C614499BC0E:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F2901452-AE22-4CB3-96E1-1C614499BC0E", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:80D74A42-61EC-45BE-AA90-5C1DF610E490:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "80D74A42-61EC-45BE-AA90-5C1DF610E490", generation: 0)
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-18 09:51:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-18 09:51:24 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-18 09:51:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 93 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:80D74A42-61EC-45BE-AA90-5C1DF610E490
,2017-07-18 09:51:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:51:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 94 Should be able to call stopAdvertisingAndListening in teardown
,2017-07-18 09:51:24 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:51:24 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:51:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:51:24 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:51:24 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:51:24 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:51:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:51:24 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can connect to a remote peer
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "5F321996-1BF0-489C-8C70-3A82EC46FE51", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:5F321996-1BF0-489C-8C70-3A82EC46FE51
2017-07-18 0,9:51:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-18 09:51:40 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:51:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
,ok 95 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:57725109-4D9E-4D84-A112-79A625B1D5D7
[ThaliCore] Browser.startListe,ning
2017-07-18 09:51:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-18 09:51:40 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":tru,e}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:51:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisi,ngStateUpdate (was in stopped state).'
ok 96 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E7823D58-1DBC-4490-B24C-D54ABF468217:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E7823D58-1DBC-4490-B24C-D54ABF468217", generation: 0)
,2017-07-18 09:51:41 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"E7823D58-1DBC-4490-B24C-D54ABF468217","generation":0}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:60D5D6A0-54FF-41BD,-9405-55F97D5EB615:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "60D5D6A0-54FF-41BD-9405-55F97D5EB615", generation: 0)
,2017-07-18 09:51:41 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for E7823D58-1DBC-4490-B24C-D54ABF468217 (syncValue: hxYNzYy6itxA8yB23iaPRRpT4x6japPL)'
,2017-07-18 09:51:41 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E7823D58-1DBC-4490-B24C-D54ABF468217", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E7823D58-1DBC-4490-B24C-D54ABF468217", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E7823D58-1DBC-4490-B24C-D54ABF468217:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-18 09:51:41 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"60D5D6A0-54FF-41BD-9405-55F97D5EB615","generation":0}'
2017-07-18 09:51:41 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-,18 09:51:41 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5F321996-1BF0-489C-8C70-3A82EC46FE51:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5F321996-1BF0-489C-8C70-3A82EC46FE51", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:E7823D58-1DBC-4490-B24C-D54ABF468217:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:E7823D58-1DBC-4490-B24C-D54ABF468217:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:E7823D58-1DBC-4490-B24C-D54ABF468217:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "E7823D58-1DBC-4490-B24C-D54ABF468217", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:53157
,2017-07-18 09:51:44 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"hxYNzYy6itxA8yB23iaPRRpT4x6japPL","error":null,"portNumber":53157}'
,2017-07-18 09:51:44 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'hxYNzYy6itxA8yB23iaPRRpT4x6japPL', error: 'null', listeningPort: '53157''
,2017-07-18 09:51:44 - INFO testThaliMobileNative: ''
,ok 97 Must have listeningPort
,ok 98 listeningPort must be a number
,ok 99 listening port should not be 0
,# teardown
,[ThaliCore] Session.session(_:peer:didChange:) peer:E7823D58-1DBC-4490-B24C-D54ABF468217:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() po,rt:53157
[ThaliCore] Session.disconnect() peer:E7823D58-1DBC-4490-B24C-D54ABF468217:0
[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "E7823D58-1DBC-4490-B24C-D54ABF468217", generation: 0)
,2017-07-18 09:51:44 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"hxYNzYy6itxA8yB23iaPRRpT4x6japPL","error":"Session disconnected","portNumber":null}'
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket erro,r:nil
[ThaliCore] TCPListener.deinit
2017-07-18 09:51:44 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"E7823D58-1DBC-4490-B24C-D54ABF468217","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-18 09:51:44 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-18 09:51:44 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"E7823D58-1DBC-4490-B24C-D54ABF468217","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-18 09:51:44 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Session.deinit peer:E7823D58-1DBC-4490-B24C-D54ABF468217:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:E7823D58-1DBC-4490-B24C-D54ABF468217:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "E7823D58-1DBC-4490-B24C-D54ABF468217", generation: 0)
,2017-07-18 09:51:46 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-18 09:51:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-18 ,09:51:46 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-18 09:51:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 100 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising(),
[ThaliCore] Advertiser.stopAdvertising() peerID:5F321996-1BF0-489C-8C70-3A82EC46FE51
2017-07-18 09:51:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:51:46 ,-, INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 101 Should be able to call stopAdvertisingAndListening in teardown
,[ThaliCore] BrowserManager.disconnect peer:E7823D58-1DBC-4490-B24C-D54ABF468217
,2017-07-18 09:51:46 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:51:46 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:51:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:51:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:51:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:51:46 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:51:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:51:46 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "85ED1FFD-D50E-497A-9762-800969B8B575", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:85ED1FFD-D50E-497A-9762-800969B8B575
,2017-07-18 09:51:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-18 09:51:46 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-18 09:51:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 102 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:F6EA1236-0D2D-403E-91A7-30A465099F62
,[ThaliCore] Browser.startListening
,2017-07-18 09:51:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-18 09:51:46 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-18 09:51:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 103 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:60D5D6A0-54FF-41BD-9405-55F97D5EB615:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "60D5D6A0-54FF-41BD-9405-55F97D5EB615", generation: 0)
2017-07-18 09:51:47 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"60D5D6A0-54FF-41BD-9405-55F97D5EB615","generation":0}'
,2017-07-18 09:51:47 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 60D5D6A0-54FF-41BD-9405-55F97D5EB615 (syncValue: H7BQIHT7JWuYBaBs1BpEVjlK0gGh03L7)'
,2017-07-18 09:51:47 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1A0499C8-21DB-4F11-B792-A89F6B7556D1:0
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retry,Count:completion:) Peer(uuid: "60D5D6A0-54FF-41BD-9405-55F97D5EB615", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "60D5D6A0-54FF-41BD-9405-55F97D5EB615", generation: 0)
[Thal,iCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1A0499C8-21DB-4F11-B792-A89F6B7556D1", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:60D5D6A0-54FF-41BD-9405-55F97D5EB615:0
[ThaliCore] BrowserRelay.init(s,ession:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-18 09:51:47 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"1A0499C8-21DB-4F11-B792-,A89F6B7556D1","generation":0}'
2017-07-18 09:51:47 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-18 09:51:47 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:31978CED-B0AE-4798-B7C8-849267BE9E39:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "31978CED-B0AE-4798-B7C8-849267BE9E39", generation: 0)
,2017-07-18 09:51:47 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"31978CED-B0AE-4798-B7C8-849267BE9E39","generation":0}'
2017-07-18 09:51:47 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-18 09:51:47 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-18 09:51:47 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:85ED1FFD-D50E-497A-9762-800969B8B575:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "85ED1FFD-D50E-497A-9762-800969B8B575", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:60D5D6A0-54FF-41BD-9405-55F97D5EB615:0 state: notConnected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:60D5D6A0-54FF-41BD-9405-55F97D5EB615:0
,[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "60D5D6A0-54FF-41BD-9405-55F97D5EB615", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "60D5D6A0-54FF-41BD-9405-55F97D5EB615", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "60D5D6A0-54FF-41BD-9405-55F97D5EB615", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:60D5D6A0-54FF-41BD-9405-55F97D5EB615:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:60D5D6A0-54FF-41BD-9405-55F97D5EB615:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:60D5D6A0-54FF-41BD-9405-55F97D5EB615:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:60,D5D6A0-54FF-41BD-9405-55F97D5EB615:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "60D5D6A0-54FF-41BD-9405-55F97D5EB615", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,0D5D6A0-54FF-41BD-9405-55F97D5EB615", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "60D5D6A0-54FF-41BD-9405-55F97D5EB615", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:60D5D6A0-54FF-41BD-9405-55F97D5EB615:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:60D5D6A0-54FF-41BD-9405-55F97D5EB615:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:60D5D6A0-54FF-41BD-9405-55F97D5EB615:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:60,D5D6A0-54FF-41BD-9405-55F97D5EB615:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "60D5D6A0-54FF-41BD-9405-55F97D5EB615", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,0D5D6A0-54FF-41BD-9405-55F97D5EB615", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "60D5D6A0-54FF-41BD-9405-55F97D5EB615", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:60D5D6A0-54FF-41BD-9405-55F97D5EB615:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:60D5D6A0-54FF-41BD-9405-55F97D5EB615:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:EB6D9739-6FDA-4FE1-B84C-21471DCA71A1
[ThaliCore] Advertiser: session connected Peer(uuid: "85ED1FFD-D50E-497A-9762-800969B8B575", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:EB6D9739-6FDA-4FE1-B84C-21471DCA71A1 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:60D5D6A0-54FF-41BD-9405-55F97D5EB615:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:60,D5D6A0-54FF-41BD-9405-55F97D5EB615:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "60D5D6A0-54FF-41BD-9405-55F97D5EB615", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:60D5D6A0,-54FF-41BD-9405-55F97D5EB615 error: max retries exceeded
2017-07-18 09:51:51 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"H7BQIHT7JWuYBaBs1BpEVjlK0gGh03L7","error":"Connection could not be established","portNumber":null}'
2017-0,7-18 09:51:51 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'H7BQIHT7JWuYBaBs1BpEVjlK0gGh03L7', error: 'Connection could not be established', listeningPort: '%s''
2017-07-18 09:51:51 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"60D5D6A0-54FF-41BD-9405-55F97D5EB615","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-18 09:51:51 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent, due to not being in started state'
2017-07-18 09:51:51 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"60D5D6A0-54FF-41BD-9405-55F97D5EB615","peerAvailable":true,"portNumber":null,"recreated":true}'
20,17-07-18 09:51:51 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-18 09:51:51 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-18 09:51:51 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 1A0499C8-21DB-4F11-B792-A89F6B7556D1 (syncValue: o6RS15m,kA4I2VcI0SASBzoFE930eVujx)'
2017-07-18 09:51:51 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1A0499C8-21DB-4F11-B792-A89F6B7556D1", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1A0499C8-21DB-4F11-B792-A89F6B7556D1", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1A0499C8-21DB-4F11-B792-A89F6B7556D1:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-18 09:51:51 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-18 09:51:51 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:60D5D6A0-54FF-41BD-9405-55F97D5EB615:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:1A0499C8-21DB-4F11-B792-A89F6B7556D1:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:EB6D9739-6FDA-4FE1-B84C-21471DCA71A1
,[ThaliCore] Session.session(_:peer:didChange:) peer:EB6D9739-6FDA-4FE1-B84C-21471DCA71A1 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:EB6D9739-6FDA-4FE1-B84C-21471DCA71A1
[ThaliCore] Session.startOutputStream(with:) peer:EB6D9739-6FDA-4FE1-B84C-21471DCA71A1
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1 [1]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:722798E2-AB6A-4C63-9A3F-E302DF92502A
[ThaliCore] Advertiser: session connected Peer(uuid: "85ED1FFD-D50E-497A-9762-800969B8B575", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:722798E2-AB6A-4C63-9A3F-E302DF92502A state: notConnected -> connecting
,2017-07-18 09:51:53 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
2017-07-18 09:51:53 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
2017-07-18 09:51:53 - DEBUG testThaliMobileNative: 'Server sends data bac,k to client (20 bytes):'
2017-07-18 09:51:53 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:1
,[ThaliCore] VirtualSocket.closeStreams() vsID:1
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:1
[ThaliCore] VirtualSocket.deinit vsID:1 []
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:1A0499C8-21DB-4F11-B792-A89F6B7556D1:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:1A0499C8-21DB-4F11-B792-A89F6B7556D1:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "1A0499C8-21DB-4F11-B792-A89F6B7556D1", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:53166
,2017-07-18 09:51:54 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"o6RS15mkA4I2VcI0SASBzoFE930eVujx","error":null,"portNumber":53166}'
,2017-07-18 09:51:54 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'o6RS15mkA4I2VcI0SASBzoFE930eVujx', error: 'null', listeningPort: '53166''
,Connecting to the localhost:53166
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
Connected to the localhost:53166
[ThaliCore] Session.startOutputStream(with:) peer:1A0499C8-21DB-4F11-B792-A89F6B7556D1:0
,2017-07-18 09:51:54 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-18 09:51:54 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:1A0499C8-21DB-4F11-B792-A89F6B7556D1:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2 [2]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 104 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pe,er})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:2
,# teardown
[ThaliCore] VirtualSocket exited RunLoop vsID:2
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:2 []
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:722798E2-AB6A-4C63-9A3F-E302DF92502A
,[ThaliCore] Session.session(_:peer:didChange:) peer:722798E2-AB6A-4C63-9A3F-E302DF92502A state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:722798E2-AB6A-4C63-9A3F-E302DF92502A
[ThaliCore] Session.startOutputStream(with:) peer:722798E2-AB6A-4C63-9A3F-E302DF92502A
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3, [3]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-18 09:51:56 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
2017-07-18 09:51:56 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
2017-07-18 09:51:56 - DEBUG testThaliMobileNative: 'Server sends data bac,k to client (20 bytes):'
2017-07-18 09:51:56 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:3
[ThaliCore] VirtualSocket.closeStreams() vsID:3
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-18 09:51:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-18 09:51:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-18 09:51:56 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-18 09:51:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 105 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:85ED1FFD-D50E-497A-9762-800969B8B575
,2017-07-18 09:51:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:51:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 106 Should be able to call stopAdvertisingAndListening in teardown
,[ThaliCore] BrowserManager.disconnect peer:1A0499C8-21DB-4F11-B792-A89F6B7556D1
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:53166
[ThaliCore] Session.disconnect() p,eer:1A0499C8-21DB-4F11-B792-A89F6B7556D1:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:722798E2-AB6A-4C63-9A3F-E302DF92502A state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "85ED1FFD-D50E-497A-9762-800969B8B575", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:722798E2-AB6A-4C63-9A3F-E302DF92502A
[ThaliCore] Advert,iserRelay.deinit
,[ThaliCore] Session.deinit peer:1A0499C8-21DB-4F11-B792-A89F6B7556D1:0
[ThaliCore] BrowserRelay.deinit
,2017-07-18 09:51:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:51:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:51:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:51:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:51:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:51:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:51:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:51:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,[ThaliCore] Session.deinit peer:722798E2-AB6A-4C63-9A3F-E302DF92502A
,# setup
,# Can shift data via parallel connections
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "6FF1C5AC-E652-4E94-8CF5-84D52A8E5C15", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:6FF1C5AC-E652-4E94-8CF5-84D52A8E5C15
,2017-07-18 09:51:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-18 09:51:57 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:51:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 107 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D8F1A2FC-3CA8-4908-9C55-3E5C06DA6244
[ThaliCore] Browser.startListening
,2017-07-18 09:51:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-18 09:51:57 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
[ThaliCore] Session.session(_:peer:didChange:) peer:EB6D9739-6FDA-4FE1-B84C-21471DCA71A1 state: connected -> notConnected
2017-07-18 09:51:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped, state).'
,ok 108 Can call startListeningForAdvertisements without error
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "85ED1FFD-D50E-497A-9762-800969B8B575", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1A0499C8-21DB-4F11-B792-A89F6B7556D1:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1A0499C8-21DB-4F11-B792-A89F6B7556D1", generation: 0)
2017-07-18 09:51:58 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"1A0499C8-21DB-4F11-B792-A89F6B7556D1","generation":0}'
2017-07-18 09:51:58 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 1A0499C8-21DB-4F11-B792-A89F6B7556D1, (syncValue: nd2VVm7jSny8FODwj2AmLuPnBpEOt8Pk)'
2017-07-18 09:51:58 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1A0499C8-21DB-4F11-B792-A89F6B7,556D1", generation: 0) creating a new relay
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:31978CED-B0AE-4798-B7C8-849267BE9E39:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "31978CED-B0AE-4798-B7C8-849267BE9E39", ,generation: 0)
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1A0499C8-21DB-4F11-B792-A89F6B7556D1", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1A0499C8-21DB-4F11-B79,2-A89F6B7556D1:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-18 09:51:58 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable,":true,"peerIdentifier":"31978CED-B0AE-4798-B7C8-849267BE9E39","generation":0}'
2017-07-18 09:51:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-18 09:51:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:13A16B2D-9A9A-4856-BD41-17E83D3985F1:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "13A16B2D-9A9A-4856-BD41-17E83D3985F1", generation: 0)
2017-07-18 09:51:58 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"13A16B2D-9A9A-4856-BD41-17E83D3985F1","generation":0}'
2017-07-18 09:51:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-18 09:51:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2B7CA6F7-3F9F-4284-8D14-32237A26476F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2B7CA6F7-3F9F-4284-8D14-32237A26476F", generation: 0)
2017-07-18 09:51:58 - DEBUG t,haliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6FF1C5AC-E652-4E94-8CF5-84D52A8E5C15:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6FF1C5AC-E652-4E94-8CF5-84D52A8E5C15", generation: 0)
,2017-07-18 09:51:58 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"2B7CA6F7-3F9F-4284-8D14-32237A26476F","generation":0}'
,2017-07-18 09:51:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-18 09:51:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-18 09:51:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-18 09:51:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:1A0499C8-21DB-4F11-B792-A89F6B7556D1:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:1A,0499C8-21DB-4F11-B792-A89F6B7556D1:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "1A0499C8-21DB-4F11-B792-A89F6B7556D1", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1,A0499C8-21DB-4F11-B792-A89F6B7556D1", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1A0499C8-21DB-4F11-B792-A89F6B7556D1", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:1A0499C8-21DB-4F11-B792-A89F6B7556D1:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:1A0499C8-21DB-4F11-B792-A89F6B7556D1:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:1A0499C8-21DB-4F11-B792-A89F6B7556D1:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:1A,0499C8-21DB-4F11-B792-A89F6B7556D1:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "1A0499C8-21DB-4F11-B792-A89F6B7556D1", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1,A0499C8-21DB-4F11-B792-A89F6B7556D1", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1A0499C8-21DB-4F11-B792-A89F6B7556D1", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:1A0499C8-21DB-4F11-B792-A89F6B7556D1:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:1A0499C8-21DB-4F11-B792-A89F6B7556D1:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:31978CED-B0AE-4798-B7C8-849267BE9E39:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "31978CED-B0AE-4798-B7C8-849267BE9E39", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:1A0499C8-21DB-4F11-B792-A89F6B7556D1:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:1A,0499C8-21DB-4F11-B792-A89F6B7556D1:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "1A0499C8-21DB-4F11-B792-A89F6B7556D1", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1,A0499C8-21DB-4F11-B792-A89F6B7556D1", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1A0499C8-21DB-4F11-B792-A89F6B7556D1", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:1A0499C8-21DB-4F11-B792-A89F6B7556D1:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:1A0499C8-21DB-4F11-B792-A89F6B7556D1:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:1A0499C8-21DB-4F11-B792-A89F6B7556D1:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:1A,0499C8-21DB-4F11-B792-A89F6B7556D1:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "1A0499C8-21DB-4F11-B792-A89F6B7556D1", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:1A0499C8,-21DB-4F11-B792-A89F6B7556D1 error: max retries exceeded
2017-07-18 09:52:02 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"nd2VVm7jSny8FODwj2AmLuPnBpEOt8Pk","error":"Connection could not be established","portNumber":null}'
2017-0,7-18 09:52:02 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'nd2VVm7jSny8FODwj2AmLuPnBpEOt8Pk', error: 'Connection could not be established', listeningPort: '%s''
2017-07-18 09:52:02 - DEBUG thaliMobileNativeWrapper: 'Received, peer availability changed event with {"peerIdentifier":"1A0499C8-21DB-4F11-B792-A89F6B7556D1","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-18 09:52:02 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEven,t due to not being in started state'
2017-07-18 09:52:02 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"1A0499C8-21DB-4F11-B792-A89F6B7556D1","peerAvailable":true,"portNumber":null,"recreated":true}'
2,017-07-18 09:52:02 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-18 09:52:02 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-18 09:52:02 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 13A16B2D-9A9A-4856-BD41-17E83D3985F1 (syncValue: xjhMA46,7HtvcirGvrv5jkKVmNXsGu6Uy)'
2017-07-18 09:52:02 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "13A16B2D-9A9A-4856-BD41-17E83D3985F1", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "13A16B2D-9A9A-4856-BD41-17E83D3985F1", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:13A16B2D-9A9A,-4856-BD41-17E83D3985F1:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-18 09:52:02 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-18 09:52:02 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:1A0499C8-21DB-4F11-B792-A89F6B7556D1:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:13A16B2D-9A9A-4856-BD41-17E83D3985F1:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:13A16B2D-9A9A-4856-BD41-17E83D3985F1:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:13A16B2D-9A9A-4856-BD41-17E83D3985F1:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "13A16B2D-9A9A-4856-BD41-17E83D3985F1", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:53177
,2017-07-18 09:52:05 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"xjhMA467HtvcirGvrv5jkKVmNXsGu6Uy","error":null,"portNumber":53177}'
,2017-07-18 09:52:05 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'xjhMA467HtvcirGvrv5jkKVmNXsGu6Uy', error: 'null', listeningPort: '53177''
,Connecting to the localhost:53177
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:13A16B2D-9A9A-4856-BD41-17E83D3985F1:0
,Connecting to the localhost:53177
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:13A16B2D-9A9A-4856-BD41-17E83D3985F1:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4 [3, 4]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:13A16B2D-9A9A-4856-BD41-17E83D3985F1:0
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,Connecting to the localhost:53177
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:13A16B2D-9A9A-4856-BD41-17E83D3985F1:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5 [3, 4, 5]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:13A16B2D-9A9A-4856-BD41-17E83D3985F1:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:13A16B2D-9A9A-4856-BD41-17E83D3985F1:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6 [3, 4, 5, 6]
,Connected to the localhost:53177
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,Connected to the localhost:53177
,Connected to the localhost:53177
,ok 109 correct string length
,2017-07-18 09:52:05 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 110 correct string length
,2017-07-18 09:52:06 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 111 correct string length
,2017-07-18 09:52:06 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,2017-07-18 09:52:06 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-18 09:52:06 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-18 09:52:06 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:4
,[ThaliCore] VirtualSocket exited RunLoop vsID:4
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket.deinit vsID:4 [3, 5, 6]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vs,ID:5
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,ok 112 got the same data back
,ok 113 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vs,ID:6
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:6
,[ThaliCore] VirtualSocket.deinit vsID:6 [3, 5]
,ok 114 got the same data back
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F6DF7613-A4D4-463D-BA47-6615C92DA0C6
[ThaliCore] Advertiser: session connected Peer(uuid: "6FF1C5AC-E652-4E94-8CF5-84D52A8E5C15", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:F6DF7613-A4D4-463D-BA47-6615C92DA0C6 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:F6DF7613-A4D4-463D-BA47-6615C92DA0C6
,[ThaliCore] Session.session(_:peer:didChange:) peer:F6DF7613-A4D4-463D-BA47-6615C92DA0C6 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F6DF7613-A4D4-463D-BA47-6615C92DA0C6
[ThaliCore] Session.startOutputStream(with:) peer:F6DF7613-A4D4-463D-BA47-6615C92DA0C6
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7, [3, 5, 7]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F6DF7613-A4D4-463D-BA47-6615C92DA0C6
[ThaliCore] Session.startOutputStream(with:) peer:F6DF7613-A4D4-463D-BA47-6615C92DA0C6
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8 [3, 5, 7, 8]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F6DF7613-A4D4-463D-BA47-6615C92DA0C6
[ThaliCore] Session.startOutputStream(with:) peer:F6DF7613-A4D4-463D-BA47-6615C92DA0C6
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9 [3, 5, 7, 8, 9]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,2017-07-18 09:52:09 - DEBUG testThaliMobileNative: 'Server received (5120 bytes):'
,2017-07-18 09:52:09 - DEBUG testThaliMobileNative: 'Server received (11264 bytes):'
,2017-07-18 09:52:09 - DEBUG testThaliMobileNative: 'Server received all data: jbkjIXax73BwfQ72wOLGpbY6f8RSXmQVBoQM4YiHoi4PLRhFvvnaSRbHNMbxFzz1aj0qfGiX0eXJihhpFcLZFUmqp7YkdH3A3kygjeLMu90mVsBGvbUvAZ04WbVbZZ6Tx4YzHXgBS4gohKlJJ0DkPFop2lR5HIvAfHMZVezuhP7dunZIvL,ldOckpo0gsyoNGaVCi6bMnedVLUDW3aCAmQnlQM3v0zfxf7w1wNQkxFUCQNlUR32hLkjng6FpfEz35ZAQan0kowuNBULQiVDisGa2dwQYOdEEGLAkVY0dpSdrdsWGcwC580jFF7C3vQZ7qHlhnI8guVncSQolq7JSYqMWvmE94AfU4n8J6nm2C4e9jzJeL6tPys0Qx8VTe9tpQIRMeGS6Y3lrkW6BidjxwUKl0vPFCB1PgXfGSzd1oK8xAsrYYGt,96uf6GZO08LFSvTmhjRG9OAYEL7UcfyTFhcnmRl3p5QPSCKiEXo34WX7xD81UmETcc9qordIs0SoSba4be418bBe5ERxcFLBfMCVlTHKviYTq94ABCsTYwECZyXBWRuVcqzozs4wNEOkMeIVZJKsdpVp9fPSIpDhwlJL8uMH9ALt7v7w42kEtsaPNei38q1PBf2Viu9jeCbiludnG8dkpgb2j66KVRhxhxRT6rvSWvbGEJOWJySELoPfU9J1YraN,GxkBHxHtZiL6OL5xUGAFJvxyOZTJZejtuo3tZFrFf146gcEx2EIQuajq8QyS963lrv1zmzL9nHam0MRlMIxddGakPSAtzK31iqAUzXYB5pHVKLalQC0Kqse5kcKESSVXaq4OR3pNhoONybKZ5OOd5BeYdG1W8QQOYEVgZtSTxxyM3kjFOLM0Kxz0x9PxgiwPAlSRHzT9bfpx8DubXeo00ox2UZ9Nuj0f9Ij5uHEhnOJwuipn3YCBB2GECEdBRCgR,HQ5LBjN5pHja4GjZxhGtuaBcMnrietGl4eqQFgZD7UPGlaWQ2S9bQt8mM764OqarAztvGaPOnCsAVIs0cyI2bkFavlfQTOxslx3VXgyZFSbWolTr5eF7Z9NVzSM37KU30eQ7ldCWSk1zO3Rx8UgAHHW9baOSrPCdql7xjJlEs21zPmWcQehzikkwfrLJKUjophZBq68Q5k375DqgDvKNm5UewdCnETogvFS98f3eInXsEvA9RbFe7EbGeJsXQqBd,1S7LCYUSkOKJYP6q58Vm2HWQgHOWWpmbjTfp7hO3D79TYPuBYeKG3VSahK6c1xTvHYe9COrhCKlByTe1OYD4MWxJ1QflbK2Y3uORYyhfJydrHT8ONicF1K0Su3oEuTf0G1e8WIEZls6PkzK7A1j7J0E94hyWYHy65nlinLSwuRaeQkMDpLa32OQ7dLpyYxz3XqoGpnxvam5nwNQIWnt36kxn0OHi8WHpwffaeWl00VtO2bbkNwToUzOv1j0JTxIT,5TKARUdGEK7E1NyhqCsSRqIwvhmOhX9WU7RWr195MyyJ3eKzzJ9kxRDdH3AvSA9ZJ2j8StMOURUkAeUbuMPi5Ocwcg31X9RWCOyS6m79sCytmMvyRRKqyXM3CMViFuU4HGuikCp1IGwU9mPs9Z4NtH5L4m6WNabRuI5TMX2j88hjMlmIBQlZ9W6HQoiKG3JhzlIpouWBBs21iEgSuTuB5ZsDvdHhfk79sN8qyK1y6REmEQa35YXJPdg8d5Pw8Hul,UV8oSisIae1uchW0EKKa4omhO1ADa9zdKqBuU0FnQuQpjqPDdYIBofK5hykpieiINdSf54DR32nzg3m2Reue0qEs4reucCBv3Qg65Z8bb8fpuCGUsnSLS7HbR7hYn2etK6G6TWUKyWCwlPxc8FssI6mcB5ym5Fpz9VYhUmtyMv1V60fLCycOt10J5ELWsy071TD4eFCjaTGSi74JSRaWbc4n1OT2JFtsENLsElJnx6mDulZekRP4NLKwQ8SoWEhp,l72fl1yEEgmRZ4rA1OmRTwVOGl1JTpVq2wLRYBjGjKAFuBwzYDoWaNbglkwgz98pHwiS9CnYZBmTqxmZ1ZmrKTFdaufezHfzRzIKJESe6QWH6p5z1lUoSXXIFCYMEwV2m8EVxGDEKcXctrz0pTn3bUKAKqKrxFcZTKXkLK1Oq4jDZonjTY3FWoF3nV39YRsJYqQm1NAiv63mkcYIeF2uNK8KqRK89AHFI5rYPAMHiExyDLmGEk5b3cK123OWv5YA,oweqNnFN7PDCf0WqxKqJ3DBNpHoGPvKmfD7tXg69g2MUr4HFSuIS2zuMR5z5hxrIv2EvMdKf1TEz86zhGfOIDYf95tlbeTvbgDmP95MzBz4eT9pj3w44LOgFcwzYNFYNviotr6QIuhxGI0YxRDJYa7synIrJw8woKVvJDctDKhEOv17W08NL66WAqytlrac51N0PwwbYWzih9w2liE9aaXBkmbVdM8SdZmB76IXN9OgcRbTj50nZ1wxueaNSi6ow,IByNM4ucanJ7gT4bozUOxLdtXOk7742fFF0ySgLThLoFCvyVyT8gWzglr6YPBv5iegzZwmYx737OPm45oaB4dOdr7zrrvo7Hu8ikHYXz5z8x3uyaM0nLlaKjcOGPbf324SbqDuOKqxqsYC3r7CGHWJ5vc3UhY5fZIVBHCslmYbw9rfFFomG9CJWeC8lGR7OGNQHsKrWsIbSDV7HR94U1Ui98tEx4NJp5dS6c2Kupr4h8GJWuZ9HzLIOe7Bv3dAC5,FGRuk8eItLJEFwURWbpNPsgy5CGKYnUXF5PWUBMT6wJgatpaXx2DrT9RAgjYigVDmr9MX0ZzmZfa1YXDe60i2vJMKiEv27T4EgaKJcjKbieXY7ta61UbpOooBVvUa3ObS82JQROAObsrwLaSC54reRlg7ZNnHaay4vj2KCrkow5asXKnKifsBbqbZlXOvgskngaJxhYRsPxLwhYC7YLS24V2sxsTq9b69Fcqzcv4MmjSt64P3ssXb7Wo8Wi2JKWR,If8UQEtTCJYGNWN1CHQ34NAhvSkSlbM6S6kCToCdlOvw4g6S1ilnryPQkP5sEH6P8n4pRukW8QiOFVWzU7xqOelo8J0O1hCdEkYHN1gYn7jEMrFCflj7XnnZGokli2kKiUBFVdtBQB23MTJbsqQNt9nPP2Wa3TEqStAHN5NqwdqaMKA5ZVYD2h4cLxFZ7qc6eUjbwuC30FvXlUcOSdowmDqWNkscEAQSdeVkX2RnnhMfRNzIlqbpsl2aDeRHvc0y,dnYCGbpthmdyQzDLAPVomnRzNLO2bgtuDGSEAedKO8DI0gvI3vn5bvvCFAQmOBEALKsAD04jkwTyzGeARzpFOCcCYeaNon9x9QUCD0bprXNyveRaaId9LaAxybxhJ3iEGxNPfjphNzp4oS9LBAgKOZ8c9Y7corMenC92v3xF8CDISzWbbpjlZzMIviMmYo7dMWVfefS7Yzf9VcK4QEE4dXwNggScF056SDJh9ROm9UGBiu2yzvNYJ9EBl5kV8mHS,ThVAXklZOCO4b6S5uegD8CUkICXqZmzq69RReGyoZ81omIz7GUl6kIO1oHOCZ0uMxtfBAP7y1aSrUP6kazd7w2afqLG8aQuNXZTUyhRJ0wcqkzLQK8kveRMx40QhmwkUCKSaQ1PFuubuuYjodipYHlqMYGyLo1grppQOp4TpsDBuMUKc1WEeEnhTfi4xuuH3tT6pwJqBJxydJFLesdXXnZjK76CXU9iPBTMD0qKOSoTg0rKb6bvfLXRZvgJx0Mav,PDauFJ5eDPDIVhhCTtzBLf7UqU2oBGV8fx6OtEIuqoF2sMb52UI60ktfBMvMpj1cMzFgaVFG8XOL0CXe2Fy0ibkVcBgHCMQ52bluJuQe22QjI6j3ZwV3pm9Sk2qZKmMKQX52K5k0BcdFxrG9CvgzRNzdBga3YofzfxBaGjI6VO9pNkcUCdRihZr8aEA2fYLamNq9wUXRkd7fDWq1dL33M93NoNlZnUbhfrB0cNQZXOkPxI3zoXnSkL8gAJcQl4Wd,xM9XFFp9u5YVGRPnmtWyxLrdwgPyGdBa5l2TSmOlhVqlU5QputZF4SDA8UbVczseql2O3GduFhD1h5QO7FOBm68wUNILAl09JeUxdrKcllrnf5joPE86zVTZ5X7OKFtlGvzmVCqZK3nU6Dt3RCC4bjNZlT6FHWWla6v7ecqWPdUDRjLng0WXGgw4GJDUbBB3giAoNzfzq7E9x9Avt2FoBv7skgF76msaGXAIur6WzeH9hG22mzFEy7CPyY6mtP7S,A0yQwY0ycRiJngP8eny2dSwsT6wP6QaZDOMn2g23XV06UxrGuHt9DRC3oujCAgTGS0BeRdtA0l3v7amVic7JT9wPzjh14RuBRzvxlU577db74zxiZJqjwawUmkc6mJf14YUWPHTS7X5i9rML0SgWpqN3DBEsQXW3hISkcmbN7e1hqxQEKoPIs2efQ9WO2jpjW6ZwfUx18kTVFpnyAE6ZMCmej4ywj0zR4je64GbnnlgKgY8HmN4ghUl4bsqw0pyH,P6NcQeehWRzcjXEBvwYmWqsANux12lIhDhVFYbfax9SI3xfgO3XSfO3r6L5YrcH2YH9AHmUxAYXqFrdHKL7ybYwrc5fxLsHRdGDI7dDR2u7pJDD7qaJ8S4T4rTy759jCubNvAIp04v2wQvMfazmo8aRJBBXB2j2cVdUyUr2cxHhGPBHB7ifNe9wHQkZ8ayqd7dhhD6zhMGjB0JlEEbHOnoBkQjMHbnz5g5XGr02YFfAnfsaDP0l3HF8Xyd2cPUeX,DlKFGZNCtSl7pIAZ29tFw0Hmq5HiyEzjWRTw1uQVaIRFGW2J9LNSvVyviR8Xc8IcDUf4jDG8Uhgyz1AqI3N3bsnEcETbwrLBfuEMFS3qexMcm8COfBGIcwhYpsK6dzsRh7JIWCjsK4FGwGA8CogmBnBFCQ4K6A0VqcuOaHUaVsG7Q1VxpI1wqu3oBHsDBrnKqy6Spwi3oXbfdjfl9tLwDYNXZFhrC7y2vnQngMk5YhQqd8xtfBjBv0j31L8gZv5S,5xhYqPxzihjIFHfnUltN1DT8rPfs4db0Hki9XKPpIrJcgy6wLcJWR4VAWL8HTSp13EhstAoYMAVTnWiJtwTud2DVK6icyDx5vROjmJ8RWukSMfOmLfWz2CWZG1La8SOQESwwaqNKdfX6YUnfQLZEIYLtGzirkqOIjqnDIUgeEw5HxBpq1cNbynQyFr2lHAYpQbADr99t4ohVEo7uxbqzR4zK64lyxAq6Xk61TOxbK9BPRI634x4svGCwOfDqlVvj,ELdKuw7w5lXj9usjgnlvcK4KqKU4FOv0HO0hEictoRgbZn4PFQxRWol12O4yACQ4qJWve2r9NkKkkW4tdPygiYMic7GE3sWjwmVi7lT0bJoOrtsQHHDnK1c9RXOjas1zHqRsF5CWby415GWcLPvhy5SEuegI6lYOBgBGvQnd1BVOiW6apnmZpwplzJ9JITh5Nqy4oArLP0QGg3l8MQUxgSbdQPpBKrIANXLhc3WyXbgj5Uw7pWd94hMZpzvFSp5E,KWDuXfa70WOErEQMM7PzFgQCBXFRVQb61ViEA1R96PehpIn0MOQjQ8pe7EKRCjyeTNgCWu9hQBosEAoHR0m1ARJmb5gRZpHNGD6k3W014Lj5LgtKJAkaHrUIlVNo7psZkuuAeHj3zJG75iACp81Nm6BL0YHOnpBQSyUe0hiZgP3lL1NNGtCBElgnAmN1hwa2Sdzyj1QwtJVtRdUUHGMFqZDMUY0LrGhy7DzFwDZFYRmrB9aZtYJoS3LVRwm3t9J8,aHgoQiv7lJbaGnJ2BU0ZPYbPIGHSQ03tidJ7FnoNX7b36uMR4wr6c6EuukS7QYFGIsMdxtY6qXkrVif06aVONtn8oGJKbUttVWVfNMd7osWkm47ZQxPQKDJDKLj0Ra7koLJSCA7H3xSu1brnaeF24V38LsEBqTcm7KH7twYNgC0AbFk9mI7Cwmqxixf6rz2dWy4rwLnRARo103RmRyahQEdlRQzPuJdMlwbrIIEgFVmtrZvZj5E7wDlZKusGCidl,RpJvPfEBJFvASCZMBMz2xcRxDqICKYcZXVIF2lVDm9YGhGXxKec7sVqhNsLOT4WPrWnV4oxCVf4QaaHKwc1VnTCuU2EVQyBokKaHWwZ7Aic9xuVcdaFEf366u7VFVXZKGt4aNUc3KuzCBxSNbu8sp9BiyIBvT3M1n8RBRDkKqnXkZH16yjSOrPASdEHiFVIhcuCTZa7sWrHEj2Z0NHBP6SkT7CDMNo7xPHNBN4bygkQGVbralm67LBnpdretYJPj,rMwwf3EnWwxjhj9LOmvJpNzabko0eglntvwjEtiryhOXzgO9IDeILl3NPzhviebpiR1T3V0mkQEbfOiQWiRhqP8Fwhqwt9UcHRTIKkzNimP0OtiHIN0nMi5x3iKKDfZ8FfcjRSFwYKmKGD82nwvtRLc2sZiANrM0qjApeFLDt9PgWqDAp30Jfv7LRscTNaqphgPlQH120gh6EtTiM8tTPdqMql7H7eYSJuXhiKCZgkHZIHCr3PxgcMvwR3S5whra,5n7PSPOe97deJlAAyUtuHWDWQjy7VoDQietHKwZUl95QuzVBZiTOg9WGYWw41KgXFcPtPVZ5ldS9HhNoOANgDjklEXGjthoNdySYLDhn3p8zWUO5diWvlqVxY4Yo1MonYwu3mJ4Zc07n9V0h6gJ9FnVtDuQsfENzLUGQguSVc1HSbg81yHD0M7iJZsP117ji84DiVMSMMEiiKtqZW2MV74wzkoDtlEMvJtUEvSja9DzWelD612JA3ssrJChuNk0U,abfpINhXXoLb4PjmI3a6ZUlmVCatZhQXttTPT1fZE6bZ32xOZSpuuh7wBpnMRdQUPEF9fqTZsOuyg0OLgFsSEMKRqgoHjBVUBEu7oP78SAi7Nm9meSpEMsymg9RpBGEFTDUqTgZizTkKUeOC0wxl68PEVmowUMSdVxSYbdh5vmXt9a3U4TTbJYbMfSjHEHCxlbCyImaIPxEF1fqfU81zh17nJ2Z5G9ifhLslDIcofRx0wbMqyN0j8rSQo4J1AmAj,JjqDH9Ib7KQ7CW2Z2nHxA14P1yehGKxspne5DQDgySvebTAj9hNQdj0Tp6WRVhXnow7XJIzjrZ2jKzSBqXJoFehBgvosx354RfFehCPXjG9UNLZgpRnQMkpQp9dXacQOnmJMPRmYzCtpNvtJAe6YADa5vpZroWvI2OTC8JEmjVmYB81qst5HyYJqUVC0A9soWFQA0DHTCcLYU33g2fRgppDMQnYm8GQyqo88LhSgAczjCw2GcJ9fvIxf0NKzjQ46,yf8tYOeuqOuQoWhd5SbknO5nPlnPFUjdRuhcsf7sEdPQI5Ksyb3yI9OiK12z2wVGtDOyJjAFRByQo7ysrEc6Kuw9md4irPX87DwtxbemU0r0f5xKlJ6746IMsojjj6GPW9P1zVXQRj2FPFXo4X8P1weLVu7CpJVKWFvOrOXKnqCtXJFA1Sd2FdPqzKFEJ8YG9E9EapMQtc4FV3j3zN1Nvh395nb7ANcmXdTKe59itseh1eMSXxW5Qq5j8GwZEXqH,SziU0NxCBSRoMjCJmZsXagy617m4u1OW4tUmdv8Uh9LYWx8YtlA78IJud9Cn59S0SQky4bOpyesIeO2bKQa7fhdND2sNlfsbf8gxbx0dGeEkpOgkg6ozgKHTRYKmK623meRLg4T1VFUdsN3lN1xNkj1UTnGBecUXoMaPW3dNTsOmSHngi2gI1Nf51FMfbAif6Hx4sFOV0nHyVK3euF6yG5Dm4zqj0LmvCFhN1SsUyTnZim0UgYxNSck89mGowv3R,xPhlwAyuECq2HH0BjG9OXGrwtn6M7AQ6cUnfzDYyIZwKBB1TbeIISt5TGpfO3BdqrV8olEyVP67K0uhlWJu8ag11tWgbRIEsbWG6eEaPRCWd8m9hL8RogDU49zx7ezJd9xh2UXVvjARDcqoGb0vP3qz5GKLgPA0pwQzR6KwS4BKRNdzmzuJggFzfWzy0zV0wocZ11ajCMsO7Sju0ebIRZ9TgT0pVmJlNHOFJUazPBcKWUSdhj6GgTPAwaoWzHNtY,n6hHCZkUrcne9WdyNl2W6vvCFhxeshIzGSVg0Ckpd9Z0XYBG74sCwq951h3Mdq6OTkpuBzhOSQX0BxOD5XDWnx9WS85F8tWJGrOOgHA4Rqg2kAD2UHXODhG4nsm6iCshyvVqPpbRf5hPrUc50DRBfo8s6giP7twAn8Sw3gU7MhNFDcpCOfRfmMc4dGENkgGBAgPOf8nqQzMWZ5vT5FMBROdvbAMujdV6Nqz7ETOahrmhtrImOWSoclBaT3hoRjUc,BDmDlwbGw049uegEtGYBhlFWLobSziFe8xhRFjEVhD6UjiRPSqPbfwSVypZ83qq66ef2hbEjEmkPU2IGCUmn4v8xSWI4sLaqsp8aqbP6RPMJzrwSfadGQmlzOtpsEaX4P3jAMSrXoXXRGjD21j9Du823ra78AVC0blbSvtBGWxfG7qE0cfhSSaiIs1B3iYiwhAPpANQARxK0LV2AKwMiXNU0jckO1cQuwajOWS2QW8b6SiAYNpE2GR4OGwORsJuo,2zi07ZzpSEimSoqlaxuOee1bV6nOfcfxKMBOhhpJ6eBlqKJud1KIZxPSnL0qrQd2rcFMDNJ1wYsl6nQdmMs5J45mIMNGdNbYzOu9vebyqbdQP6LuLrKOrQEe88hIswk4pqFtLmN6aKBRnVhX0M5uMww7EIxylvey8BrEnj7Gbg99chTfrac5lqXBp3ZsTK3D6A4cmdwEvTml8X8mBD242q6dkJA6AuTetnhKVP00hKltRVPuUNGRMwICCAelF3gg,UThxFSBeJKq6QtkG4DPGlg2NMFSrzH5AyUxfg9AwPph9mSZhwbe5QNSOVhQJuc89AxLKBOrTEaZGVQLajwiOQAWAJCDBN3bRhoHCpMYEVR2UeHBxE1DJh9fwUfQdlKZkO9yGOI99vq5dtzxv4FrPorltWwMfjxGp3YwlzBkx7kRBkTQhvaUoSv48gtKxGCIXoNepmo29giWDUEIvYqhu78tIv9UOfGSG9OXzH4tcNFNJ5cD82xhGJs8UKQFFDrjL,vfGX0Ap1qErgeTwJYUsulDiDtwbs1BXKJ5I3k4GdAAn6ZfmuJqo5NLpZ8fwq1kYkySEY5p2urizoZFod2T5H0vhweAQ7WG68rr7mqiVHshMeSehLQRHdnrXGeLR4LEXaI7bGHadtZKUcv7oXoHQXdfgviaO9bKiJ3eZVD9yCymSgIixVHbptnTAX85ePaDHTaFCBztcTETWZGMHdAly2og4JCj2MppwgVWk0uTLVfE3iyuFvtGNxMMknerdfOwUv,kXpBc10G3VXF0V1EuMMMWyaegV0DteHx1TTZPH9owuOPNy1SgCnURdOHJgxbyL3eiL0ybo8jvF4QxgxP0gK6xJ1nch79jYPkAYTAscyMzpgHEB2WNyFTv2NKmqskn1ITkWpGSqOVN8zot7vtVgH8qlcKj9EquwhiTuV6wtXe8yiClWIt7pKDQRRzgL2YrSKCsum210DTiyVWG4VrHy4SgUC2TbWhqWfrHT5LQzPHddymfiVG6UhtSjyNnVBTiwlL,eYXmb6WDL99ErWjEOZErCP9LH2XWrfchrkbnEMYPbKMHVEKbpGPdCyTXs8UDBzxrCmQhcWEfnQkjHR5EcPFu2El769c28qVbDdXgvcnnhesIc58KjUgm7RTdHiSpfHRDJF9NyXYi9rQasr58D0fOg1uPUKTofP5HI8GFF3nRnw2vYrkvUjvoslOG3kc2bLZWNFivySYEVDql5PnuDuvlG1soOFXpdXX47TYUy59u70kJqsziRsxUVKhyxlTrx3P3,eGB9yu7Me3211X5uXsxGX4NePFgf5i589CdE8uxtyFUh3cRUtEpNl0Ae2R2PCY98KMSrYURAFZauYWiYpAPl4bM7snZy6bWngEwVtaSCZerYf0cwDGpFAsNSvMmgmuGKM1PYQW0woImMH99TmnS2YT2qfPYAD5OybigfCrEK1ZHXDCptQQ5VU1SdblRGJ0SB3otuFqY1gdVClRB2UZFnXuKkhIuVn5FXy8oviY7ymkiYClgQc8HimiDrZgzIFksX,mqdYQ42Hhf4Xeb1WP0yWRANzLpWtBa3tTVn2YaTR8phSJAjS9ixnwuNJfj9SvRB4JeacBDKFzwbRbEfRqtDAaZoHGowr8btstBeXv1D5JW53qPtiuly260CXoQX8oQtq4audOiYLMF3JRd4uF2wkNjX0sOjrxyN51bGlYqlZb16m1CqOrHNqiREMQToNe5dd65j7Ql8t0oglO1CPusu1Ss5gWiKkeDsnCJkRk1rnmu84GDZNArtP0l6i5B0mRDpT,adQnVsVpSWapUgidt4BnKlvhaYx9D0QmLEqa1MLAsJAgSWv3AsKGdIOpZ5cF2Wi2PhnAsFjg23bXmNiMsdVKTn1RpNaxQVWI68dyGMpmABCWVEBipgOLWJXMoCU9ZQujDp9OZBuIyujwbYSywTZRbv7DvC6i9dKVRWet3GhBtQdeb0R0H8IZn9eCxt2vlnFs7NF5UbkgElXOk3mHI9MN4xC07xfWPm3RoR2Bm8GSZmha5f0kJsZ7K2KPjZfYnRQh,IfRcln0NEHmT1RpcR4U8SvviI0SNidTZQYBz07sLoR2kbUELKJ3IRT5vsI8DwqDtwRDkRYwIFbFmxtUYjfck4ytCacJtX4M6YeBo4etdqrZeqSzVtTWqhCpAfWKwTGqCq3dHkWbPhLVaJ3uPKPbAGjF1hnrmn6sKMOkZrxYC0S2JxiFUlaeZCfAImjz2PDGA5ajY9FhBr98Csq7edGmISHjzzvvO2IBdTr3wHLhyUCzqBcTXd6Gq1QY04hSRN7le,ULBfSsvdiM8l7j314ncth6FmBwLR6oSUYpafk3foYDPtkzGtGWpcdOdgUM53K9dKZLeEun3iT54nWvyJW4hbsBydI1cf11pRNMBet5e507OQXLcyCQ1isWw20j0UFI0RSIobR7LvgXqk8Vj0ejKFozIStSqvM4luiGJaySZU23jW4sA94sz7pXE0Vd1psxXfzDMEpPHZVvpiOscePnBJTfB38xJ3NO3q6phHE5XfGjuV1iqfzl1kNx4NxUzC69TO,paxD6qAwLsAT2f9HZtV6kBXZCBPNO2RHdKHekM7qj9ZFlxLtshCoZVRgWiw95UIxDuLxhZuZl3falrSsPEcrr0l8KhHgkFgkdUAD4inTrJb2IvYCJc6C03jEtjAJ7azo1v9nnq2oKDVw5IsJTKetGvbSiRFUt4sF4tm2Zbi8M6iNWGg7JbCb54daZ00O8wKDT3rzdzo287SQiZ9GKCTTgrqajj3phTCCLPSc5hSjmakmoa7nnXrPj0Lug4tDAGmf,Jrle310Mh4H4owFK9Oqd2pZl7AoMOvaExHMkWiLpvcGSTs3YiAI08wcwBcqnMznck93EjJb4jwWbzEFnfNjY3fV0vdrxkf8uAtnPJz9rOhuWcor8IecW4PXNCrVKvSdsV3kenwkzZokBo2HYO1HPK6XEqdIct0Ds8tzQMpEhHfv2DseythIifNLDHyxC6Tpv23vHV7D3yUCrHWWYG0QaNVRxD3mbL38tDyv5o9wu6LzgPXVi7ZzEY12vm2LgVQeD,mO8QRsqZxBsxX7afl4r6bJquyHKLXwFjIKhGV0UObdGqRZxquPVdtwVFYcrSttLfSjsmz9KipPSw5YQv4AxQ0sws9blVFfxZJPfBz10FxQ3hN0JWbLrmPNxIP0EfhXh2zShaaBZM1axKctTCQjaL2ew3K49xCJgLLMp2VwBdSOpsAVVkLgwjhaGGjatqjhH9c1oQgpyO22o99KUR8TR1pyJeCquXbtRP7ZIOVKv1nEYLa2ZDWlS3lm4LSUNmIuu5,sOYJzsEDfEVCk51CG2n7aKjfqtbZZRWYLxW3I0t35eehSEgykYwkg2QOzcC8KGfdAL75P3E4u0CYQiaROe4bvzhg4oBwQRG3wdixFnymqN9qZwPodf7Oq3PZlf2xFPUSp0Pyc2ngvMeloCX32xlufYNI1Ikitvgslsc167ZwCzQ7CTy9eU5Rxd6yr9D645g6hgG3p1UvbHd9ZPORro5VwEizOfzPrmQXWReI2hcb5nwxL1x8u3L9eiOQ65Vla2In,YnISD3BTmy3CgHC2PrPwPJpX5dMSq43YW9rZBujMfRBjwi1iua5NmNxzOiIeyGH0AxtrzpbG0xWuuuso4sJkhXtv9xfacSfMXx7ButARtWbp7tcb5JuZ3aRKhEplJDIGHkgOQT6O8zqe9j0aOIBqvwJDf8ycaXpSF3wlM9p9vzYINiVShlusAM3hvJM9vcIBKOjZH1vpppv13tAUj8fiUhfV1G3xYyiwh6XZGgnrVKnWdpxLKdSaIgSWrWj7NRN1,FWuZMVH3R6ubLAJUJs1h5DYHDPsi3uUhYtcdm12e0i6cTZDanywt3WDHfQWjZDr7rhxWJwU6lb8qd7JsKkIJowJHVIvIKEbTgRh7idTkBgfyMnQqYCQZTwVDkJxAszB2EuDBhwfvES8yLGc6jyvRdTDEM382oHhtwzsR6GfwitmGUzUuwQYsbsbu8pqviCMAYz4zZ6OdqNpcz1cWwjSkx1J4SaG4ETlE9wnvklWWhglb7EMBKoFQ7ofACtA5zTCP,mFobz4y9w5OExTSAccwjt5M3A3OiMEFSgz8NutLAjv9YiQQ5UH6QEFtdVGSBPhs43oddL1Q5pwyZQjIdGeMUEgOwDAiAmyCQ2a7AFcqxDAlgxIqP8o46rfXz2HHK40V3Ihb8Gwphzh4dr24j4kzwplRfhWEA5HIYb1Vw4fRgSH4zWHtpnnllDEUpqGFORQ4HLDaKys4d5s8zS99A5YxZ3r9GyAHBTruMqN2tnse0Sj0mxwWGYMscGptpJK1duXvA,7C0EOg8yU3sDh5mh3gveqM6jYValcoSftzjz52QxSs9pyrUVPuAwgORuWW2EHAzu6CpaSNtFO8yJ6gfnC1HaZoFCxp6DHK8g9y9DAOqVmBEpt7knJH3hqQSRLc0f7PmawtsWru12Q7q3bYzRmFudX0opXFGh7h0sQ4D9pgKYxx2AExGj58bL7JjvRWNIl5Xo5y1DxdzwwUJHr9BUakmqvYsWUiNkCtsvMRJeCDfNVlbj5S8i1ozxaBtG4Abrr3hb,8syibclcgF480CP0r8Nr2OQ8SX08KjrOUAMtAIhQyrA5aSXSPRnkBF6h8IJaUHY8o1R0qFdPma6px3GC6MWLbfT4Qw8C1UN9GIN5Jv0CUPgtKaPmHRnIxmeqSMdPqPwS9WQlasG6myeCfzQaHgqAHdqqJkdJKeciTnY69K6O964eJyJYkJPk5GX3HNVlEhtrlhLCnqAEexEw5WgQqqGdRVfoAhbds0m8DG1t86EtPZz3kEbKBdTFdn6a9oxDFKrx,IF2akYsocQlgTvyRk6jEiQiqXaTVNqRTTNqbbePF26rCZEHBqR5Yui5cUhvalPIyYRwAxrui106WJ9TXu2jQNaGtvPwo4RdXc8YAor4vv3mLSIHwuA7U4uMRcpKYKEW09pd2Zk8lvdMXq3tZraDkw6AeUNsoXNlydCBXMBgYXzjaCDrLn6JFJCmDSg97LHOqRXLP0AceNwlvbvYfytMwdL6lJLEwh0WEhx4vClPC7C1VTuY8JLSyo1CPrMLqV9gD,B2rdlY06AtqknFpNVVTQy7247PuvbCUYbk5CJxtf29uXV3GNCqij5X8gQ0xju6IYxuCKYJDLkPlPMKv70o679A3gHgggr4rLypkfhfUQmb7yjGYqd3pVlA36R6I8ZIOnoa8nkXF0IvgLzU5i3RoDBqy0zgZ279XG7sSGiYyJ3NrXYmB2bnkrHJl4ENdj3K3cxjeC4a1RRKKGFi5VIw2AJcH16DTlAkRuf7Owk1IxwtH3kqmX6YFbnPjsr8tqVvGH,cXe2462ENZTJxqYjsyQizew1gAJ7c25LrdMwaOOYoCOJq7uD9qITn1NsQJU93YKOU0cTEZCkD7RN30g7XAqyRRryZ0GK5JaPqAOFpar5T3yh3pH2dvIvy94PBJTJEOJEF9x86pMlyaIRw5oDv8mrDlF7dUDer3GHtrwhbIvqu799ZWpWggYN7snXNgQ7SrCssHkELivQzAOd1Z14qkH0e7sMEyZ1qx4lk18K72ku0agX8lKN5yAWm4PPr4ThqnIv,bkChl1gfMtIIW0gOAylQDQxePkjJ7a0CtLbXfhslx3g8lTE78xJdLLAHdGJZ6WD0Yi35QkLlLCGxAvwKGn03CVAHFSPsnOR2A1CPTz8R7BvnJAOOsSyF6c7fQtpnJW8WHiaFZbegQgokGuSRg45jJ5GaOZPTihtX604ICeza1Awy43pXXOsuahRlAF1DMuDdtHb58CCDRYe2IO2LiaHJwxxMkZYHyUK5byizTTJgpyPHHOqSAcCk1pvVXM27S7mJ,C97XFw5VjFgjXjqY1a8zn97YkcHyJwTF0kpljooSHmu7ls3kMx04Lnik3cfOX0Xq8WUXYegmA2JD5eibdrlzjnbQH0ZTuBuCtswayDVqGA053XlBDD6V0Ji3nGjEteBcwVMfOgWq0oJkuFy4TP6boT2gfYLR9G23q6vZ2AGctSPsn5ept64QoPs5WPmOV7wGM0gfW4l9D6PtzC6V1b7mOFosBRVNNULx1cXlLeTfubBDXMe1IyYMqI74TjbPFbIU,jSZSXJxX8oJz2LYv7WCgZ5BlO5KWHmcz1P7nEjz9FfA4KKQpLRgrmCnJe2NkDkWcGEBrc5xjvcyyuVDAF35DSN7eYCn2O84Iu9z4pw9QFYi8gqhRmyMVObGnmU7KumxJ2Mqbo5di1c2VpXCSj8c34hK5qsuSuUcwkUkHfKPqiHbmfpH3KGk622Al7hNUESi9BB38KfFBpgh3B9FD21eHIX9ySplhteMjQemApwxjjd1FuDfB5CCWBj3ab1Li3sBW,NpVxSDGCxSjBeCa9Iozz9XisrpccL8mL1GmFUSD7nzN8LCuezIBIhsQk7zNGl4BHBuNDj8jK9upnseQqJrZS5JHuFgOSl9DBrHh1hI54sqVwmWulVzd3PGaI82xcOxrGQGKbTt8ge0Jlwvi0rNzKhzukGy5KJS9rXOCgCKovHChkxEGOZ0wZDPvROzVEHZjOuNmLwnCQG8bvS5KgTv5pTuIPyaRxew7DUZo8cLWTiRoM2X1AQTta7FEYN1mxZdja,mh5Xs19tdiuare8DoeVLcrSA44nVnQCbs38paW5RDeYHJePrPPJM5NlLcaoZOEoFshbmvJ6teZ6e3pabgYQsYHLGrXEuTKJ9v6vbUbh1SeY5Ieag9tCUuourFUVOKA7QCUwlWTJmrTax2AIsOQCKYKXlcpmAGJH6iQlGnkcWyO79HEUtKPLgkcUu9Z3tsRDLy8iKqQ1emsBtB0nBUaxsMztsxUhYPeM6R8Pw2aZRsxk6Xd2xQrJUWEQwePaO6Nsd,6FWD5sWsDtrL0ng6fEpe1m5RO9iY9ogFt94Bi6Bc3NuQVTjVlZtnrNQiIB3IJpii8kOS0nA26gcNAd8wXlCzrSvt9bEeQuUMMwRvLdmv636c0WHeu3iaXFOB7AqJ8lx7UCBv5n3NUgTS4FI3RZVCSFkNFIkuJ8mDH4QpQD1KUD2O1pJOE2q2qSxUX1mB2XKtvhzwSy7qBUIUkN1RbVrKvlfedELx52TWZo5hJfboUpbE6zL5T4eSr1SsN3mkverb,fL1gRPjiRoFg9C0iqMatkPs0Rsdps4Xn9fi8qUA6LO3ccyA1dpj1Hiau1CE0Q1j8hW9fHgxpT1oIRblXg6ALxPfQVctGh15buDO6gizYS1X9UvVUU1xqqBKJ7PQCJRZsJplNhASwOmKyViQSspNOyfgq2FjHIR3mpOqPeyzGtJbIuXKLqBTA9jOs1eCdXFRrl4Qn0tTig39JBYD8IvDmmSE9gYyIK51InTweyyMYB8VNe0TFxHsTHJ7mOzW1bvio,YHtkej8Ou1T7jlW2BE0AiuBxhbpBCx61EKgL9kZu8ITOKQ5Zib18vRYrD8N6Y6O5oQj0oLZMTlKB3gox2cymX32Z17VqXyeET2vuIJPgPn1UlfWN1BgBna2tusIM1abV1s88VNWZcv9YgyiCVondZrBniqIwdJBh3eTNVRNTstWUkcwxuqXJQQFX60Jm1UkuC45J7d1X35Pl5su5bXuetgWz67VU6cGnSCqFO8adWcooLTUcnmAWQLFenLPM095w,OO2QaDCmxOkzgoe6H3xznJUOt7Eu6etW5P13RVpqBYGWhVNqfmfaLY9sRDfjtAx5081rkcIMCZ3W76'
2017-07-18 09:52:09 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-18 09:52:09 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-18 09:52:09 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,2017-07-18 09:52:09 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-18 09:52:09 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-07-18 09:52:09 - DEBUG testThaliMobileNative: 'Server data flushed',
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:7
,[ThaliCore] VirtualSocket.closeStreams() vsID:7
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:7
[ThaliCore] VirtualSocket.deinit vsID:7 [3, 5, 8, 9]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) cli,ent disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:8
[ThaliCore] VirtualSocket.closeStreams() vsID:8
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:8
,[ThaliCore] VirtualSocket.deinit vsID:8 [3, 5, 9]
,2017-07-18 09:52:09 - DEBUG testThaliMobileNative: 'Server received (6570 bytes):'
,2017-07-18 09:52:09 - DEBUG testThaliMobileNative: 'Server received (9814 bytes):'
,2017-07-18 09:52:09 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-18 09:52:09 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:9,
[ThaliCore] VirtualSocket.closeStreams() vsID:9
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-18 09:52:10 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-18 09:52:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-18 09:52:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
[ThaliCore] VirtualSocket exited RunLoop vsID:5
[ThaliCore] VirtualSocket.deinit vsID:5 [3, 9]
2017-07-18 0,9:52:10 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"ne,tworkType":null}})'
,2017-07-18 09:52:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 115 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:6FF1C5AC-E652-4E94-8CF5-84D52A8E5C15
,2017-07-18 09:52:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:52:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,ok 116 Should be able to call stopAdvertisingAndListening in teardown
[ThaliCore] BrowserManager.disconnect peer:13A16B2D-9A9A-4856-BD41-17E83D3985F1
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectio,nsAndDisconnectClients() port:53177
[ThaliCore] Session.disconnect() peer:13A16B2D-9A9A-4856-BD41-17E83D3985F1:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:F6DF7613-A4D4-463D-BA47-6615C92DA0C6 state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "6FF1C5AC-E652-4E94-8CF5-84D52A8E5C15", generation: 0)
,[ThaliCore] AdvertiserRelay.closeRelay()
,[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
,[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:F6DF7613-A4D4-463D-BA47-6615C92DA0C6
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:13A16B2D-9A9A-4856-BD41-17E83D3985F1:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-18 09:52:10 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:52:10 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:52:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:52:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:52:10 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:52:10 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:52:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:52:10 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data securely
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "624396A9-3501-4E23-BC49-2F10FDE3AE33", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:624396A9-3501-4E23-BC49-2F10FDE3AE33
,2017-07-18 09:52:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-18 09:52:10 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-18 09:52:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 117 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:90B1E51C-01AE-484B-87D1-88A0EBDD303C
,[ThaliCore] Browser.startListening
,2017-07-18 09:52:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-18 09:52:10 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-18 09:52:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 118 Can call startListeningForAdvertisements without error
,[ThaliCore] Session.deinit peer:F6DF7613-A4D4-463D-BA47-6615C92DA0C6
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:13A16B2D-9A9A-4856-BD41-17E83D3985F1:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "13A16B2D-9A9A-4856-BD41-17E83D3985F1", generation: 0)
2017-07-18 09:52:11 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"13A16B2D-9A9A-4856-BD41-17E83D3985F1","generation":0}'
2017-07-18 09:52:11 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 13A16B2D-9A9A-4856-BD41-17E83D3985F1, (syncValue: L7EiujSyBpPM39fYORN36b1Rv3NzQYnL)'
,2017-07-18 09:52:11 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "13A16B2D-9A9A-4856-BD41-17E83D3985F1", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "13,A16B2D-9A9A-4856-BD41-17E83D3985F1", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:13A16B2D-9A9A-4856-BD41-17E83D3985F1:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:624396A9-3501-4E23-BC49-2F10FDE3AE33:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "624396A9-3501-4E23-BC49-2F10FDE3AE33", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7DE26A7A-5E15-49DC-9309-AE715C12E4A1:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7DE26A7A-5E15-49DC-9309-AE715C12E4A1", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:74EEA8D0-8560-4241-8408-D752D9A14577:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "74EEA8D0-8560-4241-8408-D752D9A14577", generation: 0)
2017-07-18 09:52:12 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"7DE26A7A-5E15-49DC-9309-AE715,C12E4A1","generation":0}'
,2017-07-18 09:52:12 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-18 09:52:12 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-18 09:52:12 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"74EEA8D0-8560-4241-8408-D752D9A14577","generation":0}'
,2017-07-18 09:52:12 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-18 09:52:12 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-18 09:52:12 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:13A16B2D-9A9A-4856-BD41-17E83D3985F1:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:13,A16B2D-9A9A-4856-BD41-17E83D3985F1:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "13A16B2D-9A9A-4856-BD41-17E83D3985F1", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1,3A16B2D-9A9A-4856-BD41-17E83D3985F1", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "13A16B2D-9A9A-4856-BD41-17E83D3985F1", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:13A16B2D-9A9A-4856-BD41-17E83D3985F1:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:13A16B2D-9A9A-4856-BD41-17E83D3985F1:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:13A16B2D-9A9A-4856-BD41-17E83D3985F1:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:13,A16B2D-9A9A-4856-BD41-17E83D3985F1:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "13A16B2D-9A9A-4856-BD41-17E83D3985F1", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1,3A16B2D-9A9A-4856-BD41-17E83D3985F1", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "13A16B2D-9A9A-4856-BD41-17E83D3985F1", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:13A16B2D-9A9A-4856-BD41-17E83D3985F1:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:13A16B2D-9A9A-4856-BD41-17E83D3985F1:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:13A16B2D-9A9A-4856-BD41-17E83D3985F1:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:13,A16B2D-9A9A-4856-BD41-17E83D3985F1:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "13A16B2D-9A9A-4856-BD41-17E83D3985F1", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1,3A16B2D-9A9A-4856-BD41-17E83D3985F1", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "13A16B2D-9A9A-4856-BD41-17E83D3985F1", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:13A16B2D-9A9A-4856-BD41-17E83D3985F1:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:13A16B2D-9A9A-4856-BD41-17E83D3985F1:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:901B53B2-11CD-46AE-B53A-5093A88750C6
[ThaliCore] Advertiser: session connected Peer(uuid: "624396A9-3501-4E23-BC49-2F10FDE3AE33", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:901B53B2-11CD-46AE-B53A-5093A88750C6 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:13A16B2D-9A9A-4856-BD41-17E83D3985F1:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:13,A16B2D-9A9A-4856-BD41-17E83D3985F1:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "13A16B2D-9A9A-4856-BD41-17E83D3985F1", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:13A16B2D-9A9A-4856-BD41-17E83D3985F1 error: max retries exceeded
,2017-07-18 09:52:16 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"L7EiujSyBpPM39fYORN36b1Rv3NzQYnL","error":"Connection could not be established","portNumber":null}'
,2017-07-18 09:52:16 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'L7EiujSyBpPM39fYORN36b1Rv3NzQYnL', error: 'Connection could not be established', listeningPort: '%s''
,2017-07-18 09:52:16 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"13A16B2D-9A9A-4856-BD41-17E83D3985F1","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-18 09:52:16 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-18 09:52:16 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"13A16B2D-9A9A-4856-BD41-17E83D3985F1","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-18 09:52:16 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-18 09:52:16 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-18 09:52:16 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 7DE26A7A-5E15-49DC-9309-AE715C12E4A1 (syncValue: QmPRCgJH7byAIanHtjGSgsq4fqwTgFIu)'
,2017-07-18 09:52:16 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7DE26A7A-5E15-49DC-9309-AE715C12E4A1", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7DE26A7A-5E15-49DC-9309-AE715C12E4A1", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:7DE26A7A-5E15-49DC-9309-AE715C12E4A1:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-18 09:52:16 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-18 09:52:16 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:13A16B2D-9A9A-4856-BD41-17E83D3985F1:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:7DE26A7A-5E15-49DC-9309-AE715C12E4A1:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:901B53B2-11CD-46AE-B53A-5093A88750C6
,[ThaliCore] Session.session(_:peer:didChange:) peer:901B53B2-11CD-46AE-B53A-5093A88750C6 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:901B53B2-11CD-46AE-B53A-5093A88750C6
,[ThaliCore] Session.startOutputStream(with:) peer:901B53B2-11CD-46AE-B53A-5093A88750C6
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:10 [3, 9, 10]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:7DE26A7A-5E15-49DC-9309-AE715C12E4A1:0
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:7DE26A7A-5E15-49DC-9309-AE715C12E4A1:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "7DE26A7A-5E15-49DC-9309-AE715C12E4A1", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:53202
,2017-07-18 09:52:19 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"QmPRCgJH7byAIanHtjGSgsq4fqwTgFIu","error":null,"portNumber":53202}'
,2017-07-18 09:52:19 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'QmPRCgJH7byAIanHtjGSgsq4fqwTgFIu', error: 'null', listeningPort: '53202''
,Connecting to the localhost:53202
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:7DE26A7A-5E15-49DC-9309-AE715C12E4A1:0
,Server received psk id: psk-id
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7DE26A7A-5E15-49DC-9309-AE715C12E4A1:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:11 [3, 9, 10, 11]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-18 09:52:19 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-07-18 09:52:19 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-18 09:52:19 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes): '
,2017-07-18 09:52:19 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-18 09:52:19 - DEBUG testThaliMobileNative: 'Server's socket stream finished'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:10
[ThaliCore] VirtualSocket.closeStreams() vsID:10
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:10
,[ThaliCore] VirtualSocket.deinit vsID:10 [3, 9, 11]
,Connected to the localhost:53202
,2017-07-18 09:52:19 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-18 09:52:19 - DEBUG testThaliMobileNative: 'Client data flushed'
,ok 119 got the same data back
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:11
[ThaliCore] VirtualSocket.closeStreams() vsID:11
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] VirtualSocket exited RunLoop vsID:11
,[ThaliCore] VirtualSocket.deinit vsID:11 [3, 9]
,# teardown
,2017-07-18 09:52:27 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-18 09:52:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-18 ,09:52:27 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-18 09:52:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 120 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising(),
[ThaliCore] Advertiser.stopAdvertising() peerID:624396A9-3501-4E23-BC49-2F10FDE3AE33
2017-07-18 09:52:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:52:27 ,-, INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 121 Should be able to call stopAdvertisingAndListening in teardown
[ThaliCore] BrowserManager.disconnect peer:7DE26A7A-5E15-49DC-9309-AE715C12E4A1
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:53202
[ThaliCore] Session.disconnect() peer:7DE26A7A-5E15-49DC-9309-AE715C12E4A1:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:7DE26A7A-5E15-49DC-9309-AE715C12E4A1:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-18 09:52:27 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:52:27 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:52:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:52:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:52:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:52:27 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:52:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:52:27 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:901B53B2-11CD-46AE-B53A-5093A88750C6 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "624396A9-3501-4E23-BC49-2F10FDE3AE33", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:901B53B2-11CD-46AE-B53A-5093A88750C6
[ThaliCore] Advert,iserRelay.deinit
,[ThaliCore] Session.deinit peer:901B53B2-11CD-46AE-B53A-5093A88750C6
,# Can shift large amounts of data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "EA7FABF7-B03B-465A-91E3-B2E4B0213751", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:EA7FABF7-B03B-465A-91E3-B2E4B0213751
,2017-07-18 09:52:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-18 09:52:30 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-18 09:52:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 122 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:AC3D4257-C08F-462D-A0BC-995CEF73E1AA
[ThaliCore] Browser.startListening
,2017-07-18 09:52:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-18 09:52:30 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-18 09:52:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 123 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:14BBCBC7-F1A6-4ACD-9889-3E919E85D2D9:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "14BBCBC7-F1A6-4ACD-9889-3E919E85D2D9", generation: 0)
2017-07-18 09:52:30 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"14BBCBC7-F1A6-4ACD-9889-3E919E85D2D9","generation":0}'
2017-07-18 09:52:30 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 14BBCBC7-F1A6-4ACD-9889-3E919E85D2D9, (syncValue: wxW4mBm78SDfNuhAcBJ3gZQichJCFCTU)'
2017-07-18 09:52:30 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "14BBCBC7-F1A6-4ACD-9889-3E919E8,5D2D9", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "14BBCBC7-F1A6-4ACD-9889-3E919E85D2D9", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:14BBCBC7-F1A6-4ACD-9889-3E919E85D2D9:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:14BBCBC7-F1A6-4ACD-9889-3E919E85D2D9:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:EA7FABF7-B03B-465A-91E3-B2E4B0213751:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "EA7FABF7-B03B-465A-91E3-B2E4B0213751", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:74526F95-007E-4B61-843A-4180389BA28D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "74526F95-007E-4B61-843A-4180389BA28D", generation: 0)
,2017-07-18 09:52:31 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"74526F95-007E-4B61-843A-4180389BA28D","generation":0}'
2017-07-18 09:52:31 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-18 09:52:31 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:14BBCBC7-F1A6-4ACD-9889-3E919E85D2D9:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:14BBCBC7-F1A6-4ACD-9889-3E919E85D2D9:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "14BBCBC7-F1A6-4ACD-9889-3E919E85D2D9", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:53208
2017-07-18 09:52:34 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"wxW4mBm78SDfNuhAcBJ3gZQichJCFCTU",,"error":null,"portNumber":53208}'
2017-07-18 09:52:34 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'wxW4mBm78SDfNuhAcBJ3gZQichJCFCTU', error: 'null', listeningPort: '53208''
,Connecting to the localhost:53208
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:14BBCBC7-F1A6-4ACD-9889-3E919E85D2D9:0
Connected to the localh,ost:53208
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:14BBCBC7-F1A6-4ACD-9889-3E919E85D2D9:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:12 [3, 9, 12]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-18 09:52:34 - DEBUG testThaliMobileNative: 'Client sends data (65536 bytes):'
,2017-07-18 09:52:34 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:743EFA39-C137-4C21-B82D-A08FD24C5A3B
[ThaliCore] Advertiser: session connected Peer(uuid: "EA7FABF7-B03B-465A-91E3-B2E4B0213751", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:743EFA39-C137-4C21-B82D-A08FD24C5A3B state: notConnected -> connecting
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vs,ID:12
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,ok 124 got the same data back
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:743EFA39-C137-4C21-B82D-A08FD24C5A3B
,[ThaliCore] Session.session(_:peer:didChange:) peer:743EFA39-C137-4C21-B82D-A08FD24C5A3B state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:743EFA39-C137-4C21-B82D-A08FD24C5A3B
[ThaliCore] Session.startOutputStream(with:) peer:743EFA39-C137-4C21-B82D-A08FD24C5A3B
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,3 [3, 9, 12, 13]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-18 09:52:37 - DEBUG testThaliMobileNative: 'Server received (1024 bytes):'
,2017-07-18 09:52:37 - DEBUG testThaliMobileNative: 'Server received (2261 bytes):'
,2017-07-18 09:52:37 - DEBUG testThaliMobileNative: 'Server received (6570 bytes):'
,2017-07-18 09:52:37 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-18 09:52:37 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-18 09:52:37 - DEBUG testThaliMobileNative: 'Server received (3143 bytes):'
,2017-07-18 09:52:37 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-18 09:52:37 - DEBUG testThaliMobileNative: 'Server received (1237 bytes):'
,2017-07-18 09:52:37 - DEBUG testThaliMobileNative: 'Server received (3143 bytes):'
,2017-07-18 09:52:37 - DEBUG testThaliMobileNative: 'Server received (2332 bytes):'
,2017-07-18 09:52:37 - DEBUG testThaliMobileNative: 'Server received (39256 bytes):'
,2017-07-18 09:52:37 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-18 09:52:37 - DEBUG testThaliMobileNative: 'Server sends data back to client (65536 bytes):'
2017-07-18 09:52:37 - DEBUG testThaliMobileNative: 'Server data flushed',
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:13
[ThaliCore] VirtualSocket.closeStreams() vsID:13
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:13
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.deinit vsID:13 [3, 9, 12]
,[ThaliCore] Session.session(_:peer:didChange:) peer:743EFA39-C137-4C21-B82D-A08FD24C5A3B state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "EA7FABF7-B03B-465A-91E3-B2E4B0213751", generation: 0)
,[ThaliCore] AdvertiserRelay.closeRelay()
,[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
,[ThaliCore] TCPClient.deinit
,[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
,[ThaliCore] Session.disconnect() peer:743EFA39-C137-4C21-B82D-A08FD24C5A3B
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:743EFA39-C137-4C21-B82D-A08FD24C5A3B
,2017-07-18 09:52:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-18 09:52:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-18 09:52:38 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-18 09:52:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 125 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:EA7FABF7-B03B-465A-91E3-B2E4B0213751
,2017-07-18 09:52:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:52:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 126 Should be able to call stopAdvertisingAndListening in teardown
,[ThaliCore] BrowserManager.disconnect peer:14BBCBC7-F1A6-4ACD-9889-3E919E85D2D9
[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:53208
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:14BBCBC7-F1A6-4ACD-9889-3E919E85D2D9:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:14BBCBC7-F1A6-4ACD-9889-3E919E85D2D9:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "14BBCBC7-F1A6-4ACD-9889-3E919E85D2D9", generation: 0)
,2017-07-18 09:52:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:52:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:52:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:52:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:52:38 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:52:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:52:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:52:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,2017-07-18 09:52:38 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"wxW4mBm78SDfNuhAcBJ3gZQichJCFCTU","error":"Session disconnected","portNumber":null}'
,2017-07-18 09:52:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"14BBCBC7-F1A6-4ACD-9889-3E919E85D2D9","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-18 09:52:38 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-18 09:52:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"14BBCBC7-F1A6-4ACD-9889-3E919E85D2D9","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-18 09:52:38 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,# setup
,[ThaliCore] Session.deinit peer:14BBCBC7-F1A6-4ACD-9889-3E919E85D2D9:0
,# We do not emit peerAvailabilityChanged events until one of the start methods is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:5A6A04B8-ECDC-46AE-BC31-77B908110B7B
[ThaliCore] Browser.startListening
,2017-07-18 09:52:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-18 09:52:38 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-18 09:52:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 127 We should start listening fine
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "960D2F62-7D6D-4B13-B832-850740724523", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:960D2F62-7D6D-4B13-B832-850740724523
,2017-07-18 09:52:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-18 09:52:38 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-18 09:52:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 128 We should start updating fine
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:960D2F62-7D6D-4B13-B832-850740724523:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "960D2F62-7D6D-4B13-B832-850740724523", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F56E88A8-5367-48DD-834E-AA7C5F9B74B3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F56E88A8-5367-48DD-834E-AA7C5F9B74B3", generation: 0)
,2017-07-18 09:52:39 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"F56E88A8-5367-48DD-834E-AA7C5F9B74B3","generation":0}]'
,2017-07-18 09:52:39 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"F56E88A8-5367-48DD-834E-AA7C5F9B74B3","generation":0}'
,2017-07-18 09:52:39 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-18 09:52:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-18 ,09:52:44 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-18 09:52:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 129 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising(),
[ThaliCore] Advertiser.stopAdvertising() peerID:960D2F62-7D6D-4B13-B832-850740724523
2017-07-18 09:52:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:52:44 ,-, INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 130 Should be able to call stopAdvertisingAndListening in teardown
,2017-07-18 09:52:44 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:52:44 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:52:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:52:44 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:52:44 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:52:44 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:52:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:52:44 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Test updating advertising and parallel data transfer
,2017-07-18 09:52:44 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test updating advertising and parallel data transfer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-18 09:52:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:52:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 131 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-18 09:52:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:52:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 132 Should be able to call stopAdvertisingAndListening in teardown
,2017-07-18 09:52:44 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:52:44 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:52:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:52:44 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:52:44 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:52:44 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:52:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:52:44 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# discoveryAdvertisingStateUpdateNonTCP is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:BFEBD2AF-DEFF-4D64-B1E0-41CEB85575A3
,[ThaliCore] Browser.startListening
,ok 133 discoveryActive should be false
,ok 134 advertisingActive should be true
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "E1F3270B-3800-4FC6-A797-4D6B1C80159C", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:E1F3270B-3800-4FC6-A797-4D6B1C80159C
,ok 135 discoveryActive should be false
,ok 136 advertisingActive should be true
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,ok 137 discoveryActive should be false
,ok 138 advertisingActive should be true
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:E1F3270B-3800-4FC6-A797-4D6B1C80159C
,ok 139 discoveryActive should be false
,ok 140 advertisingActive should be true
,ok 141 Can call startListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,ok 142 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,ok 143 Should be able to call stopAdvertisingAndListening in teardown
,2017-07-18 09:52:45 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:52:45 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:52:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:52:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:52:45 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:52:45 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:52:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:52:45 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call connect when start listening for advertisements is not active
,2017-07-18 09:52:45 - DEBUG CoordinatedClient: 'test was skipped, name: 'cannot call connect when start listening for advertisements is not active''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-18 09:52:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:52:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 144 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-18 09:52:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-07-18 09:52:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 145 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# Get error when trying to double connect to a peer on Android
2017-07-18 09:52:45 - DEBUG CoordinatedClient: 'test was skipped, name: 'Get error when trying to double connect to a peer on Android''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-18 09:52:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:52:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 146 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-18 09:52:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-07-18 09:52:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 147 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection
,2017-07-18 09:52:46 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-18 09:52:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:52:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 148 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-18 09:52:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:52:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 149 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection
,2017-07-18 09:52:46 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-18 09:52:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:52:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 150 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-18 09:52:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:52:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 151 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer
,2017-07-18 09:52:47 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-18 09:52:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:52:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 152 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-18 09:52:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-07-18 09:52:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 153 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer
,2017-07-18 09:52:47 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-18 09:52:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:52:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 154 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-18 09:52:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-07-18 09:52:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 155 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# cannot call multiConnect when start listening for advertisements is not active
,ok 156 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:60ab420b-8445-456e-9f57-6fd728107a31 error: startListeningNotActive
,2017-07-18 09:52:48 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"QY3avbbTUpfEbFWWDs9xnnTO0TLMxsvr","error":"startListeningForAdvertisements is not active","portNumber":null}'
,ok 157 Should only get called after multiConnect returned
,ok 158 SyncValue matches
,ok 159 Got right error
,ok 160 listeningPort is null
,2017-07-18 09:52:48 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"60ab420b-8445-456e-9f57-6fd728107a31","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-18 09:52:48 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-18 09:52:48 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"60ab420b-8445-456e-9f57-6fd728107a31","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-18 09:52:48 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-18 09:52:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:52:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 161 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-18 09:52:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:52:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 162 Should be able to call stopAdvertisingAndListening in teardown
,2017-07-18 09:52:48 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:52:48 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:52:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:52:48 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:52:48 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:52:48 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:52:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:52:48 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with illegal peerID
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:051F8D26-2304-451E-8BC8-E537143D9C16
[ThaliCore] Browser.startListening
2017-07-18 09:52:49 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-18 09:52:49 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:52:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 163 No error on star,ting
ok 164 Got null as expected
,2017-07-18 09:52:49 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Qr9cxoQlH5XCLCRZPMtX7Ceb9Lx3n5Vq","error":"Illegal peerID","portNumber":null}'
ok 165 Should only get called after multiConnect returned
ok 166 SyncValue matches
,ok 167 Got right error
ok 168 listeningPort is null
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-18 09:52:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:52:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 169 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-18 09:52:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-07-18 09:52:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 170 Should be able to call stopAdvertisingAndListening in teardown
,2017-07-18 09:52:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:52:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:52:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:52:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:52:49 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:52:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:52:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:52:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# multiConnect properly fails on legal but non-existent peerID
,2017-07-18 09:52:50 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiConnect properly fails on legal but non-existent peerID''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-18 09:52:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:52:50 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 171 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-18 09:52:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:52:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 172 Should be able to call stopAdvertisingAndListening in tea,rdown
,2017-07-18 09:52:50 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-18 09:52:50 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:52:50 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:52:50 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:52:50 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:52:50 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:52:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:52:50 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with invalid syncValue
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:8976896F-CC2E-4707-9740-7030C7543B2A
[ThaliCore] Browser.startListening
2017-07-18 09:52:51 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-18 09:52:51 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:52:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 173 No error on star,ting
,ok 174 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-18 09:52:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:52:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 175 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-18 09:52:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-07-18 09:52:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 176 Should be able to call stopAdvertisingAndListening in teardown
2017-07-18 09:52:51 - DEBUG thaliMobileNativeWrapper: ,'Method peerAvailabilityChanged registered to native'
2017-07-18 09:52:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:52:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectRes,olved registered to native'
,2017-07-18 09:52:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:52:51 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:52:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:52:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:52:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call disconnect with invalid peer id
,ok 177 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-18 09:52:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:52:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 178 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-18 09:52:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:52:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 179 Should be able to call stopAdvertisingAndListening in teardown
,2017-07-18 09:52:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:52:52 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:52:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:52:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:52:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:52:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:52:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:52:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# disconnect doesn't fail on plausible but bogus peer ID
,[ThaliCore] BrowserManager.disconnect peer:049c8d45-3b0e-4475-8b03-f9bed8d8a458
,ok 180 No error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-18 09:52:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:52:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 181 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-18 09:52:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-07-18 09:52:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 182 Should be able to call stopAdvertisingAndListening in teardown
,2017-07-18 09:52:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-18 09:52:52 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:52:52 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:52:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:52:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:52:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:52:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:52:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Get same port when trying to connect multiple times on iOS
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "EE1ADE94-333C-449C-BB6D-D3402DE39710", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:EE1ADE94-333C-449C-BB6D-D3402DE39710
,2017-07-18 09:52:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-18 09:52:52 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:52:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 183 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D0DBDBF9-7E02-4274-B5F9-C07573030C51
,[ThaliCore] Browser.startListening
,2017-07-18 09:52:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-18 09:52:52 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-18 09:52:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 184 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:730E3CE2-CE3F-4684-B97C-85BAE4444C28:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "730E3CE2-CE3F-4684-B97C-85BAE4444C28", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B68E1B2B-5D40-46BE-92E9-A865509D6EEF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B68E1B2B-5D40-46BE-92E9-A865509D6EEF", generation: 0)
,2017-07-18 09:52:53 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"730E3CE2-CE3F-4684-B97C-85BAE4444C28","generation":0}'
,2017-07-18 09:52:53 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 730E3CE2-CE3F-4684-B97C-85BAE4444C28 (syncValue: a7cJ4XVkUMlyNDwktUb3bJGZogQndrbv)'
,2017-07-18 09:52:53 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "730E3CE2-CE3F-4684-B97C-85BAE4444C28", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "730E3CE2-CE3F-4684-B97C-85BAE4444C28", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:730E3CE2-CE3F-4684-B97C-85BAE4444C28:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-18 09:52:53 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B68E1B2B-5D40-46BE-92E9-A865509D6EEF","generation":0}'
,2017-07-18 09:52:53 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-18 09:52:53 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:EE1ADE94-333C-449C-BB6D-D3402DE39710:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "EE1ADE94-333C-449C-BB6D-D3402DE39710", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:730E3CE2-CE3F-4684-B97C-85BAE4444C28:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:730E3CE2-CE3F-4684-B97C-85BAE4444C28:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:730E3CE2-CE3F-4684-B97C-85BAE4444C28:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "730E3CE2-CE3F-4684-B97C-85BAE4444C28", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:53216
,2017-07-18 09:52:57 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"a7cJ4XVkUMlyNDwktUb3bJGZogQndrbv","error":null,"portNumber":53216}'
,2017-07-18 09:52:57 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'a7cJ4XVkUMlyNDwktUb3bJGZogQndrbv', error: 'null', listeningPort: '53216''
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:730E3CE2-CE3F-4684-B97C-85BAE4444C28:0
,ok 185 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "730E3CE2-CE3F-4684-B97C-85BAE4444C28", generation: 0) found active relay
,2017-07-18 09:52:57 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"AjF5NLWZWuRiIY4SLGRoXlL0oHfL1wLe","error":null,"portNumber":53216}'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:730E3CE2-CE3F-4684-B97C-85BAE4444C28:0
,ok 186 No error
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:14 [3, 9, 12, 14]
ok 187 Ports equal
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 188 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "730E3CE2-CE3F-4684-B97C-85BAE4444C28", generation: 0) found active relay
,2017-07-18 09:52:57 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"clxqnqrTrYobfcOicULuIJ0PrrWBtETz","error":null,"portNumber":53216}'
,ok 189 No error
,ok 190 Ports equal
,# teardown
,2017-07-18 09:53:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-18 09:53:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-18 09:53:01 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-18 09:53:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 191 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:EE1ADE94-333C-449C-BB6D-D3402DE39710
,2017-07-18 09:53:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:53:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 192 Should be able to call stopAdvertisingAndListening in teardown
,[ThaliCore] BrowserManager.disconnect peer:730E3CE2-CE3F-4684-B97C-85BAE4444C28
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:53216
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] VirtualSocket.closeStreams() vsID:14
,[ThaliCore] VirtualSocket exited RunLoop vsID:14
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
,[ThaliCore] VirtualSocket.deinit vsID:14 [3, 9, 12]
,[ThaliCore] Session.disconnect() peer:730E3CE2-CE3F-4684-B97C-85BAE4444C28:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:730E3CE2-CE3F-4684-B97C-85BAE4444C28:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uui,d: "730E3CE2-CE3F-4684-B97C-85BAE4444C28", generation: 0)
,2017-07-18 09:53:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:53:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:53:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:53:01 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:53:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:53:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:53:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,2017-07-18 09:53:01 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"a7cJ4XVkUMlyNDwktUb3bJGZogQndrbv","error":"Session disconnected","portNumber":null}'
,2017-07-18 09:53:01 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"730E3CE2-CE3F-4684-B97C-85BAE4444C28","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-18 09:53:01 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-18 09:53:01 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"730E3CE2-CE3F-4684-B97C-85BAE4444C28","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-18 09:53:01 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,# setup
,[ThaliCore] Session.deinit peer:730E3CE2-CE3F-4684-B97C-85BAE4444C28:0
[ThaliCore] BrowserRelay.deinit
,# initial peer discovery
,2017-07-18 09:53:02 - DEBUG CoordinatedClient: 'test was skipped, name: 'initial peer discovery''
,# teardown
,2017-07-18 09:53:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-18 09:53:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:53:02 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:53:02 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:53:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:53:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:53:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 1
,2017-07-18 09:53:02 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 1''
,# teardown
,2017-07-18 09:53:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:53:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:53:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:53:02 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:53:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:53:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:53:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 2
,2017-07-18 09:53:03 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 2''
,# teardown
,2017-07-18 09:53:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-18 09:53:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:53:03 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:53:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:53:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:53:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:53:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# check latest peer discovery
,2017-07-18 09:53:03 - DEBUG CoordinatedClient: 'test was skipped, name: 'check latest peer discovery''
,# teardown
,2017-07-18 09:53:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-18 09:53:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:53:03 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:53:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:53:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:53:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:53:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Set up for no peer discovery test
,2017-07-18 09:53:03 - DEBUG CoordinatedClient: 'test was skipped, name: 'Set up for no peer discovery test''
,# teardown
,2017-07-18 09:53:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:53:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:53:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:53:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:53:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:53:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:53:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# no peer discovery
,2017-07-18 09:53:04 - DEBUG CoordinatedClient: 'test was skipped, name: 'no peer discovery''
,# teardown
,2017-07-18 09:53:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:53:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:53:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:53:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:53:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:53:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:53:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calling createNativeListener directly rejects
,2017-07-18 09:53:04 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-18 09:53:04 - DEBUG createNativeListener: 'listening 53219'
,ok 193 Should throw
,# teardown
,2017-07-18 09:53:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-18 09:53:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-18 09:53:04 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits incomingConnectionState
,2017-07-18 09:53:04 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-18 09:53:04 - DEBUG createNativeListener: 'listening 53221'
,2017-07-18 09:53:04 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-18 09:53:04 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 194 initial connection state should be CONNECTED
,2017-07-18 09:53:04 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 195 final connection state should be DISCONNECTED
,# teardown
,2017-07-18 09:53:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-18 09:53:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-18 09:53:04 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits routerPortConnectionFailed
,2017-07-18 09:53:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-18 09:53:05 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-18 09:53:05 - DEBUG createNativeListener: 'listening 53224'
,2017-07-18 09:53:05 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-18 09:53:05 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-18 09:53:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-18 09:53:05 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - error Error: connect ECONNREFUSED'
,ok 196 tried to connect to right port
,ok 197 failed due to refused connection
,ok 198 routerPortConnectionFailed is emitted
,# teardown
,2017-07-18 09:53:05 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-18 09:53:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-18 09:53:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-18 09:53:05 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-18 09:53:05 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-18 09:53:05 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server connections all up
,2017-07-18 09:53:05 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-18 09:53:05 - DEBUG createNativeListener: 'listening 53228'
,2017-07-18 09:53:05 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-18 09:53:05 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-18 09:53:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-18 09:53:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,ok 199 Send/recvd #1 should be equal length
,ok 200 Send/recvd #1 should be same
,ok 201 Send/recvd #2 should be equal length
,ok 202 Send/recvd #2 should be same
,ok 203 Should be exactly 2 client sockets
,# teardown
,2017-07-18 09:53:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-18 09:53:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-18 09:53:05 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-18 09:53:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-18 09:53:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
,2017-07-18 09:53:05 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-18 09:53:05 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,2017-07-18 09:53:05 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-07-18 09:53:05 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# native server - closing incoming stream cleans outgoing socket
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-18 09:53:06 - DEBUG createNativeListener: 'listening 53233'
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-18 09:53:06 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,ok 204 socket shouldn't close until after stream
,ok 205 incoming remains open
,# teardown
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-18 09:53:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-18 09:53:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing incoming connection cleans outgoing socket
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'listening 53237'
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 206 we should not have gotten an error
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 207 socket shouldn't close until after incoming
,ok 208 incoming is cleaned up
,# teardown
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-18 09:53:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-18 09:53:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-18 09:53:06 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - closing outgoing socket cleans associated mux stream
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'listening 53241'
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,ok 209 stream was closed
,ok 210 incoming should survive
,ok 211 mux should have no streams
,# teardown
,2017-07-18 09:53:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-18 09:53:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing the whole server cleans everything up
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-18 09:53:07 - DEBUG createNativeListener: 'listening 53245'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 212 we should not have gotten an error
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 213 Buffers are identical
,2017-07-18 09:53:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 214 native server is nulled out
,ok 215 native server should be closed
,ok 216 incoming has been removed
,ok 217 Incoming should be done
,ok 218 The mux object should be closed
,ok 219 The mux stream should be closed
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# teardown
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-18 09:53:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - we can get a ton of connections and data through and still clean up the server completely
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'listening 53249'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - created'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - created'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - created'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - created'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - created'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - created'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - created'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - created'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - created'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - created'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - created'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - created'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - created'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - created'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - created'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - created'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - created'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - created'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - created'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - created'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - created'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - created'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - created'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - created'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - created'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - created'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - created'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - created'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - created'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - created'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - created'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - created'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - created'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - created'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - created'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - created'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - created'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - created'
,2017-07-18 09:53:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - closed'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - closed'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - closed'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - closed'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - closed'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - closed'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - closed'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - closed'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - closed'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - closed'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - closed'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - closed'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - closed'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - closed'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - closed'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - closed'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - closed'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - closed'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - closed'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - closed'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - closed'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - closed'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - closed'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - closed'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - closed'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - closed'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - closed'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - closed'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - closed'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - closed'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - closed'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - closed'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - closed'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - closed'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - closed'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - closed'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - closed'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - closed'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,ok 220 native server is nulled out
ok 221 native server should be closed
,ok 222 incoming has been removed
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-18 09:53:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - simulate mux failure, make sure everything is cleaned up
,2017-07-18 09:53:08 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-18 09:53:08 - DEBUG createNativeListener: 'listening 53301'
,2017-07-18 09:53:08 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-18 09:53:08 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 223 we should not have gotten an error
,2017-07-18 09:53:09 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 224 Buffers are identical
,2017-07-18 09:53:09 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-18 09:53:09 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-18 09:53:09 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 225 server should be fine
,ok 226 server should be open
,ok 227 incoming has been removed
,ok 228 The mux object should be closed
,ok 229 The mux stream should be closed
,2017-07-18 09:53:09 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-18 09:53:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-18 09:53:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-18 09:53:09 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - timing out the incoming connection cleans everything up
,2017-07-18 09:53:09 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-18 09:53:09 - DEBUG createNativeListener: 'listening 53305'
,2017-07-18 09:53:09 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-18 09:53:09 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 230 we should not have gotten an error
,2017-07-18 09:53:09 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 231 Buffers are identical
,2017-07-18 09:53:09 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - incoming socket timeout'
,2017-07-18 09:53:09 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-18 09:53:09 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-18 09:53:09 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 232 server should be fine
,ok 233 server should be open
,ok 234 incoming has been removed
,ok 235 The mux object should be closed
,ok 236 The mux stream should be closed
,# teardown
,2017-07-18 09:53:09 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-18 09:53:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-18 09:53:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-18 09:53:09 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# can create servers manager
,ok 237 serversManager must not be null
ok 238 serversManager must be an object
,# teardown
,# setup
,# calling stop without start causes error
,ok 239 We need to call start first
,# teardown
,# setup
,# can start/stop servers manager
,2017-07-18 09:53:10 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-18 09:53:10 - DEBUG createNativeListener: 'listening 53308'
ok 240 port must be in range
,# teardown
,2017-07-18 09:53:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-18 09:53:10 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# starting twice resolves with listening port
,2017-07-18 09:53:10 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-18 09:53:10 - DEBUG createNativeListener: 'listening 53309'
ok 241 second start should return same port
,# teardown
,2017-07-18 09:53:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-18 09:53:10 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminateIncomingConnection will terminate a connection
,2017-07-18 09:53:10 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-18 09:53:10 - DEBUG createNativeListener: 'listening 53311'
,2017-07-18 09:53:10 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-18 09:53:10 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 242 we should be connected
,2017-07-18 09:53:10 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 243 now we are disconnected
,2017-07-18 09:53:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# teardown
,2017-07-18 09:53:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-18 09:53:10 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminate an Outgoing connection
,2017-07-18 09:53:10 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 32'
,ok 244 Passed bogus id
,2017-07-18 09:53:10 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 901'
,ok 245 Passed good id but bogus port
,2017-07-18 09:53:10 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 900'
,ok 246 Passed right context
,ok 247 Right server
,ok 248 No error should be set
,ok 249 Retry should be false
,ok 250 We called close server
,# teardown
,# setup
,2017-07-18 09:53:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:53:11 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:53:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:53:11 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:53:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:53:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:53:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Single local http request
,listening on 53313
,ok 251 should be equal
,# teardown
,2017-07-18 09:53:11 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,2017-07-18 09:53:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:53:11 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:53:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:53:11 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:53:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:53:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:53:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Single coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "6058E2A4-FAC9-450F-81D5-E68925F48B59", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:6058E2A4-FAC9-450F-81D5-E68925F48B59
,2017-07-18 09:53:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-18 09:53:11 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-18 09:53:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 252 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:B546392C-361E-4C9D-A82C-AFF4F7F58FAB
[ThaliCore] Browser.startList,ening
2017-07-18 09:53:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-18 09:53:11 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":tr,ue}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-18 09:53:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 253 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7E3D0BB5-4FA3-4194-9297-87098529DE9A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7E3D0BB5-4FA3-4194-9297-87098529DE9A", generation: 0)
,2017-07-18 09:53:12 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"7E3D0BB5-4FA3-4194-9297-87098529DE9A","generation":0}'
,2017-07-18 09:53:12 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 7E3D0BB5-4FA3-4194-9297-87098529DE9A (syncValue: 4ZFGkjaSRgxmoISv4qJrfosK3OBM8d6Y)'
,2017-07-18 09:53:12 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7E3D0BB5-4FA3-4194-9297-87098529DE9A", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7E3D0BB5-4FA3-4194-9297-87098529DE9A", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:7E3D0BB5-4FA3-4194-9297-87098529DE9A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2B78F9C9-6BBF-47B1-8B50-629FB064FBE3
[ThaliCore] Advertiser: session connected Peer(uuid: "6058E2A4-FAC9-450F-81D5-E68925F48B59", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:2B78F9C9-6BBF-47B1-8B50-629FB064FBE3 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6058E2A4-FAC9-450F-81D5-E68925F48B59:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6058E2A4-FAC9-450F-81D5-E68925F48B59", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:7E3D0BB5-4FA3-4194-9297-87098529DE9A:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B77BB749-103B-4479-A004-5B3078040F60:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B77BB749-103B-4479-A004-5B3078040F60", generation: 0)
2017-07-18 09:53:12 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B77BB749-103B-4479-A004-5B3078040F60","generation":0}'
2017-07-18 09:53:12 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-18 09:53:12 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:2B78F9C9-6BBF-47B1-8B50-629FB064FBE3
,[ThaliCore] Session.session(_:peer:didChange:) peer:2B78F9C9-6BBF-47B1-8B50-629FB064FBE3 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:7E3D0BB5-4FA3-4194-9297-87098529DE9A:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:7E3D0BB5-4FA3-4194-9297-87098529DE9A:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "7E3D0BB5-4FA3-4194-9297-87098529DE9A", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:53318
,2017-07-18 09:53:15 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"4ZFGkjaSRgxmoISv4qJrfosK3OBM8d6Y","error":null,"portNumber":53318}'
,2017-07-18 09:53:15 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '4ZFGkjaSRgxmoISv4qJrfosK3OBM8d6Y', error: 'null', listeningPort: '53318''
,ok 254 should be equal
,2017-07-18 09:53:15 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B77BB749-103B-4479-A004-5B3078040F60 (syncValue: ukYJDZslxlfiHsRqapOT4iM43SZx6b4V)'
,2017-07-18 09:53:15 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B77BB749-103B-4479-A004-5B3078040F60", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B77BB749-103B-4479-A004-5B3078040F60", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B77BB749-103B-4479-A004-5B3078040F60:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:B77BB749-103B-4479-A004-5B3078040F60:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B77BB749-103B-4479-A004-5B3078040F60:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:B77BB749-103B-4479-A004-5B3078040F60:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "B77BB749-103B-4479-A004-5B3078040F60", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:53322
2017-07-18 09:53:18 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"ukYJDZslxlfiHsRqapOT4iM43SZx6b4V",,"error":null,"portNumber":53322}'
2017-07-18 09:53:18 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'ukYJDZslxlfiHsRqapOT4iM43SZx6b4V', error: 'null', listeningPort: '53322''
,ok 255 should be equal
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4A18A990-740D-42E7-BA6C-24B16A8EFA4A
[ThaliCore] Advertiser: session connected Peer(uuid: "6058E2A4-FAC9-450F-81D5-E68925F48B59", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:4A18A990-740D-42E7-BA6C-24B16A8EFA4A state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:4A18A990-740D-42E7-BA6C-24B16A8EFA4A
,[ThaliCore] Session.session(_:peer:didChange:) peer:4A18A990-740D-42E7-BA6C-24B16A8EFA4A state: connecting -> connected
,[ThaliCore] BrowserManager.disconnect peer:7E3D0BB5-4FA3-4194-9297-87098529DE9A
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:53318
[ThaliCore] Session.disconnect() p,eer:7E3D0BB5-4FA3-4194-9297-87098529DE9A:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:7E3D0BB5-4FA3-4194-9297-87098529DE9A:0
[ThaliCore] BrowserRelay.deinit
[ThaliCore] BrowserManager.disconnect peer:B77BB749-103B-4479-A004-5B3078040F60
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCP,Listener.stopListeningForConnectionsAndDisconnectClients() port:53322
[ThaliCore] Session.disconnect() peer:B77BB749-103B-4479-A004-5B3078040F60:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListen,er.deinit
[ThaliCore] Session.session(_:peer:didChange:) peer:4A18A990-740D-42E7-BA6C-24B16A8EFA4A state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "6058E2A4-FAC9-450F-81D5-E68925F48B59", generation: 0)
[ThaliCore,] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:4A18A990-740D-42E7-BA6C-24B16A8EFA4A
[Thali,Core] AdvertiserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:2B78F9C9-6BBF-47B1-8B50-629FB064FBE3 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "6058E2A4-FAC9-450F-81D5-E68925F48B59", generation: 0)
,[ThaliCore] Session.deinit peer:B77BB749-103B-4479-A004-5B3078040F60:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-18 09:53:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] Session.deinit peer:4A18A990-740D-42E7-BA6C-24B16A8EFA4A
,# setup
,2017-07-18 09:53:25 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-18 09:53:25 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:53:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:53:25 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:53:25 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:53:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:53:25 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Multiple local http requests
,listening on 53324
,ok 256 should be equal
ok 257 should be equal
ok 258 should be equal
,# teardown
,2017-07-18 09:53:25 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,2017-07-18 09:53:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-18 09:53:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:53:26 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:53:26 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:53:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-18 09:53:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
2017-07-18 09:53:26 - DEBUG thaliMobileNa,tiveWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Multiple coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "6058E2A4-FAC9-450F-81D5-E68925F48B59", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:6058E2A4-FAC9-450F-81D5-E68925F48B59
,2017-07-18 09:53:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-18 09:53:26 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-18 09:53:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 259 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-07-18 09:53:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-18 09:53:26 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-18 09:53:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 260 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6058E2A4-FAC9-450F-81D5-E68925F48B59:1
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6058E2A4-FAC9-450F-81D5-E68925F48B59", generation: 1)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4A18A990-740D-42E7-BA6C-24B16A8EFA4A
[ThaliCore] Advertiser: session connected Peer(uuid: "6058E2A4-FAC9-450F-81D5-E68925F48B59", generation: 1)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:4A18A990-740D-42E7-BA6C-24B16A8EFA4A state: notConnected -> connecting
[ThaliCore] Session.init(session:identifier:connected:notConnected:,) peer:2B78F9C9-6BBF-47B1-8B50-629FB064FBE3
[ThaliCore] Advertiser: session connected Peer(uuid: "6058E2A4-FAC9-450F-81D5-E68925F48B59", generation: 1)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[T,haliCore] Session.session(_:peer:didChange:) peer:2B78F9C9-6BBF-47B1-8B50-629FB064FBE3 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7E3D0BB5-4FA3-4194-9297-87098529DE9A:1
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7E3D0BB5-4FA3-4194-9297-87098529DE9A", generation: 1)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:B77BB749-103B-4479-A004-5B3078040F60:1
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B77BB749-103B-4479-A004-5B3078040F60", generation: 1)
,2017-07-18 09:53:27 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"7E3D0BB5-4FA3-4194-9297-87098529DE9A","generation":1}'
,2017-07-18 09:53:27 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 7E3D0BB5-4FA3-4194-9297-87098529DE9A (syncValue: uVyp1c9ReoeUdFfwuzP3vdeOd1QfvLgA)'
,2017-07-18 09:53:27 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7E3D0BB5-4FA3-4194-9297-87098529DE9A", generation: 1) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7E3D0BB5-4FA3-4194-9297-87098529DE9A", generation: 1)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:7E3D0BB5-4FA3-4194-9297-87098529DE9A:1
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-18 09:53:27 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B77BB749-103B-4479-A004-5B3078040F60","generation":1}'
,2017-07-18 09:53:27 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-18 09:53:27 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:7E3D0BB5-4FA3-4194-9297-87098529DE9A:1 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:2B78F9C9-6BBF-47B1-8B50-629FB064FBE3
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:4A18A990-740D-42E7-BA6C-24B16A8EFA4A
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:7E3D0BB5-4FA3-4194-9297-87098529DE9A:1
,[ThaliCore] Session.session(_:peer:didChange:) peer:4A18A990-740D-42E7-BA6C-24B16A8EFA4A state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:7E3D0BB5-4FA3-4194-9297-87098529DE9A:1 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "7E3D0BB5-4FA3-4194-9297-87098529DE9A", generation: 1)
[ThaliCore] BrowserRelay,.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:53331
,[ThaliCore] Session.session(_:peer:didChange:) peer:2B78F9C9-6BBF-47B1-8B50-629FB064FBE3 state: connecting -> connected
,2017-07-18 09:53:30 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"uVyp1c9ReoeUdFfwuzP3vdeOd1QfvLgA","error":null,"portNumber":53331}'
,2017-07-18 09:53:30 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'uVyp1c9ReoeUdFfwuzP3vdeOd1QfvLgA', error: 'null', listeningPort: '53331''
,ok 261 should be equal
,ok 262 should be equal
,ok 263 should be equal
,2017-07-18 09:53:30 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B77BB749-103B-4479-A004-5B3078040F60 (syncValue: x9uvLsDV5bWsoU260WW4I4R4XTlXKC0A)'
,2017-07-18 09:53:30 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B77BB749-103B-4479-A004-5B3078040F60", generation: 1) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B77BB749-103B-4479-A004-5B3078040F60", generation: 1)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B77BB749-103B-4479-A004-5B3078040F60:1
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:B77BB749-103B-4479-A004-5B3078040F60:1 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B77BB749-103B-4479-A004-5B3078040F60:1
,[ThaliCore] Session.session(_:peer:didChange:) peer:B77BB749-103B-4479-A004-5B3078040F60:1 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "B77BB749-103B-4479-A004-5B3078040F60", generation: 1)
[ThaliCore] BrowserRelay,.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:53337
,2017-07-18 09:53:33 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"x9uvLsDV5bWsoU260WW4I4R4XTlXKC0A","error":null,"portNumber":53337}'
2017-07-18 09:53:33 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'x,9uvLsDV5bWsoU260WW4I4R4XTlXKC0A', error: 'null', listeningPort: '53337''
,ok 264 should be equal
,ok 265 should be equal
,ok 266 should be equal
,# teardown
,[ThaliCore] BrowserManager.disconnect peer:7E3D0BB5-4FA3-4194-9297-87098529DE9A
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:53331
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:7E3D0BB5-4FA3-4194-9297-87098529DE9A:1
,[ThaliCore] Session.session(_:peer:didChange:) peer:4A18A990-740D-42E7-BA6C-24B16A8EFA4A state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "6058E2A4-FAC9-450F-81D5-E68925F48B59", generation: 1)
[ThaliCore] AdvertiserRelay.closeRelay()
,[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:2B78F9C9-6BBF-47B1-8B50-629FB064FBE3
[ThaliCore] Session.deinit peer:2B78F9C9-6BBF-47B1-8B50-629FB064FBE3
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:7E3D0BB5-4FA3-4194-9297-87098529DE9A:1
[ThaliCore] BrowserRelay.deinit
[ThaliCore] BrowserManager.disconnect peer:B77BB749-103B-4479-A004-5B3078040F60
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:53337
[ThaliCore] Session.disconnect() peer:B77BB749-103B-4479-A004-5B3078040F60:1
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:B77BB749-103B-4479-A004-5B3078040F60:1
[ThaliCore] BrowserRelay.deinit
,2017-07-18 09:53:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #startListeningForAdvertisements should fail if start not called
,ok 267 specific error should be returned
,# teardown
,ok 268 must be stopped
,2017-07-18 09:53:35 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-18 09:53:35 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:53:35 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:53:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:53:35 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:53:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:53:35 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# #startUpdateAdvertisingAndListening should fail if start not called
,ok 269 specific error should be returned
,# teardown
,ok 270 must be stopped
,2017-07-18 09:53:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:53:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:53:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:53:36 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:53:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:53:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:53:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #stopListeningForAdvertisements many times
,2017-07-18 09:53:36 - DEBUG thaliMobileNativeWrapper: 'listening 53341'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-18 09:53:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-18 09:53:36 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-18 09:53:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 271 no errors
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-18 09:53:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-18 09:53:36 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-18 09:53:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 272 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:6058E2A4-FAC9-450F-81D5-E68925F48B59
[ThaliCore] Advertiser.stopAdvertising() peerID:6058E2A4-FAC9-450F-81D5-E68925F48B59
,2017-07-18 09:53:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:53:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-18 09:53:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:53:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-18 09:53:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 273 must be stopped
,2017-07-18 09:53:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-18 09:53:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:53:36 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:53:36 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:53:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:53:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:53:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #startListeningForAdvertisements many times
,2017-07-18 09:53:36 - DEBUG thaliMobileNativeWrapper: 'listening 53342'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:2AD876B7-DC55-49C9-9E3E-CF766EED29A0
[ThaliCore] Browser.st,artListening
2017-07-18 09:53:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-18 09:53:36 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:53:36 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
ok 274 no errors
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-07-18 09:53:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-18 09:53:36 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-18 09:53:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 275 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-18 09:53:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-18 09:53:36 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-18 09:53:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-18 09:53:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:53:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-18 09:53:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 276 must be stopped
,2017-07-18 09:53:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:53:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:53:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:53:36 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:53:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:53:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:53:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-07-18 09:53:37 - DEBUG thaliMobileNativeWrapper: 'listening 53343'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "035CE146-B548-4F2E-ADFB-369CDB62D2FF", generation: 0)
[ThaliCore] Advertiser.startA,dvertising with peerID:035CE146-B548-4F2E-ADFB-369CDB62D2FF
2017-07-18 09:53:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-18 09:53:37 - INFO thaliMobile: 'Receive,d state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:5,3:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 277 no errors
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "035CE146-B548-4F2E-ADFB-369CDB62D2FF", generation: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:035CE146-B548-4F2E-ADFB-369CDB62,D2FF
2017-07-18 09:53:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-18 09:53:37 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":t,rue}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:53:37 - INFO thaliMobile: 'Filtered out discoveryAdverti,singStateUpdate (was in stopped state).'
,ok 278 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:035CE146-B548-4F2E-ADFB-369CDB62D2FF
,[ThaliCore] Advertiser.stopAdvertising() peerID:035CE146-B548-4F2E-ADFB-369CDB62D2FF
,2017-07-18 09:53:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:53:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-18 09:53:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:53:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-18 09:53:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 279 must be stopped
,2017-07-18 09:53:37 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:53:37 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:53:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:53:37 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:53:37 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:53:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:53:37 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #stopAdvertisingAndListening many times
,2017-07-18 09:53:37 - DEBUG thaliMobileNativeWrapper: 'listening 53346'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-18 09:53:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:53:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 280 no errors
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-18 09:53:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:53:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 281 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-18 09:53:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:53:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-18 09:53:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:53:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-18 09:53:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 282 must be stopped
,2017-07-18 09:53:37 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:53:37 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:53:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:53:37 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:53:37 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:53:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:53:37 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can get the network status before starting
,ok 283 network status should have certain non-empty properties
,# teardown
,ok 284 must be stopped
,2017-07-18 09:53:37 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:53:37 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:53:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:53:37 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:53:37 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:53:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:53:37 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# error returned with bad router
,2017-07-18 09:53:38 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a string'
ok 285 specific error expected
,# teardown
,ok 286 must be stopped
,2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:53:38 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# all services are started when we call start
,2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'listening 53347'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:57CD477E-0DBE-42C6-8EBD-BFC589EDC1FA
,[ThaliCore] Browser.startListening
,2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-18 09:53:38 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-18 09:53:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "18B34BC2-4930-40E8-9FC9-2DCF156A02B7", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:18B34BC2-4930-40E8-9FC9-2DCF156A02B7
,2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-18 09:53:38 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-18 09:53:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 287 all connection succeed
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:18B34BC2-4930-40E8-9FC9-2DCF156A02B7
,2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-18 09:53:38 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:53:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"ad,vertisingActive":false}'
2017-07-18 09:53:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-18 09:53:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 288 must be stopped
,2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:53:38 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# TCP Servers Manager should be null when we call start on iOS
,2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'listening 53350'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:695E8E20-1986-46C1-ADF8-5D68B8925693
,[ThaliCore] Browser.startListening
,2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-18 09:53:38 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-18 09:53:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "1B4457DE-8C0D-4CF3-8953-D371E7C8732D", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:1B4457DE-8C0D-4CF3-8953-D371E7C8732D
,2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-18 09:53:38 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-18 09:53:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 289 TCP Servers Manager doesn't exists
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:1B4457DE-8C0D-4CF3-8953-D371E7C8732D
,2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-18 09:53:38 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-18 09:53:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:53:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-18 09:53:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 290 must be stopped
,2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:53:38 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# all services are stopped when we call stop
,2017-07-18 09:53:39 - DEBUG thaliMobileNativeWrapper: 'listening 53352'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:A21EAD4D-1ABB-45D0-947D-8E588D6A3E85
,[ThaliCore] Browser.startListening
,2017-07-18 09:53:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-18 09:53:39 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-18 09:53:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7E3D0BB5-4FA3-4194-9297-87098529DE9A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7E3D0BB5-4FA3-4194-9297-87098529DE9A", generation: 0)
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "713821EF-73BD-4E4F-A5C7-D1E380098DF9", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:713821EF-73BD-4E4F-A5C7-D1E380098DF9
2017-07-18 09:53:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-18 09:53:39 ,- INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-18 09:53:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:713821EF-73BD-4E4F-A5C7-D1E380098DF9
2017-07-1,8 09:53:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-18 09:53:39 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not m,atch with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:53:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate, (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-18 09:53:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertising,Active":false}'
2017-07-18 09:53:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-18 09:53:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 291 is stopped after calling stop
,2017-07-18 09:53:39 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"7E3D0BB5-4FA3-4194-9297-87098529DE9A","generation":0}]'
,2017-07-18 09:53:39 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"7E3D0BB5-4FA3-4194-9297-87098529DE9A","generation":0}'
,2017-07-18 09:53:39 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,ok 292 connection should fail after stopping
,# teardown
,ok 293 must be stopped
,2017-07-18 09:53:39 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:53:39 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:53:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:39 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:53:39 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:53:39 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:53:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:53:39 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateConnection is properly hooked up
,2017-07-18 09:53:39 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateConnection is properly hooked up''
,# teardown
,ok 294 must be stopped
,2017-07-18 09:53:39 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-18 09:53:39 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:53:39 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:39 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-18 09:53:39 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-18 09:53:39 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:53:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:53:39 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateConnection is return error if we get called on iOS
,ok 295 error description matches
,# teardown
,ok 296 must be stopped
,2017-07-18 09:53:39 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:53:39 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:53:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:39 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:53:39 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:53:39 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:53:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:53:39 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is properly hooked up
,2017-07-18 09:53:40 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateListener is properly hooked up''
,# teardown
,ok 297 must be stopped
,2017-07-18 09:53:40 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-18 09:53:40 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:53:40 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:53:40 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:53:40 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:53:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:53:40 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is return error if we get called on iOS
,ok 298 error description matches
,# teardown
,ok 299 must be stopped
,2017-07-18 09:53:40 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:53:40 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:53:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:53:40 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:53:40 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:53:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:53:40 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure we actually call kill connections properly
,ok 300 IMPLEMENT ME!!!!!!
,# teardown
,ok 301 must be stopped
,2017-07-18 09:53:40 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:53:40 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:53:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:53:40 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:53:40 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:53:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:53:40 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
,2017-07-18 09:53:41 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''
,# teardown
,ok 302 must be stopped
,2017-07-18 09:53:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-18 09:53:41 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:53:41 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-18 09:53:41 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-18 09:53:41 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:53:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:53:41 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager
,2017-07-18 09:53:41 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''
,# teardown
,ok 303 must be stopped
,2017-07-18 09:53:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-18 09:53:41 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:53:41 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-18 09:53:41 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-18 09:53:41 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-18 09:53:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-18 09:53:41 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from multiConnectConnection
,2017-07-18 09:53:41 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 304 must be stopped
,2017-07-18 09:53:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:53:41 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:53:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:53:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:53:41 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:53:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:53:41 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection
,2017-07-18 09:53:41 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 305 must be stopped
,2017-07-18 09:53:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:53:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:53:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:53:42 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:53:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:53:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:53:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved
,ok 306 NOT IMPLEMENTED # SKIP
,# teardown
,ok 307 must be stopped
,2017-07-18 09:53:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-18 09:53:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:53:42 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:53:42 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:53:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:53:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:53:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure bad PSK connections fail
,2017-07-18 09:53:42 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure bad PSK connections fail''
,# teardown
,ok 308 must be stopped
,2017-07-18 09:53:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:53:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:53:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:53:42 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:53:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:53:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:53:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peer changes handled from a queue
,2017-07-18 09:53:42 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer changes handled from a queue''
,# teardown
,ok 309 must be stopped
,2017-07-18 09:53:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:53:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:53:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:53:42 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:53:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:53:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:53:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# relaying discoveryAdvertisingStateUpdateNonTCP
,2017-07-18 09:53:43 - DEBUG CoordinatedClient: 'test was skipped, name: 'relaying discoveryAdvertisingStateUpdateNonTCP''
,# teardown
,ok 310 must be stopped
,2017-07-18 09:53:43 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-18 09:53:43 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:53:43 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-18 09:53:43 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-18 09:53:43 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-18 09:53:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-18 09:53:43 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received
,2017-07-18 09:53:43 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''
,# teardown
,ok 311 must be stopped
,2017-07-18 09:53:43 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:53:43 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:53:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:53:43 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:53:43 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:53:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:53:43 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# we successfully receive and replay discoveryAdvertisingStateUpdate
,2017-07-18 09:53:43 - DEBUG thaliMobileNativeWrapper: 'listening 53355'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:4BADDD29-ED94-4DE5-86F5-5A20EA3B69AF
,[ThaliCore] Browser.startListening
,2017-07-18 09:53:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-18 09:53:43 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-18 09:53:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 312 discoveryActive matches
ok 313 advertisingActive matches
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-18 09:53:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-18 09:53:43 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-18 09:53:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-18 09:53:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18, 09:53:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 314 discoveryActive matches
,ok 315 advertisingActive matches
,2017-07-18 09:53:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-18 09:53:43 - DEBUG thaliMobileNativeWrapper: 'listening 53356'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "08D8CC7A-B4C4-4793-9D50-0F5000DD92F1", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:08D8CC7A-B4C4-4793-9D50-0F5000DD92F1
,2017-07-18 09:53:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-18 09:53:43 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:53:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 316 discoveryActive matches
ok 317 advertisingActive matches
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:08D8CC7A-B4C4-4793-9D50-0F5000DD92F1
,2017-07-18 09:53:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:53:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 318 discoveryActive matches
ok 319 advertisingActive matches
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-18 09:53:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:53:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-18 09:53:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-18 09:53:43 - DEBUG thaliMobileNativeWrapper: 'listening 53358'
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-18 09:53:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:53:44 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-18 09:53:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-18 09:53:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-18 09:53:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 320 must be stopped
,2017-07-18 09:53:44 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:53:44 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:53:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:44 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:53:44 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:53:44 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:53:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:53:44 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS
,2017-07-18 09:53:44 - DEBUG thaliMobileNativeWrapper: 'listening 53359'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:5A9BCEC0-4BD1-4FAF-AF51-E9A3559F25AE
[ThaliCore] Browser.st,artListening
2017-07-18 09:53:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-18 09:53:44 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:53:44 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "AA83439B-E4F8-4F4A-A1E4-64C344071B20", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID,:AA83439B-E4F8-4F4A-A1E4-64C344071B20
,2017-07-18 09:53:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-18 09:53:44 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:53:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7E3D0BB5-4FA3-4194-9297-87098529DE9A:1
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7E3D0BB5-4FA3-4194-9297-87098529DE9A", generation: 1)
,2017-07-18 09:53:44 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"7E3D0BB5-4FA3-4194-9297-87098529DE9A","generation":1}]'
[ThaliCore] Browser.browser(_:foundPeer:withDi,scoveryInfo:) found peer:7E3D0BB5-4FA3-4194-9297-87098529DE9A:0
2017-07-18 09:53:44 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"7E3D0BB5-4FA3-4194-9297-87098529DE9A","generation",:1}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7E3D0BB5-4FA3-4194-9297-87098529DE9A", generation: 0)
,2017-07-18 09:53:44 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"7E3D0BB5-4FA3-4194-9297-87098529DE9A","peerAvailable":true,"generation":1,"portNumber":null}'
,2017-07-18 09:53:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7E3D0BB5-4FA3-4194-9297-87098529DE9A","connectionType":"MPCF","peerAvailable":true,"generation":1,"newAddressPort":false}'
,ok 321 portNumber equal null
,# teardown
,2017-07-18 09:53:44 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"7E3D0BB5-4FA3-4194-9297-87098529DE9A","generation":0}]'
,2017-07-18 09:53:44 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"7E3D0BB5-4FA3-4194-9297-87098529DE9A","generation":0}'
,2017-07-18 09:53:44 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"7E3D0BB5-4FA3-4194-9297-87098529DE9A","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:AA83439B-E4F8-4F4A-A1E4-64C344071B20
,2017-07-18 09:53:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-18 09:53:44 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-18 09:53:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-18 09:53:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:53:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-18 09:53:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 322 must be stopped
,2017-07-18 09:53:44 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:53:44 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:53:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:44 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:53:44 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:53:44 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:53:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:53:44 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can do HTTP requests between peers
,2017-07-18 09:53:45 - DEBUG thaliMobileNativeWrapper: 'listening 53361'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:FD136716-2FE8-43A2-AD73-6E23245E33A2
,[ThaliCore] Browser.startListening
,2017-07-18 09:53:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-18 09:53:45 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-18 09:53:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "953E254B-C59F-49CE-9D01-EB3331406366", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:953E254B-C59F-49CE-9D01-EB3331406366
,2017-07-18 09:53:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-18 09:53:45 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-18 09:53:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7E3D0BB5-4FA3-4194-9297-87098529DE9A:1
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7E3D0BB5-4FA3-4194-9297-87098529DE9A", generation: 1)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7E3D0BB5-4FA3-4194-9297-87098529DE9A:0
2017-07-18 09:53:45 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdent,ifier":"7E3D0BB5-4FA3-4194-9297-87098529DE9A","generation":1}]'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7E3D0BB5-4FA3-4194-9297-87098529DE9A", generation: 0)
2017-07-18 09:53:45 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"7E3D0BB5-4FA3-4194-9297-87098529DE9A","generation":1}'
2017-07-18 09:53:45 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,,"peerIdentifier":"7E3D0BB5-4FA3-4194-9297-87098529DE9A","generation":0}]'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3", generation: 0)
2017-07-18 09:53:45 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":,"7E3D0BB5-4FA3-4194-9297-87098529DE9A","generation":0}'
,2017-07-18 09:53:45 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3","generation":0}]'
2017-07-18 09:53:45 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3","generation":0}'
,2017-07-18 09:53:45 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"7E3D0BB5-4FA3-4194-9297-87098529DE9A","peerAvailable":true,"generation":1,"portNumber":null}'
2017-07-18 09:53:45 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"7E3D0BB5-4FA3-4194-9297-87098529DE9A","peerAvailable":true,"generation":1,"portNumber":null}'
,2017-07-18 09:53:45 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 7E3D0BB5-4FA3-4194-9297-87098529DE9A (syncValue: e4Kdop4a1pLqYxx7eRj0Y1H2eaEEwkhb)'
,2017-07-18 09:53:46 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7E3D0BB5-4FA3-4194-9297-87098529DE9A", generation: 1) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7E3D0BB5-4FA3-4194-9297-87098529DE9A", generation: 1)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:7E3D0BB5-4FA3-4194-9297-87098529DE9A:1
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-18 09:53:46 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"7E3D0BB5-4FA3-4194-9297-87098529DE9A","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-18 09:53:46 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"7E3D0BB5-4FA3-4194-9297-87098529DE9A","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-18 09:53:46 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-18 09:53:46 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-18 09:53:46 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F80E614C-89F2-4E6B-9BBB-DD598F1E5ADF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F80E614C-89F2-4E6B-9BBB-DD598F1E5ADF", generation: 0)
2017-07-18 09:53:46 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"F80E614C-89F2-4E6B-9BBB-DD598F1E5ADF","generation":0}]'
2017-07-18 09:53:46 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"F80E614C-89F2-4E6B-9BBB-DD598F1E5ADF","generation":0}'
,2017-07-18 09:53:46 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"F80E614C-89F2-4E6B-9BBB-DD598F1E5ADF","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-18 09:53:46 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"F80E614C-89F2-4E6B-9BBB-DD598F1E5ADF","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-18 09:53:46 - DEBUG thaliMobileNativeTestUtils: 'We got a pe,er {"peerIdentifier":"F80E614C-89F2-4E6B-9BBB-DD598F1E5ADF","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:953E254B-C59F-49CE-9D01-EB3331406366:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "953E254B-C59F-49CE-9D01-EB3331406366", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:7E3D0BB5-4FA3-4194-9297-87098529DE9A:1 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:7E,3D0BB5-4FA3-4194-9297-87098529DE9A:1
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "7E3D0BB5-4FA3-4194-9297-87098529DE9A", generation: 1)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,E3D0BB5-4FA3-4194-9297-87098529DE9A", generation: 1) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7E3D0BB5-4FA3-4194-9297-87098529DE9A", generation: 1)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:7E3D0BB5-4FA3-4194-9297-87098529DE9A:1
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:7E3D0BB5-4FA3-4194-9297-87098529DE9A:1
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:7E3D0BB5-4FA3-4194-9297-87098529DE9A:1 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:7E,3D0BB5-4FA3-4194-9297-87098529DE9A:1
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "7E3D0BB5-4FA3-4194-9297-87098529DE9A", generation: 1)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,E3D0BB5-4FA3-4194-9297-87098529DE9A", generation: 1) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7E3D0BB5-4FA3-4194-9297-87098529DE9A", generation: 1)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:7E3D0BB5-4FA3-4194-9297-87098529DE9A:1
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:7E3D0BB5-4FA3-4194-9297-87098529DE9A:1
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:7E3D0BB5-4FA3-4194-9297-87098529DE9A:1 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:7E,3D0BB5-4FA3-4194-9297-87098529DE9A:1
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "7E3D0BB5-4FA3-4194-9297-87098529DE9A", generation: 1)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,E3D0BB5-4FA3-4194-9297-87098529DE9A", generation: 1) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7E3D0BB5-4FA3-4194-9297-87098529DE9A", generation: 1)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:7E3D0BB5-4FA3-4194-9297-87098529DE9A:1
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:7E3D0BB5-4FA3-4194-9297-87098529DE9A:1
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C3E224A1-2594-49C9-BC04-CA81D35463B0
[ThaliCore] Advertiser: session connected Peer(uuid: "953E254B-C59F-49CE-9D01-EB3331406366", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:C3E224A1-2594-49C9-BC04-CA81D35463B0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:7E3D0BB5-4FA3-4194-9297-87098529DE9A:1 state: notConnected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:7E3D0BB5-4FA3-4194-9297-87098529DE9A:1
,[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "7E3D0BB5-4FA3-4194-9297-87098529DE9A", generation: 1)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:7E3D0BB5-4FA3-4194-9297-87098529DE9A error: max retries exceeded
,2017-07-18 09:53:50 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"e4Kdop4a1pLqYxx7eRj0Y1H2eaEEwkhb","error":"Connection could not be established","portNumber":null}'
,2017-07-18 09:53:50 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'e4Kdop4a1pLqYxx7eRj0Y1H2eaEEwkhb', error: 'Connection could not be established', listeningPort: '%s''
,2017-07-18 09:53:50 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"7E3D0BB5-4FA3-4194-9297-87098529DE9A","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-18 09:53:50 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"7E3D0BB5-4FA3-4194-9297-87098529DE9A","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-18 09:53:50 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"7E3D0BB5-4FA3-4194-9297-87098529DE9A","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-18 09:53:50 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"7E3D0BB5-4FA3-4194-9297-87098529DE9A","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-18 09:53:50 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"7E3D0BB5-4FA3-4194-9297-87098529DE9A","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-18 09:53:50 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"7E3D0BB5-4FA3-4194-9297-87098529DE9A","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-18 09:53:50 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"7E3D0BB5-4FA3-4194-9297-87098529DE9A","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-18 09:53:50 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-18 09:53:50 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3 (syncValue: Ai5PszR65Fwx0oa0VLCAFdrNxjolGv9m)'
,2017-07-18 09:53:50 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:7E3D0BB5-4FA3-4194-9297-87098529DE9A:1
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:C3E224A1-2594-49C9-BC04-CA81D35463B0
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:7E3D0BB5-4FA3-4194-9297-87098529DE9A:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "7E3D0BB5-4FA3-4194-9297-87098529DE9A", generation: 0)
[ThaliCore] Browser.browser(_:lostPeer:) lost peer,:7E3D0BB5-4FA3-4194-9297-87098529DE9A:1
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "7E3D0BB5-4FA3-4194-9297-87098529DE9A", generation: 1)
,2017-07-18 09:53:53 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"7E3D0BB5-4FA3-4194-9297-87098529DE9A","generation":1}]'
,2017-07-18 09:53:53 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"7E3D0BB5-4FA3-4194-9297-87098529DE9A","generation":1}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:C3E224A1-2594-49C9-BC04-CA81D35463B0 state: connecting -> connected
,2017-07-18 09:53:53 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"7E3D0BB5-4FA3-4194-9297-87098529DE9A","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-18 09:53:53 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7E3D0BB5-4FA3-4194-9297-87098529DE9A","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C3E224A1-2594-49C9-BC04-CA81D35463B0
,[ThaliCore] Session.startOutputStream(with:) peer:C3E224A1-2594-49C9-BC04-CA81D35463B0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:15 [3, 9, 12, 15]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:53365
,2017-07-18 09:53:53 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Ai5PszR65Fwx0oa0VLCAFdrNxjolGv9m","error":null,"portNumber":53365}'
,2017-07-18 09:53:53 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'Ai5PszR65Fwx0oa0VLCAFdrNxjolGv9m', error: 'null', listeningPort: '53365''
,2017-07-18 09:53:53 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:16 [3, 9, 12, 15, 16]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-18 09:53:53 - DEBUG testUtils: 'Got response data'
,2017-07-18 09:53:53 - DEBUG testUtils: 'Got end'
ok 323 response body should match testData
ok 324 must be started
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:953E254B-C59F-49CE-9D01-EB3331406366
,2017-07-18 09:53:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-18 09:53:54 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:53:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-18 09:53:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"ad,vertisingActive":false}'
2017-07-18 09:53:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-18 09:53:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 325 must be stopped
[ThaliCore] B,rowserManager.disconnect peer:1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:53365
[ThaliCore] VirtualSocket.closeStreams() vsID:16
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:15
[ThaliCore] VirtualSocket.closeS,treams() vsID:15
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:15
[ThaliCore] VirtualSocket.deinit vsID:15 [3, 9, 12, 16]
,[ThaliCore] VirtualSocket exited RunLoop vsID:16
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
,[ThaliCore] Session.disconnect() peer:1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3:0
,[ThaliCore] VirtualSocket.closeStreams() vsID:16
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
,[ThaliCore] VirtualSocket.deinit vsID:16 [3, 9, 12]
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uui,d: "1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3", generation: 0)
,2017-07-18 09:53:54 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:53:54 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:53:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:53:54 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,[ThaliCore] Session.session(_:peer:didChange:) peer:C3E224A1-2594-49C9-BC04-CA81D35463B0 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "953E254B-C59F-49CE-9D01-EB3331406366", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:C3E224A1-2594-49C9-BC04-CA81D35463B0
[ThaliCore] Advert,iserRelay.deinit
,2017-07-18 09:53:54 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:53:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:53:54 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,2017-07-18 09:53:54 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Ai5PszR65Fwx0oa0VLCAFdrNxjolGv9m","error":"Session disconnected","portNumber":null}'
,2017-07-18 09:53:54 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-18 09:53:54 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-18 09:53:54 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-18 09:53:54 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Session.deinit peer:1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3:0
[ThaliCore] BrowserRelay.deinit
,# setup
,# can still do HTTP requests between peers with coordinator
,2017-07-18 09:53:54 - DEBUG thaliMobileNativeWrapper: 'listening 53367'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:11BCFA4D-5BE1-460C-968F-2F65E7BABE5A
[ThaliCore] Browser.st,artListening
2017-07-18 09:53:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-18 09:53:54 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:53:54 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "832961D1-12F0-4253-9FBC-B054D32A0095", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID,:,832961D1-12F0-4253-9FBC-B054D32A0095
,2017-07-18 09:53:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-18 09:53:54 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-18 09:53:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Session.deinit peer:C3E224A1-2594-49C9-BC04-CA81D35463B0
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:832961D1-12F0-4253-9FBC-B054D32A0095:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "832961D1-12F0-4253-9FBC-B054D32A0095", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CA048616-D84D-433B-A13F-489E42F417AC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CA048616-D84D-433B-A13F-489E42F417AC", generation: 0)
,2017-07-18 09:53:55 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"CA048616-D84D-433B-A13F-489E42F417AC","generation":0}]'
2017-07-18 09:53:55 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"CA048616-D84D-433B-A13F-489E42F417AC","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3BAEA213-54FC-4444-8A5D-A5BD960AADD9:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3BAEA213-54FC-4444-8A5D-A5BD960AADD9", generation: 0)
2017-07-18 09:53:55 - DEBUG t,haliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"CA048616-D84D-433B-A13F-489E42F417AC","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-18 09:53:55 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged ,from handlePeer {"peerIdentifier":"CA048616-D84D-433B-A13F-489E42F417AC","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-18 09:53:55 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"CA04861,6-D84D-433B-A13F-489E42F417AC","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-18 09:53:55 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for CA048616-D84D-433B-A13F-489E42F417AC (syncValue: l9iRJ3Edo5R7f359AVV4VYdA1C36H4ZV)'
2017-07-18 09:53:55 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[T,haliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "CA048616-D84D-433B-A13F-489E42F417AC", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CA04,8616-D84D-433B-A13F-489E42F417AC", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:CA048616-D84D-433B-A13F-489E42F417AC:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-18 09:53:55 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"3BAEA213-54FC-4444-8A5D-A5BD960AADD9","generation":0}]'
,2017-07-18 09:53:55 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"3BAEA213-54FC-4444-8A5D-A5BD960AADD9","generation":0}'
,2017-07-18 09:53:55 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"3BAEA213-54FC-4444-8A5D-A5BD960AADD9","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-18 09:53:55 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"3BAEA213-54FC-4444-8A5D-A5BD960AADD9","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-18 09:53:55 - DEBUG thaliMobileNativeTestUtils: 'We got a pe,er {"peerIdentifier":"3BAEA213-54FC-4444-8A5D-A5BD960AADD9","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:CA048616-D84D-433B-A13F-489E42F417AC:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:CA048616-D84D-433B-A13F-489E42F417AC:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:CA048616-D84D-433B-A13F-489E42F417AC:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "CA048616-D84D-433B-A13F-489E42F417AC", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:53370
2017-07-18 09:53:58 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"l9iRJ3Edo5R7f359AVV4VYdA1C36H4ZV",,"error":null,"portNumber":53370}'
2017-07-18 09:53:58 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'l9iRJ3Edo5R7f359AVV4VYdA1C36H4ZV', error: 'null', listeningPort: '53370''
2017-07-18 09:53:58 - WARN thaliMobileNativeTestUti,ls: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:CA048616-D84D-433B-A13F-489E42F417AC:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:CA048616-D84D-433B-A13F-489E42F417AC:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:17 [3, 9, 12, 17]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-18 09:53:59 - DEBUG testUtils: 'Got response data'
,2017-07-18 09:53:59 - DEBUG testUtils: 'Got end'
,ok 326 response body should match testData
,ok 327 must be started
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D5B38585-3AFA-4187-8B9C-9F83CD736B33
[ThaliCore] Advertiser: session connected Peer(uuid: "832961D1-12F0-4253-9FBC-B054D32A0095", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:D5B38585-3AFA-4187-8B9C-9F83CD736B33 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:42D5359B-CE1E-433D-BB41-8294E9596A99
[ThaliCore] Advertiser: session connected Peer(uuid: "832961D1-12F0-4253-9FBC-B054D32A0095", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:42D5359B-CE1E-433D-BB41-8294E9596A99 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:42D5359B-CE1E-433D-BB41-8294E9596A99
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D5B38585-3AFA-4187-8B9C-9F83CD736B33
,[ThaliCore] Session.session(_:peer:didChange:) peer:D5B38585-3AFA-4187-8B9C-9F83CD736B33 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D5B38585-3AFA-4187-8B9C-9F83CD736B33
[ThaliCore] Session.startOutputStream(with:) peer:D5B38585-3AFA-4187-8B9C-9F83CD736B33
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:18 [3, 9, 12, 17, 18]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:42D5359B-CE1E-433D-BB41-8294E9596A99 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:42D5359B-CE1E-433D-BB41-8294E9596A99
[ThaliCore] Session.startOutputStream(with:) peer:42D5359B-CE1E-433D-BB41-8294E9596A99
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,9 [3, 9, 12, 17, 18, 19]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:832961D1-12F0-4253-9FBC-B054D32A0095
,2017-07-18 09:54:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-18 09:54:04 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:54:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-18 09:54:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"ad,vertisingActive":false}'
2017-07-18 09:54:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-18 09:54:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 328 must be stopped
[ThaliCore] B,rowserManager.disconnect peer:CA048616-D84D-433B-A13F-489E42F417AC
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSL,ocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescript,ion=Socket closed by remote peer})
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:53370
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket.closeStreams() vsID:17
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:18
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:19
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil,
[ThaliCore] VirtualSocket.closeStreams() vsID:18
[ThaliCore] VirtualSocket.closeStreams() vsID:19
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disc,onnecting
[ThaliCore] VirtualSocket exited RunLoop vsID:17
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] Session.session(_:peer:didChange:) peer:42D5359B-CE1E-433D-BB41-8294E9596A99 state: connected -> notConnected
[ThaliCore] Session,.disconnect() peer:CA048616-D84D-433B-A13F-489E42F417AC:0
[ThaliCore] TCPListener.deinit
[ThaliCore] VirtualSocket.deinit vsID:17 [3, 9, 12, 18, 19]
[ThaliCore] Advertiser: session notConnected Peer(uuid: "832961D1-12F0-4253-9FBC-B054D32A0095", generati,on: 0)
[ThaliCore] Session.deinit peer:CA048616-D84D-433B-A13F-489E42F417AC:0
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:19
[ThaliCore] AdvertiserRelay.didCloseVirtu,alSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:18
,[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] VirtualSocket.deinit vsID:19 [3, 9, 12, 18]
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:42D5359B-CE1E-433D-B,B41-8294E9596A99
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] VirtualSocket.deinit vsID:18 [3, 9, 12]
,2017-07-18 09:54:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:54:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:54:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,[ThaliCore] Session.session(_:peer:didChange:) peer:D5B38585-3AFA-4187-8B9C-9F83CD736B33 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "832961D1-12F0-4253-9FBC-B054D32A0095", generation: 0)
,2017-07-18 09:54:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:54:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:54:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:54:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:54:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.deinit peer:42D5359B-CE1E-433D-BB41-8294E9596A99
,# calls correct starts when network changes
,2017-07-18 09:54:05 - DEBUG CoordinatedClient: 'test was skipped, name: 'calls correct starts when network changes''
,# teardown
,ok 329 must be stopped
,2017-07-18 09:54:05 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-18 09:54:05 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:54:05 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:54:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-18 09:54:05 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-18 09:54:05 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-18 09:54:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:54:05 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# test to coordinate connection cut
,# teardown
,ok 330 must be stopped
,2017-07-18 09:54:05 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:54:05 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:54:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:54:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:54:05 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:54:05 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:54:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:54:05 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can do HTTP requests after connections are cut
,2017-07-18 09:54:06 - DEBUG thaliMobileNativeWrapper: 'listening 53374'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:455253BF-790E-4685-9B40-0827214A43F8
,[ThaliCore] Browser.startListening
,2017-07-18 09:54:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-18 09:54:06 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-18 09:54:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "50E8281F-8162-4C2A-8FC0-78964F5A9464", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:50E8281F-8162-4C2A-8FC0-78964F5A9464
,2017-07-18 09:54:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-18 09:54:06 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-18 09:54:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CA048616-D84D-433B-A13F-489E42F417AC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CA048616-D84D-433B-A13F-489E42F417AC", generation: 0)
,2017-07-18 09:54:06 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"CA048616-D84D-433B-A13F-489E42F417AC","generation":0}]'
2017-07-18 09:54:06 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"CA048616-D84D-433B-A13F-489E42F417AC","generation":0}'
,2017-07-18 09:54:06 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"CA048616-D84D-433B-A13F-489E42F417AC","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-18 09:54:06 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"CA048616-D84D-433B-A13F-489E42F417AC","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-18 09:54:06 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for CA048616-D84D-433B-A13F-489E42F417AC (syncValue: exzABWKrw5wBVkKsdeGZAsqm7ORTlHE5)'
,2017-07-18 09:54:06 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "CA048616-D84D-433B-A13F-489E42F417AC", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CA048616-D84D-433B-A13F-489E42F417AC", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:CA048616-D84D-433B-A13F-489E42F417AC:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:50E8281F-8162-4C2A-8FC0-78964F5A9464:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "50E8281F-8162-4C2A-8FC0-78964F5A9464", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7715A4C7-4E63-4CF7-ACF2-CA28E269C078:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7715A4C7-4E63-4CF7-ACF2-CA28E269C078", generation: 0)
,2017-07-18 09:54:07 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"7715A4C7-4E63-4CF7-ACF2-CA28E269C078","generation":0}]'
2017-07-18 09:54:07 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"7715A4C7-4E63-4CF7-ACF2-CA28E269C078","generation":0}'
,2017-07-18 09:54:07 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"7715A4C7-4E63-4CF7-ACF2-CA28E269C078","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-18 09:54:07 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7715A4C7-4E63-4CF7-ACF2-CA28E269C078","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-18 09:54:07 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"7715A4C7-4E63-4CF7-ACF2-CA28E269C078","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A2FF3948-3AB1-4483-B3E0-379DCE76812F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A2FF3948-3AB1-4483-B3E0-379DCE76812F", generation: 0)
,2017-07-18 09:54:07 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"A2FF3948-3AB1-4483-B3E0-379DCE76812F","generation":0}]'
2017-07-18 09:54:07 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"A2FF3948-3AB1-4483-B3E0-379DCE76812F","generation":0}'
,2017-07-18 09:54:07 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"A2FF3948-3AB1-4483-B3E0-379DCE76812F","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-18 09:54:07 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"A2FF3948-3AB1-4483-B3E0-379DCE76812F","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-18 09:54:07 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"A2FF3948-3AB1-4483-B3E0-379DCE76812F","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:CA048616-D84D-433B-A13F-489E42F417AC:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:CA,048616-D84D-433B-A13F-489E42F417AC:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "CA048616-D84D-433B-A13F-489E42F417AC", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C,A048616-D84D-433B-A13F-489E42F417AC", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CA048616-D84D-433B-A13F-489E42F417AC", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:CA048616-D84D-433B-A13F-489E42F417AC:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:CA048616-D84D-433B-A13F-489E42F417AC:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:CA048616-D84D-433B-A13F-489E42F417AC:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:CA,048616-D84D-433B-A13F-489E42F417AC:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "CA048616-D84D-433B-A13F-489E42F417AC", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C,A048616-D84D-433B-A13F-489E42F417AC", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CA048616-D84D-433B-A13F-489E42F417AC", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:CA048616-D84D-433B-A13F-489E42F417AC:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:CA048616-D84D-433B-A13F-489E42F417AC:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:CA048616-D84D-433B-A13F-489E42F417AC:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:CA,048616-D84D-433B-A13F-489E42F417AC:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "CA048616-D84D-433B-A13F-489E42F417AC", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C,A048616-D84D-433B-A13F-489E42F417AC", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CA048616-D84D-433B-A13F-489E42F417AC", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:CA048616-D84D-433B-A13F-489E42F417AC:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:CA048616-D84D-433B-A13F-489E42F417AC:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:BCCC528E-079E-40F9-9B63-457B4ACDBF3C
[ThaliCore] Advertiser: session connected Peer(uuid: "50E8281F-8162-4C2A-8FC0-78964F5A9464", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:BCCC528E-079E-40F9-9B63-457B4ACDBF3C state: notConnected -> connecting
[ThaliCore] Browser.browser(_:lostPeer:) lost peer:CA048616-D84D-43,3B-A13F-489E42F417AC:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "CA048616-D84D-433B-A13F-489E42F417AC", generation: 0)
2017-07-18 09:54:10 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"pe,erAvailable":false,"peerIdentifier":"CA048616-D84D-433B-A13F-489E42F417AC","generation":0}]'
2017-07-18 09:54:10 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"CA048616-D84D-433B-,A13F-489E42F417AC","generation":0}'
2017-07-18 09:54:10 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"CA048616-D84D-433B-A13F-489E42F417AC","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-18 09,:54:10 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"CA048616-D84D-433B-A13F-489E42F417AC","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:CA048616-D84D-433B-A13F-489E42F417AC:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:CA,048616-D84D-433B-A13F-489E42F417AC:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "CA048616-D84D-433B-A13F-489E42F417AC", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:CA048616,-D84D-433B-A13F-489E42F417AC error: max retries exceeded
2017-07-18 09:54:11 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"exzABWKrw5wBVkKsdeGZAsqm7ORTlHE5","error":"Connection could not be established","portNumber":null}'
2017-07-18 09:54:11 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'exzABWKrw5wBVkKsdeGZAsqm7ORTlHE5', error: 'Connection could not be established', listeningPort: '%s''
2017-07-18 09:54:11 - DEBUG thaliMobileNativeWrapper: 'Received ,peer availability changed event with {"peerIdentifier":"CA048616-D84D-433B-A13F-489E42F417AC","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-18 09:54:11 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"CA048616-D84D-433B-A13F-489E42F417AC","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-18 09:54:11 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"CA048616-D84D-433B-A13F-489E42F417,AC","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-18 09:54:11 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"CA048616-D84D-433B-A13F-489E42F417AC","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-18 09:54:11 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"CA048616-D84D-433B-A13F-489E42F417AC","peerAvailable":true,"portNumber":null,"recreated":true}'
,[ThaliCore] BrowserManager.disconnect peer:CA048616-D84D-433B-A13F-489E42F417AC
,2017-07-18 09:54:11 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-18 09:54:11 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 7715A4C7-4E63-4CF7-ACF2-CA28E269C078 (syncValue: RXZbR4OcSJqxvADEABCbaahnKBRQT5Hb)'
,2017-07-18 09:54:11 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7715A4C7-4E63-4CF7-ACF2-CA28E269C078", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7715A4C7-4E63-4CF7-ACF2-CA28E269C078", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:7715A4C7-4E63-4CF7-ACF2-CA28E269C078:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:CA048616-D84D-433B-A13F-489E42F417AC:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:7715A4C7-4E63-4CF7-ACF2-CA28E269C078:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:15FFD872-4FA8-4E97-B00D-5F02A41E7915
[ThaliCore] Advertiser: session connected Peer(uuid: "50E8281F-8162-4C2A-8FC0-78964F5A9464", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:15FFD872-4FA8-4E97-B00D-5F02A41E7915 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:BCCC528E-079E-40F9-9B63-457B4ACDBF3C
,[ThaliCore] Session.session(_:peer:didChange:) peer:BCCC528E-079E-40F9-9B63-457B4ACDBF3C state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:BCCC528E-079E-40F9-9B63-457B4ACDBF3C
,[ThaliCore] Session.startOutputStream(with:) peer:BCCC528E-079E-40F9-9B63-457B4ACDBF3C
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:20 [3, 9, 12, 20]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:7715A4C7-4E63-4CF7-ACF2-CA28E269C078:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:7715A4C7-4E63-4CF7-ACF2-CA28E269C078:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "7715A4C7-4E63-4CF7-ACF2-CA28E269C078", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:53390
,2017-07-18 09:54:14 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"RXZbR4OcSJqxvADEABCbaahnKBRQT5Hb","error":null,"portNumber":53390}'
,2017-07-18 09:54:14 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'RXZbR4OcSJqxvADEABCbaahnKBRQT5Hb', error: 'null', listeningPort: '53390''
,2017-07-18 09:54:14 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:7715A4C7-4E63-4CF7-ACF2-CA28E269C078:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7715A4C7-4E63-4CF7-ACF2-CA28E269C078:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:21 [3, 9, 12, 20, 21]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-18 09:54:14 - DEBUG testUtils: 'Got response data'
,2017-07-18 09:54:14 - DEBUG testUtils: 'Got end'
,ok 331 response body should match testData
,ok 332 must be started
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:15FFD872-4FA8-4E97-B00D-5F02A41E7915
,[ThaliCore] Session.session(_:peer:didChange:) peer:15FFD872-4FA8-4E97-B00D-5F02A41E7915 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:15FFD872-4FA8-4E97-B00D-5F02A41E7915
,[ThaliCore] Session.startOutputStream(with:) peer:15FFD872-4FA8-4E97-B00D-5F02A41E7915
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:22 [3, 9, 12, 20, 21, 22]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:50E8281F-8162-4C2A-8FC0-78964F5A9464
2017-07-18 09:54:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-07-18 09:54:16 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:54:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stop,Listening()
2017-07-18 09:54:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:54:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
,2017-07-18 09:54:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 333 must be stopped
,[ThaliCore] BrowserManager.disconnect peer:7715A4C7-4E63-4CF7-ACF2-CA28E269C078
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:53390
[ThaliCore] VirtualSocket.closeStr,eams() vsID:21
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket remo,ved, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] Session.session(_:peer:didChange:) peer:15FFD872-4FA8-4E97-B00D-5F02A41E7915 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "50E8281F-,8162-4C2A-8FC0-78964F5A9464", generation: 0)
,[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:20
[ThaliCore] VirtualSocket.closeS,treams() vsID:20
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket exited RunLoop vsID:21
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:true socket error:Optional(Error Dom,ain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.deinit
[ThaliCore] Session.disconnect() peer:7715A4C7-4E63-4CF7-ACF2-CA28E269C078:0
[ThaliCore] Vi,rtualSocket.closeStreams() vsID:22
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:22
[ThaliCore] VirtualSocket.closeStreams() vsID:21
[ThaliCore] Session.deinit peer:7715A4C7-4E63-4CF7-ACF2-CA28E269C078:0
[ThaliCore] VirtualSock,et.closeStreams() vsID:22
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket exited RunLoop vsID:20
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:true
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:true
,[ThaliCore] VirtualSocket.deinit vsID:21 [3, 9, 12, 20, 22]
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
,[ThaliCore] VirtualSocket exited RunLoop vsID:22
,[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:15FFD872-4FA8-4E97-B00D-5F02A41E7915
,[ThaliCore] VirtualSocket.deinit vsID:20 [3, 9, 12, 22]
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] VirtualSocket.deinit vsID:22 [3, 9, 12]
,[ThaliCore] BrowserRelay.deinit
,2017-07-18 09:54:16 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:54:16 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:54:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,[ThaliCore] Session.session(_:peer:didChange:) peer:BCCC528E-079E-40F9-9B63-457B4ACDBF3C state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "50E8281F-8162-4C2A-8FC0-78964F5A9464", generation: 0)
,2017-07-18 09:54:16 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:54:16 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:54:16 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:54:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:54:16 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# will fail bad PSK connection between peers
,[ThaliCore] Session.deinit peer:15FFD872-4FA8-4E97-B00D-5F02A41E7915
,ok 334 FIX ME, PLEASE!!!
,# teardown
,ok 335 must be stopped
,2017-07-18 09:54:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-18 09:54:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:54:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:54:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:54:18 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:54:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:54:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:54:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We provide notification when a listener dies and we recreate it
,2017-07-18 09:54:18 - DEBUG CoordinatedClient: 'test was skipped, name: 'We provide notification when a listener dies and we recreate it''
,# teardown
,ok 336 must be stopped
,2017-07-18 09:54:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-18 09:54:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:54:18 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:54:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:54:18 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:54:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:54:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:54:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated
,2017-07-18 09:54:18 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated''
,# teardown
,ok 337 must be stopped
,2017-07-18 09:54:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-18 09:54:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:54:19 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:54:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-18 09:54:19 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:54:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:54:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:54:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,ok 338 ThaliMobile should be stopped
,# #startListeningForAdvertisements should fail if start not called
,ok 339 specific error should be returned
,# teardown
,2017-07-18 09:54:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-18, 09:54:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"F80E614C-89F2-4E6B-9BBB-DD598F1E5ADF","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-18 09:54:19 ,- DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"3BAEA213-54FC-4444-8A5D-A5BD960AADD9","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-18 09:54:19 - DEBUG th,aliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"7715A4C7-4E63-4CF7-ACF2-CA28E269C078","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-18 09:54:19 - DEBUG thaliMobile,: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"A2FF3948-3AB1-4483-B3E0-379DCE76812F","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 340 error should be null
,ok 341 error should be null
,# setup
,ok 342 ThaliMobile should be stopped
,# #startUpdateAdvertisingAndListening should fail if start not called
,ok 343 specific error should be returned
,# teardown
,ok 344 error should be null
,ok 345 error should be null
,# setup
,ok 346 ThaliMobile should be stopped
,# should be able to call #stopListeningForAdvertisements many times
,2017-07-18 09:54:20 - DEBUG thaliMobileNativeWrapper: 'listening 53393'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-18 09:54:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 347 error should be null
,ok 348 error should be null
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-18 09:54:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 349 error should be null
,ok 350 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-18 09:54:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:54:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-18 09:54:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:54:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-18 09:54:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 351 error should be null
,ok 352 error should be null
,# setup
,ok 353 ThaliMobile should be stopped
,# should be able to call #startListeningForAdvertisements many times
,2017-07-18 09:54:20 - DEBUG thaliMobileNativeWrapper: 'listening 53394'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:3F3E7F61-204F-493D-9320-08201177C997
,[ThaliCore] Browser.startListening
,2017-07-18 09:54:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,ok 354 error should be null
ok 355 error should be null
[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-07-18 09:54:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,ok 356 error should be null
,ok 357 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-18 09:54:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-18 09:54:20 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
,2017-07-18 09:54:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-18 09:54:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:54:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-07-18 09:54:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 358 error should be null
,ok 359 error should be null
,# setup
,ok 360 ThaliMobile should be stopped
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-07-18 09:54:21 - DEBUG thaliMobileNativeWrapper: 'listening 53395'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "A8235925-5951-4905-9BEA-7BF169A9C632", generation: 0)
[ThaliCore] Advertiser.startA,dvertising with peerID:A8235925-5951-4905-9BEA-7BF169A9C632
2017-07-18 09:54:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 361 error should be null
ok 362 error should, be null
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "A8235925-5951-4905-9BEA-7BF169A9C632", generation: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:A8235925-5951-4905-9BEA-7BF169A9C632
20,17-07-18 09:54:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 363 error should be null
ok 364 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:A8235925-5951-4905-9BEA-7BF169A9C632
,[ThaliCore] Advertiser.stopAdvertising() peerID:A8235925-5951-4905-9BEA-7BF169A9C632
,2017-07-18 09:54:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:54:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-18 09:54:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:54:21 - INFO thaliMobile: 'Fi,ltered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-18 09:54:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 365 error should be null
,ok 366 error should be null
,# setup
,ok 367 ThaliMobile should be stopped
,# should be able to call #stopAdvertisingAndListening many times
,2017-07-18 09:54:21 - DEBUG thaliMobileNativeWrapper: 'listening 53398'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-18 09:54:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 368 error should be null
,ok 369 error should be null
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-18 09:54:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 370 error should be null
,ok 371 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-18 09:54:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:54:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-18 09:54:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:54:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-18 09:54:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 372 error should be null
,ok 373 error should be null
,# setup
,ok 374 ThaliMobile should be stopped
,# #start - Causing native or wifi to fail will cause a promise reject 
,2017-07-18 09:54:21 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a Null'
,ok 375 This should not cause wifi to fail
,ok 376 native router should be bad
,# teardown
,ok 377 error should be null
,ok 378 error should be null
,# setup
,ok 379 ThaliMobile should be stopped
,# #start should fail if called twice in a row
,2017-07-18 09:54:21 - DEBUG thaliMobileNativeWrapper: 'listening 53399'
,ok 380 first call should succeed
,ok 381 first call should succeed
,ok 382 specific error should be returned
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-18 09:54:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:54:22 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-18 09:54:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-18 09:54:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-18 09:54:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 383 error should be null
ok 384 error should be null
,# setup
,ok 385 ThaliMobile should be stopped
,# #start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)
,2017-07-18 09:54:22 - DEBUG CoordinatedClient: 'test was skipped, name: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''
,# teardown
,ok 386 error should be null
ok 387 error should be null
,# setup
,ok 388 ThaliMobile should be stopped
,# does not emit duplicate discoveryAdvertisingStateUpdate
,2017-07-18 09:54:22 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not emit duplicate discoveryAdvertisingStateUpdate''
,# teardown
,ok 389 error should be null
ok 390 error should be null
,# setup
,ok 391 ThaliMobile should be stopped
,# does not send duplicate availability changes
,2017-07-18 09:54:22 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5010803c-7d03-4712-ad9d-027452e089ab","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 392 should be called once
,ok 393 should not have been called more than once
,# teardown
,2017-07-18 09:54:23 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"5010803c-7d03-4712-ad9d-027452e089ab","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 394 error should be null
ok 395 error should be null
,# setup
,ok 396 ThaliMobile should be stopped
,# can get the network status
,ok 397 network status should have certain non-empty properties
,# teardown
,ok 398 error should be null
ok 399 error should be null
,# setup
,ok 400 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer added/removed to/from cache (native)
,ok 401 we have not added peer to the cache yet
2017-07-18 09:54:23 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"ae34ed18-7d19-4931-ae8c-7c6bf3ec5adf","connectionType":"MPCF","peerAvailable":true,"generation":0,,"newAddressPort":false}'
ok 402 peer should be available
ok 403 cache contains native peer
2017-07-18 09:54:23 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"ae34ed18-7d19-4931-ae8c-7c6bf3ec5adf","connectionTyp,e":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
,ok 404 peer should be unavailable
ok 405 peer has been removed from cache
,# teardown
,ok 406 error should be null
,ok 407 error should be null
,# setup
,ok 408 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer added/removed to/from cache (wifi)
,ok 409 we have not added peer to the cache yet
,2017-07-18 09:54:23 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"205265ae-b12f-4850-97b8-34642de8dbe8","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 410 peer should be available
,ok 411 cache contains wifi peer
,2017-07-18 09:54:23 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"205265ae-b12f-4850-97b8-34642de8dbe8","connectionType":"tcp","peerAvailable":false,"generation":0,"newAddressPort":null}'
,ok 412 peer should be unavailable
,ok 413 peer has been removed from cache
,# teardown
,ok 414 error should be null
,ok 415 error should be null
,# setup
,ok 416 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored
,2017-07-18 09:54:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"59d4bc96-d862-457a-9463-e528c14ee32b","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 417 first peer is available
,2017-07-18 09:54:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"fce11814-1020-4226-b7e7-550e8c768367","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 418 second peer is available
,ok 419 first and second peers are different
,# teardown
,2017-07-18 09:54:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"59d4bc96-d862-457a-9463-e528c14ee32b","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-18 09:54:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"fce11814-1020-4226-b7e7-550e8c768367","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 420 error should be null
,ok 421 error should be null
,# setup
,ok 422 ThaliMobile should be stopped
,# native available - new peer is cached
,ok 423 should not be in cache at start
,2017-07-18 09:54:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"b27a935e-8cf1-4716-8edf-11186eef2e89","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 424 peer is available
,# teardown
,2017-07-18 09:54:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"b27a935e-8cf1-4716-8edf-11186eef2e89","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 425 error should be null
,ok 426 error should be null
,# setup
,ok 427 ThaliMobile should be stopped
,# native available - peer with same port and different generation is cached (BLUETOOTH)
,2017-07-18 09:54:24 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with same port and different generation is cached (BLUETOOTH)''
,# teardown
,ok 428 error should be null
,ok 429 error should be null
,# setup
,ok 430 ThaliMobile should be stopped
,# native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)
,2017-07-18 09:54:24 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)''
,# teardown
,ok 431 error should be null
,ok 432 error should be null
,# setup
,ok 433 ThaliMobile should be stopped
,# native available - peer with greater generation is cached (MPCF)
,2017-07-18 09:54:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"ca91c06c-fe98-4c9e-aba2-9f9a417f084a","connectionType":"MPCF","peerAvailable":true,"generation":2,"newAddressPort":false}'
,ok 434 peer should be available
,2017-07-18 09:54:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"ca91c06c-fe98-4c9e-aba2-9f9a417f084a","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
,ok 435 peer should be available
,ok 436 should store correct generation
,# teardown
,2017-07-18 09:54:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"ca91c06c-fe98-4c9e-aba2-9f9a417f084a","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 437 error should be null
,ok 438 error should be null
,# setup
,ok 439 ThaliMobile should be stopped
,# native available - peer with same or older generation is ignored (MPCF)
,2017-07-18 09:54:25 - DEBUG thaliMobileNativeWrapper: 'listening 53400'
,2017-07-18 09:54:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"a6af495f-e404-4098-bd2d-442060ca857a","connectionType":"MPCF","peerAvailable":true,"generation":2,"newAddressPort":false}'
,ok 440 discovered correct peer
,ok 441 got correct generation
,2017-07-18 09:54:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"a6af495f-e404-4098-bd2d-442060ca857a","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
,ok 442 discovered correct peer
,ok 443 got correct generation
,# teardown
,2017-07-18 09:54:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"a6af495f-e404-4098-bd2d-442060ca857a","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-18 09:54:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:54:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-18 09:54:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:54:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-18 09:54:25 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 444 error should be null
,ok 445 error should be null
,# setup
,ok 446 ThaliMobile should be stopped
,# native unavailable - new peer is ignored
,2017-07-18 09:54:25 - DEBUG thaliMobileNativeWrapper: 'listening 53401'
,2017-07-18 09:54:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"d6cb6a50-0edf-4bff-a265-04ce72d0c187","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 447 discovered available peer
,ok 448 peer is available
,# teardown
,2017-07-18 09:54:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"d6cb6a50-0edf-4bff-a265-04ce72d0c187","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-18 09:54:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:54:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-18 09:54:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:54:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-18 09:54:25 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 449 error should be null
,ok 450 error should be null
,# setup
,ok 451 ThaliMobile should be stopped
,# native unavailable - cached peer is removed
,2017-07-18 09:54:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"ee85892b-6041-40bc-93e3-5e4439f714e4","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 452 peer should be available
,2017-07-18 09:54:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"ee85892b-6041-40bc-93e3-5e4439f714e4","connectionType":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
,ok 453 peer should be unavailable
,ok 454 should be removed from cache
,# teardown
,ok 455 error should be null
,ok 456 error should be null
,# setup
,ok 457 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for wifi peers
,2017-07-18 09:54:26 - DEBUG thaliMobileNativeWrapper: 'listening 53402'
,2017-07-18 09:54:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"28e8986b-7c4c-46b6-adc3-6cbe674245a1","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 458 first peer is expected to be available
,2017-07-18 09:54:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"17ccf2a4-0ad9-4d50-b79a-752dcb7f9eba","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 459 second peer is expected to be available
,2017-07-18 09:54:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"17ccf2a4-0ad9-4d50-b79a-752dcb7f9eba","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 460 peer became unavailable
,ok 461 it was wifi peer
,2017-07-18 09:54:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"17ccf2a4-0ad9-4d50-b79a-752dcb7f9eba","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 462 we found peer again
,ok 463 it was wifi peer
2017-07-18 09:54:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"17ccf2a4-0ad9-4d50-b79a-752dcb7f9eba","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 464 peer became unavailable
,ok 465 it was wifi peer
,# teardown
,2017-07-18 09:54:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"28e8986b-7c4c-46b6-adc3-6cbe674245a1","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore,] AdvertiserManager.stopAdvertising()
2017-07-18 09:54:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:54:26 - INFO thaliMobile: 'Filtered out discoveryAdvert,isingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-18 09:54:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017,-07-18 09:54:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-18 09:54:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 466 error should be null
,ok 467 error should be null
,# setup
,ok 468 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)
,2017-07-18 09:54:26 - DEBUG CoordinatedClient: 'test was skipped, name: 'networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)''
,# teardown
,ok 469 error should be null
,ok 470 error should be null
,# setup
,ok 471 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)
,2017-07-18 09:54:26 - DEBUG thaliMobileNativeWrapper: 'listening 53403'
,2017-07-18 09:54:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"752853a1-c055-487c-861e-c67245de59c8","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 472 first peer is expected to be available
,2017-07-18 09:54:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"f0256867-3e7f-483e-b0c7-9b2fe7d4120b","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 473 second peer is expected to be available
,2017-07-18 09:54:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"752853a1-c055-487c-861e-c67245de59c8","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 474 peer became unavailable
,2017-07-18 09:54:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"f0256867-3e7f-483e-b0c7-9b2fe7d4120b","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 475 peer became unavailable
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-18 09:54:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:54:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-18 09:54:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:54:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-18 09:54:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 476 error should be null
,ok 477 error should be null
,# setup
,ok 478 ThaliMobile should be stopped
,# multiconnect failure - new peer is ignored (MPCF)
,2017-07-18 09:54:26 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - new peer is ignored (MPCF)''
,# teardown
,ok 479 error should be null
,ok 480 error should be null
,# setup
,ok 481 ThaliMobile should be stopped
,# multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)
,2017-07-18 09:54:26 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''
,# teardown
,ok 482 error should be null
,ok 483 error should be null
,# setup
,ok 484 ThaliMobile should be stopped
,# newAddressPort field (TCP_NATIVE)
,2017-07-18 09:54:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"3720ac1e-3395-43fe-835a-ef06ac8d0df8","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 485 peer discovered first time does not have new address
,2017-07-18 09:54:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"3720ac1e-3395-43fe-835a-ef06ac8d0df8","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddressPort":false}'
,ok 486 address has not been changed
,2017-07-18 09:54:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"3720ac1e-3395-43fe-835a-ef06ac8d0df8","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddressPort":true}'
,ok 487 new port handled correctly
,2017-07-18 09:54:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"3720ac1e-3395-43fe-835a-ef06ac8d0df8","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddressPort":true}'
,ok 488 new host handled correctly
,2017-07-18 09:54:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"3720ac1e-3395-43fe-835a-ef06ac8d0df8","connectionType":"tcp","peerAvailable":false,"generation":20,"newAddressPort":null}'
,ok 489 newAddressPort is null for unavailable peers
,# teardown
,ok 490 error should be null
,ok 491 error should be null
,# setup
,ok 492 ThaliMobile should be stopped
,# newAddressPort field (BLUETOOTH)
,2017-07-18 09:54:27 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort field (BLUETOOTH)''
,# teardown
,ok 493 error should be null
ok 494 error should be null
,# setup
,ok 495 ThaliMobile should be stopped
,# newAddressPort field (MPCF)
,ok 496 NOT IMPLEMENTED # SKIP
,# teardown
,ok 497 error should be null
ok 498 error should be null
,# setup
,ok 499 ThaliMobile should be stopped
,# newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)
,2017-07-18 09:54:27 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)''
,# teardown
,ok 500 error should be null
ok 501 error should be null
,# setup
,ok 502 ThaliMobile should be stopped
,# #getPeerHostInfo - error when peer has not been discovered yet
,ok 503 should be equal
,# teardown
,ok 504 error should be null
ok 505 error should be null
,# setup
,ok 506 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)
,2017-07-18 09:54:28 - DEBUG CoordinatedClient: 'test was skipped, name: '#getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)''
,# teardown
,ok 507 error should be null
ok 508 error should be null
,# setup
,ok 509 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)
,2017-07-18 09:54:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 510 contains expected properties
,ok 511 the same hostAddress
,ok 512 the same portNumber
,# teardown
,2017-07-18 09:54:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 513 error should be null
,ok 514 error should be null
,# setup
,ok 515 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached wifi peer
,2017-07-18 09:54:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 516 contains expected properties
ok 517 the same hos,tAddress
ok 518 the same portNumber
,# teardown
,2017-07-18 09:54:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 519 error should be null
ok 520 error should be null
,# setup
,ok 521 ThaliMobile should be stopped
,# #disconnect fails on wifi peers
,2017-07-18 09:54:29 - DEBUG thaliMobileNativeWrapper: 'listening 53404'
,2017-07-18 09:54:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"8f5a313f-d1f8-409f-a724-77197d66eeac","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 522 Got specific error message
,# teardown
,2017-07-18 09:54:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"8f5a313f-d1f8-409f-a724-77197d66eeac","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-18 09:54:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:54:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-18 09:54:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:54:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-18 09:54:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 523 error should be null
,ok 524 error should be null
,# setup
,ok 525 ThaliMobile should be stopped
,# #disconnect delegates native peers to the native wrapper
,2017-07-18 09:54:30 - DEBUG thaliMobileNativeWrapper: 'listening 53405'
,2017-07-18 09:54:30 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"849d3513-5ed4-4314-b4ce-9d5608aac10e","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] BrowserManager.disconnect peer:849d3513-5ed4-4314-b4ce-9d5608aac10e
,ok 526 native wrapper `disconnect` called once
,ok 527 native wrapper `disconnect` called with peer data
,# teardown
,2017-07-18 09:54:30 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"849d3513-5ed4-4314-b4ce-9d5608aac10e","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-18 09:54:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:54:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-18 09:54:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:54:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-18 09:54:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 528 error should be null
,ok 529 error should be null
,# setup
,ok 530 ThaliMobile should be stopped
,# network changes emitted correctly
,2017-07-18 09:54:30 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes emitted correctly''
,# teardown
,ok 531 error should be null
ok 532 error should be null
,# setup
,ok 533 ThaliMobile should be stopped
,# network changes not emitted in started state
,2017-07-18 09:54:30 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes not emitted in started state''
,# teardown
,ok 534 error should be null
,ok 535 error should be null
,# setup
,ok 536 ThaliMobile should be stopped
,# network changes not emitted in stopped state
,2017-07-18 09:54:30 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes not emitted in stopped state''
,# teardown
,ok 537 error should be null
,ok 538 error should be null
,# setup
,ok 539 ThaliMobile should be stopped
,# We properly fire peer unavailable and then available when connection fails on Android
,2017-07-18 09:54:30 - DEBUG CoordinatedClient: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on Android''
,# teardown
,ok 540 error should be null
,ok 541 error should be null
,# setup
,ok 542 ThaliMobile should be stopped
,# We properly fire peer unavailable and then available when connection fails on iOS
,2017-07-18 09:54:31 - DEBUG CoordinatedClient: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on iOS''
,# teardown
,ok 543 error should be null
,ok 544 error should be null
,# setup
,ok 545 ThaliMobile should be stopped
,# If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen
,2017-07-18 09:54:31 - DEBUG CoordinatedClient: 'test was skipped, name: 'If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen''
,# teardown
,ok 546 error should be null
,ok 547 error should be null
,# setup
,ok 548 ThaliMobile should be stopped
,# does not fire duplicate events after peer listener recreation
,2017-07-18 09:54:31 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not fire duplicate events after peer listener recreation''
,# teardown
,ok 549 error should be null
,ok 550 error should be null
,# setup
,ok 551 ThaliMobile should be stopped
,# #stop should change peers
,2017-07-18 09:54:32 - DEBUG thaliMobileNativeWrapper: 'listening 53406'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:5E008472-229E-4D75-A402-5F69F0A0D944
,[ThaliCore] Browser.startListening
,2017-07-18 09:54:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-18 09:54:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"0e10c486-7e41-4306-ae13-afdfec38d77d","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 552 Peer availabilities has one entry for our connection type
,2017-07-18 09:54:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"49d06e03-e581-47d3-b563-5e170bc8873f","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 553 Peer availabilities has one entry for our connection type
,2017-07-18 09:54:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"0e10c486-7e41-4306-ae13-afdfec38d77d","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-18 09:54:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"49d06e03-e581-47d3-b563-5e170bc8873f","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-18 09:54:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-18 09:54:32 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"pskIdToSecret":[102,111,1,11],"networkType":"BOTH"}})'
,2017-07-18 09:54:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-18 09:54:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:54:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-18 09:54:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-18 09:54:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 554 No peers
,ok 555 No peers
,ok 556 No peers
,# teardown
,ok 557 error should be null
,ok 558 error should be null
,# setup
,ok 559 ThaliMobile should be stopped
,# If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted
,2017-07-18 09:54:32 - DEBUG thaliMobileNativeWrapper: 'listening 53407'
2017-07-18 09:54:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"4ee99ce4-8bd0-4ae3-a16d-4352a5356eda","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 560 1
ok 561 2
,2017-07-18 09:54:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"fa78cf8a-8e3a-42e1-876f-9a52629d6535","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,# teardown
,2017-07-18 09:54:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"4ee99ce4-8bd0-4ae3-a16d-4352a5356eda","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-18 09:54:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"fa78cf8a-8e3a-42e1-876f-9a52629d6535","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-18 09:54:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:54:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-18 09:54:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:54:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-18 09:54:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 562 error should be null
,ok 563 error should be null
,# setup
,ok 564 ThaliMobile should be stopped
,# peer should be found once after listening and discovery started
,2017-07-18 09:54:32 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer should be found once after listening and discovery started''
,# teardown
,ok 565 error should be null
ok 566 error should be null
,# setup
,ok 567 ThaliMobile should be stopped
,# can get data from all participants
,2017-07-18 09:54:33 - DEBUG thaliMobileNativeWrapper: 'listening 53408'
ok 568 error should be null
ok 569 error should be null
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "1329D84C-3DE0-4ED2-9740-36,D47DF4B8A6", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:1329D84C-3DE0-4ED2-9740-36D47DF4B8A6
2017-07-18 09:54:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive,":true}'
ok 570 error should be null
,ok 571 error should be null
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:3D6A37F7-08ED-4D66-A1B5-D3E4F6D61074
[ThaliCore] Browser.startListening
2017-07-18 09:54:33 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,ok 572 error should be null
ok 573 error should be null
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A2FF3948-3AB1-4483-B3E0-379DCE76812F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A2FF3948-3AB1-4483-B3E0-379DCE76812F", generation: 0)
,2017-07-18 09:54:33 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"A2FF3948-3AB1-4483-B3E0-379DCE76812F","generation":0}]'
2017-07-18 09:54:33 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"A2FF3948-3AB1-4483-B3E0-379DCE76812F","generation":0}'
,2017-07-18 09:54:33 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"A2FF3948-3AB1-4483-B3E0-379DCE76812F","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-18 09:54:33 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"A2FF3948-3AB1-4483-B3E0-379DCE76812F","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-18 09:54:33 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for A2FF3948-3AB1-4483-B3E0-379DCE76812F (syncValue: 0)'
,2017-07-18 09:54:33 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A2FF3948-3AB1-4483-B3E0-379DCE76812F", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A2FF3948-3AB1-4483-B3E0-379DCE76812F", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:A2FF3948-3AB1-4483-B3E0-379DCE76812F:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:A2FF3948-3AB1-4483-B3E0-379DCE76812F:0 state: notConnected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:connecting
,[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:A2FF3948-3AB1-4483-B3E0-379DCE76812F:0
,[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "A2FF3948-3AB1-4483-B3E0-379DCE76812F", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A2FF3948-3AB1-4483-B3E0-379DCE76812F", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A2FF3948-3AB1-4483-B3E0-379DCE76812F", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:A2FF3948-3AB1-4483-B3E0-379DCE76812F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:A2FF3948-3AB1-4483-B3E0-379DCE76812F:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:104BF86E-803C-46C8-8A9E-8387091CD103:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "104BF86E-803C-46C8-8A9E-8387091CD103", generation: 0)
,2017-07-18 09:54:34 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"104BF86E-803C-46C8-8A9E-8387091CD103","generation":0}]'
,2017-07-18 09:54:34 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"104BF86E-803C-46C8-8A9E-8387091CD103","generation":0}'
,2017-07-18 09:54:34 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"104BF86E-803C-46C8-8A9E-8387091CD103","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-18 09:54:34 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"104BF86E-803C-46C8-8A9E-8387091CD103","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1329D84C-3DE0-4ED2-9740-36D47DF4B8A6:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1329D84C-3DE0-4ED2-9740-36D47DF4B8A6", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:45ABA631-FD53-4044-BA01-13FE72BF09A5:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "45ABA631-FD53-4044-BA01-13FE72BF09A5", generation: 0)
2017-07-18 09:54:35 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"45ABA631-FD53-4044-BA01-13FE72BF09A5","generation":0}]'
2017-07-18 09:54:35 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"45ABA631-FD53-4044-BA01-13FE72BF09A5","generation":0}'
,2017-07-18 09:54:35 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"45ABA631-FD53-4044-BA01-13FE72BF09A5","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-18 09:54:35 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"45ABA631-FD53-4044-BA01-13FE72BF09A5","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:A2FF3948-3AB1-4483-B3E0-379DCE76812F:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:A2,FF3948-3AB1-4483-B3E0-379DCE76812F:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "A2FF3948-3AB1-4483-B3E0-379DCE76812F", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A,2FF3948-3AB1-4483-B3E0-379DCE76812F", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A2FF3948-3AB1-4483-B3E0-379DCE76812F", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:A2FF3948-3AB1-4483-B3E0-379DCE76812F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:A2FF3948-3AB1-4483-B3E0-379DCE76812F:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:A2FF3948-3AB1-4483-B3E0-379DCE76812F:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "A2FF3948-3AB1-4483-B3E0-379DCE76812F", generation: 0)
2017-07-18 09:54:36 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"A2FF3948-3AB1-4483-B3E0-379DCE76812F","generation":0}]'
2017-07-18 09:54:36 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"A2FF3948-3AB1-4483-B3E0-379DCE76812F","generation":0}'
,2017-07-18 09:54:36 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"A2FF3948-3AB1-4483-B3E0-379DCE76812F","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-18 09:54:36 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"A2FF3948-3AB1-4483-B3E0-379DCE76812F","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:A2FF3948-3AB1-4483-B3E0-379DCE76812F:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:A2,FF3948-3AB1-4483-B3E0-379DCE76812F:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "A2FF3948-3AB1-4483-B3E0-379DCE76812F", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A,2FF3948-3AB1-4483-B3E0-379DCE76812F", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A2FF3948-3AB1-4483-B3E0-379DCE76812F", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-18 09:54:36 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"0","error":"Peer is unavailable","portNumber":null}'
2017-07-1,8 09:54:36 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"A2FF3948-3AB1-4483-B3E0-379DCE76812F","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-18 09:54:36 - DEBUG thaliMobileNativeWr,apper: 'Received peer availability changed event with {"peerIdentifier":"A2FF3948-3AB1-4483-B3E0-379DCE76812F","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-18 09:54:36 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 104BF86E-803C-46C8-8A9E-8387091CD103 (syncValue: 1)'
2017-07-18 09:54:36 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPee,r(_:syncValue:retryCount:completion:) Peer(uuid: "104BF86E-803C-46C8-8A9E-8387091CD103", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "104BF86E-803C-46C8-8A9E-8387091CD103", ge,neration: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:104BF86E-803C-46C8-8A9E-8387091CD103:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnec,ted:stoppedListening:)
2017-07-18 09:54:36 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"A2FF3948-3AB1-4483-B3E0-379DCE76812F","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-18 09:54:36 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"A2FF3948-3AB1-4483-B3E0-379DCE76812F","peerAvailable":true,"portNumber":null,"recreated":true}'
,[ThaliCore] Session.deinit peer:A2FF3948-3AB1-4483-B3E0-379DCE76812F:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:104BF86E-803C-46C8-8A9E-8387091CD103:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:95A0E461-9F45-4061-BC4B-3B465DD9E1FD
[ThaliCore] Advertiser: session connected Peer(uuid: "1329D84C-3DE0-4ED2-9740-36D47DF4B8A6", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:95A0E461-9F45-4061-BC4B-3B465DD9E1FD state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:104BF86E-803C-46C8-8A9E-8387091CD103:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:104BF86E-803C-46C8-8A9E-8387091CD103:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "104BF86E-803C-46C8-8A9E-8387091CD103", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:53419
2017-07-18 09:54:40 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"1","error":null,"portNumber":53419,}'
,2017-07-18 09:54:40 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 45ABA631-FD53-4044-BA01-13FE72BF09A5 (syncValue: 2)'
,2017-07-18 09:54:40 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "45ABA631-FD53-4044-BA01-13FE72BF09A5", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "45ABA631-FD53-4044-BA01-13FE72BF09A5", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:45ABA631-FD53-4044-BA01-13FE72BF09A5:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:104BF86E-803C-46C8-8A9E-8387091CD103:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:104BF86E-803C-46C8-8A9E-8387091CD103:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:23 [3, 9, 12, 23]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:25F94381-7A5C-4103-B229-CF501806E9D4
[ThaliCore] Advertiser: session connected Peer(uuid: "1329D84C-3DE0-4ED2-9740-36D47DF4B8A6", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:25F94381-7A5C-4103-B229-CF501806E9D4 state: notConnected -> connecting
,2017-07-18 09:54:40 - DEBUG testUtils: 'Got response data'
2017-07-18 09:54:40 - DEBUG testUtils: 'Got end'
,[ThaliCore] Session.session(_:peer:didChange:) peer:45ABA631-FD53-4044-BA01-13FE72BF09A5:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A2FF3948-3AB1-4483-B3E0-379DCE76812F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A2FF3948-3AB1-4483-B3E0-379DCE76812F", generation: 0)
2017-07-18 09:54:41 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"A2FF3948-3AB1-4483-B3E0-379DCE76812F","generation":0}]'
2017-07-18 09:54:41 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"A2FF3948-3AB1-4483-B3E0-379DCE76812F","generation":0}'
,2017-07-18 09:54:41 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"A2FF3948-3AB1-4483-B3E0-379DCE76812F","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-18 09:54:41 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"A2FF3948-3AB1-4483-B3E0-379DCE76812F","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:95A0E461-9F45-4061-BC4B-3B465DD9E1FD
,[ThaliCore] Session.session(_:peer:didChange:) peer:95A0E461-9F45-4061-BC4B-3B465DD9E1FD state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:95A0E461-9F45-4061-BC4B-3B465DD9E1FD
[ThaliCore] Session.startOutputStream(with:) peer:95A0E461-9F45-4061-BC4B-3B465DD9E1FD
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2,4 [3, 9, 12, 23, 24]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:25F94381-7A5C-4103-B229-CF501806E9D4
,[ThaliCore] Session.session(_:peer:didChange:) peer:25F94381-7A5C-4103-B229-CF501806E9D4 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:45ABA631-FD53-4044-BA01-13FE72BF09A5:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:25F94381-7A5C-4103-B229-CF501806E9D4
[ThaliCore] Session.startOutputStream(with:) peer:25F94381-7A5C-4103-B229-CF501806E9D4
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2,5 [3, 9, 12, 23, 24, 25]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:45ABA631-FD53-4044-BA01-13FE72BF09A5:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "45ABA631-FD53-4044-BA01-13FE72BF09A5", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:53425
,2017-07-18 09:54:43 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"2","error":null,"portNumber":53425}'
,[ThaliCore] BrowserManager.disconnect peer:A2FF3948-3AB1-4483-B3E0-379DCE76812F
,2017-07-18 09:54:43 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for A2FF3948-3AB1-4483-B3E0-379DCE76812F (syncValue: 3)'
,2017-07-18 09:54:43 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A2FF3948-3AB1-4483-B3E0-379DCE76812F", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A2FF3948-3AB1-4483-B3E0-379DCE76812F", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:A2FF3948-3AB1-4483-B3E0-379DCE76812F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:45ABA631-FD53-4044-BA01-13FE72BF09A5:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:45ABA631-FD53-4044-BA01-13FE72BF09A5:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:26 [3, 9, 12, 23, 24, 25, 26]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-18 09:54:43 - DEBUG testUtils: 'Got response data'
,2017-07-18 09:54:43 - DEBUG testUtils: 'Got end'
,ok 574 received all uuids
,# teardown
,[ThaliCore] Session.session(_:peer:didChange:) peer:A2FF3948-3AB1-4483-B3E0-379DCE76812F:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:A2,FF3948-3AB1-4483-B3E0-379DCE76812F:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "A2FF3948-3AB1-4483-B3E0-379DCE76812F", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A,2FF3948-3AB1-4483-B3E0-379DCE76812F", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A2FF3948-3AB1-4483-B3E0-379DCE76812F", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:A2FF3948-3AB1-4483-B3E0-379DCE76812F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:A2FF3948-3AB1-4483-B3E0-379DCE76812F:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:A2FF3948-3AB1-4483-B3E0-379DCE76812F:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:A2,FF3948-3AB1-4483-B3E0-379DCE76812F:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "A2FF3948-3AB1-4483-B3E0-379DCE76812F", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A,2FF3948-3AB1-4483-B3E0-379DCE76812F", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A2FF3948-3AB1-4483-B3E0-379DCE76812F", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:A2FF3948-3AB1-4483-B3E0-379DCE76812F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:A2FF3948-3AB1-4483-B3E0-379DCE76812F:0
[ThaliCore] BrowserRelay.deinit
,2017-07-18 09:54:45 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"104BF86E-803C-46C8-8A9E-8387091CD103","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-18, 09:54:45 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"45ABA631-FD53-4044-BA01-13FE72BF09A5","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-18 09:54:45 ,- DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"A2FF3948-3AB1-4483-B3E0-379DCE76812F","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:23
[ThaliCore] VirtualSocket.closeStreams() vsID:23
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:23
[Th,aliCore] VirtualSocket.deinit vsID:23 [3, 9, 12, 24, 25, 26]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.d,idSocketDisconnectHandler
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:26
[ThaliCore] VirtualSocket.closeStreams() vsID:26
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket ,exited RunLoop vsID:26
[ThaliCore] VirtualSocket.deinit vsID:26 [3, 9, 12, 24, 25]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[T,haliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] Session.session(_:peer:didChange:) peer:A2FF3948-3AB1-4483-B3E0-379DCE76812F:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:A2,FF3948-3AB1-4483-B3E0-379DCE76812F:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "A2FF3948-3AB1-4483-B3E0-379DCE76812F", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A,2FF3948-3AB1-4483-B3E0-379DCE76812F", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A2FF3948-3AB1-4483-B3E0-379DCE76812F", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:A2FF3948-3AB1-4483-B3E0-379DCE76812F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:A2FF3948-3AB1-4483-B3E0-379DCE76812F:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:A2FF3948-3AB1-4483-B3E0-379DCE76812F:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:A2,FF3948-3AB1-4483-B3E0-379DCE76812F:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "A2FF3948-3AB1-4483-B3E0-379DCE76812F", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:A2FF3948,-3AB1-4483-B3E0-379DCE76812F error: max retries exceeded
2017-07-18 09:54:47 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"3","error":"Connection could not be established","portNumber":null}'
2017-07-18 09:54:47 - DEBUG thaliMobi,leNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"A2FF3948-3AB1-4483-B3E0-379DCE76812F","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-18 09:54:47 - DEBUG thaliMobileNativeWrapper: 'Received peer avail,ability changed event with {"peerIdentifier":"A2FF3948-3AB1-4483-B3E0-379DCE76812F","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
2017-07-18 09:54:47 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event wi,th {"peerIdentifier":"A2FF3948-3AB1-4483-B3E0-379DCE76812F","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-18 09:54:47 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"A2FF3948-3AB1-44,83-B3E0-379DCE76812F","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:1329D84C-3DE0-4ED2-9740-36D47DF4B8A6
2017-07-18 09:54:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-07-18 09:54:47 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,}})'
2017-07-18 09:54:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-18 09:54:47 - DEBUG thaliMobileN,ativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:54:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-18 09:54:47 - DEBUG makeInto,CloseAllServer: 'closeAll called on server'
,[ThaliCore] Session.deinit peer:A2FF3948-3AB1-4483-B3E0-379DCE76812F:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:25
[ThaliCore] VirtualSocket.closeStreams() vsID:25
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:25
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescriptio,n=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] VirtualSocket.deinit vsID:25 [3, 9, 12, 24]
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:24
[ThaliCore] VirtualSocket.closeStrea,ms() vsID:24
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:24
[ThaliCore] VirtualSocket.deinit vsID:24 [3, 9, 12]
,2017-07-18 09:54:47 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"A2FF3948-3AB1-4483-B3E0-379DCE76812F","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-18 09:54:47 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"A2FF3948-3AB1-4483-B3E0-379DCE76812F","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-18 09:54:47 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"A2FF3948-3AB1-4483-B3E0-379DCE76812F","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,[ThaliCore] BrowserManager.disconnect peer:A2FF3948-3AB1-4483-B3E0-379DCE76812F
,2017-07-18 09:54:47 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"A2FF3948-3AB1-4483-B3E0-379DCE76812F","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,[ThaliCore] BrowserManager.disconnect peer:A2FF3948-3AB1-4483-B3E0-379DCE76812F
,ok 575 error should be null
,ok 576 error should be null
,# setup
,ok 577 ThaliMobile should be stopped
,# test for data corruption
,2017-07-18 09:54:47 - DEBUG CoordinatedClient: 'test was skipped, name: 'test for data corruption''
,# teardown
,ok 578 error should be null
,ok 579 error should be null
,# setup
,# #testThaliPeerAction - test getters
,ok 580 getPeerIdentifier
,ok 581 getConnectionType
,ok 582 getActionType
,ok 583 getActionState
,ok 584 getPskIdentity
,ok 585 getPskKey
,# teardown
,# setup
,# #testThaliPeerAction - start and kill
,ok 586 initial state
ok 587 after start
2017-07-18 09:54:49 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 588 after kill
# teardown
,# setup
,# #testThaliPeerAction - double start
,ok 589 should be equal
,# teardown
,# setup
,# #testThaliPeerAction - start after kill
,2017-07-18 09:54:49 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 590 clean kill
,ok 591 should be equal
,# teardown
,# setup
,# #testThaliPeerAction - make sure ids are unique
,ok 592 should not be equal
,# teardown
,# setup
,# #testThaliPeerAction - check that forever agent can be destroyed
,ok 593 forever agent should have it's own destroy method
,ok 594 agent's destroy should be called
,ok 595 agent's destroy should not be called again
,ok 596 agent is destroyed
,# teardown
,# setup
,# Test PeerDictionary basic functionality
,ok 597 Entry counter must be 1
,ok 598 Entry exists
,ok 599 Size must be 1
,ok 600 Entry counter must be 2
,ok 601 Entry exists
,ok 602 Size must be 2
,ok 603 Entry counter must be 1
,ok 604 Entry exists
,ok 605 Size must be 3
,ok 606 Entry counter must be 2
,ok 607 Entry exists
,ok 608 Size must be 4
,ok 609 Entry 1_1 should not be found
,ok 610 Entry 1_1 does not exist
,ok 611 Size must be 3
,ok 612 Entry 1_2 should not be found
,ok 613 Entry 1_2 does not exist
,ok 614 Size must be 2
,ok 615 should be equal
,ok 616 Entry 2_1 should not be found
,ok 617 Entry 2_2 should not be found
,ok 618 Entry 2_1 does not exist
,ok 619 Entry 2_2 does not exist
,ok 620 Size must be 0
,# teardown
,# setup
,# Test PeerDictionary with multiple entries.
,ok 621 Size must be100
,ok 622 Entries between 20 and MAXSIZE + 20 should exist
,ok 623 WAITING state entry should not be removed
,# teardown
,# setup
,# RESOLVED entries are removed before WAITING state entry.
,ok 624 Entries between 6 and MAXSIZE + 4 should exist
,ok 625 Size should be MAXSIZE
,ok 626 Size should be MAXSIZE+6
,# teardown
,# setup
,# WAITING entries are removed before CONTROLLED_BY_POOL state entry.
,ok 627 WAITING state entry should not be removed
,ok 628 Waiting entries between 6 and MAXSIZE + 4 should exist
,ok 629 Size should be MAXSIZE
,ok 630 entryCounter should be MAXSIZE+6
,# teardown
,# setup
,# When CONTROLLED_BY_POOL entry is removed and kill is called.
,ok 631 Kill should be called once
,ok 632 Size should be MAXSIZE
,# teardown
,# setup
,# #ThaliPeerPoolDefault - single action
,ok 633 is an agent
ok 634 enqueue is fine
ok 635 Everything should be off the queue
,# teardown
,# setup
,# #ThaliPeerPoolDefault - multiple actions
,ok 636 is an agent
ok 637 first enqueue is fine
ok 638 is an agent
ok 639 second enqueue is fine
ok 640 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
ok 641 Queue is empty
,# teardown
,# setup
,# #ThaliPeerPoolDefault - PSK Pool works
,ok 642 is an agent
,ok 643 good enqueue
,ok 644 Identity should match
,2017-07-18 09:54:54 - DEBUG testUtils: 'Got response data'
,2017-07-18 09:54:54 - DEBUG testUtils: 'Got end'
,ok 645 Got expected response
,ok 646 Got psk call back
,# teardown
,2017-07-18 09:54:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #ThaliPeerPoolDefault - stop
,ok 647 is an agent
,ok 648 enqueue worked
,ok 649 is an agent
ok 650 enqueue 2 worked
,ok 651 enqueue is not available when stopped
,ok 652 start action is killed
,ok 653 killed action is still killed
,ok 654 enqueued action when stopped is killed
,ok 655 inQueue is empty
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure that start verifies queue length
,ok 656 good start
,ok 657 good enqueue
,ok 658 queue is not empty
,# teardown
,# setup
,# #ThaliPeerPoolInterface - bad enqueues
,ok 659 null arg
ok 660 wrong arg type
ok 661 wrong arg type
,# teardown
,# setup
,# #ThaliPeerPoolInterface - do not allow same object type
,ok 662 good enqueue
,ok 663 already enqueued
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure we catch kill and dequeue
,ok 664 good enqueue
ok 665 2nd good enqueue
ok 666 we are in the pool
ok 667 We are out of the pool
ok 668 Action was killed
ok 669 The original kill was called too
ok 670 second item is still in queue
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent
,ok 671 good enqueue
,ok 672 first kill
,ok 673 second NOOP kill
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure that stop removes all actions
,ok 674 1st good enqueue
ok 675 2nd good enqueue
ok 676 1st action is in the pool
ok 677 2nd action is in the pool
ok 678 1st action is out of the pool
ok 679 2st action is out of the pool
ok 680 pool is empty
,# teardown
,# setup
,# We reject unrecognized connection type
,2017-07-18 09:54:57 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 681 Got right error
,ok 682 Start should not be called
,ok 683 Kill should have been called at least once
,# teardown
,# setup
,# We reject unrecognized action type
,2017-07-18 09:54:57 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-18 09:54:57 - ERROR thaliPeerPoolOneAtATime: 'Got unsupported action type: blah'
,ok 684 Got right error
,ok 685 Start should not be called
,ok 686 Kill should have been called at least once
,# teardown
,# setup
,# One action on bluetooth
,2017-07-18 09:54:58 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 687 Got null
,2017-07-18 09:54:58 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerID'
,ok 688 is an agent
,2017-07-18 09:54:58 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerID'
,ok 689 Got killed at least once
,# teardown
,# setup
,# Two notification actions
,2017-07-18 09:54:58 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 690 Got Null
,ok 691 Got another null
,2017-07-18 09:54:58 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId1'
,ok 692 is an agent
,2017-07-18 09:54:58 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId1'
,2017-07-18 09:54:58 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
,ok 693 is an agent
,2017-07-18 09:54:58 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
,ok 694 Action 1 killed at least once
,ok 695 Action 1 went first
,ok 696 Action 2 killed at least once
,# teardown
,# setup
,# replicateThroughProblems
,2017-07-18 09:54:59 - DEBUG thaliPeerPoolOneAtATime: 'Action Started success'
,2017-07-18 09:54:59 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - success'
,2017-07-18 09:54:59 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,ok 697 should have gotten null
,2017-07-18 09:54:59 - DEBUG thaliPeerPoolOneAtATime: 'Action Started noActivityTimeOut'
,2017-07-18 09:54:59 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: No activity time out - noActivityTimeOut'
,ok 698 Should have stopped nicely
,2017-07-18 09:54:59 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButNotAvailable'
,2017-07-18 09:54:59 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButNotAvailable'
,ok 699 Still looking for null
,2017-07-18 09:54:59 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButAvailable'
,2017-07-18 09:54:59 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButAvailable'
,2017-07-18 09:54:59 - DEBUG thaliPeerPoolOneAtATime: 'Replication action failed badly so we are going to retry'
,2017-07-18 09:54:59 - DEBUG thaliPeerPoolOneAtATime: 'Action Started clone!'
,2017-07-18 09:54:59 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - clone!'
,2017-07-18 09:54:59 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,ok 700 Yup, another null
,ok 701 We cloned!
,# teardown
,# setup
,# Replication goes first
,2017-07-18 09:54:59 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 702 Null 1
,ok 703 (unnamed assert)
,2017-07-18 09:54:59 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,ok 704 is an agent
,ok 705 Null 3
,ok 706 Replication not yet called
,ok 707 Notification 2 not yet called
,2017-07-18 09:54:59 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,2017-07-18 09:54:59 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
,ok 708 is an agent
,ok 709 Notification went first
,ok 710 Notification 2 not called yet
,2017-07-18 09:54:59 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
,2017-07-18 09:54:59 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,2017-07-18 09:54:59 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,ok 711 is an agent
,ok 712 Notification finished
,ok 713 Replication finished
,2017-07-18 09:54:59 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,# teardown
,# setup
,# wifi allows many parallel non-replication actions
,2017-07-18 09:55:00 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
2017-07-18 09:55:00 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
ok 714 is an agent
ok 715 First does not throw
,2017-07-18 09:55:00 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
ok 716 is an agent
ok 717 Second does not throw
2017-07-18 09:55:00 - DEBUG thaliPeerPoolOneAtATime: 'action, returned successfully from start - Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
truetruefalsetrue
,2017-07-18 09:55:00 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
,truetruetruetrue
,# teardown
,# setup
,# wifi allows no more than 2 simultaneous replication actions for same peerID
,2017-07-18 09:55:01 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-18 09:55:01 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 595, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,ok 718 is an agent
,ok 719 first ok
,2017-07-18 09:55:01 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 596, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,ok 720 is an agent
,ok 721 second ok
,ok 722 third ok
,2017-07-18 09:55:01 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 595, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,2017-07-18 09:55:01 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 596, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,2017-07-18 09:55:01 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,2017-07-18 09:55:01 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,# teardown
,# setup
,# Client to server request coordinated
,2017-07-18 09:55:01 - DEBUG CoordinatedClient: 'test was skipped, name: 'Client to server request coordinated''
,# teardown
,2017-07-18 09:55:01 - INFO testThaliNotification: 'Participants:0 Peers Replied to us:0 Peers requested to:0'
,# setup
,# Test BEACONS_RETRIEVED_AND_PARSED locally
,ok 723 peerIdentifier should match
,ok 724 generation should match
,ok 725 Response should be BEACONS_RETRIEVED_AND_PARSED
,ok 726 good beacon
,ok 727 good preAmble
,ok 728 public keys match!
,ok 729 must return null after successful call
,ok 730 Once start returns the action should be in KILLED state
,# teardown
,2017-07-18 09:55:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test HTTP_BAD_RESPONSE locally
,ok 731 Response should be HTTP_BAD_RESPONSE
,ok 732 must return null after successful call
,# teardown
,2017-07-18 09:55:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test NETWORK_PROBLEM locally
,ok 733 Response should be NETWORK_PROBLEM
,ok 734 reject reason should be: Could not establish TCP connection
,# teardown
,2017-07-18 09:55:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Action fails when getPeerHostInfo fails
,ok 735 Resolution should be BAD_PEER
,ok 736 correct error message
,# teardown
,2017-07-18 09:55:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the start two times
,ok 737 Call start once
,ok 738 Response should be BEACONS_RETRIEVED_AND_PARSED
,ok 739 must return null after successful call.
,# teardown
,2017-07-18 09:55:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill before calling the start
,ok 740 Should be Killed
,ok 741 Start after killed
,# teardown
,2017-07-18 09:55:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill immediately after the start
,ok 742 Should be KILLED
,ok 743 must return null after successful kill
,# teardown
,2017-07-18 09:55:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill while waiting a response from the server
,ok 744 Should be KILLED
ok 745 must return null after successful kill
,# teardown
,2017-07-18 09:55:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test to exceed the max content size locally
,ok 746 HTTP_BAD_RESPONSE should be response when content size is exceeded
,ok 747 must return null after successful call
,# teardown
,2017-07-18 09:55:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Close the server socket while the client is waiting a response from the server. Local test.
,2017-07-18 09:55:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 748 Should be NETWORK_PROBLEM caused closing server socket
,ok 749 Should be Could not establish TCP connection
,# teardown
,# setup
,# Close the client socket while the client is waiting a response from the server. Local test.
,ok 750 Should be NETWORK_PROBLEM caused closing client socket
ok 751 Should be Could not establish TCP connection
,# teardown
,2017-07-18 09:55:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #generatePreambleAndBeacons bad args
,ok 752 publicKeysToNotify cannot be null
ok 753 ecdh for local device cannot be null
,ok 754 milliseconds cannot be less than 0
,ok 755 milliseconds cannot be 0
,ok 756 milliseconds cannot be greater than one_day
,# teardown
,# setup
,# #generatePreambleAndBeacons empty keys to notify
,ok 757 should be equal
,# teardown
,# setup
,# #generatePreambleAndBeacons multiple keys to notify
,ok 758 should be equal
,ok 759 should be equal
,ok 760 (unnamed assert)
,ok 761 should be equal
,# teardown
,# setup
,# #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
,ok 762 should throw
,# teardown
,# setup
,# #parseBeacons invalid expiration in beaconStreamWithPreAmble
,ok 763 Preamble expiration must be a 64 bit integer
,# teardown
,# setup
,# #parseBeacons expiration out of range lower
,ok 764 Expiration out of range
,# teardown
,# setup
,# #parseBeacons expiration out of range lower
,ok 765 Expiration out of range
,# teardown
,# setup
,# #parseBeacons no beacons returns null
,ok 766 should be equal
,# teardown
,# setup
,# #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
,ok 767 Malformed encrypted beacon key ID
,# teardown
,# setup
,# #parseBeacons addressBookCallback fails decrypt
,ok 768 should be equal
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns no matches
,ok 769 should be equal
,ok 770 should be equal
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns spurious match
,ok 771 should be equal
ok 772 should be equal
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns public key
,ok 773 right number of calls to address book
,ok 774 good preAmble
,ok 775 good unencryptedKeyId
,ok 776 good beacon
,# teardown
,# setup
,# validate generatePskIdentityField
,ok 777 decoded buffers match
,# teardown
,# setup
,# validate generatePskSecret
,ok 778 secrets match
,# teardown
,# setup
,# validate generatePskSecrets
,ok 779 Matching numbers
,ok 780 We have an entry!
,ok 781 keys match
,ok 782 secrets match
,ok 783 We have an entry!
ok 784 keys match
,ok 785 secrets match
,ok 786 We have an entry!
,ok 787 keys match
,ok 788 secrets match
,# teardown
,# setup
,# validate generateBeaconStreamAndSecrets
,ok 789 Streams have same length
,ok 790 matching size
,ok 791 keys match
,ok 792 secrets match
,# teardown
,# setup
,# Add two Peers.
,ok 793 should be equal
,ok 794 peerDictionalty contains 2 peers
,ok 795 bluetooth peer's notification has correct connection type
,ok 796 tcp peer's notification has correct connection type
,2017-07-18 09:55:20 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,2017-07-18 09:55:20 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-07-18 09:55:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# TCP_NATIVE peer loses DNS
,ok 797 notification peer dictionary contains exactly 1 peer
2017-07-18 09:55:21 - WARN thaliNotificationClient: 'peer is not available'
ok 798 notification peer dictionary does not contain any peers
,2017-07-18 09:55:21 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-07-18 09:55:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Received beacons with no values for us
,ok 799 entry exists
,ok 800 entry is resolved
,# teardown
,2017-07-18 09:55:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Notification action killed with a superseded
,ok 801 Action should be KILLED
,ok 802 Peer state should be RESOLVED
,# teardown
,2017-07-18 09:55:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally
,ok 803 hostAddress must match
,ok 804 portNumber must match
,ok 805 suggestedTCPTimeout must match
,ok 806 connectionType must match
,ok 807 peerIDs must match
,# teardown
,2017-07-18 09:55:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Emits error event when peerPool.enqueue throws
,ok 808 Correct error
,# teardown
,2017-07-18 09:55:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally using ThaliPeerPoolDefault
,ok 809 hostAddress must match
,ok 810 portNumber must match
,ok 811 suggestedTCPTimeout must match
,ok 812 connectionType must match
,ok 813 peerIds must match
,# teardown
,2017-07-18 09:55:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Action fails because of a bad hostname.
,2017-07-18 09:55:24 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 814 action should be resolved with NETWORK_PROBLEM error
,2017-07-18 09:55:24 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 815 action should be resolved with NETWORK_PROBLEM error
,2017-07-18 09:55:25 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 816 action should be resolved with NETWORK_PROBLEM error
,2017-07-18 09:55:25 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 817 action should be resolved with NETWORK_PROBLEM error
ok 818 correct number of requests
ok 819 correct number of failures
ok 820 correct final peer state
,# teardown
,2017-07-18 09:55:25 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# hostaddress is removed when the action is running. 
,2017-07-18 09:55:28 - WARN thaliNotificationClient: 'peer is not available'
2017-07-18 09:55:28 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 821 peerDictionary should become empty
,# teardown
,2017-07-18 09:55:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notificationClient does not retry action with BAD_PEER resolution
,2017-07-18 09:55:28 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 822 failed with expected error
ok 823 peer state should be RESOLVED
,# teardown
,2017-07-18 09:55:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notification client correctly handles peer availability changes of the same peer
,2017-07-18 09:55:29 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 824 First action failed
,ok 825 second action killed
# teardown
,2017-07-18 09:55:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Client to server request locally
,ok 826 secrets are equal
ok 827 Public key matches with the server key
,ok 828 hostAddress must match
,ok 829 portNumber must match
,ok 830 suggestedTCPTimeout must match
,ok 831 connectionType must match
,# teardown
,2017-07-18 09:55:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache clean and expiration
,ok 832 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE
,ok 833 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE-1
,ok 834 All entries should be expired after 1 second
# teardown
,2017-07-18 09:55:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache getSecret and getPublic
,ok 835 All keys need to be available in the cache
,ok 836 All entries should be expired after 1 second
# teardown
,2017-07-18 09:55:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache multiple entries
,ok 837 Size of the cache should be 2
ok 838 Cache doesn't contain dictionary1
,ok 839 Size of the cache should be 1
ok 840 Cache doesn't contain beaconStreamAndSecretDictionary2
# teardown
,2017-07-18 09:55:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Start and stop ThaliNotificationServer
,ok 841 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
,ok 842 ThaliMobile.StopAdvertisingAndListeningshould be called once
,# teardown
,2017-07-18 09:55:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass an empty array to ThaliNotificationServer.start
,ok 843 StartUpdateAdvertisingAndListening should not be called
,ok 844 ThaliMobile.StopAdvertisingAndListening should be called once
,ok 845 no error
,ok 846 should be 204
,# teardown
,2017-07-18 09:55:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass a string to ThaliNotificationServer.start
,ok 847 StartUpdateAdvertisingAndListening should not be called
,# teardown
,2017-07-18 09:55:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass an empty parameter to ThaliNotificationServer.start
,ok 848 StartUpdateAdvertisingAndListening should not be called
,# teardown
,2017-07-18 09:55:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeacons
,ok 849 no error
,ok 850 should be 200
,ok 851 should be equal
,ok 852 should be equal
,ok 853 (unnamed assert)
,ok 854 no error
ok 855 should be 204
,# teardown
,2017-07-18 09:55:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeacons (no keys)
,ok 856 error should be null
,ok 857 should be 204
,# teardown
,2017-07-18 09:55:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeaconsbefore calling start
,ok 858 should be 404
,# teardown
,2017-07-18 09:55:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure peerDictionaryKey is reasonable
,ok 859 equal keys
ok 860 not equal connection type
ok 861 same connection type, different buffer
,# teardown
,# setup
,# Make sure start works
,2017-07-18 09:55:41 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 862 First start and on called correctly
,# teardown
,# setup
,# Make sure stop works
,ok 863 second cleared dictionary
,2017-07-18 09:55:42 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,ok 864 First start and on called correctly
,ok 865 First stop and removeListener called correctly
,ok 866 first action kill called
,ok 867 second action kill called
,ok 868 first cleared dictionary
,ok 869 first cleared pool
,ok 870 second cleared dictionary
,ok 871 second cleared pool
,# teardown
,# setup
,# Emits error event when peerPool.enqueue throws
,ok 872 Correct error
,# teardown
,# setup
,# Simple peer event
,2017-07-18 09:55:42 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,ok 873 listener has been set
,ok 874 peer dictionary has expected number of entries
,ok 875 Dictionary and pool have same action
,ok 876 ads match
,ok 877 PouchDB matches
,ok 878 DB Names match
,ok 879 public keys match
,ok 880 peer dictionary has expected number of entries
,ok 881 Dictionary and pool have same action
,ok 882 ads match
,ok 883 PouchDB matches
,ok 884 DB Names match
,ok 885 public keys match
,2017-07-18 09:55:42 - DEBUG thaliReplicationPeerAction: 'We called _complete with  and it caused us to complete'
,ok 886 start called once
,ok 887 One entry left
,ok 888 Dictionary and pool have same action
,ok 889 Start never called
,ok 890 Kill called once
,ok 891 no entries left
,ok 892 Third action is dead
,ok 893 peer dictionary has expected number of entries
,ok 894 Dictionary and pool have same action
,ok 895 ads match
,ok 896 PouchDB matches
,ok 897 DB Names match
,ok 898 public keys match
,# teardown
,# setup
,# Coordinated pull replication from notification test
,2017-07-18 09:55:43 - DEBUG CoordinatedClient: 'test was skipped, name: 'Coordinated pull replication from notification test''
,# teardown
,# setup
,# Server is not there
,2017-07-18 09:55:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-18 09:55:43 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 connect ECONNREFUSED'
,2017-07-18 09:55:43 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: connect ECONNREFUSED  and it caused us to complete'
,ok 899 right error
,# teardown
,2017-07-18 09:55:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server accepts & closes connection
,2017-07-18 09:55:44 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 socket hang up'
,2017-07-18 09:55:44 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: socket hang up  and it caused us to complete'
,ok 900 right error
,# teardown
,2017-07-18 09:55:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 500
,2017-07-18 09:55:45 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 changes rejected'
,2017-07-18 09:55:45 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 901 Got error as expected
,# teardown
,2017-07-18 09:55:45 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 401
,2017-07-18 09:55:45 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  401 changes rejected'
,2017-07-18 09:55:45 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 902 Got error as expected
,# teardown
,2017-07-18 09:55:46 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 403
,2017-07-18 09:55:46 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  403 changes rejected'
,2017-07-18 09:55:46 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 903 Got error as expected
,# teardown
,2017-07-18 09:55:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure docs replicate with remote db with same name as local db
,2017-07-18 09:55:49 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-18 09:55:49 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-18 09:55:52 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
,ok 904 should be equal
,ok 905 All tests passed!
,# teardown
,2017-07-18 09:55:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure docs replicate with remote db with different name than local db
,2017-07-18 09:55:54 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-18 09:55:55 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-18 09:55:57 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
,ok 906 should be equal
,ok 907 All tests passed!
,# teardown
,2017-07-18 09:55:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Do nothing and make sure we time out
,2017-07-18 09:55:59 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-18 09:56:00 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2017-07-18 09:56:00 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and s,o we ignored it'
ok 908 action should be killed
ok 909 Error should be timed out
,ok 910 No doc found
,# teardown
,2017-07-18 09:56:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Do something and make sure we time out
,2017-07-18 09:56:02 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-18 09:56:03 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,ok 911 should be equal
,2017-07-18 09:56:05 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2017-07-18 09:56:05 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and s,o we ignored it'
,ok 912 action should be killed
ok 913 Error should be timed out
,# teardown
,2017-07-18 09:56:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Start replicating and then catch error when server goes
,ok 914 socket hung up
,# teardown
,2017-07-18 09:56:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure clone works
,ok 915 same getPeerAdvertisesDataForUs
ok 916 Same pouchdB
ok 917 same localDbName
ok 918 Same public key
,# teardown
,# setup
,# Coordinated replication action test - each device has the same local db name
,2017-07-18 09:56:08 - DEBUG CoordinatedClient: 'test was skipped, name: 'Coordinated replication action test - each device has the same local db name''
,# teardown
,# setup
,# Coordinated replication action test - each device has different local db name
,2017-07-18 09:56:08 - DEBUG thaliMobileNativeWrapper: 'listening 53561'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:57631C5C-1285-46AE-AC33-3020913FBEA7
,[ThaliCore] Browser.startListening
,2017-07-18 09:56:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "96EDEA21-4608-4173-8B8B-32BA5F4A9A9C", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:96EDEA21-4608-4173-8B8B-32BA5F4A9A9C
,2017-07-18 09:56:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5998E650-08FC-45D0-A270-46ABE636425B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5998E650-08FC-45D0-A270-46ABE636425B", generation: 0)
2017-07-18 09:56:09 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"5998E650-08FC-45D0-A270-46ABE636425B","generation":0}]'
2017-07-18 09:56:09 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"5998E650-08FC-45D0-A270-46ABE636425B","generation":0}'
,2017-07-18 09:56:09 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"5998E650-08FC-45D0-A270-46ABE636425B","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-18 09:56:09 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5998E650-08FC-45D0-A270-46ABE636425B","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-18 09:56:09 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 5998E650-08FC-45D0-A270-46ABE636425B (syncValue: 4)'
,2017-07-18 09:56:09 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5998E650-08FC-45D0-A270-46ABE636425B", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5998E650-08FC-45D0-A270-46ABE636425B", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7CF7E90F-A14F-40A1-994C-F57FF2477BE4:0
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0
[ThaliCore] BrowserManager.foun,dPeerHandler peer:Peer(uuid: "7CF7E90F-A14F-40A1-994C-F57FF2477BE4", generation: 0)
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-18 09:56:09 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"7CF7E90F-A14F-40A1-994C-F57FF2477BE4","generation":0}]'
,2017-07-18 09:56:09 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"7CF7E90F-A14F-40A1-994C-F57FF2477BE4","generation":0}'
,2017-07-18 09:56:09 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"7CF7E90F-A14F-40A1-994C-F57FF2477BE4","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-18 09:56:09 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7CF7E90F-A14F-40A1-994C-F57FF2477BE4","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:96EDEA21-4608-4173-8B8B-32BA5F4A9A9C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "96EDEA21-4608-4173-8B8B-32BA5F4A9A9C", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:DEEE9265-B86D-4480-BD12-C8FCCBE5FDBA
[ThaliCore] Advertiser: session connected Peer(uuid: "96EDEA21-4608-4173-8B8B-32BA5F4A9A9C", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:DEEE9265-B86D-4480-BD12-C8FCCBE5FDBA state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:0C13EC7D-58C9-4EE8-AE56-E60174103537
[ThaliCore] Advertiser: session connected Peer(uuid: "96EDEA21-4608-4173-8B8B-32BA5F4A9A9C", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:0C13EC7D-58C9-4EE8-AE56-E60174103537 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "5998E650-08FC-45D0-A270-46ABE636425B", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:53564
,2017-07-18 09:56:12 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"4","error":null,"portNumber":53564}'
,2017-07-18 09:56:12 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 5998E650-08FC-45D0-A270-46ABE636425B (syncValue: 5)'
2017-07-18 09:56:12 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPee,r(_:syncValue:retryCount:completion:) Peer(uuid: "5998E650-08FC-45D0-A270-46ABE636425B", generation: 0) found active relay
,2017-07-18 09:56:12 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"5","error":null,"portNumber":53564}'
,2017-07-18 09:56:12 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 5998E650-08FC-45D0-A270-46ABE636425B (syncValue: 6)'
,2017-07-18 09:56:12 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5998E650-08FC-45D0-A270-46ABE636425B", generation: 0) found active relay
,2017-07-18 09:56:12 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"6","error":null,"portNumber":53564}'
,2017-07-18 09:56:12 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 5998E650-08FC-45D0-A270-46ABE636425B (syncValue: 7)'
,2017-07-18 09:56:12 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5998E650-08FC-45D0-A270-46ABE636425B", generation: 0) found active relay
2017-07-18 09:56:12 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"7","error":null,"portNumber":53564}'
,2017-07-18 09:56:12 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 7CF7E90F-A14F-40A1-994C-F57FF2477BE4 (syncValue: 8)'
,2017-07-18 09:56:12 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7CF7E90F-A14F-40A1-994C-F57FF2477BE4", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7CF7E90F-A14F-40A1-994C-F57FF2477BE4", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:7CF7E90F-A14F-40A1-994C-F57FF2477BE4:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[Th,aliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:27 [3, 9, 12, 27]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:28 [3, 9, 12, 27, 28]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:29 [3, 9, 12, 27, 28, 29]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:30 [3, 9, 12, 27, 28, 29, 30]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:27
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:27
,[ThaliCore] VirtualSocket.deinit vsID:27 [3, 9, 12, 28, 29, 30]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:28
,[ThaliCore] VirtualSocket exited RunLoop vsID:28
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:28 [3, 9, 12, 29, 30]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
,[ThaliCore] VirtualSocket.closeStreams() vsID:30
,[ThaliCore] VirtualSocket exited RunLoop vsID:30
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:30 [3, 9, 12, 29]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:7CF7E90F-A14F-40A1-994C-F57FF2477BE4:0 state: notConnected -> connecting
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
,[ThaliCore] VirtualSocket.closeStreams() vsID:29
,[ThaliCore] VirtualSocket exited RunLoop vsID:29
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:29 [3, 9, 12]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:31 [3, 9, 12, 31]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-18 09:56:13 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:32 [3, 9, 12, 31, 32]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:33 [3, 9, 12, 31, 32, 33]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler,
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:34 [3, 9, 12, 31, 32, 33, 34]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:35 [3, 9, 12, 31, 32, 33, 34, 35]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:34
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:34
,[ThaliCore] VirtualSocket.deinit vsID:34 [3, 9, 12, 31, 32, 33, 35]
,2017-07-18 09:56:14 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:DEEE9265-B86D-4480-BD12-C8FCCBE5FDBA
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:0C13EC7D-58C9-4EE8-AE56-E60174103537
,[ThaliCore] Session.session(_:peer:didChange:) peer:0C13EC7D-58C9-4EE8-AE56-E60174103537 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:7CF7E90F-A14F-40A1-994C-F57FF2477BE4:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0C13EC7D-58C9-4EE8-AE56-E60174103537
[ThaliCore] Session.startOutputStream(with:) peer:0C13EC7D-58C9-4EE8-AE56-E60174103537
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3,6 [3, 9, 12, 31, 32, 33, 35, 36]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0C13EC7D-58C9-4EE8-AE56-E60174103537
[ThaliCore] Session.startOutputStream(with:) peer:0C13EC7D-58C9-4EE8-AE56-E60174103537
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3,7 [3, 9, 12, 31, 32, 33, 35, 36, 37]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0C13EC7D-58C9-4EE8-AE56-E60174103537
[ThaliCore] Session.startOutputStream(with:) peer:0C13EC7D-58C9-4EE8-AE56-E60174103537
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:38 [3, 9, 12, 31, 32, 33, 35, 36, 37, 38]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0C13EC7D-58C9-4EE8-AE56-E60174103537
[ThaliCore] Session.startOutputStream(with:) peer:0C13EC7D-58C9-4EE8-AE56-E60174103537
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:39 [3, 9, 12, 31, 32, 33, 35, 36, 37, 38, 39]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] Session.session(_:peer:didChange:) peer:7CF7E90F-A14F-40A1-994C-F57FF2477BE4:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "7CF7E90F-A14F-40A1-994C-F57FF2477BE4", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:53579
,2017-07-18 09:56:15 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"8","error":null,"portNumber":53579}'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:38
[ThaliCore] VirtualSocket.closeStreams() vsID:38
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:38
,[ThaliCore] VirtualSocket.deinit vsID:38 [3, 9, 12, 31, 32, 33, 35, 36, 37, 39]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-18 09:56:15 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 7CF7E90F-A14F-40A1-994C-F57FF2477BE4 (syncValue: 9)'
,2017-07-18 09:56:15 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7CF7E90F-A14F-40A1-994C-F57FF2477BE4", generation: 0) found active relay
,2017-07-18 09:56:15 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"9","error":null,"portNumber":53579}'
,2017-07-18 09:56:15 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 7CF7E90F-A14F-40A1-994C-F57FF2477BE4 (syncValue: 10)'
,2017-07-18 09:56:15 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7CF7E90F-A14F-40A1-994C-F57FF2477BE4", generation: 0) found active relay
,2017-07-18 09:56:15 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"10","error":null,"portNumber":53579}'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:36
[ThaliCore] VirtualSocket.closeStreams() vsID:36
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:36
,[ThaliCore] VirtualSocket.deinit vsID:36 [3, 9, 12, 31, 32, 33, 35, 37, 39]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-18 09:56:15 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 7CF7E90F-A14F-40A1-994C-F57FF2477BE4 (syncValue: 11)'
,2017-07-18 09:56:15 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7CF7E90F-A14F-40A1-994C-F57FF2477BE4", generation: 0) found active relay
,2017-07-18 09:56:15 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"11","error":null,"portNumber":53579}'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:37
[ThaliCore] VirtualSocket.closeStreams() vsID:37
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:37
,[ThaliCore] VirtualSocket.deinit vsID:37 [3, 9, 12, 31, 32, 33, 35, 39]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:7CF7E90F-A14F-40A1-994C-F57FF2477BE4:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:7CF7E90F-A14F-40A1-994C-F57FF2477BE4:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7CF7E90F-A14F-40A1-994C-F57FF2477BE4:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:40 [3, 9, 12, 31, 32, 33, 35, 39, 40]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7CF7E90F-A14F-40A1-994C-F57FF2477BE4:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:41 [3, 9, 12, 31, 32, 33, 35, 39, 40, 41]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:7CF7E90F-A14F-40A1-994C-F57FF2477BE4:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:7CF7E90F-A14F-40A1-994C-F57FF2477BE4:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7CF7E90F-A14F-40A1-994C-F57FF2477BE4:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:42 [3, 9, 12, 31, 32, 33, 35, 39, 40, 41, 42]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7CF7E90F-A14F-40A1-994C-F57FF2477BE4:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:43 [3, 9, 12, 31, 32, 33, 35, 39, 40, 41, 42, 43]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:peer:didChange:) peer:DEEE9265-B86D-4480-BD12-C8FCCBE5FDBA state: connecting -> connected
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:39
[ThaliCore] VirtualSocket.closeStreams() vsID:39
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:39
,[ThaliCore] VirtualSocket.deinit vsID:39 [3, 9, 12, 31, 32, 33, 35, 40, 41, 42, 43]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0C13EC7D-58C9-4EE8-AE56-E60174103537
[ThaliCore] Session.startOutputStream(with:) peer:0C13EC7D-58C9-4EE8-AE56-E60174103537
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:44 [3, 9, 12, 31, 32, 33, 35, 40, 41, 42, 43, 44]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:DEEE9265-B86D-4480-BD12-C8FCCBE5FDBA
,[ThaliCore] Session.startOutputStream(with:) peer:DEEE9265-B86D-4480-BD12-C8FCCBE5FDBA
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:45 [3, 9, 12, 31, 32, 33, 35, 40, 41, 42, 43, 44, 45]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:DEEE9265-B86D-4480-BD12-C8FCCBE5FDBA
,[ThaliCore] Session.startOutputStream(with:) peer:DEEE9265-B86D-4480-BD12-C8FCCBE5FDBA
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:46 [3, 9, 12, 31, 32, 33, 35, 40, 41, 42, 43, 44, 45, 46]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:DEEE9265-B86D-4480-BD12-C8FCCBE5FDBA
,[ThaliCore] Session.startOutputStream(with:) peer:DEEE9265-B86D-4480-BD12-C8FCCBE5FDBA
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:47 [3, 9, 12, 31, 32, 33, 35, 40, 41, 42, 43, 44, 45, 46, 47]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:DEEE9265-B86D-4480-BD12-C8FCCBE5FDBA
,[ThaliCore] Session.startOutputStream(with:) peer:DEEE9265-B86D-4480-BD12-C8FCCBE5FDBA
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:48 [3, 9, 12, 31, 32, 33, 35, 40, 41, 42, 43, 44, 45, 46, 47, 48]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vs,ID:40
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:40
,[ThaliCore] VirtualSocket.deinit vsID:40 [3, 9, 12, 31, 32, 33, 35, 41, 42, 43, 44, 45, 46, 47, 48]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:41
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
,[ThaliCore] VirtualSocket.closeStreams() vsID:43
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:43
,[ThaliCore] VirtualSocket.deinit vsID:43 [3, 9, 12, 31, 32, 33, 35, 41, 42, 44, 45, 46, 47, 48]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:42
,[ThaliCore] VirtualSocket exited RunLoop vsID:42
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:42 [3, 9, 12, 31, 32, 33, 35, 41, 44, 45, 46, 47, 48]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:7CF7E90F-A14F-40A1-994C-F57FF2477BE4:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7CF7E90F-A14F-40A1-994C-F57FF2477BE4:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:49 [3, 9, 12, 31, 32, 33, 35, 41, 44, 45, 46, 47, 48, 49]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:47
[ThaliCore] VirtualSocket.closeStreams() vsID:47
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:47
[ThaliCore] VirtualSocket.deinit vsID:47 [3, 9, 12, 31, 32, 33, 35, 41, 44, 45, 46, 48, 49]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClie,nt.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:46
[ThaliCore] VirtualSocket.closeStreams() vsID:46
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:46
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSock,etDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket.deinit vsID:46 [3, 9, 12, 31, 32, 33, 35, 41, 44, 45, 48, 49]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:45
[ThaliCore] VirtualSocket.closeStreams() vsID:45
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:45
[ThaliCore] VirtualSocket.deinit vsID:45 [3, 9, 12, 31, 32, 33, 35, 41, 44, 48, 49]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0C13EC7D-58C9-4EE8-AE56-E60174103537
,[ThaliCore] Session.startOutputStream(with:) peer:0C13EC7D-58C9-4EE8-AE56-E60174103537
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:50 [3, 9, 12, 31, 32, 33, 35, 41, 44, 48, 49, 50]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:48
[ThaliCore] VirtualSocket.closeStreams() vsID:48
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:48
,[ThaliCore] VirtualSocket.deinit vsID:48 [3, 9, 12, 31, 32, 33, 35, 41, 44, 49, 50]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:DEEE9265-B86D-4480-BD12-C8FCCBE5FDBA
[ThaliCore] Session.startOutputStream(with:) peer:DEEE9265-B86D-4480-BD12-C8FCCBE5FDBA
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:51 [3, 9, 12, 31, 32, 33, 35, 41, 44, 49, 50, 51]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-18 09:56:16 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:7CF7E90F-A14F-40A1-994C-F57FF2477BE4:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7CF7E90F-A14F-40A1-994C-F57FF2477BE4:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:52 [3, 9, 12, 31, 32, 33, 35, 41, 44, 49, 50, 51, 52]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:DEEE9265-B86D-4480-BD12-C8FCCBE5FDBA
[ThaliCore] Session.startOutputStream(with:) peer:DEEE9265-B86D-4480-BD12-C8FCCBE5FDBA
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:53 [3, 9, 12, 31, 32, 33, 35, 41, 44, 49, 50, 51, 52, 53]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0C13EC7D-58C9-4EE8-AE56-E60174103537
[ThaliCore] Session.startOutputStream(with:) peer:0C13EC7D-58C9-4EE8-AE56-E60174103537
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:54 [3, 9, 12, 31, 32, 33, 35, 41, 44, 49, 50, 51, 52, 53, 54]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:7CF7E90F-A14F-40A1-994C-F57FF2477BE4:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7CF7E90F-A14F-40A1-994C-F57FF2477BE4:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:55 [3, 9, 12, 31, 32, 33, 35, 41, 44, 49, 50, 51, 52, 53, 54, 55]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0C13EC7D-58C9-4EE8-AE56-E60174103537
,[ThaliCore] Session.startOutputStream(with:) peer:0C13EC7D-58C9-4EE8-AE56-E60174103537
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:56 [3, 9, 12, 31, 32, 33, 35, 41, 44, 49, 50, 51, 52, 53, 54, 55, 56]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,2017-07-18 09:56:16 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 6146027520:error:1408F119:SSL routines:SSL3_GET_RECORD:decryption failed or bad record mac:../deps/openssl/openssl/ssl/s3_pkt.c:518:
'
,2017-07-18 09:56:16 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: 6146027520:error:1408F119:SSL routines:SSL3_GET_RECORD:decryption failed or bad record mac:../deps/openssl/openssl/ssl/s3_pkt.c:518:
  and it caused us to complete'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vs,ID:31
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:31
[ThaliCore] VirtualSocket.deinit vsID:31 [3, 9, 12, 32, 33, 35, 41, 44, 49, 50, 51, 52, 53, 54, 55, 56]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:32
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:32
,[ThaliCore] VirtualSocket.deinit vsID:32 [3, 9, 12, 33, 35, 41, 44, 49, 50, 51, 52, 53, 54, 55, 56]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:33
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:33
[ThaliCore] VirtualSocket.deinit vsID:33 [3, 9, 12, 35, 41, 44, 49, 50, 51, 52, 53, 54, 55, 56]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:35
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:35
,[ThaliCore] VirtualSocket.deinit vsID:35 [3, 9, 12, 41, 44, 49, 50, 51, 52, 53, 54, 55, 56]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0C13EC7D-58C9-4EE8-AE56-E60174103537
,[ThaliCore] Session.startOutputStream(with:) peer:0C13EC7D-58C9-4EE8-AE56-E60174103537
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:57 [3, 9, 12, 41, 44, 49, 50, 51, 52, 53, 54, 55, 56, 57]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:DEEE9265-B86D-4480-BD12-C8FCCBE5FDBA
,[ThaliCore] Session.startOutputStream(with:) peer:DEEE9265-B86D-4480-BD12-C8FCCBE5FDBA
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:58 [3, 9, 12, 41, 44, 49, 50, 51, 52, 53, 54, 55, 56, 57, 58]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:44
[ThaliCore] VirtualSocket.closeStreams() vsID:44
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:51
[ThaliCore] VirtualSocket.closeStreams() vsID:51
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:50
[ThaliCore] VirtualSocket.closeStreams() vsID:50
,[ThaliCore] VirtualSocket exited RunLoop vsID:51
,[ThaliCore] VirtualSocket.deinit vsID:51 [3, 9, 12, 41, 44, 49, 50, 52, 53, 54, 55, 56, 57, 58]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client di,sconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket ,error:nil
[ThaliCore] VirtualSocket exited RunLoop vsID:44
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:54
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] VirtualSocket.deinit vsID:44 [3,, 9, 12, 41, 49, 50, 52, 53, 54, 55, 56, 57, 58]
[ThaliCore] VirtualSocket.closeStreams() vsID:54
[ThaliCore] VirtualSocket exited RunLoop vsID:50
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] VirtualSocket.deinit vsID:50 [3, 9, 12, 41, 49, 52, 53, 54, 55, 56, 57, 58]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:56
[ThaliCore] VirtualSocket.closeStreams() vsID:56
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] VirtualSocket exited RunLoop vsID:54
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] VirtualSocket exited RunLoop vsID:56
[ThaliCore] VirtualSocket.deinit vsID:54 [3, 9, 12, 41, 49, 52, 53, 55, 56, 57, 58]
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] VirtualSocket.deinit vsID:56 [3, 9, 12, 41, 49, 52, 53, 55, 57, 58]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:DEEE9265-B86D-4480-BD12-C8FCCBE5FDBA
[ThaliCore] Session.startOutputStream(with:) peer:DEEE9265-B86D-4480-BD12-C8FCCBE5FDBA
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:59 [3, 9, 12, 41, 49, 52, 53, 55, 57, 58, 59]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:53
[ThaliCore] VirtualSocket.closeStreams() vsID:53
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:58
[ThaliCore] VirtualSocket.closeStreams() vsID:58
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:53
[ThaliCore] VirtualSocket.deinit vsID:53 [3, 9, 12, 41, 49, 52, 55, 57, 58, 59]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCor,e] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:58
,[ThaliCore] VirtualSocket.deinit vsID:58 [3, 9, 12, 41, 49, 52, 55, 57, 59]
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:57
[ThaliCore] VirtualSocket.closeStreams() vsID:57
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:57
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket.deinit vsID:57 [3, 9, 12, 41, 49, 52, 55, 59]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:7CF7E90F-A14F-40A1-994C-F57FF2477BE4:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7CF7E90F-A14F-40A1-994C-F57FF2477BE4:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:60 [3, 9, 12, 41, 49, 52, 55, 59, 60]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:49
[ThaliCore] Browse,rRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:49
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] VirtualSocket.deinit vsID:49 [3, 9, 12, 41, 52, 55, 59, 60]
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, coun,t:2
[ThaliCore] VirtualSocket.closeStreams() vsID:52
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:52
,[ThaliCore] VirtualSocket.deinit vsID:52 [3, 9, 12, 41, 55, 59, 60]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:1
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:55
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:55
[ThaliCore] VirtualSocket.deinit vsID:55 [3, 9, 12, 41, 59, 60]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vs,ID:60
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:60
[ThaliCore] VirtualSocket.deinit vsID:60 [3, 9, 12, 41, 59]
,2017-07-18 09:56:17 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 socket hang up -1'
,2017-07-18 09:56:17 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: socket hang up -1  but we are already killed and so we ignored it'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:96EDEA21-4608-4173-8B8B-32BA5F4A9A9C
,2017-07-18 09:56:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-18 09:56:17 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"5998E650-08FC-45D0-A270-46ABE636425B","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-18 09:56:17 - WARN thaliNotificationClient: 'peer is not available'
,2017-07-18 09:56:17 - WARN thaliNotificationClient: 'peer is not available'
,2017-07-18 09:56:17 - WARN thaliNotificationClient: 'peer is not available'
,2017-07-18 09:56:17 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"7CF7E90F-A14F-40A1-994C-F57FF2477BE4","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-18 09:56:17 - WARN thaliNotificationClient: 'peer is not available'
,2017-07-18 09:56:17 - WARN thaliNotificationClient: 'peer is not available'
,2017-07-18 09:56:17 - WARN thaliNotificationClient: 'peer is not available'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-18 09:56:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-18 09:56:17 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
,2017-07-18 09:56:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,[ThaliCore] VirtualSocket exited RunLoop vsID:41
[ThaliCore] VirtualSocket.deinit vsID:41 [3, 9, 12, 59]
,2017-07-18 09:56:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:56:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-18 09:56:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:59
[ThaliCore] VirtualSocket.closeStreams() vsID:59
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:59
,[ThaliCore] VirtualSocket.deinit vsID:59 [3, 9, 12]
,ok 919 passed
,# teardown
,# setup
,# Coordinated replication action test - should throw error when wrong remote db name is provided
,2017-07-18 09:56:18 - DEBUG thaliMobileNativeWrapper: 'listening 53601'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:0840D407-2324-415F-92C0-550C1DCC6ABD
[ThaliCore] Browser.startListening
,2017-07-18 09:56:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "D498A656-E3D2-4278-AB59-18ED013C38C7", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:D498A656-E3D2-4278-AB59-18ED013C38C7
,2017-07-18 09:56:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5998E650-08FC-45D0-A270-46ABE636425B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5998E650-08FC-45D0-A270-46ABE636425B", generation: 0)
,2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"5998E650-08FC-45D0-A270-46ABE636425B","generation":0}]'
[ThaliCore] Browser.browser(_:foundPeer:withDi,scoveryInfo:) found peer:7CF7E90F-A14F-40A1-994C-F57FF2477BE4:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7CF7E90F-A14F-40A1-994C-F57FF2477BE4", generation: 0)
,2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"5998E650-08FC-45D0-A270-46ABE636425B","generation":0}'
,2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"7CF7E90F-A14F-40A1-994C-F57FF2477BE4","generation":0}]'
,2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"7CF7E90F-A14F-40A1-994C-F57FF2477BE4","generation":0}'
,2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"5998E650-08FC-45D0-A270-46ABE636425B","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-18 09:56:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5998E650-08FC-45D0-A270-46ABE636425B","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"7CF7E90F-A14F-40A1-994C-F57FF2477BE4","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-18 09:56:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7CF7E90F-A14F-40A1-994C-F57FF2477BE4","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 5998E650-08FC-45D0-A270-46ABE636425B (syncValue: 12)'
,2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5998E650-08FC-45D0-A270-46ABE636425B", generation: 0) found active relay
,2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"12","error":null,"portNumber":53564}'
,2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 5998E650-08FC-45D0-A270-46ABE636425B (syncValue: 13)'
,2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5998E650-08FC-45D0-A270-46ABE636425B", generation: 0) found active relay
,2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"13","error":null,"portNumber":53564}'
,2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 5998E650-08FC-45D0-A270-46ABE636425B (syncValue: 14)'
,2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5998E650-08FC-45D0-A270-46ABE636425B", generation: 0) found active relay
,2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"14","error":null,"portNumber":53564}'
,2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 5998E650-08FC-45D0-A270-46ABE636425B (syncValue: 15)'
2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5998E650-08FC-45D0-A270-46ABE636425B", generation: 0) found active relay
,2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"15","error":null,"portNumber":53564}'
,2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 7CF7E90F-A14F-40A1-994C-F57FF2477BE4 (syncValue: 16)'
,2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7CF7E90F-A14F-40A1-994C-F57FF2477BE4", generation: 0) found active relay
,2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"16","error":null,"portNumber":53579}'
,2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 7CF7E90F-A14F-40A1-994C-F57FF2477BE4 (syncValue: 17)'
,2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7CF7E90F-A14F-40A1-994C-F57FF2477BE4", generation: 0) found active relay
,2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"17","error":null,"portNumber":53579}'
,2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 7CF7E90F-A14F-40A1-994C-F57FF2477BE4 (syncValue: 18)'
,2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7CF7E90F-A14F-40A1-994C-F57FF2477BE4", generation: 0) found active relay
,2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"18","error":null,"portNumber":53579}'
,2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 7CF7E90F-A14F-40A1-994C-F57FF2477BE4 (syncValue: 19)'
,2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7CF7E90F-A14F-40A1-994C-F57FF2477BE4", generation: 0) found active relay
,2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"19","error":null,"portNumber":53579}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:7CF7E90F-A14F-40A1-994C-F57FF2477BE4:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:7CF7E90F-A14F-40A1-994C-F57FF2477BE4:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:7CF7E90F-A14F-40A1-994C-F57FF2477BE4:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:7CF7E90F-A14F-40A1-994C-F57FF2477BE4:0
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4A711876-4C8F-4060-B5CA-D8ECB659AFA8:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4A711876-4C8F-4060-B5CA-D8ECB659AFA8", generation: 0)
,2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"4A711876-4C8F-4060-B5CA-D8ECB659AFA8","generation":0}]'
,2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"4A711876-4C8F-4060-B5CA-D8ECB659AFA8","generation":0}'
,2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"4A711876-4C8F-4060-B5CA-D8ECB659AFA8","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-18 09:56:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"4A711876-4C8F-4060-B5CA-D8ECB659AFA8","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 4A711876-4C8F-4060-B5CA-D8ECB659AFA8 (syncValue: 20)'
,2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4A711876-4C8F-4060-B5CA-D8ECB659AFA8", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4A711876-4C8F-4060-B5CA-D8ECB659AFA8", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4A711876-4C8F-4060-B5CA-D8ECB659AFA8:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:61 [3, 9, 12, 61]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:62 [3, 9, 12, 61, 62]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:63 [3, 9, 12, 61, 62, 63]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:64 [3, 9, 12, 61, 62, 63, 64]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:61
[ThaliCore] VirtualSocket.closeStreams() vsID:61
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:61
,[ThaliCore] VirtualSocket.deinit vsID:61 [3, 9, 12, 62, 63, 64]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRela,y.didSocketDisconnectHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:63
[ThaliCore] VirtualSocket.closeStreams() vsID:63
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:63
,[ThaliCore] VirtualSocket.deinit vsID:63 [3, 9, 12, 62, 64]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:62
[ThaliCore] VirtualSocket.closeStreams() vsID:62
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:62
[ThaliCore] VirtualSocket.deinit vsID:62 [3, 9, 12, 64]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted sock,et error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-18 09:56:19 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,2017-07-18 09:56:19 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,2017-07-18 09:56:19 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7CF7E90F-A14F-40A1-994C-F57FF2477BE4:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:65 [3, 9, 12, 64, 65]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7CF7E90F-A14F-40A1-994C-F57FF2477BE4:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:66 [3, 9, 12, 64, 65, 66]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7CF7E90F-A14F-40A1-994C-F57FF2477BE4:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:67 [3, 9, 12, 64, 65, 66, 67]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7CF7E90F-A14F-40A1-994C-F57FF2477BE4:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:68 [3, 9, 12, 64, 65, 66, 67, 68]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:65
[ThaliCore] VirtualSocket.closeStreams() vsID:65
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:66
,[ThaliCore] VirtualSocket exited RunLoop vsID:65
,[ThaliCore] VirtualSocket.closeStreams() vsID:66
,[ThaliCore] VirtualSocket.deinit vsID:65 [3, 9, 12, 64, 66, 67, 68]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:66
[ThaliCore] VirtualSocket.deinit vsID:66 [3, 9, 12, 64, 67, 68]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:67
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:68
[ThaliCore] VirtualSocket.closeStreams() vsID:67
,[ThaliCore] VirtualSocket.closeStreams() vsID:68
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:67
[ThaliCore] VirtualSocket.deinit vsID:67 [3, 9, 12, 64, 68]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:68
,[ThaliCore] VirtualSocket.deinit vsID:68 [3, 9, 12, 64]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-18 09:56:19 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B04D5511-FFB0-4BD6-B61C-A5D82A8963CF
[ThaliCore] Advertiser: session connected Peer(uuid: "D498A656-E3D2-4278-AB59-18ED013C38C7", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:B04D5511-FFB0-4BD6-B61C-A5D82A8963CF state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E9A60538-A18D-473B-B89F-8BF9C1999CE5:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E9A60538-A18D-473B-B89F-8BF9C1999CE5", generation: 0)
2017-07-18 09:56:19 - DEBUG t,haliPeerPoolDefault: 'Got err   Could not establish TCP connection'
2017-07-18 09:56:19 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
2017-07-18 09:56:19 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
[ThaliCore] Session.session(_:peer:didChange:) peer:4A711876-4C8F-4060-B5CA-D8ECB659AFA8:0 state: notConnected -> connecting
2017-07-18 09:56:20 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"E9A60538-A18D-473B-B89F-8BF9C1999CE5","generation":0}]'
2017-07-18 09:56:20 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"E9A60538-A18D-473B-B89F-8,BF9C1999CE5","generation":0}'
2017-07-18 09:56:20 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"E9A60538-A18D-473B-B89F-8BF9C1999CE5","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-18 09:5,6:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"E9A60538-A18D-473B-B89F-8BF9C1999CE5","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D498A656-E3D2-4278-AB59-18ED013C38C7:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D498A656-E3D2-4278-AB59-18ED013C38C7", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:7CF7E90F-A14F-40A1-994C-F57FF2477BE4:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "7CF7E90F-A14F-40A1-994C-F57FF2477BE4", generation: 0)
[ThaliCore] Session.session(_:didReceiveCertificat,e:fromPeer:certificateHandler:) peer:4A711876-4C8F-4060-B5CA-D8ECB659AFA8:0
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:53579
[ThaliCore] TCPListener.socketDidDisco,nnect(_:withError:) listening socket error:nil
[ThaliCore] Session.disconnect() peer:7CF7E90F-A14F-40A1-994C-F57FF2477BE4:0
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:4A711876-4C8F-4060-B5CA-D8ECB659AFA8:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "4A711876-4C8F-4060-B5CA-D8ECB659AFA8", generation: 0)
,[ThaliCore] Session.deinit peer:7CF7E90F-A14F-40A1-994C-F57FF2477BE4:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "7CF7E90F-A14F-40A1-994C-F57FF2477BE4", generation: 0) relay removed
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] BrowserRelay.openRelay(with:)
,2017-07-18 09:56:22 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"7CF7E90F-A14F-40A1-994C-F57FF2477BE4","generation":0}]'
2017-07-18 09:56:22 - DEBUG thaliMobileNative,Wrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"7CF7E90F-A14F-40A1-994C-F57FF2477BE4","generation":0}'
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localpor,t:53612
,2017-07-18 09:56:22 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"7CF7E90F-A14F-40A1-994C-F57FF2477BE4","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-18 09:56:22 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7CF7E90F-A14F-40A1-994C-F57FF2477BE4","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-18 09:56:22 - WARN thaliNotificationClient: 'peer is not available'
,2017-07-18 09:56:22 - WARN thaliNotificationClient: 'peer is not available'
,2017-07-18 09:56:22 - WARN thaliNotificationClient: 'peer is not available'
,2017-07-18 09:56:22 - WARN thaliNotificationClient: 'peer is not available'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B04D5511-FFB0-4BD6-B61C-A5D82A8963CF
,2017-07-18 09:56:22 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"20","error":null,"portNumber":53612}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:B04D5511-FFB0-4BD6-B61C-A5D82A8963CF state: connecting -> connected
,2017-07-18 09:56:22 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 4A711876-4C8F-4060-B5CA-D8ECB659AFA8 (syncValue: 21)'
,2017-07-18 09:56:22 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4A711876-4C8F-4060-B5CA-D8ECB659AFA8", generation: 0) found active relay
,2017-07-18 09:56:22 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"21","error":null,"portNumber":53612}'
,2017-07-18 09:56:22 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 4A711876-4C8F-4060-B5CA-D8ECB659AFA8 (syncValue: 22)'
,2017-07-18 09:56:22 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4A711876-4C8F-4060-B5CA-D8ECB659AFA8", generation: 0) found active relay
,2017-07-18 09:56:22 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"22","error":null,"portNumber":53612}'
,2017-07-18 09:56:22 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 4A711876-4C8F-4060-B5CA-D8ECB659AFA8 (syncValue: 23)'
,2017-07-18 09:56:22 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4A711876-4C8F-4060-B5CA-D8ECB659AFA8", generation: 0) found active relay
,2017-07-18 09:56:22 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"23","error":null,"portNumber":53612}'
,2017-07-18 09:56:22 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 5998E650-08FC-45D0-A270-46ABE636425B (syncValue: 24)'
,2017-07-18 09:56:22 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5998E650-08FC-45D0-A270-46ABE636425B", generation: 0) found active relay
,2017-07-18 09:56:22 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"24","error":null,"portNumber":53564}'
,2017-07-18 09:56:22 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for E9A60538-A18D-473B-B89F-8BF9C1999CE5 (syncValue: 25)'
,2017-07-18 09:56:22 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E9A60538-A18D-473B-B89F-8BF9C1999CE5", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E9A60538-A18D-473B-B89F-8BF9C1999CE5", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E9A60538-A18D-473B-B89F-8BF9C1999CE5:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:4A711876-4C8F-4060-B5CA-D8ECB659AFA8:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4A711876-4C8F-4060-B5CA-D8ECB659AFA8:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:69 [3, 9, 12, 64, 69]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:4A711876-4C8F-4060-B5CA-D8ECB659AFA8:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:4A711876-4C8F-4060-B5CA-D8ECB659AFA8:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4A711876-4C8F-4060-B5CA-D8ECB659AFA8:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:70 [3, 9, 12, 64, 69, 70]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4A711876-4C8F-4060-B5CA-D8ECB659AFA8:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:71 [3, 9, 12, 64, 69, 70, 71]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:4A711876-4C8F-4060-B5CA-D8ECB659AFA8:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4A711876-4C8F-4060-B5CA-D8ECB659AFA8:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:72 [3, 9, 12, 64, 69, 70, 71, 72]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:73 [3, 9, 12, 64, 69, 70, 71, 72, 73]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:73
[ThaliCore] VirtualSocket.closeStreams() vsID:73
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:73
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] VirtualSocket.deinit vsID:73 [3, 9, 12, 64, 69, 70, 71, 72]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-18 09:56:22 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:7003160D-A068-47B1-94BD-2C65360F68B1
[ThaliCore] Advertiser: session connected Peer(uuid: "D498A656-E3D2-4278-AB59-18ED013C38C7", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:7003160D-A068-47B1-94BD-2C65360F68B1 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:E9A60538-A18D-473B-B89F-8BF9C1999CE5:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B04D5511-FFB0-4BD6-B61C-A5D82A8963CF
[ThaliCore] Session.startOutputStream(with:) peer:B04D5511-FFB0-4BD6-B61C-A5D82A8963CF
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:74 [3, 9, 12, 64, 69, 70, 71, 72, 74]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B04D5511-FFB0-4BD6-B61C-A5D82A8963CF
[ThaliCore] Session.startOutputStream(with:) peer:B04D5511-FFB0-4BD6-B61C-A5D82A8963CF
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:75 [3, 9, 12, 64, 69, 70, 71, 72, 74, 75]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B04D5511-FFB0-4BD6-B61C-A5D82A8963CF
,[ThaliCore] Session.startOutputStream(with:) peer:B04D5511-FFB0-4BD6-B61C-A5D82A8963CF
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:76 [3, 9, 12, 64, 69, 70, 71, 72, 74, 75, 76]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B04D5511-FFB0-4BD6-B61C-A5D82A8963CF
[ThaliCore] Session.startOutputStream(with:) peer:B04D5511-FFB0-4BD6-B61C-A5D82A8963CF
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:77 [3, 9, 12, 64, 69, 70, 71, 72, 74, 75, 76, 77]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:71
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:71
,[ThaliCore] VirtualSocket.deinit vsID:71 [3, 9, 12, 64, 69, 70, 72, 74, 75, 76, 77]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:75
[ThaliCore] VirtualSocket.closeStreams() vsID:75
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:75
,[ThaliCore] VirtualSocket.deinit vsID:75 [3, 9, 12, 64, 69, 70, 72, 74, 76, 77]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[Tha,liCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
,[ThaliCore] VirtualSocket.closeStreams() vsID:72
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:72
,[ThaliCore] VirtualSocket.deinit vsID:72 [3, 9, 12, 64, 69, 70, 74, 76, 77]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:74
[ThaliCore] VirtualSocket.closeStreams() vsID:74
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:74
,[ThaliCore] VirtualSocket.deinit vsID:74 [3, 9, 12, 64, 69, 70, 76, 77]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
,[ThaliCore] VirtualSocket.closeStreams() vsID:70
,[ThaliCore] VirtualSocket exited RunLoop vsID:70
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:4A711876-4C8F-4060-B5CA-D8ECB659AFA8:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:69
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:69
[ThaliCore] VirtualSocket.deinit vsID:69 [3, 9, 12, 64, 70, 76, 77]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4A711876-4C8F-4060-B5CA-D8ECB659AFA8:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:78 [3, 9, 12, 64, 70, 76, 77, 78]
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:70 [3, 9, 12, 64, 76, 77, 78]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:77
[ThaliCore] VirtualSocket.closeStreams() vsID:77
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:77
[ThaliCore] VirtualSocket.deinit vsID:77 [3, 9, 12, 64, 76, 78]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:wit,hError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B04D5511-FFB0-4BD6-B61C-A5D82A8963CF
,[ThaliCore] Session.startOutputStream(with:) peer:B04D5511-FFB0-4BD6-B61C-A5D82A8963CF
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:79 [3, 9, 12, 64, 76, 78, 79]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:76
[ThaliCore] VirtualSocket.closeStreams() vsID:76
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:76
[ThaliCore] VirtualSocket.deinit vsID:76 [3, 9, 12, 64, 78, 79]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:wit,hError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-18 09:56:23 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  404 no_db_file'
,2017-07-18 09:56:23 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: no_db_file  and it caused us to complete'
,ok 920 error should be 'no_db_file'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:78
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:78
,[ThaliCore] VirtualSocket.deinit vsID:78 [3, 9, 12, 64, 79]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:79
[ThaliCore] VirtualSocket.closeStreams() vsID:79
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:E9A60538-A18D-473B-B89F-8BF9C1999CE5:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:E9A60538-A18D-473B-B89F-8BF9C1999CE5:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "E9A60538-A18D-473B-B89F-8BF9C1999CE5", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:53626
,2017-07-18 09:56:25 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"25","error":null,"portNumber":53626}'
,2017-07-18 09:56:25 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for E9A60538-A18D-473B-B89F-8BF9C1999CE5 (syncValue: 26)'
,2017-07-18 09:56:25 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E9A60538-A18D-473B-B89F-8BF9C1999CE5", generation: 0) found active relay
,2017-07-18 09:56:25 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"26","error":null,"portNumber":53626}'
,2017-07-18 09:56:25 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for E9A60538-A18D-473B-B89F-8BF9C1999CE5 (syncValue: 27)'
,2017-07-18 09:56:25 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E9A60538-A18D-473B-B89F-8BF9C1999CE5", generation: 0) found active relay
,2017-07-18 09:56:25 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"27","error":null,"portNumber":53626}'
,2017-07-18 09:56:25 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for E9A60538-A18D-473B-B89F-8BF9C1999CE5 (syncValue: 28)'
,2017-07-18 09:56:25 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E9A60538-A18D-473B-B89F-8BF9C1999CE5", generation: 0) found active relay
,2017-07-18 09:56:25 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"28","error":null,"portNumber":53626}'
,2017-07-18 09:56:25 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 5998E650-08FC-45D0-A270-46ABE636425B (syncValue: 29)'
,2017-07-18 09:56:25 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5998E650-08FC-45D0-A270-46ABE636425B", generation: 0) found active relay
,2017-07-18 09:56:25 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"29","error":null,"portNumber":53564}'
,2017-07-18 09:56:25 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 5998E650-08FC-45D0-A270-46ABE636425B (syncValue: 30)'
,2017-07-18 09:56:25 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5998E650-08FC-45D0-A270-46ABE636425B", generation: 0) found active relay
,2017-07-18 09:56:25 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"30","error":null,"portNumber":53564}'
,2017-07-18 09:56:25 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 7CF7E90F-A14F-40A1-994C-F57FF2477BE4 (syncValue: 31)'
,2017-07-18 09:56:25 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7CF7E90F-A14F-40A1-994C-F57FF2477BE4", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7CF7E90F-A14F-40A1-994C-F57FF2477BE4", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
,2017-07-18 09:56:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"31","error":"Peer is unavailable","portNumber":null}'
,2017-07-18 09:56:26 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"7CF7E90F-A14F-40A1-994C-F57FF2477BE4","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-18 09:56:26 - DEBUG thaliMobil,eNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"7CF7E90F-A14F-40A1-994C-F57FF2477BE4","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-18 09:56:26 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 7CF7E90F-A14F-40A1-994C-F57FF2477BE4 (syncValue: 32)'
,2017-07-18 09:56:26 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7CF7E90F-A14F-40A1-994C-F57FF2477BE4", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7C,F7E90F-A14F-40A1-994C-F57FF2477BE4", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-18 09:56:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"32","error":"Peer is unavailable","portNumber":null}'
,2017-07-18 09:56:26 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"7CF7E90F-A14F-40A1-994C-F57FF2477BE4","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-18 09:56:26 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"7CF7E90F-A14F-40A1-994C-F57FF2477BE4","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-18 09:56:26 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 7CF7E90F-A14F-40A1-994C-F57FF2477BE4 (syncValue: 33)'
,2017-07-18 09:56:26 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7CF7E90F-A14F-40A1-994C-F57FF2477BE4", generation: 0) creating a new relay
[ThaliCo,re] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7CF7E90F-A14F-40A1-994C-F57FF2477BE4", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
,2017-07-18 09:56:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"33","error":"Peer is unavailable","portNumber":null}'
,2017-07-18 09:56:26 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"7CF7E90F-A14F-40A1-994C-F57FF2477BE4","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-18 09:56:26 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"7CF7E90F-A14F-40A1-994C-F57FF2477BE4","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-18 09:56:26 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 7CF7E90F-A14F-40A1-994C-F57FF2477BE4 (syncValue: 34)'
,2017-07-18 09:56:26 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7CF7E90F-A14F-40A1-994C-F57FF2477BE4", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7C,F7E90F-A14F-40A1-994C-F57FF2477BE4", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
,2017-07-18 09:56:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"34","error":"Peer is unavailable","portNumber":null}'
,2017-07-18 09:56:26 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"7CF7E90F-A14F-40A1-994C-F57FF2477BE4","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-18 09:56:26 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"7CF7E90F-A14F-40A1-994C-F57FF2477BE4","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-18 09:56:26 - DEBUG thaliPeerPoolDefault: 'Got err   Peer is unavailable'
,2017-07-18 09:56:26 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 5998E650-08FC-45D0-A270-46ABE636425B (syncValue: 35)'
,2017-07-18 09:56:26 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5998E650-08FC-45D0-A270-46ABE636425B", generation: 0) found active relay
2017-07-18 09:56:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"35","error":null,"portNumber":53564}'
,2017-07-18 09:56:26 - DEBUG thaliPeerPoolDefault: 'Got err   Peer is unavailable'
,2017-07-18 09:56:26 - DEBUG thaliPeerPoolDefault: 'Got err   Peer is unavailable'
2017-07-18 09:56:26 - DEBUG thaliPeerPoolDefault: 'Got err   Peer is unavailable'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E9A60538-A18D-473B-B89F-8BF9C1999CE5:0
,2017-07-18 09:56:26 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"7CF7E90F-A14F-40A1-994C-F57FF2477BE4","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E9A60538-A18D-473B-B89F-8BF9C1999CE5:0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[Thal,iCore] Session.startOutputStream(with:) peer:E9A60538-A18D-473B-B89F-8BF9C1999CE5:0
,2017-07-18 09:56:26 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"7CF7E90F-A14F-40A1-994C-F57FF2477BE4","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-18 09:56:26 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"7CF7E90F-A14F-40A1-994C-F57FF2477BE4","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-18 09:56:26 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"7CF7E90F-A14F-40A1-994C-F57FF2477BE4","peerAvailable":true,"portNumber":null,"recreated":true}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E9A60538-A18D-473B-B89F-8BF9C1999CE5:0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[Th,aliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCo,re] Session.startOutputStream(with:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:5998E650-08FC-45,D0-A270-46ABE636425B:0
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E9A60538-A18D-473B-B89F-8BF9C1999CE5:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:80 [3, 9, 12, 64, 79, 80]
[ThaliCore] Session.session(_:didRec,eive:withName:fromPeer:) peer:E9A60538-A18D-473B-B89F-8BF9C1999CE5:0
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:81 [3, 9, 12, 64, 79, 80, 81]
[ThaliCore] BrowserRelay.didOpe,nVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:82 [3, 9, 12, 64, 79, 80, 81, 82]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-18 09:56:26 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"7CF7E90F-A14F-40A1-994C-F57FF2477BE4","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-18 09:56:26 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"7CF7E90F-A14F-40A1-994C-F57FF2477BE4","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-18 09:56:26 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"7CF7E90F-A14F-40A1-994C-F57FF2477BE4","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-18 09:56:26 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"7CF7E90F-A14F-40A1-994C-F57FF2477BE4","peerAvailable":true,"portNumber":null,"recreated":true}'
,[ThaliCore] BrowserManager.disconnect peer:7CF7E90F-A14F-40A1-994C-F57FF2477BE4
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:83 [3, 9, 12, 64, 79, 80, 81, 82, 83]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStr,eamsHandler
,[ThaliCore] BrowserManager.disconnect peer:7CF7E90F-A14F-40A1-994C-F57FF2477BE4
,[ThaliCore] BrowserManager.disconnect peer:7CF7E90F-A14F-40A1-994C-F57FF2477BE4
[ThaliCore] BrowserManager.disconnect peer:7CF7E90F-A14F-40A1-994C-F57FF2477BE4
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:82
[ThaliCore] VirtualSocket.closeStreams() vsID:82
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:84 [3, 9, 12, 64, 79, 80, 81, 82, 83, 84]
[ThaliCore] B,rowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:82
[ThaliCore] VirtualSocket.deinit vsID:82 [3, 9, 12, 64, 79, 80, 81, 83, 84]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
[Th,aliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E9A60538-A18D-473B-B89F-8BF9C1999CE5:0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:83
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:85 [3, 9, 12, 64, 79, 80, 81, 83, 84, 85]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket e,rror:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.closeStreams() vsID:83
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E9A60538-A18D-473B-B89F-8BF9C1999CE5:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:86 [3, 9, 12, 64, 79, 80, 81, 83, 84,, 85, 86]
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:83
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
[ThaliCore] VirtualSocket.deinit vsID:83 [3, 9, 12, 64, 7,9, 80, 81, 84, 85, 86]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:84
[ThaliCore] VirtualSocket.closeStreams() vsID:84
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:84
[ThaliCore] VirtualSocket.deinit vsID:84 [3, 9, 12, 64, 79, 80, 81, 85, 86]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-18 09:56:26 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,2017-07-18 09:56:26 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,2017-07-18 09:56:26 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:81
,[ThaliCore] VirtualSocket exited RunLoop vsID:81
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:81 [3, 9, 12, 64, 79, 80, 85, 86]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vs,ID:85
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:85
,[ThaliCore] VirtualSocket.deinit vsID:85 [3, 9, 12, 64, 79, 80, 86]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vs,ID:80
,[ThaliCore] VirtualSocket exited RunLoop vsID:80
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:80 [3, 9, 12, 64, 79, 86]
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:7003160D-A068-47B1-94BD-2C65360F68B1
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E9A60538-A18D-473B-B89F-8BF9C1999CE5:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:86
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:86
,[ThaliCore] VirtualSocket.deinit vsID:86 [3, 9, 12, 64, 79]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E9A60538-A18D-473B-B89F-8BF9C1999CE5:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:87 [3, 9, 12, 64, 79, 87]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:peer:didChange:) peer:7003160D-A068-47B1-94BD-2C65360F68B1 state: connecting -> connected
,2017-07-18 09:56:26 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 5998E650-08FC-45D0-A270-46ABE636425B (syncValue: 36)'
,2017-07-18 09:56:26 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5998E650-08FC-45D0-A270-46ABE636425B", generation: 0) found active relay
,2017-07-18 09:56:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"36","error":null,"portNumber":53564}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:88 [3, 9, 12, 64, 79, 87, 88]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-18 09:56:26 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 5998E650-08FC-45D0-A270-46ABE636425B (syncValue: 37)'
,2017-07-18 09:56:26 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5998E650-08FC-45D0-A270-46ABE636425B", generation: 0) found active relay
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:88
[ThaliCore] VirtualSocket.closeStreams() vsID:88
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:88
[ThaliCore] VirtualSocket.deinit vsID:88 [3, 9, 12, 64, 79, 87]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:,) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-18 09:56:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"37","error":null,"portNumber":53564}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:89 [3, 9, 12, 64, 79, 87, 89]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-18 09:56:26 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:89
[ThaliCore] VirtualSocket.closeStreams() vsID:89
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:89
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] VirtualSocket.deinit vsID:89 [3, 9, 12, 64, 79, 87]
,2017-07-18 09:56:26 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,2017-07-18 09:56:27 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 5998E650-08FC-45D0-A270-46ABE636425B (syncValue: 38)'
,2017-07-18 09:56:27 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5998E650-08FC-45D0-A270-46ABE636425B", generation: 0) found active relay
,2017-07-18 09:56:27 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"38","error":null,"portNumber":53564}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:90 [3, 9, 12, 64, 79, 87, 90]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:90
[ThaliCore] VirtualSocket.closeStreams() vsID:90
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:90
,[ThaliCore] VirtualSocket.deinit vsID:90 [3, 9, 12, 64, 79, 87]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7003160D-A068-47B1-94BD-2C65360F68B1
[ThaliCore] Session.startOutputStream(with:) peer:7003160D-A068-47B1-94BD-2C65360F68B1
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9,1 [3, 9, 12, 64, 79, 87, 91]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7003160D-A068-47B1-94BD-2C65360F68B1
[ThaliCore] Session.startOutputStream(with:) peer:7003160D-A068-47B1-94,BD-2C65360F68B1
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:92 [3, 9, 12, 64, 79, 87, 91, 92]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7003160D-A068-47B1-94BD-2C65360F68B1
[ThaliCore] Session.startOutputStream(with:) peer:7003160D-A068-47B1-94BD-2C65360F68B1
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:93 [3, 9, 12, 64, 79, 87, 91, 92, 93]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7003160D-A068-47B1-94BD-2C65360F68B1
[ThaliCore] Session.startOutputStream(with:) peer:7003160D-A068-47B1-94BD-2C65360F68B1
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:94 [3, 9, 12, 64, 79, 87, 91, 92, 93, 94]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,2017-07-18 09:56:27 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:91
[ThaliCore] VirtualSocket.closeStreams() vsID:91
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:91
,[ThaliCore] VirtualSocket.deinit vsID:91 [3, 9, 12, 64, 79, 87, 92, 93, 94]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-18 09:56:27 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  404 no_db_file'
,2017-07-18 09:56:27 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: no_db_file  and it caused us to complete'
,ok 921 error should be 'no_db_file'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
,[ThaliCore] VirtualSocket.closeStreams() vsID:87
,[ThaliCore] VirtualSocket exited RunLoop vsID:87
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:92
[ThaliCore] VirtualSocket.closeStreams() vsID:92
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:92
,[ThaliCore] VirtualSocket.deinit vsID:87 [3, 9, 12, 64, 79, 92, 93, 94]
,[ThaliCore] VirtualSocket.deinit vsID:92 [3, 9, 12, 64, 79, 93, 94]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:93
,[ThaliCore] VirtualSocket.closeStreams() vsID:93
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:93
,[ThaliCore] VirtualSocket.deinit vsID:93 [3, 9, 12, 64, 79, 94]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:94
[ThaliCore] VirtualSocket.closeStreams() vsID:94
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:94
[ThaliCore] VirtualSocket.deinit vsID:94 [3, 9, 12, 64, 79]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7003160D-A068-47B1-94BD-2C65360F68B1
[ThaliCore] Session.startOutputStream(with:) peer:7003160D-A068-47B1-94BD-2C65360F68B1
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:95 [3, 9, 12, 64, 79, 95]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-18 09:56:27 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 5998E650-08FC-45D0-A270-46ABE636425B (syncValue: 39)'
,2017-07-18 09:56:27 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5998E650-08FC-45D0-A270-46ABE636425B", generation: 0) found active relay
,2017-07-18 09:56:27 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"39","error":null,"portNumber":53564}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:96 [3, 9, 12, 64, 79, 95, 96]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:96
[ThaliCore] VirtualSocket.closeStreams() vsID:96
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] VirtualSocket exited RunLoop vsID:96
,[ThaliCore] VirtualSocket.deinit vsID:96 [3, 9, 12, 64, 79, 95]
,2017-07-18 09:56:27 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 5998E650-08FC-45D0-A270-46ABE636425B (syncValue: 40)'
,2017-07-18 09:56:27 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5998E650-08FC-45D0-A270-46ABE636425B", generation: 0) found active relay
,2017-07-18 09:56:27 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"40","error":null,"portNumber":53564}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:97 [3, 9, 12, 64, 79, 95, 97]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:97
[ThaliCore] VirtualSocket.closeStreams() vsID:97
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] VirtualSocket exited RunLoop vsID:97
,[ThaliCore] VirtualSocket.deinit vsID:97 [3, 9, 12, 64, 79, 95]
,2017-07-18 09:56:27 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,2017-07-18 09:56:27 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:95
[ThaliCore] VirtualSocket.closeStreams() vsID:95
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:95
,[ThaliCore] VirtualSocket.deinit vsID:95 [3, 9, 12, 64, 79]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:64
[ThaliCore] Browse,rRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:64
,[ThaliCore] VirtualSocket.deinit vsID:64 [3, 9, 12, 79]
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:D498A656-E3D2-4278-AB59-18ED013C38C7
,2017-07-18 09:56:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-18 09:56:28 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"5998E650-08FC-45D0-A270-46ABE636425B","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-18 09:56:28 - WARN thaliNotificationClient: 'peer is not available'
,2017-07-18 09:56:28 - WARN thaliNotificationClient: 'peer is not available'
,2017-07-18 09:56:28 - WARN thaliNotificationClient: 'peer is not available'
,2017-07-18 09:56:28 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"4A711876-4C8F-4060-B5CA-D8ECB659AFA8","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-18 09:56:28 - WARN thaliNotificationClient: 'peer is not available'
,2017-07-18 09:56:28 - WARN thaliNotificationClient: 'peer is not available'
,2017-07-18 09:56:28 - WARN thaliNotificationClient: 'peer is not available'
,2017-07-18 09:56:28 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"E9A60538-A18D-473B-B89F-8BF9C1999CE5","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-18 09:56:28 - WARN thaliNotificationClient: 'peer is not available'
,2017-07-18 09:56:28 - WARN thaliNotificationClient: 'peer is not available'
,2017-07-18 09:56:28 - WARN thaliNotificationClient: 'peer is not available'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-18 09:56:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-18 09:56:28 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
,2017-07-18 09:56:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-18 09:56:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:56:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-18 09:56:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 922 passed
,# teardown
,# setup
,# compareBufferArrays
,ok 923 should throw
,ok 924 should throw
,ok 925 (unnamed assert)
,ok 926 (unnamed assert)
,ok 927 (unnamed assert)
,ok 928 (unnamed assert)
,ok 929 (unnamed assert)
,# teardown
,# setup
,# Call start twice and get error
,ok 930 should throw
,# teardown
,# setup
,# Start and make sure it runs
,# teardown
,# setup
,# Make sure getTimeWhenRun is right after start
,ok 931 (unnamed assert)
,# teardown
,# setup
,# Make sure getTimeWhenRun is -1 after function is called
,ok 932 should be equal
# teardown
,# setup
,# Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running
,ok 933 should be equal
,ok 934 should be equal
,ok 935 should throw
,# teardown
,# setup
,# Test TransientState
,ok 936 should throw
ok 937 should throw
ok 938 should be equal
ok 939 should be equal
ok 940 should be equal
ok 941 should be equal
ok 942 (unnamed assert)
,ok 943 (unnamed assert)
,# teardown
,# setup
,# No peers and empty database
,ok 944 verify failed
,ok 945 constructor called once
,ok 946 constructor called with right args
,ok 947 match start arg
,ok 948 start called once
,ok 949 stop called once
,ok 950 stop after start
,# teardown
,# setup
,# One peer and empty DB
,2017-07-18 09:56:33 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 951 verify failed
,ok 952 constructor called once
,ok 953 constructor called with right args
,ok 954 match start arg
,ok 955 start called once
,ok 956 stop called once
,ok 957 stop after start
,# teardown
,# setup
,# One peer with _Local set behind current seq
,2017-07-18 09:56:34 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 958 verify failed
,ok 959 constructor called once
,ok 960 constructor called with right args
,ok 961 match start arg
,ok 962 start called once
,ok 963 stop called once
,ok 964 stop after start
,# teardown
,# setup
,# One peer with _Local set equal to current seq
,2017-07-18 09:56:35 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 965 verify failed
,ok 966 constructor called once
,ok 967 constructor called with right args
,ok 968 match start arg
,ok 969 start called once
,ok 970 stop called once
,ok 971 stop after start
,# teardown
,# setup
,# One peer with _Local set ahead of current seq (and no this should not happen)
,2017-07-18 09:56:36 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 972 verify failed
,ok 973 constructor called once
,ok 974 constructor called with right args
,ok 975 match start arg
,ok 976 start called once
,ok 977 stop called once
,ok 978 stop after start
,# teardown
,# setup
,# Three peers, one not in DB, one behind and one ahead
,2017-07-18 09:56:36 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 979 verify failed
ok 980 constructor called once
,ok 981 constructor called with right args
,ok 982 match start arg
,ok 983 start called once
,ok 984 stop called once
,ok 985 stop after start
,# teardown
,# setup
,# More than maximum peers, make sure we only send maximum allowed
,2017-07-18 09:56:37 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 986 verify failed
,ok 987 constructor called once
,ok 988 constructor called with right args
,ok 989 match start arg
,ok 990 start called once
,ok 991 stop called once
,ok 992 stop after start
,# teardown
,# setup
,# two peers with empty DB, update the doc
,2017-07-18 09:56:37 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,2017-07-18 09:56:37 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 993 verify failed
,ok 994 constructor called once
,ok 995 constructor called with right args
,ok 996 last start before stop
,ok 997 empty first start
,ok 998 full second start
,ok 999 only 2 timers
,# teardown
,# setup
,# add doc and make sure tokens refresh when they expire
,2017-07-18 09:56:38 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,2017-07-18 09:56:38 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,2017-07-18 09:56:38 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 1000 verify failed
,ok 1001 constructor called once
,ok 1002 constructor called with right args
,ok 1003 start before stop
,ok 1004 We got at least 3 calls to start
,ok 1005 at least 3
,ok 1006 default 1
,ok 1007 1 run
,ok 1008 default 2
,ok 1009 2 run
,ok 1010 default 3
,# teardown
,# setup
,# start and stop and start and stop
,ok 1011 start out null
,2017-07-18 09:56:39 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 1012 back to null
,2017-07-18 09:56:39 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 1013 still null
,ok 1014 verify failed
,ok 1015 constructor called once
,ok 1016 constructor called with right args
,ok 1017 first start before first stop
,ok 1018 first stop before second start
,ok 1019 second start before second stop
,# teardown
,# setup
,# two identical starts in a row
,2017-07-18 09:56:40 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 1020 verify failed
,ok 1021 constructor called once
,ok 1022 constructor called with right args
,ok 1023 (unnamed assert)
,# teardown
,# setup
,# two different starts in a row
,2017-07-18 09:56:40 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 1024 verify failed
ok 1025 constructor called once
,ok 1026 constructor called with right args
,ok 1027 (unnamed assert)
,ok 1028 (unnamed assert)
,# teardown
,# setup
,# two stops and a start and two stops
,2017-07-18 09:56:41 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 1029 verify failed
,ok 1030 constructor called once
,ok 1031 constructor called with right args
,ok 1032 start before stop
,# teardown
,# setup
,# we properly enqueue requests so no then needed
,2017-07-18 09:56:41 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 1033 verify failed
,ok 1034 constructor called once
,ok 1035 constructor called with right args
,ok 1036 start before stop
,# teardown
,# setup
,# test calculateSeqPointKeyId
,ok 1037 should be equal
ok 1038 should be equal
,# teardown
,# setup
,# #_doImmediateSeqUpdate - server is not there
,2017-07-18 09:56:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-18 09:56:42 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}'
,ok 1039 Got right error
,# teardown
,2017-07-18 09:56:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - server accepts & closes connection
,2017-07-18 09:56:42 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNRESET","status":500}'
,ok 1040 Got socket hang up
,# teardown
,2017-07-18 09:56:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - server always returns 500
,2017-07-18 09:56:43 - DEBUG localSeqManager: 'Got an error trying to update seq []'
ok 1041 Got 500 as expected
,# teardown
,2017-07-18 09:56:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - create new seq doc
,ok 1042 should be equal
,ok 1043 revs are equal
,# teardown
,2017-07-18 09:56:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - doc exists, need to get rev and update
,ok 1044 should be equal
,ok 1045 revs are equal
,# teardown
,2017-07-18 09:56:46 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - update seq three times
,ok 1046 should be equal
,ok 1047 revs are equal
,ok 1048 should be equal
,ok 1049 revs are equal
,ok 1050 should be equal
,ok 1051 revs are equal
,# teardown
,2017-07-18 09:56:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - rev got changed under us
,(node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
,Trace: 
    at $3.prototype.trace@console.js:139:8
    at addListener@events.js:140:1
    at module.exports@/private/var/containers/Bundle/Application/16C0A5F0-CF84-4126-ACE0-BE4A6E75D474/ThaliTest.app/www/jxcore/node_modules/pouchdb-all-dbs/lib/index.j,s:82:3
    at module.exports/<.start/<@/private/var/containers/Bundle/Application/16C0A5F0-CF84-4126-ACE0-BE4A6E75D474/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/lib/index.js:143:9
    at tryCatcher@/private/var/containers/Bundle/Application/1,6C0A5F0-CF84-4126-ACE0-BE4A6E75D474/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/util.js:16:16
    at module.exports/Promise.prototype._settlePromiseFromHandler@/private/var/containers/Bundle/Application/16C0A5F0-,CF84-4126-ACE0-BE4A6E75D474/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:504:13
,2017-07-18 09:56:50 - DEBUG localSeqManager: 'Got an error trying to update seq {"error":"conflict","reason":"Document update conflict","name":"conflict","status":409,"message":"Document update conflict"}'
,ok 1052 Our rev is old so we should fail
,# teardown
,2017-07-18 09:56:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - fail if stop is called
,ok 1053 confirm stop caused failure
,(node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
,Trace: 
    at $3.prototype.trace@console.js:139:8
    at addListener@events.js:140:1
    at module.exports@/private/var/containers/Bundle/Application/16C0A5F0-CF84-4126-ACE0-BE4A6E75D474/ThaliTest.app/www/jxcore/node_modules/pouchdb-all-dbs/lib/index.j,s:57:3
    at module.exports/<.start/<@/private/var/containers/Bundle/Application/16C0A5F0-CF84-4126-ACE0-BE4A6E75D474/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/lib/index.js:143:9
    at tryCatcher@/private/var/containers/Bundle/Application/1,6C0A5F0-CF84-4126-ACE0-BE4A6E75D474/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/util.js:16:16
    at module.exports/Promise.prototype._settlePromiseFromHandler@/private/var/containers/Bundle/Application/16C0A5F0-,CF84-4126-ACE0-BE4A6E75D474/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:504:13
,# teardown
,2017-07-18 09:56:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - stop after get but before put fails right
,2017-07-18 09:56:52 - DEBUG localSeqManager: 'Got an error trying to update seq {"onPut":true}'
,ok 1054 stop caused us to fail
,ok 1055 We specifically failed on a stop before put
,# teardown
,2017-07-18 09:56:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - fail if stop is called
,ok 1056 failed due to stop
,ok 1057 failed due to stop
,# teardown
,2017-07-18 09:56:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - set seq for first time
,ok 1058 should be equal
,# teardown
,2017-07-18 09:56:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - Fail on bad seq value
,2017-07-18 09:56:57 - DEBUG localSeqManager: 'Got a bad seq, submitted seq 9, _nextSeqValueToSend: 10'
,ok 1059 Expected bad seq error
,# teardown
,2017-07-18 09:56:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - do we cancel timer properly on an immediate?
,ok 1060 Different promises
,ok 1061 Timer was cancelled
,ok 1062 should be equal
,# teardown
,2017-07-18 09:57:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - do we wait for blocked update
,ok 1063 One go and one blocked
,ok 1064 All blocked
,ok 1065 Still blocked
,ok 1066 should be equal
,# teardown
,2017-07-18 09:57:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - test that we wait long enough
,ok 1067 We waited long enough
,ok 1068 should be equal
,# teardown
,2017-07-18 09:57:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - test that we pick up new sequences while we wait
,ok 1069 Should have gotten same timer promise
,ok 1070 Still same timer promise
,ok 1071 We waited long enough
,ok 1072 should be equal
,# teardown
,2017-07-18 09:57:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Coordinated seq test
,2017-07-18 09:57:08 - DEBUG CoordinatedClient: 'test was skipped, name: 'Coordinated seq test''
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-18 09:57:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:57:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,# setup
,# test thali manager spies
,2017-07-18 09:57:09 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
,2017-07-18 09:57:09 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
,2017-07-18 09:57:09 - DEBUG thaliManager: 'creating express pouchdb instance'
,ok 1073 expressPouchDB was called once
,ok 1074 expressPouchDB was called with 2 arguments
,ok 1075 expressPouchDB was called with 'PouchDB' as 1-st argument
,ok 1076 expressPouchDB was called with 'expressPouchDB options' as 2-st argument
,ok 1077 PouchDB was called once
,ok 1078 PouchDB was called with 1 arguments
,ok 1079 PouchDB was called with 'dbName' as 1-st argument
,ok 1080 ThaliSendNotificationBasedOnReplication was called once
,ok 1081 ThaliSendNotificationBasedOnReplication was called with 4 arguments
,ok 1082 ThaliSendNotificationBasedOnReplication was called with 'express.Router instance' as 1-st argument
,ok 1083 ThaliSendNotificationBasedOnReplication was called with 'ecdhForLocalDevice' as 2-st argument
,ok 1084 ThaliSendNotificationBasedOnReplication was called with 'thaliConfig.BEACON_MILLISECONDS_TO_EXPIRE' as 3-st argument
,ok 1085 ThaliSendNotificationBasedOnReplication was called with 'PouchDB instance' as 4-st argument
,ok 1086 ThaliPullReplicationFromNotification was called once
,ok 1087 ThaliPullReplicationFromNotification was called with 4 arguments
,ok 1088 ThaliPullReplicationFromNotification was called with 'PouchDB' as 1-st argument
,ok 1089 ThaliPullReplicationFromNotification was called with 'dbName' as 2-st argument
,ok 1090 ThaliPullReplicationFromNotification was called with 'ThaliPeerPoolInterface instance' as 3-st argument
,ok 1091 ThaliPullReplicationFromNotification was called with 'ecdhForLocalDevice' as 4-st argument
,ok 1092 Salti was called once
,ok 1093 Salti was called with 4 arguments
,ok 1094 Salti was called with 'dbName' as 1-st argument
,ok 1095 Salti was called with 'acl' as 2-st argument
,ok 1096 Salti was called with 'thaliIdCallback' as 3-st argument
,ok 1097 Salti was called with 'options' as 4-st argument
,2017-07-18 09:57:09 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
,2017-07-18 09:57:09 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-07-18 09:57:09 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-07-18 09:57:09 - DEBUG thaliMobileNativeWrapper: 'listening 53714'
2017-07-18 09:57:09 - DEBUG thaliManager: 'start listening for advertisements'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundP,eer:lostPeer:) peer:40D8B392-D097-4FE5-A257-BA72D1381006
[ThaliCore] Browser.startListening
2017-07-18 09:57:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-18 09:5,7:09 - DEBUG thaliManager: 'start update advertising and listening'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "54E70A1B-5D9B-4086-87DD-7470185A73FB", generation: 0)
[ThaliCore] Advertiser.startAdver,tising with peerID:54E70A1B-5D9B-4086-87DD-7470185A73FB
2017-07-18 09:57:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-18 09:57:09 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
,ok 1098 ThaliMobile.start was called once
,ok 1099 ThaliMobile.start was called with 3 arguments
,ok 1100 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
,ok 1101 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
,ok 1102 ThaliMobile.start was called with 'networkType' as 3-st argument
,ok 1103 ThaliMobile.startListeningForAdvertisements was called once
,ok 1104 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
,ok 1105 ThaliMobile.startUpdateAdvertisingAndListening was called once
,ok 1106 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
,ok 1107 ThaliSendNotificationBasedOnReplication.prototype.start was called once
,ok 1108 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
,ok 1109 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
,ok 1110 ThaliPullReplicationFromNotification.prototype.start was called once
,ok 1111 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
,ok 1112 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
,2017-07-18 09:57:09 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:54E70A1B-5D9B-4086-87DD-7470185A73FB
,2017-07-18 09:57:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-18 09:57:09 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})'
2017-07-18 09:57:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state,).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-18 09:57:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:57:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-18 09:57:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 1113 ThaliMobile.stop was called once
,ok 1114 ThaliMobile.stop was called with 0 arguments
,ok 1115 ThaliSendNotificationBasedOnReplication.prototype.stop was called once
,ok 1116 ThaliSendNotificationBasedOnReplication.prototype.stop was called with 0 arguments
,ok 1117 ThaliPullReplicationFromNotification.prototype.stop was called once
,ok 1118 ThaliPullReplicationFromNotification.prototype.stop was called with 0 arguments
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-18 09:57:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:57:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,# teardown
,# setup
,# test thali manager multiple starts and stops
,2017-07-18 09:57:10 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
,2017-07-18 09:57:10 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
,2017-07-18 09:57:10 - DEBUG thaliManager: 'creating express pouchdb instance'
,ok 1119 expressPouchDB was called once
,ok 1120 expressPouchDB was called with 2 arguments
,ok 1121 expressPouchDB was called with 'PouchDB' as 1-st argument
,ok 1122 expressPouchDB was called with 'expressPouchDB options' as 2-st argument
,ok 1123 PouchDB was called once
,ok 1124 PouchDB was called with 1 arguments
,ok 1125 PouchDB was called with 'dbName' as 1-st argument
,ok 1126 ThaliSendNotificationBasedOnReplication was called once
,ok 1127 ThaliSendNotificationBasedOnReplication was called with 4 arguments
,ok 1128 ThaliSendNotificationBasedOnReplication was called with 'express.Router instance' as 1-st argument
,ok 1129 ThaliSendNotificationBasedOnReplication was called with 'ecdhForLocalDevice' as 2-st argument
,ok 1130 ThaliSendNotificationBasedOnReplication was called with 'thaliConfig.BEACON_MILLISECONDS_TO_EXPIRE' as 3-st argument
,ok 1131 ThaliSendNotificationBasedOnReplication was called with 'PouchDB instance' as 4-st argument
,ok 1132 ThaliPullReplicationFromNotification was called once
,ok 1133 ThaliPullReplicationFromNotification was called with 4 arguments
,ok 1134 ThaliPullReplicationFromNotification was called with 'PouchDB' as 1-st argument
,ok 1135 ThaliPullReplicationFromNotification was called with 'dbName' as 2-st argument
,ok 1136 ThaliPullReplicationFromNotification was called with 'ThaliPeerPoolInterface instance' as 3-st argument
,ok 1137 ThaliPullReplicationFromNotification was called with 'ecdhForLocalDevice' as 4-st argument
,ok 1138 Salti was called once
,ok 1139 Salti was called with 4 arguments
,ok 1140 Salti was called with 'dbName' as 1-st argument
,ok 1141 Salti was called with 'acl' as 2-st argument
,ok 1142 Salti was called with 'thaliIdCallback' as 3-st argument
,ok 1143 Salti was called with 'options' as 4-st argument
,2017-07-18 09:57:10 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
,2017-07-18 09:57:10 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-07-18 09:57:10 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-07-18 09:57:10 - DEBUG thaliMobileNativeWrapper: 'listening 53716'
,2017-07-18 09:57:10 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:A77AE45F-296C-4293-AA9B-E31D64713A5C
[ThaliCore] Browser.startListening
,2017-07-18 09:57:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-18 09:57:10 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C864EFE0-4038-4053-82B1-74DFACB7D76F", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:C864EFE0-4038-4053-82B1-74DFACB7D76F
,2017-07-18 09:57:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-18 09:57:10 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
,ok 1144 ThaliMobile.start was called once
,ok 1145 ThaliMobile.start was called with 3 arguments
,ok 1146 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
,ok 1147 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
,ok 1148 ThaliMobile.start was called with 'networkType' as 3-st argument
,ok 1149 ThaliMobile.startListeningForAdvertisements was called once
,ok 1150 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
,ok 1151 ThaliMobile.startUpdateAdvertisingAndListening was called once
,ok 1152 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
,ok 1153 ThaliSendNotificationBasedOnReplication.prototype.start was called once
,ok 1154 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
,ok 1155 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
,ok 1156 ThaliPullReplicationFromNotification.prototype.start was called once
,ok 1157 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
,ok 1158 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
,2017-07-18 09:57:10 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:C864EFE0-4038-4053-82B1-74DFACB7D76F
,2017-07-18 09:57:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-18 09:57:10 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})',
,2017-07-18 09:57:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-18 09:57:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:57:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-18 09:57:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-18 09:57:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:57:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 1159 ThaliMobile.stop was called once
,ok 1160 ThaliMobile.stop was called with 0 arguments
,ok 1161 ThaliSendNotificationBasedOnReplication.prototype.stop was called once
,ok 1162 ThaliSendNotificationBasedOnReplication.prototype.stop was called with 0 arguments
,ok 1163 ThaliPullReplicationFromNotification.prototype.stop was called once
,ok 1164 ThaliPullReplicationFromNotification.prototype.stop was called with 0 arguments
,2017-07-18 09:57:10 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
,2017-07-18 09:57:10 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-07-18 09:57:10 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-07-18 09:57:10 - DEBUG thaliMobileNativeWrapper: 'listening 53718'
,2017-07-18 09:57:10 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C645ADEA-6BA1-43C4-9C68-75F0AD2EA464
,[ThaliCore] Browser.startListening
,2017-07-18 09:57:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-18 09:57:10 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C6B2BEF7-2757-42C0-95FC-AC3ACCF5AFC2", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:C6B2BEF7-2757-42C0-95FC-AC3ACCF5AFC2
,2017-07-18 09:57:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-18 09:57:10 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
,2017-07-18 09:57:10 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:C6B2BEF7-2757-42C0-95FC-AC3ACCF5AFC2
,2017-07-18 09:57:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-18 09:57:10 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})',
,2017-07-18 09:57:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-18 09:57:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:57:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-18 09:57:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-18 09:57:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:57:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-18 09:57:10 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
,2017-07-18 09:57:10 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-07-18 09:57:10 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-07-18 09:57:10 - DEBUG thaliMobileNativeWrapper: 'listening 53720'
,2017-07-18 09:57:10 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:FF4B87D8-A4CE-4C77-9120-DED0B4B34999
,[ThaliCore] Browser.startListening
,2017-07-18 09:57:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-18 09:57:10 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "EC4A18F6-C052-4E93-819C-09D7BAC328B6", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:EC4A18F6-C052-4E93-819C-09D7BAC328B6
,2017-07-18 09:57:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-18 09:57:10 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
,2017-07-18 09:57:10 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:EC4A18F6-C052-4E93-819C-09D7BAC328B6
,2017-07-18 09:57:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-18 09:57:10 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})'
,2017-07-18 09:57:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-18 09:57:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:57:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-18 09:57:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-18 09:57:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:57:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-18 09:57:10 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
,2017-07-18 09:57:10 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-07-18 09:57:10 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-07-18 09:57:10 - DEBUG thaliMobileNativeWrapper: 'listening 53722'
,2017-07-18 09:57:10 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:ED4A2C4D-3E2D-46FB-9CA6-82DF737B0228
,[ThaliCore] Browser.startListening
,2017-07-18 09:57:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-18 09:57:10 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "F18B72BA-EA40-4E3C-9298-DBAC98237B6E", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:F18B72BA-EA40-4E3C-9298-DBAC98237B6E
,2017-07-18 09:57:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-18 09:57:10 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
,ok 1165 ThaliMobile.start was called once
,ok 1166 ThaliMobile.start was called with 3 arguments
,ok 1167 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
,ok 1168 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
,ok 1169 ThaliMobile.start was called with 'networkType' as 3-st argument
,ok 1170 ThaliMobile.startListeningForAdvertisements was called once
,ok 1171 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
,ok 1172 ThaliMobile.startUpdateAdvertisingAndListening was called once
,ok 1173 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
,ok 1174 ThaliSendNotificationBasedOnReplication.prototype.start was called once
,ok 1175 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
,ok 1176 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
,ok 1177 ThaliPullReplicationFromNotification.prototype.start was called once
,ok 1178 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
,ok 1179 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
,2017-07-18 09:57:10 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:F18B72BA-EA40-4E3C-9298-DBAC98237B6E
,2017-07-18 09:57:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-18 09:57:10 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})',
,2017-07-18 09:57:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-18 09:57:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:57:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-18 09:57:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-18 09:57:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:57:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,# teardown
,# setup
,# test write
,2017-07-18 09:57:11 - DEBUG CoordinatedClient: 'test was skipped, name: 'test write''
,# teardown
,# setup
,# test repeat write 1
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll can close even when connections open'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll with promise'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning set to false'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll works even with a server that is not listening yet witheatNotRunning set to true'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on a single db change'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of multiple onCheckpointReached handlers on a single db change'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultDirectory'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultAdapter'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueue and run in order'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueueAtTop and run backwards'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - mix enqueue and enqueueAtTop'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - queues handled independently'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueued function are always executed asynchronously'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - exceptions in the executor are properly handled'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - basic'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - another'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - skip'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - another skip'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox spy'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub override'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox mock'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox restore after test end'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can pass data in setup'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Correctly parses/stringifies USN'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerLost calls jxcore'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerDiscovered calls jxcore'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopListeningForAdvertisements'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startListeningForAdvertisements twice is NOT an error'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling stopListeningForAdvertisements without calling start is NOT an error'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopUpdateAdvertisingAndListening'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startUpdateAdvertisingAndListening twice is NOT an error'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call stopUpdateAdvertisingAndListening twice without start and it is not an error'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChange is called'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can connect to a remote peer'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data via parallel connections'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data securely'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift large amounts of data'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We do not emit peerAvailabilityChanged events until one of the start methods is called'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Test updating advertising and parallel data transfer'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - discoveryAdvertisingStateUpdateNonTCP is called'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - cannot call connect when start listening for advertisements is not active'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Get error when trying to double connect to a peer on Android'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect when start listening for advertisements is not active'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with illegal peerID'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiConnect properly fails on legal but non-existent peerID'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with invalid syncValue'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call disconnect with invalid peer id'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - disconnect doesn't fail on plausible but bogus peer ID'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Get same port when trying to connect multiple times on iOS'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - initial peer discovery'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 1'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 2'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - check latest peer discovery'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Set up for no peer discovery test'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - no peer discovery'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling createNativeListener directly rejects'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits incomingConnectionState'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits routerPortConnectionFailed'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server connections all up'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming stream cleans outgoing socket'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming connection cleans outgoing socket'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing outgoing socket cleans associated mux stream'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing the whole server cleans everything up'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - we can get a ton of connections and data through and still clean up the server completely'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - simulate mux failure, make sure everything is cleaned up'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - timing out the incoming connection cleans everything up'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can create servers manager'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling stop without start causes error'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can start/stop servers manager'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - starting twice resolves with listening port'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminateIncomingConnection will terminate a connection'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminate an Outgoing connection'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single local http request'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single coordinated request ios native'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Multiple local http requests'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Multiple coordinated request ios native'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startListeningForAdvertisements should fail if start not called'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if start not called'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopListeningForAdvertisements many times'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startListeningForAdvertisements many times'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startUpdateAdvertisingAndListening many times'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopAdvertisingAndListening many times'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get the network status before starting'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - error returned with bad router'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - all services are started when we call start'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - TCP Servers Manager should be null when we call start on iOS'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - all services are stopped when we call stop'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure terminateConnection is properly hooked up'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure terminateConnection is return error if we get called on iOS'
2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure terminateListen,er is properly hooked up'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure terminateListener is return error if we get called on iOS'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure we actually call kill connections properly'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire failedNativeConnection event when we get failedConnection from multiConnectConnection'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure bad PSK connections fail'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - peer changes handled from a queue'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - relaying discoveryAdvertisingStateUpdateNonTCP'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - we successfully receive and replay discoveryAdvertisingStateUpdate'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can do HTTP requests between peers'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can still do HTTP requests between peers with coordinator'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - calls correct starts when network changes'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test to coordinate connection cut'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can do HTTP requests after connections are cut'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - will fail bad PSK connection between peers'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We provide notification when a listener dies and we recreate it'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startListeningForAdvertisements should fail if start not called'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if start not called'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopListeningForAdvertisements many times'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startListeningForAdvertisements many times'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startUpdateAdvertisingAndListening many times'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopAdvertisingAndListening many times'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #start - Causing native or wifi to fail will cause a promise reject '
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #start should fail if called twice in a row'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - does not emit duplicate discoveryAdvertisingStateUpdate'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - does not send duplicate availability changes'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get the network status'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer added/removed to/from cache (native)'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer added/removed to/from cache (wifi)'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - new peer is cached'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - native available - peer with same port and different generation is cached (BLUETOOTH)'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - peer with greater generation is cached (MPCF)'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - peer with same or older generation is ignored (MPCF)'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native unavailable - new peer is ignored'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native unavailable - cached peer is removed'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - networkChanged - fires peerAvailabilityChanged event for wifi peers'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiconnect failure - new peer is ignored (MPCF)'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - newAddressPort field (TCP_NATIVE)'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - newAddressPort field (BLUETOOTH)'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - newAddressPort field (MPCF)'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - error when peer has not been discovered yet'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - returns discovered cached wifi peer'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #disconnect fails on wifi peers'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #disconnect delegates native peers to the native wrapper'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes emitted correctly'
2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes not emitted in started state'
2017-07-18 09,:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes not emitted in stopped state'
2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We properly fire peer unavailable and then available when conn,ection fails on Android'
2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We properly fire peer unavailable and then available when connection fails on iOS'
2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER resu,lt: skipped - If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen'
2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - does not fire, duplicate events after peer listener recreation'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #stop should change peers'
2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - If there are more then PEERS_LIMIT peers presented then `discoveryDOS`, event should be emitted'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - peer should be found once after listening and discovery started'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get data from all participants'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - test for data corruption'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - test getters'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - start and kill'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - double start'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - start after kill'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - make sure ids are unique'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - check that forever agent can be destroyed'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test PeerDictionary basic functionality'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test PeerDictionary with multiple entries.'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - RESOLVED entries are removed before WAITING state entry.'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - WAITING entries are removed before CONTROLLED_BY_POOL state entry.'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - When CONTROLLED_BY_POOL entry is removed and kill is called.'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - single action'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - multiple actions'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - PSK Pool works'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - stop'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure that start verifies queue length'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - bad enqueues'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - do not allow same object type'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure we catch kill and dequeue'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure that stop removes all actions'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We reject unrecognized connection type'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We reject unrecognized action type'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - One action on bluetooth'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Two notification actions'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - replicateThroughProblems'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Replication goes first'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - wifi allows many parallel non-replication actions'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - wifi allows no more than 2 simultaneous replication actions for same peerID'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Client to server request coordinated'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test BEACONS_RETRIEVED_AND_PARSED locally'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test HTTP_BAD_RESPONSE locally'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test NETWORK_PROBLEM locally'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Action fails when getPeerHostInfo fails'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the start two times'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill before calling the start'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill immediately after the start'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill while waiting a response from the server'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test to exceed the max content size locally'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Close the server socket while the client is waiting a response from the server. Local test.'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Close the client socket while the client is waiting a response from the server. Local test.'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons bad args'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons empty keys to notify'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons multiple keys to notify'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid expiration in beaconStreamWithPreAmble'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons expiration out of range lower'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons expiration out of range lower'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons no beacons returns null'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback fails decrypt'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns no matches'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns spurious match'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns public key'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskIdentityField'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskSecret'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskSecrets'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generateBeaconStreamAndSecrets'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Add two Peers.'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - TCP_NATIVE peer loses DNS'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Received beacons with no values for us'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Notification action killed with a superseded'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Resolves an action locally'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Emits error event when peerPool.enqueue throws'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Resolves an action locally using ThaliPeerPoolDefault'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Action fails because of a bad hostname.'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - hostaddress is removed when the action is running. '
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - notificationClient does not retry action with BAD_PEER resolution'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - notification client correctly handles peer availability changes of the same peer'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Client to server request locally'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache clean and expiration'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache getSecret and getPublic'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache multiple entries'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Start and stop ThaliNotificationServer'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass an empty array to ThaliNotificationServer.start'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass a string to ThaliNotificationServer.start'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass an empty parameter to ThaliNotificationServer.start'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeacons'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeacons (no keys)'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeaconsbefore calling start'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure peerDictionaryKey is reasonable'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure start works'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure stop works'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Emits error event when peerPool.enqueue throws'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Simple peer event'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Coordinated pull replication from notification test'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server is not there'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server accepts & closes connection'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server always returns 500'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server always returns 401'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server always returns 403'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure docs replicate with remote db with same name as local db'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure docs replicate with remote db with different name than local db'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Do nothing and make sure we time out'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Do something and make sure we time out'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Start replicating and then catch error when server goes'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure clone works'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Coordinated replication action test - each device has the same local db name'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Coordinated replication action test - each device has different local db name'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Coordinated replication action test - should throw error when wrong remote db name is provided'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - compareBufferArrays'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call start twice and get error'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Start and make sure it runs'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure getTimeWhenRun is right after start'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure getTimeWhenRun is -1 after function is called'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test TransientState'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - No peers and empty database'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - One peer and empty DB'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - One peer with _Local set behind current seq'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - One peer with _Local set equal to current seq'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - One peer with _Local set ahead of current seq (and no this should not happen)'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Three peers, one not in DB, one behind and one ahead'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - More than maximum peers, make sure we only send maximum allowed'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - two peers with empty DB, update the doc'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - add doc and make sure tokens refresh when they expire'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - start and stop and start and stop'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - two identical starts in a row'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - two different starts in a row'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - two stops and a start and two stops'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - we properly enqueue requests so no then needed'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test calculateSeqPointKeyId'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - server is not there'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - server accepts & closes connection'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - server always returns 500'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - create new seq doc'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - doc exists, need to get rev and update'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - update seq three times'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - rev got changed under us'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - fail if stop is called'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - stop after get but before put fails right'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #update - fail if stop is called'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #update - set seq for first time'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #update - Fail on bad seq value'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #update - do we cancel timer properly on an immediate?'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #update - do we wait for blocked update'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #update - test that we wait long enough'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #update - test that we pick up new sequences while we wait'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Coordinated seq test'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test thali manager spies'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test thali manager multiple starts and stops'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - test write'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: failed - test repeat write 1, error: 'TypeError: thaliManager is undefined', stack: 'testRepeatWrite/<@/private/var/containers/Bundle/Application/16C0A5F0-CF84-4126-ACE0-BE4A6E75D474/Tha,liTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js:279:7
CoordinatedClient.prototype._processEvent/</<@/private/var/containers/Bundle/Application/16C0A5F0-CF84-4126-ACE0-BE4A6E75D474/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:471:9
canc,ellationExecute@/private/var/containers/Bundle/Application/16C0A5F0-CF84-4126-ACE0-BE4A6E75D474/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/debuggability.js:320:9
module.exports/Promise.prototype._resolveFromExecutor@/private/var/containers/,Bundle/Application/16C0A5F0-CF84-4126-ACE0-BE4A6E75D474/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:481:13
Promise@/private/var/containers/Bundle/Application/16C0A5F0-CF84-4126-ACE0-BE4A6E75D474/ThaliTest.app/www/jxcore/node_modul,es/bluebird/js/release/promise.js:77:9
CoordinatedClient.prototype._processEvent/<@/private/var/containers/Bundle/Application/16C0A5F0-CF84-4126-ACE0-BE4A6E75D474/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:428:14
tryCatcher@/private/var/containers,/Bundle/Application/16C0A5F0-CF84-4126-ACE0-BE4A6E75D474/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/util.js:16:16
module.exports/Promise.prototype._settlePromiseFromHandler@/private/var/containers/Bundle/Application/16C0A5F0-CF84-4126-ACE0-,BE4A6E75D474/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:510:13
module.exports/Promise.prototype._settlePromise@/private/var/containers/Bundle/Application/16C0A5F0-CF84-4126-ACE0-BE4A6E75D474/ThaliTest.app/www/jxcore/node_modules/,bluebird/js/release/promise.js:567:13
module.exports/Promise.prototype._settlePromise0@/private/var/containers/Bundle/Application/16C0A5F0-CF84-4126-ACE0-BE4A6E75D474/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:612:5
module.expor,ts/Promise.prototype._settlePromises@/private/var/containers/Bundle/Application/16C0A5F0-CF84-4126-ACE0-BE4A6E75D474/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:691:13
Async.prototype._drainQueue@/private/var/containers/Bundle/App,lication/16C0A5F0-CF84-4126-ACE0-BE4A6E75D474/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/async.js:138:13
Async.prototype._drainQueues@/private/var/containers/Bundle/Application/16C0A5F0-CF84-4126-ACE0-BE4A6E75D474/ThaliTest.app/www/jxcore/n,ode_modules/bluebird/js/release/async.js:148:5
Async/this.drainQueues@/private/var/containers/Bundle/Application/16C0A5F0-CF84-4126-ACE0-BE4A6E75D474/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/async.js:17:9
$v@timers.js:364:1
''
,2017-07-18 09:57:11 - ERROR CoordinatedClient: 'failed to run unit tests, platformName: 'ios''
,2017-07-18 10:00:11 - DEBUG CoordinatedClient: 'all tests completed'
,2017-07-18 10:00:11 - DEBUG CoordinatedClient: 'test client disconnected'
,2017-07-18 10:00:11 - DEBUG CoordinatedClient: 'test client failed'
,2017-07-18 10:00:11 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: TimeoutError: timeout exceeded, event: 'run_test repeat write 1_finished', test: 'test repeat write 1'', stack: 'CoordinatedClient.prototype._customError@/private/var/container,s/Bundle/Application/16C0A5F0-CF84-4126-ACE0-BE4A6E75D474/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:292:27
Emitter.prototype.emit@/private/var/containers/Bundle/Application/16C0A5F0-CF84-4126-ACE0-BE4A6E75D474/ThaliTest.app/www/jxcore/node_modules,/component-emitter/index.js:131:7
Socket.prototype.onevent@/private/var/containers/Bundle/Application/16C0A5F0-CF84-4126-ACE0-BE4A6E75D474/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:263:5
Socket.prototype.onpacket@/private/var/c,ontainers/Bundle/Application/16C0A5F0-CF84-4126-ACE0-BE4A6E75D474/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:221:7
module.exports/<@/private/var/containers/Bundle/Application/16C0A5F0-CF84-4126-ACE0-BE4A6E75D474/ThaliTest.app/ww,w,/jxcore/node_modules/component-bind/index.js:21:12
Emitter.prototype.emit@/private/var/containers/Bundle/Application/16C0A5F0-CF84-4126-ACE0-BE4A6E75D474/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7''
,2017-07-18 10:00:11 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'

```
